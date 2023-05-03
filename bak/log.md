# 20230503 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45141
self.closeSec=1683073199, self.tradeDate='20230503', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28588.4, self.close=28594.8, self.high=28642.4, self.low=28586.0, self.vol=1712.802, self.amt=49011607.3005 
127.0.0.1 - - [03/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-03 08:20:06,442:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230503   075500    075959  ...         0.0        0.0       0
5856  20230503   080000    080459  ...         0.0        0.0       0
5857  20230503   080500    080959  ...         0.0        0.0       0
5858  20230503   081000    081459  ...         0.0        0.0       0
5859  20230503   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 08:20:06,461:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683073199, self.tradeDate='20230503', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28588.4, self.close=28594.8, self.high=28642.4, self.low=28586.0, self.vol=1712.802, self.amt=49011607.3005, ukdf['pct'].iloc[-1]=0.000224 , ukdf['amount'].iloc[-1]=49011607.3005, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-726059.5456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28594.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45142
self.closeSec=1683073499, self.tradeDate='20230503', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28594.9, self.close=28602.2, self.high=28607.4, self.low=28578.5, self.vol=715.975, self.amt=20472620.1504 
2023-05-03 08:25:01,533:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230503   080000    080459  ...         0.0        0.0       0
5857  20230503   080500    080959  ...         0.0        0.0       0
5858  20230503   081000    081459  ...         0.0        0.0       0
5859  20230503   081500    081959  ...         0.0        0.0       0
5860  20230503   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 08:25:01,534:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683073499, self.tradeDate='20230503', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28594.9, self.close=28602.2, self.high=28607.4, self.low=28578.5, self.vol=715.975, self.amt=20472620.1504, ukdf['pct'].iloc[-1]=0.000259 , ukdf['amount'].iloc[-1]=20472620.1504, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-726562.23871111504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28603.25371429', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45703 

self.closeSec=1683071999, self.tradeDate='20230503', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28627.9, self.close=28656.5, self.high=28668.0, self.low=28627.8 
127.0.0.1 - - [03/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45704 

self.closeSec=1683072299, self.tradeDate='20230503', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28656.4, self.close=28635.9, self.high=28673.5, self.low=28624.0 
127.0.0.1 - - [03/May/2023 08:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45705 

self.closeSec=1683072599, self.tradeDate='20230503', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28636.0, self.close=28653.9, self.high=28682.1, self.low=28634.1 
127.0.0.1 - - [03/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45706 

self.closeSec=1683072899, self.tradeDate='20230503', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28654.0, self.close=28588.4, self.high=28654.0, self.low=28540.6 
127.0.0.1 - - [03/May/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45707 

self.closeSec=1683073199, self.tradeDate='20230503', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28588.4, self.close=28594.8, self.high=28642.4, self.low=28586.0 
127.0.0.1 - - [03/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45708 

self.closeSec=1683073499, self.tradeDate='20230503', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28594.9, self.close=28602.2, self.high=28607.4, self.low=28578.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-03 08:00:21,474:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230503    052959  28661.6  ...  48.750000  0.529533  0.341444
5770  20230503    055959  28635.4  ...  49.166667  0.531604  0.334052
5771  20230503    062959  28649.6  ...  49.583333  0.546753  0.320292
5772  20230503    065959  28755.9  ...  49.583333  0.541879  0.309320
5773  20230503    072959  28727.0  ...  49.166667  0.531067  0.303263

[5 rows x 33 columns]
0.5388888888888889
acc is : 0.5388888888888889
2023-05-03 08:00:21,598:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.491203  0.508797       1  ...  0.932562   1.0    0.0  1.027110
536     1  0.494017  0.505983       1  ...  0.936025   1.0    0.0  1.030925
537     0  0.527378  0.472622       0  ...  0.935081   1.0    0.0  1.029885
538     0  0.500448  0.499552       0  ...  0.932968   1.0    0.0  1.027558
539     1  0.489496  0.510504       0  ...  0.932786   1.0    0.0  1.027358

[5 rows x 10 columns]
2023-05-03 08:00:21,623:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491854  0.508146       1  ...  0.932562   1.0    0.0  1.022003
46     1  0.494327  0.505673       1  ...  0.936025   1.0    0.0  1.028171
47     0  0.527209  0.472791       0  ...  0.935081   1.0    0.0  1.024683
48     0  0.500770  0.499230       0  ...  0.932968   1.0    0.0  1.027883
49     1  0.489496  0.510504       0  ...  0.932786   1.0    0.0  1.027358

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22849 

self.closeSec=1683070199, self.tradeDate='20230503', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28672.9', self.close='28662.1'
127.0.0.1 - - [03/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22850 

self.closeSec=1683070799, self.tradeDate='20230503', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28662.2', self.close='28635.3'
127.0.0.1 - - [03/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22851 

self.closeSec=1683071399, self.tradeDate='20230503', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28635.3', self.close='28636.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22852 

self.closeSec=1683071999, self.tradeDate='20230503', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28636.5', self.close='28656.5'
127.0.0.1 - - [03/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22853 

self.closeSec=1683072599, self.tradeDate='20230503', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28656.4', self.close='28653.9'
127.0.0.1 - - [03/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22854 

self.closeSec=1683073199, self.tradeDate='20230503', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28654', self.close='28594.8'
127.0.0.1 - - [03/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22850 

self.closeSec=1683070199, self.tradeDate='20230503', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28672.9', self.close='28662.1'
127.0.0.1 - - [03/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22851 

self.closeSec=1683070799, self.tradeDate='20230503', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28662.2', self.close='28635.3'
127.0.0.1 - - [03/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [03/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22852 

self.closeSec=1683071399, self.tradeDate='20230503', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28635.3', self.close='28636.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22853 

self.closeSec=1683071999, self.tradeDate='20230503', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28636.5', self.close='28656.5'
127.0.0.1 - - [03/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22854 

self.closeSec=1683072599, self.tradeDate='20230503', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28656.4', self.close='28653.9'
127.0.0.1 - - [03/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22855 

self.closeSec=1683073199, self.tradeDate='20230503', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28654', self.close='28594.8'
127.0.0.1 - - [03/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [03/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22850 

self.closeSec=1683070199, self.tradeDate='20230503', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28672.9', self.close='28662.1'
127.0.0.1 - - [03/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22851 

self.closeSec=1683070799, self.tradeDate='20230503', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28662.2', self.close='28635.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22852 

self.closeSec=1683071399, self.tradeDate='20230503', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28635.3', self.close='28636.5'
127.0.0.1 - - [03/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22853 

self.closeSec=1683071999, self.tradeDate='20230503', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28636.5', self.close='28656.5'
127.0.0.1 - - [03/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22854 

self.closeSec=1683072599, self.tradeDate='20230503', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28656.4', self.close='28653.9'
127.0.0.1 - - [03/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22855 

self.closeSec=1683073199, self.tradeDate='20230503', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28654', self.close='28594.8'
127.0.0.1 - - [03/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41139
self.closeSec=1683073199, self.tradeDate='20230503', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28588.4, self.close=28594.8, self.high=28642.4, self.low=28586.0, self.vol=1712.802, self.amt=49011607.3005 
127.0.0.1 - - [03/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-03 08:20:06,266:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230503   075500    075959  ...         0.0        0.0       0
5856  20230503   080000    080459  ...         0.0        0.0       0
5857  20230503   080500    080959  ...         0.0        0.0       0
5858  20230503   081000    081459  ...         0.0        0.0       0
5859  20230503   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 08:20:06,280:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683073199, self.tradeDate='20230503', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28588.4, self.close=28594.8, self.high=28642.4, self.low=28586.0, self.vol=1712.802, self.amt=49011607.3005, ukdf['pct'].iloc[-1]=0.000224 , ukdf['amount'].iloc[-1]=49011607.3005, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41140
self.closeSec=1683073499, self.tradeDate='20230503', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28594.9, self.close=28602.2, self.high=28607.4, self.low=28578.5, self.vol=715.975, self.amt=20472620.1504 
2023-05-03 08:25:01,588:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230503   080000    080459  ...         0.0        0.0       0
5857  20230503   080500    080959  ...         0.0        0.0       0
5858  20230503   081000    081459  ...         0.0        0.0       0
5859  20230503   081500    081959  ...         0.0        0.0       0
5860  20230503   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 08:25:01,588:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683073499, self.tradeDate='20230503', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28594.9, self.close=28602.2, self.high=28607.4, self.low=28578.5, self.vol=715.975, self.amt=20472620.1504, ukdf['pct'].iloc[-1]=0.000259 , ukdf['amount'].iloc[-1]=20472620.1504, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230502   200000    235959  1683043199  ...    719  0.567059 -0.178762     NaN
720  20230503   000000    035959  1683057599  ...    720  0.560254 -0.200610     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '30343.341', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28691.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [03/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=952
self.closeSec=1683071999, self.tradeDate='20230503', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28676.5, self.close=28656.5, self.high=28820.0, self.low=28600.6, self.vol=48455.705, self.amt=1390299577.5618 
2023-05-03 08:00:03,244:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683071999, self.tradeDate='20230503', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28676.5, self.close=28656.5, self.high=28820.0, self.low=28600.6, self.vol=48455.705, self.amt=1390299577.5618 
2023-05-03 08:00:03,314:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230502   120000    155959  ...   39868.257  1.116407e+09  0.000467
718  20230502   160000    195959  ...   39176.734  1.097673e+09  0.001109
719  20230502   200000    235959  ...  231567.459  6.564339e+09  0.016010
720  20230503   000000    035959  ...  110120.500  3.152380e+09  0.005181
721  20230503   040000    075959  ...   48455.705  1.390300e+09 -0.000589

[5 rows x 11 columns]
2023-05-03 08:00:04,936:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230502   120000    155959  1683014399  ...    717  0.582597 -0.113055     NaN
718  20230502   160000    195959  1683028799  ...    718  0.643078  0.057836     NaN
719  20230502   200000    235959  1683043199  ...    719  0.567059 -0.178762     NaN
720  20230503   000000    035959  1683057599  ...    720  0.560254 -0.200610     NaN
721  20230503   040000    075959  1683071999  ...    721  0.553597 -0.218806     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '31872.1936677221', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28659.07486905', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


