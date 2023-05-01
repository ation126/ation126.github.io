# 20230502 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44757
self.closeSec=1682957999, self.tradeDate='20230502', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28126.1, self.close=28168.8, self.high=28177.9, self.low=28084.1, self.vol=2493.319, self.amt=70139205.3315 
127.0.0.1 - - [02/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-02 00:20:06,104:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230501   235500    235959  ...         0.0        0.0       0
5760  20230502   000000    000459  ...         0.0        0.0       0
5761  20230502   000500    000959  ...         0.0        0.0       0
5762  20230502   001000    001459  ...         0.0        0.0       0
5763  20230502   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 00:20:06,116:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682957999, self.tradeDate='20230502', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28126.1, self.close=28168.8, self.high=28177.9, self.low=28084.1, self.vol=2493.319, self.amt=70139205.3315, ukdf['pct'].iloc[-1]=0.001518 , ukdf['amount'].iloc[-1]=70139205.3315, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-700436.6048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28169.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44758
self.closeSec=1682958299, self.tradeDate='20230502', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28168.9, self.close=28092.6, self.high=28179.0, self.low=28050.0, self.vol=3622.508, self.amt=101801669.7881 
127.0.0.1 - - [02/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-02 00:25:02,097:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230502   000000    000459  ...         0.0        0.0       0
5761  20230502   000500    000959  ...         0.0        0.0       0
5762  20230502   001000    001459  ...         0.0        0.0       0
5763  20230502   001500    001959  ...         0.0        0.0       0
5764  20230502   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 00:25:02,097:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682958299, self.tradeDate='20230502', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28168.9, self.close=28092.6, self.high=28179.0, self.low=28050.0, self.vol=3622.508, self.amt=101801669.7881, ukdf['pct'].iloc[-1]=-0.002705 , ukdf['amount'].iloc[-1]=101801669.7881, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695969.82174835792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28094.87135317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [02/May/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230427' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [02/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45321 

self.closeSec=1682957399, self.tradeDate='20230502', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28238.9, self.close=28160.6, self.high=28261.0, self.low=28154.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45322 

self.closeSec=1682957699, self.tradeDate='20230502', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28160.6, self.close=28126.1, self.high=28187.0, self.low=28081.3 
127.0.0.1 - - [02/May/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45323 

self.closeSec=1682957999, self.tradeDate='20230502', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28126.1, self.close=28168.8, self.high=28177.9, self.low=28084.1 
127.0.0.1 - - [02/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/May/2023 00:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45324 

self.closeSec=1682958299, self.tradeDate='20230502', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28168.9, self.close=28092.6, self.high=28179.0, self.low=28050.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-02 00:00:19,777:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230501    212959  28581.4  ...  49.166667  0.420126  0.763443
5802  20230501    215959  28582.8  ...  48.750000  0.399622  0.767995
5803  20230501    222959  28445.4  ...  49.166667  0.404582  0.770978
5804  20230501    225959  28468.4  ...  48.750000  0.403709  0.773634
5805  20230501    232959  28462.5  ...  48.333333  0.355018  0.787071

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-05-02 00:00:19,871:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.522580  0.477420       0  ...  0.839233  -1.0    0.0  0.985713
540     1  0.487702  0.512298       1  ...  0.838554  -1.0    0.0  0.986510
541     0  0.521031  0.478969       0  ...  0.838728  -1.0    0.0  0.986305
542     0  0.510993  0.489007       0  ...  0.849558  -1.0    0.0  0.973570
543     1  0.418079  0.581921       1  ...  0.847644  -1.0    0.0  0.975764

[5 rows x 10 columns]
2023-05-02 00:00:19,892:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.521830  0.478170       0  ...  0.864771  -1.0    0.0  0.982153
46     1  0.487124  0.512876       1  ...  0.864072  -1.0    0.0  0.984684
47     0  0.520967  0.479033       0  ...  0.838728  -1.0    0.0  0.984855
48     0  0.510986  0.489014       0  ...  0.849558  -1.0    0.0  0.972139
49     1  0.418079  0.581921       1  ...  0.847644  -1.0    0.0  0.975764

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [01/May/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22657 

self.closeSec=1682954999, self.tradeDate='20230501', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28356.9', self.close='28095'
127.0.0.1 - - [01/May/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22658 

self.closeSec=1682955599, self.tradeDate='20230501', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28099.2', self.close='28109.1'
127.0.0.1 - - [01/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22659 

self.closeSec=1682956199, self.tradeDate='20230501', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28109.1', self.close='28164.9'
127.0.0.1 - - [02/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22660 

self.closeSec=1682956799, self.tradeDate='20230501', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28165', self.close='28158.3'
127.0.0.1 - - [02/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22661 

self.closeSec=1682957399, self.tradeDate='20230502', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28158.5', self.close='28160.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22662 

self.closeSec=1682957999, self.tradeDate='20230502', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28160.6', self.close='28168.9'
127.0.0.1 - - [02/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [01/May/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22658 

self.closeSec=1682954999, self.tradeDate='20230501', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28356.9', self.close='28095'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22659 

self.closeSec=1682955599, self.tradeDate='20230501', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28099.2', self.close='28109.1'
127.0.0.1 - - [01/May/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22660 

self.closeSec=1682956199, self.tradeDate='20230501', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28109.1', self.close='28164.9'
127.0.0.1 - - [01/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22661 

self.closeSec=1682956799, self.tradeDate='20230501', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28165', self.close='28158.3'
127.0.0.1 - - [02/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22662 

self.closeSec=1682957399, self.tradeDate='20230502', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28158.5', self.close='28160.6'
127.0.0.1 - - [02/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22663 

self.closeSec=1682957999, self.tradeDate='20230502', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28160.6', self.close='28168.9'
127.0.0.1 - - [02/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [01/May/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22658 

self.closeSec=1682954999, self.tradeDate='20230501', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28356.9', self.close='28095'
127.0.0.1 - - [01/May/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22659 

self.closeSec=1682955599, self.tradeDate='20230501', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28099.2', self.close='28109.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22660 

self.closeSec=1682956199, self.tradeDate='20230501', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28109.1', self.close='28164.9'
127.0.0.1 - - [01/May/2023 23:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22661 

self.closeSec=1682956799, self.tradeDate='20230501', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28165', self.close='28158.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22662 

self.closeSec=1682957399, self.tradeDate='20230502', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28158.5', self.close='28160.6'
127.0.0.1 - - [02/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22663 

self.closeSec=1682957999, self.tradeDate='20230502', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28160.6', self.close='28168.9'
127.0.0.1 - - [02/May/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40755
self.closeSec=1682957999, self.tradeDate='20230502', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28126.1, self.close=28168.8, self.high=28177.9, self.low=28084.1, self.vol=2493.319, self.amt=70139205.3315 
127.0.0.1 - - [02/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-02 00:20:06,007:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230501   235500    235959  ...         0.0        0.0       0
5760  20230502   000000    000459  ...         0.0        0.0       0
5761  20230502   000500    000959  ...         0.0        0.0       0
5762  20230502   001000    001459  ...         0.0        0.0       0
5763  20230502   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 00:20:06,017:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682957999, self.tradeDate='20230502', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28126.1, self.close=28168.8, self.high=28177.9, self.low=28084.1, self.vol=2493.319, self.amt=70139205.3315, ukdf['pct'].iloc[-1]=0.001518 , ukdf['amount'].iloc[-1]=70139205.3315, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40756
self.closeSec=1682958299, self.tradeDate='20230502', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28168.9, self.close=28092.6, self.high=28179.0, self.low=28050.0, self.vol=3622.508, self.amt=101801669.7881 
127.0.0.1 - - [02/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-02 00:25:02,090:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230502   000000    000459  ...         0.0        0.0       0
5761  20230502   000500    000959  ...         0.0        0.0       0
5762  20230502   001000    001459  ...         0.0        0.0       0
5763  20230502   001500    001959  ...         0.0        0.0       0
5764  20230502   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 00:25:02,092:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682958299, self.tradeDate='20230502', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28168.9, self.close=28092.6, self.high=28179.0, self.low=28050.0, self.vol=3622.508, self.amt=101801669.7881, ukdf['pct'].iloc[-1]=-0.002705 , ukdf['amount'].iloc[-1]=101801669.7881, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230501   120000    155959  1682927999  ...    723  0.057037 -1.678771    -1.0
724  20230501   160000    195959  1682942399  ...    724  0.124316 -1.464028    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '39218.77361880744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28501.82113492', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [02/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=944
self.closeSec=1682956799, self.tradeDate='20230501', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28510.6, self.close=28158.3, self.high=28618.0, self.low=28052.1, self.vol=130179.626, self.amt=3688901949.34935 
2023-05-02 00:00:03,248:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682956799, self.tradeDate='20230501', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28510.6, self.close=28158.3, self.high=28618.0, self.low=28052.1, self.vol=130179.626, self.amt=3688901949.34935 
2023-05-02 00:00:03,289:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230501   040000    075959  ...   75149.932  2.202846e+09 -0.004430
722  20230501   080000    115959  ...  143426.630  4.121325e+09 -0.022946
723  20230501   120000    155959  ...   77991.238  2.223718e+09  0.002256
724  20230501   160000    195959  ...   39461.984  1.126488e+09 -0.003474
725  20230501   200000    235959  ...  130179.626  3.688902e+09 -0.012357

[5 rows x 11 columns]
2023-05-02 00:00:04,852:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230501   040000    075959  1682899199  ...    721  0.035905 -1.805191    -1.0
722  20230501   080000    115959  1682913599  ...    722  0.001777 -1.873562    -1.0
723  20230501   120000    155959  1682927999  ...    723  0.057037 -1.678771    -1.0
724  20230501   160000    195959  1682942399  ...    724  0.124316 -1.464028    -1.0
725  20230501   200000    235959  1682956799  ...    725  0.199479 -1.238036    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '55136.5836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28161.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


