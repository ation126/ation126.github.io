# 20231002 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40660
self.closeSec=1696234799, self.tradeDate='20231002', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28324.1, self.close=28363.6, self.high=28385.0, self.low=28311.1, self.vol=2337.75, self.amt=66291672.9344 
127.0.0.1 - - [02/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-02 16:20:06,205:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231002   155500    155959  ...         0.0        0.0       0
5952  20231002   160000    160459  ...         0.0        0.0       0
5953  20231002   160500    160959  ...         0.0        0.0       0
5954  20231002   161000    161459  ...         0.0        0.0       0
5955  20231002   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 16:20:06,215:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696234799, self.tradeDate='20231002', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28324.1, self.close=28363.6, self.high=28385.0, self.low=28311.1, self.vol=2337.75, self.amt=66291672.9344, ukdf['pct'].iloc[-1]=0.001366 , ukdf['amount'].iloc[-1]=66291672.9344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-20944.92487722228', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28368.91586078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40661
self.closeSec=1696235099, self.tradeDate='20231002', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28359.0, self.close=28363.4, self.high=28409.1, self.low=28354.5, self.vol=3140.745, self.amt=89135017.5995 
127.0.0.1 - - [02/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-10-02 16:25:00,826:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231002   160000    160459  ...         0.0        0.0       0
5953  20231002   160500    160959  ...         0.0        0.0       0
5954  20231002   161000    161459  ...         0.0        0.0       0
5955  20231002   161500    161959  ...         0.0        0.0       0
5956  20231002   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 16:25:00,827:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696235099, self.tradeDate='20231002', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28359.0, self.close=28363.4, self.high=28409.1, self.low=28354.5, self.vol=3140.745, self.amt=89135017.5995, ukdf['pct'].iloc[-1]=-7e-06 , ukdf['amount'].iloc[-1]=89135017.5995, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-20870.94690707268', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28363.60364118', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [02/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40658 

self.closeSec=1696233599, self.tradeDate='20231002', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28269.3, self.close=28300.0, self.high=28300.0, self.low=28215.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40659 

self.closeSec=1696233899, self.tradeDate='20231002', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28299.2, self.close=28262.0, self.high=28323.9, self.low=28235.9 
127.0.0.1 - - [02/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40660 

self.closeSec=1696234199, self.tradeDate='20231002', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28266.5, self.close=28289.0, self.high=28299.0, self.low=28238.1 
127.0.0.1 - - [02/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40661 

self.closeSec=1696234499, self.tradeDate='20231002', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28295.0, self.close=28324.9, self.high=28364.0, self.low=28292.4 
127.0.0.1 - - [02/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40662 

self.closeSec=1696234799, self.tradeDate='20231002', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28324.1, self.close=28363.6, self.high=28385.0, self.low=28311.1 
127.0.0.1 - - [02/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40663 

self.closeSec=1696235099, self.tradeDate='20231002', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28359.0, self.close=28363.4, self.high=28409.1, self.low=28354.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-02 16:00:19,119:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231002    132959  28054.0  ...  55.833333  0.690169  0.337056
5786  20231002    135959  28082.9  ...  55.416667  0.654301  0.334316
5787  20231002    142959  27966.0  ...  55.833333  0.664708  0.328372
5788  20231002    145959  28034.2  ...  55.833333  0.672381  0.320241
5789  20231002    152959  28086.5  ...  56.250000  0.685888  0.307898

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-10-02 16:00:19,182:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.514944  0.485056       0  ...  0.954487   1.0    0.0  1.034499
538     1  0.468206  0.531794       1  ...  0.956828   1.0    0.0  1.037036
539     0  0.513980  0.486020       1  ...  0.958613   1.0    0.0  1.038971
540     0  0.516641  0.483359       1  ...  0.961900   1.0    0.0  1.042533
541     0  0.532710  0.467290       1  ...  0.965900   1.0    0.0  1.046869

[5 rows x 10 columns]
2023-10-02 16:00:19,196:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514660  0.485340       0  ...  0.954487   1.0    0.0  1.032730
46     1  0.467886  0.532114       1  ...  0.956828   1.0    0.0  1.033111
47     0  0.513496  0.486504       1  ...  0.958613   1.0    0.0  1.036108
48     0  0.516504  0.483496       1  ...  0.961900   1.0    0.0  1.040509
49     0  0.532710  0.467290       1  ...  0.965900   1.0    0.0  1.046869

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.95', 'enterprice': '28012.5', 'countrevence': '0', 'unrealprofit': '7151.47', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28311.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20327 

self.closeSec=1696231799, self.tradeDate='20231002', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28133.9', self.close='28182.8'
127.0.0.1 - - [02/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [02/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20328 

self.closeSec=1696232399, self.tradeDate='20231002', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28179.1', self.close='28287.7'
127.0.0.1 - - [02/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20329 

self.closeSec=1696232999, self.tradeDate='20231002', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28291.6', self.close='28353.1'
127.0.0.1 - - [02/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20330 

self.closeSec=1696233599, self.tradeDate='20231002', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28351.9', self.close='28299.1'
127.0.0.1 - - [02/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20331 

self.closeSec=1696234199, self.tradeDate='20231002', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28299.2', self.close='28289'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20332 

self.closeSec=1696234799, self.tradeDate='20231002', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28295', self.close='28363.6'
127.0.0.1 - - [02/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20330 

self.closeSec=1696231799, self.tradeDate='20231002', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28133.9', self.close='28182.8'
127.0.0.1 - - [02/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20331 

self.closeSec=1696232399, self.tradeDate='20231002', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28179.1', self.close='28287.7'
127.0.0.1 - - [02/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20332 

self.closeSec=1696232999, self.tradeDate='20231002', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28291.6', self.close='28353.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20333 

self.closeSec=1696233599, self.tradeDate='20231002', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28351.9', self.close='28299.1'
127.0.0.1 - - [02/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20334 

self.closeSec=1696234199, self.tradeDate='20231002', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28299.2', self.close='28289'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20335 

self.closeSec=1696234799, self.tradeDate='20231002', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28295', self.close='28363.6'
127.0.0.1 - - [02/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20330 

self.closeSec=1696231799, self.tradeDate='20231002', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28133.9', self.close='28182.8'
127.0.0.1 - - [02/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20331 

self.closeSec=1696232399, self.tradeDate='20231002', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28179.1', self.close='28287.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20332 

self.closeSec=1696232999, self.tradeDate='20231002', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28291.6', self.close='28353.1'
127.0.0.1 - - [02/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20333 

self.closeSec=1696233599, self.tradeDate='20231002', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28351.9', self.close='28299.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20334 

self.closeSec=1696234199, self.tradeDate='20231002', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28299.2', self.close='28289'
127.0.0.1 - - [02/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20335 

self.closeSec=1696234799, self.tradeDate='20231002', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28295', self.close='28363.6'
127.0.0.1 - - [02/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40660
self.closeSec=1696234799, self.tradeDate='20231002', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28324.1, self.close=28363.6, self.high=28385.0, self.low=28311.1, self.vol=2337.75, self.amt=66291672.9344 
127.0.0.1 - - [02/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-02 16:20:06,200:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231002   155500    155959  ...         0.0        0.0       0
5952  20231002   160000    160459  ...         0.0        0.0       0
5953  20231002   160500    160959  ...         0.0        0.0       0
5954  20231002   161000    161459  ...         0.0        0.0       0
5955  20231002   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 16:20:06,206:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696234799, self.tradeDate='20231002', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28324.1, self.close=28363.6, self.high=28385.0, self.low=28311.1, self.vol=2337.75, self.amt=66291672.9344, ukdf['pct'].iloc[-1]=0.001366 , ukdf['amount'].iloc[-1]=66291672.9344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '56651.1673', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28369.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40661
self.closeSec=1696235099, self.tradeDate='20231002', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28359.0, self.close=28363.4, self.high=28409.1, self.low=28354.5, self.vol=3140.745, self.amt=89135017.5995 
127.0.0.1 - - [02/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-10-02 16:25:00,833:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231002   160000    160459  ...         0.0        0.0       0
5953  20231002   160500    160959  ...         0.0        0.0       0
5954  20231002   161000    161459  ...         0.0        0.0       0
5955  20231002   161500    161959  ...         0.0        0.0       0
5956  20231002   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 16:25:00,834:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696235099, self.tradeDate='20231002', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28359.0, self.close=28363.4, self.high=28409.1, self.low=28354.5, self.vol=3140.745, self.amt=89135017.5995, ukdf['pct'].iloc[-1]=-7e-06 , ukdf['amount'].iloc[-1]=89135017.5995, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '56439.59883706638', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28363.60364118', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231002   040000    075959  1696204799  ...    721  0.458085 -0.444898     NaN
722  20231002   080000    115959  1696219199  ...    722  0.607722 -0.090302     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.874', 'enterprice': '27094.9', 'countrevence': '0', 'unrealprofit': '-48083.3492', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28120.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1268776.2962574002, self.flagDict['side']='sell', self.tradeCount=28, self.count=847
self.closeSec=1696233599, self.tradeDate='20231002', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28114.9, self.close=28300.0, self.high=28428.2, self.low=27880.0, self.vol=82485.833, self.amt=2322852159.12965 
127.0.0.1 - - [02/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-02 16:00:01,588:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696233599, self.tradeDate='20231002', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28114.9, self.close=28300.0, self.high=28428.2, self.low=27880.0, self.vol=82485.833, self.amt=2322852159.12965 
2023-10-02 16:00:01,605:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231001   200000    235959  ...   29635.945  8.042991e+08 -0.001413
720  20231002   000000    035959  ...   18484.542  5.006412e+08 -0.001651
721  20231002   040000    075959  ...  122070.984  3.388269e+09  0.032867
722  20231002   080000    115959  ...   63778.333  1.784399e+09  0.004953
723  20231002   120000    155959  ...   82485.833  2.322852e+09  0.006401

[5 rows x 11 columns]
2023-10-02 16:00:02,464:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231001   200000    235959  1696175999  ...    719  0.361394 -0.670357    -1.0
720  20231002   000000    035959  1696190399  ...    720  0.578343 -0.157510     NaN
721  20231002   040000    075959  1696204799  ...    721  0.458085 -0.444898     NaN
722  20231002   080000    115959  1696219199  ...    722  0.607722 -0.090302     NaN
723  20231002   120000    155959  1696233599  ...    723  0.815649  0.396154     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.874', 'enterprice': '27094.9', 'countrevence': '0', 'unrealprofit': '-56450.3582', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28299.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


