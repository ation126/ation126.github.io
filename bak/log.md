# 20230501 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44661
self.closeSec=1682929199, self.tradeDate='20230501', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28583.0, self.close=28552.0, self.high=28583.0, self.low=28529.9, self.vol=1608.755, self.amt=45932700.3826 
127.0.0.1 - - [01/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-01 16:20:06,243:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230501   155500    155959  ...         0.0        0.0       0
5952  20230501   160000    160459  ...         0.0        0.0       0
5953  20230501   160500    160959  ...         0.0        0.0       0
5954  20230501   161000    161459  ...         0.0        0.0       0
5955  20230501   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 16:20:06,252:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682929199, self.tradeDate='20230501', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28583.0, self.close=28552.0, self.high=28583.0, self.low=28529.9, self.vol=1608.755, self.amt=45932700.3826, ukdf['pct'].iloc[-1]=-0.001081 , ukdf['amount'].iloc[-1]=45932700.3826, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-723493.10486826352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28552.25109127', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44662
self.closeSec=1682929499, self.tradeDate='20230501', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28552.1, self.close=28573.9, self.high=28573.9, self.low=28552.0, self.vol=689.848, self.amt=19703893.9789 
2023-05-01 16:25:02,119:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230501   160000    160459  ...         0.0        0.0       0
5953  20230501   160500    160959  ...         0.0        0.0       0
5954  20230501   161000    161459  ...         0.0        0.0       0
5955  20230501   161500    161959  ...         0.0        0.0       0
5956  20230501   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 16:25:02,120:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682929499, self.tradeDate='20230501', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28552.1, self.close=28573.9, self.high=28573.9, self.low=28552.0, self.vol=689.848, self.amt=19703893.9789, ukdf['pct'].iloc[-1]=0.000767 , ukdf['amount'].iloc[-1]=19703893.9789, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-724795.8496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28573.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [01/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45223 

self.closeSec=1682927999, self.tradeDate='20230501', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28595.6, self.close=28610.0, self.high=28616.0, self.low=28595.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45224 

self.closeSec=1682928299, self.tradeDate='20230501', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28609.9, self.close=28604.8, self.high=28614.3, self.low=28591.1 
127.0.0.1 - - [01/May/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45225 

self.closeSec=1682928599, self.tradeDate='20230501', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28604.7, self.close=28562.7, self.high=28616.8, self.low=28560.7 
127.0.0.1 - - [01/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45226 

self.closeSec=1682928899, self.tradeDate='20230501', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28562.8, self.close=28582.9, self.high=28587.8, self.low=28560.0 
127.0.0.1 - - [01/May/2023 16:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45227 

self.closeSec=1682929199, self.tradeDate='20230501', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28583.0, self.close=28552.0, self.high=28583.0, self.low=28529.9 
127.0.0.1 - - [01/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 16:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45228 

self.closeSec=1682929499, self.tradeDate='20230501', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28552.1, self.close=28573.9, self.high=28573.9, self.low=28552.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-01 16:00:20,112:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230501    132959  28543.7  ...  50.000000  0.394341  0.709319
5786  20230501    135959  28532.8  ...  49.583333  0.386221  0.718488
5787  20230501    142959  28467.9  ...  50.000000  0.400584  0.724230
5788  20230501    145959  28542.0  ...  50.000000  0.407496  0.728215
5789  20230501    152959  28578.0  ...  50.416667  0.419991  0.729416

[5 rows x 33 columns]
0.5553505535055351
acc is : 0.5553505535055351
2023-05-01 16:00:20,189:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.512669  0.487331       0  ...  0.837361  -1.0    0.0  0.984677
538     1  0.496381  0.503619       1  ...  0.835187  -1.0    0.0  0.987233
539     0  0.530215  0.469785       1  ...  0.834131  -1.0    0.0  0.988482
540     0  0.526124  0.473876       1  ...  0.832201  -1.0    0.0  0.990768
541     0  0.535286  0.464714       0  ...  0.833192  -1.0    0.0  0.989589

[5 rows x 10 columns]
2023-05-01 16:00:20,207:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513294  0.486706       0  ...  0.830147  -1.0    0.0  0.979359
46     1  0.497461  0.502539       1  ...  0.827992  -1.0    0.0  0.993896
47     0  0.530883  0.469117       1  ...  0.834131  -1.0    0.0  0.992461
48     0  0.526433  0.473567       1  ...  0.832201  -1.0    0.0  0.991756
49     0  0.535286  0.464714       0  ...  0.833192  -1.0    0.0  0.989589

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [01/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22609 

self.closeSec=1682926199, self.tradeDate='20230501', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28616.4', self.close='28644.1'
127.0.0.1 - - [01/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22610 

self.closeSec=1682926799, self.tradeDate='20230501', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28644', self.close='28612.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22611 

self.closeSec=1682927399, self.tradeDate='20230501', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28612.9', self.close='28646.5'
127.0.0.1 - - [01/May/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22612 

self.closeSec=1682927999, self.tradeDate='20230501', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28646.5', self.close='28610'
127.0.0.1 - - [01/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22613 

self.closeSec=1682928599, self.tradeDate='20230501', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28609.9', self.close='28562.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22614 

self.closeSec=1682929199, self.tradeDate='20230501', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28562.8', self.close='28552'
127.0.0.1 - - [01/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22610 

self.closeSec=1682926199, self.tradeDate='20230501', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28616.4', self.close='28644.1'
127.0.0.1 - - [01/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22611 

self.closeSec=1682926799, self.tradeDate='20230501', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28644', self.close='28612.9'
127.0.0.1 - - [01/May/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22612 

self.closeSec=1682927399, self.tradeDate='20230501', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28612.9', self.close='28646.5'
127.0.0.1 - - [01/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22613 

self.closeSec=1682927999, self.tradeDate='20230501', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28646.5', self.close='28610'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22614 

self.closeSec=1682928599, self.tradeDate='20230501', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28609.9', self.close='28562.7'
127.0.0.1 - - [01/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22615 

self.closeSec=1682929199, self.tradeDate='20230501', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28562.8', self.close='28552'
127.0.0.1 - - [01/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22610 

self.closeSec=1682926199, self.tradeDate='20230501', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28616.4', self.close='28644.1'
127.0.0.1 - - [01/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22611 

self.closeSec=1682926799, self.tradeDate='20230501', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28644', self.close='28612.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22612 

self.closeSec=1682927399, self.tradeDate='20230501', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28612.9', self.close='28646.5'
127.0.0.1 - - [01/May/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22613 

self.closeSec=1682927999, self.tradeDate='20230501', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28646.5', self.close='28610'
127.0.0.1 - - [01/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22614 

self.closeSec=1682928599, self.tradeDate='20230501', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28609.9', self.close='28562.7'
127.0.0.1 - - [01/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22615 

self.closeSec=1682929199, self.tradeDate='20230501', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28562.8', self.close='28552'
127.0.0.1 - - [01/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40659
self.closeSec=1682929199, self.tradeDate='20230501', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28583.0, self.close=28552.0, self.high=28583.0, self.low=28529.9, self.vol=1608.755, self.amt=45932700.3826 
127.0.0.1 - - [01/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-01 16:20:06,259:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230501   155500    155959  ...         0.0        0.0       0
5952  20230501   160000    160459  ...         0.0        0.0       0
5953  20230501   160500    160959  ...         0.0        0.0       0
5954  20230501   161000    161459  ...         0.0        0.0       0
5955  20230501   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 16:20:06,278:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682929199, self.tradeDate='20230501', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28583.0, self.close=28552.0, self.high=28583.0, self.low=28529.9, self.vol=1608.755, self.amt=45932700.3826, ukdf['pct'].iloc[-1]=-0.001081 , ukdf['amount'].iloc[-1]=45932700.3826, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40660
self.closeSec=1682929499, self.tradeDate='20230501', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28552.1, self.close=28573.9, self.high=28573.9, self.low=28552.0, self.vol=689.848, self.amt=19703893.9789 
2023-05-01 16:25:02,109:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230501   160000    160459  ...         0.0        0.0       0
5953  20230501   160500    160959  ...         0.0        0.0       0
5954  20230501   161000    161459  ...         0.0        0.0       0
5955  20230501   161500    161959  ...         0.0        0.0       0
5956  20230501   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 16:25:02,110:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682929499, self.tradeDate='20230501', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28552.1, self.close=28573.9, self.high=28573.9, self.low=28552.0, self.vol=689.848, self.amt=19703893.9789, ukdf['pct'].iloc[-1]=0.000767 , ukdf['amount'].iloc[-1]=19703893.9789, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230501   040000    075959  1682899199  ...    721  0.035905 -1.805191    -1.0
722  20230501   080000    115959  1682913599  ...    722  0.001777 -1.873562    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '37428.21412128988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28540.14810734', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=942
self.closeSec=1682927999, self.tradeDate='20230501', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28545.6, self.close=28610.0, self.high=28700.0, self.low=28200.0, self.vol=77991.238, self.amt=2223717819.04177 
127.0.0.1 - - [01/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
2023-05-01 16:00:03,171:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682927999, self.tradeDate='20230501', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28545.6, self.close=28610.0, self.high=28700.0, self.low=28200.0, self.vol=77991.238, self.amt=2223717819.04177 
2023-05-01 16:00:03,201:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230430   200000    235959  ...  142401.479  4.216874e+09  0.015748
720  20230501   000000    035959  ...  117019.249  3.458024e+09 -0.010059
721  20230501   040000    075959  ...   75149.932  2.202846e+09 -0.004430
722  20230501   080000    115959  ...  143426.630  4.121325e+09 -0.022946
723  20230501   120000    155959  ...   77991.238  2.223718e+09  0.002256

[5 rows x 11 columns]
2023-05-01 16:00:04,691:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230430   200000    235959  1682870399  ...    719  0.001188 -1.987370    -1.0
720  20230501   000000    035959  1682884799  ...    720  0.001936 -1.943589    -1.0
721  20230501   040000    075959  1682899199  ...    721  0.035905 -1.805191    -1.0
722  20230501   080000    115959  1682913599  ...    722  0.001777 -1.873562    -1.0
723  20230501   120000    155959  1682927999  ...    723  0.057037 -1.678771    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '34036.22055590372', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28612.75381746', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


