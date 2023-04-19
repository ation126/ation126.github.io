# 20230420 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41301
self.closeSec=1681921199, self.tradeDate='20230420', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29284.6, self.close=29311.0, self.high=29357.2, self.low=29279.9, self.vol=3092.078, self.amt=90656742.25818 
127.0.0.1 - - [20/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-20 00:20:07,190:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230419   235500    235959  ...         0.0        0.0       0
5753  20230420   000000    000459  ...         0.0        0.0       0
5754  20230420   000500    000959  ...         0.0        0.0       0
5755  20230420   001000    001459  ...         0.0        0.0       0
5756  20230420   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 00:20:07,201:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681921199, self.tradeDate='20230420', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29284.6, self.close=29311.0, self.high=29357.2, self.low=29279.9, self.vol=3092.078, self.amt=90656742.25818, ukdf['pct'].iloc[-1]=0.000901 , ukdf['amount'].iloc[-1]=90656742.25818, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-769016.27991125664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29308.75160714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41302
self.closeSec=1681921499, self.tradeDate='20230420', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29310.9, self.close=29294.7, self.high=29320.0, self.low=29287.6, self.vol=1021.071, self.amt=29915552.6426 
2023-04-20 00:25:01,563:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230420   000000    000459  ...         0.0        0.0       0
5754  20230420   000500    000959  ...         0.0        0.0       0
5755  20230420   001000    001459  ...         0.0        0.0       0
5756  20230420   001500    001959  ...         0.0        0.0       0
5757  20230420   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 00:25:01,563:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681921499, self.tradeDate='20230420', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29310.9, self.close=29294.7, self.high=29320.0, self.low=29287.6, self.vol=1021.071, self.amt=29915552.6426, ukdf['pct'].iloc[-1]=-0.000556 , ukdf['amount'].iloc[-1]=29915552.6426, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-768170.7104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29294.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1681920299, self.tradeDate='20230420', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=29248.0, self.close=29226.3, self.high=29272.8, self.low=29225.5 

--ukdf-hist--: overDate='20230415' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41865 

self.closeSec=1681920599, self.tradeDate='20230420', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29226.3, self.close=29272.5, self.high=29279.9, self.low=29224.0 
127.0.0.1 - - [20/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41866 

self.closeSec=1681920899, self.tradeDate='20230420', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29267.4, self.close=29284.6, self.high=29290.6, self.low=29263.0 
127.0.0.1 - - [20/Apr/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41867 

self.closeSec=1681921199, self.tradeDate='20230420', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29284.6, self.close=29311.0, self.high=29357.2, self.low=29279.9 
127.0.0.1 - - [20/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41868 

self.closeSec=1681921499, self.tradeDate='20230420', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29310.9, self.close=29294.7, self.high=29320.0, self.low=29287.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-20 00:00:36,007:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230419    212959  29209.9  ...  51.250000  0.402717  0.567038
5802  20230419    215959  29251.2  ...  51.250000  0.414878  0.574985
5803  20230419    222959  29317.6  ...  51.666667  0.426698  0.579735
5804  20230419    225959  29383.7  ...  51.666667  0.425741  0.584460
5805  20230419    232959  29376.6  ...  51.666667  0.423867  0.589431

[5 rows x 33 columns]
0.5294117647058824
acc is : 0.5294117647058824
2023-04-20 00:00:36,130:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.527557  0.472443       1  ...  1.021525  -1.0    0.0  1.043795
540     0  0.537281  0.462719       1  ...  1.019226  -1.0    0.0  1.046145
541     0  0.537811  0.462189       0  ...  1.019475  -1.0    0.0  1.045889
542     0  0.526959  0.473041       0  ...  1.019958  -1.0    0.0  1.045394
543     0  0.528024  0.471976       0  ...  1.023942  -1.0    0.0  1.041310

[5 rows x 10 columns]
2023-04-20 00:00:36,153:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526577  0.473423       1  ...  1.009185  -1.0    0.0  1.042148
46     0  0.537275  0.462725       1  ...  1.019226  -1.0    0.0  1.045241
47     0  0.537564  0.462436       0  ...  1.019475  -1.0    0.0  1.045423
48     0  0.526674  0.473326       0  ...  1.019958  -1.0    0.0  1.044929
49     0  0.528024  0.471976       0  ...  1.023942  -1.0    0.0  1.041310

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20929 

self.closeSec=1681918199, self.tradeDate='20230419', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29387.3', self.close='29362.6'
127.0.0.1 - - [19/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20930 

self.closeSec=1681918799, self.tradeDate='20230419', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29362.5', self.close='29252.6'
127.0.0.1 - - [19/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20931 

self.closeSec=1681919399, self.tradeDate='20230419', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29252.6', self.close='29195'
127.0.0.1 - - [19/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20932 

self.closeSec=1681919999, self.tradeDate='20230419', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29194.9', self.close='29247.9'
127.0.0.1 - - [20/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20933 

self.closeSec=1681920599, self.tradeDate='20230420', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29248', self.close='29272.5'
127.0.0.1 - - [20/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20934 

self.closeSec=1681921199, self.tradeDate='20230420', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29267.4', self.close='29311'
127.0.0.1 - - [20/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [19/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20930 

self.closeSec=1681918199, self.tradeDate='20230419', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29387.3', self.close='29362.6'
127.0.0.1 - - [19/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20931 

self.closeSec=1681918799, self.tradeDate='20230419', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29362.5', self.close='29252.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20932 

self.closeSec=1681919399, self.tradeDate='20230419', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29252.6', self.close='29195'
127.0.0.1 - - [19/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20933 

self.closeSec=1681919999, self.tradeDate='20230419', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29194.9', self.close='29247.9'
127.0.0.1 - - [20/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20934 

self.closeSec=1681920599, self.tradeDate='20230420', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29248', self.close='29272.5'
127.0.0.1 - - [20/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20935 

self.closeSec=1681921199, self.tradeDate='20230420', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29267.4', self.close='29311'
127.0.0.1 - - [20/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20930 

self.closeSec=1681918199, self.tradeDate='20230419', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29387.3', self.close='29362.6'
127.0.0.1 - - [19/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20931 

self.closeSec=1681918799, self.tradeDate='20230419', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29362.5', self.close='29252.6'
127.0.0.1 - - [19/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20932 

self.closeSec=1681919399, self.tradeDate='20230419', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='29252.6', self.close='29195'
127.0.0.1 - - [19/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20933 

self.closeSec=1681919999, self.tradeDate='20230419', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='29194.9', self.close='29247.9'
127.0.0.1 - - [20/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20934 

self.closeSec=1681920599, self.tradeDate='20230420', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29248', self.close='29272.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20935 

self.closeSec=1681921199, self.tradeDate='20230420', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29267.4', self.close='29311'
127.0.0.1 - - [20/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37299
self.closeSec=1681921199, self.tradeDate='20230420', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29284.6, self.close=29311.0, self.high=29357.2, self.low=29279.9, self.vol=3092.078, self.amt=90656742.25818 
127.0.0.1 - - [20/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-20 00:20:07,029:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230419   235500    235959  ...         0.0        0.0       0
5753  20230420   000000    000459  ...         0.0        0.0       0
5754  20230420   000500    000959  ...         0.0        0.0       0
5755  20230420   001000    001459  ...         0.0        0.0       0
5756  20230420   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 00:20:07,042:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681921199, self.tradeDate='20230420', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29284.6, self.close=29311.0, self.high=29357.2, self.low=29279.9, self.vol=3092.078, self.amt=90656742.25818, ukdf['pct'].iloc[-1]=0.000901 , ukdf['amount'].iloc[-1]=90656742.25818, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37300
self.closeSec=1681921499, self.tradeDate='20230420', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29310.9, self.close=29294.7, self.high=29320.0, self.low=29287.6, self.vol=1021.071, self.amt=29915552.6426 
127.0.0.1 - - [20/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-20 00:25:01,556:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230420   000000    000459  ...         0.0        0.0       0
5754  20230420   000500    000959  ...         0.0        0.0       0
5755  20230420   001000    001459  ...         0.0        0.0       0
5756  20230420   001500    001959  ...         0.0        0.0       0
5757  20230420   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 00:25:01,556:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681921499, self.tradeDate='20230420', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29310.9, self.close=29294.7, self.high=29320.0, self.low=29287.6, self.vol=1021.071, self.amt=29915552.6426, ukdf['pct'].iloc[-1]=-0.000556 , ukdf['amount'].iloc[-1]=29915552.6426, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230419   120000    155959  1681891199  ...    723  0.515285 -0.009071     NaN
724  20230419   160000    195959  1681905599  ...    724  0.272167 -0.558491     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '54007.9297628238', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29298.32863492', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=872
self.closeSec=1681919999, self.tradeDate='20230419', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29300.0, self.close=29247.9, self.high=29490.0, self.low=29015.0, self.vol=98329.802, self.amt=2880595019.47932 
127.0.0.1 - - [20/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-20 00:00:01,882:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681919999, self.tradeDate='20230419', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29300.0, self.close=29247.9, self.high=29490.0, self.low=29015.0, self.vol=98329.802, self.amt=2880595019.47932 
2023-04-20 00:00:01,939:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230419   040000    075959  ...   54391.463  1.649457e+09  0.005297
722  20230419   080000    115959  ...   42292.844  1.279349e+09 -0.005463
723  20230419   120000    155959  ...   57670.911  1.737069e+09 -0.004474
724  20230419   160000    195959  ...  224711.270  6.583421e+09 -0.025438
725  20230419   200000    235959  ...   98329.802  2.880595e+09 -0.001778

[5 rows x 11 columns]
2023-04-20 00:00:04,258:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230419   040000    075959  1681862399  ...    721  0.532673  0.046307     NaN
722  20230419   080000    115959  1681876799  ...    722  0.531656  0.035613     NaN
723  20230419   120000    155959  1681891199  ...    723  0.515285 -0.009071     NaN
724  20230419   160000    195959  1681905599  ...    724  0.272167 -0.558491     NaN
725  20230419   200000    235959  1681919999  ...    725  0.310800 -0.475507     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '51695.766', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29254.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


