# 20230901 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31732
self.closeSec=1693556399, self.tradeDate='20230901', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25986.2, self.close=25970.1, self.high=25986.3, self.low=25970.0, self.vol=452.457, self.amt=11752588.0983 
127.0.0.1 - - [01/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-01 16:20:05,438:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230901   155500    155959  ...         0.0        0.0       0
5940  20230901   160000    160459  ...         0.0        0.0       0
5941  20230901   160500    160959  ...         0.0        0.0       0
5942  20230901   161000    161459  ...         0.0        0.0       0
5943  20230901   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 16:20:05,441:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693556399, self.tradeDate='20230901', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25986.2, self.close=25970.1, self.high=25986.3, self.low=25970.0, self.vol=452.457, self.amt=11752588.0983, ukdf['pct'].iloc[-1]=-0.00062 , ukdf['amount'].iloc[-1]=11752588.0983, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12460.9848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25970.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31733
self.closeSec=1693556699, self.tradeDate='20230901', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25970.1, self.close=25971.4, self.high=25983.9, self.low=25964.8, self.vol=621.05, self.amt=16129990.2158 
2023-09-01 16:25:00,841:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230901   160000    160459  ...         0.0        0.0       0
5941  20230901   160500    160959  ...         0.0        0.0       0
5942  20230901   161000    161459  ...         0.0        0.0       0
5943  20230901   161500    161959  ...         0.0        0.0       0
5944  20230901   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 16:25:00,841:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693556699, self.tradeDate='20230901', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25970.1, self.close=25971.4, self.high=25983.9, self.low=25964.8, self.vol=621.05, self.amt=16129990.2158, ukdf['pct'].iloc[-1]=5e-05 , ukdf['amount'].iloc[-1]=16129990.2158, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12442.80607268886', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25971.40538039', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [01/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31730 

self.closeSec=1693555199, self.tradeDate='20230901', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25979.7, self.close=25975.2, self.high=25979.7, self.low=25975.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31731 

self.closeSec=1693555499, self.tradeDate='20230901', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25975.3, self.close=25996.3, self.high=25999.3, self.low=25975.2 
127.0.0.1 - - [01/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31732 

self.closeSec=1693555799, self.tradeDate='20230901', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25996.2, self.close=25994.1, self.high=26006.0, self.low=25994.1 
127.0.0.1 - - [01/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31733 

self.closeSec=1693556099, self.tradeDate='20230901', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25994.2, self.close=25986.2, self.high=25994.2, self.low=25986.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31734 

self.closeSec=1693556399, self.tradeDate='20230901', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25986.2, self.close=25970.1, self.high=25986.3, self.low=25970.0 
127.0.0.1 - - [01/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31735 

self.closeSec=1693556699, self.tradeDate='20230901', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25970.1, self.close=25971.4, self.high=25983.9, self.low=25964.8 
127.0.0.1 - - [01/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-01 16:00:16,948:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230901    132959  26031.2  ...  46.250000  0.375809  0.787218
5786  20230901    135959  26030.5  ...  45.833333  0.373908  0.788459
5787  20230901    142959  26017.1  ...  45.416667  0.372174  0.790006
5788  20230901    145959  26005.2  ...  45.000000  0.369336  0.792083
5789  20230901    152959  25985.7  ...  45.000000  0.367648  0.794393

[5 rows x 33 columns]
0.525830258302583
acc is : 0.525830258302583
2023-09-01 16:00:17,009:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.497694  0.502306       0  ...  0.999475  -1.0    0.0  0.995801
538     1  0.494867  0.505133       0  ...  0.999936  -1.0    0.0  0.995342
539     1  0.492732  0.507268       0  ...  1.000686  -1.0    0.0  0.994596
540     1  0.489280  0.510720       0  ...  1.001129  -1.0    0.0  0.994155
541     1  0.489556  0.510444       1  ...  1.001086  -1.0    0.0  0.994198

[5 rows x 10 columns]
2023-09-01 16:00:17,021:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497669  0.502331       0  ...  0.999475  -1.0    0.0  0.993250
46     1  0.494918  0.505082       0  ...  0.999936  -1.0    0.0  0.993976
47     1  0.492786  0.507214       0  ...  1.000686  -1.0    0.0  0.992730
48     1  0.489491  0.510509       0  ...  1.001129  -1.0    0.0  0.994894
49     1  0.489556  0.510444       1  ...  1.001086  -1.0    0.0  0.994198

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '18344.7055', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25984.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [01/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15863 

self.closeSec=1693553399, self.tradeDate='20230901', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25991.2', self.close='25974.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15864 

self.closeSec=1693553999, self.tradeDate='20230901', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25974', self.close='25984.7'
127.0.0.1 - - [01/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15865 

self.closeSec=1693554599, self.tradeDate='20230901', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25984.7', self.close='25984.4'
127.0.0.1 - - [01/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15866 

self.closeSec=1693555199, self.tradeDate='20230901', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25984.5', self.close='25975.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15867 

self.closeSec=1693555799, self.tradeDate='20230901', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25975.3', self.close='25994.1'
127.0.0.1 - - [01/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15868 

self.closeSec=1693556399, self.tradeDate='20230901', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25994.2', self.close='25970.1'
127.0.0.1 - - [01/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [01/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15866 

self.closeSec=1693553399, self.tradeDate='20230901', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25991.2', self.close='25974.1'
127.0.0.1 - - [01/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15867 

self.closeSec=1693553999, self.tradeDate='20230901', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25974', self.close='25984.7'
127.0.0.1 - - [01/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15868 

self.closeSec=1693554599, self.tradeDate='20230901', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25984.7', self.close='25984.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15869 

self.closeSec=1693555199, self.tradeDate='20230901', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25984.5', self.close='25975.2'
127.0.0.1 - - [01/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15870 

self.closeSec=1693555799, self.tradeDate='20230901', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25975.3', self.close='25994.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15871 

self.closeSec=1693556399, self.tradeDate='20230901', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25994.2', self.close='25970.1'
127.0.0.1 - - [01/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15866 

self.closeSec=1693553399, self.tradeDate='20230901', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25991.2', self.close='25974.1'
127.0.0.1 - - [01/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15867 

self.closeSec=1693553999, self.tradeDate='20230901', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25974', self.close='25984.7'
127.0.0.1 - - [01/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15868 

self.closeSec=1693554599, self.tradeDate='20230901', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25984.7', self.close='25984.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15869 

self.closeSec=1693555199, self.tradeDate='20230901', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25984.5', self.close='25975.2'
127.0.0.1 - - [01/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15870 

self.closeSec=1693555799, self.tradeDate='20230901', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25975.3', self.close='25994.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15871 

self.closeSec=1693556399, self.tradeDate='20230901', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25994.2', self.close='25970.1'
127.0.0.1 - - [01/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31732
self.closeSec=1693556399, self.tradeDate='20230901', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25986.2, self.close=25970.1, self.high=25986.3, self.low=25970.0, self.vol=452.457, self.amt=11752588.0983 
127.0.0.1 - - [01/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-01 16:20:05,436:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230901   155500    155959  ...         0.0        0.0       0
5940  20230901   160000    160459  ...         0.0        0.0       0
5941  20230901   160500    160959  ...         0.0        0.0       0
5942  20230901   161000    161459  ...         0.0        0.0       0
5943  20230901   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 16:20:05,440:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693556399, self.tradeDate='20230901', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25986.2, self.close=25970.1, self.high=25986.3, self.low=25970.0, self.vol=452.457, self.amt=11752588.0983, ukdf['pct'].iloc[-1]=-0.00062 , ukdf['amount'].iloc[-1]=11752588.0983, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-32457.5199', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25970.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31733
self.closeSec=1693556699, self.tradeDate='20230901', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25970.1, self.close=25971.4, self.high=25983.9, self.low=25964.8, self.vol=621.05, self.amt=16129990.2158 
2023-09-01 16:25:00,831:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230901   160000    160459  ...         0.0        0.0       0
5941  20230901   160500    160959  ...         0.0        0.0       0
5942  20230901   161000    161459  ...         0.0        0.0       0
5943  20230901   161500    161959  ...         0.0        0.0       0
5944  20230901   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 16:25:00,831:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693556699, self.tradeDate='20230901', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25970.1, self.close=25971.4, self.high=25983.9, self.low=25964.8, self.vol=621.05, self.amt=16129990.2158, ukdf['pct'].iloc[-1]=5e-05 , ukdf['amount'].iloc[-1]=16129990.2158, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-32409.03676693501', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25971.40538039', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230901   040000    075959  1693526399  ...    721  0.671389  1.059724     1.0
722  20230901   080000    115959  1693540799  ...    722  0.673253  1.045144     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-100769.2452', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26073.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=661
self.closeSec=1693555199, self.tradeDate='20230901', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26071.4, self.close=25975.2, self.high=26086.2, self.low=25962.1, self.vol=18796.654, self.amt=488893032.2654 
127.0.0.1 - - [01/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-01 16:00:01,541:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693555199, self.tradeDate='20230901', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26071.4, self.close=25975.2, self.high=26086.2, self.low=25962.1, self.vol=18796.654, self.amt=488893032.2654 
2023-09-01 16:00:01,553:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230831   200000    235959  ...  102882.780  2.784818e+09 -0.014169
720  20230901   000000    035959  ...  224162.459  5.910897e+09 -0.028114
721  20230901   040000    075959  ...   90168.579  2.339531e+09 -0.008440
722  20230901   080000    115959  ...   27071.631  7.043482e+08  0.005535
723  20230901   120000    155959  ...   18796.654  4.888930e+08 -0.003694

[5 rows x 11 columns]
2023-09-01 16:00:02,251:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230831   200000    235959  1693497599  ...    719  0.839319  1.656219     1.0
720  20230901   000000    035959  1693511999  ...    720  0.707481  1.199751     1.0
721  20230901   040000    075959  1693526399  ...    721  0.671389  1.059724     1.0
722  20230901   080000    115959  1693540799  ...    722  0.673253  1.045144     1.0
723  20230901   120000    155959  1693555199  ...    723  0.673651  1.030149     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-106380.89775725568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25975.68329216', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


