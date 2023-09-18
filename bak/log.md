# 20230918 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36628
self.closeSec=1695025199, self.tradeDate='20230918', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26706.2, self.close=26695.1, self.high=26707.6, self.low=26686.8, self.vol=246.401, self.amt=6578470.2906 
127.0.0.1 - - [18/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-18 16:20:06,118:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230918   155500    155959  ...         0.0        0.0       0
5952  20230918   160000    160459  ...         0.0        0.0       0
5953  20230918   160500    160959  ...         0.0        0.0       0
5954  20230918   161000    161459  ...         0.0        0.0       0
5955  20230918   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 16:20:06,120:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695025199, self.tradeDate='20230918', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26706.2, self.close=26695.1, self.high=26707.6, self.low=26686.8, self.vol=246.401, self.amt=6578470.2906, ukdf['pct'].iloc[-1]=-0.000416 , ukdf['amount'].iloc[-1]=6578470.2906, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2310.3234', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26699', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36629
self.closeSec=1695025499, self.tradeDate='20230918', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26695.2, self.close=26676.5, self.high=26700.0, self.low=26676.5, self.vol=271.243, self.amt=7238106.125 
127.0.0.1 - - [18/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-18 16:25:00,772:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230918   160000    160459  ...         0.0        0.0       0
5953  20230918   160500    160959  ...         0.0        0.0       0
5954  20230918   161000    161459  ...         0.0        0.0       0
5955  20230918   161500    161959  ...         0.0        0.0       0
5956  20230918   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 16:25:00,772:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695025499, self.tradeDate='20230918', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26695.2, self.close=26676.5, self.high=26700.0, self.low=26676.5, self.vol=271.243, self.amt=7238106.125, ukdf['pct'].iloc[-1]=-0.000697 , ukdf['amount'].iloc[-1]=7238106.125, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2596.36450492122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26678.45992353', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  127.0.0.1 - - [18/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -
version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36626 

self.closeSec=1695023999, self.tradeDate='20230918', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26673.5, self.close=26701.7, self.high=26702.2, self.low=26673.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36627 

self.closeSec=1695024299, self.tradeDate='20230918', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26701.8, self.close=26722.2, self.high=26722.3, self.low=26700.4 
127.0.0.1 - - [18/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36628 

self.closeSec=1695024599, self.tradeDate='20230918', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26722.2, self.close=26681.2, self.high=26722.3, self.low=26679.0 
127.0.0.1 - - [18/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36629 

self.closeSec=1695024899, self.tradeDate='20230918', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26681.1, self.close=26706.2, self.high=26712.0, self.low=26678.5 
127.0.0.1 - - [18/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36630 

self.closeSec=1695025199, self.tradeDate='20230918', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26706.2, self.close=26695.1, self.high=26707.6, self.low=26686.8 
127.0.0.1 - - [18/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36631 

self.closeSec=1695025499, self.tradeDate='20230918', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26695.2, self.close=26676.5, self.high=26700.0, self.low=26676.5 
127.0.0.1 - - [18/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-18 16:00:18,866:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230918    132959  26613.5  ...  53.333333  0.544782  0.448014
5786  20230918    135959  26633.4  ...  53.333333  0.545293  0.436588
5787  20230918    142959  26635.0  ...  53.333333  0.555711  0.420568
5788  20230918    145959  26665.6  ...  52.916667  0.533567  0.415124
5789  20230918    152959  26611.2  ...  52.916667  0.572070  0.389002

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-09-18 16:00:18,937:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502127  0.497873       1  ...  0.934692   1.0    0.0  1.034602
538     1  0.498169  0.501831       1  ...  0.935769   1.0    0.0  1.035794
539     0  0.507250  0.492750       0  ...  0.933856   1.0    0.0  1.033677
540     1  0.486889  0.513111       1  ...  0.938089   1.0    0.0  1.038362
541     0  0.533408  0.466592       0  ...  0.937032   1.0    0.0  1.037193

[5 rows x 10 columns]
2023-09-18 16:00:18,950:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502119  0.497881       1  ...  0.934692   1.0    0.0  1.035012
46     1  0.497919  0.502081       1  ...  0.935769   1.0    0.0  1.034802
47     0  0.507234  0.492766       0  ...  0.933856   1.0    0.0  1.033549
48     1  0.487166  0.512834       1  ...  0.938089   1.0    0.0  1.038665
49     0  0.533408  0.466592       0  ...  0.937032   1.0    0.0  1.037193

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '3067.983', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26706.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18311 

self.closeSec=1695022199, self.tradeDate='20230918', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26673.9', self.close='26731.9'
127.0.0.1 - - [18/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18312 

self.closeSec=1695022799, self.tradeDate='20230918', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26732', self.close='26679.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18313 

self.closeSec=1695023399, self.tradeDate='20230918', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26679.4', self.close='26686.1'
127.0.0.1 - - [18/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18314 

self.closeSec=1695023999, self.tradeDate='20230918', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26686.2', self.close='26701.7'
127.0.0.1 - - [18/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18315 

self.closeSec=1695024599, self.tradeDate='20230918', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26701.8', self.close='26681.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18316 

self.closeSec=1695025199, self.tradeDate='20230918', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26681.1', self.close='26695.1'
127.0.0.1 - - [18/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18314 

self.closeSec=1695022199, self.tradeDate='20230918', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26673.9', self.close='26731.9'
127.0.0.1 - - [18/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18315 

self.closeSec=1695022799, self.tradeDate='20230918', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26732', self.close='26679.1'
127.0.0.1 - - [18/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [18/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18316 

self.closeSec=1695023399, self.tradeDate='20230918', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26679.4', self.close='26686.1'
127.0.0.1 - - [18/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18317 

self.closeSec=1695023999, self.tradeDate='20230918', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26686.2', self.close='26701.7'
127.0.0.1 - - [18/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18318 

self.closeSec=1695024599, self.tradeDate='20230918', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26701.8', self.close='26681.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18319 

self.closeSec=1695025199, self.tradeDate='20230918', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26681.1', self.close='26695.1'
127.0.0.1 - - [18/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18314 

self.closeSec=1695022199, self.tradeDate='20230918', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26673.9', self.close='26731.9'
127.0.0.1 - - [18/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18315 

self.closeSec=1695022799, self.tradeDate='20230918', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26732', self.close='26679.1'
127.0.0.1 - - [18/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18316 

self.closeSec=1695023399, self.tradeDate='20230918', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26679.4', self.close='26686.1'
127.0.0.1 - - [18/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18317 

self.closeSec=1695023999, self.tradeDate='20230918', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26686.2', self.close='26701.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18318 

self.closeSec=1695024599, self.tradeDate='20230918', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26701.8', self.close='26681.2'
127.0.0.1 - - [18/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18319 

self.closeSec=1695025199, self.tradeDate='20230918', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26681.1', self.close='26695.1'
127.0.0.1 - - [18/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36628
self.closeSec=1695025199, self.tradeDate='20230918', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26706.2, self.close=26695.1, self.high=26707.6, self.low=26686.8, self.vol=246.401, self.amt=6578470.2906 
127.0.0.1 - - [18/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-18 16:20:06,119:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230918   155500    155959  ...         0.0        0.0       0
5952  20230918   160000    160459  ...         0.0        0.0       0
5953  20230918   160500    160959  ...         0.0        0.0       0
5954  20230918   161000    161459  ...         0.0        0.0       0
5955  20230918   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 16:20:06,121:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695025199, self.tradeDate='20230918', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26706.2, self.close=26695.1, self.high=26707.6, self.low=26686.8, self.vol=246.401, self.amt=6578470.2906, ukdf['pct'].iloc[-1]=-0.000416 , ukdf['amount'].iloc[-1]=6578470.2906, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-5385.445', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26699', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36629
self.closeSec=1695025499, self.tradeDate='20230918', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26695.2, self.close=26676.5, self.high=26700.0, self.low=26676.5, self.vol=271.243, self.amt=7238106.125 
127.0.0.1 - - [18/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-18 16:25:00,769:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230918   160000    160459  ...         0.0        0.0       0
5953  20230918   160500    160959  ...         0.0        0.0       0
5954  20230918   161000    161459  ...         0.0        0.0       0
5955  20230918   161500    161959  ...         0.0        0.0       0
5956  20230918   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 16:25:00,769:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695025499, self.tradeDate='20230918', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26695.2, self.close=26676.5, self.high=26700.0, self.low=26676.5, self.vol=271.243, self.amt=7238106.125, ukdf['pct'].iloc[-1]=-0.000697 , ukdf['amount'].iloc[-1]=7238106.125, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-6148.32398017227', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26678.45992353', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230918   040000    075959  1694995199  ...    721  0.105896 -0.793562    -1.0
722  20230918   080000    115959  1695009599  ...    722  0.036809 -1.075083    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.675', 'enterprice': '26538.7', 'countrevence': '0', 'unrealprofit': '-6038.4375', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26651.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1423040.2577775, self.flagDict['side']='sell', self.tradeCount=24, self.count=763
self.closeSec=1695023999, self.tradeDate='20230918', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26646.2, self.close=26701.7, self.high=26796.0, self.low=26550.1, self.vol=34889.774, self.amt=930333418.87452 
127.0.0.1 - - [18/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-18 16:00:01,521:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695023999, self.tradeDate='20230918', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26646.2, self.close=26701.7, self.high=26796.0, self.low=26550.1, self.vol=34889.774, self.amt=930333418.87452 
2023-09-18 16:00:01,535:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230917   200000    235959  ...  15182.625  4.030439e+08 -0.000636
720  20230918   000000    035959  ...  18907.419  5.009485e+08 -0.001726
721  20230918   040000    075959  ...  24458.481  6.470407e+08  0.000868
722  20230918   080000    115959  ...  59009.210  1.567701e+09  0.004982
723  20230918   120000    155959  ...  34889.774  9.303334e+08  0.002079

[5 rows x 11 columns]
2023-09-18 16:00:02,269:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230917   200000    235959  1694966399  ...    719  0.153439 -0.627340    -1.0
720  20230918   000000    035959  1694980799  ...    720  0.123332 -0.735192    -1.0
721  20230918   040000    075959  1694995199  ...    721  0.105896 -0.793562    -1.0
722  20230918   080000    115959  1695009599  ...    722  0.036809 -1.075083    -1.0
723  20230918   120000    155959  1695023999  ...    723  0.067519 -0.927845    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.675', 'enterprice': '26538.7', 'countrevence': '0', 'unrealprofit': '-8754.3925', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26701.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


