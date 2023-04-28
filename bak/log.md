# 20230428 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43797
self.closeSec=1682669999, self.tradeDate='20230428', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29412.5, self.close=29367.9, self.high=29412.6, self.low=29326.0, self.vol=3280.874, self.amt=96349428.3731 
127.0.0.1 - - [28/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-28 16:20:06,351:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230428   155500    155959  ...         0.0        0.0       0
5945  20230428   160000    160459  ...         0.0        0.0       0
5946  20230428   160500    160959  ...         0.0        0.0       0
5947  20230428   161000    161459  ...         0.0        0.0       0
5948  20230428   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 16:20:06,362:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682669999, self.tradeDate='20230428', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29412.5, self.close=29367.9, self.high=29412.6, self.low=29326.0, self.vol=3280.874, self.amt=96349428.3731, ukdf['pct'].iloc[-1]=-0.001516 , ukdf['amount'].iloc[-1]=96349428.3731, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-772372.08531351392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29364.51811542', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43798
self.closeSec=1682670299, self.tradeDate='20230428', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29367.9, self.close=29361.5, self.high=29388.2, self.low=29360.0, self.vol=1384.872, self.amt=40676768.0878 
127.0.0.1 - - [28/Apr/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-04-28 16:25:02,100:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230428   160000    160459  ...         0.0        0.0       0
5946  20230428   160500    160959  ...         0.0        0.0       0
5947  20230428   161000    161459  ...         0.0        0.0       0
5948  20230428   161500    161959  ...         0.0        0.0       0
5949  20230428   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 16:25:02,100:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682670299, self.tradeDate='20230428', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29367.9, self.close=29361.5, self.high=29388.2, self.low=29360.0, self.vol=1384.872, self.amt=40676768.0878, ukdf['pct'].iloc[-1]=-0.000218 , ukdf['amount'].iloc[-1]=40676768.0878, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-772372.16648311504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29364.51946429', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [28/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44359 

self.closeSec=1682668799, self.tradeDate='20230428', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29483.9, self.close=29473.9, self.high=29488.9, self.low=29451.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44360 

self.closeSec=1682669099, self.tradeDate='20230428', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29473.8, self.close=29442.6, self.high=29493.7, self.low=29440.3 
127.0.0.1 - - [28/Apr/2023 16:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44361 

self.closeSec=1682669399, self.tradeDate='20230428', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29442.6, self.close=29419.9, self.high=29452.0, self.low=29403.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44362 

self.closeSec=1682669699, self.tradeDate='20230428', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29420.0, self.close=29412.5, self.high=29422.5, self.low=29400.1 
127.0.0.1 - - [28/Apr/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44363 

self.closeSec=1682669999, self.tradeDate='20230428', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29412.5, self.close=29367.9, self.high=29412.6, self.low=29326.0 
127.0.0.1 - - [28/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 16:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44364 

self.closeSec=1682670299, self.tradeDate='20230428', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29367.9, self.close=29361.5, self.high=29388.2, self.low=29360.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-28 16:00:18,629:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230428    132959  29489.8  ...  54.166667  0.546323  0.318254
5786  20230428    135959  29475.6  ...  54.166667  0.544969  0.320280
5787  20230428    142959  29462.8  ...  53.750000  0.540671  0.324302
5788  20230428    145959  29423.1  ...  54.166667  0.543991  0.326127
5789  20230428    152959  29459.0  ...  53.750000  0.541855  0.328862

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-04-28 16:00:18,743:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.498616  0.501384       0  ...  0.832386   1.0    0.0  0.987594
538     0  0.501290  0.498710       0  ...  0.831259   1.0    0.0  0.986257
539     0  0.500998  0.499002       1  ...  0.832279   1.0    0.0  0.987467
540     0  0.512227  0.487773       0  ...  0.831734   1.0    0.0  0.986820
541     1  0.493581  0.506419       1  ...  0.832697   1.0    0.0  0.987963

[5 rows x 10 columns]
2023-04-28 16:00:18,771:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497763  0.502237       0  ...  0.838070   1.0    0.0  0.971901
46     0  0.500817  0.499183       0  ...  0.836935   1.0    0.0  0.972202
47     0  0.500116  0.499884       1  ...  0.837962   1.0    0.0  0.972678
48     0  0.511795  0.488205       0  ...  0.837413   1.0    0.0  0.980098
49     1  0.493581  0.506419       1  ...  0.832697   1.0    0.0  0.987963

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22177 

self.closeSec=1682666999, self.tradeDate='20230428', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29487.7', self.close='29439.8'
127.0.0.1 - - [28/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22178 

self.closeSec=1682667599, self.tradeDate='20230428', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29439.8', self.close='29449.7'
127.0.0.1 - - [28/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22179 

self.closeSec=1682668199, self.tradeDate='20230428', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29449.8', self.close='29506.6'
127.0.0.1 - - [28/Apr/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22180 

self.closeSec=1682668799, self.tradeDate='20230428', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29506.7', self.close='29473.9'
127.0.0.1 - - [28/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22181 

self.closeSec=1682669399, self.tradeDate='20230428', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29473.8', self.close='29419.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22182 

self.closeSec=1682669999, self.tradeDate='20230428', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29420', self.close='29367.9'
127.0.0.1 - - [28/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22178 

self.closeSec=1682666999, self.tradeDate='20230428', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29487.7', self.close='29439.8'
127.0.0.1 - - [28/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22179 

self.closeSec=1682667599, self.tradeDate='20230428', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29439.8', self.close='29449.7'
127.0.0.1 - - [28/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22180 

self.closeSec=1682668199, self.tradeDate='20230428', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29449.8', self.close='29506.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22181 

self.closeSec=1682668799, self.tradeDate='20230428', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29506.7', self.close='29473.9'
127.0.0.1 - - [28/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22182 

self.closeSec=1682669399, self.tradeDate='20230428', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29473.8', self.close='29419.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22183 

self.closeSec=1682669999, self.tradeDate='20230428', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29420', self.close='29367.9'
127.0.0.1 - - [28/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22178 

self.closeSec=1682666999, self.tradeDate='20230428', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29487.7', self.close='29439.8'
127.0.0.1 - - [28/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22179 

self.closeSec=1682667599, self.tradeDate='20230428', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29439.8', self.close='29449.7'
127.0.0.1 - - [28/Apr/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22180 

self.closeSec=1682668199, self.tradeDate='20230428', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29449.8', self.close='29506.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22181 

self.closeSec=1682668799, self.tradeDate='20230428', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29506.7', self.close='29473.9'
127.0.0.1 - - [28/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22182 

self.closeSec=1682669399, self.tradeDate='20230428', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29473.8', self.close='29419.9'
127.0.0.1 - - [28/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22183 

self.closeSec=1682669999, self.tradeDate='20230428', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29420', self.close='29367.9'
127.0.0.1 - - [28/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39795
self.closeSec=1682669999, self.tradeDate='20230428', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29412.5, self.close=29367.9, self.high=29412.6, self.low=29326.0, self.vol=3280.874, self.amt=96349428.3731 
127.0.0.1 - - [28/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-28 16:20:06,253:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230428   155500    155959  ...         0.0        0.0       0
5945  20230428   160000    160459  ...         0.0        0.0       0
5946  20230428   160500    160959  ...         0.0        0.0       0
5947  20230428   161000    161459  ...         0.0        0.0       0
5948  20230428   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 16:20:06,271:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682669999, self.tradeDate='20230428', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29412.5, self.close=29367.9, self.high=29412.6, self.low=29326.0, self.vol=3280.874, self.amt=96349428.3731, ukdf['pct'].iloc[-1]=-0.001516 , ukdf['amount'].iloc[-1]=96349428.3731, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39796
self.closeSec=1682670299, self.tradeDate='20230428', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29367.9, self.close=29361.5, self.high=29388.2, self.low=29360.0, self.vol=1384.872, self.amt=40676768.0878 
127.0.0.1 - - [28/Apr/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-04-28 16:25:02,103:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230428   160000    160459  ...         0.0        0.0       0
5946  20230428   160500    160959  ...         0.0        0.0       0
5947  20230428   161000    161459  ...         0.0        0.0       0
5948  20230428   161500    161959  ...         0.0        0.0       0
5949  20230428   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 16:25:02,103:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682670299, self.tradeDate='20230428', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29367.9, self.close=29361.5, self.high=29388.2, self.low=29360.0, self.vol=1384.872, self.amt=40676768.0878, ukdf['pct'].iloc[-1]=-0.000218 , ukdf['amount'].iloc[-1]=40676768.0878, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230428   040000    075959  1682639999  ...    721  0.951217  0.942706     1.0
722  20230428   080000    115959  1682654399  ...    722  0.840334  0.570203     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '21705.456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29412.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1352827.6996185002, self.flagDict['side']='buy', self.tradeCount=32, self.count=924
self.closeSec=1682668799, self.tradeDate='20230428', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29412.8, self.close=29473.9, self.high=29560.9, self.low=29382.9, self.vol=49552.737, self.amt=1460038950.94074 
127.0.0.1 - - [28/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-04-28 16:00:02,003:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682668799, self.tradeDate='20230428', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29412.8, self.close=29473.9, self.high=29560.9, self.low=29382.9, self.vol=49552.737, self.amt=1460038950.94074 
2023-04-28 16:00:02,045:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230427   200000    235959  ...  206699.481  6.004047e+09  0.007451
720  20230428   000000    035959  ...  204824.129  6.045769e+09  0.017957
721  20230428   040000    075959  ...   98577.491  2.912385e+09 -0.006773
722  20230428   080000    115959  ...   78696.354  2.317531e+09 -0.001568
723  20230428   120000    155959  ...   49552.737  1.460039e+09  0.002077

[5 rows x 11 columns]
2023-04-28 16:00:03,897:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230427   200000    235959  1682611199  ...    719  0.972886  0.997366     1.0
720  20230428   000000    035959  1682625599  ...    720  1.016249  1.156824     1.0
721  20230428   040000    075959  1682639999  ...    721  0.951217  0.942706     1.0
722  20230428   080000    115959  1682654399  ...    722  0.840334  0.570203     NaN
723  20230428   120000    155959  1682668799  ...    723  0.759440  0.298279     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '24573.0087', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29473.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


