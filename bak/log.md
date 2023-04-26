# 20230427 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43317
self.closeSec=1682525999, self.tradeDate='20230427', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29812.1, self.close=29739.3, self.high=29812.6, self.low=29722.0, self.vol=4115.265, self.amt=122514198.4129 
127.0.0.1 - - [27/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-27 00:20:06,081:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230426   235500    235959  ...         0.0        0.0       0
5753  20230427   000000    000459  ...         0.0        0.0       0
5754  20230427   000500    000959  ...         0.0        0.0       0
5755  20230427   001000    001459  ...         0.0        0.0       0
5756  20230427   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 00:20:06,091:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682525999, self.tradeDate='20230427', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29812.1, self.close=29739.3, self.high=29812.6, self.low=29722.0, self.vol=4115.265, self.amt=122514198.4129, ukdf['pct'].iloc[-1]=-0.002442 , ukdf['amount'].iloc[-1]=122514198.4129, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-795496.632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29748.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43318
self.closeSec=1682526299, self.tradeDate='20230427', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29739.2, self.close=29820.4, self.high=29821.4, self.low=29719.8, self.vol=3898.398, self.amt=116051682.8099 
127.0.0.1 - - [27/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-27 00:25:01,576:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230427   000000    000459  ...         0.0        0.0       0
5754  20230427   000500    000959  ...         0.0        0.0       0
5755  20230427   001000    001459  ...         0.0        0.0       0
5756  20230427   001500    001959  ...         0.0        0.0       0
5757  20230427   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 00:25:01,576:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682526299, self.tradeDate='20230427', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29739.2, self.close=29820.4, self.high=29821.4, self.low=29719.8, self.vol=3898.398, self.amt=116051682.8099, ukdf['pct'].iloc[-1]=0.002727 , ukdf['amount'].iloc[-1]=116051682.8099, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-799811.2512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29820.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [27/Apr/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230422' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43881 

self.closeSec=1682525399, self.tradeDate='20230427', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29803.1, self.close=29869.4, self.high=29899.0, self.low=29800.0 
127.0.0.1 - - [27/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43882 

self.closeSec=1682525699, self.tradeDate='20230427', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29869.4, self.close=29812.1, self.high=29871.2, self.low=29801.0 
127.0.0.1 - - [27/Apr/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43883 

self.closeSec=1682525999, self.tradeDate='20230427', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29812.1, self.close=29739.3, self.high=29812.6, self.low=29722.0 
127.0.0.1 - - [27/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43884 

self.closeSec=1682526299, self.tradeDate='20230427', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29739.2, self.close=29820.4, self.high=29821.4, self.low=29719.8 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-27 00:00:20,489:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230426    212959  29955.1  ...  55.000000  0.725751  0.120047
5802  20230426    215959  29822.2  ...  55.416667  0.726808  0.117479
5803  20230426    222959  29837.4  ...  55.000000  0.691510  0.120171
5804  20230426    225959  29639.9  ...  55.416667  0.695175  0.121450
5805  20230426    232959  29687.9  ...  55.416667  0.695391  0.122684

[5 rows x 33 columns]
0.5606617647058824
acc is : 0.5606617647058824
2023-04-27 00:00:20,582:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.517812  0.482188       1  ...  0.918106   1.0    0.0  0.980958
540     0  0.548688  0.451312       0  ...  0.912032   1.0    0.0  0.974468
541     1  0.495357  0.504643       1  ...  0.913505   1.0    0.0  0.976043
542     1  0.487134  0.512866       1  ...  0.913592   1.0    0.0  0.976135
543     1  0.462233  0.537767       1  ...  0.917047   1.0    0.0  0.979827

[5 rows x 10 columns]
2023-04-27 00:00:20,604:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518138  0.481862       1  ...  0.918106   1.0    0.0  0.982308
46     0  0.548662  0.451338       0  ...  0.912032   1.0    0.0  0.975757
47     1  0.494969  0.505031       1  ...  0.913505   1.0    0.0  0.975934
48     1  0.486241  0.513759       1  ...  0.913592   1.0    0.0  0.976026
49     1  0.462233  0.537767       1  ...  0.917047   1.0    0.0  0.979827

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [26/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21937 

self.closeSec=1682522999, self.tradeDate='20230426', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29730.1', self.close='29690.7'
127.0.0.1 - - [26/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21938 

self.closeSec=1682523599, self.tradeDate='20230426', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29690.8', self.close='29738.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21939 

self.closeSec=1682524199, self.tradeDate='20230426', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29738.1', self.close='29809.9'
127.0.0.1 - - [26/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21940 

self.closeSec=1682524799, self.tradeDate='20230426', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29809.8', self.close='29803'
127.0.0.1 - - [27/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21941 

self.closeSec=1682525399, self.tradeDate='20230427', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29803.1', self.close='29869.4'
127.0.0.1 - - [27/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21942 

self.closeSec=1682525999, self.tradeDate='20230427', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29869.4', self.close='29739.3'
127.0.0.1 - - [27/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [26/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21938 

self.closeSec=1682522999, self.tradeDate='20230426', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29730.1', self.close='29690.7'
127.0.0.1 - - [26/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21939 

self.closeSec=1682523599, self.tradeDate='20230426', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29690.8', self.close='29738.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21940127.0.0.1 - - [26/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -
 

self.closeSec=1682524199, self.tradeDate='20230426', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29738.1', self.close='29809.9'
127.0.0.1 - - [27/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21941 

self.closeSec=1682524799, self.tradeDate='20230426', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29809.8', self.close='29803'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21942 

self.closeSec=1682525399, self.tradeDate='20230427', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29803.1', self.close='29869.4'
127.0.0.1 - - [27/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21943 

self.closeSec=1682525999, self.tradeDate='20230427', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29869.4', self.close='29739.3'
127.0.0.1 - - [27/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21938 

self.closeSec=1682522999, self.tradeDate='20230426', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29730.1', self.close='29690.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21939 

self.closeSec=1682523599, self.tradeDate='20230426', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29690.8', self.close='29738.2'
127.0.0.1 - - [26/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21940 

self.closeSec=1682524199, self.tradeDate='20230426', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29738.1', self.close='29809.9'
127.0.0.1 - - [26/Apr/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21941 

self.closeSec=1682524799, self.tradeDate='20230426', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29809.8', self.close='29803'
127.0.0.1 - - [27/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21942 

self.closeSec=1682525399, self.tradeDate='20230427', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29803.1', self.close='29869.4'
127.0.0.1 - - [27/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21943 

self.closeSec=1682525999, self.tradeDate='20230427', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29869.4', self.close='29739.3'
127.0.0.1 - - [27/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39315
self.closeSec=1682525999, self.tradeDate='20230427', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29812.1, self.close=29739.3, self.high=29812.6, self.low=29722.0, self.vol=4115.265, self.amt=122514198.4129 
127.0.0.1 - - [27/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-27 00:20:06,062:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230426   235500    235959  ...         0.0        0.0       0
5753  20230427   000000    000459  ...         0.0        0.0       0
5754  20230427   000500    000959  ...         0.0        0.0       0
5755  20230427   001000    001459  ...         0.0        0.0       0
5756  20230427   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 00:20:06,072:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682525999, self.tradeDate='20230427', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29812.1, self.close=29739.3, self.high=29812.6, self.low=29722.0, self.vol=4115.265, self.amt=122514198.4129, ukdf['pct'].iloc[-1]=-0.002442 , ukdf['amount'].iloc[-1]=122514198.4129, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [27/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39316
self.closeSec=1682526299, self.tradeDate='20230427', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29739.2, self.close=29820.4, self.high=29821.4, self.low=29719.8, self.vol=3898.398, self.amt=116051682.8099 
2023-04-27 00:25:01,574:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230427   000000    000459  ...         0.0        0.0       0
5754  20230427   000500    000959  ...         0.0        0.0       0
5755  20230427   001000    001459  ...         0.0        0.0       0
5756  20230427   001500    001959  ...         0.0        0.0       0
5757  20230427   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 00:25:01,574:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682526299, self.tradeDate='20230427', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29739.2, self.close=29820.4, self.high=29821.4, self.low=29719.8, self.vol=3898.398, self.amt=116051682.8099, ukdf['pct'].iloc[-1]=0.002727 , ukdf['amount'].iloc[-1]=116051682.8099, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-04-26 20:00:10,741:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42147F1682510405429I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682510405522707, 'quantity': '52.48', 'price': '28949.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1682510404897, 'updatetime': 1682510405522, 'tradetype': 'usdt', 'selfid': 42147, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682510405522, 'clientorderid': '42147F1682510405429I0L65', 'price': '28949.9', 'quantity': '52.48', 'commission': '1519.290752', 'commissionasset': 'USDT', 'tradetime': 1682510405522, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682510405522}], 'gatetype': 'simulator', 'handletime': 0}
2023-04-26 20:00:10,741:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42147F1682510405429I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682510405522707, 'quantity': '52.48', 'price': '28949.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1682510404897, 'updatetime': 1682510405522, 'tradetype': 'usdt', 'selfid': 42147, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682510405522, 'clientorderid': '42147F1682510405429I0L65', 'price': '28949.9', 'quantity': '52.48', 'commission': '1519.290752', 'commissionasset': 'USDT', 'tradetime': 1682510405522, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682510405522}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Apr/2023 20:00:10] "POST / HTTP/1.1" 200 -
2023-04-26 20:00:10,864:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42148F1682510410716I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682510410817791, 'quantity': '46.779', 'price': '28948.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1682510410537, 'updatetime': 1682510410817, 'tradetype': 'usdt', 'selfid': 42148, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682510410817, 'clientorderid': '42148F1682510410716I0L65', 'price': '28948.5', 'quantity': '46.779', 'commission': '1354.1818815', 'commissionasset': 'USDT', 'tradetime': 1682510410817, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682510410817}], 'gatetype': 'simulator', 'handletime': 0}
2023-04-26 20:00:11,047:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42148F1682510410716I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1682510410817791, 'quantity': '46.779', 'price': '28948.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1682510410537, 'updatetime': 1682510410817, 'tradetype': 'usdt', 'selfid': 42148, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1682510410817, 'clientorderid': '42148F1682510410716I0L65', 'price': '28948.5', 'quantity': '46.779', 'commission': '1354.1818815', 'commissionasset': 'USDT', 'tradetime': 1682510410817, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1682510410817}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Apr/2023 20:00:11] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1352827.6996185002, self.flagDict['side']='buy', self.tradeCount=32, self.count=914
self.closeSec=1682524799, self.tradeDate='20230426', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28940.7, self.close=29803.0, self.high=30048.2, self.low=28940.6, self.vol=306318.812, self.amt=9088141068.81204 
127.0.0.1 - - [27/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-27 00:00:03,139:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682524799, self.tradeDate='20230426', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28940.7, self.close=29803.0, self.high=30048.2, self.low=28940.6, self.vol=306318.812, self.amt=9088141068.81204 
2023-04-27 00:00:03,180:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230426   040000    075959  ...  162175.001  4.557367e+09  0.025025
722  20230426   080000    115959  ...   71407.185  2.024510e+09  0.000336
723  20230426   120000    155959  ...   62803.722  1.782336e+09  0.002431
724  20230426   160000    195959  ...  213528.425  6.150918e+09  0.020296
725  20230426   200000    235959  ...  306318.812  9.088141e+09  0.029795

[5 rows x 11 columns]
2023-04-27 00:00:04,962:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230426   040000    075959  1682467199  ...    721  0.718385 -0.013986     NaN
722  20230426   080000    115959  1682481599  ...    722  0.644339 -0.197825     NaN
723  20230426   120000    155959  1682495999  ...    723  0.687079 -0.037325     NaN
724  20230426   160000    195959  1682510399  ...    724  0.966401  0.887644     1.0
725  20230426   200000    235959  1682524799  ...    725  1.365592  2.168048     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '40220.5842', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29808.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


