# 20230419 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41013
self.closeSec=1681834799, self.tradeDate='20230419', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30241.0, self.close=30227.6, self.high=30247.0, self.low=30209.0, self.vol=1399.402, self.amt=42301357.5315 
127.0.0.1 - - [19/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-19 00:20:07,324:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230418   235500    235959  ...         0.0        0.0       0
5753  20230419   000000    000459  ...         0.0        0.0       0
5754  20230419   000500    000959  ...         0.0        0.0       0
5755  20230419   001000    001459  ...         0.0        0.0       0
5756  20230419   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 00:20:07,333:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681834799, self.tradeDate='20230419', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30241.0, self.close=30227.6, self.high=30247.0, self.low=30209.0, self.vol=1399.402, self.amt=42301357.5315, ukdf['pct'].iloc[-1]=-0.00044 , ukdf['amount'].iloc[-1]=42301357.5315, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-824308.9008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30227.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41014
self.closeSec=1681835099, self.tradeDate='20230419', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30227.6, self.close=30218.0, self.high=30240.0, self.low=30216.7, self.vol=908.194, self.amt=27452778.0404 
127.0.0.1 - - [19/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-19 00:25:01,576:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230419   000000    000459  ...         0.0        0.0       0
5754  20230419   000500    000959  ...         0.0        0.0       0
5755  20230419   001000    001459  ...         0.0        0.0       0
5756  20230419   001500    001959  ...         0.0        0.0       0
5757  20230419   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 00:25:01,576:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681835099, self.tradeDate='20230419', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30227.6, self.close=30218.0, self.high=30240.0, self.low=30216.7, self.vol=908.194, self.amt=27452778.0404, ukdf['pct'].iloc[-1]=-0.000318 , ukdf['amount'].iloc[-1]=27452778.0404, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-823855.93624648544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30220.07267094', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [19/Apr/2023 00:05:01] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230414' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [19/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41577 

self.closeSec=1681834199, self.tradeDate='20230419', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=30200.0, self.close=30240.1, self.high=30244.6, self.low=30199.9 
127.0.0.1 - - [19/Apr/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41578 

self.closeSec=1681834499, self.tradeDate='20230419', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=30240.1, self.close=30240.9, self.high=30244.0, self.low=30214.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41579 

self.closeSec=1681834799, self.tradeDate='20230419', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30241.0, self.close=30227.6, self.high=30247.0, self.low=30209.0 
127.0.0.1 - - [19/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41580 

self.closeSec=1681835099, self.tradeDate='20230419', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30227.6, self.close=30218.0, self.high=30240.0, self.low=30216.7 
127.0.0.1 - - [19/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-19 00:00:35,323:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230418    212959  30290.9  ...  54.583333  0.600804  0.297113
5802  20230418    215959  30327.4  ...  55.000000  0.606399  0.282898
5803  20230418    222959  30362.3  ...  54.583333  0.563242  0.278547
5804  20230418    225959  30174.9  ...  54.583333  0.572417  0.271851
5805  20230418    232959  30230.4  ...  54.583333  0.559832  0.268365

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-04-19 00:00:35,490:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.551115  0.448885       1  ...  1.050280   1.0    0.0  1.087704
540     0  0.545963  0.454037       0  ...  1.043794   1.0    0.0  1.080987
541     1  0.462474  0.537526       1  ...  1.045710   1.0    0.0  1.082972
542     0  0.513530  0.486470       0  ...  1.043700   1.0    0.0  1.080891
543     1  0.492885  0.507115       0  ...  1.043631   1.0    0.0  1.080819

[5 rows x 10 columns]
2023-04-19 00:00:35,539:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.550166  0.449834       1  ...  1.050280   1.0    0.0  1.085783
46     0  0.545439  0.454561       0  ...  1.043794   1.0    0.0  1.080155
47     1  0.462044  0.537956       1  ...  1.045710   1.0    0.0  1.081581
48     0  0.512560  0.487440       0  ...  1.043700   1.0    0.0  1.079502
49     1  0.492885  0.507115       0  ...  1.043631   1.0    0.0  1.080819

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20785 

self.closeSec=1681831799, self.tradeDate='20230418', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30149.9', self.close='30172.2'
127.0.0.1 - - [18/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20786 

self.closeSec=1681832399, self.tradeDate='20230418', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30172.1', self.close='30114'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20787 

self.closeSec=1681832999, self.tradeDate='20230418', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30113.9', self.close='30139.3'
127.0.0.1 - - [18/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20788 

self.closeSec=1681833599, self.tradeDate='20230418', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30139.2', self.close='30170.2'
127.0.0.1 - - [19/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20789 

self.closeSec=1681834199, self.tradeDate='20230419', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30170.1', self.close='30240.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20790 

self.closeSec=1681834799, self.tradeDate='20230419', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30240.1', self.close='30227.6'
127.0.0.1 - - [19/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [18/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20786 

self.closeSec=1681831799, self.tradeDate='20230418', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30149.9', self.close='30172.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20787 

self.closeSec=1681832399, self.tradeDate='20230418', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30172.1', self.close='30114'
127.0.0.1 - - [18/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20788 

self.closeSec=1681832999, self.tradeDate='20230418', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30113.9', self.close='30139.3'
127.0.0.1 - - [18/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20789 

self.closeSec=1681833599, self.tradeDate='20230418', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30139.2', self.close='30170.2'
127.0.0.1 - - [19/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20790 

self.closeSec=1681834199, self.tradeDate='20230419', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30170.1', self.close='30240.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20791 

self.closeSec=1681834799, self.tradeDate='20230419', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30240.1', self.close='30227.6'
127.0.0.1 - - [19/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20786 

self.closeSec=1681831799, self.tradeDate='20230418', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30149.9', self.close='30172.2'
127.0.0.1 - - [18/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20787 

self.closeSec=1681832399, self.tradeDate='20230418', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30172.1', self.close='30114'
127.0.0.1 - - [18/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20788 

self.closeSec=1681832999, self.tradeDate='20230418', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30113.9', self.close='30139.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20789 

self.closeSec=1681833599, self.tradeDate='20230418', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30139.2', self.close='30170.2'
127.0.0.1 - - [19/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20790 

self.closeSec=1681834199, self.tradeDate='20230419', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30170.1', self.close='30240.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20791 

self.closeSec=1681834799, self.tradeDate='20230419', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30240.1', self.close='30227.6'
127.0.0.1 - - [19/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37011
self.closeSec=1681834799, self.tradeDate='20230419', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30241.0, self.close=30227.6, self.high=30247.0, self.low=30209.0, self.vol=1399.402, self.amt=42301357.5315 
127.0.0.1 - - [19/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-19 00:20:07,176:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230418   235500    235959  ...         0.0        0.0       0
5753  20230419   000000    000459  ...         0.0        0.0       0
5754  20230419   000500    000959  ...         0.0        0.0       0
5755  20230419   001000    001459  ...         0.0        0.0       0
5756  20230419   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 00:20:07,184:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681834799, self.tradeDate='20230419', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30241.0, self.close=30227.6, self.high=30247.0, self.low=30209.0, self.vol=1399.402, self.amt=42301357.5315, ukdf['pct'].iloc[-1]=-0.00044 , ukdf['amount'].iloc[-1]=42301357.5315, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37012
self.closeSec=1681835099, self.tradeDate='20230419', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30227.6, self.close=30218.0, self.high=30240.0, self.low=30216.7, self.vol=908.194, self.amt=27452778.0404 
127.0.0.1 - - [19/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-19 00:25:01,537:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230419   000000    000459  ...         0.0        0.0       0
5754  20230419   000500    000959  ...         0.0        0.0       0
5755  20230419   001000    001459  ...         0.0        0.0       0
5756  20230419   001500    001959  ...         0.0        0.0       0
5757  20230419   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 00:25:01,537:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681835099, self.tradeDate='20230419', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30227.6, self.close=30218.0, self.high=30240.0, self.low=30216.7, self.vol=908.194, self.amt=27452778.0404, ukdf['pct'].iloc[-1]=-0.000318 , ukdf['amount'].iloc[-1]=27452778.0404, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230418   120000    155959  1681804799  ...    723  0.633434  0.301390     NaN
724  20230418   160000    195959  1681819199  ...    724  0.524906  0.053565     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '112329.6068199825', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30408.9004155', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=866127.0.0.1 - - [19/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1681833599, self.tradeDate='20230418', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30369.7, self.close=30170.2, self.high=30480.0, self.low=30082.8, self.vol=143790.876, self.amt=4354219622.70112 
2023-04-19 00:00:01,831:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681833599, self.tradeDate='20230418', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30369.7, self.close=30170.2, self.high=30480.0, self.low=30082.8, self.vol=143790.876, self.amt=4354219622.70112 
2023-04-19 00:00:01,879:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230418   040000    075959  ...   29840.920  8.786944e+08 -0.001344
722  20230418   080000    115959  ...   65673.966  1.925481e+09  0.000398
723  20230418   120000    155959  ...   59863.929  1.773492e+09  0.011049
724  20230418   160000    195959  ...  120369.504  3.613284e+09  0.020594
725  20230418   200000    235959  ...  143790.876  4.354220e+09 -0.006569

[5 rows x 11 columns]
2023-04-19 00:00:04,057:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230418   040000    075959  1681775999  ...    721  0.613656  0.278546     NaN
722  20230418   080000    115959  1681790399  ...    722  0.645747  0.337719     NaN
723  20230418   120000    155959  1681804799  ...    723  0.633434  0.301390     NaN
724  20230418   160000    195959  1681819199  ...    724  0.524906  0.053565     NaN
725  20230418   200000    235959  1681833599  ...    725  0.515898  0.025734     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '100108.63711822365', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30176.18652991', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


