# 20231010 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42964
self.closeSec=1696925999, self.tradeDate='20231010', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27678.0, self.close=27681.7, self.high=27691.8, self.low=27655.5, self.vol=723.716, self.amt=20026135.0985 
127.0.0.1 - - [10/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-10-10 16:20:07,422:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231010   155500    155959  ...         0.0        0.0       0
5952  20231010   160000    160459  ...         0.0        0.0       0
5953  20231010   160500    160959  ...         0.0        0.0       0
5954  20231010   161000    161459  ...         0.0        0.0       0
5955  20231010   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 16:20:07,426:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696925999, self.tradeDate='20231010', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27678.0, self.close=27681.7, self.high=27691.8, self.low=27655.5, self.vol=723.716, self.amt=20026135.0985, ukdf['pct'].iloc[-1]=0.000134 , ukdf['amount'].iloc[-1]=20026135.0985, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11391.468', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27682.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42965
self.closeSec=1696926299, self.tradeDate='20231010', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27681.7, self.close=27686.2, self.high=27727.3, self.low=27680.2, self.vol=2234.099, self.amt=61896958.4229 
127.0.0.1 - - [10/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-10-10 16:25:00,797:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231010   160000    160459  ...         0.0        0.0       0
5953  20231010   160500    160959  ...         0.0        0.0       0
5954  20231010   161000    161459  ...         0.0        0.0       0
5955  20231010   161500    161959  ...         0.0        0.0       0
5956  20231010   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 16:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696926299, self.tradeDate='20231010', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27681.7, self.close=27686.2, self.high=27727.3, self.low=27680.2, self.vol=2234.099, self.amt=61896958.4229, ukdf['pct'].iloc[-1]=0.000163 , ukdf['amount'].iloc[-1]=61896958.4229, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11450.6706651876', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27687.1512326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42962 

self.closeSec=1696924799, self.tradeDate='20231010', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27641.4, self.close=27634.8, self.high=27641.5, self.low=27633.3 
127.0.0.1 - - [10/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42963 

self.closeSec=1696925099, self.tradeDate='20231010', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27634.9, self.close=27641.0, self.high=27641.9, self.low=27630.0 
127.0.0.1 - - [10/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42964 

self.closeSec=1696925399, self.tradeDate='20231010', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27641.1, self.close=27635.7, self.high=27648.0, self.low=27635.6 
127.0.0.1 - - [10/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42965 

self.closeSec=1696925699, self.tradeDate='20231010', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27635.6, self.close=27678.0, self.high=27682.5, self.low=27635.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42966 

self.closeSec=1696925999, self.tradeDate='20231010', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27678.0, self.close=27681.7, self.high=27691.8, self.low=27655.5 
127.0.0.1 - - [10/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42967 

self.closeSec=1696926299, self.tradeDate='20231010', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27681.7, self.close=27686.2, self.high=27727.3, self.low=27680.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-10 16:00:17,787:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231010    132959  27584.6  ...  49.166667  0.465464  0.506557
5786  20231010    135959  27577.9  ...  49.583333  0.471228  0.492354
5787  20231010    142959  27595.9  ...  50.000000  0.481280  0.474781
5788  20231010    145959  27627.6  ...  50.000000  0.484561  0.456963
5789  20231010    152959  27638.0  ...  50.416667  0.489220  0.438332

[5 rows x 33 columns]
0.5627306273062731
acc is : 0.5627306273062731
2023-10-10 16:00:17,849:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494270  0.505730       1  ...  0.943323  -1.0    0.0  1.019921
538     0  0.503953  0.496047       1  ...  0.942239  -1.0    0.0  1.021093
539     0  0.509139  0.490861       1  ...  0.941884  -1.0    0.0  1.021477
540     0  0.505904  0.494096       1  ...  0.941383  -1.0    0.0  1.022020
541     0  0.508455  0.491545       0  ...  0.941989  -1.0    0.0  1.021362

[5 rows x 10 columns]
2023-10-10 16:00:17,861:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494115  0.505885       1  ...  0.943323  -1.0    0.0  1.022002
46     0  0.503597  0.496403       1  ...  0.942239  -1.0    0.0  1.022419
47     0  0.509087  0.490913       1  ...  0.941884  -1.0    0.0  1.023182
48     0  0.505472  0.494528       1  ...  0.941383  -1.0    0.0  1.021216
49     0  0.508455  0.491545       0  ...  0.941989  -1.0    0.0  1.021362

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.618', 'enterprice': '27520.8', 'countrevence': '0', 'unrealprofit': '-2812.9038', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27639.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [10/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21479 

self.closeSec=1696922999, self.tradeDate='20231010', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27662.4', self.close='27652.8'
127.0.0.1 - - [10/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21480 

self.closeSec=1696923599, self.tradeDate='20231010', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27652.7', self.close='27651'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21481 

self.closeSec=1696924199, self.tradeDate='20231010', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27651', self.close='27639.6'
127.0.0.1 - - [10/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21482 

self.closeSec=1696924799, self.tradeDate='20231010', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27639.7', self.close='27634.8'
127.0.0.1 - - [10/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21483 

self.closeSec=1696925399, self.tradeDate='20231010', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27634.9', self.close='27635.7'
127.0.0.1 - - [10/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21484 

self.closeSec=1696925999, self.tradeDate='20231010', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27635.6', self.close='27681.7'
127.0.0.1 - - [10/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21482 

self.closeSec=1696922999, self.tradeDate='20231010', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27662.4', self.close='27652.8'
127.0.0.1 - - [10/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21483 

self.closeSec=1696923599, self.tradeDate='20231010', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27652.7', self.close='27651'
127.0.0.1 - - [10/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21484 

self.closeSec=1696924199, self.tradeDate='20231010', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27651', self.close='27639.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21485 

self.closeSec=1696924799, self.tradeDate='20231010', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27639.7', self.close='27634.8'
127.0.0.1 - - [10/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21486 

self.closeSec=1696925399, self.tradeDate='20231010', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27634.9', self.close='27635.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21487 

self.closeSec=1696925999, self.tradeDate='20231010', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27635.6', self.close='27681.7'
127.0.0.1 - - [10/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21482 

self.closeSec=1696922999, self.tradeDate='20231010', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27662.4', self.close='27652.8'
127.0.0.1 - - [10/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21483 

self.closeSec=1696923599, self.tradeDate='20231010', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27652.7', self.close='27651'

--handleKline--: 127.0.0.1 - - [10/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21484 

self.closeSec=1696924199, self.tradeDate='20231010', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27651', self.close='27639.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21485 

self.closeSec=1696924799, self.tradeDate='20231010', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27639.7', self.close='27634.8'
127.0.0.1 - - [10/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21486 

self.closeSec=1696925399, self.tradeDate='20231010', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27634.9', self.close='27635.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21487 

self.closeSec=1696925999, self.tradeDate='20231010', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27635.6', self.close='27681.7'
127.0.0.1 - - [10/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42964
self.closeSec=1696925999, self.tradeDate='20231010', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27678.0, self.close=27681.7, self.high=27691.8, self.low=27655.5, self.vol=723.716, self.amt=20026135.0985 
127.0.0.1 - - [10/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-10-10 16:20:07,424:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231010   155500    155959  ...         0.0        0.0       0
5952  20231010   160000    160459  ...         0.0        0.0       0
5953  20231010   160500    160959  ...         0.0        0.0       0
5954  20231010   161000    161459  ...         0.0        0.0       0
5955  20231010   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 16:20:07,430:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696925999, self.tradeDate='20231010', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27678.0, self.close=27681.7, self.high=27691.8, self.low=27655.5, self.vol=723.716, self.amt=20026135.0985, ukdf['pct'].iloc[-1]=0.000134 , ukdf['amount'].iloc[-1]=20026135.0985, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '31157.5849', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27682.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42965
self.closeSec=1696926299, self.tradeDate='20231010', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27681.7, self.close=27686.2, self.high=27727.3, self.low=27680.2, self.vol=2234.099, self.amt=61896958.4229 
127.0.0.1 - - [10/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-10-10 16:25:00,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231010   160000    160459  ...         0.0        0.0       0
5953  20231010   160500    160959  ...         0.0        0.0       0
5954  20231010   161000    161459  ...         0.0        0.0       0
5955  20231010   161500    161959  ...         0.0        0.0       0
5956  20231010   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 16:25:00,802:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696926299, self.tradeDate='20231010', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27681.7, self.close=27686.2, self.high=27727.3, self.low=27680.2, self.vol=2234.099, self.amt=61896958.4229, ukdf['pct'].iloc[-1]=0.000163 , ukdf['amount'].iloc[-1]=61896958.4229, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '31315.4799299966', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27687.1512326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231010   040000    075959  1696895999  ...    721  0.134666 -0.990590    -1.0
722  20231010   080000    115959  1696910399  ...    722  0.108002 -1.054893    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '13981.5579', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27623.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=895
self.closeSec=1696924799, self.tradeDate='20231010', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27621.5, self.close=27634.8, self.high=27694.9, self.low=27565.2, self.vol=18658.552, self.amt=515390180.9441 
127.0.0.1 - - [10/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-10 16:00:01,500:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696924799, self.tradeDate='20231010', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27621.5, self.close=27634.8, self.high=27694.9, self.low=27565.2, self.vol=18658.552, self.amt=515390180.9441 
2023-10-10 16:00:01,513:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231009   200000    235959  ...  60969.452  1.674700e+09 -0.000830
720  20231010   000000    035959  ...  99576.614  2.736496e+09  0.006139
721  20231010   040000    075959  ...  15212.963  4.196862e+08 -0.000837
722  20231010   080000    115959  ...  24569.399  6.778474e+08  0.001566
723  20231010   120000    155959  ...  18658.552  5.153902e+08  0.000478

[5 rows x 11 columns]
2023-10-10 16:00:02,211:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231009   200000    235959  1696867199  ...    719  0.091458 -1.143627    -1.0
720  20231010   000000    035959  1696881599  ...    720  0.150387 -0.960126    -1.0
721  20231010   040000    075959  1696895999  ...    721  0.134666 -0.990590    -1.0
722  20231010   080000    115959  1696910399  ...    722  0.108002 -1.054893    -1.0
723  20231010   120000    155959  1696924799  ...    723  0.086998 -1.102367    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '13397.69074685388', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27637.09236996', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


