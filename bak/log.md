# 20230913 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34996
self.closeSec=1694535599, self.tradeDate='20230913', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26150.8, self.close=26166.3, self.high=26167.9, self.low=26136.6, self.vol=1053.915, self.amt=27561042.6828 
127.0.0.1 - - [13/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-13 00:20:06,132:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230912   235500    235959  ...         0.0        0.0       0
5760  20230913   000000    000459  ...         0.0        0.0       0
5761  20230913   000500    000959  ...         0.0        0.0       0
5762  20230913   001000    001459  ...         0.0        0.0       0
5763  20230913   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 00:20:06,135:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694535599, self.tradeDate='20230913', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26150.8, self.close=26166.3, self.high=26167.9, self.low=26136.6, self.vol=1053.915, self.amt=27561042.6828, ukdf['pct'].iloc[-1]=0.000593 , ukdf['amount'].iloc[-1]=27561042.6828, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9716.1702', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26167.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34997
self.closeSec=1694535899, self.tradeDate='20230913', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26166.2, self.close=26214.2, self.high=26258.7, self.low=26160.0, self.vol=3732.987, self.amt=97882486.5869 
2023-09-13 00:25:00,800:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230913   000000    000459  ...         0.0        0.0       0
5761  20230913   000500    000959  ...         0.0        0.0       0
5762  20230913   001000    001459  ...         0.0        0.0       0
5763  20230913   001500    001959  ...         0.0        0.0       0
5764  20230913   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 00:25:00,800:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694535899, self.tradeDate='20230913', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26166.2, self.close=26214.2, self.high=26258.7, self.low=26160.0, self.vol=3732.987, self.amt=97882486.5869, ukdf['pct'].iloc[-1]=0.001831 , ukdf['amount'].iloc[-1]=97882486.5869, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9029.6184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26216.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [13/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230908' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [13/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34996 

self.closeSec=1694534999, self.tradeDate='20230913', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26203.9, self.close=26175.7, self.high=26249.9, self.low=26170.9 
127.0.0.1 - - [13/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34997 

self.closeSec=1694535299, self.tradeDate='20230913', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26174.0, self.close=26150.8, self.high=26192.0, self.low=26145.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34998 

self.closeSec=1694535599, self.tradeDate='20230913', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26150.8, self.close=26166.3, self.high=26167.9, self.low=26136.6 
127.0.0.1 - - [13/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34999 

self.closeSec=1694535899, self.tradeDate='20230913', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26166.2, self.close=26214.2, self.high=26258.7, self.low=26160.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-13 00:00:19,548:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230912    212959  26111.1  ...  50.000000  0.572094  0.295875
5802  20230912    215959  26075.1  ...  50.416667  0.597703  0.279491
5803  20230912    222959  26258.6  ...  50.000000  0.574290  0.272384
5804  20230912    225959  26136.0  ...  49.583333  0.568044  0.267241
5805  20230912    232959  26097.3  ...  50.000000  0.579024  0.258941

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-09-13 00:00:19,618:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.470894  0.529106       1  ...  0.996756   1.0    0.0  1.010910
540     0  0.533941  0.466059       0  ...  0.992106   1.0    0.0  1.006194
541     1  0.456097  0.543903       0  ...  0.990827   1.0    0.0  1.004897
542     1  0.471071  0.528929       1  ...  0.993833   1.0    0.0  1.007946
543     0  0.505021  0.494979       1  ...  0.994239   1.0    0.0  1.008358

[5 rows x 10 columns]
2023-09-13 00:00:19,631:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.471396  0.528604       1  ...  0.996756   1.0    0.0  1.009748
46     0  0.534228  0.465772       0  ...  0.992106   1.0    0.0  1.005792
47     1  0.456084  0.543916       0  ...  0.990827   1.0    0.0  1.004940
48     1  0.471069  0.528931       1  ...  0.993833   1.0    0.0  1.007989
49     0  0.505021  0.494979       1  ...  0.994239   1.0    0.0  1.008358

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.233', 'enterprice': '25817.5', 'countrevence': '0', 'unrealprofit': '10775.00624379327', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26199.14581319', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [12/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17495 

self.closeSec=1694532599, self.tradeDate='20230912', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26140', self.close='26181.6'
127.0.0.1 - - [12/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17496 

self.closeSec=1694533199, self.tradeDate='20230912', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26179.9', self.close='26209.9'
127.0.0.1 - - [12/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17497 

self.closeSec=1694533799, self.tradeDate='20230912', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26209.9', self.close='26172.6'
127.0.0.1 - - [13/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17498 

self.closeSec=1694534399, self.tradeDate='20230912', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26172.6', self.close='26192.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17499 

self.closeSec=1694534999, self.tradeDate='20230913', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26192.3', self.close='26174'
127.0.0.1 - - [13/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17500 

self.closeSec=1694535599, self.tradeDate='20230913', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26174', self.close='26166.2'
127.0.0.1 - - [13/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17498 

self.closeSec=1694532599, self.tradeDate='20230912', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26140', self.close='26181.6'
127.0.0.1 - - [12/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17499 

self.closeSec=1694533199, self.tradeDate='20230912', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26179.9', self.close='26209.9'
127.0.0.1 - - [12/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17500 

self.closeSec=1694533799, self.tradeDate='20230912', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26209.9', self.close='26172.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17501 

self.closeSec=1694534399, self.tradeDate='20230912', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26172.6', self.close='26192.3'
127.0.0.1 - - [13/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17502 

self.closeSec=1694534999, self.tradeDate='20230913', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26192.3', self.close='26174'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17503 

self.closeSec=1694535599, self.tradeDate='20230913', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26174', self.close='26166.2'
127.0.0.1 - - [13/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [12/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17498 

self.closeSec=1694532599, self.tradeDate='20230912', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26140', self.close='26181.6'

--handleKline--: 127.0.0.1 - - [12/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17499 

self.closeSec=1694533199, self.tradeDate='20230912', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26179.9', self.close='26209.9'
127.0.0.1 - - [12/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17500 

self.closeSec=1694533799, self.tradeDate='20230912', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26209.9', self.close='26172.6'
127.0.0.1 - - [13/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17501 

self.closeSec=1694534399, self.tradeDate='20230912', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26172.6', self.close='26192.3'
127.0.0.1 - - [13/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17502 

self.closeSec=1694534999, self.tradeDate='20230913', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26192.3', self.close='26174'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17503 

self.closeSec=1694535599, self.tradeDate='20230913', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26174', self.close='26166.2'
127.0.0.1 - - [13/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34996
self.closeSec=1694535599, self.tradeDate='20230913', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26150.8, self.close=26166.3, self.high=26167.9, self.low=26136.6, self.vol=1053.915, self.amt=27561042.6828 
127.0.0.1 - - [13/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-13 00:20:06,134:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230912   235500    235959  ...         0.0        0.0       0
5760  20230913   000000    000459  ...         0.0        0.0       0
5761  20230913   000500    000959  ...         0.0        0.0       0
5762  20230913   001000    001459  ...         0.0        0.0       0
5763  20230913   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 00:20:06,146:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694535599, self.tradeDate='20230913', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26150.8, self.close=26166.3, self.high=26167.9, self.low=26136.6, self.vol=1053.915, self.amt=27561042.6828, ukdf['pct'].iloc[-1]=0.000593 , ukdf['amount'].iloc[-1]=27561042.6828, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-25137.0288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26167.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34997
self.closeSec=1694535899, self.tradeDate='20230913', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26166.2, self.close=26214.2, self.high=26258.7, self.low=26160.0, self.vol=3732.987, self.amt=97882486.5869 
127.0.0.1 - - [13/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-13 00:25:00,797:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230913   000000    000459  ...         0.0        0.0       0
5761  20230913   000500    000959  ...         0.0        0.0       0
5762  20230913   001000    001459  ...         0.0        0.0       0
5763  20230913   001500    001959  ...         0.0        0.0       0
5764  20230913   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 00:25:00,798:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694535899, self.tradeDate='20230913', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26166.2, self.close=26214.2, self.high=26258.7, self.low=26160.0, self.vol=3732.987, self.amt=97882486.5869, ukdf['pct'].iloc[-1]=0.001831 , ukdf['amount'].iloc[-1]=97882486.5869, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-23305.9775', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26216.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230912   120000    155959  1694505599  ...    723  0.150643 -0.666047    -1.0
724  20230912   160000    195959  1694519999  ...    724  0.104921 -0.794423    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-11269.5867', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26089.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [13/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=729
self.closeSec=1694534399, self.tradeDate='20230912', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26087.2, self.close=26192.3, self.high=26397.0, self.low=26021.0, self.vol=104596.895, self.amt=2736354076.077 
2023-09-13 00:00:01,585:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694534399, self.tradeDate='20230912', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26087.2, self.close=26192.3, self.high=26397.0, self.low=26021.0, self.vol=104596.895, self.amt=2736354076.077 
2023-09-13 00:00:01,603:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230912   040000    075959  ...   41241.175  1.034585e+09  0.005682
722  20230912   080000    115959  ...  109017.062  2.787754e+09  0.025355
723  20230912   120000    155959  ...   95929.589  2.472843e+09  0.000857
724  20230912   160000    195959  ...  107772.154  2.806439e+09  0.010709
725  20230912   200000    235959  ...  104596.895  2.736354e+09  0.004052

[5 rows x 11 columns]
2023-09-13 00:00:02,276:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230912   040000    075959  1694476799  ...    721  0.312324 -0.219917     NaN
722  20230912   080000    115959  1694491199  ...    722  0.202304 -0.523436     NaN
723  20230912   120000    155959  1694505599  ...    723  0.150643 -0.666047    -1.0
724  20230912   160000    195959  1694519999  ...    724  0.104921 -0.794423    -1.0
725  20230912   200000    235959  1694534399  ...    725  0.154263 -0.664905    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-17153.1', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26192.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


