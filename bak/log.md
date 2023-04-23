# 20230423 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42261
self.closeSec=1682209199, self.tradeDate='20230423', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27735.0, self.close=27749.0, self.high=27749.5, self.low=27710.8, self.vol=1624.098, self.amt=45044677.2201 
127.0.0.1 - - [23/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-23 08:20:05,167:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230423   075500    075959  ...         0.0        0.0       0
5849  20230423   080000    080459  ...         0.0        0.0       0
5850  20230423   080500    080959  ...         0.0        0.0       0
5851  20230423   081000    081459  ...         0.0        0.0       0
5852  20230423   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 08:20:05,168:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682209199, self.tradeDate='20230423', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27735.0, self.close=27749.0, self.high=27749.5, self.low=27710.8, self.vol=1624.098, self.amt=45044677.2201, ukdf['pct'].iloc[-1]=0.000508 , ukdf['amount'].iloc[-1]=45044677.2201, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-675172.92498783088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27749.27017063', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42262
self.closeSec=1682209499, self.tradeDate='20230423', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27748.9, self.close=27729.9, self.high=27749.1, self.low=27722.6, self.vol=823.199, self.amt=22831655.1368 
127.0.0.1 - - [23/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-23 08:25:01,563:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230423   080000    080459  ...         0.0        0.0       0
5850  20230423   080500    080959  ...         0.0        0.0       0
5851  20230423   081000    081459  ...         0.0        0.0       0
5852  20230423   081500    081959  ...         0.0        0.0       0
5853  20230423   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 08:25:01,567:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682209499, self.tradeDate='20230423', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27748.9, self.close=27729.9, self.high=27749.1, self.low=27722.6, self.vol=823.199, self.amt=22831655.1368, ukdf['pct'].iloc[-1]=-0.000688 , ukdf['amount'].iloc[-1]=22831655.1368, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-674013.3232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27730', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [23/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42823 

self.closeSec=1682207999, self.tradeDate='20230423', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27811.2, self.close=27807.2, self.high=27816.8, self.low=27793.6 
127.0.0.1 - - [23/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42824 

self.closeSec=1682208299, self.tradeDate='20230423', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27807.2, self.close=27792.4, self.high=27807.3, self.low=27777.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42825 

self.closeSec=1682208599, self.tradeDate='20230423', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27792.5, self.close=27768.4, self.high=27792.5, self.low=27766.8 
127.0.0.1 - - [23/Apr/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42826 

self.closeSec=1682208899, self.tradeDate='20230423', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27768.5, self.close=27734.9, self.high=27771.0, self.low=27731.8 
127.0.0.1 - - [23/Apr/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42827 

self.closeSec=1682209199, self.tradeDate='20230423', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27735.0, self.close=27749.0, self.high=27749.5, self.low=27710.8 
127.0.0.1 - - [23/Apr/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42828 

self.closeSec=1682209499, self.tradeDate='20230423', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27748.9, self.close=27729.9, self.high=27749.1, self.low=27722.6 
127.0.0.1 - - [23/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-23 08:00:18,921:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230423    052959  27621.4  ...  50.833333  0.467372  0.464730
5770  20230423    055959  27600.0  ...  50.833333  0.479181  0.446907
5771  20230423    062959  27658.8  ...  50.833333  0.492711  0.424404
5772  20230423    065959  27728.1  ...  50.833333  0.513188  0.400745
5773  20230423    072959  27837.8  ...  50.833333  0.504836  0.382736

[5 rows x 33 columns]
0.5351851851851852
acc is : 0.5351851851851852
2023-04-23 08:00:19,019:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.516715  0.483285       1  ...  0.887678   1.0    0.0  0.916033
536     0  0.535553  0.464447       1  ...  0.889898   1.0    0.0  0.918325
537     0  0.541520  0.458480       1  ...  0.893422   1.0    0.0  0.921962
538     0  0.555186  0.444814       0  ...  0.892007   1.0    0.0  0.920501
539     0  0.519361  0.480639       1  ...  0.892440   1.0    0.0  0.920948

[5 rows x 10 columns]
2023-04-23 08:00:19,031:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.516893  0.483107       1  ...  0.887678   1.0    0.0  0.916479
46     0  0.535722  0.464278       1  ...  0.889898   1.0    0.0  0.918438
47     0  0.541516  0.458484       1  ...  0.893422   1.0    0.0  0.924405
48     0  0.555464  0.444536       0  ...  0.892007   1.0    0.0  0.921991
49     0  0.519361  0.480639       1  ...  0.892440   1.0    0.0  0.920948

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21409 

self.closeSec=1682206199, self.tradeDate='20230423', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27798', self.close='27793.7'
127.0.0.1 - - [23/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21410 

self.closeSec=1682206799, self.tradeDate='20230423', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27793.6', self.close='27818.5'
127.0.0.1 - - [23/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21411 

self.closeSec=1682207399, self.tradeDate='20230423', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27818.6', self.close='27803.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21412 

self.closeSec=1682207999, self.tradeDate='20230423', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27803.7', self.close='27807.2'
127.0.0.1 - - [23/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21413 

self.closeSec=1682208599, self.tradeDate='20230423', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27807.2', self.close='27768.4'
127.0.0.1 - - [23/Apr/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21414 

self.closeSec=1682209199, self.tradeDate='20230423', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27768.5', self.close='27749'
127.0.0.1 - - [23/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [23/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21410 

self.closeSec=1682206199, self.tradeDate='20230423', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27798', self.close='27793.7'
127.0.0.1 - - [23/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21411 

self.closeSec=1682206799, self.tradeDate='20230423', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27793.6', self.close='27818.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21412 

self.closeSec=1682207399, self.tradeDate='20230423', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27818.6', self.close='27803.7'
127.0.0.1 - - [23/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21413 

self.closeSec=1682207999, self.tradeDate='20230423', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27803.7', self.close='27807.2'
127.0.0.1 - - [23/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21414 

self.closeSec=1682208599, self.tradeDate='20230423', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27807.2', self.close='27768.4'
127.0.0.1 - - [23/Apr/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21415 

self.closeSec=1682209199, self.tradeDate='20230423', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27768.5', self.close='27749'
127.0.0.1 - - [23/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21410 

self.closeSec=1682206199, self.tradeDate='20230423', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27798', self.close='27793.7'
127.0.0.1 - - [23/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21411 

self.closeSec=1682206799, self.tradeDate='20230423', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27793.6', self.close='27818.5'
127.0.0.1 - - [23/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [23/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21412 

self.closeSec=1682207399, self.tradeDate='20230423', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27818.6', self.close='27803.7'
127.0.0.1 - - [23/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21413 

self.closeSec=1682207999, self.tradeDate='20230423', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27803.7', self.close='27807.2'
127.0.0.1 - - [23/Apr/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21414 

self.closeSec=1682208599, self.tradeDate='20230423', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27807.2', self.close='27768.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21415 

self.closeSec=1682209199, self.tradeDate='20230423', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27768.5', self.close='27749'
127.0.0.1 - - [23/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38259
self.closeSec=1682209199, self.tradeDate='20230423', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27735.0, self.close=27749.0, self.high=27749.5, self.low=27710.8, self.vol=1624.098, self.amt=45044677.2201 
127.0.0.1 - - [23/Apr/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-04-23 08:20:03,369:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230423   075500    075959  ...         0.0        0.0       0
5849  20230423   080000    080459  ...         0.0        0.0       0
5850  20230423   080500    080959  ...         0.0        0.0       0
5851  20230423   081000    081459  ...         0.0        0.0       0
5852  20230423   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 08:20:03,370:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682209199, self.tradeDate='20230423', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27735.0, self.close=27749.0, self.high=27749.5, self.low=27710.8, self.vol=1624.098, self.amt=45044677.2201, ukdf['pct'].iloc[-1]=0.000508 , ukdf['amount'].iloc[-1]=45044677.2201, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [23/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38260
self.closeSec=1682209499, self.tradeDate='20230423', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27748.9, self.close=27729.9, self.high=27749.1, self.low=27722.6, self.vol=823.199, self.amt=22831655.1368 
2023-04-23 08:25:01,573:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230423   080000    080459  ...         0.0        0.0       0
5850  20230423   080500    080959  ...         0.0        0.0       0
5851  20230423   081000    081459  ...         0.0        0.0       0
5852  20230423   081500    081959  ...         0.0        0.0       0
5853  20230423   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-23 08:25:01,574:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682209499, self.tradeDate='20230423', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27748.9, self.close=27729.9, self.high=27749.1, self.low=27722.6, self.vol=823.199, self.amt=22831655.1368, ukdf['pct'].iloc[-1]=-0.000688 , ukdf['amount'].iloc[-1]=22831655.1368, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230422   200000    235959  1682179199  ...    719  0.957747  0.797817     1.0
720  20230423   000000    035959  1682193599  ...    720  0.969293  0.807105     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-34733.421', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27608.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [23/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=892
self.closeSec=1682207999, self.tradeDate='20230423', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27604.6, self.close=27807.2, self.high=27888.0, self.low=27554.6, self.vol=52141.27, self.amt=1446621140.09252 
2023-04-23 08:00:01,928:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682207999, self.tradeDate='20230423', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27604.6, self.close=27807.2, self.high=27888.0, self.low=27554.6, self.vol=52141.27, self.amt=1446621140.09252 
2023-04-23 08:00:01,957:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230422   120000    155959  ...  36075.068  9.851259e+08 -0.001520
718  20230422   160000    195959  ...  42889.652  1.168175e+09  0.000282
719  20230422   200000    235959  ...  82203.755  2.251310e+09  0.007369
720  20230423   000000    035959  ...  86509.805  2.389329e+09  0.004644
721  20230423   040000    075959  ...  52141.270  1.446621e+09  0.007336

[5 rows x 11 columns]
2023-04-23 08:00:03,695:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230422   120000    155959  1682150399  ...    717  0.928324  0.765001     1.0
718  20230422   160000    195959  1682164799  ...    718  0.969895  0.846018     1.0
719  20230422   200000    235959  1682179199  ...    719  0.957747  0.797817     1.0
720  20230423   000000    035959  1682193599  ...    720  0.969293  0.807105     1.0
721  20230423   040000    075959  1682207999  ...    721  0.988576  0.835122     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-24298.6905', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27807.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


