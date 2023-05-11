# 20230511 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47541
self.closeSec=1683793199, self.tradeDate='20230511', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27393.7, self.close=27410.0, self.high=27427.5, self.low=27374.0, self.vol=1822.661, self.amt=49961570.8966 
127.0.0.1 - - [11/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-11 16:20:06,626:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230511   155500    155959  ...         0.0        0.0       0
5952  20230511   160000    160459  ...         0.0        0.0       0
5953  20230511   160500    160959  ...         0.0        0.0       0
5954  20230511   161000    161459  ...         0.0        0.0       0
5955  20230511   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 16:20:06,638:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683793199, self.tradeDate='20230511', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27393.7, self.close=27410.0, self.high=27427.5, self.low=27374.0, self.vol=1822.661, self.amt=49961570.8966, ukdf['pct'].iloc[-1]=0.000591 , ukdf['amount'].iloc[-1]=49961570.8966, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-654679.6100310152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27408.71388645', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47542
self.closeSec=1683793499, self.tradeDate='20230511', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27409.9, self.close=27388.2, self.high=27410.0, self.low=27362.6, self.vol=1402.815, self.amt=38412500.7728 
2023-05-11 16:25:02,218:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230511   160000    160459  ...         0.0        0.0       0
5953  20230511   160500    160959  ...         0.0        0.0       0
5954  20230511   161000    161459  ...         0.0        0.0       0
5955  20230511   161500    161959  ...         0.0        0.0       0
5956  20230511   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 16:25:02,218:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683793499, self.tradeDate='20230511', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27409.9, self.close=27388.2, self.high=27410.0, self.low=27362.6, self.vol=1402.815, self.amt=38412500.7728, ukdf['pct'].iloc[-1]=-0.000795 , ukdf['amount'].iloc[-1]=38412500.7728, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-653469.57517085152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27388.60562302', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48103 

self.closeSec=1683791999, self.tradeDate='20230511', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27477.1, self.close=27437.5, self.high=27480.6, self.low=27401.1 
127.0.0.1 - - [11/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48104 

self.closeSec=1683792299, self.tradeDate='20230511', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27437.5, self.close=27372.5, self.high=27438.9, self.low=27220.0 
127.0.0.1 - - [11/May/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48105 

self.closeSec=1683792599, self.tradeDate='20230511', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27372.4, self.close=27415.1, self.high=27415.1, self.low=27354.3 
127.0.0.1 - - [11/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48106 

self.closeSec=1683792899, self.tradeDate='20230511', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27415.1, self.close=27393.8, self.high=27415.3, self.low=27372.3 
127.0.0.1 - - [11/May/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48107 

self.closeSec=1683793199, self.tradeDate='20230511', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27393.7, self.close=27410.0, self.high=27427.5, self.low=27374.0 
127.0.0.1 - - [11/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 16:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48108 

self.closeSec=1683793499, self.tradeDate='20230511', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27409.9, self.close=27388.2, self.high=27410.0, self.low=27362.6 


## /root/FIL/strategy/logic/log.txt ----- -----

5786  20230511    135959  27450.7  ...  49.166667  0.474871  0.452661
5787  20230511    142959  27515.5  ...  49.166667  0.470816  0.455735
5788  20230511    145959  27483.8  ...  49.166667  0.471603  0.458383
5789  20230511    152959  27489.3  ...  49.166667  0.475288  0.459833

[5 rows x 33 columns]
0.5350553505535055
acc is : 0.5350553505535055
2023-05-11 16:00:19,749:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.491017  0.508983       1  ...  0.955167   1.0    0.0  0.944757
538     0  0.518498  0.481502       0  ...  0.954070   1.0    0.0  0.943672
539     0  0.500637  0.499363       1  ...  0.954258   1.0    0.0  0.943858
540     0  0.510041  0.489959       1  ...  0.955126   1.0    0.0  0.944716
541     0  0.509663  0.490337       0  ...  0.952463   1.0    0.0  0.942083

[5 rows x 10 columns]
2023-05-11 16:00:19,761:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490510  0.509490       1  ...  0.954409  -1.0    0.0  0.942760
46     0  0.518262  0.481738       0  ...  0.955505  -1.0    0.0  0.942611
47     0  0.500156  0.499844       1  ...  0.955317  -1.0    0.0  0.941002
48     0  0.509815  0.490185       1  ...  0.954448  -1.0    0.0  0.942180
49     0  0.509663  0.490337       0  ...  0.952463   1.0    0.0  0.942083

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-05-11 16:00:20,340:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '27.877', 'buy' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:764762.82159285179', 'result': 'success', 'clientorderid': ''}
2023-05-11 16:00:20,357:INFO:logic:main.py:494:insertFactor:885513: curDateTime:5111600, name:logic, symbol:BTCUSDT, tradeDate:20230511, closeTime:155959, close:27437.5, sign:1, total:767183.2585902, side:buy  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24049 

self.closeSec=1683790199, self.tradeDate='20230511', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27493', self.close='27514.2'
127.0.0.1 - - [11/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24050 

self.closeSec=1683790799, self.tradeDate='20230511', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27514.2', self.close='27524.6'
127.0.0.1 - - [11/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24051 

self.closeSec=1683791399, self.tradeDate='20230511', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27524.6', self.close='27497.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24052 

self.closeSec=1683791999, self.tradeDate='20230511', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27497.8', self.close='27437.5'
127.0.0.1 - - [11/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24053 

self.closeSec=1683792599, self.tradeDate='20230511', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27437.5', self.close='27415.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24054 

self.closeSec=1683793199, self.tradeDate='20230511', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27415.1', self.close='27410'
127.0.0.1 - - [11/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24050 

self.closeSec=1683790199, self.tradeDate='20230511', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27493', self.close='27514.2'
127.0.0.1 - - [11/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24051 

self.closeSec=1683790799, self.tradeDate='20230511', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27514.2', self.close='27524.6'
127.0.0.1 - - [11/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24052 

self.closeSec=1683791399, self.tradeDate='20230511', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27524.6', self.close='27497.9'
127.0.0.1 - - [11/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24053 

self.closeSec=1683791999, self.tradeDate='20230511', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27497.8', self.close='27437.5'
127.0.0.1 - - [11/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24054 

self.closeSec=1683792599, self.tradeDate='20230511', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27437.5', self.close='27415.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24055 

self.closeSec=1683793199, self.tradeDate='20230511', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27415.1', self.close='27410'
127.0.0.1 - - [11/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24050 

self.closeSec=1683790199, self.tradeDate='20230511', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27493', self.close='27514.2'
127.0.0.1 - - [11/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24051 

self.closeSec=1683790799, self.tradeDate='20230511', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27514.2', self.close='27524.6'
127.0.0.1 - - [11/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24052 

self.closeSec=1683791399, self.tradeDate='20230511', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27524.6', self.close='27497.9'
127.0.0.1 - - [11/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24053 

self.closeSec=1683791999, self.tradeDate='20230511', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27497.8', self.close='27437.5'
127.0.0.1 - - [11/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24054 

self.closeSec=1683792599, self.tradeDate='20230511', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27437.5', self.close='27415.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24055 

self.closeSec=1683793199, self.tradeDate='20230511', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27415.1', self.close='27410'
127.0.0.1 - - [11/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43539
self.closeSec=1683793199, self.tradeDate='20230511', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27393.7, self.close=27410.0, self.high=27427.5, self.low=27374.0, self.vol=1822.661, self.amt=49961570.8966 
127.0.0.1 - - [11/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-11 16:20:06,238:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230511   155500    155959  ...         0.0        0.0       0
5952  20230511   160000    160459  ...         0.0        0.0       0
5953  20230511   160500    160959  ...         0.0        0.0       0
5954  20230511   161000    161459  ...         0.0        0.0       0
5955  20230511   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 16:20:06,250:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683793199, self.tradeDate='20230511', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27393.7, self.close=27410.0, self.high=27427.5, self.low=27374.0, self.vol=1822.661, self.amt=49961570.8966, ukdf['pct'].iloc[-1]=0.000591 , ukdf['amount'].iloc[-1]=49961570.8966, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [11/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43540
self.closeSec=1683793499, self.tradeDate='20230511', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27409.9, self.close=27388.2, self.high=27410.0, self.low=27362.6, self.vol=1402.815, self.amt=38412500.7728 
2023-05-11 16:25:02,199:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230511   160000    160459  ...         0.0        0.0       0
5953  20230511   160500    160959  ...         0.0        0.0       0
5954  20230511   161000    161459  ...         0.0        0.0       0
5955  20230511   161500    161959  ...         0.0        0.0       0
5956  20230511   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 16:25:02,199:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683793499, self.tradeDate='20230511', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27409.9, self.close=27388.2, self.high=27410.0, self.low=27362.6, self.vol=1402.815, self.amt=38412500.7728, ukdf['pct'].iloc[-1]=-0.000795 , ukdf['amount'].iloc[-1]=38412500.7728, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230511   040000    075959  1683763199  ...    721  0.442410 -0.312865     NaN
722  20230511   080000    115959  1683777599  ...    722  0.447831 -0.287138     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '-9341.55793109762', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27432.16895238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1448108.3022399, self.flagDict['side']='buy', self.tradeCount=34, self.count=1002
self.closeSec=1683791999, self.tradeDate='20230511', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27435.1, self.close=27437.5, self.high=27544.1, self.low=27382.4, self.vol=39192.274, self.amt=1076570011.9986 
2023-05-11 16:00:03,461:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683791999, self.tradeDate='20230511', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27435.1, self.close=27437.5, self.high=27544.1, self.low=27382.4, self.vol=39192.274, self.amt=1076570011.9986 
127.0.0.1 - - [11/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
2023-05-11 16:00:03,521:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230510   200000    235959  ...  213950.080  6.001232e+09  0.017371
720  20230511   000000    035959  ...  289613.920  7.950327e+09 -0.016261
721  20230511   040000    075959  ...   99430.444  2.747766e+09 -0.003638
722  20230511   080000    115959  ...   56879.457  1.563685e+09 -0.005358
723  20230511   120000    155959  ...   39192.274  1.076570e+09  0.000087

[5 rows x 11 columns]
2023-05-11 16:00:04,692:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230510   200000    235959  1683734399  ...    719  0.862802  1.105271     1.0
720  20230511   000000    035959  1683748799  ...    720  0.488827 -0.165419     NaN
721  20230511   040000    075959  1683763199  ...    721  0.442410 -0.312865     NaN
722  20230511   080000    115959  1683777599  ...    722  0.447831 -0.287138     NaN
723  20230511   120000    155959  1683791999  ...    723  0.412500 -0.397041     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '-8995.49807050678', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27438.76044322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


