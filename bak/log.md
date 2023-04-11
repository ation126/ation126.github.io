# 20230411 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38805
self.closeSec=1681172399, self.tradeDate='20230411', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29660.0, self.close=29643.2, self.high=29698.0, self.low=29639.2, self.vol=1796.503, self.amt=53302368.5754 
127.0.0.1 - - [11/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-11 08:20:07,607:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230411   075500    075959  ...         0.0        0.0       0
5849  20230411   080000    080459  ...         0.0        0.0       0
5850  20230411   080500    080959  ...         0.0        0.0       0
5851  20230411   081000    081459  ...         0.0        0.0       0
5852  20230411   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 08:20:07,611:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681172399, self.tradeDate='20230411', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29660.0, self.close=29643.2, self.high=29698.0, self.low=29639.2, self.vol=1796.503, self.amt=53302368.5754, ukdf['pct'].iloc[-1]=-0.000563 , ukdf['amount'].iloc[-1]=53302368.5754, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-789388.768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29647.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38806
self.closeSec=1681172699, self.tradeDate='20230411', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29643.1, self.close=29643.3, self.high=29657.4, self.low=29635.3, self.vol=873.932, self.amt=25909704.0887 
2023-04-11 08:25:01,606:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230411   080000    080459  ...         0.0        0.0       0
5850  20230411   080500    080959  ...         0.0        0.0       0
5851  20230411   081000    081459  ...         0.0        0.0       0
5852  20230411   081500    081959  ...         0.0        0.0       0
5853  20230411   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 08:25:01,610:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681172699, self.tradeDate='20230411', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29643.1, self.close=29643.3, self.high=29657.4, self.low=29635.3, self.vol=873.932, self.amt=25909704.0887, ukdf['pct'].iloc[-1]=3e-06 , ukdf['amount'].iloc[-1]=25909704.0887, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-789148.064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29643.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39367 

self.closeSec=1681171199, self.tradeDate='20230411', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29595.1, self.close=29623.1, self.high=29639.3, self.low=29595.0 
127.0.0.1 - - [11/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39368 

self.closeSec=1681171499, self.tradeDate='20230411', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29623.1, self.close=29611.5, self.high=29650.0, self.low=29611.5 
127.0.0.1 - - [11/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39369 

self.closeSec=1681171799, self.tradeDate='20230411', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29611.1, self.close=29575.8, self.high=29612.8, self.low=29573.9 
127.0.0.1 - - [11/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39370 

self.closeSec=1681172099, self.tradeDate='20230411', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29575.8, self.close=29659.9, self.high=29660.0, self.low=29575.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39371 

self.closeSec=1681172399, self.tradeDate='20230411', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29660.0, self.close=29643.2, self.high=29698.0, self.low=29639.2 
127.0.0.1 - - [11/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39372 

self.closeSec=1681172699, self.tradeDate='20230411', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29643.1, self.close=29643.3, self.high=29657.4, self.low=29635.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-11 08:00:35,113:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230411    052959  29107.8  ...  50.000000  0.678435  0.246083
5770  20230411    055959  29211.4  ...  50.000000  0.678629  0.234743
5771  20230411    062959  29212.8  ...  50.416667  0.717908  0.230490
5772  20230411    065959  29551.7  ...  50.833333  0.720827  0.225399
5773  20230411    072959  29580.0  ...  50.833333  0.729397  0.217278

[5 rows x 33 columns]
0.5425925925925926
acc is : 0.5425925925925926
2023-04-11 08:00:35,271:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.513024  0.486976       1  ...  0.962795   1.0    0.0  1.039916
536     0  0.504245  0.495755       1  ...  0.973961   1.0    0.0  1.051976
537     0  0.584900  0.415100       1  ...  0.974897   1.0    0.0  1.052987
538     0  0.530783  0.469217       1  ...  0.977705   1.0    0.0  1.056020
539     0  0.545390  0.454610       0  ...  0.976315   1.0    0.0  1.054518

[5 rows x 10 columns]
2023-04-11 08:00:35,308:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511552  0.488448       1  ...  0.962795   1.0    0.0  1.030743
46     0  0.503809  0.496191       1  ...  0.973961   1.0    0.0  1.044798
47     0  0.584714  0.415286       1  ...  0.974897   1.0    0.0  1.048341
48     0  0.530801  0.469199       1  ...  0.977705   1.0    0.0  1.050664
49     0  0.545390  0.454610       0  ...  0.976315   1.0    0.0  1.054518

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19681 

self.closeSec=1681169399, self.tradeDate='20230411', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29677.9', self.close='29665.3'
127.0.0.1 - - [11/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19682 

self.closeSec=1681169999, self.tradeDate='20230411', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29665.2', self.close='29682.9'
127.0.0.1 - - [11/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19683 

self.closeSec=1681170599, self.tradeDate='20230411', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29682.9', self.close='29650.5'
127.0.0.1 - - [11/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19684 

self.closeSec=1681171199, self.tradeDate='20230411', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29650.4', self.close='29623.1'
127.0.0.1 - - [11/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19685 

self.closeSec=1681171799, self.tradeDate='20230411', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29623.1', self.close='29575.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19686 

self.closeSec=1681172399, self.tradeDate='20230411', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29575.8', self.close='29643.2'
127.0.0.1 - - [11/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [11/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19682 

self.closeSec=1681169399, self.tradeDate='20230411', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29677.9', self.close='29665.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19683 

self.closeSec=1681169999, self.tradeDate='20230411', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29665.2', self.close='29682.9'
127.0.0.1 - - [11/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19684 

self.closeSec=1681170599, self.tradeDate='20230411', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29682.9', self.close='29650.5'
127.0.0.1 - - [11/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19685 

self.closeSec=1681171199, self.tradeDate='20230411', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29650.4', self.close='29623.1'
127.0.0.1 - - [11/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19686 

self.closeSec=1681171799, self.tradeDate='20230411', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29623.1', self.close='29575.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19687 

self.closeSec=1681172399, self.tradeDate='20230411', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29575.8', self.close='29643.2'
127.0.0.1 - - [11/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [11/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19682 

self.closeSec=1681169399, self.tradeDate='20230411', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29677.9', self.close='29665.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19683 

self.closeSec=1681169999, self.tradeDate='20230411', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29665.2', self.close='29682.9'
127.0.0.1 - - [11/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19684 

self.closeSec=1681170599, self.tradeDate='20230411', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29682.9', self.close='29650.5'
127.0.0.1 - - [11/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19685 

self.closeSec=1681171199, self.tradeDate='20230411', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29650.4', self.close='29623.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19686 

self.closeSec=1681171799, self.tradeDate='20230411', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29623.1', self.close='29575.7'
127.0.0.1 - - [11/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19687 

self.closeSec=1681172399, self.tradeDate='20230411', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29575.8', self.close='29643.2'
127.0.0.1 - - [11/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34803
self.closeSec=1681172399, self.tradeDate='20230411', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29660.0, self.close=29643.2, self.high=29698.0, self.low=29639.2, self.vol=1796.503, self.amt=53302368.5754 
127.0.0.1 - - [11/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-11 08:20:07,476:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230411   075500    075959  ...         0.0        0.0       0
5849  20230411   080000    080459  ...         0.0        0.0       0
5850  20230411   080500    080959  ...         0.0        0.0       0
5851  20230411   081000    081459  ...         0.0        0.0       0
5852  20230411   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 08:20:07,490:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681172399, self.tradeDate='20230411', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29660.0, self.close=29643.2, self.high=29698.0, self.low=29639.2, self.vol=1796.503, self.amt=53302368.5754, ukdf['pct'].iloc[-1]=-0.000563 , ukdf['amount'].iloc[-1]=53302368.5754, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34804
self.closeSec=1681172699, self.tradeDate='20230411', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29643.1, self.close=29643.3, self.high=29657.4, self.low=29635.3, self.vol=873.932, self.amt=25909704.0887 
127.0.0.1 - - [11/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-11 08:25:01,616:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230411   080000    080459  ...         0.0        0.0       0
5850  20230411   080500    080959  ...         0.0        0.0       0
5851  20230411   081000    081459  ...         0.0        0.0       0
5852  20230411   081500    081959  ...         0.0        0.0       0
5853  20230411   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 08:25:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681172699, self.tradeDate='20230411', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29643.1, self.close=29643.3, self.high=29657.4, self.low=29635.3, self.vol=873.932, self.amt=25909704.0887, ukdf['pct'].iloc[-1]=3e-06 , ukdf['amount'].iloc[-1]=25909704.0887, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230410   200000    235959  1681142399  ...    719  0.635240  1.725680     1.0
720  20230411   000000    035959  1681156799  ...    720  1.632748  5.391564     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '47855.3808126006', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29181.17070004', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [11/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=820
self.closeSec=1681171199, self.tradeDate='20230411', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29164.9, self.close=29623.1, self.high=29840.0, self.low=29058.0, self.vol=138521.033, self.amt=4086109628.46351 
2023-04-11 08:00:02,015:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681171199, self.tradeDate='20230411', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29164.9, self.close=29623.1, self.high=29840.0, self.low=29058.0, self.vol=138521.033, self.amt=4086109628.46351 
2023-04-11 08:00:02,091:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230410   120000    155959  ...   32457.910  9.169262e+08  0.000297
718  20230410   160000    195959  ...   33714.023  9.544942e+08  0.000569
719  20230410   200000    235959  ...   91955.851  2.606687e+09  0.004715
720  20230411   000000    035959  ...  244253.752  7.086679e+09  0.025932
721  20230411   040000    075959  ...  138521.033  4.086110e+09  0.015711

[5 rows x 11 columns]
2023-04-11 08:00:04,601:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230410   120000    155959  1681113599  ...    717  0.421837  0.737938     1.0
718  20230410   160000    195959  1681127999  ...    718  0.428663  0.753419     1.0
719  20230410   200000    235959  1681142399  ...    719  0.635240  1.725680     1.0
720  20230411   000000    035959  1681156799  ...    720  1.632748  5.391564     1.0
721  20230411   040000    075959  1681171199  ...    721  1.949541  5.398415     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '71281.46281482495', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29627.25433333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


