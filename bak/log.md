# 20230827 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30292
self.closeSec=1693124399, self.tradeDate='20230827', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26038.5, self.close=26031.5, self.high=26038.5, self.low=26031.4, self.vol=127.935, self.amt=3330738.4904 
127.0.0.1 - - [27/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-27 16:20:05,013:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230827   155500    155959  ...         0.0        0.0       0
5940  20230827   160000    160459  ...         0.0        0.0       0
5941  20230827   160500    160959  ...         0.0        0.0       0
5942  20230827   161000    161459  ...         0.0        0.0       0
5943  20230827   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 16:20:05,024:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693124399, self.tradeDate='20230827', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26038.5, self.close=26031.5, self.high=26038.5, self.low=26031.4, self.vol=127.935, self.amt=3330738.4904, ukdf['pct'].iloc[-1]=-0.000269 , ukdf['amount'].iloc[-1]=3330738.4904, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11605.9284', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26031.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30293
self.closeSec=1693124699, self.tradeDate='20230827', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26031.5, self.close=26020.2, self.high=26033.1, self.low=26020.2, self.vol=473.098, self.amt=12313520.613 
2023-08-27 16:25:00,780:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230827   160000    160459  ...         0.0        0.0       0
5941  20230827   160500    160959  ...         0.0        0.0       0
5942  20230827   161000    161459  ...         0.0        0.0       0
5943  20230827   161500    161959  ...         0.0        0.0       0
5944  20230827   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 16:25:00,780:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693124699, self.tradeDate='20230827', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26031.5, self.close=26020.2, self.high=26033.1, self.low=26020.2, self.vol=473.098, self.amt=12313520.613, ukdf['pct'].iloc[-1]=-0.000434 , ukdf['amount'].iloc[-1]=12313520.613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11761.8996', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26020.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [27/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30290 

self.closeSec=1693123199, self.tradeDate='20230827', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26029.8, self.close=26028.4, self.high=26029.8, self.low=26028.4 
127.0.0.1 - - [27/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30291 

self.closeSec=1693123499, self.tradeDate='20230827', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26028.5, self.close=26034.1, self.high=26034.1, self.low=26028.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30292 

self.closeSec=1693123799, self.tradeDate='20230827', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26034.1, self.close=26040.1, self.high=26040.1, self.low=26034.0 
127.0.0.1 - - [27/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30293 

self.closeSec=1693124099, self.tradeDate='20230827', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26040.1, self.close=26038.5, self.high=26041.4, self.low=26038.4 
127.0.0.1 - - [27/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30294 

self.closeSec=1693124399, self.tradeDate='20230827', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26038.5, self.close=26031.5, self.high=26038.5, self.low=26031.4 
127.0.0.1 - - [27/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30295 

self.closeSec=1693124699, self.tradeDate='20230827', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26031.5, self.close=26020.2, self.high=26033.1, self.low=26020.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-27 16:00:20,554:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230827    132959  26026.4  ...  50.416667  0.488809  0.587808
5786  20230827    135959  26020.8  ...  50.416667  0.490103  0.575718
5787  20230827    142959  26023.5  ...  50.416667  0.490590  0.563852
5788  20230827    145959  26024.5  ...  50.416667  0.496725  0.545493
5789  20230827    152959  26037.0  ...  50.000000  0.496286  0.528882

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-08-27 16:00:20,633:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.491831  0.508169       1  ...  1.064656  -1.0    0.0  0.891143
538     1  0.493443  0.506557       1  ...  1.064615  -1.0    0.0  0.891177
539     1  0.491387  0.508613       1  ...  1.064104  -1.0    0.0  0.891605
540     1  0.497355  0.502645       0  ...  1.064140  -1.0    0.0  0.891574
541     1  0.491259  0.508741       0  ...  1.064451  -1.0    0.0  0.891314

[5 rows x 10 columns]
2023-08-27 16:00:20,647:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491759  0.508241       1  ...  1.064656  -1.0    0.0  0.890770
46     1  0.493426  0.506574       1  ...  1.064615  -1.0    0.0  0.892136
47     1  0.491305  0.508695       1  ...  1.064104  -1.0    0.0  0.892249
48     1  0.497246  0.502754       0  ...  1.064140  -1.0    0.0  0.891986
49     1  0.491259  0.508741       0  ...  1.064451  -1.0    0.0  0.891314

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '10541.10677453407', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26028.61234903', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15143 

self.closeSec=1693121399, self.tradeDate='20230827', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26036.6', self.close='26036.1'
127.0.0.1 - - [27/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15144 

self.closeSec=1693121999, self.tradeDate='20230827', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26036', self.close='26033.5'
127.0.0.1 - - [27/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [27/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15145 

self.closeSec=1693122599, self.tradeDate='20230827', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26033.5', self.close='26035.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15146 

self.closeSec=1693123199, self.tradeDate='20230827', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26035.5', self.close='26028.5'
127.0.0.1 - - [27/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15147 

self.closeSec=1693123799, self.tradeDate='20230827', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26028.5', self.close='26040.1'
127.0.0.1 - - [27/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15148 

self.closeSec=1693124399, self.tradeDate='20230827', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26040.1', self.close='26031.5'
127.0.0.1 - - [27/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [27/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15146 

self.closeSec=1693121399, self.tradeDate='20230827', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26036.6', self.close='26036.1'
127.0.0.1 - - [27/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15147 

self.closeSec=1693121999, self.tradeDate='20230827', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26036', self.close='26033.5'
127.0.0.1 - - [27/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15148 

self.closeSec=1693122599, self.tradeDate='20230827', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26033.5', self.close='26035.6'
127.0.0.1 - - [27/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15149 

self.closeSec=1693123199, self.tradeDate='20230827', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26035.5', self.close='26028.5'
127.0.0.1 - - [27/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15150 

self.closeSec=1693123799, self.tradeDate='20230827', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26028.5', self.close='26040.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15151 

self.closeSec=1693124399, self.tradeDate='20230827', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26040.1', self.close='26031.5'
127.0.0.1 - - [27/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15146 

self.closeSec=1693121399, self.tradeDate='20230827', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26036.6', self.close='26036.1'
127.0.0.1 - - [27/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15147 127.0.0.1 - - [27/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -


self.closeSec=1693121999, self.tradeDate='20230827', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26036', self.close='26033.5'
127.0.0.1 - - [27/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15148 

self.closeSec=1693122599, self.tradeDate='20230827', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26033.5', self.close='26035.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15149 

self.closeSec=1693123199, self.tradeDate='20230827', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26035.5', self.close='26028.5'
127.0.0.1 - - [27/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15150 

self.closeSec=1693123799, self.tradeDate='20230827', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26028.5', self.close='26040.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15151 

self.closeSec=1693124399, self.tradeDate='20230827', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26040.1', self.close='26031.5'
127.0.0.1 - - [27/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30292
self.closeSec=1693124399, self.tradeDate='20230827', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26038.5, self.close=26031.5, self.high=26038.5, self.low=26031.4, self.vol=127.935, self.amt=3330738.4904 
127.0.0.1 - - [27/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-27 16:20:05,013:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230827   155500    155959  ...         0.0        0.0       0
5940  20230827   160000    160459  ...         0.0        0.0       0
5941  20230827   160500    160959  ...         0.0        0.0       0
5942  20230827   161000    161459  ...         0.0        0.0       0
5943  20230827   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 16:20:05,022:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693124399, self.tradeDate='20230827', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26038.5, self.close=26031.5, self.high=26038.5, self.low=26031.4, self.vol=127.935, self.amt=3330738.4904, ukdf['pct'].iloc[-1]=-0.000269 , ukdf['amount'].iloc[-1]=3330738.4904, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-30177.0625', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26031.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [27/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30293
self.closeSec=1693124699, self.tradeDate='20230827', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26031.5, self.close=26020.2, self.high=26033.1, self.low=26020.2, self.vol=473.098, self.amt=12313520.613 
2023-08-27 16:25:00,791:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230827   160000    160459  ...         0.0        0.0       0
5941  20230827   160500    160959  ...         0.0        0.0       0
5942  20230827   161000    161459  ...         0.0        0.0       0
5943  20230827   161500    161959  ...         0.0        0.0       0
5944  20230827   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 16:25:00,791:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693124699, self.tradeDate='20230827', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26031.5, self.close=26020.2, self.high=26033.1, self.low=26020.2, self.vol=473.098, self.amt=12313520.613, ukdf['pct'].iloc[-1]=-0.000434 , ukdf['amount'].iloc[-1]=12313520.613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-30593.0417', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26020.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230827   040000    075959  1693094399  ...    721  0.130818 -0.490147     NaN
722  20230827   080000    115959  1693108799  ...    722  0.354509  0.169445     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '175901.124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26009.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [27/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=631
self.closeSec=1693123199, self.tradeDate='20230827', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26009.7, self.close=26028.5, self.high=26041.9, self.low=26009.6, self.vol=7936.958, self.amt=206576474.7149 
2023-08-27 16:00:01,603:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693123199, self.tradeDate='20230827', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26009.7, self.close=26028.5, self.high=26041.9, self.low=26009.6, self.vol=7936.958, self.amt=206576474.7149 
2023-08-27 16:00:01,617:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230826   200000    235959  ...  12983.287  3.379272e+08  0.000161
720  20230827   000000    035959  ...   8874.796  2.308703e+08 -0.000657
721  20230827   040000    075959  ...   7354.576  1.913056e+08 -0.000722
722  20230827   080000    115959  ...   9486.116  2.465406e+08  0.000208
723  20230827   120000    155959  ...   7936.958  2.065765e+08  0.000727

[5 rows x 11 columns]
2023-08-27 16:00:02,246:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230826   200000    235959  1693065599  ...    719  0.155291 -0.455290     NaN
720  20230827   000000    035959  1693079999  ...    720  0.143820 -0.471517     NaN
721  20230827   040000    075959  1693094399  ...    721  0.130818 -0.490147     NaN
722  20230827   080000    115959  1693108799  ...    722  0.354509  0.169445     NaN
723  20230827   120000    155959  1693123199  ...    723  0.341607  0.162127     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174924.14310204636', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26028.61184903', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


