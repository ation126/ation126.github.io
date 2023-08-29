# 20230830 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30964
self.closeSec=1693325999, self.tradeDate='20230830', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27632.9, self.close=27698.2, self.high=27716.0, self.low=27597.8, self.vol=10745.019, self.amt=297081295.9193 
127.0.0.1 - - [30/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-30 00:20:05,178:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230829   235500    235959  ...         0.0        0.0       0
5748  20230830   000000    000459  ...         0.0        0.0       0
5749  20230830   000500    000959  ...         0.0        0.0       0
5750  20230830   001000    001459  ...         0.0        0.0       0
5751  20230830   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 00:20:05,185:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693325999, self.tradeDate='20230830', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27632.9, self.close=27698.2, self.high=27716.0, self.low=27597.8, self.vol=10745.019, self.amt=297081295.9193, ukdf['pct'].iloc[-1]=0.002595 , ukdf['amount'].iloc[-1]=297081295.9193, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-12187.35346367154', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27740.05104579', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30965
self.closeSec=1693326299, self.tradeDate='20230830', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27698.2, self.close=27900.8, self.high=27978.2, self.low=27661.2, self.vol=18359.483, self.amt=510761809.29298 
2023-08-30 00:25:00,821:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230830   000000    000459  ...         0.0        0.0       0
5749  20230830   000500    000959  ...         0.0        0.0       0
5750  20230830   001000    001459  ...         0.0        0.0       0
5751  20230830   001500    001959  ...         0.0        0.0       0
5752  20230830   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 00:25:00,821:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693326299, self.tradeDate='20230830', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27698.2, self.close=27900.8, self.high=27978.2, self.low=27661.2, self.vol=18359.483, self.amt=510761809.29298, ukdf['pct'].iloc[-1]=0.007315 , ukdf['amount'].iloc[-1]=510761809.29298, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14375.8098', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27897.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1693325099, self.tradeDate='20230830', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27411.4, self.close=27358.4, self.high=27445.0, self.low=27350.0 

--ukdf-hist--: overDate='20230825' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [30/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30964 

self.closeSec=1693325399, self.tradeDate='20230830', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27356.1, self.close=27437.3, self.high=27455.0, self.low=27337.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30965 

self.closeSec=1693325699, self.tradeDate='20230830', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27437.2, self.close=27626.5, self.high=27905.4, self.low=27435.4 
127.0.0.1 - - [30/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30966 

self.closeSec=1693325999, self.tradeDate='20230830', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27632.9, self.close=27698.2, self.high=27716.0, self.low=27597.8 
127.0.0.1 - - [30/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30967 

self.closeSec=1693326299, self.tradeDate='20230830', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27698.2, self.close=27900.8, self.high=27978.2, self.low=27661.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-30 00:00:18,431:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230829    212959  26034.5  ...  49.166667  0.487409  0.633181
5802  20230829    215959  26005.7  ...  49.583333  0.500273  0.627638
5803  20230829    222959  26036.2  ...  50.000000  0.717509  0.599277
5804  20230829    225959  26936.3  ...  50.416667  0.774721  0.567112
5805  20230829    232959  27484.8  ...  50.416667  0.748409  0.540447

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-08-30 00:00:18,490:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     1  0.490365  0.509635       1  ...  0.977433  -1.0  0.0000  0.985529
540     0  0.506925  0.493075       1  ...  0.942936  -1.0  0.0000  1.020312
541     0  0.796431  0.203569       1  ...  0.959832   1.0 -0.0016  1.040226
542     0  0.757033  0.242967       0  ...  0.956706   1.0  0.0000  1.036838
543     0  0.608617  0.391383       1  ...  0.957390   1.0  0.0000  1.037580

[5 rows x 10 columns]
2023-08-30 00:00:18,501:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.489814  0.510186       1  ...  0.979092  -1.0  0.0000  0.982502
46     0  0.506424  0.493576       1  ...  0.944537  -1.0  0.0000  1.017535
47     0  0.794237  0.205763       1  ...  0.961461   1.0 -0.0016  1.039305
48     0  0.754603  0.245397       0  ...  0.958330   1.0  0.0000  1.035920
49     0  0.608617  0.391383       1  ...  0.957390   1.0  0.0000  1.037580

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.567', 'enterprice': '27521.6', 'countrevence': '0', 'unrealprofit': '-2444.2052', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27426', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15479 

self.closeSec=1693322999, self.tradeDate='20230829', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27342', self.close='27391.7'
127.0.0.1 - - [29/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15480 

self.closeSec=1693323599, self.tradeDate='20230829', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27397', self.close='27444'
127.0.0.1 - - [29/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15481 

self.closeSec=1693324199, self.tradeDate='20230829', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27445', self.close='27390'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15482 

self.closeSec=1693324799, self.tradeDate='20230829', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27390', self.close='27411.3'
127.0.0.1 - - [30/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15483 

self.closeSec=1693325399, self.tradeDate='20230830', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27411.4', self.close='27437.3'
127.0.0.1 - - [30/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15484 

self.closeSec=1693325999, self.tradeDate='20230830', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27437.2', self.close='27698.3'
127.0.0.1 - - [30/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [29/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15482 

self.closeSec=1693322999, self.tradeDate='20230829', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27342', self.close='27391.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15483 

self.closeSec=1693323599, self.tradeDate='20230829', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27397', self.close='27444'
127.0.0.1 - - [29/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [29/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15484 

self.closeSec=1693324199, self.tradeDate='20230829', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27445', self.close='27390'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15485 

self.closeSec=1693324799, self.tradeDate='20230829', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27390', self.close='27411.3'
127.0.0.1 - - [30/Aug/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15486 

self.closeSec=1693325399, self.tradeDate='20230830', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27411.4', self.close='27437.3'
127.0.0.1 - - [30/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15487 

self.closeSec=1693325999, self.tradeDate='20230830', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27437.2', self.close='27698.3'
127.0.0.1 - - [30/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15482 

self.closeSec=1693322999, self.tradeDate='20230829', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27342', self.close='27391.7'
127.0.0.1 - - [29/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15483 

self.closeSec=1693323599, self.tradeDate='20230829', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27397', self.close='27444'
127.0.0.1 - - [29/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15484 

self.closeSec=1693324199, self.tradeDate='20230829', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27445', self.close='27390'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15485 

self.closeSec=1693324799, self.tradeDate='20230829', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27390', self.close='27411.3'
127.0.0.1 - - [30/Aug/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15486 

self.closeSec=1693325399, self.tradeDate='20230830', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27411.4', self.close='27437.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15487 

self.closeSec=1693325999, self.tradeDate='20230830', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27437.2', self.close='27698.3'
127.0.0.1 - - [30/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30964
self.closeSec=1693325999, self.tradeDate='20230830', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27632.9, self.close=27698.2, self.high=27716.0, self.low=27597.8, self.vol=10745.019, self.amt=297081295.9193 
127.0.0.1 - - [30/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-30 00:20:05,183:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230829   235500    235959  ...         0.0        0.0       0
5748  20230830   000000    000459  ...         0.0        0.0       0
5749  20230830   000500    000959  ...         0.0        0.0       0
5750  20230830   001000    001459  ...         0.0        0.0       0
5751  20230830   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 00:20:05,186:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693325999, self.tradeDate='20230830', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27632.9, self.close=27698.2, self.high=27716.0, self.low=27597.8, self.vol=10745.019, self.amt=297081295.9193, ukdf['pct'].iloc[-1]=0.002595 , ukdf['amount'].iloc[-1]=297081295.9193, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '33280.23189168639', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27740.05104579', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [30/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30965
self.closeSec=1693326299, self.tradeDate='20230830', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27698.2, self.close=27900.8, self.high=27978.2, self.low=27661.2, self.vol=18359.483, self.amt=510761809.29298 
2023-08-30 00:25:00,822:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230830   000000    000459  ...         0.0        0.0       0
5749  20230830   000500    000959  ...         0.0        0.0       0
5750  20230830   001000    001459  ...         0.0        0.0       0
5751  20230830   001500    001959  ...         0.0        0.0       0
5752  20230830   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 00:25:00,822:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693326299, self.tradeDate='20230830', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27698.2, self.close=27900.8, self.high=27978.2, self.low=27661.2, self.vol=18359.483, self.amt=510761809.29298, ukdf['pct'].iloc[-1]=0.007315 , ukdf['amount'].iloc[-1]=510761809.29298, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '39116.9012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27897.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230829   120000    155959  ...  5.307007e-06 -1.103177    -1.0
724  20230829   160000    195959  ...  1.459807e-07 -1.102574    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '178205.66224791616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25964.75415568', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=645
self.closeSec=1693324799, self.tradeDate='20230829', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25962.2, self.close=27411.3, self.high=27690.0, self.low=25951.7, self.vol=362946.286, self.amt=9819942827.46348 
127.0.0.1 - - [30/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-30 00:00:01,581:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693324799, self.tradeDate='20230829', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25962.2, self.close=27411.3, self.high=27690.0, self.low=25951.7, self.vol=362946.286, self.amt=9819942827.46348 
2023-08-30 00:00:01,596:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230829   040000    075959  ...   25253.358  6.578352e+08  0.004807
722  20230829   080000    115959  ...   22733.617  5.936283e+08 -0.001463
723  20230829   120000    155959  ...   20248.279  5.270296e+08 -0.002927
724  20230829   160000    195959  ...   33052.011  8.583218e+08 -0.001093
725  20230829   200000    235959  ...  362946.286  9.819943e+09  0.055759

[5 rows x 11 columns]
2023-08-30 00:00:02,201:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime  ...          beta    zscore  signal
721  20230829   040000    075959  ...  1.885711e-04 -1.110704    -1.0
722  20230829   080000    115959  ...  3.378700e-07 -1.105306    -1.0
723  20230829   120000    155959  ...  5.307007e-06 -1.103177    -1.0
724  20230829   160000    195959  ...  1.459807e-07 -1.102574    -1.0
725  20230829   200000    235959  ...  2.902323e-06 -1.102490    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '103704.72647704192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27414.52717216', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


