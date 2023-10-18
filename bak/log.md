# 20231018 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45268
self.closeSec=1697617199, self.tradeDate='20231018', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28476.6, self.close=28465.2, self.high=28503.3, self.low=28456.0, self.vol=974.004, self.amt=27733140.1097 
127.0.0.1 - - [18/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -
2023-10-18 16:20:18,906:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231018   155500    155959  ...         0.0        0.0       0
5952  20231018   160000    160459  ...         0.0        0.0       0
5953  20231018   160500    160959  ...         0.0        0.0       0
5954  20231018   161000    161459  ...         0.0        0.0       0
5955  20231018   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 16:20:18,927:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697617199, self.tradeDate='20231018', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28476.6, self.close=28465.2, self.high=28503.3, self.low=28456.0, self.vol=974.004, self.amt=27733140.1097, ukdf['pct'].iloc[-1]=-0.0004 , ukdf['amount'].iloc[-1]=27733140.1097, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-22351.23', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28469.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45269
self.closeSec=1697617499, self.tradeDate='20231018', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28465.1, self.close=28506.9, self.high=28510.5, self.low=28459.4, self.vol=745.796, self.amt=21244186.4793 
127.0.0.1 - - [18/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-18 16:25:03,251:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231018   160000    160459  ...         0.0        0.0       0
5953  20231018   160500    160959  ...         0.0        0.0       0
5954  20231018   161000    161459  ...         0.0        0.0       0
5955  20231018   161500    161959  ...         0.0        0.0       0
5956  20231018   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 16:25:03,256:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697617499, self.tradeDate='20231018', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28465.1, self.close=28506.9, self.high=28510.5, self.low=28459.4, self.vol=745.796, self.amt=21244186.4793, ukdf['pct'].iloc[-1]=0.001465 , ukdf['amount'].iloc[-1]=21244186.4793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-22897.61298826518', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28509.13473993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [18/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45266 

self.closeSec=1697615999, self.tradeDate='20231018', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28482.9, self.close=28485.2, self.high=28489.9, self.low=28477.4 
127.0.0.1 - - [18/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45267 

self.closeSec=1697616299, self.tradeDate='20231018', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28485.1, self.close=28507.1, self.high=28522.8, self.low=28452.9 
127.0.0.1 - - [18/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45268 

self.closeSec=1697616599, self.tradeDate='20231018', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28507.0, self.close=28516.4, self.high=28539.0, self.low=28500.6 

--handleKline--: 127.0.0.1 - - [18/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45269 

self.closeSec=1697616899, self.tradeDate='20231018', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28515.1, self.close=28476.6, self.high=28517.7, self.low=28465.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45270 

self.closeSec=1697617199, self.tradeDate='20231018', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28476.6, self.close=28465.2, self.high=28503.3, self.low=28456.0 
127.0.0.1 - - [18/Oct/2023 16:20:10] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45271 

self.closeSec=1697617499, self.tradeDate='20231018', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28465.1, self.close=28506.9, self.high=28510.5, self.low=28459.4 
127.0.0.1 - - [18/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-18 16:00:19,076:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231018    132959  28716.8  ...  52.500000  0.578401  0.383314
5786  20231018    135959  28688.7  ...  52.083333  0.578066  0.386115
5787  20231018    142959  28681.9  ...  52.083333  0.575204  0.389815
5788  20231018    145959  28666.0  ...  51.666667  0.572961  0.394108
5789  20231018    152959  28653.4  ...  51.250000  0.555489  0.404762

[5 rows x 33 columns]
0.566420664206642
acc is : 0.566420664206642
2023-10-18 16:00:19,147:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510067  0.489933       0  ...  0.960769   1.0    0.0  1.027948
538     0  0.515505  0.484495       0  ...  0.960233   1.0    0.0  1.027374
539     0  0.509007  0.490993       0  ...  0.959818   1.0    0.0  1.026930
540     0  0.510870  0.489130       0  ...  0.956535   1.0    0.0  1.023418
541     1  0.465511  0.534489       0  ...  0.954180   1.0    0.0  1.020898

[5 rows x 10 columns]
2023-10-18 16:00:19,160:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509895  0.490105       0  ...  0.960769   1.0    0.0  1.025753
46     0  0.515515  0.484485       0  ...  0.960233   1.0    0.0  1.027746
47     0  0.508837  0.491163       0  ...  0.959818   1.0    0.0  1.026378
48     0  0.510794  0.489206       0  ...  0.956535   1.0    0.0  1.023091
49     1  0.465511  0.534489       0  ...  0.954180   1.0    0.0  1.020898

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.938', 'enterprice': '28688.1', 'countrevence': '0', 'unrealprofit': '-4595.15778862028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28478.63889194', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [18/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22631 

self.closeSec=1697614199, self.tradeDate='20231018', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28569.6', self.close='28555.5'
127.0.0.1 - - [18/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22632 

self.closeSec=1697614799, self.tradeDate='20231018', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28555.5', self.close='28557.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22633 

self.closeSec=1697615399, self.tradeDate='20231018', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28548.1', self.close='28479.3'
127.0.0.1 - - [18/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22634 

self.closeSec=1697615999, self.tradeDate='20231018', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28472.8', self.close='28485.2'
127.0.0.1 - - [18/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22635 

self.closeSec=1697616599, self.tradeDate='20231018', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28485.1', self.close='28516.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22636 

self.closeSec=1697617199, self.tradeDate='20231018', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28515.1', self.close='28465.2'
127.0.0.1 - - [18/Oct/2023 16:20:14] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [18/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22634 

self.closeSec=1697614199, self.tradeDate='20231018', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28569.6', self.close='28555.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22635 

self.closeSec=1697614799, self.tradeDate='20231018', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28555.5', self.close='28557.7'
127.0.0.1 - - [18/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22636 

self.closeSec=1697615399, self.tradeDate='20231018', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28548.1', self.close='28479.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22637 

self.closeSec=1697615999, self.tradeDate='20231018', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28472.8', self.close='28485.2'
127.0.0.1 - - [18/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22638 

self.closeSec=1697616599, self.tradeDate='20231018', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28485.1', self.close='28516.4'
127.0.0.1 - - [18/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22639 

self.closeSec=1697617199, self.tradeDate='20231018', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28515.1', self.close='28465.2'
127.0.0.1 - - [18/Oct/2023 16:20:14] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [18/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22634 

self.closeSec=1697614199, self.tradeDate='20231018', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28569.6', self.close='28555.5'
127.0.0.1 - - [18/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22635 

self.closeSec=1697614799, self.tradeDate='20231018', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28555.5', self.close='28557.7'
127.0.0.1 - - [18/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22636 

self.closeSec=1697615399, self.tradeDate='20231018', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28548.1', self.close='28479.3'
127.0.0.1 - - [18/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22637 

self.closeSec=1697615999, self.tradeDate='20231018', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28472.8', self.close='28485.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22638 

self.closeSec=1697616599, self.tradeDate='20231018', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28485.1', self.close='28516.4'
127.0.0.1 - - [18/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22639 

self.closeSec=1697617199, self.tradeDate='20231018', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28515.1', self.close='28465.2'
127.0.0.1 - - [18/Oct/2023 16:20:14] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45268
self.closeSec=1697617199, self.tradeDate='20231018', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28476.6, self.close=28465.2, self.high=28503.3, self.low=28456.0, self.vol=974.004, self.amt=27733140.1097 
127.0.0.1 - - [18/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -
2023-10-18 16:20:18,886:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231018   155500    155959  ...         0.0        0.0       0
5952  20231018   160000    160459  ...         0.0        0.0       0
5953  20231018   160500    160959  ...         0.0        0.0       0
5954  20231018   161000    161459  ...         0.0        0.0       0
5955  20231018   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 16:20:18,906:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697617199, self.tradeDate='20231018', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28476.6, self.close=28465.2, self.high=28503.3, self.low=28456.0, self.vol=974.004, self.amt=27733140.1097, ukdf['pct'].iloc[-1]=-0.0004 , ukdf['amount'].iloc[-1]=27733140.1097, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '60387.5519', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28469.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45269
self.closeSec=1697617499, self.tradeDate='20231018', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28465.1, self.close=28506.9, self.high=28510.5, self.low=28459.4, self.vol=745.796, self.amt=21244186.4793 
127.0.0.1 - - [18/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-18 16:25:03,246:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231018   160000    160459  ...         0.0        0.0       0
5953  20231018   160500    160959  ...         0.0        0.0       0
5954  20231018   161000    161459  ...         0.0        0.0       0
5955  20231018   161500    161959  ...         0.0        0.0       0
5956  20231018   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 16:25:03,253:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697617499, self.tradeDate='20231018', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28465.1, self.close=28506.9, self.high=28510.5, self.low=28459.4, self.vol=745.796, self.amt=21244186.4793, ukdf['pct'].iloc[-1]=0.001465 , ukdf['amount'].iloc[-1]=21244186.4793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '61844.76937574013', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28509.13473993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231018   040000    075959  1697587199  ...    721  0.992506  0.497216     NaN
722  20231018   080000    115959  1697601599  ...    722  0.946815  0.429065     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '28812.10138831374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28498.62043529', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=943
self.closeSec=1697615999, self.tradeDate='20231018', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28498.1, self.close=28485.2, self.high=29100.0, self.low=28428.3, self.vol=98876.718, self.amt=2836423036.10633 
127.0.0.1 - - [18/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-18 16:00:01,541:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697615999, self.tradeDate='20231018', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28498.1, self.close=28485.2, self.high=29100.0, self.low=28428.3, self.vol=98876.718, self.amt=2836423036.10633 
2023-10-18 16:00:01,556:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231017   200000    235959  ...  98853.837  2.801737e+09  0.001306
720  20231018   000000    035959  ...  47386.641  1.347540e+09  0.001870
721  20231018   040000    075959  ...  24541.976  6.983148e+08 -0.004109
722  20231018   080000    115959  ...  25900.836  7.355935e+08  0.004122
723  20231018   120000    155959  ...  98876.718  2.836423e+09 -0.000481

[5 rows x 11 columns]
2023-10-18 16:00:02,249:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231017   200000    235959  1697558399  ...    719  1.170284  0.775830     1.0
720  20231018   000000    035959  1697572799  ...    720  1.104558  0.671671     1.0
721  20231018   040000    075959  1697587199  ...    721  0.992506  0.497216     NaN
722  20231018   080000    115959  1697601599  ...    722  0.946815  0.429065     NaN
723  20231018   120000    155959  1697615999  ...    723  0.968668  0.467607     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '28219.8252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28485.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


