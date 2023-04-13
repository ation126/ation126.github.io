# 20230413 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39477
self.closeSec=1681373999, self.tradeDate='20230413', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30032.9, self.close=30033.2, self.high=30036.2, self.low=30025.7, self.vol=599.07, self.amt=17990751.1928 
127.0.0.1 - - [13/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-13 16:20:07,319:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230413   155500    155959  ...         0.0        0.0       0
5945  20230413   160000    160459  ...         0.0        0.0       0
5946  20230413   160500    160959  ...         0.0        0.0       0
5947  20230413   161000    161459  ...         0.0        0.0       0
5948  20230413   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 16:20:07,322:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681373999, self.tradeDate='20230413', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30032.9, self.close=30033.2, self.high=30036.2, self.low=30025.7, self.vol=599.07, self.amt=17990751.1928, ukdf['pct'].iloc[-1]=7e-06 , ukdf['amount'].iloc[-1]=17990751.1928, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-812610.18339062128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30033.19164103', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39478
self.closeSec=1681374299, self.tradeDate='20230413', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30033.2, self.close=30031.9, self.high=30044.9, self.low=30031.9, self.vol=275.302, self.amt=8269510.8049 
2023-04-13 16:25:01,595:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230413   160000    160459  ...         0.0        0.0       0
5946  20230413   160500    160959  ...         0.0        0.0       0
5947  20230413   161000    161459  ...         0.0        0.0       0
5948  20230413   161500    161959  ...         0.0        0.0       0
5949  20230413   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 16:25:01,595:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681374299, self.tradeDate='20230413', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30033.2, self.close=30031.9, self.high=30044.9, self.low=30031.9, self.vol=275.302, self.amt=8269510.8049, ukdf['pct'].iloc[-1]=-4.3e-05 , ukdf['amount'].iloc[-1]=8269510.8049, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-812550.91697372816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30032.20675641', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40039 

self.closeSec=1681372799, self.tradeDate='20230413', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30066.8, self.close=30055.0, self.high=30076.0, self.low=30055.0 
127.0.0.1 - - [13/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40040 

self.closeSec=1681373099, self.tradeDate='20230413', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=30054.0, self.close=30044.8, self.high=30066.1, self.low=30044.7 
127.0.0.1 - - [13/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40041 

self.closeSec=1681373399, self.tradeDate='20230413', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=30044.8, self.close=30041.1, self.high=30057.9, self.low=30039.0 
127.0.0.1 - - [13/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40042 

self.closeSec=1681373699, self.tradeDate='20230413', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=30041.2, self.close=30033.0, self.high=30071.8, self.low=30030.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40043 

self.closeSec=1681373999, self.tradeDate='20230413', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30032.9, self.close=30033.2, self.high=30036.2, self.low=30025.7 
127.0.0.1 - - [13/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40044 

self.closeSec=1681374299, self.tradeDate='20230413', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30033.2, self.close=30031.9, self.high=30044.9, self.low=30031.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-13 16:00:35,965:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230413    132959  30038.7  ...  52.083333  0.543180  0.585272
5786  20230413    135959  30065.0  ...  52.083333  0.547593  0.576394
5787  20230413    142959  30091.2  ...  51.666667  0.541199  0.570541
5788  20230413    145959  30059.9  ...  51.666667  0.529250  0.569691
5789  20230413    152959  30000.3  ...  52.083333  0.537430  0.565277

[5 rows x 33 columns]
0.5830258302583026
acc is : 0.5830258302583026
2023-04-13 16:00:36,172:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.513058  0.486942       1  ...  1.016239  -1.0    0.0  1.057721
538     0  0.516720  0.483280       0  ...  1.017300  -1.0    0.0  1.056617
539     0  0.505994  0.494006       0  ...  1.019314  -1.0    0.0  1.054525
540     1  0.494928  0.505072       1  ...  1.017727  -1.0    0.0  1.056167
541     0  0.521042  0.478958       1  ...  1.017456  -1.0    0.0  1.056448

[5 rows x 10 columns]
2023-04-13 16:00:36,194:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511758  0.488242       1  ...  1.033868  -1.0    0.0  1.055665
46     0  0.515701  0.484299       0  ...  1.017300  -1.0    0.0  1.054571
47     0  0.505346  0.494654       0  ...  1.019314  -1.0    0.0  1.053093
48     1  0.495484  0.504516       1  ...  1.017727  -1.0    0.0  1.056364
49     0  0.521042  0.478958       1  ...  1.017456  -1.0    0.0  1.056448

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20017 

self.closeSec=1681370999, self.tradeDate='20230413', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30042', self.close='30047'
127.0.0.1 - - [13/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20018 

self.closeSec=1681371599, self.tradeDate='20230413', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30047', self.close='30019'
127.0.0.1 - - [13/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20019 

self.closeSec=1681372199, self.tradeDate='20230413', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30018.9', self.close='30057.4'
127.0.0.1 - - [13/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20020 

self.closeSec=1681372799, self.tradeDate='20230413', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30057.5', self.close='30055'
127.0.0.1 - - [13/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20021 

self.closeSec=1681373399, self.tradeDate='20230413', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30054', self.close='30041.1'
127.0.0.1 - - [13/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20022 

self.closeSec=1681373999, self.tradeDate='20230413', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30041.2', self.close='30033.2'
127.0.0.1 - - [13/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [13/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20018 

self.closeSec=1681370999, self.tradeDate='20230413', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30042', self.close='30047'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20019 

self.closeSec=1681371599, self.tradeDate='20230413', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30047', self.close='30019'
127.0.0.1 - - [13/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20020 

self.closeSec=1681372199, self.tradeDate='20230413', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30018.9', self.close='30057.4'
127.0.0.1 - - [13/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20021 

self.closeSec=1681372799, self.tradeDate='20230413', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30057.5', self.close='30055'
127.0.0.1 - - [13/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20022 

self.closeSec=1681373399, self.tradeDate='20230413', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30054', self.close='30041.1'
127.0.0.1 - - [13/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20023 

self.closeSec=1681373999, self.tradeDate='20230413', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30041.2', self.close='30033.2'
127.0.0.1 - - [13/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [13/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20018 

self.closeSec=1681370999, self.tradeDate='20230413', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30042', self.close='30047'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20019 

self.closeSec=1681371599, self.tradeDate='20230413', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30047', self.close='30019'
127.0.0.1 - - [13/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20020 

self.closeSec=1681372199, self.tradeDate='20230413', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30018.9', self.close='30057.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20021 

self.closeSec=1681372799, self.tradeDate='20230413', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30057.5', self.close='30055'
127.0.0.1 - - [13/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20022 

self.closeSec=1681373399, self.tradeDate='20230413', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30054', self.close='30041.1'
127.0.0.1 - - [13/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20023 

self.closeSec=1681373999, self.tradeDate='20230413', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30041.2', self.close='30033.2'
127.0.0.1 - - [13/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35475
self.closeSec=1681373999, self.tradeDate='20230413', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30032.9, self.close=30033.2, self.high=30036.2, self.low=30025.7, self.vol=599.07, self.amt=17990751.1928 
127.0.0.1 - - [13/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-13 16:20:07,238:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230413   155500    155959  ...         0.0        0.0       0
5945  20230413   160000    160459  ...         0.0        0.0       0
5946  20230413   160500    160959  ...         0.0        0.0       0
5947  20230413   161000    161459  ...         0.0        0.0       0
5948  20230413   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 16:20:07,262:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681373999, self.tradeDate='20230413', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30032.9, self.close=30033.2, self.high=30036.2, self.low=30025.7, self.vol=599.07, self.amt=17990751.1928, ukdf['pct'].iloc[-1]=7e-06 , ukdf['amount'].iloc[-1]=17990751.1928, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [13/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35476
self.closeSec=1681374299, self.tradeDate='20230413', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30033.2, self.close=30031.9, self.high=30044.9, self.low=30031.9, self.vol=275.302, self.amt=8269510.8049 
2023-04-13 16:25:01,585:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230413   160000    160459  ...         0.0        0.0       0
5946  20230413   160500    160959  ...         0.0        0.0       0
5947  20230413   161000    161459  ...         0.0        0.0       0
5948  20230413   161500    161959  ...         0.0        0.0       0
5949  20230413   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-13 16:25:01,586:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681374299, self.tradeDate='20230413', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30033.2, self.close=30031.9, self.high=30044.9, self.low=30031.9, self.vol=275.302, self.amt=8269510.8049, ukdf['pct'].iloc[-1]=-4.3e-05 , ukdf['amount'].iloc[-1]=8269510.8049, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230413   040000    075959  1681343999  ...    721  1.082367  1.376775     1.0
722  20230413   080000    115959  1681358399  ...    722  1.058124  1.291224     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '93776.3535077334', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30055.60605556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [13/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=834
self.closeSec=1681372799, self.tradeDate='20230413', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30057.2, self.close=30055.0, self.high=30120.0, self.low=29980.1, self.vol=28859.962, self.amt=867280294.0481 
2023-04-13 16:00:01,852:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681372799, self.tradeDate='20230413', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30057.2, self.close=30055.0, self.high=30120.0, self.low=29980.1, self.vol=28859.962, self.amt=867280294.0481 
2023-04-13 16:00:01,918:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230412   200000    235959  ...  266359.400  8.017304e+09 -0.001856
720  20230413   000000    035959  ...   77606.552  2.323241e+09 -0.005296
721  20230413   040000    075959  ...   40504.038  1.210339e+09  0.002874
722  20230413   080000    115959  ...   52435.953  1.575004e+09  0.006102
723  20230413   120000    155959  ...   28859.962  8.672803e+08 -0.000077

[5 rows x 11 columns]
2023-04-13 16:00:05,014:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230412   200000    235959  1681315199  ...    719  1.148402  1.602193     1.0
720  20230413   000000    035959  1681329599  ...    720  1.122756  1.503012     1.0
721  20230413   040000    075959  1681343999  ...    721  1.082367  1.376775     1.0
722  20230413   080000    115959  1681358399  ...    722  1.058124  1.291224     1.0
723  20230413   120000    155959  1681372799  ...    723  1.003784  1.144108     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '93692.0115', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30054', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


