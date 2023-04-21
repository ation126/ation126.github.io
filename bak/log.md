# 20230421 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41685
self.closeSec=1682036399, self.tradeDate='20230421', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28279.5, self.close=28290.1, self.high=28319.7, self.low=28266.7, self.vol=1281.972, self.amt=36275425.1871 
127.0.0.1 - - [21/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-21 08:20:05,837:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230421   075500    075959  ...         0.0        0.0       0
5849  20230421   080000    080459  ...         0.0        0.0       0
5850  20230421   080500    080959  ...         0.0        0.0       0
5851  20230421   081000    081459  ...         0.0        0.0       0
5852  20230421   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 08:20:05,842:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682036399, self.tradeDate='20230421', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28279.5, self.close=28290.1, self.high=28319.7, self.low=28266.7, self.vol=1281.972, self.amt=36275425.1871, ukdf['pct'].iloc[-1]=0.000375 , ukdf['amount'].iloc[-1]=36275425.1871, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-707770.83940961312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28290.97972962', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41686
self.closeSec=1682036699, self.tradeDate='20230421', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28290.1, self.close=28197.9, self.high=28290.1, self.low=28177.0, self.vol=2036.203, self.amt=57477308.428 
2023-04-21 08:25:01,547:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230421   080000    080459  ...         0.0        0.0       0
5850  20230421   080500    080959  ...         0.0        0.0       0
5851  20230421   081000    081459  ...         0.0        0.0       0
5852  20230421   081500    081959  ...         0.0        0.0       0
5853  20230421   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 08:25:01,547:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682036699, self.tradeDate='20230421', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28290.1, self.close=28197.9, self.high=28290.1, self.low=28177.0, self.vol=2036.203, self.amt=57477308.428, ukdf['pct'].iloc[-1]=-0.003259 , ukdf['amount'].iloc[-1]=57477308.428, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-702855.68', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28209.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42247 

self.closeSec=1682035199, self.tradeDate='20230421', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28248.5, self.close=28229.9, self.high=28248.5, self.low=28210.0 
127.0.0.1 - - [21/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42248 

self.closeSec=1682035499, self.tradeDate='20230421', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28229.9, self.close=28275.0, self.high=28277.5, self.low=28198.1 
127.0.0.1 - - [21/Apr/2023 08:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42249 

self.closeSec=1682035799, self.tradeDate='20230421', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28275.0, self.close=28275.8, self.high=28303.5, self.low=28251.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42250 

self.closeSec=1682036099, self.tradeDate='20230421', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28275.7, self.close=28279.5, self.high=28297.0, self.low=28258.5 
127.0.0.1 - - [21/Apr/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42251 

self.closeSec=1682036399, self.tradeDate='20230421', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28279.5, self.close=28290.1, self.high=28319.7, self.low=28266.7 
127.0.0.1 - - [21/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42252 

self.closeSec=1682036699, self.tradeDate='20230421', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28290.1, self.close=28197.9, self.high=28290.1, self.low=28177.0 
127.0.0.1 - - [21/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-21 08:00:21,932:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230421    052959  28192.5  ...  50.416667  0.377386  0.739163
5770  20230421    055959  28188.1  ...  50.833333  0.383054  0.742074
5771  20230421    062959  28220.7  ...  50.833333  0.391396  0.741881
5772  20230421    065959  28268.7  ...  50.416667  0.388069  0.743509
5773  20230421    072959  28239.0  ...  50.416667  0.385435  0.746453

[5 rows x 33 columns]
0.5037037037037037
acc is : 0.5037037037037037
2023-04-21 08:00:22,059:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
535     0  0.522464  0.477536       1  ...  0.955308  -1.0  0.0000  1.012493
536     0  0.551279  0.448721       1  ...  0.955397   1.0 -0.0016  1.014208
537     0  0.557015  0.442985       0  ...  0.954393   1.0  0.0000  1.013142
538     0  0.530557  0.469443       0  ...  0.953603   1.0  0.0000  1.012302
539     0  0.530608  0.469392       1  ...  0.954089   1.0  0.0000  1.012819

[5 rows x 10 columns]
2023-04-21 08:00:22,085:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.522837  0.477163       1  ...  0.961052  -1.0  0.0000  1.012503
46     0  0.551257  0.448743       1  ...  0.955397   1.0 -0.0016  1.014171
47     0  0.556243  0.443757       0  ...  0.987403   1.0  0.0000  1.012347
48     0  0.530174  0.469826       0  ...  0.986585   1.0  0.0000  1.011860
49     0  0.530608  0.469392       1  ...  0.954089   1.0  0.0000  1.012819

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21121 

self.closeSec=1682033399, self.tradeDate='20230421', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28263.3', self.close='28215.5'
127.0.0.1 - - [21/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21122 

self.closeSec=1682033999, self.tradeDate='20230421', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28215.6', self.close='28243'
127.0.0.1 - - [21/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21123 

self.closeSec=1682034599, self.tradeDate='20230421', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28243', self.close='28235'
127.0.0.1 - - [21/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21124 

self.closeSec=1682035199, self.tradeDate='20230421', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28235', self.close='28229.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21125 

self.closeSec=1682035799, self.tradeDate='20230421', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28229.9', self.close='28275.8'
127.0.0.1 - - [21/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21126 

self.closeSec=1682036399, self.tradeDate='20230421', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28275.7', self.close='28290.1'
127.0.0.1 - - [21/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21122 

self.closeSec=1682033399, self.tradeDate='20230421', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28263.3', self.close='28215.5'
127.0.0.1 - - [21/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21123 

self.closeSec=1682033999, self.tradeDate='20230421', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28215.6', self.close='28243'
127.0.0.1 - - [21/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21124 

self.closeSec=1682034599, self.tradeDate='20230421', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28243', self.close='28235'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21125 

self.closeSec=1682035199, self.tradeDate='20230421', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28235', self.close='28229.9'
127.0.0.1 - - [21/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21126 

self.closeSec=1682035799, self.tradeDate='20230421', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28229.9', self.close='28275.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21127 

self.closeSec=1682036399, self.tradeDate='20230421', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28275.7', self.close='28290.1'
127.0.0.1 - - [21/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [21/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21122 

self.closeSec=1682033399, self.tradeDate='20230421', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28263.3', self.close='28215.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21123 

self.closeSec=1682033999, self.tradeDate='20230421', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28215.6', self.close='28243'
127.0.0.1 - - [21/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21124 

self.closeSec=1682034599, self.tradeDate='20230421', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28243', self.close='28235'
127.0.0.1 - - [21/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21125 

self.closeSec=1682035199, self.tradeDate='20230421', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28235', self.close='28229.9'
127.0.0.1 - - [21/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21126 

self.closeSec=1682035799, self.tradeDate='20230421', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28229.9', self.close='28275.8'
127.0.0.1 - - [21/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21127 

self.closeSec=1682036399, self.tradeDate='20230421', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28275.7', self.close='28290.1'
127.0.0.1 - - [21/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37683
self.closeSec=1682036399, self.tradeDate='20230421', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28279.5, self.close=28290.1, self.high=28319.7, self.low=28266.7, self.vol=1281.972, self.amt=36275425.1871 
127.0.0.1 - - [21/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-21 08:20:05,281:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230421   075500    075959  ...         0.0        0.0       0
5849  20230421   080000    080459  ...         0.0        0.0       0
5850  20230421   080500    080959  ...         0.0        0.0       0
5851  20230421   081000    081459  ...         0.0        0.0       0
5852  20230421   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 08:20:05,284:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682036399, self.tradeDate='20230421', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28279.5, self.close=28290.1, self.high=28319.7, self.low=28266.7, self.vol=1281.972, self.amt=36275425.1871, ukdf['pct'].iloc[-1]=0.000375 , ukdf['amount'].iloc[-1]=36275425.1871, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37684
self.closeSec=1682036699, self.tradeDate='20230421', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28290.1, self.close=28197.9, self.high=28290.1, self.low=28177.0, self.vol=2036.203, self.amt=57477308.428 
127.0.0.1 - - [21/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-21 08:25:01,544:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230421   080000    080459  ...         0.0        0.0       0
5850  20230421   080500    080959  ...         0.0        0.0       0
5851  20230421   081000    081459  ...         0.0        0.0       0
5852  20230421   081500    081959  ...         0.0        0.0       0
5853  20230421   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-21 08:25:01,545:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682036699, self.tradeDate='20230421', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28290.1, self.close=28197.9, self.high=28290.1, self.low=28177.0, self.vol=2036.203, self.amt=57477308.428, ukdf['pct'].iloc[-1]=-0.003259 , ukdf['amount'].iloc[-1]=57477308.428, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230420   200000    235959  1682006399  ...    719  0.579524  0.090516     NaN
720  20230421   000000    035959  1682020799  ...    720  0.604005  0.135192     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-10304.7039849285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28073.6759881', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [21/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=880
self.closeSec=1682035199, self.tradeDate='20230421', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28091.2, self.close=28229.9, self.high=28358.4, self.low=27995.1, self.vol=69632.679, self.amt=1964322964.79556 
2023-04-21 08:00:01,792:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682035199, self.tradeDate='20230421', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28091.2, self.close=28229.9, self.high=28358.4, self.low=27995.1, self.vol=69632.679, self.amt=1964322964.79556 
2023-04-21 08:00:01,851:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230420   120000    155959  ...   58959.523  1.704867e+09  0.000263
718  20230420   160000    195959  ...   68189.911  1.961852e+09 -0.008875
719  20230420   200000    235959  ...  164293.111  4.712963e+09 -0.003821
720  20230421   000000    035959  ...  186192.325  5.276888e+09 -0.014060
721  20230421   040000    075959  ...   69632.679  1.964323e+09  0.004920

[5 rows x 11 columns]
2023-04-21 08:00:04,095:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230420   120000    155959  1681977599  ...    717  0.494668 -0.082384     NaN
718  20230420   160000    195959  1681991999  ...    718  0.552418  0.039686     NaN
719  20230420   200000    235959  1682006399  ...    719  0.579524  0.090516     NaN
720  20230421   000000    035959  1682020799  ...    720  0.604005  0.135192     NaN
721  20230421   040000    075959  1682035199  ...    721  0.659259  0.250416     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-2095.3485', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28230', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


