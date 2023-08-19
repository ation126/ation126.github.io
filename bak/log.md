# 20230820 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28084
self.closeSec=1692461999, self.tradeDate='20230820', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26138.3, self.close=26160.2, self.high=26178.9, self.low=26127.9, self.vol=1242.239, self.amt=32498579.463 
127.0.0.1 - - [20/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-20 00:20:04,792:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230819   235500    235959  ...         0.0        0.0       0
5748  20230820   000000    000459  ...         0.0        0.0       0
5749  20230820   000500    000959  ...         0.0        0.0       0
5750  20230820   001000    001459  ...         0.0        0.0       0
5751  20230820   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 00:20:04,800:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692461999, self.tradeDate='20230820', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26138.3, self.close=26160.2, self.high=26178.9, self.low=26127.9, self.vol=1242.239, self.amt=32498579.463, ukdf['pct'].iloc[-1]=0.000838 , ukdf['amount'].iloc[-1]=32498579.463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9788.15693360538', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26162.03076737', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28085
self.closeSec=1692462299, self.tradeDate='20230820', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26158.7, self.close=26109.3, self.high=26158.8, self.low=26105.9, self.vol=1268.701, self.amt=33142226.5603 
2023-08-20 00:25:00,804:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230820   000000    000459  ...         0.0        0.0       0
5749  20230820   000500    000959  ...         0.0        0.0       0
5750  20230820   001000    001459  ...         0.0        0.0       0
5751  20230820   001500    001959  ...         0.0        0.0       0
5752  20230820   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 00:25:00,805:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692462299, self.tradeDate='20230820', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26158.7, self.close=26109.3, self.high=26158.8, self.low=26105.9, self.vol=1268.701, self.amt=33142226.5603, ukdf['pct'].iloc[-1]=-0.001946 , ukdf['amount'].iloc[-1]=33142226.5603, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10523.8782', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26109.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
489  20230816   164500    164959  1692175799  ...  29182.4 -0.000524   1641    3
490  20230816   165000    165459  1692176099  ...  29171.7 -0.000164   1642    4
491  20230816   165500    165959  1692176399  ...  29171.0 -0.000288   1643    5
492  20230816   170000    170459  1692176699  ...  29165.1 -0.000120   1644    0
493  20230816   170500    170959  1692176999  ...  29150.7 -0.000576   1645    1

[5 rows x 11 columns] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28084 

self.closeSec=1692461399, self.tradeDate='20230820', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26190.4, self.close=26137.6, self.high=26190.4, self.low=26120.0 
127.0.0.1 - - [20/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28085 

self.closeSec=1692461699, self.tradeDate='20230820', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26136.7, self.close=26138.3, self.high=26142.7, self.low=26101.0 
127.0.0.1 - - [20/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28086 

self.closeSec=1692461999, self.tradeDate='20230820', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26138.3, self.close=26160.2, self.high=26178.9, self.low=26127.9 
127.0.0.1 - - [20/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28087 

self.closeSec=1692462299, self.tradeDate='20230820', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26158.7, self.close=26109.3, self.high=26158.8, self.low=26105.9 
127.0.0.1 - - [20/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-20 00:00:16,405:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230819    212959  25900.0  ...  42.500000  0.383324  0.604119
5802  20230819    215959  25951.4  ...  42.500000  0.377653  0.614174
5803  20230819    222959  25910.1  ...  42.500000  0.399749  0.610498
5804  20230819    225959  26011.2  ...  42.083333  0.392692  0.610247
5805  20230819    232959  25961.9  ...  42.083333  0.410442  0.597627

[5 rows x 33 columns]
0.5147058823529411
acc is : 0.5147058823529411
2023-08-20 00:00:16,466:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510732  0.489268       0  ...  1.107897  -1.0    0.0  0.887490
540     1  0.471288  0.528712       1  ...  1.103570  -1.0    0.0  0.890956
541     0  0.534612  0.465388       0  ...  1.105700  -1.0    0.0  0.889237
542     1  0.469212  0.530788       1  ...  1.102126  -1.0    0.0  0.892111
543     0  0.526149  0.473851       1  ...  1.095521  -1.0    0.0  0.897457

[5 rows x 10 columns]
2023-08-20 00:00:16,477:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510817  0.489183       0  ...  1.107897  -1.0    0.0  0.886336
46     1  0.471272  0.528728       1  ...  1.103570  -1.0    0.0  0.889196
47     0  0.534750  0.465250       0  ...  1.105700  -1.0    0.0  0.888741
48     1  0.469352  0.530648       1  ...  1.102126  -1.0    0.0  0.891613
49     0  0.526149  0.473851       1  ...  1.095521  -1.0    0.0  0.897457

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.207', 'enterprice': '29084.9', 'countrevence': '0', 'unrealprofit': '69843.86984689452', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26199.62425964', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14039 

self.closeSec=1692458999, self.tradeDate='20230819', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26065.5', self.close='26044.9'
127.0.0.1 - - [19/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [19/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14040 

self.closeSec=1692459599, self.tradeDate='20230819', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26045', self.close='26017'
127.0.0.1 - - [19/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14041 

self.closeSec=1692460199, self.tradeDate='20230819', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26016.9', self.close='26116.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14042 

self.closeSec=1692460799, self.tradeDate='20230819', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26113', self.close='26201'
127.0.0.1 - - [20/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14043 

self.closeSec=1692461399, self.tradeDate='20230820', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26201', self.close='26137.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14044 

self.closeSec=1692461999, self.tradeDate='20230820', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26136.7', self.close='26160.2'
127.0.0.1 - - [20/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14042 

self.closeSec=1692458999, self.tradeDate='20230819', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26065.5', self.close='26044.9'
127.0.0.1 - - [19/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14043 

self.closeSec=1692459599, self.tradeDate='20230819', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26045', self.close='26017'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14044 

self.closeSec=1692460199, self.tradeDate='20230819', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26016.9', self.close='26116.1'
127.0.0.1 - - [19/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14045 

self.closeSec=1692460799, self.tradeDate='20230819', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26113', self.close='26201'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14046 

self.closeSec=1692461399, self.tradeDate='20230820', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26201', self.close='26137.6'
127.0.0.1 - - [20/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14047 

self.closeSec=1692461999, self.tradeDate='20230820', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26136.7', self.close='26160.2'
127.0.0.1 - - [20/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14042 

self.closeSec=1692458999, self.tradeDate='20230819', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26065.5', self.close='26044.9'
127.0.0.1 - - [19/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14043 

self.closeSec=1692459599, self.tradeDate='20230819', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26045', self.close='26017'
127.0.0.1 - - [19/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14044 

self.closeSec=1692460199, self.tradeDate='20230819', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26016.9', self.close='26116.1'
127.0.0.1 - - [20/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14045 

self.closeSec=1692460799, self.tradeDate='20230819', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26113', self.close='26201'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14046 

self.closeSec=1692461399, self.tradeDate='20230820', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26201', self.close='26137.6'
127.0.0.1 - - [20/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14047 

self.closeSec=1692461999, self.tradeDate='20230820', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26136.7', self.close='26160.2'
127.0.0.1 - - [20/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28084
self.closeSec=1692461999, self.tradeDate='20230820', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26138.3, self.close=26160.2, self.high=26178.9, self.low=26127.9, self.vol=1242.239, self.amt=32498579.463 
127.0.0.1 - - [20/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-20 00:20:04,792:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230819   235500    235959  ...         0.0        0.0       0
5748  20230820   000000    000459  ...         0.0        0.0       0
5749  20230820   000500    000959  ...         0.0        0.0       0
5750  20230820   001000    001459  ...         0.0        0.0       0
5751  20230820   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 00:20:04,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692461999, self.tradeDate='20230820', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26138.3, self.close=26160.2, self.high=26178.9, self.low=26127.9, self.vol=1242.239, self.amt=32498579.463, ukdf['pct'].iloc[-1]=0.000838 , ukdf['amount'].iloc[-1]=32498579.463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-25329.01926911083', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26162.03076737', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28085
self.closeSec=1692462299, self.tradeDate='20230820', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26158.7, self.close=26109.3, self.high=26158.8, self.low=26105.9, self.vol=1268.701, self.amt=33142226.5603 
127.0.0.1 - - [20/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-20 00:25:00,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230820   000000    000459  ...         0.0        0.0       0
5749  20230820   000500    000959  ...         0.0        0.0       0
5750  20230820   001000    001459  ...         0.0        0.0       0
5751  20230820   001500    001959  ...         0.0        0.0       0
5752  20230820   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 00:25:00,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692462299, self.tradeDate='20230820', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26158.7, self.close=26109.3, self.high=26158.8, self.low=26105.9, self.vol=1268.701, self.amt=33142226.5603, ukdf['pct'].iloc[-1]=-0.001946 , ukdf['amount'].iloc[-1]=33142226.5603, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27291.2068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26109.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230819   120000    155959  1692431999  ...    723  0.494699 -0.010184     NaN
724  20230819   160000    195959  1692446399  ...    724  0.521104  0.047041     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '181928.9364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25892.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=585
self.closeSec=1692460799, self.tradeDate='20230819', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25885.3, self.close=26201.0, self.high=26216.4, self.low=25858.0, self.vol=50260.815, self.amt=1307814637.88466 127.0.0.1 - - [20/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

2023-08-20 00:00:01,559:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692460799, self.tradeDate='20230819', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25885.3, self.close=26201.0, self.high=26216.4, self.low=25858.0, self.vol=50260.815, self.amt=1307814637.88466 
2023-08-20 00:00:01,576:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230819   040000    075959  ...  36849.478  9.618929e+08 -0.000434
722  20230819   080000    115959  ...  28906.008  7.519707e+08 -0.003206
723  20230819   120000    155959  ...  38367.552  9.932486e+08 -0.001995
724  20230819   160000    195959  ...  26956.868  6.987260e+08 -0.000834
725  20230819   200000    235959  ...  50260.815  1.307815e+09  0.012200

[5 rows x 11 columns]
2023-08-20 00:00:02,298:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230819   040000    075959  1692403199  ...    721  0.431456 -0.149531     NaN
722  20230819   080000    115959  1692417599  ...    722  0.463325 -0.078695     NaN
723  20230819   120000    155959  1692431999  ...    723  0.494699 -0.010184     NaN
724  20230819   160000    195959  1692446399  ...    724  0.521104  0.047041     NaN
725  20230819   200000    235959  1692460799  ...    725  0.534194  0.074744     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '166317.80938548988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26196.08934799', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


