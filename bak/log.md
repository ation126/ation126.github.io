# 20230901 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31540
self.closeSec=1693498799, self.tradeDate='20230901', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26834.8, self.close=26788.3, self.high=26863.7, self.low=26700.0, self.vol=10418.664, self.amt=279137138.7053 
127.0.0.1 - - [01/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-01 00:20:05,287:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230831   235500    235959  ...         0.0        0.0       0
5748  20230901   000000    000459  ...         0.0        0.0       0
5749  20230901   000500    000959  ...         0.0        0.0       0
5750  20230901   001000    001459  ...         0.0        0.0       0
5751  20230901   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 00:20:05,290:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693498799, self.tradeDate='20230901', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26834.8, self.close=26788.3, self.high=26863.7, self.low=26700.0, self.vol=10418.664, self.amt=279137138.7053, ukdf['pct'].iloc[-1]=-0.001733 , ukdf['amount'].iloc[-1]=279137138.7053, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '937.2198', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26797.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31541
self.closeSec=1693499099, self.tradeDate='20230901', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26789.2, self.close=26768.6, self.high=26837.8, self.low=26761.2, self.vol=3156.992, self.amt=84597885.8981 
2023-09-01 00:25:00,787:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230901   000000    000459  ...         0.0        0.0       0
5749  20230901   000500    000959  ...         0.0        0.0       0
5750  20230901   001000    001459  ...         0.0        0.0       0
5751  20230901   001500    001959  ...         0.0        0.0       0
5752  20230901   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 00:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693499099, self.tradeDate='20230901', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26789.2, self.close=26768.6, self.high=26837.8, self.low=26761.2, self.vol=3156.992, self.amt=84597885.8981, ukdf['pct'].iloc[-1]=-0.000735 , ukdf['amount'].iloc[-1]=84597885.8981, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1251.61252064244', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26775.02404706', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1693497899, self.tradeDate='20230901', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26909.4, self.close=26876.9, self.high=26913.6, self.low=26849.9 

--ukdf-hist--: overDate='20230827' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [01/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31540 

self.closeSec=1693498199, self.tradeDate='20230901', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26876.2, self.close=26889.5, self.high=26913.9, self.low=26871.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31541 

self.closeSec=1693498499, self.tradeDate='20230901', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26889.4, self.close=26834.8, self.high=26899.4, self.low=26823.0 
127.0.0.1 - - [01/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31542 

self.closeSec=1693498799, self.tradeDate='20230901', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26834.8, self.close=26788.3, self.high=26863.7, self.low=26700.0 
127.0.0.1 - - [01/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31543 

self.closeSec=1693499099, self.tradeDate='20230901', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26789.2, self.close=26768.6, self.high=26837.8, self.low=26761.2 
127.0.0.1 - - [01/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-01 00:00:17,043:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230831    212959  27178.8  ...  47.916667  0.509792  0.521416
5802  20230831    215959  27153.9  ...  47.500000  0.505979  0.540466
5803  20230831    222959  27138.0  ...  47.500000  0.502653  0.559621
5804  20230831    225959  27126.8  ...  47.500000  0.511174  0.573926
5805  20230831    232959  27162.3  ...  47.500000  0.504925  0.589806

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-09-01 00:00:17,102:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.476345  0.523655       0  ...  0.976957   1.0    0.0  1.040827
540     1  0.472110  0.527890       0  ...  0.976464   1.0    0.0  1.040301
541     1  0.472517  0.527483       1  ...  0.977746   1.0    0.0  1.041667
542     1  0.494258  0.505742       0  ...  0.976839   1.0    0.0  1.040700
543     1  0.480641  0.519359       0  ...  0.968570   1.0    0.0  1.031890

[5 rows x 10 columns]
2023-09-01 00:00:17,113:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.476531  0.523469       0  ...  0.976957   1.0    0.0  1.041326
46     1  0.472503  0.527497       0  ...  0.976464   1.0    0.0  1.041192
47     1  0.472601  0.527399       1  ...  0.977746   1.0    0.0  1.042106
48     1  0.494449  0.505551       0  ...  0.976839   1.0    0.0  1.041139
49     1  0.480641  0.519359       0  ...  0.968570   1.0    0.0  1.031890

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.311', 'enterprice': '27227', 'countrevence': '0', 'unrealprofit': '-8534.92850682827', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26902.61367843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15767 

self.closeSec=1693495799, self.tradeDate='20230831', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27143.9', self.close='27134.8'
127.0.0.1 - - [31/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15768 

self.closeSec=1693496399, self.tradeDate='20230831', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27134.7', self.close='27080'
127.0.0.1 - - [31/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15769 

self.closeSec=1693496999, self.tradeDate='20230831', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27080', self.close='26917.8'
127.0.0.1 - - [01/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15770 

self.closeSec=1693497599, self.tradeDate='20230831', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26917.8', self.close='26909.5'
127.0.0.1 - - [01/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15771 

self.closeSec=1693498199, self.tradeDate='20230901', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26909.4', self.close='26889.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15772 

self.closeSec=1693498799, self.tradeDate='20230901', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26889.4', self.close='26788.3'
127.0.0.1 - - [01/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [31/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15770 

self.closeSec=1693495799, self.tradeDate='20230831', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27143.9', self.close='27134.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15771 

self.closeSec=1693496399, self.tradeDate='20230831', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27134.7', self.close='27080'
127.0.0.1 - - [31/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15772 

self.closeSec=1693496999, self.tradeDate='20230831', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27080', self.close='26917.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15773 

self.closeSec=1693497599, self.tradeDate='20230831', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26917.8', self.close='26909.5'
127.0.0.1 - - [01/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15774 

self.closeSec=1693498199, self.tradeDate='20230901', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26909.4', self.close='26889.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15775 

self.closeSec=1693498799, self.tradeDate='20230901', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26889.4', self.close='26788.3'
127.0.0.1 - - [01/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15770 

self.closeSec=1693495799, self.tradeDate='20230831', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27143.9', self.close='27134.8'
127.0.0.1 - - [31/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15771 

self.closeSec=1693496399, self.tradeDate='20230831', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27134.7', self.close='27080'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15772 

self.closeSec=1693496999, self.tradeDate='20230831', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27080', self.close='26917.8'
127.0.0.1 - - [31/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15773 

self.closeSec=1693497599, self.tradeDate='20230831', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26917.8', self.close='26909.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15774 

self.closeSec=1693498199, self.tradeDate='20230901', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26909.4', self.close='26889.5'
127.0.0.1 - - [01/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15775 

self.closeSec=1693498799, self.tradeDate='20230901', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26889.4', self.close='26788.3'
127.0.0.1 - - [01/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31540
self.closeSec=1693498799, self.tradeDate='20230901', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26834.8, self.close=26788.3, self.high=26863.7, self.low=26700.0, self.vol=10418.664, self.amt=279137138.7053 
127.0.0.1 - - [01/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-09-01 00:20:05,288:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230831   235500    235959  ...         0.0        0.0       0
5748  20230901   000000    000459  ...         0.0        0.0       0
5749  20230901   000500    000959  ...         0.0        0.0       0
5750  20230901   001000    001459  ...         0.0        0.0       0
5751  20230901   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 00:20:05,290:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693498799, self.tradeDate='20230901', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26834.8, self.close=26788.3, self.high=26863.7, self.low=26700.0, self.vol=10418.664, self.amt=279137138.7053, ukdf['pct'].iloc[-1]=-0.001733 , ukdf['amount'].iloc[-1]=279137138.7053, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1723.3424', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26797.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31541
self.closeSec=1693499099, self.tradeDate='20230901', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26789.2, self.close=26768.6, self.high=26837.8, self.low=26761.2, self.vol=3156.992, self.amt=84597885.8981 
2023-09-01 00:25:00,786:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230901   000000    000459  ...         0.0        0.0       0
5749  20230901   000500    000959  ...         0.0        0.0       0
5750  20230901   001000    001459  ...         0.0        0.0       0
5751  20230901   001500    001959  ...         0.0        0.0       0
5752  20230901   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 00:25:00,786:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693499099, self.tradeDate='20230901', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26789.2, self.close=26768.6, self.high=26837.8, self.low=26761.2, self.vol=3156.992, self.amt=84597885.8981, ukdf['pct'].iloc[-1]=-0.000735 , ukdf['amount'].iloc[-1]=84597885.8981, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2561.83586814454', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26775.02404706', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230831   120000    155959  1693468799  ...    723  0.848542  1.788930     1.0
724  20230831   160000    195959  1693483199  ...    724  0.856356  1.760820     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-30916.13987356908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27293.79895421', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=657
self.closeSec=1693497599, self.tradeDate='20230831', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27291.8, self.close=26905.1, self.high=27305.1, self.low=26733.8, self.vol=102882.78, self.amt=2784818322.00247 
127.0.0.1 - - [01/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-01 00:00:01,546:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693497599, self.tradeDate='20230831', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27291.8, self.close=26905.1, self.high=27305.1, self.low=26733.8, self.vol=102882.78, self.amt=2784818322.00247 
2023-09-01 00:00:01,560:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230831   040000    075959  ...   21666.717  5.907011e+08  0.004535
722  20230831   080000    115959  ...   16078.296  4.374189e+08 -0.003027
723  20230831   120000    155959  ...   16560.471  4.511445e+08  0.001514
724  20230831   160000    195959  ...   53026.501  1.449832e+09  0.001567
725  20230831   200000    235959  ...  102882.780  2.784818e+09 -0.014169

[5 rows x 11 columns]
2023-09-01 00:00:02,260:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230831   040000    075959  1693439999  ...    721  0.943311  2.238721     1.0
722  20230831   080000    115959  1693454399  ...    722  0.898518  2.013491     1.0
723  20230831   120000    155959  1693468799  ...    723  0.848542  1.788930     1.0
724  20230831   160000    195959  1693483199  ...    724  0.856356  1.760820     1.0
725  20230831   200000    235959  1693497599  ...    725  0.839319  1.656219     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-52918.0236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26909.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


