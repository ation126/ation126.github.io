# 20230414 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39573
self.closeSec=1681402799, self.tradeDate='20230414', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30343.0, self.close=30350.2, self.high=30357.9, self.low=30340.7, self.vol=1012.398, self.amt=30728036.5368 
127.0.0.1 - - [14/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-14 00:20:08,094:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230413   235500    235959  ...         0.0        0.0       0
5753  20230414   000000    000459  ...         0.0        0.0       0
5754  20230414   000500    000959  ...         0.0        0.0       0
5755  20230414   001000    001459  ...         0.0        0.0       0
5756  20230414   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 00:20:08,103:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681402799, self.tradeDate='20230414', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30343.0, self.close=30350.2, self.high=30357.9, self.low=30340.7, self.vol=1012.398, self.amt=30728036.5368, ukdf['pct'].iloc[-1]=0.000237 , ukdf['amount'].iloc[-1]=30728036.5368, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-831878.026837068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30353.38313675', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39574
self.closeSec=1681403099, self.tradeDate='20230414', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30350.1, self.close=30330.0, self.high=30350.4, self.low=30318.0, self.vol=1292.648, self.amt=39210630.4678 
2023-04-14 00:25:01,654:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230414   000000    000459  ...         0.0        0.0       0
5754  20230414   000500    000959  ...         0.0        0.0       0
5755  20230414   001000    001459  ...         0.0        0.0       0
5756  20230414   001500    001959  ...         0.0        0.0       0
5757  20230414   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 00:25:01,655:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681403099, self.tradeDate='20230414', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30350.1, self.close=30330.0, self.high=30350.4, self.low=30318.0, self.vol=1292.648, self.amt=39210630.4678, ukdf['pct'].iloc[-1]=-0.000666 , ukdf['amount'].iloc[-1]=39210630.4678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-830476.9408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30330.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
451  20230410   133500    133959  1681105199  ...  28220.3  0.000011   1603    1
452  20230410   134000    134459  1681105499  ...  28232.1  0.001654   1604    2
453  20230410   134500    134959  1681105799  ...  28265.5 -0.000453   1605    3
454  20230410   135000    135459  1681106099  ...  28251.1  0.000340   1606    4
455  20230410   135500    135959  1681106399  ...  28268.0 -0.000141   1607    5

[5 rows x 11 columns] 

127.0.0.1 - - [14/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40137 

self.closeSec=1681402199, self.tradeDate='20230414', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=30398.9, self.close=30382.3, self.high=30436.0, self.low=30377.0 
127.0.0.1 - - [14/Apr/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40138 

self.closeSec=1681402499, self.tradeDate='20230414', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=30382.2, self.close=30343.0, self.high=30385.1, self.low=30327.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40139 

self.closeSec=1681402799, self.tradeDate='20230414', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30343.0, self.close=30350.2, self.high=30357.9, self.low=30340.7 
127.0.0.1 - - [14/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40140 

self.closeSec=1681403099, self.tradeDate='20230414', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30350.1, self.close=30330.0, self.high=30350.4, self.low=30318.0 
127.0.0.1 - - [14/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-14 00:00:34,006:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5801  20230413    212959  30258.9  ...    53.75  0.566705  0.399738
5802  20230413    215959  30243.2  ...    53.75  0.548791  0.394647
5803  20230413    222959  30164.3  ...    53.75  0.570845  0.376658
5804  20230413    225959  30290.1  ...    53.75  0.593170  0.361922
5805  20230413    232959  30428.3  ...    53.75  0.585706  0.356329

[5 rows x 33 columns]
0.5772058823529411
acc is : 0.5772058823529411
2023-04-14 00:00:34,171:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.507959  0.492041       0  ...  1.013730  -1.0    0.0  1.060428
540     1  0.490557  0.509443       1  ...  1.009505  -1.0    0.0  1.064847
541     0  0.540572  0.459428       1  ...  1.004896  -1.0    0.0  1.069709
542     0  0.548229  0.451771       0  ...  1.005993  -1.0    0.0  1.068542
543     0  0.507723  0.492277       1  ...  1.005086  -1.0    0.0  1.069505

[5 rows x 10 columns]
2023-04-14 00:00:34,204:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508365  0.491635       0  ...  1.013730  -1.0    0.0  1.060111
46     1  0.491638  0.508362       1  ...  1.009505  -1.0    0.0  1.065874
47     0  0.540708  0.459292       1  ...  1.004896  -1.0    0.0  1.069720
48     0  0.548795  0.451205       0  ...  1.005993  -1.0    0.0  1.068553
49     0  0.507723  0.492277       1  ...  1.005086  -1.0    0.0  1.069505

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20065 

self.closeSec=1681399799, self.tradeDate='20230413', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30331.7', self.close='30395.1'
127.0.0.1 - - [13/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20066 

self.closeSec=1681400399, self.tradeDate='20230413', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30395.2', self.close='30400.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20067 

self.closeSec=1681400999, self.tradeDate='20230413', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30400.7', self.close='30402.3'
127.0.0.1 - - [13/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20068 

self.closeSec=1681401599, self.tradeDate='20230413', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30401', self.close='30422.5'
127.0.0.1 - - [14/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20069 

self.closeSec=1681402199, self.tradeDate='20230414', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30422.6', self.close='30382.3'
127.0.0.1 - - [14/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20070 

self.closeSec=1681402799, self.tradeDate='20230414', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30382.2', self.close='30350.2'
127.0.0.1 - - [14/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20066 

self.closeSec=1681399799, self.tradeDate='20230413', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30331.7', self.close='30395.1'
127.0.0.1 - - [13/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20067 

self.closeSec=1681400399, self.tradeDate='20230413', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30395.2', self.close='30400.7'
127.0.0.1 - - [13/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20068 

self.closeSec=1681400999, self.tradeDate='20230413', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30400.7', self.close='30402.3'
127.0.0.1 - - [13/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20069 

self.closeSec=1681401599, self.tradeDate='20230413', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30401', self.close='30422.5'
127.0.0.1 - - [14/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20070 

self.closeSec=1681402199, self.tradeDate='20230414', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30422.6', self.close='30382.3'
127.0.0.1 - - [14/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20071 

self.closeSec=1681402799, self.tradeDate='20230414', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30382.2', self.close='30350.2'
127.0.0.1 - - [14/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [13/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20066 

self.closeSec=1681399799, self.tradeDate='20230413', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30331.7', self.close='30395.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20067 

self.closeSec=1681400399, self.tradeDate='20230413', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30395.2', self.close='30400.7'
127.0.0.1 - - [13/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20068 

self.closeSec=1681400999, self.tradeDate='20230413', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30400.7', self.close='30402.3'
127.0.0.1 - - [13/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20069 

self.closeSec=1681401599, self.tradeDate='20230413', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30401', self.close='30422.5'
127.0.0.1 - - [14/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20070 

self.closeSec=1681402199, self.tradeDate='20230414', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30422.6', self.close='30382.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20071 

self.closeSec=1681402799, self.tradeDate='20230414', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30382.2', self.close='30350.2'
127.0.0.1 - - [14/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35571
self.closeSec=1681402799, self.tradeDate='20230414', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30343.0, self.close=30350.2, self.high=30357.9, self.low=30340.7, self.vol=1012.398, self.amt=30728036.5368 
127.0.0.1 - - [14/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-14 00:20:08,052:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230413   235500    235959  ...         0.0        0.0       0
5753  20230414   000000    000459  ...         0.0        0.0       0
5754  20230414   000500    000959  ...         0.0        0.0       0
5755  20230414   001000    001459  ...         0.0        0.0       0
5756  20230414   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 00:20:08,058:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681402799, self.tradeDate='20230414', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30343.0, self.close=30350.2, self.high=30357.9, self.low=30340.7, self.vol=1012.398, self.amt=30728036.5368, ukdf['pct'].iloc[-1]=0.000237 , ukdf['amount'].iloc[-1]=30728036.5368, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [14/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35572
self.closeSec=1681403099, self.tradeDate='20230414', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30350.1, self.close=30330.0, self.high=30350.4, self.low=30318.0, self.vol=1292.648, self.amt=39210630.4678 
2023-04-14 00:25:01,636:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230414   000000    000459  ...         0.0        0.0       0
5754  20230414   000500    000959  ...         0.0        0.0       0
5755  20230414   001000    001459  ...         0.0        0.0       0
5756  20230414   001500    001959  ...         0.0        0.0       0
5757  20230414   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 00:25:01,640:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681403099, self.tradeDate='20230414', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30350.1, self.close=30330.0, self.high=30350.4, self.low=30318.0, self.vol=1292.648, self.amt=39210630.4678, ukdf['pct'].iloc[-1]=-0.000666 , ukdf['amount'].iloc[-1]=39210630.4678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230413   120000    155959  1681372799  ...    723  1.003784  1.144108     1.0
724  20230413   160000    195959  1681387199  ...    724  0.976496  1.061582     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '98943.5115', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30154', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [14/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=836
self.closeSec=1681401599, self.tradeDate='20230413', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30149.1, self.close=30422.5, self.high=30648.9, self.low=30116.5, self.vol=147335.344, self.amt=4469851360.85734 
2023-04-14 00:00:01,941:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681401599, self.tradeDate='20230413', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30149.1, self.close=30422.5, self.high=30648.9, self.low=30116.5, self.vol=147335.344, self.amt=4469851360.85734 
2023-04-14 00:00:02,014:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230413   040000    075959  ...   40504.038  1.210339e+09  0.002874
722  20230413   080000    115959  ...   52435.953  1.575004e+09  0.006102
723  20230413   120000    155959  ...   28859.962  8.672803e+08 -0.000077
724  20230413   160000    195959  ...   92038.937  2.779242e+09  0.003134
725  20230413   200000    235959  ...  147335.344  4.469851e+09  0.009065

[5 rows x 11 columns]
2023-04-14 00:00:04,549:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230413   040000    075959  1681343999  ...    721  1.082367  1.376775     1.0
722  20230413   080000    115959  1681358399  ...    722  1.058124  1.291224     1.0
723  20230413   120000    155959  1681372799  ...    723  1.003784  1.144108     1.0
724  20230413   160000    195959  1681387199  ...    724  0.976496  1.061582     1.0
725  20230413   200000    235959  1681401599  ...    725  0.949147  0.982769     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '113374.17163740195', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30428.79120513', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


