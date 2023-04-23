# 20230423 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42357
self.closeSec=1682237999, self.tradeDate='20230423', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27706.0, self.close=27671.8, self.high=27709.9, self.low=27668.6, self.vol=1530.033, self.amt=42364267.6809 
127.0.0.1 - - [23/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-23 16:20:06,024:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230423   155500    155959  ...         0.0        0.0       0
5945  20230423   160000    160459  ...         0.0        0.0       0
5946  20230423   160500    160959  ...         0.0        0.0       0
5947  20230423   161000    161459  ...         0.0        0.0       0
5948  20230423   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 16:20:06,028:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682237999, self.tradeDate='20230423', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27706.0, self.close=27671.8, self.high=27709.9, self.low=27668.6, self.vol=1530.033, self.amt=42364267.6809, ukdf['pct'].iloc[-1]=-0.001238 , ukdf['amount'].iloc[-1]=42364267.6809, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-670697.6256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27674.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42358
self.closeSec=1682238299, self.tradeDate='20230423', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27672.0, self.close=27668.0, self.high=27681.2, self.low=27653.7, self.vol=769.939, self.amt=21303442.9878 
2023-04-23 16:25:01,688:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230423   160000    160459  ...         0.0        0.0       0
5946  20230423   160500    160959  ...         0.0        0.0       0
5947  20230423   161000    161459  ...         0.0        0.0       0
5948  20230423   161500    161959  ...         0.0        0.0       0
5949  20230423   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 16:25:01,688:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682238299, self.tradeDate='20230423', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27672.0, self.close=27668.0, self.high=27681.2, self.low=27653.7, self.vol=769.939, self.amt=21303442.9878, ukdf['pct'].iloc[-1]=-0.000137 , ukdf['amount'].iloc[-1]=21303442.9878, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-670282.4112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27668', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [23/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42919 

self.closeSec=1682236799, self.tradeDate='20230423', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27709.9, self.close=27704.6, self.high=27736.7, self.low=27696.9 
127.0.0.1 - - [23/Apr/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42920 

self.closeSec=1682237099, self.tradeDate='20230423', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27704.7, self.close=27683.0, self.high=27718.9, self.low=27674.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42921 

self.closeSec=1682237399, self.tradeDate='20230423', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27683.0, self.close=27723.9, self.high=27724.7, self.low=27668.6 
127.0.0.1 - - [23/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42922 

self.closeSec=1682237699, self.tradeDate='20230423', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27723.8, self.close=27706.1, self.high=27760.0, self.low=27704.2 
127.0.0.1 - - [23/Apr/2023 16:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42923 

self.closeSec=1682237999, self.tradeDate='20230423', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27706.0, self.close=27671.8, self.high=27709.9, self.low=27668.6 
127.0.0.1 - - [23/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42924 

self.closeSec=1682238299, self.tradeDate='20230423', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27672.0, self.close=27668.0, self.high=27681.2, self.low=27653.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-23 16:00:19,927:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230423    132959  27592.0  ...  51.250000  0.471635  0.394870
5786  20230423    135959  27579.4  ...  50.833333  0.470676  0.397638
5787  20230423    142959  27573.7  ...  50.833333  0.472468  0.399388
5788  20230423    145959  27582.7  ...  50.416667  0.471039  0.403986
5789  20230423    152959  27575.0  ...  50.416667  0.472912  0.407370

[5 rows x 33 columns]
0.5350553505535055
acc is : 0.5350553505535055
2023-04-23 16:00:20,064:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.505649  0.494351       0  ...  0.879229   1.0    0.0  0.912647
538     0  0.502804  0.497196       1  ...  0.879516   1.0    0.0  0.912945
539     0  0.512039  0.487961       0  ...  0.879264   1.0    0.0  0.912683
540     0  0.505293  0.494707       1  ...  0.879554   1.0    0.0  0.912984
541     0  0.507582  0.492418       1  ...  0.883400   1.0    0.0  0.916976

[5 rows x 10 columns]
2023-04-23 16:00:20,099:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505784  0.494216       0  ...  0.879229   1.0    0.0  0.911503
46     0  0.503226  0.496774       1  ...  0.879516   1.0    0.0  0.913901
47     0  0.512212  0.487788       0  ...  0.879264   1.0    0.0  0.913527
48     0  0.505187  0.494813       1  ...  0.879554   1.0    0.0  0.910459
49     0  0.507582  0.492418       1  ...  0.883400   1.0    0.0  0.916976

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21457 

self.closeSec=1682234999, self.tradeDate='20230423', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27554.9', self.close='27584'
127.0.0.1 - - [23/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21458 

self.closeSec=1682235599, self.tradeDate='20230423', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27584', self.close='27654.1'
127.0.0.1 - - [23/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21459 

self.closeSec=1682236199, self.tradeDate='20230423', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27653.6', self.close='27710'
127.0.0.1 - - [23/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21460 

self.closeSec=1682236799, self.tradeDate='20230423', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27709.9', self.close='27704.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21461 

self.closeSec=1682237399, self.tradeDate='20230423', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27704.7', self.close='27723.9'
127.0.0.1 - - [23/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21462 

self.closeSec=1682237999, self.tradeDate='20230423', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27723.8', self.close='27671.8'
127.0.0.1 - - [23/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21458 

self.closeSec=1682234999, self.tradeDate='20230423', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27554.9', self.close='27584'
127.0.0.1 - - [23/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21459 

self.closeSec=1682235599, self.tradeDate='20230423', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27584', self.close='27654.1'
127.0.0.1 - - [23/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21460 

self.closeSec=1682236199, self.tradeDate='20230423', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27653.6', self.close='27710'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21461 

self.closeSec=1682236799, self.tradeDate='20230423', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27709.9', self.close='27704.6'
127.0.0.1 - - [23/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21462 

self.closeSec=1682237399, self.tradeDate='20230423', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27704.7', self.close='27723.9'
127.0.0.1 - - [23/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21463 

self.closeSec=1682237999, self.tradeDate='20230423', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27723.8', self.close='27671.8'
127.0.0.1 - - [23/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21458 

self.closeSec=1682234999, self.tradeDate='20230423', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27554.9', self.close='27584'
127.0.0.1 - - [23/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21459 

self.closeSec=1682235599, self.tradeDate='20230423', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27584', self.close='27654.1'
127.0.0.1 - - [23/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21460 

self.closeSec=1682236199, self.tradeDate='20230423', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27653.6', self.close='27710'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21461 

self.closeSec=1682236799, self.tradeDate='20230423', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27709.9', self.close='27704.6'
127.0.0.1 - - [23/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21462 

self.closeSec=1682237399, self.tradeDate='20230423', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27704.7', self.close='27723.9'
127.0.0.1 - - [23/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21463 

self.closeSec=1682237999, self.tradeDate='20230423', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27723.8', self.close='27671.8'
127.0.0.1 - - [23/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38355
self.closeSec=1682237999, self.tradeDate='20230423', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27706.0, self.close=27671.8, self.high=27709.9, self.low=27668.6, self.vol=1530.033, self.amt=42364267.6809 
127.0.0.1 - - [23/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-23 16:20:05,319:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230423   155500    155959  ...         0.0        0.0       0
5945  20230423   160000    160459  ...         0.0        0.0       0
5946  20230423   160500    160959  ...         0.0        0.0       0
5947  20230423   161000    161459  ...         0.0        0.0       0
5948  20230423   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 16:20:05,331:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682237999, self.tradeDate='20230423', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27706.0, self.close=27671.8, self.high=27709.9, self.low=27668.6, self.vol=1530.033, self.amt=42364267.6809, ukdf['pct'].iloc[-1]=-0.001238 , ukdf['amount'].iloc[-1]=42364267.6809, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [23/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38356
self.closeSec=1682238299, self.tradeDate='20230423', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27672.0, self.close=27668.0, self.high=27681.2, self.low=27653.7, self.vol=769.939, self.amt=21303442.9878 
2023-04-23 16:25:01,650:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230423   160000    160459  ...         0.0        0.0       0
5946  20230423   160500    160959  ...         0.0        0.0       0
5947  20230423   161000    161459  ...         0.0        0.0       0
5948  20230423   161500    161959  ...         0.0        0.0       0
5949  20230423   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 16:25:01,650:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682238299, self.tradeDate='20230423', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27672.0, self.close=27668.0, self.high=27681.2, self.low=27653.7, self.vol=769.939, self.amt=21303442.9878, ukdf['pct'].iloc[-1]=-0.000137 , ukdf['amount'].iloc[-1]=21303442.9878, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230423   040000    075959  1682207999  ...    721  0.988576  0.835122     1.0
722  20230423   080000    115959  1682222399  ...    722  1.018294  0.888383     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-37961.39958403725', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27547.03225585', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=894
self.closeSec=1682236799, self.tradeDate='20230423', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27545.2, self.close=27704.6, self.high=27738.5, self.low=27519.2, self.vol=32611.861, self.amt=900369150.8122 127.0.0.1 - - [23/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

2023-04-23 16:00:01,811:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682236799, self.tradeDate='20230423', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27545.2, self.close=27704.6, self.high=27738.5, self.low=27519.2, self.vol=32611.861, self.amt=900369150.8122 
2023-04-23 16:00:01,841:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230422   200000    235959  ...  82203.755  2.251310e+09  0.007369
720  20230423   000000    035959  ...  86509.805  2.389329e+09  0.004644
721  20230423   040000    075959  ...  52141.270  1.446621e+09  0.007336
722  20230423   080000    115959  ...  66658.757  1.837779e+09 -0.009422
723  20230423   120000    155959  ...  32611.861  9.003692e+08  0.005787

[5 rows x 11 columns]
2023-04-23 16:00:03,554:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230422   200000    235959  1682179199  ...    719  0.957747  0.797817     1.0
720  20230423   000000    035959  1682193599  ...    720  0.969293  0.807105     1.0
721  20230423   040000    075959  1682207999  ...    721  0.988576  0.835122     1.0
722  20230423   080000    115959  1682222399  ...    722  1.018294  0.888383     1.0
723  20230423   120000    155959  1682236799  ...    723  1.089573  1.040425     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-29681.478', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27704.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


