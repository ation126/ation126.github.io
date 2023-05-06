# 20230506 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46101
self.closeSec=1683361199, self.tradeDate='20230506', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29245.0, self.close=29257.4, self.high=29273.5, self.low=29224.7, self.vol=1669.262, self.amt=48832016.2234 
127.0.0.1 - - [06/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-06 16:20:06,210:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230506   155500    155959  ...         0.0        0.0       0
5952  20230506   160000    160459  ...         0.0        0.0       0
5953  20230506   160500    160959  ...         0.0        0.0       0
5954  20230506   161000    161459  ...         0.0        0.0       0
5955  20230506   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 16:20:06,220:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683361199, self.tradeDate='20230506', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29245.0, self.close=29257.4, self.high=29273.5, self.low=29224.7, self.vol=1669.262, self.amt=48832016.2234, ukdf['pct'].iloc[-1]=0.000424 , ukdf['amount'].iloc[-1]=48832016.2234, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-766028.68990226384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29259.10407309', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/May/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46102
self.closeSec=1683361499, self.tradeDate='20230506', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29257.4, self.close=29284.9, self.high=29302.5, self.low=29246.1, self.vol=2123.059, self.amt=62170483.4233 
2023-05-06 16:25:01,601:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230506   160000    160459  ...         0.0        0.0       0
5953  20230506   160500    160959  ...         0.0        0.0       0
5954  20230506   161000    161459  ...         0.0        0.0       0
5955  20230506   161500    161959  ...         0.0        0.0       0
5956  20230506   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 16:25:01,603:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683361499, self.tradeDate='20230506', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29257.4, self.close=29284.9, self.high=29302.5, self.low=29246.1, self.vol=2123.059, self.amt=62170483.4233, ukdf['pct'].iloc[-1]=0.00094 , ukdf['amount'].iloc[-1]=62170483.4233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-767587.0032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29285', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [06/May/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46663 

self.closeSec=1683359999, self.tradeDate='20230506', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29377.0, self.close=29350.2, self.high=29377.0, self.low=29348.6 
127.0.0.1 - - [06/May/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46664 

self.closeSec=1683360299, self.tradeDate='20230506', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29350.2, self.close=29174.4, self.high=29359.2, self.low=29108.0 
127.0.0.1 - - [06/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46665 

self.closeSec=1683360599, self.tradeDate='20230506', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29167.1, self.close=29242.1, self.high=29242.1, self.low=29160.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46666 

self.closeSec=1683360899, self.tradeDate='20230506', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29242.1, self.close=29245.0, self.high=29245.0, self.low=29205.5 
127.0.0.1 - - [06/May/2023 16:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46667 

self.closeSec=1683361199, self.tradeDate='20230506', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29245.0, self.close=29257.4, self.high=29273.5, self.low=29224.7 
127.0.0.1 - - [06/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/May/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46668 

self.closeSec=1683361499, self.tradeDate='20230506', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29257.4, self.close=29284.9, self.high=29302.5, self.low=29246.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-06 16:00:18,253:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230506    132959  29342.6  ...  51.666667  0.535294  0.298824
5786  20230506    135959  29365.4  ...  51.666667  0.530421  0.306165
5787  20230506    142959  29340.5  ...  51.250000  0.529500  0.313273
5788  20230506    145959  29335.6  ...  51.250000  0.536558  0.317703
5789  20230506    152959  29376.1  ...  51.250000  0.540148  0.320713

[5 rows x 33 columns]
0.5535055350553506
acc is : 0.5535055350553506
2023-05-06 16:00:18,349:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.484051  0.515949       0  ...  0.990477  -1.0    0.0  1.068953
538     1  0.481733  0.518267       0  ...  0.990636  -1.0    0.0  1.068781
539     1  0.486219  0.513781       1  ...  0.989272  -1.0    0.0  1.070253
540     1  0.496988  0.503012       1  ...  0.988578  -1.0    0.0  1.071004
541     1  0.497949  0.502051       0  ...  0.990142  -1.0    0.0  1.069310

[5 rows x 10 columns]
2023-05-06 16:00:18,373:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483633  0.516367       0  ...  1.003621  -1.0    0.0  1.068953
46     1  0.481113  0.518887       0  ...  1.003782  -1.0    0.0  1.065466
47     1  0.486563  0.513437       1  ...  0.989272  -1.0    0.0  1.068319
48     1  0.496752  0.503248       1  ...  0.988578  -1.0    0.0  1.070033
49     1  0.497949  0.502051       0  ...  0.990142  -1.0    0.0  1.069310

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [06/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23329 

self.closeSec=1683358199, self.tradeDate='20230506', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29373.9', self.close='29396.7'
127.0.0.1 - - [06/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23330 

self.closeSec=1683358799, self.tradeDate='20230506', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29396.6', self.close='29377.9'
127.0.0.1 - - [06/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23331 

self.closeSec=1683359399, self.tradeDate='20230506', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29377.9', self.close='29357.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23332 

self.closeSec=1683359999, self.tradeDate='20230506', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29357.9', self.close='29350.2'
127.0.0.1 - - [06/May/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23333 

self.closeSec=1683360599, self.tradeDate='20230506', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29350.2', self.close='29242.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23334 

self.closeSec=1683361199, self.tradeDate='20230506', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29242.1', self.close='29257.4'
127.0.0.1 - - [06/May/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23330 

self.closeSec=1683358199, self.tradeDate='20230506', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29373.9', self.close='29396.7'
127.0.0.1 - - [06/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23331 

self.closeSec=1683358799, self.tradeDate='20230506', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29396.6', self.close='29377.9'
127.0.0.1 - - [06/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23332 

self.closeSec=1683359399, self.tradeDate='20230506', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29377.9', self.close='29357.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23333 

self.closeSec=1683359999, self.tradeDate='20230506', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29357.9', self.close='29350.2'
127.0.0.1 - - [06/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23334 

self.closeSec=1683360599, self.tradeDate='20230506', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29350.2', self.close='29242.1'
127.0.0.1 - - [06/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23335 

self.closeSec=1683361199, self.tradeDate='20230506', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29242.1', self.close='29257.4'
127.0.0.1 - - [06/May/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [06/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23330 

self.closeSec=1683358199, self.tradeDate='20230506', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29373.9', self.close='29396.7'
127.0.0.1 - - [06/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23331 

self.closeSec=1683358799, self.tradeDate='20230506', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29396.6', self.close='29377.9'
127.0.0.1 - - [06/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23332 

self.closeSec=1683359399, self.tradeDate='20230506', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29377.9', self.close='29357.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23333 

self.closeSec=1683359999, self.tradeDate='20230506', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29357.9', self.close='29350.2'
127.0.0.1 - - [06/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23334 

self.closeSec=1683360599, self.tradeDate='20230506', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29350.2', self.close='29242.1'
127.0.0.1 - - [06/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23335 

self.closeSec=1683361199, self.tradeDate='20230506', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29242.1', self.close='29257.4'
127.0.0.1 - - [06/May/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42099
self.closeSec=1683361199, self.tradeDate='20230506', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29245.0, self.close=29257.4, self.high=29273.5, self.low=29224.7, self.vol=1669.262, self.amt=48832016.2234 
127.0.0.1 - - [06/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-06 16:20:06,171:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230506   155500    155959  ...         0.0        0.0       0
5952  20230506   160000    160459  ...         0.0        0.0       0
5953  20230506   160500    160959  ...         0.0        0.0       0
5954  20230506   161000    161459  ...         0.0        0.0       0
5955  20230506   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 16:20:06,190:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683361199, self.tradeDate='20230506', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29245.0, self.close=29257.4, self.high=29273.5, self.low=29224.7, self.vol=1669.262, self.amt=48832016.2234, ukdf['pct'].iloc[-1]=0.000424 , ukdf['amount'].iloc[-1]=48832016.2234, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42100
self.closeSec=1683361499, self.tradeDate='20230506', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29257.4, self.close=29284.9, self.high=29302.5, self.low=29246.1, self.vol=2123.059, self.amt=62170483.4233 
127.0.0.1 - - [06/May/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-05-06 16:25:01,600:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230506   160000    160459  ...         0.0        0.0       0
5953  20230506   160500    160959  ...         0.0        0.0       0
5954  20230506   161000    161459  ...         0.0        0.0       0
5955  20230506   161500    161959  ...         0.0        0.0       0
5956  20230506   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 16:25:01,600:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683361499, self.tradeDate='20230506', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29257.4, self.close=29284.9, self.high=29302.5, self.low=29246.1, self.vol=2123.059, self.amt=62170483.4233, ukdf['pct'].iloc[-1]=0.00094 , ukdf['amount'].iloc[-1]=62170483.4233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230506   040000    075959  1683331199  ...    721  0.566793 -0.216533     NaN
722  20230506   080000    115959  1683345599  ...    722  0.593235 -0.130025     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '-663.3956', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29355.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=972
self.closeSec=1683359999, self.tradeDate='20230506', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29360.0, self.close=29350.2, self.high=29430.0, self.low=29225.3, self.vol=42728.114, self.amt=1253975762.23083 
2023-05-06 16:00:02,045:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683359999, self.tradeDate='20230506', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29360.0, self.close=29350.2, self.high=29430.0, self.low=29225.3, self.vol=42728.114, self.amt=1253975762.23083 
127.0.0.1 - - [06/May/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-05-06 16:00:02,094:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230505   200000    235959  ...  192645.919  5.611956e+09  0.007200
720  20230506   000000    035959  ...  133203.275  3.931405e+09  0.006859
721  20230506   040000    075959  ...   40781.438  1.203951e+09 -0.001936
722  20230506   080000    115959  ...   76988.632  2.276442e+09 -0.004456
723  20230506   120000    155959  ...   42728.114  1.253976e+09 -0.000337

[5 rows x 11 columns]
2023-05-06 16:00:03,431:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230505   200000    235959  1683302399  ...    719  0.502555 -0.420950     NaN
720  20230506   000000    035959  1683316799  ...    720  0.555457 -0.254955     NaN
721  20230506   040000    075959  1683331199  ...    721  0.566793 -0.216533     NaN
722  20230506   080000    115959  1683345599  ...    722  0.593235 -0.130025     NaN
723  20230506   120000    155959  1683359999  ...    723  0.511397 -0.376513     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '-420.462', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29350.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


