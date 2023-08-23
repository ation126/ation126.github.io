# 20230823 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29140
self.closeSec=1692778799, self.tradeDate='20230823', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26078.4, self.close=26056.0, self.high=26085.6, self.low=26055.2, self.vol=492.5, self.amt=12839411.8835 
127.0.0.1 - - [23/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-23 16:20:05,302:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230823   155500    155959  ...         0.0        0.0       0
5940  20230823   160000    160459  ...         0.0        0.0       0
5941  20230823   160500    160959  ...         0.0        0.0       0
5942  20230823   161000    161459  ...         0.0        0.0       0
5943  20230823   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 16:20:05,313:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692778799, self.tradeDate='20230823', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26078.4, self.close=26056.0, self.high=26085.6, self.low=26055.2, self.vol=492.5, self.amt=12839411.8835, ukdf['pct'].iloc[-1]=-0.000855 , ukdf['amount'].iloc[-1]=12839411.8835, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11241.0672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26057.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29141
self.closeSec=1692779099, self.tradeDate='20230823', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26056.0, self.close=26055.8, self.high=26063.5, self.low=26043.3, self.vol=441.755, self.amt=11509050.6671 
2023-08-23 16:25:00,793:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230823   160000    160459  ...         0.0        0.0       0
5941  20230823   160500    160959  ...         0.0        0.0       0
5942  20230823   161000    161459  ...         0.0        0.0       0
5943  20230823   161500    161959  ...         0.0        0.0       0
5944  20230823   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 16:25:00,793:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692779099, self.tradeDate='20230823', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26056.0, self.close=26055.8, self.high=26063.5, self.low=26043.3, self.vol=441.755, self.amt=11509050.6671, ukdf['pct'].iloc[-1]=-8e-06 , ukdf['amount'].iloc[-1]=11509050.6671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11267.5266', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26055.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [23/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29138 

self.closeSec=1692777599, self.tradeDate='20230823', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26039.7, self.close=26045.3, self.high=26046.0, self.low=26033.9 
127.0.0.1 - - [23/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29139 

self.closeSec=1692777899, self.tradeDate='20230823', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26045.3, self.close=26048.0, self.high=26053.3, self.low=26043.9 
127.0.0.1 - - [23/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29140 

self.closeSec=1692778199, self.tradeDate='20230823', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26048.0, self.close=26051.8, self.high=26053.3, self.low=26037.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29141 

self.closeSec=1692778499, self.tradeDate='20230823', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26051.8, self.close=26078.3, self.high=26078.4, self.low=26051.7 
127.0.0.1 - - [23/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29142 

self.closeSec=1692778799, self.tradeDate='20230823', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26078.4, self.close=26056.0, self.high=26085.6, self.low=26055.2 
127.0.0.1 - - [23/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29143 

self.closeSec=1692779099, self.tradeDate='20230823', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26056.0, self.close=26055.8, self.high=26063.5, self.low=26043.3 
127.0.0.1 - - [23/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-23 16:00:18,552:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230823    132959  26036.1  ...  49.583333  0.498271  0.352975
5786  20230823    135959  26007.8  ...  49.583333  0.503725  0.340473
5787  20230823    142959  26028.7  ...  49.583333  0.505954  0.328172
5788  20230823    145959  26037.1  ...  50.000000  0.508971  0.315844
5789  20230823    152959  26049.6  ...  50.416667  0.520839  0.300972

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-08-23 16:00:18,646:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.477804  0.522196       1  ...  1.090487   1.0    0.0  0.884646
538     1  0.497557  0.502443       1  ...  1.090843   1.0    0.0  0.884935
539     1  0.496348  0.503652       1  ...  1.091321   1.0    0.0  0.885323
540     1  0.495603  0.504397       1  ...  1.093219   1.0    0.0  0.886862
541     0  0.507054  0.492946       0  ...  1.091187   1.0    0.0  0.885214

[5 rows x 10 columns]
2023-08-23 16:00:18,667:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.477396  0.522604       1  ...  1.090487   1.0    0.0  0.884977
46     1  0.497147  0.502853       1  ...  1.090843   1.0    0.0  0.885014
47     1  0.496383  0.503617       1  ...  1.091321   1.0    0.0  0.885624
48     1  0.495151  0.504849       1  ...  1.093219   1.0    0.0  0.887074
49     0  0.507054  0.492946       0  ...  1.091187   1.0    0.0  0.885214

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.534', 'enterprice': '26078.7', 'countrevence': '0', 'unrealprofit': '-989.389', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26045.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14567 

self.closeSec=1692775799, self.tradeDate='20230823', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26119.2', self.close='26093.8'
127.0.0.1 - - [23/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14568 

self.closeSec=1692776399, self.tradeDate='20230823', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26093.8', self.close='26026.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14569 

self.closeSec=1692776999, self.tradeDate='20230823', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26026.4', self.close='26039.8'
127.0.0.1 - - [23/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14570 

self.closeSec=1692777599, self.tradeDate='20230823', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26039.8', self.close='26045.3'
127.0.0.1 - - [23/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14571 

self.closeSec=1692778199, self.tradeDate='20230823', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26045.3', self.close='26051.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14572 

self.closeSec=1692778799, self.tradeDate='20230823', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26051.8', self.close='26055.9'
127.0.0.1 - - [23/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [23/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14570 

self.closeSec=1692775799, self.tradeDate='20230823', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26119.2', self.close='26093.8'
127.0.0.1 - - [23/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14571 

self.closeSec=1692776399, self.tradeDate='20230823', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26093.8', self.close='26026.4'
127.0.0.1 - - [23/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14572 

self.closeSec=1692776999, self.tradeDate='20230823', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26026.4', self.close='26039.8'
127.0.0.1 - - [23/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14573 

self.closeSec=1692777599, self.tradeDate='20230823', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26039.8', self.close='26045.3'
127.0.0.1 - - [23/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14574 

self.closeSec=1692778199, self.tradeDate='20230823', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26045.3', self.close='26051.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14575 

self.closeSec=1692778799, self.tradeDate='20230823', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26051.8', self.close='26055.9'
127.0.0.1 - - [23/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14570 

self.closeSec=1692775799, self.tradeDate='20230823', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26119.2', self.close='26093.8'
127.0.0.1 - - [23/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14571 

self.closeSec=1692776399, self.tradeDate='20230823', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26093.8', self.close='26026.4'
127.0.0.1 - - [23/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14572 

self.closeSec=1692776999, self.tradeDate='20230823', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26026.4', self.close='26039.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14573 

self.closeSec=1692777599, self.tradeDate='20230823', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26039.8', self.close='26045.3'
127.0.0.1 - - [23/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14574 

self.closeSec=1692778199, self.tradeDate='20230823', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26045.3', self.close='26051.8'
127.0.0.1 - - [23/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14575 

self.closeSec=1692778799, self.tradeDate='20230823', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26051.8', self.close='26055.9'
127.0.0.1 - - [23/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29140
self.closeSec=1692778799, self.tradeDate='20230823', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26078.4, self.close=26056.0, self.high=26085.6, self.low=26055.2, self.vol=492.5, self.amt=12839411.8835 
127.0.0.1 - - [23/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-23 16:20:05,291:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230823   155500    155959  ...         0.0        0.0       0
5940  20230823   160000    160459  ...         0.0        0.0       0
5941  20230823   160500    160959  ...         0.0        0.0       0
5942  20230823   161000    161459  ...         0.0        0.0       0
5943  20230823   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 16:20:05,296:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692778799, self.tradeDate='20230823', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26078.4, self.close=26056.0, self.high=26085.6, self.low=26055.2, self.vol=492.5, self.amt=12839411.8835, ukdf['pct'].iloc[-1]=-0.000855 , ukdf['amount'].iloc[-1]=12839411.8835, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29203.9683', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26057.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29141
self.closeSec=1692779099, self.tradeDate='20230823', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26056.0, self.close=26055.8, self.high=26063.5, self.low=26043.3, self.vol=441.755, self.amt=11509050.6671 
127.0.0.1 - - [23/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-23 16:25:00,797:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230823   160000    160459  ...         0.0        0.0       0
5941  20230823   160500    160959  ...         0.0        0.0       0
5942  20230823   161000    161459  ...         0.0        0.0       0
5943  20230823   161500    161959  ...         0.0        0.0       0
5944  20230823   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 16:25:00,797:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692779099, self.tradeDate='20230823', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26056.0, self.close=26055.8, self.high=26063.5, self.low=26043.3, self.vol=441.755, self.amt=11509050.6671, ukdf['pct'].iloc[-1]=-8e-06 , ukdf['amount'].iloc[-1]=11509050.6671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29274.5362', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26055.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230823   040000    075959  1692748799  ...    721  0.020726 -1.055603    -1.0
722  20230823   080000    115959  1692763199  ...    722  0.019857 -1.058389    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '176678.10839553744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25994.48004212', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [23/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=607
self.closeSec=1692777599, self.tradeDate='20230823', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25992.0, self.close=26045.3, self.high=26170.0, self.low=25967.1, self.vol=36125.446, self.amt=941289234.7704 
2023-08-23 16:00:01,564:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692777599, self.tradeDate='20230823', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25992.0, self.close=26045.3, self.high=26170.0, self.low=25967.1, self.vol=36125.446, self.amt=941289234.7704 
2023-08-23 16:00:01,591:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230822   200000    235959  ...   44562.768  1.158462e+09 -0.004455
720  20230823   000000    035959  ...  116546.068  3.015657e+09 -0.006010
721  20230823   040000    075959  ...  102208.075  2.627786e+09  0.010758
722  20230823   080000    115959  ...   35799.297  9.329007e+08 -0.002008
723  20230823   120000    155959  ...   36125.446  9.412892e+08  0.002047

[5 rows x 11 columns]
2023-08-23 16:00:02,534:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230822   200000    235959  1692719999  ...    719  0.000080 -1.102173    -1.0
720  20230823   000000    035959  1692734399  ...    720  0.002444 -1.096267    -1.0
721  20230823   040000    075959  1692748799  ...    721  0.020726 -1.055603    -1.0
722  20230823   080000    115959  1692763199  ...    722  0.019857 -1.058389    -1.0
723  20230823   120000    155959  1692777599  ...    723  0.020046 -1.058495    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174066.5724', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26045.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


