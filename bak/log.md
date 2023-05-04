# 20230504 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45525
self.closeSec=1683188399, self.tradeDate='20230504', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28985.4, self.close=29025.6, self.high=29032.0, self.low=28967.4, self.vol=2142.741, self.amt=62137349.0381 
127.0.0.1 - - [04/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-04 16:20:06,556:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230504   155500    155959  ...         0.0        0.0       0
5952  20230504   160000    160459  ...         0.0        0.0       0
5953  20230504   160500    160959  ...         0.0        0.0       0
5954  20230504   161000    161459  ...         0.0        0.0       0
5955  20230504   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 16:20:06,565:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683188399, self.tradeDate='20230504', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28985.4, self.close=29025.6, self.high=29032.0, self.low=28967.4, self.vol=2142.741, self.amt=62137349.0381, ukdf['pct'].iloc[-1]=0.001383 , ukdf['amount'].iloc[-1]=62137349.0381, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-752260.176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29030.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45526
self.closeSec=1683188699, self.tradeDate='20230504', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29025.6, self.close=29036.9, self.high=29054.6, self.low=29025.5, self.vol=932.797, self.amt=27090598.547 
127.0.0.1 - - [04/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-05-04 16:25:02,104:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230504   160000    160459  ...         0.0        0.0       0
5953  20230504   160500    160959  ...         0.0        0.0       0
5954  20230504   161000    161459  ...         0.0        0.0       0
5955  20230504   161500    161959  ...         0.0        0.0       0
5956  20230504   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 16:25:02,104:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683188699, self.tradeDate='20230504', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29025.6, self.close=29036.9, self.high=29054.6, self.low=29025.5, self.vol=932.797, self.amt=27090598.547, ukdf['pct'].iloc[-1]=0.000389 , ukdf['amount'].iloc[-1]=27090598.547, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-752788.06590052704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29039.07243254', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46087 

self.closeSec=1683187199, self.tradeDate='20230504', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29052.0, self.close=29048.6, self.high=29073.0, self.low=29045.9 
127.0.0.1 - - [04/May/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46088 

self.closeSec=1683187499, self.tradeDate='20230504', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29048.7, self.close=29064.7, self.high=29064.8, self.low=29046.8 
127.0.0.1 - - [04/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46089 

self.closeSec=1683187799, self.tradeDate='20230504', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29064.8, self.close=29057.6, self.high=29073.0, self.low=29054.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46090 

self.closeSec=1683188099, self.tradeDate='20230504', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29057.6, self.close=28985.5, self.high=29057.6, self.low=28975.4 
127.0.0.1 - - [04/May/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46091 

self.closeSec=1683188399, self.tradeDate='20230504', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28985.4, self.close=29025.6, self.high=29032.0, self.low=28967.4 
127.0.0.1 - - [04/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 16:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46092 

self.closeSec=1683188699, self.tradeDate='20230504', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29025.6, self.close=29036.9, self.high=29054.6, self.low=29025.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-04 16:00:19,965:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230504    132959  29089.8  ...  50.833333  0.578736  0.276305
5786  20230504    135959  29106.6  ...  51.250000  0.590285  0.261698
5787  20230504    142959  29190.9  ...  51.250000  0.574870  0.252641
5788  20230504    145959  29110.1  ...  51.250000  0.580289  0.241971
5789  20230504    152959  29149.2  ...  51.250000  0.568241  0.235627

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-05-04 16:00:20,090:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.503290  0.496710       1  ...  0.844095   1.0    0.0  1.060226
538     0  0.521178  0.478822       0  ...  0.841756   1.0    0.0  1.057288
539     1  0.481715  0.518285       1  ...  0.842890   1.0    0.0  1.058712
540     0  0.505939  0.494061       0  ...  0.841042   1.0    0.0  1.056391
541     1  0.482065  0.517935       0  ...  0.839978   1.0    0.0  1.055054

[5 rows x 10 columns]
2023-05-04 16:00:20,121:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502426  0.497574       1  ...  0.844095   1.0    0.0  1.048610
46     0  0.520740  0.479260       0  ...  0.841756   1.0    0.0  1.047363
47     1  0.480711  0.519289       1  ...  0.842890   1.0    0.0  1.048264
48     0  0.505545  0.494455       0  ...  0.841042   1.0    0.0  1.049586
49     1  0.482065  0.517935       0  ...  0.839978   1.0    0.0  1.055054

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23041 

self.closeSec=1683185399, self.tradeDate='20230504', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29106.7', self.close='29085.4'
127.0.0.1 - - [04/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23042 

self.closeSec=1683185999, self.tradeDate='20230504', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29085.4', self.close='29059.7'
127.0.0.1 - - [04/May/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23043 

self.closeSec=1683186599, self.tradeDate='20230504', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29059.7', self.close='29042.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23044 

self.closeSec=1683187199, self.tradeDate='20230504', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29042.7', self.close='29048.6'
127.0.0.1 - - [04/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23045 

self.closeSec=1683187799, self.tradeDate='20230504', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29048.7', self.close='29057.6'
127.0.0.1 - - [04/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23046 

self.closeSec=1683188399, self.tradeDate='20230504', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29057.6', self.close='29025.6'
127.0.0.1 - - [04/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [04/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23042 

self.closeSec=1683185399, self.tradeDate='20230504', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29106.7', self.close='29085.4'
127.0.0.1 - - [04/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23043 

self.closeSec=1683185999, self.tradeDate='20230504', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29085.4', self.close='29059.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23044 

self.closeSec=1683186599, self.tradeDate='20230504', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29059.7', self.close='29042.8'
127.0.0.1 - - [04/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23045 

self.closeSec=1683187199, self.tradeDate='20230504', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29042.7', self.close='29048.6'
127.0.0.1 - - [04/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23046 

self.closeSec=1683187799, self.tradeDate='20230504', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29048.7', self.close='29057.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23047 

self.closeSec=1683188399, self.tradeDate='20230504', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29057.6', self.close='29025.6'
127.0.0.1 - - [04/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23042 

self.closeSec=1683185399, self.tradeDate='20230504', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29106.7', self.close='29085.4'
127.0.0.1 - - [04/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23043 

self.closeSec=1683185999, self.tradeDate='20230504', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29085.4', self.close='29059.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23044 

self.closeSec=1683186599, self.tradeDate='20230504', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29059.7', self.close='29042.8'
127.0.0.1 - - [04/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23045 

self.closeSec=1683187199, self.tradeDate='20230504', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29042.7', self.close='29048.6'
127.0.0.1 - - [04/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23046 

self.closeSec=1683187799, self.tradeDate='20230504', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29048.7', self.close='29057.6'
127.0.0.1 - - [04/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23047 

self.closeSec=1683188399, self.tradeDate='20230504', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29057.6', self.close='29025.6'
127.0.0.1 - - [04/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41523
self.closeSec=1683188399, self.tradeDate='20230504', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28985.4, self.close=29025.6, self.high=29032.0, self.low=28967.4, self.vol=2142.741, self.amt=62137349.0381 
127.0.0.1 - - [04/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-04 16:20:06,553:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230504   155500    155959  ...         0.0        0.0       0
5952  20230504   160000    160459  ...         0.0        0.0       0
5953  20230504   160500    160959  ...         0.0        0.0       0
5954  20230504   161000    161459  ...         0.0        0.0       0
5955  20230504   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 16:20:06,561:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683188399, self.tradeDate='20230504', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28985.4, self.close=29025.6, self.high=29032.0, self.low=28967.4, self.vol=2142.741, self.amt=62137349.0381, ukdf['pct'].iloc[-1]=0.001383 , ukdf['amount'].iloc[-1]=62137349.0381, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [04/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41524
self.closeSec=1683188699, self.tradeDate='20230504', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29025.6, self.close=29036.9, self.high=29054.6, self.low=29025.5, self.vol=932.797, self.amt=27090598.547 
2023-05-04 16:25:02,126:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230504   160000    160459  ...         0.0        0.0       0
5953  20230504   160500    160959  ...         0.0        0.0       0
5954  20230504   161000    161459  ...         0.0        0.0       0
5955  20230504   161500    161959  ...         0.0        0.0       0
5956  20230504   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-04 16:25:02,126:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683188699, self.tradeDate='20230504', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29025.6, self.close=29036.9, self.high=29054.6, self.low=29025.5, self.vol=932.797, self.amt=27090598.547, ukdf['pct'].iloc[-1]=0.000389 , ukdf['amount'].iloc[-1]=27090598.547, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230504   040000    075959  1683158399  ...    721  0.558697 -0.207774     NaN
722  20230504   080000    115959  1683172799  ...    722  0.575833 -0.157035     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '11852.3566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29087.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [04/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=960
self.closeSec=1683187199, self.tradeDate='20230504', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29084.7, self.close=29048.6, self.high=29228.1, self.low=29022.4, self.vol=50341.471, self.amt=1465750261.553 
2023-05-04 16:00:03,163:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683187199, self.tradeDate='20230504', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29084.7, self.close=29048.6, self.high=29228.1, self.low=29022.4, self.vol=50341.471, self.amt=1465750261.553 
2023-05-04 16:00:03,221:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230503   200000    235959  ...  135071.937  3.821706e+09 -0.008491
720  20230504   000000    035959  ...  229709.193  6.540452e+09  0.000569
721  20230504   040000    075959  ...  157117.840  4.540651e+09  0.025066
722  20230504   080000    115959  ...   48827.682  1.418092e+09  0.002285
723  20230504   120000    155959  ...   50341.471  1.465750e+09 -0.001241

[5 rows x 11 columns]
2023-05-04 16:00:04,687:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230503   200000    235959  1683129599  ...    719  0.606136 -0.059211     NaN
720  20230504   000000    035959  1683143999  ...    720  0.609041 -0.053257     NaN
721  20230504   040000    075959  1683158399  ...    721  0.558697 -0.207774     NaN
722  20230504   080000    115959  1683172799  ...    722  0.575833 -0.157035     NaN
723  20230504   120000    155959  1683187199  ...    723  0.587248 -0.124703     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '13613.04585989278', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29049.91240079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


