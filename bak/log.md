# 20230419 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41205
self.closeSec=1681892399, self.tradeDate='20230419', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29440.0, self.close=29406.1, self.high=29538.0, self.low=29362.5, self.vol=9563.068, self.amt=281770861.7907 
127.0.0.1 - - [19/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-19 16:20:06,937:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230419   155500    155959  ...         0.0        0.0       0
5945  20230419   160000    160459  ...         0.0        0.0       0
5946  20230419   160500    160959  ...         0.0        0.0       0
5947  20230419   161000    161459  ...         0.0        0.0       0
5948  20230419   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 16:20:06,951:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681892399, self.tradeDate='20230419', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29440.0, self.close=29406.1, self.high=29538.0, self.low=29362.5, self.vol=9563.068, self.amt=281770861.7907, ukdf['pct'].iloc[-1]=-0.001155 , ukdf['amount'].iloc[-1]=281770861.7907, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-774681.7536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29402.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41206
self.closeSec=1681892699, self.tradeDate='20230419', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29406.9, self.close=29190.1, self.high=29420.3, self.low=28800.0, self.vol=25986.592, self.amt=758008469.82471 
2023-04-19 16:25:01,569:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230419   160000    160459  ...         0.0        0.0       0
5946  20230419   160500    160959  ...         0.0        0.0       0
5947  20230419   161000    161459  ...         0.0        0.0       0
5948  20230419   161500    161959  ...         0.0        0.0       0
5949  20230419   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 16:25:01,570:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681892699, self.tradeDate='20230419', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29406.9, self.close=29190.1, self.high=29420.3, self.low=28800.0, self.vol=25986.592, self.amt=758008469.82471, ukdf['pct'].iloc[-1]=-0.007345 , ukdf['amount'].iloc[-1]=758008469.82471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-762781.81815335088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29205.14781563', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41767 

self.closeSec=1681891199, self.tradeDate='20230419', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30042.0, self.close=30064.8, self.high=30077.8, self.low=30042.0 
127.0.0.1 - - [19/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41768 

self.closeSec=1681891499, self.tradeDate='20230419', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=30064.7, self.close=30026.5, self.high=30067.1, self.low=29972.0 
127.0.0.1 - - [19/Apr/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41769 

self.closeSec=1681891799, self.tradeDate='20230419', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=30028.5, self.close=29780.3, self.high=30054.0, self.low=29501.4 
127.0.0.1 - - [19/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41770 

self.closeSec=1681892099, self.tradeDate='20230419', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29786.8, self.close=29440.1, self.high=29818.6, self.low=29200.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41771 

self.closeSec=1681892399, self.tradeDate='20230419', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29440.0, self.close=29406.1, self.high=29538.0, self.low=29362.5 
127.0.0.1 - - [19/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41772 

self.closeSec=1681892699, self.tradeDate='20230419', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29406.9, self.close=29190.1, self.high=29420.3, self.low=28800.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-19 16:00:34,838:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230419    132959  30189.9  ...  52.500000  0.536643  0.251824
5786  20230419    135959  30213.2  ...  52.500000  0.544012  0.258955
5787  20230419    142959  30254.0  ...  52.083333  0.512632  0.282633
5788  20230419    145959  30100.0  ...  51.666667  0.491882  0.317736
5789  20230419    152959  29989.9  ...  52.083333  0.511510  0.342764

[5 rows x 33 columns]
0.5276752767527675
acc is : 0.5276752767527675
2023-04-19 16:00:35,003:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.513415  0.486585       1  ...  1.059327   1.0    0.0  1.085197
538     0  0.514831  0.485169       0  ...  1.053938   1.0    0.0  1.079677
539     1  0.469175  0.530825       0  ...  1.050076   1.0    0.0  1.075721
540     1  0.468997  0.531003       1  ...  1.053833   1.0    0.0  1.079569
541     0  0.521103  0.478897       0  ...  1.052702   1.0    0.0  1.078411

[5 rows x 10 columns]
2023-04-19 16:00:35,040:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512702  0.487298       1  ...  1.059327   1.0    0.0  1.085485
46     0  0.513728  0.486272       0  ...  1.041206   1.0    0.0  1.077169
47     1  0.468586  0.531414       0  ...  1.050076   1.0    0.0  1.075104
48     1  0.468676  0.531324       1  ...  1.053833   1.0    0.0  1.079109
49     0  0.521103  0.478897       0  ...  1.052702   1.0    0.0  1.078411

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20881 

self.closeSec=1681889399, self.tradeDate='20230419', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30048.4', self.close='30095.8'
127.0.0.1 - - [19/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20882 

self.closeSec=1681889999, self.tradeDate='20230419', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30095.8', self.close='30084.6'
127.0.0.1 - - [19/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20883 

self.closeSec=1681890599, self.tradeDate='20230419', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30084.6', self.close='30079.8'
127.0.0.1 - - [19/Apr/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20884 

self.closeSec=1681891199, self.tradeDate='20230419', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30079.7', self.close='30064.8'
127.0.0.1 - - [19/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20885 

self.closeSec=1681891799, self.tradeDate='20230419', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30064.7', self.close='29780.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20886 

self.closeSec=1681892399, self.tradeDate='20230419', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29786.8', self.close='29406.1'
127.0.0.1 - - [19/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20882 

self.closeSec=1681889399, self.tradeDate='20230419', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30048.4', self.close='30095.8'
127.0.0.1 - - [19/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20883 

self.closeSec=1681889999, self.tradeDate='20230419', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30095.8', self.close='30084.6'
127.0.0.1 - - [19/Apr/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20884 

self.closeSec=1681890599, self.tradeDate='20230419', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30084.6', self.close='30079.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20885 

self.closeSec=1681891199, self.tradeDate='20230419', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30079.7', self.close='30064.8'
127.0.0.1 - - [19/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20886 

self.closeSec=1681891799, self.tradeDate='20230419', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30064.7', self.close='29780.3'
127.0.0.1 - - [19/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20887 

self.closeSec=1681892399, self.tradeDate='20230419', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29786.8', self.close='29406.1'
127.0.0.1 - - [19/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20882 

self.closeSec=1681889399, self.tradeDate='20230419', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30048.4', self.close='30095.8'
127.0.0.1 - - [19/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20883 

self.closeSec=1681889999, self.tradeDate='20230419', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30095.8', self.close='30084.6'
127.0.0.1 - - [19/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20884 

self.closeSec=1681890599, self.tradeDate='20230419', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30084.6', self.close='30079.8'
127.0.0.1 - - [19/Apr/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20885 

self.closeSec=1681891199, self.tradeDate='20230419', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30079.7', self.close='30064.8'
127.0.0.1 - - [19/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20886 

self.closeSec=1681891799, self.tradeDate='20230419', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30064.7', self.close='29780.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20887 

self.closeSec=1681892399, self.tradeDate='20230419', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29786.8', self.close='29406.1'
127.0.0.1 - - [19/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37203
self.closeSec=1681892399, self.tradeDate='20230419', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29440.0, self.close=29406.1, self.high=29538.0, self.low=29362.5, self.vol=9563.068, self.amt=281770861.7907 
127.0.0.1 - - [19/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-19 16:20:06,886:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230419   155500    155959  ...         0.0        0.0       0
5945  20230419   160000    160459  ...         0.0        0.0       0
5946  20230419   160500    160959  ...         0.0        0.0       0
5947  20230419   161000    161459  ...         0.0        0.0       0
5948  20230419   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 16:20:06,890:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681892399, self.tradeDate='20230419', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29440.0, self.close=29406.1, self.high=29538.0, self.low=29362.5, self.vol=9563.068, self.amt=281770861.7907, ukdf['pct'].iloc[-1]=-0.001155 , ukdf['amount'].iloc[-1]=281770861.7907, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37204
self.closeSec=1681892699, self.tradeDate='20230419', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29406.9, self.close=29190.1, self.high=29420.3, self.low=28800.0, self.vol=25986.592, self.amt=758008469.82471 
2023-04-19 16:25:01,603:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230419   160000    160459  ...         0.0        0.0       0
5946  20230419   160500    160959  ...         0.0        0.0       0
5947  20230419   161000    161459  ...         0.0        0.0       0
5948  20230419   161500    161959  ...         0.0        0.0       0
5949  20230419   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 16:25:01,604:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681892699, self.tradeDate='20230419', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29406.9, self.close=29190.1, self.high=29420.3, self.low=28800.0, self.vol=25986.592, self.amt=758008469.82471, ukdf['pct'].iloc[-1]=-0.007345 , ukdf['amount'].iloc[-1]=758008469.82471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230419   040000    075959  1681862399  ...    721  0.532673  0.046307     NaN
722  20230419   080000    115959  1681876799  ...    722  0.531656  0.035613     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '101394.80420126985', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30200.67795299', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--: 127.0.0.1 - - [19/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=870
self.closeSec=1681891199, self.tradeDate='20230419', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30199.9, self.close=30064.8, self.high=30326.9, self.low=29960.0, self.vol=57670.911, self.amt=1737069433.9142 
2023-04-19 16:00:01,853:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681891199, self.tradeDate='20230419', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30199.9, self.close=30064.8, self.high=30326.9, self.low=29960.0, self.vol=57670.911, self.amt=1737069433.9142 
2023-04-19 16:00:01,934:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230418   200000    235959  ...  143790.876  4.354220e+09 -0.006569
720  20230419   000000    035959  ...   89098.270  2.684624e+09  0.001180
721  20230419   040000    075959  ...   54391.463  1.649457e+09  0.005297
722  20230419   080000    115959  ...   42292.844  1.279349e+09 -0.005463
723  20230419   120000    155959  ...   57670.911  1.737069e+09 -0.004474

[5 rows x 11 columns]
2023-04-19 16:00:04,173:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230418   200000    235959  1681833599  ...    719  0.515898  0.025734     NaN
720  20230419   000000    035959  1681847999  ...    720  0.524155  0.036081     NaN
721  20230419   040000    075959  1681862399  ...    721  0.532673  0.046307     NaN
722  20230419   080000    115959  1681876799  ...    722  0.531656  0.035613     NaN
723  20230419   120000    155959  1681891199  ...    723  0.515285 -0.009071     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '94306.78253557125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30065.70657975', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


