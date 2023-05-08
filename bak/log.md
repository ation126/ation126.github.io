# 20230508 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46677
self.closeSec=1683533999, self.tradeDate='20230508', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27871.7, self.close=27915.2, self.high=27927.0, self.low=27866.1, self.vol=2347.704, self.amt=65513527.1617 
127.0.0.1 - - [08/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-08 16:20:06,449:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230508   155500    155959  ...         0.0        0.0       0
5952  20230508   160000    160459  ...         0.0        0.0       0
5953  20230508   160500    160959  ...         0.0        0.0       0
5954  20230508   161000    161459  ...         0.0        0.0       0
5955  20230508   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 16:20:06,453:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683533999, self.tradeDate='20230508', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27871.7, self.close=27915.2, self.high=27927.0, self.low=27866.1, self.vol=2347.704, self.amt=65513527.1617, ukdf['pct'].iloc[-1]=0.001561 , ukdf['amount'].iloc[-1]=65513527.1617, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-685249.65098083776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27916.72440476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46678
self.closeSec=1683534299, self.tradeDate='20230508', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27915.2, self.close=27920.0, self.high=27920.0, self.low=27871.1, self.vol=1751.06, self.amt=48862167.2859 
127.0.0.1 - - [08/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-05-08 16:25:02,119:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230508   160000    160459  ...         0.0        0.0       0
5953  20230508   160500    160959  ...         0.0        0.0       0
5954  20230508   161000    161459  ...         0.0        0.0       0
5955  20230508   161500    161959  ...         0.0        0.0       0
5956  20230508   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 16:25:02,119:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683534299, self.tradeDate='20230508', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27915.2, self.close=27920.0, self.high=27920.0, self.low=27871.1, self.vol=1751.06, self.amt=48862167.2859, ukdf['pct'].iloc[-1]=0.000172 , ukdf['amount'].iloc[-1]=48862167.2859, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-685450.58843547296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27920.06356746', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [08/May/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47239 

self.closeSec=1683532799, self.tradeDate='20230508', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27935.6, self.close=27957.8, self.high=27978.8, self.low=27925.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47240 

self.closeSec=1683533099, self.tradeDate='20230508', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27957.7, self.close=27935.1, self.high=27977.6, self.low=27906.0 
127.0.0.1 - - [08/May/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47241 

self.closeSec=1683533399, self.tradeDate='20230508', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27937.6, self.close=27842.6, self.high=27944.7, self.low=27835.9 
127.0.0.1 - - [08/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47242 

self.closeSec=1683533699, self.tradeDate='20230508', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27842.6, self.close=27871.7, self.high=27924.9, self.low=27827.0 
127.0.0.1 - - [08/May/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47243 

self.closeSec=1683533999, self.tradeDate='20230508', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27871.7, self.close=27915.2, self.high=27927.0, self.low=27866.1 
127.0.0.1 - - [08/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 16:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47244 

self.closeSec=1683534299, self.tradeDate='20230508', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27915.2, self.close=27920.0, self.high=27920.0, self.low=27871.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-08 16:00:20,136:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230508    132959  28110.2  ...  50.000000  0.386137  0.720141
5786  20230508    135959  28172.4  ...  50.416667  0.401768  0.723864
5787  20230508    142959  28243.8  ...  50.000000  0.398837  0.728576
5788  20230508    145959  28223.5  ...  49.583333  0.389448  0.736980
5789  20230508    152959  28158.2  ...  49.166667  0.382949  0.747653

[5 rows x 33 columns]
0.5535055350553506
acc is : 0.5535055350553506
2023-05-08 16:00:20,224:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.505487  0.494513       1  ...  0.945721  -1.0    0.0  0.966753
538     0  0.522279  0.477721       0  ...  0.946397  -1.0    0.0  0.966062
539     0  0.502666  0.497334       0  ...  0.948590  -1.0    0.0  0.963824
540     1  0.493535  0.506465       0  ...  0.950146  -1.0    0.0  0.962242
541     1  0.498839  0.501161       0  ...  0.955358  -1.0    0.0  0.956964

[5 rows x 10 columns]
2023-05-08 16:00:20,236:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505202  0.494798       1  ...  0.931041  -1.0    0.0  0.998642
46     0  0.521888  0.478112       0  ...  0.931707  -1.0    0.0  0.995187
47     0  0.502475  0.497525       0  ...  0.914214  -1.0    0.0  0.991629
48     1  0.493130  0.506870       0  ...  0.915714  -1.0    0.0  0.956460
49     1  0.498839  0.501161       0  ...  0.955358  -1.0    0.0  0.956964

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23617 

self.closeSec=1683530999, self.tradeDate='20230508', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28093.2', self.close='28112'
127.0.0.1 - - [08/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23618 

self.closeSec=1683531599, self.tradeDate='20230508', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28111.9', self.close='28067.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23619 

self.closeSec=1683532199, self.tradeDate='20230508', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28067.5', self.close='27890.1'
127.0.0.1 - - [08/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23620 

self.closeSec=1683532799, self.tradeDate='20230508', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27890', self.close='27957.8'
127.0.0.1 - - [08/May/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23621 

self.closeSec=1683533399, self.tradeDate='20230508', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27957.7', self.close='27842.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23622 

self.closeSec=1683533999, self.tradeDate='20230508', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27842.6', self.close='27915.2'
127.0.0.1 - - [08/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23618 

self.closeSec=1683530999, self.tradeDate='20230508', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28093.2', self.close='28112'
127.0.0.1 - - [08/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23619 

self.closeSec=1683531599, self.tradeDate='20230508', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28111.9', self.close='28067.5'
127.0.0.1 - - [08/May/2023 15:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23620 

self.closeSec=1683532199, self.tradeDate='20230508', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28067.5', self.close='27890.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23621 

self.closeSec=1683532799, self.tradeDate='20230508', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27890', self.close='27957.8'
127.0.0.1 - - [08/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23622 

self.closeSec=1683533399, self.tradeDate='20230508', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27957.7', self.close='27842.6'
127.0.0.1 - - [08/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23623 

self.closeSec=1683533999, self.tradeDate='20230508', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27842.6', self.close='27915.2'
127.0.0.1 - - [08/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [08/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23618 

self.closeSec=1683530999, self.tradeDate='20230508', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28093.2', self.close='28112'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23619 

self.closeSec=1683531599, self.tradeDate='20230508', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28111.9', self.close='28067.5'
127.0.0.1 - - [08/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23620 

self.closeSec=1683532199, self.tradeDate='20230508', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28067.5', self.close='27890.1'
127.0.0.1 - - [08/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23621 

self.closeSec=1683532799, self.tradeDate='20230508', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27890', self.close='27957.8'
127.0.0.1 - - [08/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23622 

self.closeSec=1683533399, self.tradeDate='20230508', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27957.7', self.close='27842.6'
127.0.0.1 - - [08/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23623 

self.closeSec=1683533999, self.tradeDate='20230508', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27842.6', self.close='27915.2'
127.0.0.1 - - [08/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42675
self.closeSec=1683533999, self.tradeDate='20230508', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27871.7, self.close=27915.2, self.high=27927.0, self.low=27866.1, self.vol=2347.704, self.amt=65513527.1617 
127.0.0.1 - - [08/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-08 16:20:06,447:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230508   155500    155959  ...         0.0        0.0       0
5952  20230508   160000    160459  ...         0.0        0.0       0
5953  20230508   160500    160959  ...         0.0        0.0       0
5954  20230508   161000    161459  ...         0.0        0.0       0
5955  20230508   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 16:20:06,455:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683533999, self.tradeDate='20230508', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27871.7, self.close=27915.2, self.high=27927.0, self.low=27866.1, self.vol=2347.704, self.amt=65513527.1617, ukdf['pct'].iloc[-1]=0.001561 , ukdf['amount'].iloc[-1]=65513527.1617, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42676
self.closeSec=1683534299, self.tradeDate='20230508', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27915.2, self.close=27920.0, self.high=27920.0, self.low=27871.1, self.vol=1751.06, self.amt=48862167.2859 
2023-05-08 16:25:02,106:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230508   160000    160459  ...         0.0        0.0       0
5953  20230508   160500    160959  ...         0.0        0.0       0
5954  20230508   161000    161459  ...         0.0        0.0       0
5955  20230508   161500    161959  ...         0.0        0.0       0
5956  20230508   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 16:25:02,107:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683534299, self.tradeDate='20230508', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27915.2, self.close=27920.0, self.high=27920.0, self.low=27871.1, self.vol=1751.06, self.amt=48862167.2859, ukdf['pct'].iloc[-1]=0.000172 , ukdf['amount'].iloc[-1]=48862167.2859, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230508   040000    075959  1683503999  ...    721  0.129701 -1.323498    -1.0
722  20230508   080000    115959  1683518399  ...    722  0.264857 -0.891031    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '54128.22232584158', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28182.68399919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=984
self.closeSec=1683532799, self.tradeDate='20230508', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28188.1, self.close=27957.8, self.high=28249.0, self.low=27800.0, self.vol=82354.151, self.amt=2312412362.18719 
2023-05-08 16:00:02,565:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683532799, self.tradeDate='20230508', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28188.1, self.close=27957.8, self.high=28249.0, self.low=27800.0, self.vol=82354.151, self.amt=2312412362.18719 
127.0.0.1 - - [08/May/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-05-08 16:00:02,618:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230507   200000    235959  ...   58996.190  1.707798e+09  0.003698
720  20230508   000000    035959  ...   46812.975  1.352144e+09 -0.001351
721  20230508   040000    075959  ...   66956.679  1.920791e+09 -0.016426
722  20230508   080000    115959  ...  142837.352  4.040366e+09 -0.008142
723  20230508   120000    155959  ...   82354.151  2.312412e+09 -0.008167

[5 rows x 11 columns]
2023-05-08 16:00:03,940:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230507   200000    235959  1683475199  ...    719  0.210014 -1.138046    -1.0
720  20230508   000000    035959  1683489599  ...    720  0.147027 -1.300751    -1.0
721  20230508   040000    075959  1683503999  ...    721  0.129701 -1.323498    -1.0
722  20230508   080000    115959  1683518399  ...    722  0.264857 -0.891031    -1.0
723  20230508   120000    155959  1683532799  ...    723  0.391871 -0.483625     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '64682.59471130744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27956.76738492', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


