# 20230412 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38997
self.closeSec=1681229999, self.tradeDate='20230412', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30182.9, self.close=30146.1, self.high=30183.0, self.low=30080.1, self.vol=4797.629, self.amt=144573060.9292 
127.0.0.1 - - [12/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-12 00:20:07,045:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230411   235500    235959  ...         0.0        0.0       0
5753  20230412   000000    000459  ...         0.0        0.0       0
5754  20230412   000500    000959  ...         0.0        0.0       0
5755  20230412   001000    001459  ...         0.0        0.0       0
5756  20230412   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 00:20:07,064:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681229999, self.tradeDate='20230412', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30182.9, self.close=30146.1, self.high=30183.0, self.low=30080.1, self.vol=4797.629, self.amt=144573060.9292, ukdf['pct'].iloc[-1]=-0.001219 , ukdf['amount'].iloc[-1]=144573060.9292, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-819524.9088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30148.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38998
self.closeSec=1681230299, self.tradeDate='20230412', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30146.1, self.close=30163.8, self.high=30167.0, self.low=30138.4, self.vol=1329.932, self.amt=40101235.0138 
2023-04-12 00:25:01,620:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230412   000000    000459  ...         0.0        0.0       0
5754  20230412   000500    000959  ...         0.0        0.0       0
5755  20230412   001000    001459  ...         0.0        0.0       0
5756  20230412   001500    001959  ...         0.0        0.0       0
5757  20230412   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 00:25:01,620:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681230299, self.tradeDate='20230412', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30146.1, self.close=30163.8, self.high=30167.0, self.low=30138.4, self.vol=1329.932, self.amt=40101235.0138, ukdf['pct'].iloc[-1]=0.000587 , ukdf['amount'].iloc[-1]=40101235.0138, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-820469.672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30163.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
      tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1027  20230410   133500    133959  1681105199  ...  28220.3  0.000011   1603    1
1028  20230410   134000    134459  1681105499  ...  28232.1  0.001654   1604    2
1029  20230410   134500    134959  1681105799  ...  28265.5 -0.000453   1605    3
1030  20230410   135000    135459  1681106099  ...  28251.1  0.000340   1606    4
1031  20230410   135500    135959  1681106399  ...  28268.0 -0.000141   1607    5

[5 rows x 11 columns] 

127.0.0.1 - - [12/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39561 

self.closeSec=1681229399, self.tradeDate='20230412', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=30190.9, self.close=30227.7, self.high=30230.0, self.low=30184.7 
127.0.0.1 - - [12/Apr/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39562 

self.closeSec=1681229699, self.tradeDate='20230412', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=30227.8, self.close=30182.9, self.high=30258.8, self.low=30182.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39563 

self.closeSec=1681229999, self.tradeDate='20230412', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30182.9, self.close=30146.1, self.high=30183.0, self.low=30080.1 
127.0.0.1 - - [12/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39564 

self.closeSec=1681230299, self.tradeDate='20230412', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30146.1, self.close=30163.8, self.high=30167.0, self.low=30138.4 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-12 00:00:32,522:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230411    212959  30088.4  ...  51.666667  0.666461  0.195021
5802  20230411    215959  30155.5  ...  51.666667  0.674616  0.193861
5803  20230411    222959  30233.5  ...  51.666667  0.667455  0.194319
5804  20230411    225959  30199.9  ...  51.250000  0.636171  0.201739
5805  20230411    232959  30047.8  ...  51.250000  0.649283  0.203377

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-04-12 00:00:32,699:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.497453  0.502547       1  ...  1.011386  -1.0    0.0  1.087658
540     0  0.505695  0.494305       0  ...  1.012506  -1.0    0.0  1.086452
541     1  0.485957  0.514043       0  ...  1.017606  -1.0    0.0  1.080981
542     1  0.452880  0.547120       1  ...  1.013579  -1.0    0.0  1.085258
543     0  0.510094  0.489906       1  ...  1.013152  -1.0    0.0  1.085715

[5 rows x 10 columns]
2023-04-12 00:00:32,728:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497869  0.502131       1  ...  1.011386  -1.0    0.0  1.078786
46     0  0.505748  0.494252       0  ...  1.012506  -1.0    0.0  1.076396
47     1  0.485600  0.514400       0  ...  1.017606  -1.0    0.0  1.070570
48     1  0.452094  0.547906       1  ...  0.998763  -1.0    0.0  1.074806
49     0  0.510094  0.489906       1  ...  1.013152  -1.0    0.0  1.085715

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19777 

self.closeSec=1681226999, self.tradeDate='20230411', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30177', self.close='30166.7'
127.0.0.1 - - [11/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19778 

self.closeSec=1681227599, self.tradeDate='20230411', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30166.6', self.close='30155.9'
127.0.0.1 - - [11/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19779 

self.closeSec=1681228199, self.tradeDate='20230411', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30155.9', self.close='30190'
127.0.0.1 - - [12/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19780 

self.closeSec=1681228799, self.tradeDate='20230411', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30190', self.close='30179.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19781 

self.closeSec=1681229399, self.tradeDate='20230412', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30179.5', self.close='30227.7'
127.0.0.1 - - [12/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19782 

self.closeSec=1681229999, self.tradeDate='20230412', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30227.8', self.close='30146.1'
127.0.0.1 - - [12/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19778 

self.closeSec=1681226999, self.tradeDate='20230411', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30177', self.close='30166.7'
127.0.0.1 - - [11/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19779 

self.closeSec=1681227599, self.tradeDate='20230411', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30166.6', self.close='30155.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19780 

self.closeSec=1681228199, self.tradeDate='20230411', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30155.9', self.close='30190'
127.0.0.1 - - [11/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19781 

self.closeSec=1681228799, self.tradeDate='20230411', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30190', self.close='30179.4'
127.0.0.1 - - [12/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19782 

self.closeSec=1681229399, self.tradeDate='20230412', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30179.5', self.close='30227.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19783 

self.closeSec=1681229999, self.tradeDate='20230412', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30227.8', self.close='30146.1'
127.0.0.1 - - [12/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [11/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19778 

self.closeSec=1681226999, self.tradeDate='20230411', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30177', self.close='30166.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19779 

self.closeSec=1681227599, self.tradeDate='20230411', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30166.6', self.close='30155.9'
127.0.0.1 - - [11/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19780 

self.closeSec=1681228199, self.tradeDate='20230411', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30155.9', self.close='30190'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19781 

self.closeSec=1681228799, self.tradeDate='20230411', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30190', self.close='30179.4'
127.0.0.1 - - [12/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19782 

self.closeSec=1681229399, self.tradeDate='20230412', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30179.5', self.close='30227.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19783 

self.closeSec=1681229999, self.tradeDate='20230412', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30227.8', self.close='30146.1'
127.0.0.1 - - [12/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34995
self.closeSec=1681229999, self.tradeDate='20230412', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30182.9, self.close=30146.1, self.high=30183.0, self.low=30080.1, self.vol=4797.629, self.amt=144573060.9292 
127.0.0.1 - - [12/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-12 00:20:06,968:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230411   235500    235959  ...         0.0        0.0       0
5753  20230412   000000    000459  ...         0.0        0.0       0
5754  20230412   000500    000959  ...         0.0        0.0       0
5755  20230412   001000    001459  ...         0.0        0.0       0
5756  20230412   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 00:20:06,983:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681229999, self.tradeDate='20230412', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30182.9, self.close=30146.1, self.high=30183.0, self.low=30080.1, self.vol=4797.629, self.amt=144573060.9292, ukdf['pct'].iloc[-1]=-0.001219 , ukdf['amount'].iloc[-1]=144573060.9292, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [12/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34996
self.closeSec=1681230299, self.tradeDate='20230412', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30146.1, self.close=30163.8, self.high=30167.0, self.low=30138.4, self.vol=1329.932, self.amt=40101235.0138 
2023-04-12 00:25:01,550:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230412   000000    000459  ...         0.0        0.0       0
5754  20230412   000500    000959  ...         0.0        0.0       0
5755  20230412   001000    001459  ...         0.0        0.0       0
5756  20230412   001500    001959  ...         0.0        0.0       0
5757  20230412   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 00:25:01,550:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681230299, self.tradeDate='20230412', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30146.1, self.close=30163.8, self.high=30167.0, self.low=30138.4, self.vol=1329.932, self.amt=40101235.0138, ukdf['pct'].iloc[-1]=0.000587 , ukdf['amount'].iloc[-1]=40101235.0138, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230411   120000    155959  1681199999  ...    723  1.576662  3.292181     1.0
724  20230411   160000    195959  1681214399  ...    724  1.306424  2.446208     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '92956.8015', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30040', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=824
self.closeSec=1681228799, self.tradeDate='20230411', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30045.1, self.close=30179.4, self.high=30280.0, self.low=29938.9, self.vol=117522.262, self.amt=3540363683.48796 
127.0.0.1 - - [12/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-12 00:00:01,802:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681228799, self.tradeDate='20230411', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30045.1, self.close=30179.4, self.high=30280.0, self.low=29938.9, self.vol=117522.262, self.amt=3540363683.48796 
2023-04-12 00:00:01,844:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230411   040000    075959  ...  138521.033  4.086110e+09  0.015711
722  20230411   080000    115959  ...  202989.715  6.097405e+09  0.016295
723  20230411   120000    155959  ...   75212.768  2.258270e+09 -0.000349
724  20230411   160000    195959  ...   53203.501  1.599732e+09 -0.001671
725  20230411   200000    235959  ...  117522.262  3.540364e+09  0.004473

[5 rows x 11 columns]
2023-04-12 00:00:04,071:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230411   040000    075959  1681171199  ...    721  1.949541  5.398415     1.0
722  20230411   080000    115959  1681185599  ...    722  1.968087  4.680088     1.0
723  20230411   120000    155959  1681199999  ...    723  1.576662  3.292181     1.0
724  20230411   160000    195959  1681214399  ...    724  1.306424  2.446208     1.0
725  20230411   200000    235959  1681228799  ...    725  1.237339  2.179330     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '100233.8150530572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30178.57019048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


