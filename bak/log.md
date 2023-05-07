# 20230507 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46293
self.closeSec=1683418799, self.tradeDate='20230507', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28825.7, self.close=28807.0, self.high=28825.7, self.low=28806.5, self.vol=314.801, self.amt=9071595.3519 
127.0.0.1 - - [07/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-07 08:20:06,567:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230507   075500    075959  ...         0.0        0.0       0
5856  20230507   080000    080459  ...         0.0        0.0       0
5857  20230507   080500    080959  ...         0.0        0.0       0
5858  20230507   081000    081459  ...         0.0        0.0       0
5859  20230507   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 08:20:06,578:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683418799, self.tradeDate='20230507', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28825.7, self.close=28807.0, self.high=28825.7, self.low=28806.5, self.vol=314.801, self.amt=9071595.3519, ukdf['pct'].iloc[-1]=-0.000649 , ukdf['amount'].iloc[-1]=9071595.3519, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-738949.2448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28809.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46294
self.closeSec=1683419099, self.tradeDate='20230507', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28807.0, self.close=28808.5, self.high=28863.6, self.low=28801.1, self.vol=1671.847, self.amt=48194821.3814 
127.0.0.1 - - [07/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-05-07 08:25:01,643:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230507   080000    080459  ...         0.0        0.0       0
5857  20230507   080500    080959  ...         0.0        0.0       0
5858  20230507   081000    081459  ...         0.0        0.0       0
5859  20230507   081500    081959  ...         0.0        0.0       0
5860  20230507   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 08:25:01,643:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683419099, self.tradeDate='20230507', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28807.0, self.close=28808.5, self.high=28863.6, self.low=28801.1, self.vol=1671.847, self.amt=48194821.3814, ukdf['pct'].iloc[-1]=5.2e-05 , ukdf['amount'].iloc[-1]=48194821.3814, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-738962.76958647408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28809.32475383', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46855 

self.closeSec=1683417599, self.tradeDate='20230507', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28848.4, self.close=28837.8, self.high=28861.4, self.low=28832.0 
127.0.0.1 - - [07/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46856 

self.closeSec=1683417899, self.tradeDate='20230507', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28837.9, self.close=28852.1, self.high=28857.3, self.low=28832.6 
127.0.0.1 - - [07/May/2023 08:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46857 

self.closeSec=1683418199, self.tradeDate='20230507', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28852.0, self.close=28821.8, self.high=28855.7, self.low=28821.8 
127.0.0.1 - - [07/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46858 

self.closeSec=1683418499, self.tradeDate='20230507', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28821.8, self.close=28825.7, self.high=28836.0, self.low=28807.9 
127.0.0.1 - - [07/May/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46859 

self.closeSec=1683418799, self.tradeDate='20230507', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28825.7, self.close=28807.0, self.high=28825.7, self.low=28806.5 
127.0.0.1 - - [07/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/May/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46860 

self.closeSec=1683419099, self.tradeDate='20230507', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28807.0, self.close=28808.5, self.high=28863.6, self.low=28801.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-07 08:00:21,474:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230507    052959  28783.6  ...  49.583333  0.440627  0.673138
5770  20230507    055959  28754.2  ...  49.583333  0.449437  0.669252
5771  20230507    062959  28797.3  ...  50.000000  0.454924  0.663025
5772  20230507    065959  28824.2  ...  49.583333  0.453643  0.656947
5773  20230507    072959  28816.9  ...  49.583333  0.455521  0.649869

[5 rows x 33 columns]
0.5388888888888889
acc is : 0.5388888888888889
2023-05-07 08:00:21,573:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.482019  0.517981       1  ...  1.008915  -1.0    0.0  1.042950
536     0  0.503823  0.496177       1  ...  1.007969  -1.0    0.0  1.043928
537     0  0.506747  0.493253       0  ...  1.008231  -1.0    0.0  1.043656
538     0  0.503633  0.496367       1  ...  1.007916  -1.0    0.0  1.043982
539     0  0.508148  0.491852       1  ...  1.007497  -1.0    0.0  1.044416

[5 rows x 10 columns]
2023-05-07 08:00:21,598:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.482612  0.517388       1  ...  1.008915  -1.0    0.0  1.053708
46     0  0.504157  0.495843       1  ...  1.007969  -1.0    0.0  1.052958
47     0  0.506841  0.493159       0  ...  1.008231  -1.0    0.0  1.052250
48     0  0.503973  0.496027       1  ...  1.007916  -1.0    0.0  1.053929
49     0  0.508148  0.491852       1  ...  1.007497  -1.0    0.0  1.044416

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [07/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23425 

self.closeSec=1683415799, self.tradeDate='20230507', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28852.8', self.close='28825.8'
127.0.0.1 - - [07/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23426 

self.closeSec=1683416399, self.tradeDate='20230507', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28825.8', self.close='28806'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23427 

self.closeSec=1683416999, self.tradeDate='20230507', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28805.9', self.close='28807.8'
127.0.0.1 - - [07/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23428 

self.closeSec=1683417599, self.tradeDate='20230507', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28807.8', self.close='28837.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23429 

self.closeSec=1683418199, self.tradeDate='20230507', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28837.9', self.close='28821.8'
127.0.0.1 - - [07/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23430 

self.closeSec=1683418799, self.tradeDate='20230507', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28821.8', self.close='28807'
127.0.0.1 - - [07/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23426 

self.closeSec=1683415799, self.tradeDate='20230507', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28852.8', self.close='28825.8'
127.0.0.1 - - [07/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23427 

self.closeSec=1683416399, self.tradeDate='20230507', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28825.8', self.close='28806'
127.0.0.1 - - [07/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23428 

self.closeSec=1683416999, self.tradeDate='20230507', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28805.9', self.close='28807.8'
127.0.0.1 - - [07/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23429 

self.closeSec=1683417599, self.tradeDate='20230507', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28807.8', self.close='28837.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23430 

self.closeSec=1683418199, self.tradeDate='20230507', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28837.9', self.close='28821.8'
127.0.0.1 - - [07/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23431 

self.closeSec=1683418799, self.tradeDate='20230507', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28821.8', self.close='28807'
127.0.0.1 - - [07/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23426 

self.closeSec=1683415799, self.tradeDate='20230507', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28852.8', self.close='28825.8'
127.0.0.1 - - [07/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23427 

self.closeSec=1683416399, self.tradeDate='20230507', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28825.8', self.close='28806'
127.0.0.1 - - [07/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23428 

self.closeSec=1683416999, self.tradeDate='20230507', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28805.9', self.close='28807.8'
127.0.0.1 - - [07/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23429 

self.closeSec=1683417599, self.tradeDate='20230507', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28807.8', self.close='28837.8'
127.0.0.1 - - [07/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23430 

self.closeSec=1683418199, self.tradeDate='20230507', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28837.9', self.close='28821.8'
127.0.0.1 - - [07/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23431 

self.closeSec=1683418799, self.tradeDate='20230507', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28821.8', self.close='28807'
127.0.0.1 - - [07/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42291
self.closeSec=1683418799, self.tradeDate='20230507', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28825.7, self.close=28807.0, self.high=28825.7, self.low=28806.5, self.vol=314.801, self.amt=9071595.3519 
127.0.0.1 - - [07/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-07 08:20:06,419:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230507   075500    075959  ...         0.0        0.0       0
5856  20230507   080000    080459  ...         0.0        0.0       0
5857  20230507   080500    080959  ...         0.0        0.0       0
5858  20230507   081000    081459  ...         0.0        0.0       0
5859  20230507   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 08:20:06,430:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683418799, self.tradeDate='20230507', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28825.7, self.close=28807.0, self.high=28825.7, self.low=28806.5, self.vol=314.801, self.amt=9071595.3519, ukdf['pct'].iloc[-1]=-0.000649 , ukdf['amount'].iloc[-1]=9071595.3519, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42292
self.closeSec=1683419099, self.tradeDate='20230507', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28807.0, self.close=28808.5, self.high=28863.6, self.low=28801.1, self.vol=1671.847, self.amt=48194821.3814 
127.0.0.1 - - [07/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-05-07 08:25:01,641:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230507   080000    080459  ...         0.0        0.0       0
5857  20230507   080500    080959  ...         0.0        0.0       0
5858  20230507   081000    081459  ...         0.0        0.0       0
5859  20230507   081500    081959  ...         0.0        0.0       0
5860  20230507   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-07 08:25:01,642:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683419099, self.tradeDate='20230507', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28807.0, self.close=28808.5, self.high=28863.6, self.low=28801.1, self.vol=1671.847, self.amt=48194821.3814, ukdf['pct'].iloc[-1]=5.2e-05 , ukdf['amount'].iloc[-1]=48194821.3814, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230506   200000    235959  1683388799  ...    719  0.274583 -1.074422    -1.0
720  20230507   000000    035959  1683403199  ...    720  0.310965 -0.943053    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '23798.1492', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28831.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=976
self.closeSec=1683417599, self.tradeDate='20230507', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28831.9, self.close=28837.8, self.high=28869.9, self.low=28620.2, self.vol=38973.798, self.amt=1121835677.198 
127.0.0.1 - - [07/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
2023-05-07 08:00:03,189:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683417599, self.tradeDate='20230507', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28831.9, self.close=28837.8, self.high=28869.9, self.low=28620.2, self.vol=38973.798, self.amt=1121835677.198 
2023-05-07 08:00:03,221:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230506   120000    155959  ...   42728.114  1.253976e+09 -0.000337
718  20230506   160000    195959  ...   58055.462  1.698515e+09 -0.002920
719  20230506   200000    235959  ...  181672.364  5.225998e+09 -0.024145
720  20230507   000000    035959  ...   77210.531  2.222132e+09  0.009595
721  20230507   040000    075959  ...   38973.798  1.121836e+09  0.000205

[5 rows x 11 columns]
2023-05-07 08:00:04,643:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230506   120000    155959  1683359999  ...    717  0.511397 -0.376513     NaN
718  20230506   160000    195959  1683374399  ...    718  0.430030 -0.616101    -1.0
719  20230506   200000    235959  1683388799  ...    719  0.274583 -1.074422    -1.0
720  20230507   000000    035959  1683403199  ...    720  0.310965 -0.943053    -1.0
721  20230507   040000    075959  1683417599  ...    721  0.308148 -0.931649    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '23517.8412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28837.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


