# 20230826 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29812
self.closeSec=1692980399, self.tradeDate='20230826', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25950.0, self.close=25962.2, self.high=25962.2, self.low=25941.2, self.vol=598.821, self.amt=15540072.7588 
127.0.0.1 - - [26/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-26 00:20:05,264:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230825   235500    235959  ...         0.0        0.0       0
5748  20230826   000000    000459  ...         0.0        0.0       0
5749  20230826   000500    000959  ...         0.0        0.0       0
5750  20230826   001000    001459  ...         0.0        0.0       0
5751  20230826   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 00:20:05,274:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692980399, self.tradeDate='20230826', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25950.0, self.close=25962.2, self.high=25962.2, self.low=25941.2, self.vol=598.821, self.amt=15540072.7588, ukdf['pct'].iloc[-1]=0.000474 , ukdf['amount'].iloc[-1]=15540072.7588, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12600.2448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25960.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29813
self.closeSec=1692980699, self.tradeDate='20230826', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25962.1, self.close=25984.7, self.high=25986.1, self.low=25951.5, self.vol=1090.141, self.amt=28313119.7717 
2023-08-26 00:25:00,800:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230826   000000    000459  ...         0.0        0.0       0
5749  20230826   000500    000959  ...         0.0        0.0       0
5750  20230826   001000    001459  ...         0.0        0.0       0
5751  20230826   001500    001959  ...         0.0        0.0       0
5752  20230826   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 00:25:00,801:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692980699, self.tradeDate='20230826', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25962.1, self.close=25984.7, self.high=25986.1, self.low=25951.5, self.vol=1090.141, self.amt=28313119.7717, ukdf['pct'].iloc[-1]=0.000867 , ukdf['amount'].iloc[-1]=28313119.7717, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12274.3764', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25983.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1692979499, self.tradeDate='20230826', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=25917.3, self.close=25927.0, self.high=25950.0, self.low=25915.0 

--ukdf-hist--: overDate='20230821' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29812 

self.closeSec=1692979799, self.tradeDate='20230826', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25924.3, self.close=25945.3, self.high=25945.3, self.low=25909.3 
127.0.0.1 - - [26/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [26/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -
version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29813 

self.closeSec=1692980099, self.tradeDate='20230826', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25945.4, self.close=25949.9, self.high=25957.2, self.low=25921.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29814 

self.closeSec=1692980399, self.tradeDate='20230826', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25950.0, self.close=25962.2, self.high=25962.2, self.low=25941.2 
127.0.0.1 - - [26/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29815 

self.closeSec=1692980699, self.tradeDate='20230826', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25962.1, self.close=25984.7, self.high=25986.1, self.low=25951.5 
127.0.0.1 - - [26/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-26 00:00:17,291:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230825    212959  26095.5  ...  50.000000  0.502577  0.502479
5802  20230825    215959  26159.0  ...  50.000000  0.476403  0.505996
5803  20230825    222959  26056.3  ...  50.416667  0.477214  0.514343
5804  20230825    225959  26059.2  ...  50.416667  0.424137  0.538509
5805  20230825    232959  25821.5  ...  50.833333  0.467033  0.540475

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-08-26 00:00:17,386:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.508813  0.491187       0  ...  1.052171  -1.0    0.0  0.886476
540     1  0.443814  0.556186       1  ...  1.052049  -1.0    0.0  0.886578
541     1  0.480047  0.519953       0  ...  1.061642  -1.0    0.0  0.878495
542     1  0.379644  0.620356       1  ...  1.054714  -1.0    0.0  0.884228
543     0  0.527742  0.472258       0  ...  1.057624  -1.0    0.0  0.881788

[5 rows x 10 columns]
2023-08-26 00:00:17,407:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508834  0.491166       0  ...  1.052171  -1.0    0.0  0.885181
46     1  0.443571  0.556429       1  ...  1.052049  -1.0    0.0  0.886253
47     1  0.479983  0.520017       0  ...  1.061642  -1.0    0.0  0.878041
48     1  0.379193  0.620807       1  ...  1.054714  -1.0    0.0  0.883771
49     0  0.527742  0.472258       0  ...  1.057624  -1.0    0.0  0.881788

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '13635.573', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14903 

self.closeSec=1692977399, self.tradeDate='20230825', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25962.8', self.close='25990.1'
127.0.0.1 - - [25/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14904 

self.closeSec=1692977999, self.tradeDate='20230825', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25989.9', self.close='25980.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14905 

self.closeSec=1692978599, self.tradeDate='20230825', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25980.9', self.close='25933.5'
127.0.0.1 - - [25/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14906 

self.closeSec=1692979199, self.tradeDate='20230825', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25933.5', self.close='25917.4'
127.0.0.1 - - [26/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14907 

self.closeSec=1692979799, self.tradeDate='20230826', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25917.3', self.close='25945.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14908 

self.closeSec=1692980399, self.tradeDate='20230826', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25945.4', self.close='25962.2'
127.0.0.1 - - [26/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [25/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14906 

self.closeSec=1692977399, self.tradeDate='20230825', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25962.8', self.close='25990.1'
127.0.0.1 - - [25/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14907 

self.closeSec=1692977999, self.tradeDate='20230825', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25989.9', self.close='25980.9'
127.0.0.1 - - [25/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14908 

self.closeSec=1692978599, self.tradeDate='20230825', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25980.9', self.close='25933.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14909 

self.closeSec=1692979199, self.tradeDate='20230825', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25933.5', self.close='25917.4'
127.0.0.1 - - [26/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14910 

self.closeSec=1692979799, self.tradeDate='20230826', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25917.3', self.close='25945.3'
127.0.0.1 - - [26/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14911 

self.closeSec=1692980399, self.tradeDate='20230826', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25945.4', self.close='25962.2'
127.0.0.1 - - [26/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14906 

self.closeSec=1692977399, self.tradeDate='20230825', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25962.8', self.close='25990.1'
127.0.0.1 - - [25/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14907 

self.closeSec=1692977999, self.tradeDate='20230825', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25989.9', self.close='25980.9'

--handleKline--:  127.0.0.1 - - [25/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14908 

self.closeSec=1692978599, self.tradeDate='20230825', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25980.9', self.close='25933.5'
127.0.0.1 - - [26/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14909 

self.closeSec=1692979199, self.tradeDate='20230825', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25933.5', self.close='25917.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14910 

self.closeSec=1692979799, self.tradeDate='20230826', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25917.3', self.close='25945.3'
127.0.0.1 - - [26/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14911 

self.closeSec=1692980399, self.tradeDate='20230826', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25945.4', self.close='25962.2'
127.0.0.1 - - [26/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29812
self.closeSec=1692980399, self.tradeDate='20230826', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25950.0, self.close=25962.2, self.high=25962.2, self.low=25941.2, self.vol=598.821, self.amt=15540072.7588 
127.0.0.1 - - [26/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-26 00:20:05,257:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230825   235500    235959  ...         0.0        0.0       0
5748  20230826   000000    000459  ...         0.0        0.0       0
5749  20230826   000500    000959  ...         0.0        0.0       0
5750  20230826   001000    001459  ...         0.0        0.0       0
5751  20230826   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 00:20:05,265:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692980399, self.tradeDate='20230826', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25950.0, self.close=25962.2, self.high=25962.2, self.low=25941.2, self.vol=598.821, self.amt=15540072.7588, ukdf['pct'].iloc[-1]=0.000474 , ukdf['amount'].iloc[-1]=15540072.7588, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-32828.9299', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25960.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29813
self.closeSec=1692980699, self.tradeDate='20230826', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25962.1, self.close=25984.7, self.high=25986.1, self.low=25951.5, self.vol=1090.141, self.amt=28313119.7717 
2023-08-26 00:25:00,798:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230826   000000    000459  ...         0.0        0.0       0
5749  20230826   000500    000959  ...         0.0        0.0       0
5750  20230826   001000    001459  ...         0.0        0.0       0
5751  20230826   001500    001959  ...         0.0        0.0       0
5752  20230826   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 00:25:00,798:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692980699, self.tradeDate='20230826', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25962.1, self.close=25984.7, self.high=25986.1, self.low=25951.5, self.vol=1090.141, self.amt=28313119.7717, ukdf['pct'].iloc[-1]=0.000867 , ukdf['amount'].iloc[-1]=28313119.7717, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31959.8305', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25983.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230825   120000    155959  1692950399  ...    723  0.195809 -0.474029     NaN
724  20230825   160000    195959  1692964799  ...    724  0.195125 -0.459209     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '171887.7212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26087.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=621
self.closeSec=1692979199, self.tradeDate='20230825', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26087.7, self.close=25917.4, self.high=26300.0, self.low=25754.4, self.vol=138297.912, self.amt=3598671867.79923 
127.0.0.1 - - [26/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-26 00:00:01,556:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692979199, self.tradeDate='20230825', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26087.7, self.close=25917.4, self.high=26300.0, self.low=25754.4, self.vol=138297.912, self.amt=3598671867.79923 
2023-08-26 00:00:01,571:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230825   040000    075959  ...   30501.019  7.950300e+08  0.005391
722  20230825   080000    115959  ...   21737.921  5.674885e+08 -0.002652
723  20230825   120000    155959  ...   28254.409  7.352599e+08 -0.004817
724  20230825   160000    195959  ...   23053.719  6.011113e+08  0.004555
725  20230825   200000    235959  ...  138297.912  3.598672e+09 -0.006528

[5 rows x 11 columns]
2023-08-26 00:00:02,326:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230825   040000    075959  1692921599  ...    721  0.186231 -0.532023     NaN
722  20230825   080000    115959  1692935999  ...    722  0.188793 -0.508607     NaN
723  20230825   120000    155959  1692950399  ...    723  0.195809 -0.474029     NaN
724  20230825   160000    195959  1692964799  ...    724  0.195125 -0.459209     NaN
725  20230825   200000    235959  1692979199  ...    725  0.159068 -0.535499     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '180618.26757748988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25917.80534799', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


