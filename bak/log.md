# 20230916 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36052
self.closeSec=1694852399, self.tradeDate='20230916', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26462.6, self.close=26477.4, self.high=26477.4, self.low=26461.3, self.vol=1018.947, self.amt=26966646.1903 
127.0.0.1 - - [16/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-16 16:20:06,234:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230916   155500    155959  ...         0.0        0.0       0
5952  20230916   160000    160459  ...         0.0        0.0       0
5953  20230916   160500    160959  ...         0.0        0.0       0
5954  20230916   161000    161459  ...         0.0        0.0       0
5955  20230916   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 16:20:06,237:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694852399, self.tradeDate='20230916', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26462.6, self.close=26477.4, self.high=26477.4, self.low=26461.3, self.vol=1018.947, self.amt=26966646.1903, ukdf['pct'].iloc[-1]=0.000559 , ukdf['amount'].iloc[-1]=26966646.1903, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5397.7176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26477.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36053
self.closeSec=1694852699, self.tradeDate='20230916', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26477.4, self.close=26472.0, self.high=26478.4, self.low=26465.0, self.vol=475.306, self.amt=12582294.8388 
127.0.0.1 - - [16/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-16 16:25:00,799:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230916   160000    160459  ...         0.0        0.0       0
5953  20230916   160500    160959  ...         0.0        0.0       0
5954  20230916   161000    161459  ...         0.0        0.0       0
5955  20230916   161500    161959  ...         0.0        0.0       0
5956  20230916   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 16:25:00,799:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694852699, self.tradeDate='20230916', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26477.4, self.close=26472.0, self.high=26478.4, self.low=26465.0, self.vol=475.306, self.amt=12582294.8388, ukdf['pct'].iloc[-1]=-0.000204 , ukdf['amount'].iloc[-1]=12582294.8388, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5439.18539055144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26474.32227556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [16/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36050 

self.closeSec=1694851199, self.tradeDate='20230916', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26480.3, self.close=26486.0, self.high=26486.8, self.low=26480.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36051 

self.closeSec=1694851499, self.tradeDate='20230916', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26486.0, self.close=26475.8, self.high=26486.1, self.low=26470.2 
127.0.0.1 - - [16/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36052 

self.closeSec=1694851799, self.tradeDate='20230916', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26472.6, self.close=26474.9, self.high=26480.3, self.low=26471.6 
127.0.0.1 - - [16/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36053 

self.closeSec=1694852099, self.tradeDate='20230916', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26475.0, self.close=26462.6, self.high=26476.6, self.low=26461.2 
127.0.0.1 - - [16/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36054 

self.closeSec=1694852399, self.tradeDate='20230916', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26462.6, self.close=26477.4, self.high=26477.4, self.low=26461.3 
127.0.0.1 - - [16/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36055 

self.closeSec=1694852699, self.tradeDate='20230916', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26477.4, self.close=26472.0, self.high=26478.4, self.low=26465.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-16 16:00:17,276:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230916    132959  26540.6  ...  49.583333  0.521995  0.493898
5786  20230916    135959  26539.9  ...  49.166667  0.518054  0.496744
5787  20230916    142959  26523.2  ...  49.166667  0.504977  0.504843
5788  20230916    145959  26467.4  ...  49.583333  0.506821  0.511612
5789  20230916    152959  26475.6  ...  50.000000  0.511498  0.515940

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-09-16 16:00:17,334:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485748  0.514252       0  ...  0.943365   1.0    0.0  1.029739
538     1  0.479601  0.520399       0  ...  0.941380   1.0    0.0  1.027573
539     1  0.470566  0.529434       1  ...  0.941668   1.0    0.0  1.027887
540     1  0.489068  0.510932       1  ...  0.942394   1.0    0.0  1.028679
541     1  0.494824  0.505176       0  ...  0.942038   1.0    0.0  1.028291

[5 rows x 10 columns]
2023-09-16 16:00:17,345:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485614  0.514386       0  ...  0.943365   1.0    0.0  1.029487
46     1  0.479472  0.520528       0  ...  0.941380   1.0    0.0  1.027046
47     1  0.470186  0.529814       1  ...  0.941668   1.0    0.0  1.025626
48     1  0.488876  0.511124       1  ...  0.942394   1.0    0.0  1.028575
49     1  0.494824  0.505176       0  ...  0.942038   1.0    0.0  1.028291

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '-2874.8180002905', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26484.9902103', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18023 

self.closeSec=1694849399, self.tradeDate='20230916', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26480.4', self.close='26496'
127.0.0.1 - - [16/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18024 

self.closeSec=1694849999, self.tradeDate='20230916', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26496', self.close='26481'
127.0.0.1 - - [16/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18025 

self.closeSec=1694850599, self.tradeDate='20230916', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26481', self.close='26483.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18026 

self.closeSec=1694851199, self.tradeDate='20230916', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26483.6', self.close='26486'
127.0.0.1 - - [16/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18027 

self.closeSec=1694851799, self.tradeDate='20230916', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26486', self.close='26474.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18028 

self.closeSec=1694852399, self.tradeDate='20230916', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26475', self.close='26477.4'
127.0.0.1 - - [16/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18026 

self.closeSec=1694849399, self.tradeDate='20230916', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26480.4', self.close='26496'
127.0.0.1 - - [16/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18027 

self.closeSec=1694849999, self.tradeDate='20230916', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26496', self.close='26481'

--handleKline--: 127.0.0.1 - - [16/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18028 

self.closeSec=1694850599, self.tradeDate='20230916', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26481', self.close='26483.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18029 

self.closeSec=1694851199, self.tradeDate='20230916', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26483.6', self.close='26486'
127.0.0.1 - - [16/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18030 

self.closeSec=1694851799, self.tradeDate='20230916', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26486', self.close='26474.9'
127.0.0.1 - - [16/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18031 

self.closeSec=1694852399, self.tradeDate='20230916', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26475', self.close='26477.4'
127.0.0.1 - - [16/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18026 

self.closeSec=1694849399, self.tradeDate='20230916', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26480.4', self.close='26496'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18027 

self.closeSec=1694849999, self.tradeDate='20230916', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26496', self.close='26481'
127.0.0.1 - - [16/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18028 

self.closeSec=1694850599, self.tradeDate='20230916', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26481', self.close='26483.6'
127.0.0.1 - - [16/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18029 

self.closeSec=1694851199, self.tradeDate='20230916', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26483.6', self.close='26486'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18030 

self.closeSec=1694851799, self.tradeDate='20230916', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26486', self.close='26474.9'
127.0.0.1 - - [16/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18031 

self.closeSec=1694852399, self.tradeDate='20230916', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26475', self.close='26477.4'
127.0.0.1 - - [16/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36052
self.closeSec=1694852399, self.tradeDate='20230916', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26462.6, self.close=26477.4, self.high=26477.4, self.low=26461.3, self.vol=1018.947, self.amt=26966646.1903 
127.0.0.1 - - [16/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-16 16:20:06,240:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230916   155500    155959  ...         0.0        0.0       0
5952  20230916   160000    160459  ...         0.0        0.0       0
5953  20230916   160500    160959  ...         0.0        0.0       0
5954  20230916   161000    161459  ...         0.0        0.0       0
5955  20230916   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 16:20:06,242:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694852399, self.tradeDate='20230916', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26462.6, self.close=26477.4, self.high=26477.4, self.low=26461.3, self.vol=1018.947, self.amt=26966646.1903, ukdf['pct'].iloc[-1]=0.000559 , ukdf['amount'].iloc[-1]=26966646.1903, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-13593.606', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26478', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36053
self.closeSec=1694852699, self.tradeDate='20230916', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26477.4, self.close=26472.0, self.high=26478.4, self.low=26465.0, self.vol=475.306, self.amt=12582294.8388 
127.0.0.1 - - [16/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-16 16:25:00,803:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230916   160000    160459  ...         0.0        0.0       0
5953  20230916   160500    160959  ...         0.0        0.0       0
5954  20230916   161000    161459  ...         0.0        0.0       0
5955  20230916   161500    161959  ...         0.0        0.0       0
5956  20230916   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 16:25:00,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694852699, self.tradeDate='20230916', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26477.4, self.close=26472.0, self.high=26478.4, self.low=26465.0, self.vol=475.306, self.amt=12582294.8388, ukdf['pct'].iloc[-1]=-0.000204 , ukdf['amount'].iloc[-1]=12582294.8388, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-13730.20036342604', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26474.32227556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230916   040000    075959  1694822399  ...    721  0.530162  0.704080     1.0
722  20230916   080000    115959  1694836799  ...    722  0.353228  0.057789     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-3959.5325', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26604.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1431863.74296, self.flagDict['side']='buy', self.tradeCount=23, self.count=751
self.closeSec=1694851199, self.tradeDate='20230916', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26602.4, self.close=26486.0, self.high=26608.8, self.low=26453.3, self.vol=32167.402, self.amt=853190982.5033 
127.0.0.1 - - [16/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-16 16:00:01,558:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694851199, self.tradeDate='20230916', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26602.4, self.close=26486.0, self.high=26608.8, self.low=26453.3, self.vol=32167.402, self.amt=853190982.5033 
2023-09-16 16:00:01,570:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230915   200000    235959  ...  69223.358  1.824085e+09 -0.003911
720  20230916   000000    035959  ...  24017.548  6.329968e+08  0.002885
721  20230916   040000    075959  ...  66407.988  1.769890e+09  0.007724
722  20230916   080000    115959  ...  32987.327  8.790867e+08  0.000436
723  20230916   120000    155959  ...  32167.402  8.531910e+08 -0.004376

[5 rows x 11 columns]
2023-09-16 16:00:02,204:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230915   200000    235959  1694793599  ...    719  0.548969  0.756718     1.0
720  20230916   000000    035959  1694807999  ...    720  0.613952  1.005085     1.0
721  20230916   040000    075959  1694822399  ...    721  0.530162  0.704080     1.0
722  20230916   080000    115959  1694836799  ...    722  0.353228  0.057789     NaN
723  20230916   120000    155959  1694851199  ...    723  0.426659  0.347395     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-10336.69', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26486', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


