# 20230918 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36436
self.closeSec=1694967599, self.tradeDate='20230918', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26519.2, self.close=26495.6, self.high=26519.2, self.low=26489.1, self.vol=1743.133, self.amt=46197500.4593 
127.0.0.1 - - [18/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-18 00:20:06,405:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230917   235500    235959  ...         0.0        0.0       0
5760  20230918   000000    000459  ...         0.0        0.0       0
5761  20230918   000500    000959  ...         0.0        0.0       0
5762  20230918   001000    001459  ...         0.0        0.0       0
5763  20230918   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 00:20:06,414:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694967599, self.tradeDate='20230918', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26519.2, self.close=26495.6, self.high=26519.2, self.low=26489.1, self.vol=1743.133, self.amt=46197500.4593, ukdf['pct'].iloc[-1]=-0.000886 , ukdf['amount'].iloc[-1]=46197500.4593, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5128.9458', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26496.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36437
self.closeSec=1694967899, self.tradeDate='20230918', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26495.5, self.close=26511.6, self.high=26515.7, self.low=26495.3, self.vol=927.385, self.amt=24582324.6132 
2023-09-18 00:25:00,787:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230918   000000    000459  ...         0.0        0.0       0
5761  20230918   000500    000959  ...         0.0        0.0       0
5762  20230918   001000    001459  ...         0.0        0.0       0
5763  20230918   001500    001959  ...         0.0        0.0       0
5764  20230918   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 00:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694967899, self.tradeDate='20230918', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26495.5, self.close=26511.6, self.high=26515.7, self.low=26495.3, self.vol=927.385, self.amt=24582324.6132, ukdf['pct'].iloc[-1]=0.000604 , ukdf['amount'].iloc[-1]=24582324.6132, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4917.10522234404', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26511.81187546', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [18/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230913' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36436 

self.closeSec=1694966999, self.tradeDate='20230918', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26532.3, self.close=26524.7, self.high=26532.3, self.low=26524.7 
127.0.0.1 - - [18/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36437 

self.closeSec=1694967299, self.tradeDate='20230918', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26524.7, self.close=26519.1, self.high=26524.8, self.low=26518.1 
127.0.0.1 - - [18/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36438 

self.closeSec=1694967599, self.tradeDate='20230918', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26519.2, self.close=26495.6, self.high=26519.2, self.low=26489.1 
127.0.0.1 - - [18/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36439 

self.closeSec=1694967899, self.tradeDate='20230918', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26495.5, self.close=26511.6, self.high=26515.7, self.low=26495.3 
127.0.0.1 - - [18/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-18 00:00:17,695:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230917    212959  26564.1  ...  53.750000  0.521734  0.381525
5802  20230917    215959  26556.9  ...  53.333333  0.510156  0.382502
5803  20230917    222959  26529.5  ...  53.750000  0.519190  0.376289
5804  20230917    225959  26552.3  ...  53.750000  0.508206  0.378673
5805  20230917    232959  26526.0  ...  53.750000  0.518946  0.372435

[5 rows x 33 columns]
0.5588235294117647
acc is : 0.5588235294117647
2023-09-18 00:00:17,752:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.493511  0.506489       0  ...  0.943582   1.0    0.0  1.031670
540     1  0.487051  0.512949       1  ...  0.944396   1.0    0.0  1.032561
541     0  0.501135  0.498865       0  ...  0.943461   1.0    0.0  1.031538
542     1  0.488056  0.511944       1  ...  0.944428   1.0    0.0  1.032596
543     0  0.500373  0.499627       0  ...  0.943852   1.0    0.0  1.031966

[5 rows x 10 columns]
2023-09-18 00:00:17,763:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493690  0.506310       0  ...  0.943582   1.0    0.0  1.030260
46     1  0.487042  0.512958       1  ...  0.944396   1.0    0.0  1.030529
47     0  0.500890  0.499110       0  ...  0.943461   1.0    0.0  1.029436
48     1  0.488294  0.511706       1  ...  0.944428   1.0    0.0  1.030492
49     0  0.500373  0.499627       0  ...  0.943852   1.0    0.0  1.031966

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '-1429.218', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26538.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18215 

self.closeSec=1694964599, self.tradeDate='20230917', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26534.3', self.close='26553.1'
127.0.0.1 - - [17/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18216 

self.closeSec=1694965199, self.tradeDate='20230917', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26553.2', self.close='26523.8'

--handleKline--:  127.0.0.1 - - [17/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18217 

self.closeSec=1694965799, self.tradeDate='20230917', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26523.7', self.close='26536.4'
127.0.0.1 - - [18/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18218 

self.closeSec=1694966399, self.tradeDate='20230917', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26536.4', self.close='26537'
127.0.0.1 - - [18/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18219 

self.closeSec=1694966999, self.tradeDate='20230918', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26536.9', self.close='26524.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18220 

self.closeSec=1694967599, self.tradeDate='20230918', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26524.7', self.close='26495.5'
127.0.0.1 - - [18/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18218 

self.closeSec=1694964599, self.tradeDate='20230917', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26534.3', self.close='26553.1'
127.0.0.1 - - [17/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [17/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18219 

self.closeSec=1694965199, self.tradeDate='20230917', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26553.2', self.close='26523.8'

--handleKline--: 127.0.0.1 - - [17/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18220 

self.closeSec=1694965799, self.tradeDate='20230917', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26523.7', self.close='26536.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18221 

self.closeSec=1694966399, self.tradeDate='20230917', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26536.4', self.close='26537'
127.0.0.1 - - [18/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18222 

self.closeSec=1694966999, self.tradeDate='20230918', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26536.9', self.close='26524.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18223 

self.closeSec=1694967599, self.tradeDate='20230918', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26524.7', self.close='26495.5'
127.0.0.1 - - [18/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18218 

self.closeSec=1694964599, self.tradeDate='20230917', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26534.3', self.close='26553.1'
127.0.0.1 - - [17/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18219 

self.closeSec=1694965199, self.tradeDate='20230917', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26553.2', self.close='26523.8'
127.0.0.1 - - [17/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18220 

self.closeSec=1694965799, self.tradeDate='20230917', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26523.7', self.close='26536.4'
127.0.0.1 - - [18/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18221 

self.closeSec=1694966399, self.tradeDate='20230917', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26536.4', self.close='26537'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18222 

self.closeSec=1694966999, self.tradeDate='20230918', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26536.9', self.close='26524.7'
127.0.0.1 - - [18/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18223 

self.closeSec=1694967599, self.tradeDate='20230918', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26524.7', self.close='26495.5'
127.0.0.1 - - [18/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36436
self.closeSec=1694967599, self.tradeDate='20230918', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26519.2, self.close=26495.6, self.high=26519.2, self.low=26489.1, self.vol=1743.133, self.amt=46197500.4593 
127.0.0.1 - - [18/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-18 00:20:06,407:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230917   235500    235959  ...         0.0        0.0       0
5760  20230918   000000    000459  ...         0.0        0.0       0
5761  20230918   000500    000959  ...         0.0        0.0       0
5762  20230918   001000    001459  ...         0.0        0.0       0
5763  20230918   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 00:20:06,415:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694967599, self.tradeDate='20230918', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26519.2, self.close=26495.6, self.high=26519.2, self.low=26489.1, self.vol=1743.133, self.amt=46197500.4593, ukdf['pct'].iloc[-1]=-0.000886 , ukdf['amount'].iloc[-1]=46197500.4593, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12902.7834', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26496.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36437
self.closeSec=1694967899, self.tradeDate='20230918', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26495.5, self.close=26511.6, self.high=26515.7, self.low=26495.3, self.vol=927.385, self.amt=24582324.6132 
2023-09-18 00:25:00,786:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230918   000000    000459  ...         0.0        0.0       0
5761  20230918   000500    000959  ...         0.0        0.0       0
5762  20230918   001000    001459  ...         0.0        0.0       0
5763  20230918   001500    001959  ...         0.0        0.0       0
5764  20230918   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 00:25:00,786:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694967899, self.tradeDate='20230918', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26495.5, self.close=26511.6, self.high=26515.7, self.low=26495.3, self.vol=927.385, self.amt=24582324.6132, ukdf['pct'].iloc[-1]=0.000604 , ukdf['amount'].iloc[-1]=24582324.6132, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12337.79913354014', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26511.81187546', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230917   040000    075959  ...   9029.999  2.396382e+08  0.000856
722  20230917   080000    115959  ...  24901.582  6.592066e+08 -0.001349
723  20230917   120000    155959  ...  12207.039  3.237591e+08 -0.001075
724  20230917   160000    195959  ...  18581.011  4.934868e+08  0.002692
725  20230917   200000    235959  ...  15182.625  4.030439e+08 -0.000636

[5 rows x 11 columns]
2023-09-18 00:00:02,138:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230917   040000    075959  1694908799  ...    721  0.483101  0.617305     1.0
722  20230917   080000    115959  1694923199  ...    722  0.465218  0.558486     NaN
723  20230917   120000    155959  1694937599  ...    723  0.321356  0.008056     NaN
724  20230917   160000    195959  1694951999  ...    724  0.216169 -0.393143     NaN
725  20230917   200000    235959  1694966399  ...    725  0.153439 -0.627340    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-7596.715', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26537', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-7596.715', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26537', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-09-18 00:00:08,928:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1428677.9363329', 'total': '1428677.9363329', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-09-18 00:00:09,390:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 53.675, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42952F1694966409389I0L65'}
2023-09-18 00:00:09,417:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:9180000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230917, closeTime:235959, close:26537.0, sign:-1, total:1428677.9363329, side:sell  
127.0.0.1 - - [18/Sep/2023 00:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Sep/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-09-18 00:00:09,421:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42951F1694966403851I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1694966404286088, 'quantity': '53.725', 'price': '26536.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1694966402970, 'updatetime': 1694966404286, 'tradetype': 'usdt', 'selfid': 42951, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1694966404286, 'clientorderid': '42951F1694966403851I0L65', 'price': '26536.9', 'quantity': '53.725', 'commission': '1425.6949525', 'commissionasset': 'USDT', 'tradetime': 1694966404286, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1694966404286}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-18 00:00:09,422:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42951F1694966403851I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1694966404286088, 'quantity': '53.725', 'price': '26536.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1694966402970, 'updatetime': 1694966404286, 'tradetype': 'usdt', 'selfid': 42951, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1694966404286, 'clientorderid': '42951F1694966403851I0L65', 'price': '26536.9', 'quantity': '53.725', 'commission': '1425.6949525', 'commissionasset': 'USDT', 'tradetime': 1694966404286, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1694966404286}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-18 00:00:09,845:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42952F1694966409389I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1694966409820450, 'quantity': '53.675', 'price': '26538.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1694966408940, 'updatetime': 1694966409820, 'tradetype': 'usdt', 'selfid': 42952, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1694966409820, 'clientorderid': '42952F1694966409389I0L65', 'price': '26538.7', 'quantity': '53.675', 'commission': '1424.4647225', 'commissionasset': 'USDT', 'tradetime': 1694966409820, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1694966409820}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Sep/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-09-18 00:00:09,998:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42952F1694966409389I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1694966409820450, 'quantity': '53.675', 'price': '26538.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1694966408940, 'updatetime': 1694966409820, 'tradetype': 'usdt', 'selfid': 42952, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1694966409820, 'clientorderid': '42952F1694966409389I0L65', 'price': '26538.7', 'quantity': '53.675', 'commission': '1424.4647225', 'commissionasset': 'USDT', 'tradetime': 1694966409820, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1694966409820}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Sep/2023 00:00:09] "POST / HTTP/1.1" 200 -


