# 20230429 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43893
self.closeSec=1682698799, self.tradeDate='20230429', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29240.9, self.close=29167.9, self.high=29240.9, self.low=29126.4, self.vol=3912.441, self.amt=114141096.5838 
127.0.0.1 - - [29/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-29 00:20:06,286:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230428   235500    235959  ...         0.0        0.0       0
5753  20230429   000000    000459  ...         0.0        0.0       0
5754  20230429   000500    000959  ...         0.0        0.0       0
5755  20230429   001000    001459  ...         0.0        0.0       0
5756  20230429   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 00:20:06,291:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682698799, self.tradeDate='20230429', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29240.9, self.close=29167.9, self.high=29240.9, self.low=29126.4, self.vol=3912.441, self.amt=114141096.5838, ukdf['pct'].iloc[-1]=-0.002497 , ukdf['amount'].iloc[-1]=114141096.5838, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-760763.0448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29171.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/Apr/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43894
self.closeSec=1682699099, self.tradeDate='20230429', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29167.8, self.close=29134.5, self.high=29192.6, self.low=29134.0, self.vol=1466.264, self.amt=42762442.3406 
2023-04-29 00:25:02,123:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230429   000000    000459  ...         0.0        0.0       0
5754  20230429   000500    000959  ...         0.0        0.0       0
5755  20230429   001000    001459  ...         0.0        0.0       0
5756  20230429   001500    001959  ...         0.0        0.0       0
5757  20230429   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 00:25:02,123:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682699099, self.tradeDate='20230429', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29167.8, self.close=29134.5, self.high=29192.6, self.low=29134.0, self.vol=1466.264, self.amt=42762442.3406, ukdf['pct'].iloc[-1]=-0.001145 , ukdf['amount'].iloc[-1]=42762442.3406, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-758719.64550241888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29137.64295238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [29/Apr/2023 00:05:02] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230424' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44457 

self.closeSec=1682698199, self.tradeDate='20230429', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29166.3, self.close=29239.2, self.high=29269.1, self.low=29166.2 
127.0.0.1 - - [29/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44458 

self.closeSec=1682698499, self.tradeDate='20230429', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29239.2, self.close=29240.9, self.high=29261.3, self.low=29224.6 
127.0.0.1 - - [29/Apr/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44459 

self.closeSec=1682698799, self.tradeDate='20230429', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29240.9, self.close=29167.9, self.high=29240.9, self.low=29126.4 
127.0.0.1 - - [29/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44460 

self.closeSec=1682699099, self.tradeDate='20230429', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29167.8, self.close=29134.5, self.high=29192.6, self.low=29134.0 
127.0.0.1 - - [29/Apr/2023 00:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-29 00:00:18,951:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230428    212959  29213.9  ...  53.333333  0.524424  0.505787
5802  20230428    215959  29307.3  ...  52.916667  0.492743  0.529085
5803  20230428    222959  29018.8  ...  52.916667  0.513970  0.537574
5804  20230428    225959  29223.3  ...  52.916667  0.499831  0.553637
5805  20230428    232959  29087.8  ...  52.916667  0.497398  0.569436

[5 rows x 33 columns]
0.5496323529411765
acc is : 0.5496323529411765
2023-04-29 00:00:19,033:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.523005  0.476995       0  ...  0.817351   1.0  0.0000  0.972770
540     1  0.432161  0.567839       1  ...  0.810286  -1.0 -0.0016  0.979622
541     0  0.542074  0.457926       0  ...  0.814041  -1.0  0.0000  0.975083
542     1  0.462827  0.537173       0  ...  0.814701  -1.0  0.0000  0.974292
543     1  0.489356  0.510644       1  ...  0.812747  -1.0  0.0000  0.976628

[5 rows x 10 columns]
2023-04-29 00:00:19,056:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.522007  0.477993       0  ...  0.817351   1.0  0.0000  0.969177
46     1  0.432171  0.567829       1  ...  0.810286  -1.0 -0.0016  0.977692
47     0  0.541653  0.458347       0  ...  0.814041  -1.0  0.0000  0.972976
48     1  0.462169  0.537831       0  ...  0.814701  -1.0  0.0000  0.972187
49     1  0.489356  0.510644       1  ...  0.812747  -1.0  0.0000  0.976628

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22225 

self.closeSec=1682695799, self.tradeDate='20230428', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29045.4', self.close='29064.2'

--handleKline--:  127.0.0.1 - - [28/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22226 

self.closeSec=1682696399, self.tradeDate='20230428', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29064.2', self.close='29054.6'
127.0.0.1 - - [28/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22227 

self.closeSec=1682696999, self.tradeDate='20230428', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29054.6', self.close='29147.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22228 

self.closeSec=1682697599, self.tradeDate='20230428', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29147.6', self.close='29133.9'
127.0.0.1 - - [29/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22229 

self.closeSec=1682698199, self.tradeDate='20230429', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29134', self.close='29239.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22230 

self.closeSec=1682698799, self.tradeDate='20230429', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29239.2', self.close='29167.9'
127.0.0.1 - - [29/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22226 

self.closeSec=1682695799, self.tradeDate='20230428', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29045.4', self.close='29064.2'
127.0.0.1 - - [28/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22227 

self.closeSec=1682696399, self.tradeDate='20230428', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29064.2', self.close='29054.6'
127.0.0.1 - - [28/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22228 

self.closeSec=1682696999, self.tradeDate='20230428', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29054.6', self.close='29147.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22229 

self.closeSec=1682697599, self.tradeDate='20230428', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29147.6', self.close='29133.9'
127.0.0.1 - - [29/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22230 

self.closeSec=1682698199, self.tradeDate='20230429', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29134', self.close='29239.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22231 

self.closeSec=1682698799, self.tradeDate='20230429', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29239.2', self.close='29167.9'
127.0.0.1 - - [29/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [28/Apr/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22226 

self.closeSec=1682695799, self.tradeDate='20230428', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29045.4', self.close='29064.2'

--handleKline--:  127.0.0.1 - - [28/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22227 

self.closeSec=1682696399, self.tradeDate='20230428', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29064.2', self.close='29054.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22228 

self.closeSec=1682696999, self.tradeDate='20230428', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29054.6', self.close='29147.6'
127.0.0.1 - - [28/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22229 

self.closeSec=1682697599, self.tradeDate='20230428', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29147.6', self.close='29133.9'
127.0.0.1 - - [29/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22230 

self.closeSec=1682698199, self.tradeDate='20230429', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29134', self.close='29239.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22231 

self.closeSec=1682698799, self.tradeDate='20230429', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29239.2', self.close='29167.9'
127.0.0.1 - - [29/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39891
self.closeSec=1682698799, self.tradeDate='20230429', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29240.9, self.close=29167.9, self.high=29240.9, self.low=29126.4, self.vol=3912.441, self.amt=114141096.5838 
127.0.0.1 - - [29/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-29 00:20:05,799:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230428   235500    235959  ...         0.0        0.0       0
5753  20230429   000000    000459  ...         0.0        0.0       0
5754  20230429   000500    000959  ...         0.0        0.0       0
5755  20230429   001000    001459  ...         0.0        0.0       0
5756  20230429   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 00:20:05,804:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682698799, self.tradeDate='20230429', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29240.9, self.close=29167.9, self.high=29240.9, self.low=29126.4, self.vol=3912.441, self.amt=114141096.5838, ukdf['pct'].iloc[-1]=-0.002497 , ukdf['amount'].iloc[-1]=114141096.5838, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [29/Apr/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39892
self.closeSec=1682699099, self.tradeDate='20230429', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29167.8, self.close=29134.5, self.high=29192.6, self.low=29134.0, self.vol=1466.264, self.amt=42762442.3406 
2023-04-29 00:25:02,122:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230429   000000    000459  ...         0.0        0.0       0
5754  20230429   000500    000959  ...         0.0        0.0       0
5755  20230429   001000    001459  ...         0.0        0.0       0
5756  20230429   001500    001959  ...         0.0        0.0       0
5757  20230429   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 00:25:02,122:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682699099, self.tradeDate='20230429', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29167.8, self.close=29134.5, self.high=29192.6, self.low=29134.0, self.vol=1466.264, self.amt=42762442.3406, ukdf['pct'].iloc[-1]=-0.001145 , ukdf['amount'].iloc[-1]=42762442.3406, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230428   120000    155959  1682668799  ...    723  0.759440  0.298279     NaN
724  20230428   160000    195959  1682683199  ...    724  0.722649  0.179516     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '12731.49270251361', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29220.66256659', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1352827.6996185002, self.flagDict['side']='buy', self.tradeCount=32, self.count=926127.0.0.1 - - [29/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

self.closeSec=1682697599, self.tradeDate='20230428', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29225.9, self.close=29133.9, self.high=29463.3, self.low=28870.0, self.vol=170065.295, self.amt=4955368540.28015 
2023-04-29 00:00:03,218:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682697599, self.tradeDate='20230428', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29225.9, self.close=29133.9, self.high=29463.3, self.low=28870.0, self.vol=170065.295, self.amt=4955368540.28015 
2023-04-29 00:00:03,252:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230428   040000    075959  ...   98577.491  2.912385e+09 -0.006773
722  20230428   080000    115959  ...   78696.354  2.317531e+09 -0.001568
723  20230428   120000    155959  ...   49552.737  1.460039e+09  0.002077
724  20230428   160000    195959  ...   86710.553  2.537331e+09 -0.008411
725  20230428   200000    235959  ...  170065.295  4.955369e+09 -0.003151

[5 rows x 11 columns]
2023-04-29 00:00:04,587:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230428   040000    075959  1682639999  ...    721  0.951217  0.942706     1.0
722  20230428   080000    115959  1682654399  ...    722  0.840334  0.570203     NaN
723  20230428   120000    155959  1682668799  ...    723  0.759440  0.298279     NaN
724  20230428   160000    195959  1682683199  ...    724  0.722649  0.179516     NaN
725  20230428   200000    235959  1682697599  ...    725  0.693585  0.086854     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '8672.8266', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29133.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


