# 20231014 16:26:07

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44116
self.closeSec=1697271599, self.tradeDate='20231014', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26841.8, self.close=26847.9, self.high=26847.9, self.low=26840.3, self.vol=296.58, self.amt=7960998.4758 
127.0.0.1 - - [14/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-14 16:20:08,512:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231014   155500    155959  ...         0.0        0.0       0
5952  20231014   160000    160459  ...         0.0        0.0       0
5953  20231014   160500    160959  ...         0.0        0.0       0
5954  20231014   161000    161459  ...         0.0        0.0       0
5955  20231014   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 16:20:08,522:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697271599, self.tradeDate='20231014', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26841.8, self.close=26847.9, self.high=26847.9, self.low=26840.3, self.vol=296.58, self.amt=7960998.4758, ukdf['pct'].iloc[-1]=0.000227 , ukdf['amount'].iloc[-1]=7960998.4758, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '236.742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26847.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44117
self.closeSec=1697271899, self.tradeDate='20231014', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26847.9, self.close=26847.6, self.high=26850.8, self.low=26847.5, self.vol=116.962, self.amt=3140412.3535 
127.0.0.1 - - [14/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-14 16:25:03,219:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231014   160000    160459  ...         0.0        0.0       0
5953  20231014   160500    160959  ...         0.0        0.0       0
5954  20231014   161000    161459  ...         0.0        0.0       0
5955  20231014   161500    161959  ...         0.0        0.0       0
5956  20231014   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 16:25:03,231:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697271899, self.tradeDate='20231014', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26847.9, self.close=26847.6, self.high=26850.8, self.low=26847.5, self.vol=116.962, self.amt=3140412.3535, ukdf['pct'].iloc[-1]=-1.1e-05 , ukdf['amount'].iloc[-1]=3140412.3535, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '215.26912209132', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26849.44192718', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44114 

self.closeSec=1697270399, self.tradeDate='20231014', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26852.1, self.close=26857.0, self.high=26857.0, self.low=26845.8 
127.0.0.1 - - [14/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44115 

self.closeSec=1697270699, self.tradeDate='20231014', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26860.4, self.close=26865.8, self.high=26874.5, self.low=26860.4 
127.0.0.1 - - [14/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44116 

self.closeSec=1697270999, self.tradeDate='20231014', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26865.8, self.close=26862.1, self.high=26869.0, self.low=26862.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44117 

self.closeSec=1697271299, self.tradeDate='20231014', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26862.2, self.close=26841.8, self.high=26862.2, self.low=26840.3 
127.0.0.1 - - [14/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44118 

self.closeSec=1697271599, self.tradeDate='20231014', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26841.8, self.close=26847.9, self.high=26847.9, self.low=26840.3 
127.0.0.1 - - [14/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44119 

self.closeSec=1697271899, self.tradeDate='20231014', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26847.9, self.close=26847.6, self.high=26850.8, self.low=26847.5 
127.0.0.1 - - [14/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-14 16:00:17,844:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231014    132959  26896.5  ...  49.583333  0.518128  0.510276
5786  20231014    135959  26919.1  ...  49.583333  0.504568  0.512734
5787  20231014    142959  26874.2  ...  49.166667  0.496623  0.519007
5788  20231014    145959  26847.3  ...  49.166667  0.497793  0.524285
5789  20231014    152959  26851.1  ...  49.583333  0.499194  0.528531

[5 rows x 33 columns]
0.5553505535055351
acc is : 0.5553505535055351
2023-10-14 16:00:17,909:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.505668  0.494332       0  ...  0.940088   1.0    0.0  0.980166
538     1  0.481312  0.518688       0  ...  0.939147   1.0    0.0  0.979185
539     1  0.483810  0.516190       1  ...  0.939283   1.0    0.0  0.979327
540     1  0.493754  0.506246       1  ...  0.939444   1.0    0.0  0.979495
541     1  0.494445  0.505555       1  ...  0.939486   1.0    0.0  0.979539

[5 rows x 10 columns]
2023-10-14 16:00:17,920:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505358  0.494642       0  ...  0.940088   1.0    0.0  0.975803
46     1  0.481288  0.518712       0  ...  0.939147   1.0    0.0  0.975627
47     1  0.483946  0.516054       1  ...  0.939283   1.0    0.0  0.977057
48     1  0.493729  0.506271       1  ...  0.939444   1.0    0.0  0.975273
49     1  0.494445  0.505555       1  ...  0.939486   1.0    0.0  0.979539

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.627', 'enterprice': '27009.6', 'countrevence': '0', 'unrealprofit': '-3522.7857', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26860.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22055 

self.closeSec=1697268599, self.tradeDate='20231014', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26860.5', self.close='26855.8'
127.0.0.1 - - [14/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22056 

self.closeSec=1697269199, self.tradeDate='20231014', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26855.8', self.close='26855.8'
127.0.0.1 - - [14/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22057 

self.closeSec=1697269799, self.tradeDate='20231014', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26855.8', self.close='26852.4'
127.0.0.1 - - [14/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22058 

self.closeSec=1697270399, self.tradeDate='20231014', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26852.3', self.close='26857'

--handleKline--: 127.0.0.1 - - [14/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22059 

self.closeSec=1697270999, self.tradeDate='20231014', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26860.4', self.close='26862.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22060 

self.closeSec=1697271599, self.tradeDate='20231014', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26862.2', self.close='26847.9'
127.0.0.1 - - [14/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [14/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22058 

self.closeSec=1697268599, self.tradeDate='20231014', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26860.5', self.close='26855.8'
127.0.0.1 - - [14/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22059 

self.closeSec=1697269199, self.tradeDate='20231014', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26855.8', self.close='26855.8'
127.0.0.1 - - [14/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22060 

self.closeSec=1697269799, self.tradeDate='20231014', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26855.8', self.close='26852.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22061 

self.closeSec=1697270399, self.tradeDate='20231014', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26852.3', self.close='26857'
127.0.0.1 - - [14/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22062 

self.closeSec=1697270999, self.tradeDate='20231014', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26860.4', self.close='26862.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22063 

self.closeSec=1697271599, self.tradeDate='20231014', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26862.2', self.close='26847.9'
127.0.0.1 - - [14/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22058 

self.closeSec=1697268599, self.tradeDate='20231014', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26860.5', self.close='26855.8'
127.0.0.1 - - [14/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22059 

self.closeSec=1697269199, self.tradeDate='20231014', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26855.8', self.close='26855.8'
127.0.0.1 - - [14/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22060 

self.closeSec=1697269799, self.tradeDate='20231014', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26855.8', self.close='26852.4'
127.0.0.1 - - [14/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22061 

self.closeSec=1697270399, self.tradeDate='20231014', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26852.3', self.close='26857'
127.0.0.1 - - [14/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22062 

self.closeSec=1697270999, self.tradeDate='20231014', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26860.4', self.close='26862.1'
127.0.0.1 - - [14/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22063 

self.closeSec=1697271599, self.tradeDate='20231014', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26862.2', self.close='26847.9'
127.0.0.1 - - [14/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44116
self.closeSec=1697271599, self.tradeDate='20231014', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26841.8, self.close=26847.9, self.high=26847.9, self.low=26840.3, self.vol=296.58, self.amt=7960998.4758 
127.0.0.1 - - [14/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-14 16:20:08,511:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231014   155500    155959  ...         0.0        0.0       0
5952  20231014   160000    160459  ...         0.0        0.0       0
5953  20231014   160500    160959  ...         0.0        0.0       0
5954  20231014   161000    161459  ...         0.0        0.0       0
5955  20231014   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 16:20:08,514:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697271599, self.tradeDate='20231014', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26841.8, self.close=26847.9, self.high=26847.9, self.low=26840.3, self.vol=296.58, self.amt=7960998.4758, ukdf['pct'].iloc[-1]=0.000227 , ukdf['amount'].iloc[-1]=7960998.4758, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '144.8499', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26847.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44117
self.closeSec=1697271899, self.tradeDate='20231014', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26847.9, self.close=26847.6, self.high=26850.8, self.low=26847.5, self.vol=116.962, self.amt=3140412.3535 
127.0.0.1 - - [14/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-14 16:25:03,219:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231014   160000    160459  ...         0.0        0.0       0
5953  20231014   160500    160959  ...         0.0        0.0       0
5954  20231014   161000    161459  ...         0.0        0.0       0
5955  20231014   161500    161959  ...         0.0        0.0       0
5956  20231014   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 16:25:03,231:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697271899, self.tradeDate='20231014', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26847.9, self.close=26847.6, self.high=26850.8, self.low=26847.5, self.vol=116.962, self.amt=3140412.3535, ukdf['pct'].iloc[-1]=-1.1e-05 , ukdf['amount'].iloc[-1]=3140412.3535, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '202.11861739238', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26849.44192718', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231014   040000    075959  1697241599  ...    721  0.804414  0.629649     1.0
722  20231014   080000    115959  1697255999  ...    722  0.845632  0.747851     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '4384.671', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26919.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1263543.0464457, self.flagDict['side']='buy', self.tradeCount=33, self.count=919
self.closeSec=1697270399, self.tradeDate='20231014', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26918.2, self.close=26860.5, self.high=26926.4, self.low=26828.4, self.vol=14754.421, self.amt=396536683.5063 
127.0.0.1 - - [14/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-14 16:00:01,518:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697270399, self.tradeDate='20231014', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26918.2, self.close=26860.5, self.high=26926.4, self.low=26828.4, self.vol=14754.421, self.amt=396536683.5063 
2023-10-14 16:00:01,546:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231013   200000    235959  ...  52873.068  1.417818e+09 -0.004368
720  20231014   000000    035959  ...  24418.280  6.530784e+08  0.002821
721  20231014   040000    075959  ...  93383.298  2.515112e+09  0.003048
722  20231014   080000    115959  ...  19650.989  5.285537e+08  0.002544
723  20231014   120000    155959  ...  14754.421  3.965367e+08 -0.002140

[5 rows x 11 columns]
2023-10-14 16:00:02,641:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231013   200000    235959  1697212799  ...    719  0.846559  0.756405     1.0
720  20231014   000000    035959  1697227199  ...    720  0.868009  0.813295     1.0
721  20231014   040000    075959  1697241599  ...    721  0.804414  0.629649     1.0
722  20231014   080000    115959  1697255999  ...    722  0.845632  0.747851     1.0
723  20231014   120000    155959  1697270399  ...    723  0.832137  0.715226     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '1584.1392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26860.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


