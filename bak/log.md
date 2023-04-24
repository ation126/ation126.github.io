# 20230424 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  127.0.0.1 - - [24/Apr/2023 16:20:01] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42645
self.closeSec=1682324399, self.tradeDate='20230424', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27493.2, self.close=27463.2, self.high=27493.2, self.low=27463.0, self.vol=1413.537, self.amt=38837999.463 
2023-04-24 16:20:02,366:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230424   155500    155959  ...         0.0        0.0       0
5945  20230424   160000    160459  ...         0.0        0.0       0
5946  20230424   160500    160959  ...         0.0        0.0       0
5947  20230424   161000    161459  ...         0.0        0.0       0
5948  20230424   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 16:20:02,376:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682324399, self.tradeDate='20230424', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27493.2, self.close=27463.2, self.high=27493.2, self.low=27463.0, self.vol=1413.537, self.amt=38837999.463, ukdf['pct'].iloc[-1]=-0.001091 , ukdf['amount'].iloc[-1]=38837999.463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-658027.48474435792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27464.34860317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42646
self.closeSec=1682324699, self.tradeDate='20230424', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27463.2, self.close=27384.5, self.high=27467.2, self.low=27382.0, self.vol=2632.37, self.amt=72164023.2651 
2023-04-24 16:25:01,561:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230424   160000    160459  ...         0.0        0.0       0
5946  20230424   160500    160959  ...         0.0        0.0       0
5947  20230424   161000    161459  ...         0.0        0.0       0
5948  20230424   161500    161959  ...         0.0        0.0       0
5949  20230424   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 16:25:01,563:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682324699, self.tradeDate='20230424', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27463.2, self.close=27384.5, self.high=27467.2, self.low=27382.0, self.vol=2632.37, self.amt=72164023.2651, ukdf['pct'].iloc[-1]=-0.002866 , ukdf['amount'].iloc[-1]=72164023.2651, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-653419.21454500688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27387.76873413', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43207 

self.closeSec=1682323199, self.tradeDate='20230424', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27460.0, self.close=27440.8, self.high=27460.0, self.low=27420.0 
127.0.0.1 - - [24/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43208 

self.closeSec=1682323499, self.tradeDate='20230424', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27440.9, self.close=27435.7, self.high=27440.9, self.low=27419.6 
127.0.0.1 - - [24/Apr/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43209 

self.closeSec=1682323799, self.tradeDate='20230424', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27435.6, self.close=27446.1, self.high=27449.2, self.low=27400.0 
127.0.0.1 - - [24/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43210 

self.closeSec=1682324099, self.tradeDate='20230424', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27446.1, self.close=27493.2, self.high=27510.0, self.low=27445.4 
127.0.0.1 - - [24/Apr/2023 16:15:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Apr/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43211 

self.closeSec=1682324399, self.tradeDate='20230424', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27493.2, self.close=27463.2, self.high=27493.2, self.low=27463.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43212 

self.closeSec=1682324699, self.tradeDate='20230424', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27463.2, self.close=27384.5, self.high=27467.2, self.low=27382.0 
127.0.0.1 - - [24/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-24 16:00:19,366:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230424    132959  27689.8  ...  50.416667  0.515004  0.443625
5786  20230424    135959  27727.7  ...  50.000000  0.498471  0.447064
5787  20230424    142959  27643.4  ...  50.416667  0.501624  0.448765
5788  20230424    145959  27659.7  ...  50.416667  0.477996  0.461978
5789  20230424    152959  27534.0  ...  50.000000  0.464989  0.481075

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2023-04-24 16:00:19,489:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.519480  0.480520       0  ...  0.883991   1.0    0.0  0.922280
538     1  0.489612  0.510388       1  ...  0.884512   1.0    0.0  0.922823
539     0  0.506235  0.493765       0  ...  0.880496   1.0    0.0  0.918633
540     1  0.467899  0.532101       0  ...  0.878158   1.0    0.0  0.916194
541     1  0.479331  0.520669       0  ...  0.877516   1.0    0.0  0.915523

[5 rows x 10 columns]
2023-04-24 16:00:19,519:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519681  0.480319       0  ...  0.883991   1.0    0.0  0.926626
46     1  0.489541  0.510459       1  ...  0.884512   1.0    0.0  0.925076
47     0  0.507106  0.492894       0  ...  0.891262   1.0    0.0  0.921640
48     1  0.467735  0.532265       0  ...  0.878158   1.0    0.0  0.917287
49     1  0.479331  0.520669       0  ...  0.877516   1.0    0.0  0.915523

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21601 

self.closeSec=1682321399, self.tradeDate='20230424', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27449.9', self.close='27460.9'
127.0.0.1 - - [24/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21602 

self.closeSec=1682321999, self.tradeDate='20230424', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27460.8', self.close='27457.1'
127.0.0.1 - - [24/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21603 

self.closeSec=1682322599, self.tradeDate='20230424', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27457.1', self.close='27460.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21604 

self.closeSec=1682323199, self.tradeDate='20230424', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27460.5', self.close='27440.8'
127.0.0.1 - - [24/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21605 

self.closeSec=1682323799, self.tradeDate='20230424', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27440.9', self.close='27446.1'
127.0.0.1 - - [24/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21606 

self.closeSec=1682324399, self.tradeDate='20230424', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27446.1', self.close='27463.2'
127.0.0.1 - - [24/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21602 

self.closeSec=1682321399, self.tradeDate='20230424', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27449.9', self.close='27460.9'
127.0.0.1 - - [24/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21603 

self.closeSec=1682321999, self.tradeDate='20230424', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27460.8', self.close='27457.1'
127.0.0.1 - - [24/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21604 

self.closeSec=1682322599, self.tradeDate='20230424', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27457.1', self.close='27460.4'
127.0.0.1 - - [24/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21605 

self.closeSec=1682323199, self.tradeDate='20230424', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27460.5', self.close='27440.8'
127.0.0.1 - - [24/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21606 

self.closeSec=1682323799, self.tradeDate='20230424', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27440.9', self.close='27446.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21607 

self.closeSec=1682324399, self.tradeDate='20230424', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27446.1', self.close='27463.2'
127.0.0.1 - - [24/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21602 

self.closeSec=1682321399, self.tradeDate='20230424', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27449.9', self.close='27460.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21603 

self.closeSec=1682321999, self.tradeDate='20230424', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27460.8', self.close='27457.1'
127.0.0.1 - - [24/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21604 

self.closeSec=1682322599, self.tradeDate='20230424', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27457.1', self.close='27460.4'
127.0.0.1 - - [24/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21605 

self.closeSec=1682323199, self.tradeDate='20230424', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27460.5', self.close='27440.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21606 

self.closeSec=1682323799, self.tradeDate='20230424', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27440.9', self.close='27446.1'
127.0.0.1 - - [24/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21607 

self.closeSec=1682324399, self.tradeDate='20230424', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27446.1', self.close='27463.2'
127.0.0.1 - - [24/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38643
self.closeSec=1682324399, self.tradeDate='20230424', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27493.2, self.close=27463.2, self.high=27493.2, self.low=27463.0, self.vol=1413.537, self.amt=38837999.463 
127.0.0.1 - - [24/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-04-24 16:20:04,773:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230424   155500    155959  ...         0.0        0.0       0
5945  20230424   160000    160459  ...         0.0        0.0       0
5946  20230424   160500    160959  ...         0.0        0.0       0
5947  20230424   161000    161459  ...         0.0        0.0       0
5948  20230424   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 16:20:04,777:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682324399, self.tradeDate='20230424', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27493.2, self.close=27463.2, self.high=27493.2, self.low=27463.0, self.vol=1413.537, self.amt=38837999.463, ukdf['pct'].iloc[-1]=-0.001091 , ukdf['amount'].iloc[-1]=38837999.463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38644
self.closeSec=1682324699, self.tradeDate='20230424', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27463.2, self.close=27384.5, self.high=27467.2, self.low=27382.0, self.vol=2632.37, self.amt=72164023.2651 
2023-04-24 16:25:01,557:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230424   160000    160459  ...         0.0        0.0       0
5946  20230424   160500    160959  ...         0.0        0.0       0
5947  20230424   161000    161459  ...         0.0        0.0       0
5948  20230424   161500    161959  ...         0.0        0.0       0
5949  20230424   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-24 16:25:01,562:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682324699, self.tradeDate='20230424', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27463.2, self.close=27384.5, self.high=27467.2, self.low=27382.0, self.vol=2632.37, self.amt=72164023.2651, ukdf['pct'].iloc[-1]=-0.002866 , ukdf['amount'].iloc[-1]=72164023.2651, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230424   040000    075959  1682294399  ...    721  1.101631  0.980042     1.0
722  20230424   080000    115959  1682308799  ...    722  0.986282  0.678939     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-25606.314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27782.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=900
self.closeSec=1682323199, self.tradeDate='20230424', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27780.1, self.close=27440.8, self.high=27782.3, self.low=27331.0, self.vol=65884.391, self.amt=1814763177.63627 127.0.0.1 - - [24/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

2023-04-24 16:00:02,087:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682323199, self.tradeDate='20230424', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27780.1, self.close=27440.8, self.high=27782.3, self.low=27331.0, self.vol=65884.391, self.amt=1814763177.63627 
2023-04-24 16:00:02,117:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230423   200000    235959  ...  70478.522  1.940022e+09 -0.006246
720  20230424   000000    035959  ...  74820.167  2.056871e+09 -0.000251
721  20230424   040000    075959  ...  37569.391  1.034168e+09  0.004469
722  20230424   080000    115959  ...  99571.446  2.762542e+09  0.007398
723  20230424   120000    155959  ...  65884.391  1.814763e+09 -0.012210

[5 rows x 11 columns]
2023-04-24 16:00:03,598:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230423   200000    235959  1682265599  ...    719  1.054536  0.905609     1.0
720  20230424   000000    035959  1682279999  ...    720  1.042068  0.855422     1.0
721  20230424   040000    075959  1682294399  ...    721  1.101631  0.980042     1.0
722  20230424   080000    115959  1682308799  ...    722  0.986282  0.678939     1.0
723  20230424   120000    155959  1682323199  ...    723  0.946303  0.563779     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-43534.935', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27440.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


