# 20231007 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42100
self.closeSec=1696666799, self.tradeDate='20231007', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27892.1, self.close=27885.3, self.high=27894.0, self.low=27880.0, self.vol=606.697, self.amt=16918382.2786 
127.0.0.1 - - [07/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-07 16:20:06,097:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231007   155500    155959  ...         0.0        0.0       0
5952  20231007   160000    160459  ...         0.0        0.0       0
5953  20231007   160500    160959  ...         0.0        0.0       0
5954  20231007   161000    161459  ...         0.0        0.0       0
5955  20231007   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 16:20:06,108:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696666799, self.tradeDate='20231007', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27892.1, self.close=27885.3, self.high=27894.0, self.low=27880.0, self.vol=606.697, self.amt=16918382.2786, ukdf['pct'].iloc[-1]=-0.000244 , ukdf['amount'].iloc[-1]=16918382.2786, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14210.0904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27885.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42101
self.closeSec=1696667099, self.tradeDate='20231007', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27885.3, self.close=27907.1, self.high=27907.2, self.low=27885.0, self.vol=383.509, self.amt=10699225.5066 
2023-10-07 16:25:00,805:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231007   160000    160459  ...         0.0        0.0       0
5953  20231007   160500    160959  ...         0.0        0.0       0
5954  20231007   161000    161459  ...         0.0        0.0       0
5955  20231007   161500    161959  ...         0.0        0.0       0
5956  20231007   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 16:25:00,806:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696667099, self.tradeDate='20231007', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27885.3, self.close=27907.1, self.high=27907.2, self.low=27885.0, self.vol=383.509, self.amt=10699225.5066, ukdf['pct'].iloc[-1]=0.000782 , ukdf['amount'].iloc[-1]=10699225.5066, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14515.0698', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27907.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42098127.0.0.1 - - [07/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -
 

self.closeSec=1696665599, self.tradeDate='20231007', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27875.1, self.close=27879.5, self.high=27880.2, self.low=27873.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42099 

self.closeSec=1696665899, self.tradeDate='20231007', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27878.1, self.close=27869.2, self.high=27881.6, self.low=27865.4 
127.0.0.1 - - [07/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42100 

self.closeSec=1696666199, self.tradeDate='20231007', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27869.1, self.close=27875.1, self.high=27878.4, self.low=27867.0 
127.0.0.1 - - [07/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42101 

self.closeSec=1696666499, self.tradeDate='20231007', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27875.1, self.close=27892.1, self.high=27892.1, self.low=27875.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42102 

self.closeSec=1696666799, self.tradeDate='20231007', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27892.1, self.close=27885.3, self.high=27894.0, self.low=27880.0 
127.0.0.1 - - [07/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42103 

self.closeSec=1696667099, self.tradeDate='20231007', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27885.3, self.close=27907.1, self.high=27907.2, self.low=27885.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-07 16:00:21,400:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231007    132959  27900.0  ...  54.166667  0.539886  0.374995
5786  20231007    135959  27905.7  ...  54.166667  0.536001  0.378893
5787  20231007    142959  27889.1  ...  53.750000  0.535225  0.382701
5788  20231007    145959  27886.5  ...  53.333333  0.532791  0.386781
5789  20231007    152959  27875.6  ...  53.333333  0.537941  0.389326

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-10-07 16:00:21,481:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.498737  0.501263       0  ...  0.977859   1.0    0.0  1.062450
538     1  0.489482  0.510518       0  ...  0.977743   1.0    0.0  1.062324
539     1  0.492095  0.507905       0  ...  0.977385   1.0    0.0  1.061936
540     1  0.487960  0.512040       1  ...  0.978244   1.0    0.0  1.062869
541     1  0.499964  0.500036       0  ...  0.977522   1.0    0.0  1.062084

[5 rows x 10 columns]
2023-10-07 16:00:21,495:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498475  0.501525       0  ...  0.977859   1.0    0.0  1.061746
46     1  0.489130  0.510870       0  ...  0.977743   1.0    0.0  1.061087
47     1  0.491814  0.508186       0  ...  0.977385   1.0    0.0  1.060296
48     1  0.487926  0.512074       1  ...  0.978244   1.0    0.0  1.062129
49     1  0.499964  0.500036       0  ...  0.977522   1.0    0.0  1.062084

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.669', 'enterprice': '27936.3', 'countrevence': '0', 'unrealprofit': '-1399.10915455077', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27877.18853967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21047 

self.closeSec=1696663799, self.tradeDate='20231007', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27881.2', self.close='27901.6'
127.0.0.1 - - [07/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21048 

self.closeSec=1696664399, self.tradeDate='20231007', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27901.5', self.close='27891.6'
127.0.0.1 - - [07/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21049 

self.closeSec=1696664999, self.tradeDate='20231007', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27891.6', self.close='27884.5'
127.0.0.1 - - [07/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [07/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21050 

self.closeSec=1696665599, self.tradeDate='20231007', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27884.5', self.close='27878.2'
127.0.0.1 - - [07/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21051 

self.closeSec=1696666199, self.tradeDate='20231007', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27878.1', self.close='27875.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21052 

self.closeSec=1696666799, self.tradeDate='20231007', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27875.1', self.close='27885.4'
127.0.0.1 - - [07/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21050 

self.closeSec=1696663799, self.tradeDate='20231007', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27881.2', self.close='27901.6'
127.0.0.1 - - [07/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21051 

self.closeSec=1696664399, self.tradeDate='20231007', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27901.5', self.close='27891.6'
127.0.0.1 - - [07/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21052 

self.closeSec=1696664999, self.tradeDate='20231007', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27891.6', self.close='27884.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21053 

self.closeSec=1696665599, self.tradeDate='20231007', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27884.5', self.close='27878.2'
127.0.0.1 - - [07/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21054 

self.closeSec=1696666199, self.tradeDate='20231007', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27878.1', self.close='27875.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21055 

self.closeSec=1696666799, self.tradeDate='20231007', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27875.1', self.close='27885.4'
127.0.0.1 - - [07/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21050 

self.closeSec=1696663799, self.tradeDate='20231007', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27881.2', self.close='27901.6'
127.0.0.1 - - [07/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21051 

self.closeSec=1696664399, self.tradeDate='20231007', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27901.5', self.close='27891.6'
127.0.0.1 - - [07/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21052 

self.closeSec=1696664999, self.tradeDate='20231007', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27891.6', self.close='27884.5'
127.0.0.1 - - [07/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21053 

self.closeSec=1696665599, self.tradeDate='20231007', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27884.5', self.close='27878.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21054 

self.closeSec=1696666199, self.tradeDate='20231007', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27878.1', self.close='27875.1'
127.0.0.1 - - [07/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21055 

self.closeSec=1696666799, self.tradeDate='20231007', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27875.1', self.close='27885.4'
127.0.0.1 - - [07/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42100
self.closeSec=1696666799, self.tradeDate='20231007', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27892.1, self.close=27885.3, self.high=27894.0, self.low=27880.0, self.vol=606.697, self.amt=16918382.2786 
127.0.0.1 - - [07/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-07 16:20:06,096:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231007   155500    155959  ...         0.0        0.0       0
5952  20231007   160000    160459  ...         0.0        0.0       0
5953  20231007   160500    160959  ...         0.0        0.0       0
5954  20231007   161000    161459  ...         0.0        0.0       0
5955  20231007   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 16:20:06,106:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696666799, self.tradeDate='20231007', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27892.1, self.close=27885.3, self.high=27894.0, self.low=27880.0, self.vol=606.697, self.amt=16918382.2786, ukdf['pct'].iloc[-1]=-0.000244 , ukdf['amount'].iloc[-1]=16918382.2786, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '38674.9233', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27885.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [07/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42101
self.closeSec=1696667099, self.tradeDate='20231007', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27885.3, self.close=27907.1, self.high=27907.2, self.low=27885.0, self.vol=383.509, self.amt=10699225.5066 
2023-10-07 16:25:00,815:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231007   160000    160459  ...         0.0        0.0       0
5953  20231007   160500    160959  ...         0.0        0.0       0
5954  20231007   161000    161459  ...         0.0        0.0       0
5955  20231007   161500    161959  ...         0.0        0.0       0
5956  20231007   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 16:25:00,816:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696667099, self.tradeDate='20231007', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27885.3, self.close=27907.1, self.high=27907.2, self.low=27885.0, self.vol=383.509, self.amt=10699225.5066, ukdf['pct'].iloc[-1]=0.000782 , ukdf['amount'].iloc[-1]=10699225.5066, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '39488.3112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27907.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231007   040000    075959  1696636799  ...    721  0.195185 -1.229155    -1.0
722  20231007   080000    115959  1696651199  ...    722  0.259306 -1.046460    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '2257.51438245275', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27892.61858425', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [07/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=877
self.closeSec=1696665599, self.tradeDate='20231007', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27891.0, self.close=27878.2, self.high=27933.0, self.low=27858.4, self.vol=13365.886, self.amt=372796320.7572 
2023-10-07 16:00:01,586:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696665599, self.tradeDate='20231007', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27891.0, self.close=27878.2, self.high=27933.0, self.low=27858.4, self.vol=13365.886, self.amt=372796320.7572 
2023-10-07 16:00:01,602:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231006   200000    235959  ...  192444.274  5.308505e+09  0.006578
720  20231007   000000    035959  ...   74169.479  2.070069e+09  0.000351
721  20231007   040000    075959  ...   61484.735  1.724951e+09 -0.000716
722  20231007   080000    115959  ...   26860.834  7.491186e+08 -0.000910
723  20231007   120000    155959  ...   13365.886  3.727963e+08 -0.000455

[5 rows x 11 columns]
2023-10-07 16:00:02,324:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231006   200000    235959  1696607999  ...    719  0.332489 -0.923390    -1.0
720  20231007   000000    035959  1696622399  ...    720  0.067516 -1.587487    -1.0
721  20231007   040000    075959  1696636799  ...    721  0.195185 -1.229155    -1.0
722  20231007   080000    115959  1696651199  ...    722  0.259306 -1.046460    -1.0
723  20231007   120000    155959  1696665599  ...    723  0.227771 -1.107926    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '2899.2005', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27877.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


