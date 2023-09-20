# 20230921 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37300
self.closeSec=1695226799, self.tradeDate='20230921', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27170.8, self.close=27167.5, self.high=27189.0, self.low=27167.4, self.vol=623.406, self.amt=16946425.8436 
127.0.0.1 - - [21/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-21 00:20:06,707:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230920   235500    235959  ...         0.0        0.0       0
5760  20230921   000000    000459  ...         0.0        0.0       0
5761  20230921   000500    000959  ...         0.0        0.0       0
5762  20230921   001000    001459  ...         0.0        0.0       0
5763  20230921   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 00:20:06,716:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695226799, self.tradeDate='20230921', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27170.8, self.close=27167.5, self.high=27189.0, self.low=27167.4, self.vol=623.406, self.amt=16946425.8436, ukdf['pct'].iloc[-1]=-0.000121 , ukdf['amount'].iloc[-1]=16946425.8436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4176.64016320254', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27164.81671429', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37301
self.closeSec=1695227099, self.tradeDate='20230921', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27166.8, self.close=27148.1, self.high=27180.3, self.low=27124.7, self.vol=1414.407, self.amt=38400529.269 
127.0.0.1 - - [21/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-21 00:25:00,795:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230921   000000    000459  ...         0.0        0.0       0
5761  20230921   000500    000959  ...         0.0        0.0       0
5762  20230921   001000    001459  ...         0.0        0.0       0
5763  20230921   001500    001959  ...         0.0        0.0       0
5764  20230921   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 00:25:00,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695227099, self.tradeDate='20230921', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27166.8, self.close=27148.1, self.high=27180.3, self.low=27124.7, self.vol=1414.407, self.amt=38400529.269, ukdf['pct'].iloc[-1]=-0.000714 , ukdf['amount'].iloc[-1]=38400529.269, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3876.9984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27143.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1695225899, self.tradeDate='20230921', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27168.7, self.close=27172.7, self.high=27179.9, self.low=27163.8 

--ukdf-hist--: overDate='20230916' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37300 

self.closeSec=1695226199, self.tradeDate='20230921', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27172.1, self.close=27162.2, self.high=27179.5, self.low=27154.2 
127.0.0.1 - - [21/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37301 

self.closeSec=1695226499, self.tradeDate='20230921', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27161.7, self.close=27170.8, self.high=27188.0, self.low=27156.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37302 

self.closeSec=1695226799, self.tradeDate='20230921', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27170.8, self.close=27167.5, self.high=27189.0, self.low=27167.4 
127.0.0.1 - - [21/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37303 

self.closeSec=1695227099, self.tradeDate='20230921', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27166.8, self.close=27148.1, self.high=27180.3, self.low=27124.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-21 00:00:17,272:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230920    212959  27056.3  ...  52.916667  0.505972  0.619234
5802  20230920    215959  27036.6  ...  53.333333  0.528319  0.611977
5803  20230920    222959  27146.6  ...  53.333333  0.530101  0.603878
5804  20230920    225959  27156.4  ...  53.333333  0.519864  0.603092
5805  20230920    232959  27110.0  ...  52.916667  0.517648  0.603830

[5 rows x 33 columns]
0.53125
acc is : 0.53125
2023-09-21 00:00:17,330:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.492383  0.507617       1  ...  0.921306  -1.0    0.0  1.049337
540     0  0.530957  0.469043       1  ...  0.920997  -1.0    0.0  1.049689
541     0  0.505868  0.494132       0  ...  0.922574  -1.0    0.0  1.047891
542     1  0.487769  0.512231       0  ...  0.922918  -1.0    0.0  1.047501
543     1  0.493141  0.506859       1  ...  0.920650  -1.0    0.0  1.050075

[5 rows x 10 columns]
2023-09-21 00:00:17,341:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492442  0.507558       1  ...  0.921306  -1.0    0.0  1.050031
46     0  0.530893  0.469107       1  ...  0.920997  -1.0    0.0  1.049701
47     0  0.505992  0.494008       0  ...  0.922574  -1.0    0.0  1.048098
48     1  0.487942  0.512058       0  ...  0.922918  -1.0    0.0  1.047708
49     1  0.493141  0.506859       1  ...  0.920650  -1.0    0.0  1.050075

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '-1078.14', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27173.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18647 

self.closeSec=1695223799, self.tradeDate='20230920', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27151.7', self.close='27099.9'
127.0.0.1 - - [20/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18648 

self.closeSec=1695224399, self.tradeDate='20230920', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27101.4', self.close='27117.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18649 

self.closeSec=1695224999, self.tradeDate='20230920', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27117.1', self.close='27172'
127.0.0.1 - - [20/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18650 

self.closeSec=1695225599, self.tradeDate='20230920', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27171.7', self.close='27166.5'
127.0.0.1 - - [21/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18651 

self.closeSec=1695226199, self.tradeDate='20230921', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27168.7', self.close='27162.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18652 

self.closeSec=1695226799, self.tradeDate='20230921', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27161.7', self.close='27167.5'
127.0.0.1 - - [21/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [20/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18650 

self.closeSec=1695223799, self.tradeDate='20230920', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27151.7', self.close='27099.9'
127.0.0.1 - - [20/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18651 

self.closeSec=1695224399, self.tradeDate='20230920', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27101.4', self.close='27117.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18652 

self.closeSec=1695224999, self.tradeDate='20230920', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27117.1', self.close='27172'
127.0.0.1 - - [20/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18653 

self.closeSec=1695225599, self.tradeDate='20230920', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27171.7', self.close='27166.5'
127.0.0.1 - - [21/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18654 

self.closeSec=1695226199, self.tradeDate='20230921', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27168.7', self.close='27162.2'
127.0.0.1 - - [21/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18655 

self.closeSec=1695226799, self.tradeDate='20230921', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27161.7', self.close='27167.5'
127.0.0.1 - - [21/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18650 

self.closeSec=1695223799, self.tradeDate='20230920', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27151.7', self.close='27099.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18651 

self.closeSec=1695224399, self.tradeDate='20230920', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27101.4', self.close='27117.1'
127.0.0.1 - - [20/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18652 

self.closeSec=1695224999, self.tradeDate='20230920', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27117.1', self.close='27172'
127.0.0.1 - - [21/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18653 

self.closeSec=1695225599, self.tradeDate='20230920', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27171.7', self.close='27166.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18654 

self.closeSec=1695226199, self.tradeDate='20230921', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27168.7', self.close='27162.2'
127.0.0.1 - - [21/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18655 

self.closeSec=1695226799, self.tradeDate='20230921', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27161.7', self.close='27167.5'
127.0.0.1 - - [21/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37300
self.closeSec=1695226799, self.tradeDate='20230921', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27170.8, self.close=27167.5, self.high=27189.0, self.low=27167.4, self.vol=623.406, self.amt=16946425.8436 
127.0.0.1 - - [21/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-21 00:20:06,709:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230920   235500    235959  ...         0.0        0.0       0
5760  20230921   000000    000459  ...         0.0        0.0       0
5761  20230921   000500    000959  ...         0.0        0.0       0
5762  20230921   001000    001459  ...         0.0        0.0       0
5763  20230921   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 00:20:06,720:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695226799, self.tradeDate='20230921', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27170.8, self.close=27167.5, self.high=27189.0, self.low=27167.4, self.vol=623.406, self.amt=16946425.8436, ukdf['pct'].iloc[-1]=-0.000121 , ukdf['amount'].iloc[-1]=16946425.8436, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '11915.45358544489', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27164.81671429', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [21/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37301
self.closeSec=1695227099, self.tradeDate='20230921', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27166.8, self.close=27148.1, self.high=27180.3, self.low=27124.7, self.vol=1414.407, self.amt=38400529.269 
2023-09-21 00:25:00,801:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230921   000000    000459  ...         0.0        0.0       0
5761  20230921   000500    000959  ...         0.0        0.0       0
5762  20230921   001000    001459  ...         0.0        0.0       0
5763  20230921   001500    001959  ...         0.0        0.0       0
5764  20230921   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 00:25:00,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695227099, self.tradeDate='20230921', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27166.8, self.close=27148.1, self.high=27180.3, self.low=27124.7, self.vol=1414.407, self.amt=38400529.269, ukdf['pct'].iloc[-1]=-0.000714 , ukdf['amount'].iloc[-1]=38400529.269, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '11116.3013', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27143.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230920   120000    155959  1695196799  ...    723  1.389618  3.322454     1.0
724  20230920   160000    195959  1695211199  ...    724  1.333400  2.958932     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-8410.3272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27085.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [21/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=777
self.closeSec=1695225599, self.tradeDate='20230920', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27085.5, self.close=27166.5, self.high=27228.8, self.low=26980.2, self.vol=57520.038, self.amt=1559204013.56338 
2023-09-21 00:00:01,528:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695225599, self.tradeDate='20230920', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27085.5, self.close=27166.5, self.high=27228.8, self.low=26980.2, self.vol=57520.038, self.amt=1559204013.56338 
2023-09-21 00:00:01,541:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230920   040000    075959  ...  32685.998  8.865219e+08  0.000994
722  20230920   080000    115959  ...  46102.861  1.254524e+09 -0.003291
723  20230920   120000    155959  ...  42439.459  1.147899e+09 -0.000623
724  20230920   160000    195959  ...  49754.746  1.346007e+09 -0.000148
725  20230920   200000    235959  ...  57520.038  1.559204e+09  0.002991

[5 rows x 11 columns]
2023-09-21 00:00:02,236:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230920   040000    075959  1695167999  ...    721  1.258084  3.471109     1.0
722  20230920   080000    115959  1695182399  ...    722  1.453450  3.795504     1.0
723  20230920   120000    155959  1695196799  ...    723  1.389618  3.322454     1.0
724  20230920   160000    195959  1695211199  ...    724  1.333400  2.958932     1.0
725  20230920   200000    235959  1695225599  ...    725  1.263330  2.615045     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-4195.0062', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27168.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


