# 20230426 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43029
self.closeSec=1682439599, self.tradeDate='20230426', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27338.5, self.close=27368.0, self.high=27370.0, self.low=27305.1, self.vol=1318.997, self.amt=36068191.2022 
127.0.0.1 - - [26/Apr/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-04-26 00:20:03,931:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230425   235500    235959  ...         0.0        0.0       0
5753  20230426   000000    000459  ...         0.0        0.0       0
5754  20230426   000500    000959  ...         0.0        0.0       0
5755  20230426   001000    001459  ...         0.0        0.0       0
5756  20230426   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 00:20:03,940:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682439599, self.tradeDate='20230426', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27338.5, self.close=27368.0, self.high=27370.0, self.low=27305.1, self.vol=1318.997, self.amt=36068191.2022, ukdf['pct'].iloc[-1]=0.001079 , ukdf['amount'].iloc[-1]=36068191.2022, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-652375.3830227296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27370.4224246', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43030
self.closeSec=1682439899, self.tradeDate='20230426', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27368.0, self.close=27389.3, self.high=27406.8, self.low=27368.0, self.vol=2411.184, self.amt=66041428.7928 
127.0.0.1 - - [26/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-26 00:25:01,556:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230426   000000    000459  ...         0.0        0.0       0
5754  20230426   000500    000959  ...         0.0        0.0       0
5755  20230426   001000    001459  ...         0.0        0.0       0
5756  20230426   001500    001959  ...         0.0        0.0       0
5757  20230426   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 00:25:01,556:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682439899, self.tradeDate='20230426', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27368.0, self.close=27389.3, self.high=27406.8, self.low=27368.0, self.vol=2411.184, self.amt=66041428.7928, ukdf['pct'].iloc[-1]=0.000778 , ukdf['amount'].iloc[-1]=66041428.7928, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-653585.22771168928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27390.52752778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [26/Apr/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230421' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [26/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43593 

self.closeSec=1682438999, self.tradeDate='20230426', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27309.7, self.close=27328.5, self.high=27344.7, self.low=27306.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43594 

self.closeSec=1682439299, self.tradeDate='20230426', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27328.4, self.close=27338.5, self.high=27346.4, self.low=27318.0 
127.0.0.1 - - [26/Apr/2023 00:15:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43595 

self.closeSec=1682439599, self.tradeDate='20230426', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27338.5, self.close=27368.0, self.high=27370.0, self.low=27305.1 

--handleKline--: 127.0.0.1 - - [26/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43596 

self.closeSec=1682439899, self.tradeDate='20230426', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27368.0, self.close=27389.3, self.high=27406.8, self.low=27368.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-26 00:00:19,618:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230425    212959  27383.5  ...  52.083333  0.486859  0.427793
5802  20230425    215959  27388.9  ...  51.666667  0.476491  0.440404
5803  20230425    222959  27332.6  ...  51.666667  0.468125  0.459758
5804  20230425    225959  27286.2  ...  51.666667  0.467005  0.478837
5805  20230425    232959  27280.1  ...  52.083333  0.480350  0.485964

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-04-26 00:00:19,769:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.515416  0.484584       0  ...  0.863637   1.0    0.0  0.889154
540     1  0.498438  0.501562       0  ...  0.862174   1.0    0.0  0.887648
541     1  0.491540  0.508460       0  ...  0.861978   1.0    0.0  0.887446
542     1  0.495489  0.504511       1  ...  0.864038   1.0    0.0  0.889567
543     0  0.517598  0.482402       0  ...  0.863542   1.0    0.0  0.889056

[5 rows x 10 columns]
2023-04-26 00:00:19,805:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515134  0.484866       0  ...  0.863637   1.0    0.0  0.887278
46     1  0.498130  0.501870       0  ...  0.862174   1.0    0.0  0.881935
47     1  0.491483  0.508517       0  ...  0.861978   1.0    0.0  0.881866
48     1  0.495421  0.504579       1  ...  0.864038   1.0    0.0  0.883974
49     0  0.517598  0.482402       0  ...  0.863542   1.0    0.0  0.889056

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21793 

self.closeSec=1682436599, self.tradeDate='20230425', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27390.2', self.close='27345.2'
127.0.0.1 - - [25/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21794 

self.closeSec=1682437199, self.tradeDate='20230425', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27345.1', self.close='27324.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21795 

self.closeSec=1682437799, self.tradeDate='20230425', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27324.2', self.close='27331.8'
127.0.0.1 - - [25/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21796 

self.closeSec=1682438399, self.tradeDate='20230425', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27331.7', self.close='27329.5'
127.0.0.1 - - [26/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21797 

self.closeSec=1682438999, self.tradeDate='20230426', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27329.5', self.close='27328.5'
127.0.0.1 - - [26/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21798 

self.closeSec=1682439599, self.tradeDate='20230426', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27328.4', self.close='27368'
127.0.0.1 - - [26/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [25/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21794 

self.closeSec=1682436599, self.tradeDate='20230425', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27390.2', self.close='27345.2'

--handleKline--: 127.0.0.1 - - [25/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21795 

self.closeSec=1682437199, self.tradeDate='20230425', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27345.1', self.close='27324.2'
127.0.0.1 - - [25/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21796 

self.closeSec=1682437799, self.tradeDate='20230425', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27324.2', self.close='27331.8'
127.0.0.1 - - [26/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21797 

self.closeSec=1682438399, self.tradeDate='20230425', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27331.7', self.close='27329.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21798 

self.closeSec=1682438999, self.tradeDate='20230426', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27329.5', self.close='27328.5'
127.0.0.1 - - [26/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21799 

self.closeSec=1682439599, self.tradeDate='20230426', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27328.4', self.close='27368'
127.0.0.1 - - [26/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21794 

self.closeSec=1682436599, self.tradeDate='20230425', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27390.2', self.close='27345.2'
127.0.0.1 - - [25/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21795 

self.closeSec=1682437199, self.tradeDate='20230425', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27345.1', self.close='27324.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21796 

self.closeSec=1682437799, self.tradeDate='20230425', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27324.2', self.close='27331.8'
127.0.0.1 - - [25/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21797 

self.closeSec=1682438399, self.tradeDate='20230425', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27331.7', self.close='27329.5'
127.0.0.1 - - [26/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21798 

self.closeSec=1682438999, self.tradeDate='20230426', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27329.5', self.close='27328.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21799 

self.closeSec=1682439599, self.tradeDate='20230426', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27328.4', self.close='27368'
127.0.0.1 - - [26/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39027
self.closeSec=1682439599, self.tradeDate='20230426', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27338.5, self.close=27368.0, self.high=27370.0, self.low=27305.1, self.vol=1318.997, self.amt=36068191.2022 
127.0.0.1 - - [26/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-04-26 00:20:05,156:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230425   235500    235959  ...         0.0        0.0       0
5753  20230426   000000    000459  ...         0.0        0.0       0
5754  20230426   000500    000959  ...         0.0        0.0       0
5755  20230426   001000    001459  ...         0.0        0.0       0
5756  20230426   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 00:20:05,158:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682439599, self.tradeDate='20230426', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27338.5, self.close=27368.0, self.high=27370.0, self.low=27305.1, self.vol=1318.997, self.amt=36068191.2022, ukdf['pct'].iloc[-1]=0.001079 , ukdf['amount'].iloc[-1]=36068191.2022, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39028
self.closeSec=1682439899, self.tradeDate='20230426', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27368.0, self.close=27389.3, self.high=27406.8, self.low=27368.0, self.vol=2411.184, self.amt=66041428.7928 
2023-04-26 00:25:01,560:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230426   000000    000459  ...         0.0        0.0       0
5754  20230426   000500    000959  ...         0.0        0.0       0
5755  20230426   001000    001459  ...         0.0        0.0       0
5756  20230426   001500    001959  ...         0.0        0.0       0
5757  20230426   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 00:25:01,560:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682439899, self.tradeDate='20230426', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27368.0, self.close=27389.3, self.high=27406.8, self.low=27368.0, self.vol=2411.184, self.amt=66041428.7928, ukdf['pct'].iloc[-1]=0.000778 , ukdf['amount'].iloc[-1]=66041428.7928, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-04-25 20:00:10,785:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42145F1682424005467I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682424005553064, 'quantity': '52.515', 'price': '27388.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1682424005077, 'updatetime': 1682424005553, 'tradetype': 'usdt', 'selfid': 42145, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682424005553, 'clientorderid': '42145F1682424005467I0L65', 'price': '27388.7', 'quantity': '52.515', 'commission': '1438.3175805', 'commissionasset': 'USDT', 'tradetime': 1682424005553, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682424005553}], 'gatetype': 'simulator', 'handletime': 0}
2023-04-25 20:00:10,785:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42145F1682424005467I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682424005553064, 'quantity': '52.515', 'price': '27388.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1682424005077, 'updatetime': 1682424005553, 'tradetype': 'usdt', 'selfid': 42145, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682424005553, 'clientorderid': '42145F1682424005467I0L65', 'price': '27388.7', 'quantity': '52.515', 'commission': '1438.3175805', 'commissionasset': 'USDT', 'tradetime': 1682424005553, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682424005553}], 'gatetype': 'simulator', 'handletime': 0}
2023-04-25 20:00:10,912:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42146F1682424010762I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682424010865980, 'quantity': '52.48', 'price': '27388.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1682424010576, 'updatetime': 1682424010865, 'tradetype': 'usdt', 'selfid': 42146, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682424010865, 'clientorderid': '42146F1682424010762I0L65', 'price': '27388.7', 'quantity': '52.48', 'commission': '1437.358976', 'commissionasset': 'USDT', 'tradetime': 1682424010865, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682424010865}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Apr/2023 20:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-04-25 20:00:11,095:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42146F1682424010762I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682424010865980, 'quantity': '52.48', 'price': '27388.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1682424010576, 'updatetime': 1682424010865, 'tradetype': 'usdt', 'selfid': 42146, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682424010865, 'clientorderid': '42146F1682424010762I0L65', 'price': '27388.7', 'quantity': '52.48', 'commission': '1437.358976', 'commissionasset': 'USDT', 'tradetime': 1682424010865, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682424010865}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1435921.617024, self.flagDict['side']='sell', self.tradeCount=31, self.count=908
self.closeSec=1682438399, self.tradeDate='20230425', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27382.2, self.close=27329.5, self.high=27466.0, self.low=27200.0, self.vol=74964.782, self.amt=2049647720.5968 
2023-04-26 00:00:01,799:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682438399, self.tradeDate='20230425', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27382.2, self.close=27329.5, self.high=27466.0, self.low=27200.0, self.vol=74964.782, self.amt=2049647720.5968 
2023-04-26 00:00:01,850:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230425   040000    075959  ...  37313.066  1.023684e+09  0.004519
722  20230425   080000    115959  ...  43907.361  1.204137e+09 -0.005815
723  20230425   120000    155959  ...  45282.567  1.238376e+09 -0.003120
724  20230425   160000    195959  ...  66538.637  1.818263e+09  0.004763
725  20230425   200000    235959  ...  74964.782  2.049648e+09 -0.001921

[5 rows x 11 columns]
2023-04-26 00:00:03,763:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230425   040000    075959  1682380799  ...    721  0.628881 -0.321602     NaN
722  20230425   080000    115959  1682395199  ...    722  0.589595 -0.430115     NaN
723  20230425   120000    155959  1682409599  ...    723  0.571203 -0.484200     NaN
724  20230425   160000    195959  1682423999  ...    724  0.469231 -0.754624    -1.0
725  20230425   200000    235959  1682438399  ...    725  0.399294 -0.928003    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.48', 'enterprice': '27388.7', 'countrevence': '0', 'unrealprofit': '2912.1072865408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27333.21015079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


