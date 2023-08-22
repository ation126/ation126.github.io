# 20230822 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28852
self.closeSec=1692692399, self.tradeDate='20230822', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26094.1, self.close=26077.0, self.high=26097.5, self.low=26077.0, self.vol=255.049, self.amt=6653371.6436 
127.0.0.1 - - [22/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-22 16:20:05,058:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230822   155500    155959  ...         0.0        0.0       0
5940  20230822   160000    160459  ...         0.0        0.0       0
5941  20230822   160500    160959  ...         0.0        0.0       0
5942  20230822   161000    161459  ...         0.0        0.0       0
5943  20230822   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 16:20:05,062:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692692399, self.tradeDate='20230822', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26094.1, self.close=26077.0, self.high=26097.5, self.low=26077.0, self.vol=255.049, self.amt=6653371.6436, ukdf['pct'].iloc[-1]=-0.000651 , ukdf['amount'].iloc[-1]=6653371.6436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10967.17551348078', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26077.36764947', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28853
self.closeSec=1692692699, self.tradeDate='20230822', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26077.0, self.close=26094.1, self.high=26097.0, self.low=26077.0, self.vol=337.905, self.amt=8815139.2508 
2023-08-22 16:25:00,831:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230822   160000    160459  ...         0.0        0.0       0
5941  20230822   160500    160959  ...         0.0        0.0       0
5942  20230822   161000    161459  ...         0.0        0.0       0
5943  20230822   161500    161959  ...         0.0        0.0       0
5944  20230822   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 16:25:00,831:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692692699, self.tradeDate='20230822', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26077.0, self.close=26094.1, self.high=26097.0, self.low=26077.0, self.vol=337.905, self.amt=8815139.2508, ukdf['pct'].iloc[-1]=0.000656 , ukdf['amount'].iloc[-1]=8815139.2508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10731.82569542226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26094.26767949', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28850 

self.closeSec=1692691199, self.tradeDate='20230822', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26080.0, self.close=26091.6, self.high=26095.9, self.low=26074.9 
127.0.0.1 - - [22/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28851 

self.closeSec=1692691499, self.tradeDate='20230822', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26091.7, self.close=26087.7, self.high=26100.0, self.low=26082.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28852 

self.closeSec=1692691799, self.tradeDate='20230822', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26087.7, self.close=26090.0, self.high=26090.0, self.low=26073.7 
127.0.0.1 - - [22/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28853 

self.closeSec=1692692099, self.tradeDate='20230822', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26089.9, self.close=26094.0, self.high=26099.4, self.low=26089.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28854 

self.closeSec=1692692399, self.tradeDate='20230822', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26094.1, self.close=26077.0, self.high=26097.5, self.low=26077.0 
127.0.0.1 - - [22/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28855 

self.closeSec=1692692699, self.tradeDate='20230822', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26077.0, self.close=26094.1, self.high=26097.0, self.low=26077.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-22 16:00:17,109:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230822    132959  26003.4  ...  46.666667  0.472929  0.472499
5786  20230822    135959  26019.4  ...  46.666667  0.476118  0.475832
5787  20230822    142959  26029.1  ...  47.083333  0.481151  0.476804
5788  20230822    145959  26044.6  ...  47.083333  0.485540  0.475851
5789  20230822    152959  26058.0  ...  47.500000  0.488996  0.473502

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-08-22 16:00:17,170:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.488693  0.511307       1  ...  1.093810  -1.0    0.0  0.883112
538     1  0.491537  0.508463       1  ...  1.093163  -1.0    0.0  0.883635
539     1  0.488661  0.511339       1  ...  1.092601  -1.0    0.0  0.884089
540     1  0.492583  0.507417       1  ...  1.092160  -1.0    0.0  0.884445
541     1  0.495089  0.504911       1  ...  1.091193  -1.0    0.0  0.885229

[5 rows x 10 columns]
2023-08-22 16:00:17,181:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488691  0.511309       1  ...  1.093810  -1.0    0.0  0.883625
46     1  0.491553  0.508447       1  ...  1.093163  -1.0    0.0  0.884439
47     1  0.488647  0.511353       1  ...  1.092601  -1.0    0.0  0.884798
48     1  0.492567  0.507433       1  ...  1.092160  -1.0    0.0  0.885368
49     1  0.495089  0.504911       1  ...  1.091193  -1.0    0.0  0.885229

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '-851.9328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26096.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14423 

self.closeSec=1692689399, self.tradeDate='20230822', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26072.9', self.close='26068.5'
127.0.0.1 - - [22/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14424 

self.closeSec=1692689999, self.tradeDate='20230822', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26068.6', self.close='26093'

--handleKline--: 127.0.0.1 - - [22/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14425 

self.closeSec=1692690599, self.tradeDate='20230822', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26093', self.close='26089.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14426 

self.closeSec=1692691199, self.tradeDate='20230822', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26089.2', self.close='26091.6'
127.0.0.1 - - [22/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14427 

self.closeSec=1692691799, self.tradeDate='20230822', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26091.7', self.close='26090'
127.0.0.1 - - [22/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14428 

self.closeSec=1692692399, self.tradeDate='20230822', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26089.9', self.close='26077'
127.0.0.1 - - [22/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14426 

self.closeSec=1692689399, self.tradeDate='20230822', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26072.9', self.close='26068.5'
127.0.0.1 - - [22/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14427 

self.closeSec=1692689999, self.tradeDate='20230822', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26068.6', self.close='26093'
127.0.0.1 - - [22/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14428 

self.closeSec=1692690599, self.tradeDate='20230822', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26093', self.close='26089.1'
127.0.0.1 - - [22/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14429 

self.closeSec=1692691199, self.tradeDate='20230822', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26089.2', self.close='26091.6'
127.0.0.1 - - [22/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14430 

self.closeSec=1692691799, self.tradeDate='20230822', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26091.7', self.close='26090'
127.0.0.1 - - [22/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14431 

self.closeSec=1692692399, self.tradeDate='20230822', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26089.9', self.close='26077'
127.0.0.1 - - [22/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14426 

self.closeSec=1692689399, self.tradeDate='20230822', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26072.9', self.close='26068.5'
127.0.0.1 - - [22/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14427 

self.closeSec=1692689999, self.tradeDate='20230822', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26068.6', self.close='26093'
127.0.0.1 - - [22/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14428 

self.closeSec=1692690599, self.tradeDate='20230822', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26093', self.close='26089.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14429 

self.closeSec=1692691199, self.tradeDate='20230822', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26089.2', self.close='26091.6'
127.0.0.1 - - [22/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14430 

self.closeSec=1692691799, self.tradeDate='20230822', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26091.7', self.close='26090'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14431 

self.closeSec=1692692399, self.tradeDate='20230822', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26089.9', self.close='26077'
127.0.0.1 - - [22/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28852
self.closeSec=1692692399, self.tradeDate='20230822', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26094.1, self.close=26077.0, self.high=26097.5, self.low=26077.0, self.vol=255.049, self.amt=6653371.6436 
127.0.0.1 - - [22/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-22 16:20:05,062:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230822   155500    155959  ...         0.0        0.0       0
5940  20230822   160000    160459  ...         0.0        0.0       0
5941  20230822   160500    160959  ...         0.0        0.0       0
5942  20230822   161000    161459  ...         0.0        0.0       0
5943  20230822   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 16:20:05,078:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692692399, self.tradeDate='20230822', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26094.1, self.close=26077.0, self.high=26097.5, self.low=26077.0, self.vol=255.049, self.amt=6653371.6436, ukdf['pct'].iloc[-1]=-0.000651 , ukdf['amount'].iloc[-1]=6653371.6436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-28473.49213103473', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26077.36764947', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28853
self.closeSec=1692692699, self.tradeDate='20230822', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26077.0, self.close=26094.1, self.high=26097.0, self.low=26077.0, self.vol=337.905, self.amt=8815139.2508 
2023-08-22 16:25:00,838:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230822   160000    160459  ...         0.0        0.0       0
5941  20230822   160500    160959  ...         0.0        0.0       0
5942  20230822   161000    161459  ...         0.0        0.0       0
5943  20230822   161500    161959  ...         0.0        0.0       0
5944  20230822   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 16:25:00,838:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692692699, self.tradeDate='20230822', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26077.0, self.close=26094.1, self.high=26097.0, self.low=26077.0, self.vol=337.905, self.amt=8815139.2508, ukdf['pct'].iloc[-1]=0.000656 , ukdf['amount'].iloc[-1]=8815139.2508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27845.80811606191', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26094.26767949', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230822   040000    075959  1692662399  ...    721  0.187173 -0.684183    -1.0
722  20230822   080000    115959  1692676799  ...    722  0.228351 -0.594178     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174231.014', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26042.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=601
self.closeSec=1692691199, self.tradeDate='20230822', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26042.2, self.close=26091.6, self.high=26108.7, self.low=25981.6, self.vol=18541.356, self.amt=482787634.667 
127.0.0.1 - - [22/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-08-22 16:00:01,528:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692691199, self.tradeDate='20230822', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26042.2, self.close=26091.6, self.high=26108.7, self.low=25981.6, self.vol=18541.356, self.amt=482787634.667 
2023-08-22 16:00:01,542:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230821   200000    235959  ...  78006.038  2.027997e+09 -0.003674
720  20230822   000000    035959  ...  34319.441  8.935149e+08  0.006210
721  20230822   040000    075959  ...  24701.899  6.458832e+08  0.001119
722  20230822   080000    115959  ...  15716.085  4.095923e+08 -0.002803
723  20230822   120000    155959  ...  18541.356  4.827876e+08  0.001897

[5 rows x 11 columns]
2023-08-22 16:00:02,238:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230821   200000    235959  1692633599  ...    719  0.088583 -0.907845    -1.0
720  20230822   000000    035959  1692647999  ...    720  0.002066 -1.101779    -1.0
721  20230822   040000    075959  1692662399  ...    721  0.187173 -0.684183    -1.0
722  20230822   080000    115959  1692676799  ...    722  0.228351 -0.594178     NaN
723  20230822   120000    155959  1692691199  ...    723  0.073155 -0.944331    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '171563.74475543048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26094.00451554', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


