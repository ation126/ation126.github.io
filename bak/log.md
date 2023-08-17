# 20230817 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27412
self.closeSec=1692260399, self.tradeDate='20230817', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28603.0, self.close=28591.2, self.high=28603.0, self.low=28589.3, self.vol=441.819, self.amt=12634093.4142 
127.0.0.1 - - [17/Aug/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-08-17 16:20:05,430:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230817   155500    155959  ...         0.0        0.0       0
5940  20230817   160000    160459  ...         0.0        0.0       0
5941  20230817   160500    160959  ...         0.0        0.0       0
5942  20230817   161000    161459  ...         0.0        0.0       0
5943  20230817   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 16:20:05,441:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692260399, self.tradeDate='20230817', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28603.0, self.close=28591.2, self.high=28603.0, self.low=28589.3, self.vol=441.819, self.amt=12634093.4142, ukdf['pct'].iloc[-1]=-0.000413 , ukdf['amount'].iloc[-1]=12634093.4142, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-24024.02755255866', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28590.02046191', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27413
self.closeSec=1692260699, self.tradeDate='20230817', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28591.1, self.close=28573.0, self.high=28591.2, self.low=28570.5, self.vol=1309.593, self.amt=37427076.1414 
2023-08-17 16:25:00,769:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230817   160000    160459  ...         0.0        0.0       0
5941  20230817   160500    160959  ...         0.0        0.0       0
5942  20230817   161000    161459  ...         0.0        0.0       0
5943  20230817   161500    161959  ...         0.0        0.0       0
5944  20230817   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 16:25:00,770:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692260699, self.tradeDate='20230817', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28591.1, self.close=28573.0, self.high=28591.2, self.low=28570.5, self.vol=1309.593, self.amt=37427076.1414, ukdf['pct'].iloc[-1]=-0.000637 , ukdf['amount'].iloc[-1]=37427076.1414, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-23805.77240181096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28574.34796796', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27410 

self.closeSec=1692259199, self.tradeDate='20230817', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28610.1, self.close=28613.1, self.high=28615.1, self.low=28600.9 
127.0.0.1 - - [17/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27411 

self.closeSec=1692259499, self.tradeDate='20230817', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28613.1, self.close=28623.8, self.high=28623.9, self.low=28610.0 
127.0.0.1 - - [17/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27412 

self.closeSec=1692259799, self.tradeDate='20230817', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28623.8, self.close=28609.0, self.high=28627.8, self.low=28608.9 
127.0.0.1 - - [17/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27413 

self.closeSec=1692260099, self.tradeDate='20230817', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28609.0, self.close=28603.0, self.high=28609.0, self.low=28602.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27414 

self.closeSec=1692260399, self.tradeDate='20230817', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28603.0, self.close=28591.2, self.high=28603.0, self.low=28589.3 
127.0.0.1 - - [17/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27415 

self.closeSec=1692260699, self.tradeDate='20230817', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28591.1, self.close=28573.0, self.high=28591.2, self.low=28570.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-17 16:00:20,180:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230817    132959  28636.6  ...  46.250000  0.377046  0.662186
5786  20230817    135959  28642.7  ...  46.666667  0.387208  0.657566
5787  20230817    142959  28671.8  ...  46.666667  0.385771  0.653721
5788  20230817    145959  28665.1  ...  47.083333  0.389519  0.649374
5789  20230817    152959  28675.8  ...  46.666667  0.376613  0.649491

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-08-17 16:00:20,238:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.500734  0.499266       1  ...  0.988535  -1.0    0.0  0.986811
538     0  0.506905  0.493095       0  ...  0.988762  -1.0    0.0  0.986584
539     1  0.495707  0.504293       1  ...  0.988393  -1.0    0.0  0.986952
540     0  0.501506  0.498494       0  ...  0.990423  -1.0    0.0  0.984925
541     1  0.474544  0.525456       0  ...  0.990555  -1.0    0.0  0.984794

[5 rows x 10 columns]
2023-08-17 16:00:20,249:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500463  0.499537       1  ...  0.988535  -1.0    0.0  0.986577
46     0  0.506532  0.493468       0  ...  0.988762  -1.0    0.0  0.985783
47     1  0.495422  0.504578       1  ...  0.988393  -1.0    0.0  0.986338
48     0  0.501376  0.498624       0  ...  0.990423  -1.0    0.0  0.984830
49     1  0.474544  0.525456       0  ...  0.990555  -1.0    0.0  0.984794

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.207', 'enterprice': '29084.9', 'countrevence': '0', 'unrealprofit': '11435.74183608069', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28612.48533333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13703 

self.closeSec=1692257399, self.tradeDate='20230817', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28615', self.close='28616.9'
127.0.0.1 - - [17/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [17/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13704 

self.closeSec=1692257999, self.tradeDate='20230817', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28616.9', self.close='28606.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13705 

self.closeSec=1692258599, self.tradeDate='20230817', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28606.1', self.close='28598.9'
127.0.0.1 - - [17/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13706 

self.closeSec=1692259199, self.tradeDate='20230817', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28598.9', self.close='28613'
127.0.0.1 - - [17/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13707 

self.closeSec=1692259799, self.tradeDate='20230817', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28613.1', self.close='28609'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13708 

self.closeSec=1692260399, self.tradeDate='20230817', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28609', self.close='28591.2'
127.0.0.1 - - [17/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13706 

self.closeSec=1692257399, self.tradeDate='20230817', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28615', self.close='28616.9'
127.0.0.1 - - [17/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13707 

self.closeSec=1692257999, self.tradeDate='20230817', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28616.9', self.close='28606.1'
127.0.0.1 - - [17/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13708 

self.closeSec=1692258599, self.tradeDate='20230817', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28606.1', self.close='28598.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13709 

self.closeSec=1692259199, self.tradeDate='20230817', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28598.9', self.close='28613'
127.0.0.1 - - [17/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13710 

self.closeSec=1692259799, self.tradeDate='20230817', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28613.1', self.close='28609'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13711 

self.closeSec=1692260399, self.tradeDate='20230817', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28609', self.close='28591.2'
127.0.0.1 - - [17/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13706 

self.closeSec=1692257399, self.tradeDate='20230817', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28615', self.close='28616.9'
127.0.0.1 - - [17/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13707 

self.closeSec=1692257999, self.tradeDate='20230817', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28616.9', self.close='28606.1'
127.0.0.1 - - [17/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13708 

self.closeSec=1692258599, self.tradeDate='20230817', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28606.1', self.close='28598.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13709 

self.closeSec=1692259199, self.tradeDate='20230817', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28598.9', self.close='28613'
127.0.0.1 - - [17/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13710 

self.closeSec=1692259799, self.tradeDate='20230817', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28613.1', self.close='28609'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13711 

self.closeSec=1692260399, self.tradeDate='20230817', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28609', self.close='28591.2'
127.0.0.1 - - [17/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27412
self.closeSec=1692260399, self.tradeDate='20230817', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28603.0, self.close=28591.2, self.high=28603.0, self.low=28589.3, self.vol=441.819, self.amt=12634093.4142 
127.0.0.1 - - [17/Aug/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-08-17 16:20:05,405:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230817   155500    155959  ...         0.0        0.0       0
5940  20230817   160000    160459  ...         0.0        0.0       0
5941  20230817   160500    160959  ...         0.0        0.0       0
5942  20230817   161000    161459  ...         0.0        0.0       0
5943  20230817   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 16:20:05,414:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692260399, self.tradeDate='20230817', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28603.0, self.close=28591.2, self.high=28603.0, self.low=28589.3, self.vol=441.819, self.amt=12634093.4142, ukdf['pct'].iloc[-1]=-0.000413 , ukdf['amount'].iloc[-1]=12634093.4142, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '64848.94597579931', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28590.02046191', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27413
self.closeSec=1692260699, self.tradeDate='20230817', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28591.1, self.close=28573.0, self.high=28591.2, self.low=28570.5, self.vol=1309.593, self.amt=37427076.1414 
127.0.0.1 - - [17/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-17 16:25:00,767:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230817   160000    160459  ...         0.0        0.0       0
5941  20230817   160500    160959  ...         0.0        0.0       0
5942  20230817   161000    161459  ...         0.0        0.0       0
5943  20230817   161500    161959  ...         0.0        0.0       0
5944  20230817   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 16:25:00,768:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692260699, self.tradeDate='20230817', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28591.1, self.close=28573.0, self.high=28591.2, self.low=28570.5, self.vol=1309.593, self.amt=37427076.1414, ukdf['pct'].iloc[-1]=-0.000637 , ukdf['amount'].iloc[-1]=37427076.1414, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '64266.85387800236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28574.34796796', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230817   040000    075959  1692230399  ...    721  0.147228 -0.788914    -1.0
722  20230817   080000    115959  1692244799  ...    722  0.272425 -0.507407     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '40581.8777139708', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28642.8849359', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=571
self.closeSec=1692259199, self.tradeDate='20230817', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28643.5, self.close=28613.1, self.high=28694.9, self.low=28590.2, self.vol=27424.778, self.amt=785438624.7684 
127.0.0.1 - - [17/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-08-17 16:00:01,590:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692259199, self.tradeDate='20230817', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28643.5, self.close=28613.1, self.high=28694.9, self.low=28590.2, self.vol=27424.778, self.amt=785438624.7684 
2023-08-17 16:00:01,607:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230816   200000    235959  ...   52724.950  1.535489e+09 -0.000717
720  20230817   000000    035959  ...   75411.961  2.192964e+09 -0.000978
721  20230817   040000    075959  ...   81121.615  2.344017e+09 -0.013437
722  20230817   080000    115959  ...  100604.312  2.873872e+09 -0.002469
723  20230817   120000    155959  ...   27424.778  7.854386e+08 -0.001061

[5 rows x 11 columns]
2023-08-17 16:00:02,346:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230816   200000    235959  1692201599  ...    719  0.112624 -0.865000    -1.0
720  20230817   000000    035959  1692215999  ...    720  0.134955 -0.814892    -1.0
721  20230817   040000    075959  1692230399  ...    721  0.147228 -0.788914    -1.0
722  20230817   080000    115959  1692244799  ...    722  0.272425 -0.507407     NaN
723  20230817   120000    155959  1692259199  ...    723  0.389168 -0.246678     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '42038.18191678332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28614.54555311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


