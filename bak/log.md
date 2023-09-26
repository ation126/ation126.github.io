# 20230926 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38932
self.closeSec=1695716399, self.tradeDate='20230926', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26261.3, self.close=26251.0, self.high=26261.4, self.low=26250.7, self.vol=215.557, self.amt=5659584.1638 
127.0.0.1 - - [26/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-26 16:20:05,855:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230926   155500    155959  ...         0.0        0.0       0
5952  20230926   160000    160459  ...         0.0        0.0       0
5953  20230926   160500    160959  ...         0.0        0.0       0
5954  20230926   161000    161459  ...         0.0        0.0       0
5955  20230926   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 16:20:05,858:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695716399, self.tradeDate='20230926', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26261.3, self.close=26251.0, self.high=26261.4, self.low=26250.7, self.vol=215.557, self.amt=5659584.1638, ukdf['pct'].iloc[-1]=-0.000396 , ukdf['amount'].iloc[-1]=5659584.1638, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8549.1714', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26251', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38933
self.closeSec=1695716699, self.tradeDate='20230926', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26251.0, self.close=26254.9, self.high=26264.5, self.low=26250.7, self.vol=237.767, self.amt=6242809.9957 
2023-09-26 16:25:00,780:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230926   160000    160459  ...         0.0        0.0       0
5953  20230926   160500    160959  ...         0.0        0.0       0
5954  20230926   161000    161459  ...         0.0        0.0       0
5955  20230926   161500    161959  ...         0.0        0.0       0
5956  20230926   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 16:25:00,780:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695716699, self.tradeDate='20230926', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26251.0, self.close=26254.9, self.high=26264.5, self.low=26250.7, self.vol=237.767, self.amt=6242809.9957, ukdf['pct'].iloc[-1]=0.000149 , ukdf['amount'].iloc[-1]=6242809.9957, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8435.68272149262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26259.14940963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [26/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38930 

self.closeSec=1695715199, self.tradeDate='20230926', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26271.1, self.close=26256.3, self.high=26271.1, self.low=26254.8 
127.0.0.1 - - [26/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38931 

self.closeSec=1695715499, self.tradeDate='20230926', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26256.3, self.close=26269.7, self.high=26271.7, self.low=26252.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38932 

self.closeSec=1695715799, self.tradeDate='20230926', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26269.7, self.close=26253.4, self.high=26273.4, self.low=26252.7 
127.0.0.1 - - [26/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38933 

self.closeSec=1695716099, self.tradeDate='20230926', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26253.3, self.close=26261.4, self.high=26267.3, self.low=26252.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38934 

self.closeSec=1695716399, self.tradeDate='20230926', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26261.3, self.close=26251.0, self.high=26261.4, self.low=26250.7 
127.0.0.1 - - [26/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38935 

self.closeSec=1695716699, self.tradeDate='20230926', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26251.0, self.close=26254.9, self.high=26264.5, self.low=26250.7 
127.0.0.1 - - [26/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-26 16:00:19,766:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230926    132959  26331.2  ...  46.666667  0.496118  0.365295
5786  20230926    135959  26321.8  ...  46.250000  0.491536  0.359934
5787  20230926    142959  26308.1  ...  46.250000  0.481657  0.359193
5788  20230926    145959  26278.6  ...  46.250000  0.482123  0.358314
5789  20230926    152959  26279.7  ...  46.250000  0.477769  0.359350

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-09-26 16:00:19,834:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.488944  0.511056       0  ...  0.976012  -1.0    0.0  0.994143
538     1  0.486093  0.513907       0  ...  0.977111  -1.0    0.0  0.993024
539     1  0.482639  0.517361       1  ...  0.977062  -1.0    0.0  0.993073
540     1  0.490914  0.509086       0  ...  0.977542  -1.0    0.0  0.992586
541     1  0.486652  0.513348       0  ...  0.977936  -1.0    0.0  0.992185

[5 rows x 10 columns]
2023-09-26 16:00:19,847:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488052  0.511948       0  ...  0.976012  -1.0    0.0  0.989476
46     1  0.485423  0.514577       0  ...  0.977111  -1.0    0.0  0.989029
47     1  0.482219  0.517781       1  ...  0.977062  -1.0    0.0  0.991305
48     1  0.490700  0.509300       0  ...  0.977542  -1.0    0.0  0.991350
49     1  0.486652  0.513348       0  ...  0.977936  -1.0    0.0  0.992185

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '22381.673', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26259.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19463 

self.closeSec=1695713399, self.tradeDate='20230926', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26276.7', self.close='26266.9'
127.0.0.1 - - [26/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19464 

self.closeSec=1695713999, self.tradeDate='20230926', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26266.8', self.close='26250.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19465127.0.0.1 - - [26/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
 

self.closeSec=1695714599, self.tradeDate='20230926', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26250.3', self.close='26241.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19466 

self.closeSec=1695715199, self.tradeDate='20230926', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26241.6', self.close='26256.3'
127.0.0.1 - - [26/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19467 

self.closeSec=1695715799, self.tradeDate='20230926', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26256.3', self.close='26253.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19468 

self.closeSec=1695716399, self.tradeDate='20230926', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26253.3', self.close='26251'
127.0.0.1 - - [26/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [26/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19466 

self.closeSec=1695713399, self.tradeDate='20230926', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26276.7', self.close='26266.9'

--handleKline--: 127.0.0.1 - - [26/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19467 

self.closeSec=1695713999, self.tradeDate='20230926', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26266.8', self.close='26250.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19468 

self.closeSec=1695714599, self.tradeDate='20230926', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26250.3', self.close='26241.6'
127.0.0.1 - - [26/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19469 

self.closeSec=1695715199, self.tradeDate='20230926', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26241.6', self.close='26256.3'
127.0.0.1 - - [26/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19470 

self.closeSec=1695715799, self.tradeDate='20230926', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26256.3', self.close='26253.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19471 

self.closeSec=1695716399, self.tradeDate='20230926', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26253.3', self.close='26251'
127.0.0.1 - - [26/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19466 

self.closeSec=1695713399, self.tradeDate='20230926', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26276.7', self.close='26266.9'
127.0.0.1 - - [26/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19467 

self.closeSec=1695713999, self.tradeDate='20230926', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26266.8', self.close='26250.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19468 

self.closeSec=1695714599, self.tradeDate='20230926', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26250.3', self.close='26241.6'
127.0.0.1 - - [26/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19469 

self.closeSec=1695715199, self.tradeDate='20230926', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26241.6', self.close='26256.3'
127.0.0.1 - - [26/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19470 

self.closeSec=1695715799, self.tradeDate='20230926', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26256.3', self.close='26253.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19471 

self.closeSec=1695716399, self.tradeDate='20230926', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26253.3', self.close='26251'
127.0.0.1 - - [26/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38932
self.closeSec=1695716399, self.tradeDate='20230926', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26261.3, self.close=26251.0, self.high=26261.4, self.low=26250.7, self.vol=215.557, self.amt=5659584.1638 
127.0.0.1 - - [26/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-26 16:20:05,859:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230926   155500    155959  ...         0.0        0.0       0
5952  20230926   160000    160459  ...         0.0        0.0       0
5953  20230926   160500    160959  ...         0.0        0.0       0
5954  20230926   161000    161459  ...         0.0        0.0       0
5955  20230926   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 16:20:05,868:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695716399, self.tradeDate='20230926', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26261.3, self.close=26251.0, self.high=26261.4, self.low=26250.7, self.vol=215.557, self.amt=5659584.1638, ukdf['pct'].iloc[-1]=-0.000396 , ukdf['amount'].iloc[-1]=5659584.1638, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-22024.613', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26251', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38933
self.closeSec=1695716699, self.tradeDate='20230926', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26251.0, self.close=26254.9, self.high=26264.5, self.low=26250.7, self.vol=237.767, self.amt=6242809.9957 
2023-09-26 16:25:00,793:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230926   160000    160459  ...         0.0        0.0       0
5953  20230926   160500    160959  ...         0.0        0.0       0
5954  20230926   161000    161459  ...         0.0        0.0       0
5955  20230926   161500    161959  ...         0.0        0.0       0
5956  20230926   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 16:25:00,793:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695716699, self.tradeDate='20230926', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26251.0, self.close=26254.9, self.high=26264.5, self.low=26250.7, self.vol=237.767, self.amt=6242809.9957, ukdf['pct'].iloc[-1]=0.000149 , ukdf['amount'].iloc[-1]=6242809.9957, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-21721.93577693217', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26259.14940963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230926   040000    075959  1695686399  ...    721  0.255654 -0.872703    -1.0
722  20230926   080000    115959  1695700799  ...    722  0.263544 -0.851426    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-9672.80406311796', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26339.47459341', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=811
self.closeSec=1695715199, self.tradeDate='20230926', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26338.8, self.close=26256.3, self.high=26353.3, self.low=26241.4, self.vol=15913.957, self.amt=418439246.216 
127.0.0.1 - - [26/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-26 16:00:01,516:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695715199, self.tradeDate='20230926', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26338.8, self.close=26256.3, self.high=26353.3, self.low=26241.4, self.vol=15913.957, self.amt=418439246.216 
2023-09-26 16:00:01,534:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230925   200000    235959  ...  58168.921  1.520600e+09  0.006338
720  20230926   000000    035959  ...  53444.241  1.406415e+09  0.003225
721  20230926   040000    075959  ...  23377.527  6.153584e+08 -0.000908
722  20230926   080000    115959  ...  20252.450  5.326637e+08  0.001841
723  20230926   120000    155959  ...  15913.957  4.184392e+08 -0.003132

[5 rows x 11 columns]
2023-09-26 16:00:02,261:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230925   200000    235959  1695657599  ...    719  0.217799 -0.959629    -1.0
720  20230926   000000    035959  1695671999  ...    720  0.257942 -0.870637    -1.0
721  20230926   040000    075959  1695686399  ...    721  0.255654 -0.872703    -1.0
722  20230926   080000    115959  1695700799  ...    722  0.263544 -0.851426    -1.0
723  20230926   120000    155959  1695715199  ...    723  0.269543 -0.835454    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-5515.42305030736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26257.56543956', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


