# 20230922 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37588
self.closeSec=1695313199, self.tradeDate='20230922', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26550.0, self.close=26563.0, self.high=26570.3, self.low=26540.5, self.vol=1158.864, self.amt=30778050.1709 
127.0.0.1 - - [22/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-22 00:20:06,196:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230921   235500    235959  ...         0.0        0.0       0
5760  20230922   000000    000459  ...         0.0        0.0       0
5761  20230922   000500    000959  ...         0.0        0.0       0
5762  20230922   001000    001459  ...         0.0        0.0       0
5763  20230922   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 00:20:06,200:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695313199, self.tradeDate='20230922', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26550.0, self.close=26563.0, self.high=26570.3, self.low=26540.5, self.vol=1158.864, self.amt=30778050.1709, ukdf['pct'].iloc[-1]=0.000686 , ukdf['amount'].iloc[-1]=30778050.1709, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4217.9971183911', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26562.01352015', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37589
self.closeSec=1695313499, self.tradeDate='20230922', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26563.1, self.close=26561.9, self.high=26569.9, self.low=26548.5, self.vol=510.315, self.amt=13554741.0537 
2023-09-22 00:25:00,824:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230922   000000    000459  ...         0.0        0.0       0
5761  20230922   000500    000959  ...         0.0        0.0       0
5762  20230922   001000    001459  ...         0.0        0.0       0
5763  20230922   001500    001959  ...         0.0        0.0       0
5764  20230922   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 00:25:00,825:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695313499, self.tradeDate='20230922', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26563.1, self.close=26561.9, self.high=26569.9, self.low=26548.5, self.vol=510.315, self.amt=13554741.0537, ukdf['pct'].iloc[-1]=-4.1e-05 , ukdf['amount'].iloc[-1]=13554741.0537, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4199.37504684324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26563.35073626', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [22/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230917' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37588 

self.closeSec=1695312599, self.tradeDate='20230922', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26562.3, self.close=26554.3, self.high=26582.1, self.low=26538.4 
127.0.0.1 - - [22/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37589 

self.closeSec=1695312899, self.tradeDate='20230922', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26554.3, self.close=26544.8, self.high=26563.3, self.low=26530.8 
127.0.0.1 - - [22/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37590 

self.closeSec=1695313199, self.tradeDate='20230922', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26550.0, self.close=26563.0, self.high=26570.3, self.low=26540.5 
127.0.0.1 - - [22/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37591 

self.closeSec=1695313499, self.tradeDate='20230922', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26563.1, self.close=26561.9, self.high=26569.9, self.low=26548.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-22 00:00:19,277:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230921    212959  26630.1  ...  50.416667  0.412750  0.688800
5802  20230921    215959  26549.8  ...  50.000000  0.390706  0.706317
5803  20230921    222959  26408.2  ...  50.416667  0.414255  0.715218
5804  20230921    225959  26510.4  ...  50.833333  0.427394  0.718232
5805  20230921    232959  26569.8  ...  50.416667  0.424775  0.722265

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-09-22 00:00:19,335:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.466714  0.533286       0  ...  0.906330  -1.0    0.0  1.021871
540     1  0.441301  0.558699       1  ...  0.902826  -1.0    0.0  1.025821
541     0  0.510932  0.489068       1  ...  0.900803  -1.0    0.0  1.028120
542     0  0.504496  0.495504       0  ...  0.901345  -1.0    0.0  1.027501
543     1  0.487509  0.512491       1  ...  0.900870  -1.0    0.0  1.028042

[5 rows x 10 columns]
2023-09-22 00:00:19,346:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.466495  0.533505       0  ...  0.906330  -1.0    0.0  1.021456
46     1  0.441668  0.558332       1  ...  0.902826  -1.0    0.0  1.025865
47     0  0.510807  0.489193       1  ...  0.900803  -1.0    0.0  1.027965
48     0  0.504376  0.495624       0  ...  0.901345  -1.0    0.0  1.027346
49     1  0.487509  0.512491       1  ...  0.900870  -1.0    0.0  1.028042

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '14609.4071561341', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26562.27623077', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18791 

self.closeSec=1695310199, self.tradeDate='20230921', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26550.8', self.close='26550.5'
127.0.0.1 - - [21/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [21/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18792 

self.closeSec=1695310799, self.tradeDate='20230921', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26550.5', self.close='26540.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18793 

self.closeSec=1695311399, self.tradeDate='20230921', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26540', self.close='26619.2'
127.0.0.1 - - [21/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18794 

self.closeSec=1695311999, self.tradeDate='20230921', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26619.2', self.close='26567.6'
127.0.0.1 - - [22/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18795 

self.closeSec=1695312599, self.tradeDate='20230922', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26567.6', self.close='26554.3'
127.0.0.1 - - [22/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18796 

self.closeSec=1695313199, self.tradeDate='20230922', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26554.3', self.close='26563'
127.0.0.1 - - [22/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [21/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18794 

self.closeSec=1695310199, self.tradeDate='20230921', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26550.8', self.close='26550.5'
127.0.0.1 - - [21/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18795 

self.closeSec=1695310799, self.tradeDate='20230921', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26550.5', self.close='26540.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18796 

self.closeSec=1695311399, self.tradeDate='20230921', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26540', self.close='26619.2'
127.0.0.1 - - [21/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18797 

self.closeSec=1695311999, self.tradeDate='20230921', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26619.2', self.close='26567.6'
127.0.0.1 - - [22/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18798 

self.closeSec=1695312599, self.tradeDate='20230922', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26567.6', self.close='26554.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18799 

self.closeSec=1695313199, self.tradeDate='20230922', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26554.3', self.close='26563'
127.0.0.1 - - [22/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18794 

self.closeSec=1695310199, self.tradeDate='20230921', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26550.8', self.close='26550.5'
127.0.0.1 - - [21/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18795 

self.closeSec=1695310799, self.tradeDate='20230921', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26550.5', self.close='26540.1'
127.0.0.1 - - [21/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18796 

self.closeSec=1695311399, self.tradeDate='20230921', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26540', self.close='26619.2'
127.0.0.1 - - [22/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18797 

self.closeSec=1695311999, self.tradeDate='20230921', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26619.2', self.close='26567.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18798 

self.closeSec=1695312599, self.tradeDate='20230922', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26567.6', self.close='26554.3'
127.0.0.1 - - [22/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18799 

self.closeSec=1695313199, self.tradeDate='20230922', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26554.3', self.close='26563'
127.0.0.1 - - [22/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37588
self.closeSec=1695313199, self.tradeDate='20230922', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26550.0, self.close=26563.0, self.high=26570.3, self.low=26540.5, self.vol=1158.864, self.amt=30778050.1709 
127.0.0.1 - - [22/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-22 00:20:06,199:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230921   235500    235959  ...         0.0        0.0       0
5760  20230922   000000    000459  ...         0.0        0.0       0
5761  20230922   000500    000959  ...         0.0        0.0       0
5762  20230922   001000    001459  ...         0.0        0.0       0
5763  20230922   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 00:20:06,203:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695313199, self.tradeDate='20230922', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26550.0, self.close=26563.0, self.high=26570.3, self.low=26540.5, self.vol=1158.864, self.amt=30778050.1709, ukdf['pct'].iloc[-1]=0.000686 , ukdf['amount'].iloc[-1]=30778050.1709, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10473.25984810885', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26562.01352015', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37589
self.closeSec=1695313499, self.tradeDate='20230922', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26563.1, self.close=26561.9, self.high=26569.9, self.low=26548.5, self.vol=510.315, self.amt=13554741.0537 
2023-09-22 00:25:00,825:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230922   000000    000459  ...         0.0        0.0       0
5761  20230922   000500    000959  ...         0.0        0.0       0
5762  20230922   001000    001459  ...         0.0        0.0       0
5763  20230922   001500    001959  ...         0.0        0.0       0
5764  20230922   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 00:25:00,826:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695313499, self.tradeDate='20230922', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26563.1, self.close=26561.9, self.high=26569.9, self.low=26548.5, self.vol=510.315, self.amt=13554741.0537, ukdf['pct'].iloc[-1]=-4.1e-05 , ukdf['amount'].iloc[-1]=13554741.0537, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10423.59430456734', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26563.35073626', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230921   120000    155959  1695283199  ...    723  0.918522  1.378474     1.0
724  20230921   160000    195959  1695297599  ...    724  0.803757  1.048500     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-27021.90953264913', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26719.33648901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [22/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=783
self.closeSec=1695311999, self.tradeDate='20230921', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26722.8, self.close=26567.7, self.high=26769.8, self.low=26360.1, self.vol=114856.578, self.amt=3047360031.22669 
2023-09-22 00:00:01,515:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695311999, self.tradeDate='20230921', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26722.8, self.close=26567.7, self.high=26769.8, self.low=26360.1, self.vol=114856.578, self.amt=3047360031.22669 
2023-09-22 00:00:01,528:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230921   040000    075959  ...   45455.539  1.231102e+09  0.007175
722  20230921   080000    115959  ...   30051.717  8.117329e+08 -0.002977
723  20230921   120000    155959  ...   23776.748  6.426496e+08 -0.001798
724  20230921   160000    195959  ...   93622.480  2.506864e+09 -0.009474
725  20230921   200000    235959  ...  114856.578  3.047360e+09 -0.005804

[5 rows x 11 columns]
2023-09-22 00:00:02,173:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230921   040000    075959  1695254399  ...    721  1.168680  2.155180     1.0
722  20230921   080000    115959  1695268799  ...    722  1.072655  1.830405     1.0
723  20230921   120000    155959  1695283199  ...    723  0.918522  1.378474     1.0
724  20230921   160000    195959  1695297599  ...    724  0.803757  1.048500     1.0
725  20230921   200000    235959  1695311999  ...    725  0.683797  0.714745     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-34673.06775214854', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26568.68458558', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


