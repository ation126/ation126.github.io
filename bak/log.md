# 20230429 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44085
self.closeSec=1682756399, self.tradeDate='20230429', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29307.7, self.close=29300.3, self.high=29323.6, self.low=29294.5, self.vol=637.235, self.amt=18676861.7317 
127.0.0.1 - - [29/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-29 16:20:06,471:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230429   155500    155959  ...         0.0        0.0       0
5945  20230429   160000    160459  ...         0.0        0.0       0
5946  20230429   160500    160959  ...         0.0        0.0       0
5947  20230429   161000    161459  ...         0.0        0.0       0
5948  20230429   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 16:20:06,489:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682756399, self.tradeDate='20230429', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29307.7, self.close=29300.3, self.high=29323.6, self.low=29294.5, self.vol=637.235, self.amt=18676861.7317, ukdf['pct'].iloc[-1]=-0.000252 , ukdf['amount'].iloc[-1]=18676861.7317, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-768570.14402070176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29301.33775626', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44086
self.closeSec=1682756699, self.tradeDate='20230429', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29300.4, self.close=29269.7, self.high=29307.9, self.low=29250.0, self.vol=1987.999, self.amt=58199705.9224 
127.0.0.1 - - [29/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-29 16:25:01,596:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230429   160000    160459  ...         0.0        0.0       0
5946  20230429   160500    160959  ...         0.0        0.0       0
5947  20230429   161000    161459  ...         0.0        0.0       0
5948  20230429   161500    161959  ...         0.0        0.0       0
5949  20230429   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 16:25:01,596:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682756699, self.tradeDate='20230429', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29300.4, self.close=29269.7, self.high=29307.9, self.low=29250.0, self.vol=1987.999, self.amt=58199705.9224, ukdf['pct'].iloc[-1]=-0.001044 , ukdf['amount'].iloc[-1]=58199705.9224, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-766672.328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29269.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [29/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44647 

self.closeSec=1682755199, self.tradeDate='20230429', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29338.8, self.close=29333.9, self.high=29346.8, self.low=29332.5 
127.0.0.1 - - [29/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44648 

self.closeSec=1682755499, self.tradeDate='20230429', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29333.8, self.close=29328.0, self.high=29349.9, self.low=29325.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44649 

self.closeSec=1682755799, self.tradeDate='20230429', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29327.9, self.close=29311.4, self.high=29333.5, self.low=29308.0 
127.0.0.1 - - [29/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44650 

self.closeSec=1682756099, self.tradeDate='20230429', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29311.4, self.close=29307.7, self.high=29316.0, self.low=29284.3 
127.0.0.1 - - [29/Apr/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44651 

self.closeSec=1682756399, self.tradeDate='20230429', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29307.7, self.close=29300.3, self.high=29323.6, self.low=29294.5 
127.0.0.1 - - [29/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44652 

self.closeSec=1682756699, self.tradeDate='20230429', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29300.4, self.close=29269.7, self.high=29307.9, self.low=29250.0 
127.0.0.1 - - [29/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-29 16:00:21,852:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230429    132959  29363.0  ...  51.666667  0.527265  0.362344
5786  20230429    135959  29364.3  ...  51.666667  0.524436  0.351368
5787  20230429    142959  29345.9  ...  51.250000  0.517827  0.345944
5788  20230429    145959  29303.1  ...  51.666667  0.519699  0.339422
5789  20230429    152959  29316.0  ...  51.666667  0.518277  0.334345

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-04-29 16:00:21,946:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.515196  0.484804       0  ...  0.807471  -1.0    0.0  0.999659
538     0  0.510685  0.489315       0  ...  0.808652  -1.0    0.0  0.998198
539     0  0.504314  0.495686       1  ...  0.808293  -1.0    0.0  0.998641
540     0  0.511806  0.488194       0  ...  0.808541  -1.0    0.0  0.998334
541     0  0.508870  0.491130       1  ...  0.807802  -1.0    0.0  0.999247

[5 rows x 10 columns]
2023-04-29 16:00:21,972:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513899  0.486101       0  ...  0.806822  -1.0    0.0  0.995060
46     0  0.509918  0.490082       0  ...  0.808001  -1.0    0.0  0.994823
47     0  0.503910  0.496090       1  ...  0.807643  -1.0    0.0  0.996468
48     0  0.511438  0.488562       0  ...  0.808541  -1.0    0.0  0.997301
49     0  0.508870  0.491130       1  ...  0.807802  -1.0    0.0  0.999247

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22321 

self.closeSec=1682753399, self.tradeDate='20230429', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29294.9', self.close='29307.1'
127.0.0.1 - - [29/Apr/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22322 

self.closeSec=1682753999, self.tradeDate='20230429', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29307', self.close='29321.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22323 

self.closeSec=1682754599, self.tradeDate='20230429', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29321.6', self.close='29330.7'
127.0.0.1 - - [29/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22324 

self.closeSec=1682755199, self.tradeDate='20230429', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29330.7', self.close='29333.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22325 

self.closeSec=1682755799, self.tradeDate='20230429', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29333.8', self.close='29311.4'
127.0.0.1 - - [29/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22326 

self.closeSec=1682756399, self.tradeDate='20230429', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29311.4', self.close='29300.3'
127.0.0.1 - - [29/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22322 

self.closeSec=1682753399, self.tradeDate='20230429', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29294.9', self.close='29307.1'
127.0.0.1 - - [29/Apr/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22323 

self.closeSec=1682753999, self.tradeDate='20230429', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29307', self.close='29321.6'
127.0.0.1 - - [29/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22324 

self.closeSec=1682754599, self.tradeDate='20230429', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29321.6', self.close='29330.7'
127.0.0.1 - - [29/Apr/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22325 

self.closeSec=1682755199, self.tradeDate='20230429', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29330.7', self.close='29333.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22326 

self.closeSec=1682755799, self.tradeDate='20230429', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29333.8', self.close='29311.4'
127.0.0.1 - - [29/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22327 

self.closeSec=1682756399, self.tradeDate='20230429', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29311.4', self.close='29300.3'
127.0.0.1 - - [29/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [29/Apr/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22322 

self.closeSec=1682753399, self.tradeDate='20230429', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29294.9', self.close='29307.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22323 

self.closeSec=1682753999, self.tradeDate='20230429', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29307', self.close='29321.6'
127.0.0.1 - - [29/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22324 

self.closeSec=1682754599, self.tradeDate='20230429', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29321.6', self.close='29330.7'
127.0.0.1 - - [29/Apr/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22325 

self.closeSec=1682755199, self.tradeDate='20230429', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29330.7', self.close='29333.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22326 

self.closeSec=1682755799, self.tradeDate='20230429', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29333.8', self.close='29311.4'
127.0.0.1 - - [29/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22327 

self.closeSec=1682756399, self.tradeDate='20230429', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29311.4', self.close='29300.3'
127.0.0.1 - - [29/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40083
self.closeSec=1682756399, self.tradeDate='20230429', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29307.7, self.close=29300.3, self.high=29323.6, self.low=29294.5, self.vol=637.235, self.amt=18676861.7317 
127.0.0.1 - - [29/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-29 16:20:06,425:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230429   155500    155959  ...         0.0        0.0       0
5945  20230429   160000    160459  ...         0.0        0.0       0
5946  20230429   160500    160959  ...         0.0        0.0       0
5947  20230429   161000    161459  ...         0.0        0.0       0
5948  20230429   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 16:20:06,438:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682756399, self.tradeDate='20230429', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29307.7, self.close=29300.3, self.high=29323.6, self.low=29294.5, self.vol=637.235, self.amt=18676861.7317, ukdf['pct'].iloc[-1]=-0.000252 , ukdf['amount'].iloc[-1]=18676861.7317, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [29/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40084
self.closeSec=1682756699, self.tradeDate='20230429', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29300.4, self.close=29269.7, self.high=29307.9, self.low=29250.0, self.vol=1987.999, self.amt=58199705.9224 
2023-04-29 16:25:01,595:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230429   160000    160459  ...         0.0        0.0       0
5946  20230429   160500    160959  ...         0.0        0.0       0
5947  20230429   161000    161459  ...         0.0        0.0       0
5948  20230429   161500    161959  ...         0.0        0.0       0
5949  20230429   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 16:25:01,596:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682756699, self.tradeDate='20230429', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29300.4, self.close=29269.7, self.high=29307.9, self.low=29250.0, self.vol=1987.999, self.amt=58199705.9224, ukdf['pct'].iloc[-1]=-0.001044 , ukdf['amount'].iloc[-1]=58199705.9224, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230428   200000    235959  ...  170065.295  4.955369e+09 -0.003151
720  20230429   000000    035959  ...   89994.009  2.631370e+09  0.006305
721  20230429   040000    075959  ...   33331.207  9.776626e+08 -0.000600
722  20230429   080000    115959  ...   39776.622  1.165452e+09  0.000983
723  20230429   120000    155959  ...   36929.533  1.083732e+09  0.000174

[5 rows x 11 columns]
2023-04-29 16:00:05,372:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230428   200000    235959  1682697599  ...    719  0.693585  0.086854     NaN
720  20230429   000000    035959  1682711999  ...    720  0.649444 -0.061526     NaN
721  20230429   040000    075959  1682726399  ...    721  0.588055 -0.271519     NaN
722  20230429   080000    115959  1682740799  ...    722  0.509761 -0.538935     NaN
723  20230429   120000    155959  1682755199  ...    723  0.428820 -0.812974    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '18036.03233131164', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29334.05831316', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '18036.03233131164', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29334.05831316', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-04-29 16:00:12,286:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1374555.7001342', 'total': '1374555.7001342', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-04-29 16:00:12,824:INFO:s_rsrs:main.py:269:openSell:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 46.718, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42150F1682755212822I0L65'}
2023-04-29 16:00:12,844:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:4291600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230429, closeTime:155959, close:29333.9, sign:-1, total:1374555.7001342, side:sell  
127.0.0.1 - - [29/Apr/2023 16:00:12] "POST / HTTP/1.1" 200 -
2023-04-29 16:00:12,846:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42149F1682755207132I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682755207483422, 'quantity': '46.779', 'price': '29333.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1682755206217, 'updatetime': 1682755207483, 'tradetype': 'usdt', 'selfid': 42149, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682755207483, 'clientorderid': '42149F1682755207132I0L65', 'price': '29333.8', 'quantity': '46.779', 'commission': '1372.2058302', 'commissionasset': 'USDT', 'tradetime': 1682755207483, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682755207483}], 'gatetype': 'simulator', 'handletime': 0}
2023-04-29 16:00:12,847:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42149F1682755207132I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682755207483422, 'quantity': '46.779', 'price': '29333.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1682755206217, 'updatetime': 1682755207483, 'tradetype': 'usdt', 'selfid': 42149, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682755207483, 'clientorderid': '42149F1682755207132I0L65', 'price': '29333.8', 'quantity': '46.779', 'commission': '1372.2058302', 'commissionasset': 'USDT', 'tradetime': 1682755207483, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682755207483}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Apr/2023 16:00:12] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 16:00:13] "POST / HTTP/1.1" 200 -
2023-04-29 16:00:13,330:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42150F1682755212822I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682755213273215, 'quantity': '46.718', 'price': '29341.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1682755212321, 'updatetime': 1682755213273, 'tradetype': 'usdt', 'selfid': 42150, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682755213273, 'clientorderid': '42150F1682755212822I0L65', 'price': '29341.3', 'quantity': '46.718', 'commission': '1370.7668534', 'commissionasset': 'USDT', 'tradetime': 1682755213273, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682755213273}], 'gatetype': 'simulator', 'handletime': 0}
2023-04-29 16:00:13,543:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42150F1682755212822I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682755213273215, 'quantity': '46.718', 'price': '29341.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1682755212321, 'updatetime': 1682755213273, 'tradetype': 'usdt', 'selfid': 42150, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682755213273, 'clientorderid': '42150F1682755212822I0L65', 'price': '29341.3', 'quantity': '46.718', 'commission': '1370.7668534', 'commissionasset': 'USDT', 'tradetime': 1682755213273, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682755213273}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Apr/2023 16:00:13] "POST / HTTP/1.1" 200 -


