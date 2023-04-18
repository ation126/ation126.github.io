# 20230418 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40917
self.closeSec=1681805999, self.tradeDate='20230418', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29767.7, self.close=29716.2, self.high=29767.7, self.low=29713.0, self.vol=1876.549, self.amt=55805289.9927 
127.0.0.1 - - [18/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-18 16:20:07,314:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230418   155500    155959  ...         0.0        0.0       0
5945  20230418   160000    160459  ...         0.0        0.0       0
5946  20230418   160500    160959  ...         0.0        0.0       0
5947  20230418   161000    161459  ...         0.0        0.0       0
5948  20230418   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 16:20:07,324:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681805999, self.tradeDate='20230418', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29767.7, self.close=29716.2, self.high=29767.7, self.low=29713.0, self.vol=1876.549, self.amt=55805289.9927, ukdf['pct'].iloc[-1]=-0.001764 , ukdf['amount'].iloc[-1]=55805289.9927, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-793883.9152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40918
self.closeSec=1681806299, self.tradeDate='20230418', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29716.3, self.close=29732.6, self.high=29736.5, self.low=29716.2, self.vol=747.616, self.amt=22225541.2463 
127.0.0.1 - - [18/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-18 16:25:01,553:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230418   160000    160459  ...         0.0        0.0       0
5946  20230418   160500    160959  ...         0.0        0.0       0
5947  20230418   161000    161459  ...         0.0        0.0       0
5948  20230418   161500    161959  ...         0.0        0.0       0
5949  20230418   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 16:25:01,553:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681806299, self.tradeDate='20230418', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29716.3, self.close=29732.6, self.high=29736.5, self.low=29716.2, self.vol=747.616, self.amt=22225541.2463, ukdf['pct'].iloc[-1]=0.000552 , ukdf['amount'].iloc[-1]=22225541.2463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-794527.7984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29732.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41479 

self.closeSec=1681804799, self.tradeDate='20230418', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29774.9, self.close=29756.9, self.high=29790.0, self.low=29753.4 
127.0.0.1 - - [18/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41480 

self.closeSec=1681805099, self.tradeDate='20230418', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29756.8, self.close=29756.6, self.high=29798.0, self.low=29756.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41481 

self.closeSec=1681805399, self.tradeDate='20230418', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29756.6, self.close=29779.7, self.high=29780.7, self.low=29743.2 
127.0.0.1 - - [18/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41482 

self.closeSec=1681805699, self.tradeDate='20230418', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29779.7, self.close=29768.7, self.high=29818.0, self.low=29763.2 
127.0.0.1 - - [18/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41483 

self.closeSec=1681805999, self.tradeDate='20230418', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29767.7, self.close=29716.2, self.high=29767.7, self.low=29713.0 
127.0.0.1 - - [18/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41484 

self.closeSec=1681806299, self.tradeDate='20230418', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29716.3, self.close=29732.6, self.high=29736.5, self.low=29716.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-18 16:00:34,411:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230418    132959  29480.3  ...  53.333333  0.433954  0.677908
5786  20230418    135959  29526.0  ...  53.333333  0.435138  0.662174
5787  20230418    142959  29530.1  ...  53.750000  0.477111  0.634484
5788  20230418    145959  29688.0  ...  54.166667  0.480823  0.607267
5789  20230418    152959  29703.0  ...  54.166667  0.482610  0.574356

[5 rows x 33 columns]
0.5535055350553506
acc is : 0.5535055350553506
2023-04-18 16:00:34,578:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.536972  0.463028       1  ...  1.093410  -1.0  0.0000  1.054086
538     0  0.529822  0.470178       1  ...  1.087560  -1.0  0.0000  1.059725
539     0  0.569412  0.430588       1  ...  1.086365   1.0 -0.0016  1.060257
540     0  0.538361  0.461639       1  ...  1.086625   1.0  0.0000  1.060511
541     0  0.535453  0.464547       1  ...  1.088337   1.0  0.0000  1.062181

[5 rows x 10 columns]
2023-04-18 16:00:34,615:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.537041  0.462959       1  ...  1.066653  -1.0  0.0000  1.058127
46     0  0.529488  0.470512       1  ...  1.087560  -1.0  0.0000  1.060498
47     0  0.568539  0.431461       1  ...  1.069384   1.0 -0.0016  1.059709
48     0  0.537936  0.462064       1  ...  1.086625   1.0  0.0000  1.060212
49     0  0.535453  0.464547       1  ...  1.088337   1.0  0.0000  1.062181

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20737 

self.closeSec=1681802999, self.tradeDate='20230418', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29683.7', self.close='29710.1'
127.0.0.1 - - [18/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20738 

self.closeSec=1681803599, self.tradeDate='20230418', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29710.2', self.close='29727'
127.0.0.1 - - [18/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20739 

self.closeSec=1681804199, self.tradeDate='20230418', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29726.9', self.close='29762.1'
127.0.0.1 - - [18/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20740 

self.closeSec=1681804799, self.tradeDate='20230418', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29762.2', self.close='29756.9'
127.0.0.1 - - [18/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20741 

self.closeSec=1681805399, self.tradeDate='20230418', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29756.8', self.close='29779.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20742 

self.closeSec=1681805999, self.tradeDate='20230418', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29779.7', self.close='29716.2'
127.0.0.1 - - [18/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20738 

self.closeSec=1681802999, self.tradeDate='20230418', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29683.7', self.close='29710.1'
127.0.0.1 - - [18/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [18/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20739 

self.closeSec=1681803599, self.tradeDate='20230418', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29710.2', self.close='29727'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20740 

self.closeSec=1681804199, self.tradeDate='20230418', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29726.9', self.close='29762.1'
127.0.0.1 - - [18/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20741 

self.closeSec=1681804799, self.tradeDate='20230418', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29762.2', self.close='29756.9'
127.0.0.1 - - [18/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20742 

self.closeSec=1681805399, self.tradeDate='20230418', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29756.8', self.close='29779.7'
127.0.0.1 - - [18/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20743 

self.closeSec=1681805999, self.tradeDate='20230418', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29779.7', self.close='29716.2'
127.0.0.1 - - [18/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20738 

self.closeSec=1681802999, self.tradeDate='20230418', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29683.7', self.close='29710.1'
127.0.0.1 - - [18/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20739 

self.closeSec=1681803599, self.tradeDate='20230418', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29710.2', self.close='29727'
127.0.0.1 - - [18/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20740 

self.closeSec=1681804199, self.tradeDate='20230418', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29726.9', self.close='29762.1'
127.0.0.1 - - [18/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20741 

self.closeSec=1681804799, self.tradeDate='20230418', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29762.2', self.close='29756.9'
127.0.0.1 - - [18/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20742 

self.closeSec=1681805399, self.tradeDate='20230418', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29756.8', self.close='29779.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20743 

self.closeSec=1681805999, self.tradeDate='20230418', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29779.7', self.close='29716.2'
127.0.0.1 - - [18/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36915
self.closeSec=1681805999, self.tradeDate='20230418', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29767.7, self.close=29716.2, self.high=29767.7, self.low=29713.0, self.vol=1876.549, self.amt=55805289.9927 
127.0.0.1 - - [18/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-18 16:20:07,033:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230418   155500    155959  ...         0.0        0.0       0
5945  20230418   160000    160459  ...         0.0        0.0       0
5946  20230418   160500    160959  ...         0.0        0.0       0
5947  20230418   161000    161459  ...         0.0        0.0       0
5948  20230418   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 16:20:07,044:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681805999, self.tradeDate='20230418', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29767.7, self.close=29716.2, self.high=29767.7, self.low=29713.0, self.vol=1876.549, self.amt=55805289.9927, ukdf['pct'].iloc[-1]=-0.001764 , ukdf['amount'].iloc[-1]=55805289.9927, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [18/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36916
self.closeSec=1681806299, self.tradeDate='20230418', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29716.3, self.close=29732.6, self.high=29736.5, self.low=29716.2, self.vol=747.616, self.amt=22225541.2463 
2023-04-18 16:25:01,593:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230418   160000    160459  ...         0.0        0.0       0
5946  20230418   160500    160959  ...         0.0        0.0       0
5947  20230418   161000    161459  ...         0.0        0.0       0
5948  20230418   161500    161959  ...         0.0        0.0       0
5949  20230418   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 16:25:01,593:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681806299, self.tradeDate='20230418', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29716.3, self.close=29732.6, self.high=29736.5, self.low=29716.2, self.vol=747.616, self.amt=22225541.2463, ukdf['pct'].iloc[-1]=0.000552 , ukdf['amount'].iloc[-1]=22225541.2463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230418   040000    075959  1681775999  ...    721  0.613656  0.278546     NaN
722  20230418   080000    115959  1681790399  ...    722  0.645747  0.337719     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '61055.5772883987', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29432.53119658', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [18/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=864
self.closeSec=1681804799, self.tradeDate='20230418', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29431.6, self.close=29756.9, self.high=29790.0, self.low=29426.6, self.vol=59863.929, self.amt=1773491572.32266 
2023-04-18 16:00:02,025:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681804799, self.tradeDate='20230418', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29431.6, self.close=29756.9, self.high=29790.0, self.low=29426.6, self.vol=59863.929, self.amt=1773491572.32266 
2023-04-18 16:00:02,069:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230417   200000    235959  ...  131855.384  3.877899e+09 -0.007159
720  20230418   000000    035959  ...   55045.794  1.621368e+09  0.003854
721  20230418   040000    075959  ...   29840.920  8.786944e+08 -0.001344
722  20230418   080000    115959  ...   65673.966  1.925481e+09  0.000398
723  20230418   120000    155959  ...   59863.929  1.773492e+09  0.011049

[5 rows x 11 columns]
2023-04-18 16:00:04,831:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230417   200000    235959  1681747199  ...    719  0.416468 -0.132860     NaN
720  20230418   000000    035959  1681761599  ...    720  0.528920  0.103449     NaN
721  20230418   040000    075959  1681775999  ...    721  0.613656  0.278546     NaN
722  20230418   080000    115959  1681790399  ...    722  0.645747  0.337719     NaN
723  20230418   120000    155959  1681804799  ...    723  0.633434  0.301390     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '78173.829', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29758.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


