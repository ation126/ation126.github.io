# 20231005 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41332
self.closeSec=1696436399, self.tradeDate='20231005', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27395.0, self.close=27420.1, self.high=27420.1, self.low=27393.8, self.vol=427.293, self.amt=11711534.2291 
127.0.0.1 - - [05/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-05 00:20:06,651:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231004   235500    235959  ...         0.0        0.0       0
5760  20231005   000000    000459  ...         0.0        0.0       0
5761  20231005   000500    000959  ...         0.0        0.0       0
5762  20231005   001000    001459  ...         0.0        0.0       0
5763  20231005   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 00:20:06,661:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696436399, self.tradeDate='20231005', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27395.0, self.close=27420.1, self.high=27420.1, self.low=27393.8, self.vol=427.293, self.amt=11711534.2291, ukdf['pct'].iloc[-1]=0.000953 , ukdf['amount'].iloc[-1]=11711534.2291, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7733.40751509348', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27420.22152198', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41333
self.closeSec=1696436699, self.tradeDate='20231005', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27420.1, self.close=27416.6, self.high=27424.4, self.low=27404.6, self.vol=490.77, self.amt=13455890.489 
2023-10-05 00:25:00,826:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231005   000000    000459  ...         0.0        0.0       0
5761  20231005   000500    000959  ...         0.0        0.0       0
5762  20231005   001000    001459  ...         0.0        0.0       0
5763  20231005   001500    001959  ...         0.0        0.0       0
5764  20231005   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 00:25:00,826:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696436699, self.tradeDate='20231005', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27420.1, self.close=27416.6, self.high=27424.4, self.low=27404.6, self.vol=490.77, self.amt=13455890.489, ukdf['pct'].iloc[-1]=-0.000128 , ukdf['amount'].iloc[-1]=13455890.489, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7682.9742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27416.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1696435499, self.tradeDate='20231005', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27388.3, self.close=27398.2, self.high=27405.5, self.low=27385.8 

--ukdf-hist--: overDate='20230930' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41332 

self.closeSec=1696435799, self.tradeDate='20231005', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27400.5, self.close=27406.5, self.high=27406.5, self.low=27396.0 
127.0.0.1 - - [05/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41333 

self.closeSec=1696436099, self.tradeDate='20231005', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27406.5, self.close=27394.0, self.high=27413.1, self.low=27394.0 
127.0.0.1 - - [05/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41334 

self.closeSec=1696436399, self.tradeDate='20231005', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27395.0, self.close=27420.1, self.high=27420.1, self.low=27393.8 
127.0.0.1 - - [05/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41335 

self.closeSec=1696436699, self.tradeDate='20231005', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27420.1, self.close=27416.6, self.high=27424.4, self.low=27404.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-05 00:00:16,128:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231004    212959  27553.0  ...  55.416667  0.501874  0.325547
5802  20231004    215959  27508.4  ...  55.416667  0.480953  0.333372
5803  20231004    222959  27404.6  ...  55.416667  0.469160  0.348827
5804  20231004    225959  27341.1  ...  55.416667  0.476442  0.358721
5805  20231004    232959  27376.7  ...  55.833333  0.491147  0.358600

[5 rows x 33 columns]
0.5735294117647058
acc is : 0.5735294117647058
2023-10-05 00:00:16,189:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.487985  0.512015       0  ...  0.961428  -1.0    0.0  1.031315
540     1  0.464150  0.535850       0  ...  0.963593  -1.0    0.0  1.028993
541     1  0.471266  0.528734       1  ...  0.962384  -1.0    0.0  1.030284
542     1  0.496623  0.503377       1  ...  0.959895  -1.0    0.0  1.032948
543     0  0.511703  0.488297       0  ...  0.961962  -1.0    0.0  1.030724

[5 rows x 10 columns]
2023-10-05 00:00:16,200:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487877  0.512123       0  ...  0.961428  -1.0    0.0  1.031509
46     1  0.464164  0.535836       0  ...  0.963593  -1.0    0.0  1.029202
47     1  0.471403  0.528597       1  ...  0.962384  -1.0    0.0  1.030625
48     1  0.496756  0.503244       1  ...  0.959895  -1.0    0.0  1.033290
49     0  0.511703  0.488297       0  ...  0.961962  -1.0    0.0  1.030724

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.906', 'enterprice': '28298.9', 'countrevence': '0', 'unrealprofit': '21754.46', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27388.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20663 

self.closeSec=1696433399, self.tradeDate='20231004', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27429.9', self.close='27447.5'
127.0.0.1 - - [04/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20664 

self.closeSec=1696433999, self.tradeDate='20231004', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27447.6', self.close='27455'
127.0.0.1 - - [04/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [04/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20665 

self.closeSec=1696434599, self.tradeDate='20231004', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27456.4', self.close='27429.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20666 

self.closeSec=1696435199, self.tradeDate='20231004', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27429.6', self.close='27388.4'
127.0.0.1 - - [05/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20667 

self.closeSec=1696435799, self.tradeDate='20231005', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27388.3', self.close='27406.5'
127.0.0.1 - - [05/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20668 

self.closeSec=1696436399, self.tradeDate='20231005', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27406.5', self.close='27420.1'
127.0.0.1 - - [05/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20666 

self.closeSec=1696433399, self.tradeDate='20231004', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27429.9', self.close='27447.5'
127.0.0.1 - - [04/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20667 

self.closeSec=1696433999, self.tradeDate='20231004', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27447.6', self.close='27455'
127.0.0.1 - - [04/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20668 

self.closeSec=1696434599, self.tradeDate='20231004', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27456.4', self.close='27429.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20669 

self.closeSec=1696435199, self.tradeDate='20231004', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27429.6', self.close='27388.4'
127.0.0.1 - - [05/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20670 

self.closeSec=1696435799, self.tradeDate='20231005', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27388.3', self.close='27406.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20671 

self.closeSec=1696436399, self.tradeDate='20231005', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27406.5', self.close='27420.1'
127.0.0.1 - - [05/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20666 

self.closeSec=1696433399, self.tradeDate='20231004', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27429.9', self.close='27447.5'
127.0.0.1 - - [04/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [04/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20667 

self.closeSec=1696433999, self.tradeDate='20231004', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27447.6', self.close='27455'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20668 

self.closeSec=1696434599, self.tradeDate='20231004', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27456.4', self.close='27429.7'
127.0.0.1 - - [04/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20669 

self.closeSec=1696435199, self.tradeDate='20231004', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27429.6', self.close='27388.4'
127.0.0.1 - - [05/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20670 

self.closeSec=1696435799, self.tradeDate='20231005', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27388.3', self.close='27406.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20671 

self.closeSec=1696436399, self.tradeDate='20231005', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27406.5', self.close='27420.1'
127.0.0.1 - - [05/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41332
self.closeSec=1696436399, self.tradeDate='20231005', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27395.0, self.close=27420.1, self.high=27420.1, self.low=27393.8, self.vol=427.293, self.amt=11711534.2291 
127.0.0.1 - - [05/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-05 00:20:06,650:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231004   235500    235959  ...         0.0        0.0       0
5760  20231005   000000    000459  ...         0.0        0.0       0
5761  20231005   000500    000959  ...         0.0        0.0       0
5762  20231005   001000    001459  ...         0.0        0.0       0
5763  20231005   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 00:20:06,660:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696436399, self.tradeDate='20231005', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27395.0, self.close=27420.1, self.high=27420.1, self.low=27393.8, self.vol=427.293, self.amt=11711534.2291, ukdf['pct'].iloc[-1]=0.000953 , ukdf['amount'].iloc[-1]=11711534.2291, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '21401.44354785918', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27420.22152198', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41333
self.closeSec=1696436699, self.tradeDate='20231005', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27420.1, self.close=27416.6, self.high=27424.4, self.low=27404.6, self.vol=490.77, self.amt=13455890.489 
2023-10-05 00:25:00,832:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231005   000000    000459  ...         0.0        0.0       0
5761  20231005   000500    000959  ...         0.0        0.0       0
5762  20231005   001000    001459  ...         0.0        0.0       0
5763  20231005   001500    001959  ...         0.0        0.0       0
5764  20231005   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 00:25:00,832:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696436699, self.tradeDate='20231005', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27420.1, self.close=27416.6, self.high=27424.4, self.low=27404.6, self.vol=490.77, self.amt=13455890.489, ukdf['pct'].iloc[-1]=-0.000128 , ukdf['amount'].iloc[-1]=13455890.489, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '21266.9366', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27416.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231004   120000    155959  1696406399  ...    723  1.082437  0.808364     1.0
724  20231004   160000    195959  1696420799  ...    724  1.012130  0.633837     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-19914.10083331396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27560.13320147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [05/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1223948.6721539998, self.flagDict['side']='buy', self.tradeCount=29, self.count=861
self.closeSec=1696435199, self.tradeDate='20231004', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27560.0, self.close=27388.4, self.high=27619.4, self.low=27317.1, self.vol=55560.01, self.amt=1525355458.33136 
2023-10-05 00:00:01,566:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696435199, self.tradeDate='20231004', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27560.0, self.close=27388.4, self.high=27619.4, self.low=27317.1, self.vol=55560.01, self.amt=1525355458.33136 
2023-10-05 00:00:01,579:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231004   040000    075959  ...  48321.199  1.320651e+09  0.005436
722  20231004   080000    115959  ...  57219.623  1.564484e+09  0.000208
723  20231004   120000    155959  ...  18070.915  4.949720e+08  0.000883
724  20231004   160000    195959  ...  43059.184  1.185835e+09  0.004304
725  20231004   200000    235959  ...  55560.010  1.525355e+09 -0.006226

[5 rows x 11 columns]
2023-10-05 00:00:02,231:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231004   040000    075959  1696377599  ...    721  1.186991  1.095715     1.0
722  20231004   080000    115959  1696391999  ...    722  1.151617  0.991374     1.0
723  20231004   120000    155959  1696406399  ...    723  1.082437  0.808364     1.0
724  20231004   160000    195959  1696420799  ...    724  1.012130  0.633837     1.0
725  20231004   200000    235959  1696435199  ...    725  0.955153  0.504670     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-27382.87573963812', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27389.34808059', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


