# 20230412 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39189
self.closeSec=1681287599, self.tradeDate='20230412', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30011.9, self.close=30014.0, self.high=30041.2, self.low=30011.9, self.vol=1362.801, self.amt=40921198.2119 
127.0.0.1 - - [12/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-12 16:20:07,405:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230412   155500    155959  ...         0.0        0.0       0
5945  20230412   160000    160459  ...         0.0        0.0       0
5946  20230412   160500    160959  ...         0.0        0.0       0
5947  20230412   161000    161459  ...         0.0        0.0       0
5948  20230412   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 16:20:07,414:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681287599, self.tradeDate='20230412', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30011.9, self.close=30014.0, self.high=30041.2, self.low=30011.9, self.vol=1362.801, self.amt=40921198.2119, ukdf['pct'].iloc[-1]=6.7e-05 , ukdf['amount'].iloc[-1]=40921198.2119, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-811704.05353164208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30018.13364683', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39190
self.closeSec=1681287899, self.tradeDate='20230412', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30014.0, self.close=29964.9, self.high=30014.1, self.low=29964.9, self.vol=1135.098, self.amt=34035440.7762 
2023-04-12 16:25:01,626:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230412   160000    160459  ...         0.0        0.0       0
5946  20230412   160500    160959  ...         0.0        0.0       0
5947  20230412   161000    161459  ...         0.0        0.0       0
5948  20230412   161500    161959  ...         0.0        0.0       0
5949  20230412   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 16:25:01,628:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681287899, self.tradeDate='20230412', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30014.0, self.close=29964.9, self.high=30014.1, self.low=29964.9, self.vol=1135.098, self.amt=34035440.7762, ukdf['pct'].iloc[-1]=-0.001636 , ukdf['amount'].iloc[-1]=34035440.7762, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-808711.5968079056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29968.4052381', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [12/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39751 

self.closeSec=1681286399, self.tradeDate='20230412', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29960.6, self.close=29979.4, self.high=29979.5, self.low=29959.7 
127.0.0.1 - - [12/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39752 

self.closeSec=1681286699, self.tradeDate='20230412', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29979.5, self.close=30008.7, self.high=30008.7, self.low=29979.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39753 

self.closeSec=1681286999, self.tradeDate='20230412', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=30008.6, self.close=30000.2, self.high=30015.9, self.low=29975.2 
127.0.0.1 - - [12/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39754 

self.closeSec=1681287299, self.tradeDate='20230412', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=30000.2, self.close=30012.0, self.high=30018.0, self.low=29999.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39755 

self.closeSec=1681287599, self.tradeDate='20230412', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30011.9, self.close=30014.0, self.high=30041.2, self.low=30011.9 
127.0.0.1 - - [12/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39756 

self.closeSec=1681287899, self.tradeDate='20230412', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30014.0, self.close=29964.9, self.high=30014.1, self.low=29964.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-12 16:00:34,166:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230412    132959  29962.1  ...  51.250000  0.549605  0.546790
5786  20230412    135959  29909.9  ...  51.250000  0.549311  0.568399
5787  20230412    142959  29908.1  ...  51.250000  0.547132  0.589664
5788  20230412    145959  29895.8  ...  51.666667  0.550827  0.607281
5789  20230412    152959  29921.0  ...  51.666667  0.566055  0.614321

[5 rows x 33 columns]
0.5867158671586716
acc is : 0.5867158671586716
2023-04-12 16:00:34,314:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.489379  0.510621       0  ...  1.022690  -1.0    0.0  1.050166
538     1  0.494462  0.505538       0  ...  1.023114  -1.0    0.0  1.049731
539     1  0.496310  0.503690       1  ...  1.022251  -1.0    0.0  1.050615
540     0  0.506103  0.493897       1  ...  1.018623  -1.0    0.0  1.054344
541     0  0.526019  0.473981       0  ...  1.020244  -1.0    0.0  1.052666

[5 rows x 10 columns]
2023-04-12 16:00:34,347:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489362  0.510638       0  ...  1.022690  -1.0    0.0  1.047338
46     1  0.494091  0.505909       0  ...  1.023114  -1.0    0.0  1.046753
47     1  0.496459  0.503541       1  ...  1.022251  -1.0    0.0  1.048381
48     0  0.506411  0.493589       1  ...  1.018623  -1.0    0.0  1.055256
49     0  0.526019  0.473981       0  ...  1.020244  -1.0    0.0  1.052666

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [12/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19873 

self.closeSec=1681284599, self.tradeDate='20230412', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29965.9', self.close='30027.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19874 

self.closeSec=1681285199, self.tradeDate='20230412', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30028.7', self.close='29985.1'
127.0.0.1 - - [12/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19875 

self.closeSec=1681285799, self.tradeDate='20230412', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29985.1', self.close='29971.6'
127.0.0.1 - - [12/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19876 

self.closeSec=1681286399, self.tradeDate='20230412', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29971.7', self.close='29979.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19877 

self.closeSec=1681286999, self.tradeDate='20230412', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29979.5', self.close='30000.2'
127.0.0.1 - - [12/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19878 

self.closeSec=1681287599, self.tradeDate='20230412', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30000.2', self.close='30014'
127.0.0.1 - - [12/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19874 

self.closeSec=1681284599, self.tradeDate='20230412', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29965.9', self.close='30027.2'
127.0.0.1 - - [12/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19875 

self.closeSec=1681285199, self.tradeDate='20230412', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30028.7', self.close='29985.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19876 

self.closeSec=1681285799, self.tradeDate='20230412', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29985.1', self.close='29971.6'
127.0.0.1 - - [12/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19877 

self.closeSec=1681286399, self.tradeDate='20230412', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29971.7', self.close='29979.4'
127.0.0.1 - - [12/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19878 

self.closeSec=1681286999, self.tradeDate='20230412', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29979.5', self.close='30000.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19879 

self.closeSec=1681287599, self.tradeDate='20230412', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30000.2', self.close='30014'
127.0.0.1 - - [12/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19874 

self.closeSec=1681284599, self.tradeDate='20230412', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29965.9', self.close='30027.2'
127.0.0.1 - - [12/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19875 

self.closeSec=1681285199, self.tradeDate='20230412', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30028.7', self.close='29985.1'
127.0.0.1 - - [12/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19876 

self.closeSec=1681285799, self.tradeDate='20230412', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29985.1', self.close='29971.6'
127.0.0.1 - - [12/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19877 

self.closeSec=1681286399, self.tradeDate='20230412', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29971.7', self.close='29979.4'
127.0.0.1 - - [12/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19878 

self.closeSec=1681286999, self.tradeDate='20230412', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29979.5', self.close='30000.2'
127.0.0.1 - - [12/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19879 

self.closeSec=1681287599, self.tradeDate='20230412', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30000.2', self.close='30014'
127.0.0.1 - - [12/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35187
self.closeSec=1681287599, self.tradeDate='20230412', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30011.9, self.close=30014.0, self.high=30041.2, self.low=30011.9, self.vol=1362.801, self.amt=40921198.2119 
127.0.0.1 - - [12/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-12 16:20:07,196:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230412   155500    155959  ...         0.0        0.0       0
5945  20230412   160000    160459  ...         0.0        0.0       0
5946  20230412   160500    160959  ...         0.0        0.0       0
5947  20230412   161000    161459  ...         0.0        0.0       0
5948  20230412   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 16:20:07,205:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681287599, self.tradeDate='20230412', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30011.9, self.close=30014.0, self.high=30041.2, self.low=30011.9, self.vol=1362.801, self.amt=40921198.2119, ukdf['pct'].iloc[-1]=6.7e-05 , ukdf['amount'].iloc[-1]=40921198.2119, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [12/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35188
self.closeSec=1681287899, self.tradeDate='20230412', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30014.0, self.close=29964.9, self.high=30014.1, self.low=29964.9, self.vol=1135.098, self.amt=34035440.7762 
2023-04-12 16:25:01,624:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230412   160000    160459  ...         0.0        0.0       0
5946  20230412   160500    160959  ...         0.0        0.0       0
5947  20230412   161000    161459  ...         0.0        0.0       0
5948  20230412   161500    161959  ...         0.0        0.0       0
5949  20230412   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 16:25:01,624:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681287899, self.tradeDate='20230412', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30014.0, self.close=29964.9, self.high=30014.1, self.low=29964.9, self.vol=1135.098, self.amt=34035440.7762, ukdf['pct'].iloc[-1]=-0.001636 , ukdf['amount'].iloc[-1]=34035440.7762, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230412   040000    075959  1681257599  ...    721  1.211553  1.963309     1.0
722  20230412   080000    115959  1681271999  ...    722  1.214636  1.905647     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '86350.3456244769', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29914.19868846', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=828
self.closeSec=1681286399, self.tradeDate='20230412', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29914.8, self.close=29979.4, self.high=30063.0, self.low=29829.5, self.vol=47788.578, self.amt=1430809077.2251 
127.0.0.1 - - [12/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-04-12 16:00:01,953:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681286399, self.tradeDate='20230412', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29914.8, self.close=29979.4, self.high=30063.0, self.low=29829.5, self.vol=47788.578, self.amt=1430809077.2251 
2023-04-12 16:00:01,985:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230411   200000    235959  ...  117522.262  3.540364e+09  0.004473
720  20230412   000000    035959  ...  112939.472  3.416080e+09 -0.001905
721  20230412   040000    075959  ...   67110.773  2.021571e+09  0.002098
722  20230412   080000    115959  ...   93503.580  2.808320e+09 -0.008955
723  20230412   120000    155959  ...   47788.578  1.430809e+09  0.002159

[5 rows x 11 columns]
2023-04-12 16:00:04,498:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230411   200000    235959  1681228799  ...    719  1.237339  2.179330     1.0
720  20230412   000000    035959  1681243199  ...    720  1.246563  2.120049     1.0
721  20230412   040000    075959  1681257599  ...    721  1.211553  1.963309     1.0
722  20230412   080000    115959  1681271999  ...    722  1.214636  1.905647     1.0
723  20230412   120000    155959  1681286399  ...    723  1.174109  1.754042     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '89774.3925', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29979.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


