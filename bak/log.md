# 20230823 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28948
self.closeSec=1692721199, self.tradeDate='20230823', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25876.7, self.close=25885.7, self.high=25913.3, self.low=25834.3, self.vol=4461.866, self.amt=115442727.1764 
127.0.0.1 - - [23/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-23 00:20:05,292:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230822   235500    235959  ...         0.0        0.0       0
5748  20230823   000000    000459  ...         0.0        0.0       0
5749  20230823   000500    000959  ...         0.0        0.0       0
5750  20230823   001000    001459  ...         0.0        0.0       0
5751  20230823   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 00:20:05,306:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692721199, self.tradeDate='20230823', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25876.7, self.close=25885.7, self.high=25913.3, self.low=25834.3, self.vol=4461.866, self.amt=115442727.1764, ukdf['pct'].iloc[-1]=0.000429 , ukdf['amount'].iloc[-1]=115442727.1764, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13707.0479803752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25880.6225348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28949
self.closeSec=1692721499, self.tradeDate='20230823', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25882.5, self.close=25855.1, self.high=25901.6, self.low=25808.3, self.vol=4109.397, self.amt=106219553.1062 
127.0.0.1 - - [23/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-23 00:25:00,789:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230823   000000    000459  ...         0.0        0.0       0
5749  20230823   000500    000959  ...         0.0        0.0       0
5750  20230823   001000    001459  ...         0.0        0.0       0
5751  20230823   001500    001959  ...         0.0        0.0       0
5752  20230823   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 00:25:00,790:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692721499, self.tradeDate='20230823', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25882.5, self.close=25855.1, self.high=25901.6, self.low=25808.3, self.vol=4109.397, self.amt=106219553.1062, ukdf['pct'].iloc[-1]=-0.001182 , ukdf['amount'].iloc[-1]=106219553.1062, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14037.408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25856.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [23/Aug/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230818' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [23/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28948 

self.closeSec=1692720599, self.tradeDate='20230823', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25913.1, self.close=25907.3, self.high=25935.2, self.low=25900.0 
127.0.0.1 - - [23/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28949 

self.closeSec=1692720899, self.tradeDate='20230823', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25907.3, self.close=25874.6, self.high=25915.4, self.low=25870.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28950 

self.closeSec=1692721199, self.tradeDate='20230823', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25876.7, self.close=25885.7, self.high=25913.3, self.low=25834.3 
127.0.0.1 - - [23/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28951 

self.closeSec=1692721499, self.tradeDate='20230823', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25882.5, self.close=25855.1, self.high=25901.6, self.low=25808.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-23 00:00:17,338:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230822    212959  26028.5  ...  47.916667  0.470508  0.553529
5802  20230822    215959  26008.7  ...  47.916667  0.463224  0.575779
5803  20230822    222959  25986.2  ...  48.333333  0.465880  0.589904
5804  20230822    225959  25993.9  ...  47.916667  0.461087  0.605658
5805  20230822    232959  25980.1  ...  47.916667  0.469207  0.616617

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-08-23 00:00:17,395:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.485223  0.514777       0  ...  1.095569  -1.0    0.0  0.882924
540     1  0.479121  0.520879       1  ...  1.095283  -1.0    0.0  0.883155
541     1  0.488823  0.511177       0  ...  1.095873  -1.0    0.0  0.882680
542     1  0.479420  0.520580       1  ...  1.095012  -1.0    0.0  0.883373
543     1  0.494636  0.505364       0  ...  1.098272  -1.0    0.0  0.880743

[5 rows x 10 columns]
2023-08-23 00:00:17,406:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485263  0.514737       0  ...  1.095569  -1.0    0.0  0.882424
46     1  0.479810  0.520190       1  ...  1.095283  -1.0    0.0  0.883275
47     1  0.488830  0.511170       0  ...  1.095873  -1.0    0.0  0.882140
48     1  0.480072  0.519928       1  ...  1.095012  -1.0    0.0  0.882833
49     1  0.494636  0.505364       0  ...  1.098272  -1.0    0.0  0.880743

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '4334.07126734903', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25920.88462637', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14471 

self.closeSec=1692718199, self.tradeDate='20230822', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25998.5', self.close='26000.4'
127.0.0.1 - - [22/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14472 

self.closeSec=1692718799, self.tradeDate='20230822', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26000.4', self.close='25978.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14473 

self.closeSec=1692719399, self.tradeDate='20230822', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25978.4', self.close='25957.5'
127.0.0.1 - - [22/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14474 

self.closeSec=1692719999, self.tradeDate='20230822', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25957.4', self.close='25923'
127.0.0.1 - - [23/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14475 

self.closeSec=1692720599, self.tradeDate='20230823', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25923', self.close='25907.3'
127.0.0.1 - - [23/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14476 

self.closeSec=1692721199, self.tradeDate='20230823', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25907.3', self.close='25885.7'
127.0.0.1 - - [23/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14474 

self.closeSec=1692718199, self.tradeDate='20230822', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25998.5', self.close='26000.4'
127.0.0.1 - - [22/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14475 

self.closeSec=1692718799, self.tradeDate='20230822', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26000.4', self.close='25978.5'
127.0.0.1 - - [22/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14476 

self.closeSec=1692719399, self.tradeDate='20230822', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25978.4', self.close='25957.5'
127.0.0.1 - - [22/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14477 

self.closeSec=1692719999, self.tradeDate='20230822', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25957.4', self.close='25923'
127.0.0.1 - - [23/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14478 

self.closeSec=1692720599, self.tradeDate='20230823', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25923', self.close='25907.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14479 

self.closeSec=1692721199, self.tradeDate='20230823', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25907.3', self.close='25885.7'
127.0.0.1 - - [23/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14474 

self.closeSec=1692718199, self.tradeDate='20230822', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25998.5', self.close='26000.4'
127.0.0.1 - - [22/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14475 

self.closeSec=1692718799, self.tradeDate='20230822', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26000.4', self.close='25978.5'
127.0.0.1 - - [22/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14476 

self.closeSec=1692719399, self.tradeDate='20230822', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25978.4', self.close='25957.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14477 

self.closeSec=1692719999, self.tradeDate='20230822', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25957.4', self.close='25923'
127.0.0.1 - - [23/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14478 

self.closeSec=1692720599, self.tradeDate='20230823', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25923', self.close='25907.3'
127.0.0.1 - - [23/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14479 

self.closeSec=1692721199, self.tradeDate='20230823', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25907.3', self.close='25885.7'
127.0.0.1 - - [23/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28948
self.closeSec=1692721199, self.tradeDate='20230823', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25876.7, self.close=25885.7, self.high=25913.3, self.low=25834.3, self.vol=4461.866, self.amt=115442727.1764 
127.0.0.1 - - [23/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-23 00:20:05,293:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230822   235500    235959  ...         0.0        0.0       0
5748  20230823   000000    000459  ...         0.0        0.0       0
5749  20230823   000500    000959  ...         0.0        0.0       0
5750  20230823   001000    001459  ...         0.0        0.0       0
5751  20230823   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 00:20:05,306:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692721199, self.tradeDate='20230823', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25876.7, self.close=25885.7, self.high=25913.3, self.low=25834.3, self.vol=4461.866, self.amt=115442727.1764, ukdf['pct'].iloc[-1]=0.000429 , ukdf['amount'].iloc[-1]=115442727.1764, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35780.8024349932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25880.6225348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [23/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28949
self.closeSec=1692721499, self.tradeDate='20230823', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25882.5, self.close=25855.1, self.high=25901.6, self.low=25808.3, self.vol=4109.397, self.amt=106219553.1062 
2023-08-23 00:25:00,785:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230823   000000    000459  ...         0.0        0.0       0
5749  20230823   000500    000959  ...         0.0        0.0       0
5750  20230823   001000    001459  ...         0.0        0.0       0
5751  20230823   001500    001959  ...         0.0        0.0       0
5752  20230823   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 00:25:00,786:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692721499, self.tradeDate='20230823', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25882.5, self.close=25855.1, self.high=25901.6, self.low=25808.3, self.vol=4109.397, self.amt=106219553.1062, ukdf['pct'].iloc[-1]=-0.001182 , ukdf['amount'].iloc[-1]=106219553.1062, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36661.8811', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25856.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230822   120000    155959  1692691199  ...    723  0.073155 -0.944331    -1.0
724  20230822   160000    195959  1692705599  ...    724  0.030819 -1.035881    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174300.88426820396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26040.74033883', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=603
self.closeSec=1692719999, self.tradeDate='20230822', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26039.0, self.close=25923.0, self.high=26087.2, self.low=25900.0, self.vol=44562.768, self.amt=1158461645.4287 
127.0.0.1 - - [23/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-23 00:00:01,537:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692719999, self.tradeDate='20230822', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26039.0, self.close=25923.0, self.high=26087.2, self.low=25900.0, self.vol=44562.768, self.amt=1158461645.4287 
2023-08-23 00:00:01,551:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230822   040000    075959  ...  24701.899  6.458832e+08  0.001119
722  20230822   080000    115959  ...  15716.085  4.095923e+08 -0.002803
723  20230822   120000    155959  ...  18541.356  4.827876e+08  0.001897
724  20230822   160000    195959  ...  15537.931  4.046899e+08 -0.002016
725  20230822   200000    235959  ...  44562.768  1.158462e+09 -0.004455

[5 rows x 11 columns]
2023-08-23 00:00:02,243:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230822   040000    075959  1692662399  ...    721  0.187173 -0.684183    -1.0
722  20230822   080000    115959  1692676799  ...    722  0.228351 -0.594178     NaN
723  20230822   120000    155959  1692691199  ...    723  0.073155 -0.944331    -1.0
724  20230822   160000    195959  1692705599  ...    724  0.030819 -1.035881    -1.0
725  20230822   200000    235959  1692719999  ...    725  0.000080 -1.102173    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '180170.00054773764', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25926.52853297', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


