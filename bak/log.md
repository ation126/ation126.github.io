# 20230919 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36724
self.closeSec=1695053999, self.tradeDate='20230919', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27259.7, self.close=27221.2, self.high=27265.6, self.low=27212.3, self.vol=1487.421, self.amt=40501733.2524 
127.0.0.1 - - [19/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-19 00:20:06,653:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230918   235500    235959  ...         0.0        0.0       0
5760  20230919   000000    000459  ...         0.0        0.0       0
5761  20230919   000500    000959  ...         0.0        0.0       0
5762  20230919   001000    001459  ...         0.0        0.0       0
5763  20230919   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-19 00:20:06,664:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695053999, self.tradeDate='20230919', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27259.7, self.close=27221.2, self.high=27265.6, self.low=27212.3, self.vol=1487.421, self.amt=40501733.2524, ukdf['pct'].iloc[-1]=-0.001412 , ukdf['amount'].iloc[-1]=40501733.2524, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4945.1226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27220', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36725
self.closeSec=1695054299, self.tradeDate='20230919', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27221.2, self.close=27185.2, self.high=27225.4, self.low=27178.9, self.vol=1910.293, self.amt=51963354.2152 
2023-09-19 00:25:00,834:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230919   000000    000459  ...         0.0        0.0       0
5761  20230919   000500    000959  ...         0.0        0.0       0
5762  20230919   001000    001459  ...         0.0        0.0       0
5763  20230919   001500    001959  ...         0.0        0.0       0
5764  20230919   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-19 00:25:00,835:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695054299, self.tradeDate='20230919', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27221.2, self.close=27185.2, self.high=27225.4, self.low=27178.9, self.vol=1910.293, self.amt=51963354.2152, ukdf['pct'].iloc[-1]=-0.001322 , ukdf['amount'].iloc[-1]=51963354.2152, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4447.80091962228', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27184.28826078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1695053099, self.tradeDate='20230919', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27258.8, self.close=27296.1, self.high=27296.1, self.low=27251.3 

--ukdf-hist--: overDate='20230914' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [19/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36724 

self.closeSec=1695053399, self.tradeDate='20230919', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27296.0, self.close=27265.0, self.high=27296.8, self.low=27261.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36725 

self.closeSec=1695053699, self.tradeDate='20230919', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27265.0, self.close=27259.7, self.high=27269.2, self.low=27238.6 
127.0.0.1 - - [19/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36726 

self.closeSec=1695053999, self.tradeDate='20230919', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27259.7, self.close=27221.2, self.high=27265.6, self.low=27212.3 
127.0.0.1 - - [19/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36727 

self.closeSec=1695054299, self.tradeDate='20230919', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27221.2, self.close=27185.2, self.high=27225.4, self.low=27178.9 
127.0.0.1 - - [19/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-19 00:00:16,405:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230918    212959  27354.6  ...  52.916667  0.665358  0.231781
5802  20230918    215959  27255.2  ...  52.500000  0.660214  0.226383
5803  20230918    222959  27240.3  ...  52.083333  0.654594  0.222372
5804  20230918    225959  27224.3  ...  52.083333  0.658744  0.217190
5805  20230918    232959  27246.7  ...  52.083333  0.665285  0.210062

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-09-19 00:00:16,468:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.480774  0.519226       0  ...  0.955937   1.0    0.0  1.057843
540     1  0.497174  0.502826       0  ...  0.955375   1.0    0.0  1.057221
541     1  0.494623  0.505377       1  ...  0.956161   1.0    0.0  1.058091
542     0  0.502170  0.497830       1  ...  0.957414   1.0    0.0  1.059478
543     0  0.500757  0.499243       0  ...  0.956582   1.0    0.0  1.058557

[5 rows x 10 columns]
2023-09-19 00:00:16,480:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.480360  0.519640       0  ...  0.955937   1.0    0.0  1.056407
46     1  0.496862  0.503138       0  ...  0.955375   1.0    0.0  1.057254
47     1  0.494986  0.505014       1  ...  0.956161   1.0    0.0  1.058597
48     0  0.502546  0.497454       1  ...  0.957414   1.0    0.0  1.059984
49     0  0.500757  0.499243       0  ...  0.956582   1.0    0.0  1.058557

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '17859.852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27256.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18359 

self.closeSec=1695050999, self.tradeDate='20230918', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27280.5', self.close='27282.5'
127.0.0.1 - - [18/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18360 

self.closeSec=1695051599, self.tradeDate='20230918', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27282.4', self.close='27266.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18361 

self.closeSec=1695052199, self.tradeDate='20230918', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27269.1', self.close='27269.3'
127.0.0.1 - - [18/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18362 

self.closeSec=1695052799, self.tradeDate='20230918', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27269.2', self.close='27258.8'
127.0.0.1 - - [19/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18363 

self.closeSec=1695053399, self.tradeDate='20230919', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27258.8', self.close='27265'
127.0.0.1 - - [19/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18364 

self.closeSec=1695053999, self.tradeDate='20230919', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27265', self.close='27221.2'
127.0.0.1 - - [19/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18362 

self.closeSec=1695050999, self.tradeDate='20230918', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27280.5', self.close='27282.5'
127.0.0.1 - - [18/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18363 

self.closeSec=1695051599, self.tradeDate='20230918', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27282.4', self.close='27266.9'
127.0.0.1 - - [18/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18364 

self.closeSec=1695052199, self.tradeDate='20230918', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27269.1', self.close='27269.3'
127.0.0.1 - - [19/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18365 

self.closeSec=1695052799, self.tradeDate='20230918', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27269.2', self.close='27258.8'
127.0.0.1 - - [19/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18366 

self.closeSec=1695053399, self.tradeDate='20230919', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27258.8', self.close='27265'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18367 

self.closeSec=1695053999, self.tradeDate='20230919', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27265', self.close='27221.2'
127.0.0.1 - - [19/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18362 

self.closeSec=1695050999, self.tradeDate='20230918', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27280.5', self.close='27282.5'
127.0.0.1 - - [18/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [18/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18363 

self.closeSec=1695051599, self.tradeDate='20230918', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27282.4', self.close='27266.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18364 

self.closeSec=1695052199, self.tradeDate='20230918', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27269.1', self.close='27269.3'
127.0.0.1 - - [18/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18365 

self.closeSec=1695052799, self.tradeDate='20230918', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27269.2', self.close='27258.8'
127.0.0.1 - - [19/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18366 

self.closeSec=1695053399, self.tradeDate='20230919', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27258.8', self.close='27265'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18367 

self.closeSec=1695053999, self.tradeDate='20230919', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27265', self.close='27221.2'
127.0.0.1 - - [19/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36724
self.closeSec=1695053999, self.tradeDate='20230919', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27259.7, self.close=27221.2, self.high=27265.6, self.low=27212.3, self.vol=1487.421, self.amt=40501733.2524 
127.0.0.1 - - [19/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-19 00:20:06,655:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230918   235500    235959  ...         0.0        0.0       0
5760  20230919   000000    000459  ...         0.0        0.0       0
5761  20230919   000500    000959  ...         0.0        0.0       0
5762  20230919   001000    001459  ...         0.0        0.0       0
5763  20230919   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-19 00:20:06,672:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695053999, self.tradeDate='20230919', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27259.7, self.close=27221.2, self.high=27265.6, self.low=27212.3, self.vol=1487.421, self.amt=40501733.2524, ukdf['pct'].iloc[-1]=-0.001412 , ukdf['amount'].iloc[-1]=40501733.2524, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '13965.016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27220', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36725
self.closeSec=1695054299, self.tradeDate='20230919', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27221.2, self.close=27185.2, self.high=27225.4, self.low=27178.9, self.vol=1910.293, self.amt=51963354.2152 
127.0.0.1 - - [19/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-19 00:25:00,836:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230919   000000    000459  ...         0.0        0.0       0
5761  20230919   000500    000959  ...         0.0        0.0       0
5762  20230919   001000    001459  ...         0.0        0.0       0
5763  20230919   001500    001959  ...         0.0        0.0       0
5764  20230919   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-19 00:25:00,837:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695054299, self.tradeDate='20230919', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27221.2, self.close=27185.2, self.high=27225.4, self.low=27178.9, self.vol=1910.293, self.amt=51963354.2152, ukdf['pct'].iloc[-1]=-0.001322 , ukdf['amount'].iloc[-1]=51963354.2152, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '12638.64629362998', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27184.28826078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

722  20230918   080000    115959  ...   59009.210  1.567701e+09  0.004982
723  20230918   120000    155959  ...   34889.774  9.303334e+08  0.002079
724  20230918   160000    195959  ...  117536.972  3.171943e+09  0.018018
725  20230918   200000    235959  ...   99944.871  2.725819e+09  0.002796

[5 rows x 11 columns]
2023-09-19 00:00:02,167:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230918   040000    075959  1694995199  ...    721  0.105896 -0.793562    -1.0
722  20230918   080000    115959  1695009599  ...    722  0.036809 -1.075083    -1.0
723  20230918   120000    155959  1695023999  ...    723  0.067519 -0.927845    -1.0
724  20230918   160000    195959  1695038399  ...    724  0.216534 -0.241430     NaN
725  20230918   200000    235959  1695052799  ...    725  0.582874  1.495848     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.675', 'enterprice': '26538.7', 'countrevence': '0', 'unrealprofit': '-38651.3675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27258.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.675', 'enterprice': '26538.7', 'countrevence': '0', 'unrealprofit': '-38651.3675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27258.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-09-19 00:00:09,099:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1388563.4527429', 'total': '1388563.4527429', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-09-19 00:00:09,576:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-09-19 00:00:09,577:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 50.787, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42954F1695052809574I0L65'}
2023-09-19 00:00:09,602:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:9190000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230918, closeTime:235959, close:27258.8, sign:1, total:1388563.4527429, side:buy  
127.0.0.1 - - [19/Sep/2023 00:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Sep/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-09-19 00:00:09,607:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42953F1695052804028I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695052804442051, 'quantity': '53.675', 'price': '27258.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1695052803035, 'updatetime': 1695052804442, 'tradetype': 'usdt', 'selfid': 42953, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695052804442, 'clientorderid': '42953F1695052804028I0L65', 'price': '27258.8', 'quantity': '53.675', 'commission': '1463.11609', 'commissionasset': 'USDT', 'tradetime': 1695052804442, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695052804442}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-19 00:00:09,607:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42953F1695052804028I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695052804442051, 'quantity': '53.675', 'price': '27258.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1695052803035, 'updatetime': 1695052804442, 'tradetype': 'usdt', 'selfid': 42953, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695052804442, 'clientorderid': '42953F1695052804028I0L65', 'price': '27258.8', 'quantity': '53.675', 'commission': '1463.11609', 'commissionasset': 'USDT', 'tradetime': 1695052804442, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695052804442}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Sep/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-09-19 00:00:10,067:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42954F1695052809574I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695052810025374, 'quantity': '50.787', 'price': '27251.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1695052809113, 'updatetime': 1695052810025, 'tradetype': 'usdt', 'selfid': 42954, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695052810025, 'clientorderid': '42954F1695052809574I0L65', 'price': '27251.4', 'quantity': '50.787', 'commission': '1384.0168518', 'commissionasset': 'USDT', 'tradetime': 1695052810025, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695052810025}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-19 00:00:10,219:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42954F1695052809574I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695052810025374, 'quantity': '50.787', 'price': '27251.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1695052809113, 'updatetime': 1695052810025, 'tradetype': 'usdt', 'selfid': 42954, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695052810025, 'clientorderid': '42954F1695052809574I0L65', 'price': '27251.4', 'quantity': '50.787', 'commission': '1384.0168518', 'commissionasset': 'USDT', 'tradetime': 1695052810025, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695052810025}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Sep/2023 00:00:10] "POST / HTTP/1.1" 200 -


