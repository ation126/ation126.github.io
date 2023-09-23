# 20230924 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38164
self.closeSec=1695485999, self.tradeDate='20230924', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26552.8, self.close=26548.7, self.high=26554.7, self.low=26548.7, self.vol=144.157, self.amt=3827797.7597 
127.0.0.1 - - [24/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-24 00:20:06,123:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230923   235500    235959  ...         0.0        0.0       0
5760  20230924   000000    000459  ...         0.0        0.0       0
5761  20230924   000500    000959  ...         0.0        0.0       0
5762  20230924   001000    001459  ...         0.0        0.0       0
5763  20230924   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 00:20:06,126:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695485999, self.tradeDate='20230924', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26552.8, self.close=26548.7, self.high=26554.7, self.low=26548.7, self.vol=144.157, self.amt=3827797.7597, ukdf['pct'].iloc[-1]=-0.000151 , ukdf['amount'].iloc[-1]=3827797.7597, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4372.98582293694', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26550.88407131', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38165
self.closeSec=1695486299, self.tradeDate='20230924', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26548.7, self.close=26548.3, self.high=26554.5, self.low=26548.3, self.vol=126.472, self.amt=3357987.5204 
127.0.0.1 - - [24/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-24 00:25:00,788:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230924   000000    000459  ...         0.0        0.0       0
5761  20230924   000500    000959  ...         0.0        0.0       0
5762  20230924   001000    001459  ...         0.0        0.0       0
5763  20230924   001500    001959  ...         0.0        0.0       0
5764  20230924   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 00:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695486299, self.tradeDate='20230924', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26548.7, self.close=26548.3, self.high=26554.5, self.low=26548.3, self.vol=126.472, self.amt=3357987.5204, ukdf['pct'].iloc[-1]=-1.5e-05 , ukdf['amount'].iloc[-1]=3357987.5204, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4392.02936125404', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26549.51659046', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [24/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230919' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38164 

self.closeSec=1695485399, self.tradeDate='20230924', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26554.2, self.close=26549.6, self.high=26554.9, self.low=26549.5 
127.0.0.1 - - [24/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38165 

self.closeSec=1695485699, self.tradeDate='20230924', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26549.5, self.close=26552.7, self.high=26552.8, self.low=26549.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38166 

self.closeSec=1695485999, self.tradeDate='20230924', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26552.8, self.close=26548.7, self.high=26554.7, self.low=26548.7 
127.0.0.1 - - [24/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38167 

self.closeSec=1695486299, self.tradeDate='20230924', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26548.7, self.close=26548.3, self.high=26554.5, self.low=26548.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-24 00:00:18,111:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230923    212959  26563.8  ...  45.833333  0.467082  0.569653
5802  20230923    215959  26557.4  ...  46.250000  0.469197  0.559402
5803  20230923    222959  26561.8  ...  46.250000  0.469025  0.550001
5804  20230923    225959  26561.6  ...  45.833333  0.464835  0.545229
5805  20230923    232959  26551.9  ...  45.416667  0.457494  0.543352

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-09-24 00:00:18,168:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495099  0.504901       1  ...  0.937229  -1.0    0.0  1.029124
540     1  0.497428  0.502572       1  ...  0.937243  -1.0    0.0  1.029109
541     1  0.495441  0.504559       0  ...  0.937582  -1.0    0.0  1.028737
542     1  0.492472  0.507528       0  ...  0.938179  -1.0    0.0  1.028082
543     1  0.490842  0.509158       1  ...  0.937030  -1.0    0.0  1.029341

[5 rows x 10 columns]
2023-09-24 00:00:18,179:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494838  0.505162       1  ...  0.937229  -1.0    0.0  1.030654
46     1  0.497570  0.502430       1  ...  0.937243  -1.0    0.0  1.031402
47     1  0.495735  0.504265       0  ...  0.937582  -1.0    0.0  1.031526
48     1  0.492767  0.507233       0  ...  0.938179  -1.0    0.0  1.030870
49     1  0.490842  0.509158       1  ...  0.937030  -1.0    0.0  1.029341

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '14570.0156478181', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26563.81076557', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19079 

self.closeSec=1695482999, self.tradeDate='20230923', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26556.8', self.close='26535.1'
127.0.0.1 - - [23/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19080 

self.closeSec=1695483599, self.tradeDate='20230923', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26535', self.close='26544'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19081 

self.closeSec=1695484199, self.tradeDate='20230923', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26543.9', self.close='26545.2'
127.0.0.1 - - [23/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19082 

self.closeSec=1695484799, self.tradeDate='20230923', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26546.7', self.close='26567.5'
127.0.0.1 - - [24/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19083 

self.closeSec=1695485399, self.tradeDate='20230924', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26567.4', self.close='26549.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19084 

self.closeSec=1695485999, self.tradeDate='20230924', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26549.5', self.close='26548.7'
127.0.0.1 - - [24/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  127.0.0.1 - - [23/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19082 

self.closeSec=1695482999, self.tradeDate='20230923', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26556.8', self.close='26535.1'
127.0.0.1 - - [23/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19083 

self.closeSec=1695483599, self.tradeDate='20230923', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26535', self.close='26544'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19084 

self.closeSec=1695484199, self.tradeDate='20230923', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26543.9', self.close='26545.2'
127.0.0.1 - - [23/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19085 

self.closeSec=1695484799, self.tradeDate='20230923', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26546.7', self.close='26567.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19086 

self.closeSec=1695485399, self.tradeDate='20230924', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26567.4', self.close='26549.6'
127.0.0.1 - - [24/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19087 

self.closeSec=1695485999, self.tradeDate='20230924', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26549.5', self.close='26548.7'
127.0.0.1 - - [24/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19082 

self.closeSec=1695482999, self.tradeDate='20230923', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26556.8', self.close='26535.1'
127.0.0.1 - - [23/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19083 

self.closeSec=1695483599, self.tradeDate='20230923', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26535', self.close='26544'
127.0.0.1 - - [23/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19084 

self.closeSec=1695484199, self.tradeDate='20230923', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26543.9', self.close='26545.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19085 

self.closeSec=1695484799, self.tradeDate='20230923', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26546.7', self.close='26567.5'
127.0.0.1 - - [24/Sep/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19086 

self.closeSec=1695485399, self.tradeDate='20230924', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26567.4', self.close='26549.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19087 

self.closeSec=1695485999, self.tradeDate='20230924', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26549.5', self.close='26548.7'
127.0.0.1 - - [24/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38164
self.closeSec=1695485999, self.tradeDate='20230924', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26552.8, self.close=26548.7, self.high=26554.7, self.low=26548.7, self.vol=144.157, self.amt=3827797.7597 
127.0.0.1 - - [24/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-24 00:20:06,127:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230923   235500    235959  ...         0.0        0.0       0
5760  20230924   000000    000459  ...         0.0        0.0       0
5761  20230924   000500    000959  ...         0.0        0.0       0
5762  20230924   001000    001459  ...         0.0        0.0       0
5763  20230924   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 00:20:06,137:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695485999, self.tradeDate='20230924', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26552.8, self.close=26548.7, self.high=26554.7, self.low=26548.7, self.vol=144.157, self.amt=3827797.7597, ukdf['pct'].iloc[-1]=-0.000151 , ukdf['amount'].iloc[-1]=3827797.7597, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10886.61870747529', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26550.88407131', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38165
self.closeSec=1695486299, self.tradeDate='20230924', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26548.7, self.close=26548.3, self.high=26554.5, self.low=26548.3, self.vol=126.472, self.amt=3357987.5204 
2023-09-24 00:25:00,773:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230924   000000    000459  ...         0.0        0.0       0
5761  20230924   000500    000959  ...         0.0        0.0       0
5762  20230924   001000    001459  ...         0.0        0.0       0
5763  20230924   001500    001959  ...         0.0        0.0       0
5764  20230924   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 00:25:00,773:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695486299, self.tradeDate='20230924', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26548.7, self.close=26548.3, self.high=26554.5, self.low=26548.3, self.vol=126.472, self.amt=3357987.5204, ukdf['pct'].iloc[-1]=-1.5e-05 , ukdf['amount'].iloc[-1]=3357987.5204, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10937.40831372514', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26549.51659046', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230923   120000    155959  1695455999  ...    723  1.246309  1.946445     1.0
724  20230923   160000    195959  1695470399  ...    724  1.314916  2.050083     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-34916.34926981124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26563.89435348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [24/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=795
self.closeSec=1695484799, self.tradeDate='20230923', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26562.5, self.close=26567.5, self.high=26580.0, self.low=26530.1, self.vol=9319.372, self.amt=247489765.5507 
2023-09-24 00:00:01,564:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695484799, self.tradeDate='20230923', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26562.5, self.close=26567.5, self.high=26580.0, self.low=26530.1, self.vol=9319.372, self.amt=247489765.5507 
2023-09-24 00:00:01,581:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230923   040000    075959  ...  20007.182  5.309535e+08  0.001493
722  20230923   080000    115959  ...  12073.366  3.206306e+08 -0.001792
723  20230923   120000    155959  ...  10416.599  2.764745e+08  0.001976
724  20230923   160000    195959  ...   6701.253  1.779708e+08 -0.000339
725  20230923   200000    235959  ...   9319.372  2.474898e+08  0.000188

[5 rows x 11 columns]
2023-09-24 00:00:02,235:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230923   040000    075959  1695427199  ...    721  1.134255  1.774907     1.0
722  20230923   080000    115959  1695441599  ...    722  1.193795  1.874602     1.0
723  20230923   120000    155959  1695455999  ...    723  1.246309  1.946445     1.0
724  20230923   160000    195959  1695470399  ...    724  1.314916  2.050083     1.0
725  20230923   200000    235959  1695484799  ...    725  1.332019  2.020627     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-34695.34247682063', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26568.24599451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


