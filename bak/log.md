# 20230430 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44373
self.closeSec=1682842799, self.tradeDate='20230430', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29255.7, self.close=29234.0, self.high=29256.3, self.low=29234.0, self.vol=313.322, self.amt=9163410.9459 
127.0.0.1 - - [30/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-04-30 16:20:06,145:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230430   155500    155959  ...         0.0        0.0       0
5945  20230430   160000    160459  ...         0.0        0.0       0
5946  20230430   160500    160959  ...         0.0        0.0       0
5947  20230430   161000    161459  ...         0.0        0.0       0
5948  20230430   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 16:20:06,157:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682842799, self.tradeDate='20230430', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29255.7, self.close=29234.0, self.high=29256.3, self.low=29234.0, self.vol=313.322, self.amt=9163410.9459, ukdf['pct'].iloc[-1]=-0.000738 , ukdf['amount'].iloc[-1]=9163410.9459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-764734.6608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29237.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44374
self.closeSec=1682843099, self.tradeDate='20230430', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29234.0, self.close=29250.6, self.high=29251.4, self.low=29234.0, self.vol=377.958, self.amt=11053975.5526 
127.0.0.1 - - [30/Apr/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-04-30 16:25:02,175:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230430   160000    160459  ...         0.0        0.0       0
5946  20230430   160500    160959  ...         0.0        0.0       0
5947  20230430   161000    161459  ...         0.0        0.0       0
5948  20230430   161500    161959  ...         0.0        0.0       0
5949  20230430   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 16:25:02,176:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682843099, self.tradeDate='20230430', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29234.0, self.close=29250.6, self.high=29251.4, self.low=29234.0, self.vol=377.958, self.amt=11053975.5526, ukdf['pct'].iloc[-1]=0.000568 , ukdf['amount'].iloc[-1]=11053975.5526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-765516.9488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29250.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [30/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44935 

self.closeSec=1682841599, self.tradeDate='20230430', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29255.9, self.close=29252.0, self.high=29256.0, self.low=29248.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44936 

self.closeSec=1682841899, self.tradeDate='20230430', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29251.9, self.close=29252.9, self.high=29261.0, self.low=29248.1 
127.0.0.1 - - [30/Apr/2023 16:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44937 

self.closeSec=1682842199, self.tradeDate='20230430', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29252.9, self.close=29232.7, self.high=29259.3, self.low=29230.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44938 

self.closeSec=1682842499, self.tradeDate='20230430', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29232.7, self.close=29255.6, self.high=29256.9, self.low=29232.7 
127.0.0.1 - - [30/Apr/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44939 

self.closeSec=1682842799, self.tradeDate='20230430', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29255.7, self.close=29234.0, self.high=29256.3, self.low=29234.0 
127.0.0.1 - - [30/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44940 

self.closeSec=1682843099, self.tradeDate='20230430', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29234.0, self.close=29250.6, self.high=29251.4, self.low=29234.0 
127.0.0.1 - - [30/Apr/2023 16:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-30 16:00:20,050:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230430    132959  29198.6  ...  50.416667  0.503924  0.551757
5786  20230430    135959  29221.8  ...  50.416667  0.509432  0.539085
5787  20230430    142959  29245.8  ...  50.000000  0.504478  0.530863
5788  20230430    145959  29225.0  ...  50.416667  0.512593  0.517140
5789  20230430    152959  29260.0  ...  50.833333  0.514221  0.503118

[5 rows x 33 columns]
0.5645756457564576
acc is : 0.5645756457564576
2023-04-30 16:00:20,140:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.519775  0.480225       1  ...  0.889772  -1.0    0.0  0.965007
538     0  0.522589  0.477411       0  ...  0.890405  -1.0    0.0  0.964321
539     0  0.511935  0.488065       1  ...  0.889342  -1.0    0.0  0.965473
540     0  0.523531  0.476469       1  ...  0.889129  -1.0    0.0  0.965704
541     0  0.517031  0.482969       0  ...  0.889585  -1.0    0.0  0.965209

[5 rows x 10 columns]
2023-04-30 16:00:20,153:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519709  0.480291       1  ...  0.889772  -1.0    0.0  0.963427
46     0  0.522833  0.477167       0  ...  0.890405  -1.0    0.0  0.963889
47     0  0.511907  0.488093       1  ...  0.889342  -1.0    0.0  0.963584
48     0  0.523793  0.476207       1  ...  0.889129  -1.0    0.0  0.965898
49     0  0.517031  0.482969       0  ...  0.889585  -1.0    0.0  0.965209

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [30/Apr/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22465 

self.closeSec=1682839799, self.tradeDate='20230430', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29279', self.close='29267'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22466 

self.closeSec=1682840399, self.tradeDate='20230430', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29267', self.close='29258'
127.0.0.1 - - [30/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22467 

self.closeSec=1682840999, self.tradeDate='20230430', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29258.1', self.close='29260.4'
127.0.0.1 - - [30/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22468 

self.closeSec=1682841599, self.tradeDate='20230430', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29260.4', self.close='29252'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22469 

self.closeSec=1682842199, self.tradeDate='20230430', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29251.9', self.close='29232.7'
127.0.0.1 - - [30/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22470 

self.closeSec=1682842799, self.tradeDate='20230430', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29232.7', self.close='29234.1'
127.0.0.1 - - [30/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [30/Apr/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22466 

self.closeSec=1682839799, self.tradeDate='20230430', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29279', self.close='29267'
127.0.0.1 - - [30/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22467 

self.closeSec=1682840399, self.tradeDate='20230430', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29267', self.close='29258'
127.0.0.1 - - [30/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22468 

self.closeSec=1682840999, self.tradeDate='20230430', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29258.1', self.close='29260.4'

--handleKline--:  127.0.0.1 - - [30/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22469 

self.closeSec=1682841599, self.tradeDate='20230430', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29260.4', self.close='29252'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22470 

self.closeSec=1682842199, self.tradeDate='20230430', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29251.9', self.close='29232.7'
127.0.0.1 - - [30/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22471 

self.closeSec=1682842799, self.tradeDate='20230430', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29232.7', self.close='29234.1'
127.0.0.1 - - [30/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [30/Apr/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22466 

self.closeSec=1682839799, self.tradeDate='20230430', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29279', self.close='29267'

--handleKline--: 127.0.0.1 - - [30/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22467 

self.closeSec=1682840399, self.tradeDate='20230430', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29267', self.close='29258'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22468 

self.closeSec=1682840999, self.tradeDate='20230430', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29258.1', self.close='29260.4'
127.0.0.1 - - [30/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22469 

self.closeSec=1682841599, self.tradeDate='20230430', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29260.4', self.close='29252'
127.0.0.1 - - [30/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22470 

self.closeSec=1682842199, self.tradeDate='20230430', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29251.9', self.close='29232.7'
127.0.0.1 - - [30/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22471 

self.closeSec=1682842799, self.tradeDate='20230430', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29232.7', self.close='29234.1'
127.0.0.1 - - [30/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40371
self.closeSec=1682842799, self.tradeDate='20230430', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29255.7, self.close=29234.0, self.high=29256.3, self.low=29234.0, self.vol=313.322, self.amt=9163410.9459 
127.0.0.1 - - [30/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-30 16:20:06,375:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230430   155500    155959  ...         0.0        0.0       0
5945  20230430   160000    160459  ...         0.0        0.0       0
5946  20230430   160500    160959  ...         0.0        0.0       0
5947  20230430   161000    161459  ...         0.0        0.0       0
5948  20230430   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 16:20:06,387:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682842799, self.tradeDate='20230430', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29255.7, self.close=29234.0, self.high=29256.3, self.low=29234.0, self.vol=313.322, self.amt=9163410.9459, ukdf['pct'].iloc[-1]=-0.000738 , ukdf['amount'].iloc[-1]=9163410.9459, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40372
self.closeSec=1682843099, self.tradeDate='20230430', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29234.0, self.close=29250.6, self.high=29251.4, self.low=29234.0, self.vol=377.958, self.amt=11053975.5526 
127.0.0.1 - - [30/Apr/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-04-30 16:25:02,172:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230430   160000    160459  ...         0.0        0.0       0
5946  20230430   160500    160959  ...         0.0        0.0       0
5947  20230430   161000    161459  ...         0.0        0.0       0
5948  20230430   161500    161959  ...         0.0        0.0       0
5949  20230430   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 16:25:02,172:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682843099, self.tradeDate='20230430', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29234.0, self.close=29250.6, self.high=29251.4, self.low=29234.0, self.vol=377.958, self.amt=11053975.5526, ukdf['pct'].iloc[-1]=0.000568 , ukdf['amount'].iloc[-1]=11053975.5526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230430   040000    075959  1682812799  ...    721  0.041425 -2.057776    -1.0
722  20230430   080000    115959  1682827199  ...    722  0.013603 -2.105147    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '8209.54780201094', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29165.57441667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=936
self.closeSec=1682841599, self.tradeDate='20230430', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29168.0, self.close=29252.0, self.high=29287.5, self.low=29158.6, self.vol=24448.044, self.amt=714639504.8987 
127.0.0.1 - - [30/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-04-30 16:00:01,826:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682841599, self.tradeDate='20230430', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29168.0, self.close=29252.0, self.high=29287.5, self.low=29158.6, self.vol=24448.044, self.amt=714639504.8987 
2023-04-30 16:00:01,884:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230429   200000    235959  ...  38754.353  1.136095e+09 -0.002227
720  20230430   000000    035959  ...  47665.322  1.390575e+09 -0.001234
721  20230430   040000    075959  ...  19822.623  5.787364e+08 -0.000318
722  20230430   080000    115959  ...  25444.574  7.413127e+08 -0.001530
723  20230430   120000    155959  ...  24448.044  7.146395e+08  0.002880

[5 rows x 11 columns]
2023-04-30 16:00:03,651:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230429   200000    235959  1682783999  ...    719  0.222407 -1.497885    -1.0
720  20230430   000000    035959  1682798399  ...    720  0.117851 -1.833244    -1.0
721  20230430   040000    075959  1682812799  ...    721  0.041425 -2.057776    -1.0
722  20230430   080000    115959  1682827199  ...    722  0.013603 -2.105147    -1.0
723  20230430   120000    155959  1682841599  ...    723  0.005092 -2.073333    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '4171.9174', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29252', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


