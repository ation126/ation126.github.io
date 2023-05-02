# 20230502 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44853
self.closeSec=1682986799, self.tradeDate='20230502', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27987.4, self.close=27994.3, self.high=28000.0, self.low=27984.6, self.vol=464.534, self.amt=13004334.2131 
127.0.0.1 - - [02/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-02 08:20:06,028:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230502   075500    075959  ...         0.0        0.0       0
5856  20230502   080000    080459  ...         0.0        0.0       0
5857  20230502   080500    080959  ...         0.0        0.0       0
5858  20230502   081000    081459  ...         0.0        0.0       0
5859  20230502   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 08:20:06,038:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682986799, self.tradeDate='20230502', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27987.4, self.close=27994.3, self.high=28000.0, self.low=27984.6, self.vol=464.534, self.amt=13004334.2131, ukdf['pct'].iloc[-1]=0.000247 , ukdf['amount'].iloc[-1]=13004334.2131, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-689965.9808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27995.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44854
self.closeSec=1682987099, self.tradeDate='20230502', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27994.3, self.close=27976.3, self.high=27997.1, self.low=27963.5, self.vol=903.557, self.amt=25278592.8456 
127.0.0.1 - - [02/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-05-02 08:25:02,070:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230502   080000    080459  ...         0.0        0.0       0
5857  20230502   080500    080959  ...         0.0        0.0       0
5858  20230502   081000    081459  ...         0.0        0.0       0
5859  20230502   081500    081959  ...         0.0        0.0       0
5860  20230502   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 08:25:02,070:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682987099, self.tradeDate='20230502', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27994.3, self.close=27976.3, self.high=27997.1, self.low=27963.5, self.vol=903.557, self.amt=25278592.8456, ukdf['pct'].iloc[-1]=-0.000643 , ukdf['amount'].iloc[-1]=25278592.8456, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-688834.78303916224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27976.30184524', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45415 

self.closeSec=1682985599, self.tradeDate='20230502', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28069.7, self.close=28054.4, self.high=28074.4, self.low=28044.0 
127.0.0.1 - - [02/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45416 

self.closeSec=1682985899, self.tradeDate='20230502', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28054.5, self.close=27994.3, self.high=28054.5, self.low=27981.5 
127.0.0.1 - - [02/May/2023 08:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45417 

self.closeSec=1682986199, self.tradeDate='20230502', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27994.4, self.close=28047.2, self.high=28047.2, self.low=27967.7 
127.0.0.1 - - [02/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45418 

self.closeSec=1682986499, self.tradeDate='20230502', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28047.2, self.close=27987.4, self.high=28047.2, self.low=27977.5 
127.0.0.1 - - [02/May/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45419 

self.closeSec=1682986799, self.tradeDate='20230502', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27987.4, self.close=27994.3, self.high=28000.0, self.low=27984.6 
127.0.0.1 - - [02/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/May/2023 08:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45420 

self.closeSec=1682987099, self.tradeDate='20230502', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27994.3, self.close=27976.3, self.high=27997.1, self.low=27963.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-02 08:00:22,325:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230502    052959  27663.7  ...  48.750000  0.377586  0.847616
5770  20230502    055959  27873.8  ...  48.750000  0.394511  0.837121
5771  20230502    062959  27975.2  ...  48.750000  0.392964  0.828240
5772  20230502    065959  27960.8  ...  49.166667  0.399786  0.817354
5773  20230502    072959  28001.7  ...  49.166667  0.412808  0.802172

[5 rows x 33 columns]
0.5611111111111111
acc is : 0.5611111111111111
2023-05-02 08:00:22,456:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.545113  0.454887       1  ...  0.880489   1.0    0.0  0.983619
536     0  0.542839  0.457161       0  ...  0.880036   1.0    0.0  0.983113
537     0  0.533335  0.466665       1  ...  0.881323   1.0    0.0  0.984551
538     0  0.547187  0.452813       1  ...  0.883812   1.0    0.0  0.987332
539     0  0.573966  0.426034       0  ...  0.882978   1.0    0.0  0.986400

[5 rows x 10 columns]
2023-05-02 08:00:22,483:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.544295  0.455705       1  ...  0.880489   1.0    0.0  0.981855
46     0  0.543193  0.456807       0  ...  0.880036   1.0    0.0  0.978924
47     0  0.533372  0.466628       1  ...  0.881323   1.0    0.0  0.984869
48     0  0.547757  0.452243       1  ...  0.883812   1.0    0.0  0.983373
49     0  0.573966  0.426034       0  ...  0.882978   1.0    0.0  0.986400

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [02/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22705 

self.closeSec=1682983799, self.tradeDate='20230502', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28100.5', self.close='28080.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22706 

self.closeSec=1682984399, self.tradeDate='20230502', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28081', self.close='28101'
127.0.0.1 - - [02/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22707 

self.closeSec=1682984999, self.tradeDate='20230502', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28101', self.close='28081.8'
127.0.0.1 - - [02/May/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22708 

self.closeSec=1682985599, self.tradeDate='20230502', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28081.8', self.close='28054.4'
127.0.0.1 - - [02/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22709 

self.closeSec=1682986199, self.tradeDate='20230502', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28054.5', self.close='28047.2'
127.0.0.1 - - [02/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22710 

self.closeSec=1682986799, self.tradeDate='20230502', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28047.2', self.close='27994.3'
127.0.0.1 - - [02/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [02/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22706 

self.closeSec=1682983799, self.tradeDate='20230502', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28100.5', self.close='28080.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22707 

self.closeSec=1682984399, self.tradeDate='20230502', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28081', self.close='28101'
127.0.0.1 - - [02/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22708 

self.closeSec=1682984999, self.tradeDate='20230502', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28101', self.close='28081.8'
127.0.0.1 - - [02/May/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22709 

self.closeSec=1682985599, self.tradeDate='20230502', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28081.8', self.close='28054.4'
127.0.0.1 - - [02/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22710 

self.closeSec=1682986199, self.tradeDate='20230502', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28054.5', self.close='28047.2'
127.0.0.1 - - [02/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22711 

self.closeSec=1682986799, self.tradeDate='20230502', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28047.2', self.close='27994.3'
127.0.0.1 - - [02/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22706 

self.closeSec=1682983799, self.tradeDate='20230502', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28100.5', self.close='28080.9'
127.0.0.1 - - [02/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22707 

self.closeSec=1682984399, self.tradeDate='20230502', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28081', self.close='28101'
127.0.0.1 - - [02/May/2023 07:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/May/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22708 

self.closeSec=1682984999, self.tradeDate='20230502', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28101', self.close='28081.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22709 

self.closeSec=1682985599, self.tradeDate='20230502', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28081.8', self.close='28054.4'
127.0.0.1 - - [02/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22710 

self.closeSec=1682986199, self.tradeDate='20230502', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28054.5', self.close='28047.2'
127.0.0.1 - - [02/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22711 

self.closeSec=1682986799, self.tradeDate='20230502', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28047.2', self.close='27994.3'
127.0.0.1 - - [02/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40851
self.closeSec=1682986799, self.tradeDate='20230502', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27987.4, self.close=27994.3, self.high=28000.0, self.low=27984.6, self.vol=464.534, self.amt=13004334.2131 
127.0.0.1 - - [02/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-02 08:20:05,841:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230502   075500    075959  ...         0.0        0.0       0
5856  20230502   080000    080459  ...         0.0        0.0       0
5857  20230502   080500    080959  ...         0.0        0.0       0
5858  20230502   081000    081459  ...         0.0        0.0       0
5859  20230502   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 08:20:05,844:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682986799, self.tradeDate='20230502', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27987.4, self.close=27994.3, self.high=28000.0, self.low=27984.6, self.vol=464.534, self.amt=13004334.2131, ukdf['pct'].iloc[-1]=0.000247 , ukdf['amount'].iloc[-1]=13004334.2131, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40852
self.closeSec=1682987099, self.tradeDate='20230502', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27994.3, self.close=27976.3, self.high=27997.1, self.low=27963.5, self.vol=903.557, self.amt=25278592.8456 
127.0.0.1 - - [02/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-05-02 08:25:02,084:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230502   080000    080459  ...         0.0        0.0       0
5857  20230502   080500    080959  ...         0.0        0.0       0
5858  20230502   081000    081459  ...         0.0        0.0       0
5859  20230502   081500    081959  ...         0.0        0.0       0
5860  20230502   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 08:25:02,085:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682987099, self.tradeDate='20230502', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27994.3, self.close=27976.3, self.high=27997.1, self.low=27963.5, self.vol=903.557, self.amt=25278592.8456, ukdf['pct'].iloc[-1]=-0.000643 , ukdf['amount'].iloc[-1]=25278592.8456, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230501   200000    235959  1682956799  ...    719  0.199479 -1.238036    -1.0
720  20230502   000000    035959  1682971199  ...    720  0.349701 -0.784732    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '70691.13017117396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27828.15452778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [02/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=946
self.closeSec=1682985599, self.tradeDate='20230502', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27833.9, self.close=28054.4, self.high=28143.0, self.low=27650.0, self.vol=85032.81, self.amt=2372993526.32724 
2023-05-02 08:00:03,211:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682985599, self.tradeDate='20230502', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27833.9, self.close=28054.4, self.high=28143.0, self.low=27650.0, self.vol=85032.81, self.amt=2372993526.32724 
2023-05-02 08:00:03,254:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230501   120000    155959  ...   77991.238  2.223718e+09  0.002256
718  20230501   160000    195959  ...   39461.984  1.126488e+09 -0.003474
719  20230501   200000    235959  ...  130179.626  3.688902e+09 -0.012357
720  20230502   000000    035959  ...  148882.200  4.182104e+09 -0.011521
721  20230502   040000    075959  ...   85032.810  2.372994e+09  0.007922

[5 rows x 11 columns]
2023-05-02 08:00:04,928:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230501   120000    155959  1682927999  ...    717  0.057037 -1.678771    -1.0
718  20230501   160000    195959  1682942399  ...    718  0.124316 -1.464028    -1.0
719  20230501   200000    235959  1682956799  ...    719  0.199479 -1.238036    -1.0
720  20230502   000000    035959  1682971199  ...    720  0.349701 -0.784732    -1.0
721  20230502   040000    075959  1682985599  ...    721  0.467685 -0.435252     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '60560.5434', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28045', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


