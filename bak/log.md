# 20230421 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41781
self.closeSec=1682065199, self.tradeDate='20230421', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28070.0, self.close=28115.2, self.high=28139.6, self.low=28069.0, self.vol=2226.444, self.amt=62583270.7692 
127.0.0.1 - - [21/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-21 16:20:05,617:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230421   155500    155959  ...         0.0        0.0       0
5945  20230421   160000    160459  ...         0.0        0.0       0
5946  20230421   160500    160959  ...         0.0        0.0       0
5947  20230421   161000    161459  ...         0.0        0.0       0
5948  20230421   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 16:20:05,624:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682065199, self.tradeDate='20230421', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28070.0, self.close=28115.2, self.high=28139.6, self.low=28069.0, self.vol=2226.444, self.amt=62583270.7692, ukdf['pct'].iloc[-1]=0.00161 , ukdf['amount'].iloc[-1]=62583270.7692, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-697229.224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28115.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41782
self.closeSec=1682065499, self.tradeDate='20230421', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28115.3, self.close=28134.3, self.high=28144.5, self.low=28084.2, self.vol=1264.155, self.amt=35537043.8637 
2023-04-21 16:25:01,549:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230421   160000    160459  ...         0.0        0.0       0
5946  20230421   160500    160959  ...         0.0        0.0       0
5947  20230421   161000    161459  ...         0.0        0.0       0
5948  20230421   161500    161959  ...         0.0        0.0       0
5949  20230421   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 16:25:01,550:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682065499, self.tradeDate='20230421', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28115.3, self.close=28134.3, self.high=28144.5, self.low=28084.2, self.vol=1264.155, self.amt=35537043.8637, ukdf['pct'].iloc[-1]=0.000679 , ukdf['amount'].iloc[-1]=35537043.8637, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-698361.9199079496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28134.62305085', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42343 

self.closeSec=1682063999, self.tradeDate='20230421', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28115.8, self.close=28142.3, self.high=28159.9, self.low=28103.7 
127.0.0.1 - - [21/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42344 

self.closeSec=1682064299, self.tradeDate='20230421', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28142.4, self.close=28146.0, self.high=28225.8, self.low=28136.5 
127.0.0.1 - - [21/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42345 

self.closeSec=1682064599, self.tradeDate='20230421', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28146.0, self.close=28112.7, self.high=28168.2, self.low=28106.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42346 

self.closeSec=1682064899, self.tradeDate='20230421', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28112.8, self.close=28070.0, self.high=28131.6, self.low=28070.0 
127.0.0.1 - - [21/Apr/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42347 

self.closeSec=1682065199, self.tradeDate='20230421', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28070.0, self.close=28115.2, self.high=28139.6, self.low=28069.0 
127.0.0.1 - - [21/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42348 

self.closeSec=1682065499, self.tradeDate='20230421', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28115.3, self.close=28134.3, self.high=28144.5, self.low=28084.2 
127.0.0.1 - - [21/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-21 16:00:18,905:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230421    132959  28225.9  ...  49.583333  0.404017  0.746083
5786  20230421    135959  28214.6  ...  49.583333  0.395145  0.751858
5787  20230421    142959  28143.1  ...  49.583333  0.396976  0.756572
5788  20230421    145959  28152.8  ...  49.583333  0.367600  0.766848
5789  20230421    152959  27906.0  ...  49.166667  0.362207  0.779333

[5 rows x 33 columns]
0.5055350553505535
acc is : 0.5055350553505535
2023-04-21 16:00:19,000:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.525750  0.474250       0  ...  0.955212   1.0    0.0  0.991897
538     0  0.505238  0.494762       1  ...  0.955541   1.0    0.0  0.992239
539     0  0.522643  0.477357       0  ...  0.947022   1.0    0.0  0.983393
540     1  0.451220  0.548780       0  ...  0.945342   1.0    0.0  0.981648
541     1  0.494859  0.505141       1  ...  0.955171   1.0    0.0  0.991855

[5 rows x 10 columns]
2023-04-21 16:00:19,023:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524827  0.475173       0  ...  0.955212   1.0    0.0  0.990246
46     0  0.504628  0.495372       1  ...  0.955541   1.0    0.0  0.992512
47     0  0.522355  0.477645       0  ...  0.947022   1.0    0.0  0.983972
48     1  0.451680  0.548320       0  ...  0.913739   1.0    0.0  0.983853
49     1  0.494859  0.505141       1  ...  0.955171   1.0    0.0  0.991855

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21169 

self.closeSec=1682062199, self.tradeDate='20230421', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27942.9', self.close='27852.3'
127.0.0.1 - - [21/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21170 

self.closeSec=1682062799, self.tradeDate='20230421', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27852.3', self.close='27948'
127.0.0.1 - - [21/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [21/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21171 

self.closeSec=1682063399, self.tradeDate='20230421', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27948', self.close='28057.8'
127.0.0.1 - - [21/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21172 

self.closeSec=1682063999, self.tradeDate='20230421', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28055', self.close='28142.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21173 

self.closeSec=1682064599, self.tradeDate='20230421', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28142.4', self.close='28112.7'
127.0.0.1 - - [21/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21174 

self.closeSec=1682065199, self.tradeDate='20230421', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28112.8', self.close='28115.2'
127.0.0.1 - - [21/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [21/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21170 

self.closeSec=1682062199, self.tradeDate='20230421', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27942.9', self.close='27852.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21171 

self.closeSec=1682062799, self.tradeDate='20230421', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27852.3', self.close='27948'
127.0.0.1 - - [21/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21172 

self.closeSec=1682063399, self.tradeDate='20230421', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27948', self.close='28057.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21173 

self.closeSec=1682063999, self.tradeDate='20230421', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28055', self.close='28142.3'
127.0.0.1 - - [21/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21174 

self.closeSec=1682064599, self.tradeDate='20230421', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28142.4', self.close='28112.7'
127.0.0.1 - - [21/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21175 

self.closeSec=1682065199, self.tradeDate='20230421', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28112.8', self.close='28115.2'
127.0.0.1 - - [21/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21170 

self.closeSec=1682062199, self.tradeDate='20230421', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27942.9', self.close='27852.3'
127.0.0.1 - - [21/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21171 

self.closeSec=1682062799, self.tradeDate='20230421', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27852.3', self.close='27948'
127.0.0.1 - - [21/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21172 

self.closeSec=1682063399, self.tradeDate='20230421', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27948', self.close='28057.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21173 

self.closeSec=1682063999, self.tradeDate='20230421', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28055', self.close='28142.3'
127.0.0.1 - - [21/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21174 

self.closeSec=1682064599, self.tradeDate='20230421', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28142.4', self.close='28112.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21175 

self.closeSec=1682065199, self.tradeDate='20230421', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28112.8', self.close='28115.2'
127.0.0.1 - - [21/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37779
self.closeSec=1682065199, self.tradeDate='20230421', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28070.0, self.close=28115.2, self.high=28139.6, self.low=28069.0, self.vol=2226.444, self.amt=62583270.7692 
127.0.0.1 - - [21/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-04-21 16:20:05,076:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230421   155500    155959  ...         0.0        0.0       0
5945  20230421   160000    160459  ...         0.0        0.0       0
5946  20230421   160500    160959  ...         0.0        0.0       0
5947  20230421   161000    161459  ...         0.0        0.0       0
5948  20230421   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 16:20:05,084:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682065199, self.tradeDate='20230421', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28070.0, self.close=28115.2, self.high=28139.6, self.low=28069.0, self.vol=2226.444, self.amt=62583270.7692, ukdf['pct'].iloc[-1]=0.00161 , ukdf['amount'].iloc[-1]=62583270.7692, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [21/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37780
self.closeSec=1682065499, self.tradeDate='20230421', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28115.3, self.close=28134.3, self.high=28144.5, self.low=28084.2, self.vol=1264.155, self.amt=35537043.8637 
2023-04-21 16:25:01,520:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230421   160000    160459  ...         0.0        0.0       0
5946  20230421   160500    160959  ...         0.0        0.0       0
5947  20230421   161000    161459  ...         0.0        0.0       0
5948  20230421   161500    161959  ...         0.0        0.0       0
5949  20230421   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 16:25:01,521:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682065499, self.tradeDate='20230421', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28115.3, self.close=28134.3, self.high=28144.5, self.low=28084.2, self.vol=1264.155, self.amt=35537043.8637, ukdf['pct'].iloc[-1]=0.000679 , ukdf['amount'].iloc[-1]=35537043.8637, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230421   040000    075959  1682035199  ...    721  0.659259  0.250416     NaN
722  20230421   080000    115959  1682049599  ...    722  0.723722  0.386529     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '2515.4685', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28317.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [21/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=882
self.closeSec=1682063999, self.tradeDate='20230421', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28309.2, self.close=28142.3, self.high=28332.3, self.low=27800.0, self.vol=119795.709, self.amt=3357784333.69807 
2023-04-21 16:00:01,780:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682063999, self.tradeDate='20230421', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28309.2, self.close=28142.3, self.high=28332.3, self.low=27800.0, self.vol=119795.709, self.amt=3357784333.69807 
2023-04-21 16:00:01,843:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230420   200000    235959  ...  164293.111  4.712963e+09 -0.003821
720  20230421   000000    035959  ...  186192.325  5.276888e+09 -0.014060
721  20230421   040000    075959  ...   69632.679  1.964323e+09  0.004920
722  20230421   080000    115959  ...   58395.542  1.648645e+09  0.002806
723  20230421   120000    155959  ...  119795.709  3.357784e+09 -0.005892

[5 rows x 11 columns]
2023-04-21 16:00:03,843:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230420   200000    235959  1682006399  ...    719  0.579524  0.090516     NaN
720  20230421   000000    035959  1682020799  ...    720  0.604005  0.135192     NaN
721  20230421   040000    075959  1682035199  ...    721  0.659259  0.250416     NaN
722  20230421   080000    115959  1682049599  ...    722  0.723722  0.386529     NaN
723  20230421   120000    155959  1682063999  ...    723  0.725958  0.377815     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-6690.3296206554', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28142.50154964', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


