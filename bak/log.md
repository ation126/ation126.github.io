# 20231017 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44980
self.closeSec=1697530799, self.tradeDate='20231017', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28442.0, self.close=28376.8, self.high=28453.5, self.low=28375.3, self.vol=2240.522, self.amt=63632734.4902 
127.0.0.1 - - [17/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -
2023-10-17 16:20:17,715:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231017   155500    155959  ...         0.0        0.0       0
5952  20231017   160000    160459  ...         0.0        0.0       0
5953  20231017   160500    160959  ...         0.0        0.0       0
5954  20231017   161000    161459  ...         0.0        0.0       0
5955  20231017   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 16:20:17,734:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697530799, self.tradeDate='20231017', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28442.0, self.close=28376.8, self.high=28453.5, self.low=28375.3, self.vol=2240.522, self.amt=63632734.4902, ukdf['pct'].iloc[-1]=-0.002296 , ukdf['amount'].iloc[-1]=63632734.4902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-21238.5426', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28390', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44981
self.closeSec=1697531099, self.tradeDate='20231017', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28376.9, self.close=28387.1, self.high=28403.1, self.low=28375.0, self.vol=933.114, self.amt=26490287.4431 
127.0.0.1 - - [17/Oct/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-10-17 16:25:03,509:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231017   160000    160459  ...         0.0        0.0       0
5953  20231017   160500    160959  ...         0.0        0.0       0
5954  20231017   161000    161459  ...         0.0        0.0       0
5955  20231017   161500    161959  ...         0.0        0.0       0
5956  20231017   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 16:25:03,518:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697531099, self.tradeDate='20231017', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28376.9, self.close=28387.1, self.high=28403.1, self.low=28375.0, self.vol=933.114, self.amt=26490287.4431, ukdf['pct'].iloc[-1]=0.000363 , ukdf['amount'].iloc[-1]=26490287.4431, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-21210.57031612464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28387.99136264', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [17/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44978 

self.closeSec=1697529599, self.tradeDate='20231017', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28452.6, self.close=28407.4, self.high=28452.8, self.low=28389.1 
127.0.0.1 - - [17/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44979 

self.closeSec=1697529899, self.tradeDate='20231017', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28408.1, self.close=28465.9, self.high=28466.0, self.low=28377.0 
127.0.0.1 - - [17/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44980 

self.closeSec=1697530199, self.tradeDate='20231017', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28465.9, self.close=28469.6, self.high=28509.4, self.low=28462.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44981 

self.closeSec=1697530499, self.tradeDate='20231017', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28470.9, self.close=28442.1, self.high=28488.1, self.low=28440.0 
127.0.0.1 - - [17/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44982 

self.closeSec=1697530799, self.tradeDate='20231017', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28442.0, self.close=28376.8, self.high=28453.5, self.low=28375.3 
127.0.0.1 - - [17/Oct/2023 16:20:10] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44983 

self.closeSec=1697531099, self.tradeDate='20231017', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28376.9, self.close=28387.1, self.high=28403.1, self.low=28375.0 
127.0.0.1 - - [17/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-17 16:00:17,178:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231017    132959  28175.0  ...  50.833333  0.552419  0.680903
5786  20231017    135959  28192.9  ...  50.833333  0.554441  0.690153
5787  20231017    142959  28212.0  ...  50.416667  0.541807  0.700913
5788  20231017    145959  28114.4  ...  50.833333  0.552500  0.708771
5789  20231017    152959  28214.7  ...  50.833333  0.551558  0.716261

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-10-17 16:00:17,240:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495071  0.504929       1  ...  0.950027   1.0    0.0  1.027909
538     0  0.502297  0.497703       0  ...  0.946741   1.0    0.0  1.024353
539     1  0.462588  0.537412       1  ...  0.950118   1.0    0.0  1.028008
540     0  0.529430  0.470570       0  ...  0.949876   1.0    0.0  1.027745
541     0  0.500513  0.499487       1  ...  0.956631   1.0    0.0  1.035054

[5 rows x 10 columns]
2023-10-17 16:00:17,251:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495075  0.504925       1  ...  0.950027   1.0    0.0  1.028801
46     0  0.502725  0.497275       0  ...  0.946741   1.0    0.0  1.026414
47     1  0.462576  0.537424       1  ...  0.950118   1.0    0.0  1.029797
48     0  0.529533  0.470467       0  ...  0.949876   1.0    0.0  1.027906
49     0  0.500513  0.499487       1  ...  0.956631   1.0    0.0  1.035054

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '22.687', 'enterprice': '28423.9', 'countrevence': '0', 'unrealprofit': '-954.31506979753', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28381.83559881', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22487 

self.closeSec=1697527799, self.tradeDate='20231017', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28243.5', self.close='28207.6'
127.0.0.1 - - [17/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22488 

self.closeSec=1697528399, self.tradeDate='20231017', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28207.7', self.close='28236.3'
127.0.0.1 - - [17/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22489 

self.closeSec=1697528999, self.tradeDate='20231017', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28236.4', self.close='28374.9'
127.0.0.1 - - [17/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22490 

self.closeSec=1697529599, self.tradeDate='20231017', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28379.2', self.close='28407.4'
127.0.0.1 - - [17/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22491 

self.closeSec=1697530199, self.tradeDate='20231017', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28408.1', self.close='28469.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22492 

self.closeSec=1697530799, self.tradeDate='20231017', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28470.9', self.close='28376.8'
127.0.0.1 - - [17/Oct/2023 16:20:14] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [17/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22490 

self.closeSec=1697527799, self.tradeDate='20231017', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28243.5', self.close='28207.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22491 

self.closeSec=1697528399, self.tradeDate='20231017', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28207.7', self.close='28236.3'
127.0.0.1 - - [17/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22492 

self.closeSec=1697528999, self.tradeDate='20231017', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28236.4', self.close='28374.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22493 

self.closeSec=1697529599, self.tradeDate='20231017', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28379.2', self.close='28407.4'
127.0.0.1 - - [17/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22494 

self.closeSec=1697530199, self.tradeDate='20231017', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28408.1', self.close='28469.6'
127.0.0.1 - - [17/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22495 

self.closeSec=1697530799, self.tradeDate='20231017', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28470.9', self.close='28376.8'
127.0.0.1 - - [17/Oct/2023 16:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [17/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22490 

self.closeSec=1697527799, self.tradeDate='20231017', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28243.5', self.close='28207.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22491 

self.closeSec=1697528399, self.tradeDate='20231017', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28207.7', self.close='28236.3'
127.0.0.1 - - [17/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22492 

self.closeSec=1697528999, self.tradeDate='20231017', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28236.4', self.close='28374.9'
127.0.0.1 - - [17/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22493 

self.closeSec=1697529599, self.tradeDate='20231017', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28379.2', self.close='28407.4'
127.0.0.1 - - [17/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22494 

self.closeSec=1697530199, self.tradeDate='20231017', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28408.1', self.close='28469.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22495 

self.closeSec=1697530799, self.tradeDate='20231017', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28470.9', self.close='28376.8'
127.0.0.1 - - [17/Oct/2023 16:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44980
self.closeSec=1697530799, self.tradeDate='20231017', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28442.0, self.close=28376.8, self.high=28453.5, self.low=28375.3, self.vol=2240.522, self.amt=63632734.4902 
127.0.0.1 - - [17/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -
2023-10-17 16:20:17,695:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231017   155500    155959  ...         0.0        0.0       0
5952  20231017   160000    160459  ...         0.0        0.0       0
5953  20231017   160500    160959  ...         0.0        0.0       0
5954  20231017   161000    161459  ...         0.0        0.0       0
5955  20231017   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 16:20:17,724:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697530799, self.tradeDate='20231017', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28442.0, self.close=28376.8, self.high=28453.5, self.low=28375.3, self.vol=2240.522, self.amt=63632734.4902, ukdf['pct'].iloc[-1]=-0.002296 , ukdf['amount'].iloc[-1]=63632734.4902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '57419.986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28390', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44981
self.closeSec=1697531099, self.tradeDate='20231017', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28376.9, self.close=28387.1, self.high=28403.1, self.low=28375.0, self.vol=933.114, self.amt=26490287.4431 
127.0.0.1 - - [17/Oct/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-10-17 16:25:03,505:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231017   160000    160459  ...         0.0        0.0       0
5953  20231017   160500    160959  ...         0.0        0.0       0
5954  20231017   161000    161459  ...         0.0        0.0       0
5955  20231017   161500    161959  ...         0.0        0.0       0
5956  20231017   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 16:25:03,508:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697531099, self.tradeDate='20231017', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28376.9, self.close=28387.1, self.high=28403.1, self.low=28375.0, self.vol=933.114, self.amt=26490287.4431, ukdf['pct'].iloc[-1]=0.000363 , ukdf['amount'].iloc[-1]=26490287.4431, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '57345.38319981224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28387.99136264', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231017   040000    075959  1697500799  ...    721  1.974534  2.149736     1.0
722  20231017   080000    115959  1697515199  ...    722  1.538501  1.403763     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '18328.57930842162', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28259.30339927', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=937
self.closeSec=1697529599, self.tradeDate='20231017', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28259.9, self.close=28408.2, self.high=28452.8, self.low=28055.0, self.vol=53558.993, self.amt=1511651500.67703 
127.0.0.1 - - [17/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-17 16:00:01,530:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697529599, self.tradeDate='20231017', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28259.9, self.close=28408.2, self.high=28452.8, self.low=28055.0, self.vol=53558.993, self.amt=1511651500.67703 
2023-10-17 16:00:01,543:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231016   200000    235959  ...  460426.856  1.314773e+10  0.011432
720  20231017   000000    035959  ...   99392.957  2.822350e+09  0.014187
721  20231017   040000    075959  ...   45745.440  1.300854e+09  0.001202
722  20231017   080000    115959  ...   36124.470  1.023821e+09 -0.007965
723  20231017   120000    155959  ...   53558.993  1.511652e+09  0.005266

[5 rows x 11 columns]
2023-10-17 16:00:02,227:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231016   200000    235959  1697471999  ...    719  4.305991  6.740435     1.0
720  20231017   000000    035959  1697486399  ...    720  2.848707  3.703573     1.0
721  20231017   040000    075959  1697500799  ...    721  1.974534  2.149736     1.0
722  20231017   080000    115959  1697515199  ...    722  1.538501  1.403763     1.0
723  20231017   120000    155959  1697529599  ...    723  1.401377  1.162817     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '24851.1438', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28408.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


