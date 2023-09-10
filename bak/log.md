# 20230911 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34420
self.closeSec=1694362799, self.tradeDate='20230911', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25765.0, self.close=25774.2, self.high=25779.1, self.low=25760.5, self.vol=348.539, self.amt=8982941.9607 
127.0.0.1 - - [11/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-11 00:20:06,233:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230910   235500    235959  ...         0.0        0.0       0
5760  20230911   000000    000459  ...         0.0        0.0       0
5761  20230911   000500    000959  ...         0.0        0.0       0
5762  20230911   001000    001459  ...         0.0        0.0       0
5763  20230911   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 00:20:06,237:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694362799, self.tradeDate='20230911', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25765.0, self.close=25774.2, self.high=25779.1, self.low=25760.5, self.vol=348.539, self.amt=8982941.9607, ukdf['pct'].iloc[-1]=0.000357 , ukdf['amount'].iloc[-1]=8982941.9607, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15171.07950998442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25775.49317033', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34421
self.closeSec=1694363099, self.tradeDate='20230911', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25774.3, self.close=25757.1, self.high=25774.3, self.low=25757.0, self.vol=223.448, self.amt=5757185.5366 
2023-09-11 00:25:00,816:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230911   000000    000459  ...         0.0        0.0       0
5761  20230911   000500    000959  ...         0.0        0.0       0
5762  20230911   001000    001459  ...         0.0        0.0       0
5763  20230911   001500    001959  ...         0.0        0.0       0
5764  20230911   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 00:25:00,817:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694363099, self.tradeDate='20230911', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25774.3, self.close=25757.1, self.high=25774.3, self.low=25757.0, self.vol=223.448, self.amt=5757185.5366, ukdf['pct'].iloc[-1]=-0.000663 , ukdf['amount'].iloc[-1]=5757185.5366, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15427.2228', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25757.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1694361899, self.tradeDate='20230911', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=25764.1, self.close=25763.6, self.high=25770.7, self.low=25760.6 

--ukdf-hist--: overDate='20230906' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [11/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34420 

self.closeSec=1694362199, self.tradeDate='20230911', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25763.7, self.close=25763.9, self.high=25767.9, self.low=25759.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34421 

self.closeSec=1694362499, self.tradeDate='20230911', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25763.9, self.close=25765.0, self.high=25767.6, self.low=25760.0 
127.0.0.1 - - [11/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34422 

self.closeSec=1694362799, self.tradeDate='20230911', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25765.0, self.close=25774.2, self.high=25779.1, self.low=25760.5 
127.0.0.1 - - [11/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34423 

self.closeSec=1694363099, self.tradeDate='20230911', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25774.3, self.close=25757.1, self.high=25774.3, self.low=25757.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-11 00:00:18,848:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230910    212959  25790.2  ...  52.500000  0.461767  0.561972
5802  20230910    215959  25787.8  ...  52.916667  0.468755  0.564685
5803  20230910    222959  25799.6  ...  52.916667  0.462982  0.571348
5804  20230910    225959  25788.4  ...  52.500000  0.449466  0.587455
5805  20230910    232959  25761.8  ...  52.500000  0.437031  0.603981

[5 rows x 33 columns]
0.53125
acc is : 0.53125
2023-09-11 00:00:18,918:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.491059  0.508941       1  ...  1.031964  -1.0    0.0  0.940661
540     1  0.494642  0.505358       0  ...  1.032412  -1.0    0.0  0.940253
541     1  0.489518  0.510482       0  ...  1.033485  -1.0    0.0  0.939275
542     1  0.483367  0.516633       0  ...  1.034512  -1.0    0.0  0.938342
543     1  0.481470  0.518530       1  ...  1.033383  -1.0    0.0  0.939367

[5 rows x 10 columns]
2023-09-11 00:00:18,931:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490637  0.509363       1  ...  1.031964  -1.0    0.0  0.940856
46     1  0.494516  0.505484       0  ...  1.032412  -1.0    0.0  0.942080
47     1  0.489250  0.510750       0  ...  1.033485  -1.0    0.0  0.938461
48     1  0.482947  0.517053       0  ...  1.034512  -1.0    0.0  0.937528
49     1  0.481470  0.518530       1  ...  1.033383  -1.0    0.0  0.939367

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '275.43199948288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25761.76948352', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [10/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17207 

self.closeSec=1694359799, self.tradeDate='20230910', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25758.6', self.close='25736'
127.0.0.1 - - [10/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17208 

self.closeSec=1694360399, self.tradeDate='20230910', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25736', self.close='25767.4'

--handleKline--: 127.0.0.1 - - [10/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17209 

self.closeSec=1694360999, self.tradeDate='20230910', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25767.4', self.close='25763.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17210 

self.closeSec=1694361599, self.tradeDate='20230910', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25763.1', self.close='25764'
127.0.0.1 - - [11/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17211 

self.closeSec=1694362199, self.tradeDate='20230911', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25764.1', self.close='25763.9'
127.0.0.1 - - [11/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17212 

self.closeSec=1694362799, self.tradeDate='20230911', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25763.9', self.close='25774.2'
127.0.0.1 - - [11/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [10/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17210 

self.closeSec=1694359799, self.tradeDate='20230910', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25758.6', self.close='25736'
127.0.0.1 - - [10/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17211 

self.closeSec=1694360399, self.tradeDate='20230910', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25736', self.close='25767.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17212 

self.closeSec=1694360999, self.tradeDate='20230910', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25767.4', self.close='25763.1'
127.0.0.1 - - [10/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17213 

self.closeSec=1694361599, self.tradeDate='20230910', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25763.1', self.close='25764'
127.0.0.1 - - [11/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17214 

self.closeSec=1694362199, self.tradeDate='20230911', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25764.1', self.close='25763.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17215 

self.closeSec=1694362799, self.tradeDate='20230911', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25763.9', self.close='25774.2'
127.0.0.1 - - [11/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [10/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17210 

self.closeSec=1694359799, self.tradeDate='20230910', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25758.6', self.close='25736'
127.0.0.1 - - [10/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17211 

self.closeSec=1694360399, self.tradeDate='20230910', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25736', self.close='25767.4'
127.0.0.1 - - [10/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17212 

self.closeSec=1694360999, self.tradeDate='20230910', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25767.4', self.close='25763.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17213 

self.closeSec=1694361599, self.tradeDate='20230910', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25763.1', self.close='25764'
127.0.0.1 - - [11/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17214 

self.closeSec=1694362199, self.tradeDate='20230911', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25764.1', self.close='25763.9'
127.0.0.1 - - [11/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17215 

self.closeSec=1694362799, self.tradeDate='20230911', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25763.9', self.close='25774.2'
127.0.0.1 - - [11/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34420
self.closeSec=1694362799, self.tradeDate='20230911', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25765.0, self.close=25774.2, self.high=25779.1, self.low=25760.5, self.vol=348.539, self.amt=8982941.9607 
127.0.0.1 - - [11/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-11 00:20:06,231:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230910   235500    235959  ...         0.0        0.0       0
5760  20230911   000000    000459  ...         0.0        0.0       0
5761  20230911   000500    000959  ...         0.0        0.0       0
5762  20230911   001000    001459  ...         0.0        0.0       0
5763  20230911   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 00:20:06,233:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694362799, self.tradeDate='20230911', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25765.0, self.close=25774.2, self.high=25779.1, self.low=25760.5, self.vol=348.539, self.amt=8982941.9607, ukdf['pct'].iloc[-1]=0.000357 , ukdf['amount'].iloc[-1]=8982941.9607, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-39685.41216077347', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25775.49317033', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [11/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34421
self.closeSec=1694363099, self.tradeDate='20230911', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25774.3, self.close=25757.1, self.high=25774.3, self.low=25757.0, self.vol=223.448, self.amt=5757185.5366 
2023-09-11 00:25:00,817:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230911   000000    000459  ...         0.0        0.0       0
5761  20230911   000500    000959  ...         0.0        0.0       0
5762  20230911   001000    001459  ...         0.0        0.0       0
5763  20230911   001500    001959  ...         0.0        0.0       0
5764  20230911   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 00:25:00,818:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694363099, self.tradeDate='20230911', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25774.3, self.close=25757.1, self.high=25774.3, self.low=25757.0, self.vol=223.448, self.amt=5757185.5366, ukdf['pct'].iloc[-1]=-0.000663 , ukdf['amount'].iloc[-1]=5757185.5366, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-40368.5529', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25757.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230910   120000    155959  1694332799  ...    723  0.113988 -0.792834    -1.0
724  20230910   160000    195959  1694347199  ...    724  0.106684 -0.811072    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '6197.58446660649', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25783.90703663', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [11/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=717
self.closeSec=1694361599, self.tradeDate='20230910', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25783.0, self.close=25764.0, self.high=25827.0, self.low=25702.0, self.vol=23274.67, self.amt=599783305.88966 
2023-09-11 00:00:01,545:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694361599, self.tradeDate='20230910', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25783.0, self.close=25764.0, self.high=25827.0, self.low=25702.0, self.vol=23274.67, self.amt=599783305.88966 
2023-09-11 00:00:01,571:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230910   040000    075959  ...   6773.836  1.752851e+08  0.001338
722  20230910   080000    115959  ...  10214.867  2.640082e+08 -0.001603
723  20230910   120000    155959  ...  21004.581  5.421424e+08 -0.000313
724  20230910   160000    195959  ...  13734.798  3.546014e+08 -0.002326
725  20230910   200000    235959  ...  23274.670  5.997833e+08 -0.000733

[5 rows x 11 columns]
2023-09-11 00:00:02,317:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230910   040000    075959  1694303999  ...    721  0.125757 -0.764330    -1.0
722  20230910   080000    115959  1694318399  ...    722  0.111707 -0.801232    -1.0
723  20230910   120000    155959  1694332799  ...    723  0.113988 -0.792834    -1.0
724  20230910   160000    195959  1694347199  ...    724  0.106684 -0.811072    -1.0
725  20230910   200000    235959  1694361599  ...    725  0.105012 -0.813227    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '7330.0914', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25764.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


