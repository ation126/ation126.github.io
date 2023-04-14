# 20230414 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39765
self.closeSec=1681460399, self.tradeDate='20230414', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30746.9, self.close=30774.3, self.high=30787.4, self.low=30726.7, self.vol=1238.442, self.amt=38091149.2604 
127.0.0.1 - - [14/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-14 16:20:07,342:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230414   155500    155959  ...         0.0        0.0       0
5945  20230414   160000    160459  ...         0.0        0.0       0
5946  20230414   160500    160959  ...         0.0        0.0       0
5947  20230414   161000    161459  ...         0.0        0.0       0
5948  20230414   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 16:20:07,344:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681460399, self.tradeDate='20230414', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30746.9, self.close=30774.3, self.high=30787.4, self.low=30726.7, self.vol=1238.442, self.amt=38091149.2604, ukdf['pct'].iloc[-1]=0.000891 , ukdf['amount'].iloc[-1]=38091149.2604, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-856562.60925037168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30763.58957143', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39766
self.closeSec=1681460699, self.tradeDate='20230414', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30774.2, self.close=30727.8, self.high=30774.3, self.low=30720.0, self.vol=1623.466, self.amt=49905440.4537 
2023-04-14 16:25:01,643:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230414   160000    160459  ...         0.0        0.0       0
5946  20230414   160500    160959  ...         0.0        0.0       0
5947  20230414   161000    161459  ...         0.0        0.0       0
5948  20230414   161500    161959  ...         0.0        0.0       0
5949  20230414   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 16:25:01,647:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681460699, self.tradeDate='20230414', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30774.2, self.close=30727.8, self.high=30774.3, self.low=30720.0, self.vol=1623.466, self.amt=49905440.4537, ukdf['pct'].iloc[-1]=-0.001511 , ukdf['amount'].iloc[-1]=49905440.4537, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-854463.06049142576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30728.69943651', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [14/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40327 

self.closeSec=1681459199, self.tradeDate='20230414', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30770.0, self.close=30739.9, self.high=30780.0, self.low=30730.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40328 

self.closeSec=1681459499, self.tradeDate='20230414', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=30739.9, self.close=30775.2, self.high=30794.0, self.low=30739.9 
127.0.0.1 - - [14/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40329 

self.closeSec=1681459799, self.tradeDate='20230414', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=30775.2, self.close=30730.1, self.high=30779.7, self.low=30724.8 
127.0.0.1 - - [14/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40330 

self.closeSec=1681460099, self.tradeDate='20230414', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=30730.1, self.close=30746.9, self.high=30766.0, self.low=30715.0 
127.0.0.1 - - [14/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40331 

self.closeSec=1681460399, self.tradeDate='20230414', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30746.9, self.close=30774.3, self.high=30787.4, self.low=30726.7 
127.0.0.1 - - [14/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40332 

self.closeSec=1681460699, self.tradeDate='20230414', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30774.2, self.close=30727.8, self.high=30774.3, self.low=30720.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-14 16:00:35,785:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230414    132959  30700.9  ...  55.416667  0.609568  0.332873
5786  20230414    135959  30745.1  ...  55.416667  0.615838  0.323735
5787  20230414    142959  30786.8  ...  55.833333  0.618551  0.313758
5788  20230414    145959  30805.0  ...  56.250000  0.637886  0.301329
5789  20230414    152959  30939.0  ...  56.250000  0.636756  0.290054

[5 rows x 33 columns]
0.5701107011070111
acc is : 0.5701107011070111
2023-04-14 16:00:35,992:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.519089  0.480911       1  ...  1.015107   1.0    0.0  1.094292
538     0  0.515965  0.484035       1  ...  1.015704   1.0    0.0  1.094935
539     0  0.511789  0.488211       1  ...  1.020125   1.0    0.0  1.099701
540     0  0.541601  0.458399       0  ...  1.019974   1.0    0.0  1.099538
541     0  0.513269  0.486731       0  ...  1.013561   1.0    0.0  1.092625

[5 rows x 10 columns]
2023-04-14 16:00:36,035:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519117  0.480883       1  ...  1.015107   1.0    0.0  1.101748
46     0  0.515352  0.484648       1  ...  1.015704   1.0    0.0  1.096521
47     0  0.511004  0.488996       1  ...  0.999270   1.0    0.0  1.101103
48     0  0.540140  0.459860       0  ...  0.999121   1.0    0.0  1.098476
49     0  0.513269  0.486731       0  ...  1.013561   1.0    0.0  1.092625

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20161 

self.closeSec=1681457399, self.tradeDate='20230414', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30925', self.close='30934.4'
127.0.0.1 - - [14/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20162 

self.closeSec=1681457999, self.tradeDate='20230414', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30934.4', self.close='30779.9'
127.0.0.1 - - [14/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20163 

self.closeSec=1681458599, self.tradeDate='20230414', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30780', self.close='30775.7'
127.0.0.1 - - [14/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20164 

self.closeSec=1681459199, self.tradeDate='20230414', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30775.7', self.close='30739.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20165 

self.closeSec=1681459799, self.tradeDate='20230414', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30739.9', self.close='30730.1'
127.0.0.1 - - [14/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20166 

self.closeSec=1681460399, self.tradeDate='20230414', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30730.1', self.close='30774.3'
127.0.0.1 - - [14/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20162 

self.closeSec=1681457399, self.tradeDate='20230414', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30925', self.close='30934.4'
127.0.0.1 - - [14/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20163 

self.closeSec=1681457999, self.tradeDate='20230414', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30934.4', self.close='30779.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20164 

self.closeSec=1681458599, self.tradeDate='20230414', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30780', self.close='30775.7'
127.0.0.1 - - [14/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20165 

self.closeSec=1681459199, self.tradeDate='20230414', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30775.7', self.close='30739.9'
127.0.0.1 - - [14/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20166 

self.closeSec=1681459799, self.tradeDate='20230414', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30739.9', self.close='30730.1'
127.0.0.1 - - [14/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20167 

self.closeSec=1681460399, self.tradeDate='20230414', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30730.1', self.close='30774.3'
127.0.0.1 - - [14/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20162 

self.closeSec=1681457399, self.tradeDate='20230414', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30925', self.close='30934.4'
127.0.0.1 - - [14/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20163 

self.closeSec=1681457999, self.tradeDate='20230414', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30934.4', self.close='30779.9'
127.0.0.1 - - [14/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20164 

self.closeSec=1681458599, self.tradeDate='20230414', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30780', self.close='30775.7'
127.0.0.1 - - [14/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20165 

self.closeSec=1681459199, self.tradeDate='20230414', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30775.7', self.close='30739.9'
127.0.0.1 - - [14/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20166 

self.closeSec=1681459799, self.tradeDate='20230414', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30739.9', self.close='30730.1'
127.0.0.1 - - [14/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20167 

self.closeSec=1681460399, self.tradeDate='20230414', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30730.1', self.close='30774.3'
127.0.0.1 - - [14/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35763
self.closeSec=1681460399, self.tradeDate='20230414', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30746.9, self.close=30774.3, self.high=30787.4, self.low=30726.7, self.vol=1238.442, self.amt=38091149.2604 
127.0.0.1 - - [14/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-14 16:20:07,052:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230414   155500    155959  ...         0.0        0.0       0
5945  20230414   160000    160459  ...         0.0        0.0       0
5946  20230414   160500    160959  ...         0.0        0.0       0
5947  20230414   161000    161459  ...         0.0        0.0       0
5948  20230414   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 16:20:07,063:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681460399, self.tradeDate='20230414', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30746.9, self.close=30774.3, self.high=30787.4, self.low=30726.7, self.vol=1238.442, self.amt=38091149.2604, ukdf['pct'].iloc[-1]=0.000891 , ukdf['amount'].iloc[-1]=38091149.2604, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [14/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35764
self.closeSec=1681460699, self.tradeDate='20230414', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30774.2, self.close=30727.8, self.high=30774.3, self.low=30720.0, self.vol=1623.466, self.amt=49905440.4537 
2023-04-14 16:25:01,622:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230414   160000    160459  ...         0.0        0.0       0
5946  20230414   160500    160959  ...         0.0        0.0       0
5947  20230414   161000    161459  ...         0.0        0.0       0
5948  20230414   161500    161959  ...         0.0        0.0       0
5949  20230414   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 16:25:01,623:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681460699, self.tradeDate='20230414', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30774.2, self.close=30727.8, self.high=30774.3, self.low=30720.0, self.vol=1623.466, self.amt=49905440.4537, ukdf['pct'].iloc[-1]=-0.001511 , ukdf['amount'].iloc[-1]=49905440.4537, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230414   040000    075959  1681430399  ...    721  0.853519  0.747101     1.0
722  20230414   080000    115959  1681444799  ...    722  0.877030  0.787572     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '127149.318', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30691.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [14/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=840
self.closeSec=1681459199, self.tradeDate='20230414', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30684.5, self.close=30739.9, self.high=31059.0, self.low=30665.9, self.vol=95052.482, self.amt=2930391684.98152 
2023-04-14 16:00:02,296:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681459199, self.tradeDate='20230414', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30684.5, self.close=30739.9, self.high=31059.0, self.low=30665.9, self.vol=95052.482, self.amt=2930391684.98152 
2023-04-14 16:00:02,343:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230413   200000    235959  ...  147335.344  4.469851e+09  0.009065
720  20230414   000000    035959  ...   76467.563  2.322848e+09 -0.003267
721  20230414   040000    075959  ...   39042.382  1.182256e+09  0.001306
722  20230414   080000    115959  ...  143783.626  4.413223e+09  0.010602
723  20230414   120000    155959  ...   95052.482  2.930392e+09  0.001802

[5 rows x 11 columns]
2023-04-14 16:00:04,556:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230413   200000    235959  1681401599  ...    719  0.949147  0.982769     1.0
720  20230414   000000    035959  1681415999  ...    720  0.887913  0.834126     1.0
721  20230414   040000    075959  1681430399  ...    721  0.853519  0.747101     1.0
722  20230414   080000    115959  1681444799  ...    722  0.877030  0.787572     1.0
723  20230414   120000    155959  1681459199  ...    723  0.818031  0.651874     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '129694.8832214571', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30739.57310714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


