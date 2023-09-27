# 20230928 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39316
self.closeSec=1695831599, self.tradeDate='20230928', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26270.7, self.close=26267.6, self.high=26272.8, self.low=26255.5, self.vol=919.09, self.amt=24139669.4705 
127.0.0.1 - - [28/Sep/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-09-28 00:20:06,560:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230927   235500    235959  ...         0.0        0.0       0
5760  20230928   000000    000459  ...         0.0        0.0       0
5761  20230928   000500    000959  ...         0.0        0.0       0
5762  20230928   001000    001459  ...         0.0        0.0       0
5763  20230928   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 00:20:06,569:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695831599, self.tradeDate='20230928', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26270.7, self.close=26267.6, self.high=26272.8, self.low=26255.5, self.vol=919.09, self.amt=24139669.4705, ukdf['pct'].iloc[-1]=-0.000122 , ukdf['amount'].iloc[-1]=24139669.4705, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8316.6072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26267.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39317
self.closeSec=1695831899, self.tradeDate='20230928', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26267.6, self.close=26286.3, self.high=26302.7, self.low=26267.6, self.vol=602.681, self.amt=15844245.5734 
2023-09-28 00:25:00,797:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230928   000000    000459  ...         0.0        0.0       0
5761  20230928   000500    000959  ...         0.0        0.0       0
5762  20230928   001000    001459  ...         0.0        0.0       0
5763  20230928   001500    001959  ...         0.0        0.0       0
5764  20230928   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 00:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695831899, self.tradeDate='20230928', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26267.6, self.close=26286.3, self.high=26302.7, self.low=26267.6, self.vol=602.681, self.amt=15844245.5734, ukdf['pct'].iloc[-1]=0.000712 , ukdf['amount'].iloc[-1]=15844245.5734, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8036.85905937552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26287.78819048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1695830699, self.tradeDate='20230928', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26293.4, self.close=26261.6, self.high=26293.4, self.low=26254.5 

--ukdf-hist--: overDate='20230923' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [28/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39316 

self.closeSec=1695830999, self.tradeDate='20230928', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26260.4, self.close=26272.6, self.high=26289.1, self.low=26257.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39317 127.0.0.1 - - [28/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -


self.closeSec=1695831299, self.tradeDate='20230928', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26272.6, self.close=26270.8, self.high=26303.7, self.low=26270.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39318 

self.closeSec=1695831599, self.tradeDate='20230928', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26270.7, self.close=26267.6, self.high=26272.8, self.low=26255.5 
127.0.0.1 - - [28/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39319 

self.closeSec=1695831899, self.tradeDate='20230928', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26267.6, self.close=26286.3, self.high=26302.7, self.low=26267.6 
127.0.0.1 - - [28/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-28 00:00:18,235:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230927    212959  26710.8  ...  47.916667  0.634017  0.267882
5802  20230927    215959  26727.7  ...  47.916667  0.592020  0.270199
5803  20230927    222959  26607.8  ...  47.500000  0.503920  0.295749
5804  20230927    225959  26326.8  ...  47.083333  0.468759  0.331523
5805  20230927    232959  26184.0  ...  47.500000  0.501032  0.354077

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-09-28 00:00:18,297:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.516994  0.483006       0  ...  0.967837   1.0  0.0000  1.004942
540     1  0.465572  0.534428       0  ...  0.957303   1.0  0.0000  0.994004
541     1  0.388234  0.611766       0  ...  0.960975  -1.0 -0.0016  0.988602
542     1  0.419301  0.580699       1  ...  0.956203  -1.0  0.0000  0.993510
543     0  0.507591  0.492409       0  ...  0.956956  -1.0  0.0000  0.992728

[5 rows x 10 columns]
2023-09-28 00:00:18,309:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.517029  0.482971       0  ...  0.967837   1.0  0.0000  1.005645
46     1  0.465510  0.534490       0  ...  0.957303   1.0  0.0000  0.994395
47     1  0.387988  0.612012       0  ...  0.960975  -1.0 -0.0016  0.988228
48     1  0.418917  0.581083       1  ...  0.956203  -1.0  0.0000  0.993135
49     0  0.507591  0.492409       0  ...  0.956956  -1.0  0.0000  0.992728

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.231', 'enterprice': '26175', 'countrevence': '0', 'unrealprofit': '-2885.80024619399', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26285.01487729', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19655 

self.closeSec=1695828599, self.tradeDate='20230927', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26242.9', self.close='26314.1'
127.0.0.1 - - [27/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19656 

self.closeSec=1695829199, self.tradeDate='20230927', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26312.2', self.close='26273.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19657 

self.closeSec=1695829799, self.tradeDate='20230927', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26273.8', self.close='26265.6'
127.0.0.1 - - [27/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19658 

self.closeSec=1695830399, self.tradeDate='20230927', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26265.6', self.close='26293.4'
127.0.0.1 - - [28/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19659 

self.closeSec=1695830999, self.tradeDate='20230928', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26293.4', self.close='26272.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19660 

self.closeSec=1695831599, self.tradeDate='20230928', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26272.6', self.close='26267.6'
127.0.0.1 - - [28/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [27/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19658 

self.closeSec=1695828599, self.tradeDate='20230927', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26242.9', self.close='26314.1'
127.0.0.1 - - [27/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19659 

self.closeSec=1695829199, self.tradeDate='20230927', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26312.2', self.close='26273.9'

--handleKline--: 127.0.0.1 - - [27/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19660 

self.closeSec=1695829799, self.tradeDate='20230927', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26273.8', self.close='26265.6'
127.0.0.1 - - [28/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19661 

self.closeSec=1695830399, self.tradeDate='20230927', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26265.6', self.close='26293.4'
127.0.0.1 - - [28/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19662 

self.closeSec=1695830999, self.tradeDate='20230928', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26293.4', self.close='26272.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19663 

self.closeSec=1695831599, self.tradeDate='20230928', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26272.6', self.close='26267.6'
127.0.0.1 - - [28/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19658 

self.closeSec=1695828599, self.tradeDate='20230927', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26242.9', self.close='26314.1'
127.0.0.1 - - [27/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19659 

self.closeSec=1695829199, self.tradeDate='20230927', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26312.2', self.close='26273.9'
127.0.0.1 - - [27/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19660 

self.closeSec=1695829799, self.tradeDate='20230927', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26273.8', self.close='26265.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19661 

self.closeSec=1695830399, self.tradeDate='20230927', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26265.6', self.close='26293.4'
127.0.0.1 - - [28/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19662 

self.closeSec=1695830999, self.tradeDate='20230928', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26293.4', self.close='26272.6'
127.0.0.1 - - [28/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19663 

self.closeSec=1695831599, self.tradeDate='20230928', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26272.6', self.close='26267.6'
127.0.0.1 - - [28/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39316
self.closeSec=1695831599, self.tradeDate='20230928', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26270.7, self.close=26267.6, self.high=26272.8, self.low=26255.5, self.vol=919.09, self.amt=24139669.4705 
127.0.0.1 - - [28/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-28 00:20:06,553:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230927   235500    235959  ...         0.0        0.0       0
5760  20230928   000000    000459  ...         0.0        0.0       0
5761  20230928   000500    000959  ...         0.0        0.0       0
5762  20230928   001000    001459  ...         0.0        0.0       0
5763  20230928   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 00:20:06,559:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695831599, self.tradeDate='20230928', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26270.7, self.close=26267.6, self.high=26272.8, self.low=26255.5, self.vol=919.09, self.amt=24139669.4705, ukdf['pct'].iloc[-1]=-0.000122 , ukdf['amount'].iloc[-1]=24139669.4705, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-21404.3583', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26267.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39317
self.closeSec=1695831899, self.tradeDate='20230928', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26267.6, self.close=26286.3, self.high=26302.7, self.low=26267.6, self.vol=602.681, self.amt=15844245.5734 
127.0.0.1 - - [28/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-28 00:25:00,798:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230928   000000    000459  ...         0.0        0.0       0
5761  20230928   000500    000959  ...         0.0        0.0       0
5762  20230928   001000    001459  ...         0.0        0.0       0
5763  20230928   001500    001959  ...         0.0        0.0       0
5764  20230928   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 00:25:00,798:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695831899, self.tradeDate='20230928', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26267.6, self.close=26286.3, self.high=26302.7, self.low=26267.6, self.vol=602.681, self.amt=15844245.5734, ukdf['pct'].iloc[-1]=0.000712 , ukdf['amount'].iloc[-1]=15844245.5734, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-20658.26281738232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26287.78819048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230927   120000    155959  1695801599  ...    723  0.261979 -0.872222    -1.0
724  20230927   160000    195959  1695815999  ...    724  0.172633 -1.097239    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-32032.1116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26780', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=819
self.closeSec=1695830399, self.tradeDate='20230927', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26755.7, self.close=26293.4, self.high=26849.9, self.low=26050.0, self.vol=148743.729, self.amt=3936223616.60274 127.0.0.1 - - [28/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

2023-09-28 00:00:01,548:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695830399, self.tradeDate='20230927', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26755.7, self.close=26293.4, self.high=26849.9, self.low=26050.0, self.vol=148743.729, self.amt=3936223616.60274 
2023-09-28 00:00:01,566:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230927   040000    075959  ...   23705.843  6.206869e+08 -0.001029
722  20230927   080000    115959  ...   18602.743  4.880133e+08  0.002217
723  20230927   120000    155959  ...   10642.269  2.792936e+08 -0.001275
724  20230927   160000    195959  ...  109986.918  2.917954e+09  0.019879
725  20230927   200000    235959  ...  148743.729  3.936224e+09 -0.017249

[5 rows x 11 columns]
2023-09-28 00:00:02,383:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230927   040000    075959  1695772799  ...    721  0.268882 -0.846173    -1.0
722  20230927   080000    115959  1695787199  ...    722  0.269419 -0.848148    -1.0
723  20230927   120000    155959  1695801599  ...    723  0.261979 -0.872222    -1.0
724  20230927   160000    195959  1695815999  ...    724  0.172633 -1.097239    -1.0
725  20230927   200000    235959  1695830399  ...    725  0.070100 -1.344874    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-7355.26493065332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26293.81419597', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


