# 20231021 16:26:10

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46132
self.closeSec=1697876399, self.tradeDate='20231021', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29645.5, self.close=29659.2, self.high=29676.0, self.low=29644.5, self.vol=346.133, self.amt=10265470.8073 
127.0.0.1 - - [21/Oct/2023 16:20:14] "POST / HTTP/1.1" 200 -
2023-10-21 16:20:20,993:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231021   155500    155959  ...         0.0        0.0       0
5952  20231021   160000    160459  ...         0.0        0.0       0
5953  20231021   160500    160959  ...         0.0        0.0       0
5954  20231021   161000    161459  ...         0.0        0.0       0
5955  20231021   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 16:20:21,013:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697876399, self.tradeDate='20231021', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29645.5, self.close=29659.2, self.high=29676.0, self.low=29644.5, self.vol=346.133, self.amt=10265470.8073, ukdf['pct'].iloc[-1]=0.000462 , ukdf['amount'].iloc[-1]=10265470.8073, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-38994.1926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29665', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46133
self.closeSec=1697876699, self.tradeDate='20231021', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29659.2, self.close=29681.0, self.high=29683.9, self.low=29656.0, self.vol=335.951, self.amt=9967425.4583 
127.0.0.1 - - [21/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-21 16:25:03,062:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231021   160000    160459  ...         0.0        0.0       0
5953  20231021   160500    160959  ...         0.0        0.0       0
5954  20231021   161000    161459  ...         0.0        0.0       0
5955  20231021   161500    161959  ...         0.0        0.0       0
5956  20231021   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 16:25:03,065:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697876699, self.tradeDate='20231021', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29659.2, self.close=29681.0, self.high=29683.9, self.low=29656.0, self.vol=335.951, self.amt=9967425.4583, ukdf['pct'].iloc[-1]=0.000735 , ukdf['amount'].iloc[-1]=9967425.4583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-39190.5492', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29679.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46130 

self.closeSec=1697875199, self.tradeDate='20231021', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29681.3, self.close=29682.5, self.high=29692.8, self.low=29679.4 
127.0.0.1 - - [21/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46131 

self.closeSec=1697875499, self.tradeDate='20231021', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29681.1, self.close=29657.0, self.high=29685.0, self.low=29656.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46132 

self.closeSec=1697875799, self.tradeDate='20231021', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29657.0, self.close=29644.8, self.high=29660.8, self.low=29642.8 
127.0.0.1 - - [21/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46133 

self.closeSec=1697876099, self.tradeDate='20231021', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29645.6, self.close=29645.5, self.high=29651.5, self.low=29642.9 
127.0.0.1 - - [21/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46134 

self.closeSec=1697876399, self.tradeDate='20231021', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29645.5, self.close=29659.2, self.high=29676.0, self.low=29644.5 
127.0.0.1 - - [21/Oct/2023 16:20:12] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46135 

self.closeSec=1697876699, self.tradeDate='20231021', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29659.2, self.close=29681.0, self.high=29683.9, self.low=29656.0 
127.0.0.1 - - [21/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-21 16:00:17,323:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231021    132959  29540.4  ...  52.500000  0.572171  0.539016
5786  20231021    135959  29560.0  ...  52.500000  0.572867  0.551261
5787  20231021    142959  29564.5  ...  52.916667  0.587100  0.556207
5788  20231021    145959  29654.9  ...  53.333333  0.592112  0.550330
5789  20231021    152959  29688.6  ...  53.333333  0.594593  0.543343

[5 rows x 33 columns]
0.5571955719557196
acc is : 0.5571955719557196
2023-10-21 16:00:17,393:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.522029  0.477971       1  ...  0.978072  -1.0    0.0  1.073496
538     0  0.514920  0.485080       1  ...  0.975052  -1.0    0.0  1.076811
539     0  0.540262  0.459738       1  ...  0.973967  -1.0    0.0  1.078009
540     0  0.530197  0.469803       1  ...  0.973432  -1.0    0.0  1.078601
541     0  0.529420  0.470580       0  ...  0.974169  -1.0    0.0  1.077784

[5 rows x 10 columns]
2023-10-21 16:00:17,406:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.521331  0.478669       1  ...  0.978072  -1.0    0.0  1.072110
46     0  0.514236  0.485764       1  ...  0.975052  -1.0    0.0  1.075901
47     0  0.539515  0.460485       1  ...  0.973967  -1.0    0.0  1.076520
48     0  0.529374  0.470626       1  ...  0.973432  -1.0    0.0  1.076268
49     0  0.529420  0.470580       0  ...  0.974169  -1.0    0.0  1.077784

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.539', 'enterprice': '29526.5', 'countrevence': '0', 'unrealprofit': '-3333.85917439575', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29681.28244925', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [21/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23063 

self.closeSec=1697873399, self.tradeDate='20231021', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29655.2', self.close='29705.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23064 

self.closeSec=1697873999, self.tradeDate='20231021', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29705', self.close='29689.7'
127.0.0.1 - - [21/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23065 

self.closeSec=1697874599, self.tradeDate='20231021', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29689.7', self.close='29687.1'
127.0.0.1 - - [21/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23066 

self.closeSec=1697875199, self.tradeDate='20231021', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29687.2', self.close='29681'
127.0.0.1 - - [21/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23067 

self.closeSec=1697875799, self.tradeDate='20231021', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29681.1', self.close='29644.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23068 

self.closeSec=1697876399, self.tradeDate='20231021', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29645.6', self.close='29659.2'
127.0.0.1 - - [21/Oct/2023 16:20:15] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [21/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23066 

self.closeSec=1697873399, self.tradeDate='20231021', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29655.2', self.close='29705.1'
127.0.0.1 - - [21/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23067 

self.closeSec=1697873999, self.tradeDate='20231021', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29705', self.close='29689.7'
127.0.0.1 - - [21/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23068 

self.closeSec=1697874599, self.tradeDate='20231021', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29689.7', self.close='29687.1'
127.0.0.1 - - [21/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23069 

self.closeSec=1697875199, self.tradeDate='20231021', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29687.2', self.close='29681'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23070 

self.closeSec=1697875799, self.tradeDate='20231021', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29681.1', self.close='29644.8'
127.0.0.1 - - [21/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23071 

self.closeSec=1697876399, self.tradeDate='20231021', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29645.6', self.close='29659.2'
127.0.0.1 - - [21/Oct/2023 16:20:15] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23066 

self.closeSec=1697873399, self.tradeDate='20231021', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29655.2', self.close='29705.1'
127.0.0.1 - - [21/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [21/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23067 

self.closeSec=1697873999, self.tradeDate='20231021', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29705', self.close='29689.7'
127.0.0.1 - - [21/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23068 

self.closeSec=1697874599, self.tradeDate='20231021', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29689.7', self.close='29687.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23069 

self.closeSec=1697875199, self.tradeDate='20231021', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29687.2', self.close='29681'
127.0.0.1 - - [21/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23070 

self.closeSec=1697875799, self.tradeDate='20231021', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29681.1', self.close='29644.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23071 

self.closeSec=1697876399, self.tradeDate='20231021', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29645.6', self.close='29659.2'
127.0.0.1 - - [21/Oct/2023 16:20:15] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46132
self.closeSec=1697876399, self.tradeDate='20231021', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29645.5, self.close=29659.2, self.high=29676.0, self.low=29644.5, self.vol=346.133, self.amt=10265470.8073 
127.0.0.1 - - [21/Oct/2023 16:20:14] "POST / HTTP/1.1" 200 -
2023-10-21 16:20:20,983:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231021   155500    155959  ...         0.0        0.0       0
5952  20231021   160000    160459  ...         0.0        0.0       0
5953  20231021   160500    160959  ...         0.0        0.0       0
5954  20231021   161000    161459  ...         0.0        0.0       0
5955  20231021   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 16:20:21,003:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697876399, self.tradeDate='20231021', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29645.5, self.close=29659.2, self.high=29676.0, self.low=29644.5, self.vol=346.133, self.amt=10265470.8073, ukdf['pct'].iloc[-1]=0.000462 , ukdf['amount'].iloc[-1]=10265470.8073, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '104774.761', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29665', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46133
self.closeSec=1697876699, self.tradeDate='20231021', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29659.2, self.close=29681.0, self.high=29683.9, self.low=29656.0, self.vol=335.951, self.amt=9967425.4583 
127.0.0.1 - - [21/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-21 16:25:03,062:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231021   160000    160459  ...         0.0        0.0       0
5953  20231021   160500    160959  ...         0.0        0.0       0
5954  20231021   161000    161459  ...         0.0        0.0       0
5955  20231021   161500    161959  ...         0.0        0.0       0
5956  20231021   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 16:25:03,065:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697876699, self.tradeDate='20231021', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29659.2, self.close=29681.0, self.high=29683.9, self.low=29656.0, self.vol=335.951, self.amt=9967425.4583, ukdf['pct'].iloc[-1]=0.000735 , ukdf['amount'].iloc[-1]=9967425.4583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '105298.4491', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29679.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231021   040000    075959  1697846399  ...    721  1.157986  0.864808     1.0
722  20231021   080000    115959  1697860799  ...    722  1.073225  0.726643     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '2243.2441360686', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29593.4357326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=961127.0.0.1 - - [21/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1697875199, self.tradeDate='20231021', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29591.0, self.close=29682.5, self.high=29725.8, self.low=29524.4, self.vol=23430.769, self.amt=694345500.7913 
2023-10-21 16:00:01,522:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697875199, self.tradeDate='20231021', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29591.0, self.close=29682.5, self.high=29725.8, self.low=29524.4, self.vol=23430.769, self.amt=694345500.7913 
2023-10-21 16:00:01,537:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231020   200000    235959  ...  114979.415  3.399972e+09 -0.009649
720  20231021   000000    035959  ...   37888.713  1.116360e+09  0.000376
721  20231021   040000    075959  ...   34230.291  1.014654e+09  0.003492
722  20231021   080000    115959  ...   29914.061  8.840110e+08 -0.002091
723  20231021   120000    155959  ...   23430.769  6.943455e+08  0.003089

[5 rows x 11 columns]
2023-10-21 16:00:02,330:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231020   200000    235959  1697817599  ...    719  0.094832 -0.801326    -1.0
720  20231021   000000    035959  1697831999  ...    720  1.157761  0.882013     1.0
721  20231021   040000    075959  1697846399  ...    721  1.157986  0.864808     1.0
722  20231021   080000    115959  1697860799  ...    722  1.073225  0.726643     1.0
723  20231021   120000    155959  1697875199  ...    723  0.992068  0.595616     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '5897.6746105686', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29681.7902326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


