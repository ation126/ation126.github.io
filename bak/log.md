# 20230418 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40821
self.closeSec=1681777199, self.tradeDate='20230418', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29435.0, self.close=29381.9, self.high=29435.1, self.low=29374.1, self.vol=1271.507, self.amt=37375805.3493 
127.0.0.1 - - [18/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-18 08:20:07,300:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230418   075500    075959  ...         0.0        0.0       0
5849  20230418   080000    080459  ...         0.0        0.0       0
5850  20230418   080500    080959  ...         0.0        0.0       0
5851  20230418   081000    081459  ...         0.0        0.0       0
5852  20230418   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 08:20:07,309:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681777199, self.tradeDate='20230418', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29435.0, self.close=29381.9, self.high=29435.1, self.low=29374.1, self.vol=1271.507, self.amt=37375805.3493, ukdf['pct'].iloc[-1]=-0.001807 , ukdf['amount'].iloc[-1]=37375805.3493, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-773282.5116745048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29379.64750855', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40822
self.closeSec=1681777499, self.tradeDate='20230418', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29381.9, self.close=29423.9, self.high=29429.5, self.low=29373.7, self.vol=1107.975, self.amt=32575902.2404 
127.0.0.1 - - [18/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-18 08:25:01,711:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230418   080000    080459  ...         0.0        0.0       0
5850  20230418   080500    080959  ...         0.0        0.0       0
5851  20230418   081000    081459  ...         0.0        0.0       0
5852  20230418   081500    081959  ...         0.0        0.0       0
5853  20230418   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 08:25:01,711:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681777499, self.tradeDate='20230418', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29381.9, self.close=29423.9, self.high=29429.5, self.low=29373.7, self.vol=1107.975, self.amt=32575902.2404, ukdf['pct'].iloc[-1]=0.001429 , ukdf['amount'].iloc[-1]=32575902.2404, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-775945.4496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29423.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [18/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41383 

self.closeSec=1681775999, self.tradeDate='20230418', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29403.2, self.close=29420.0, self.high=29422.7, self.low=29380.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41384 

self.closeSec=1681776299, self.tradeDate='20230418', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29420.1, self.close=29417.0, self.high=29426.2, self.low=29407.0 
127.0.0.1 - - [18/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41385 

self.closeSec=1681776599, self.tradeDate='20230418', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29416.9, self.close=29434.6, self.high=29434.6, self.low=29414.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41386 

self.closeSec=1681776899, self.tradeDate='20230418', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29434.5, self.close=29435.1, self.high=29439.8, self.low=29427.5 
127.0.0.1 - - [18/Apr/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41387 

self.closeSec=1681777199, self.tradeDate='20230418', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29435.0, self.close=29381.9, self.high=29435.1, self.low=29374.1 
127.0.0.1 - - [18/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41388 

self.closeSec=1681777499, self.tradeDate='20230418', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29381.9, self.close=29423.9, self.high=29429.5, self.low=29373.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-18 08:00:35,541:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230418    052959  29436.0  ...  52.916667  0.379320  0.777519
5770  20230418    055959  29424.7  ...  52.916667  0.383339  0.775663
5771  20230418    062959  29438.2  ...  53.333333  0.398020  0.770096
5772  20230418    065959  29488.6  ...  53.750000  0.398951  0.763030
5773  20230418    072959  29491.7  ...  53.333333  0.391974  0.758545

[5 rows x 33 columns]
0.562962962962963
acc is : 0.562962962962963
2023-04-18 08:00:35,710:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.514725  0.485275       1  ...  1.070017  -1.0    0.0  1.048944
536     0  0.518906  0.481094       1  ...  1.068192  -1.0    0.0  1.050733
537     0  0.534585  0.465415       1  ...  1.068076  -1.0    0.0  1.050847
538     0  0.527493  0.472507       0  ...  1.069384  -1.0    0.0  1.049560
539     0  0.517319  0.482681       0  ...  1.070676  -1.0    0.0  1.048292

[5 rows x 10 columns]
2023-04-18 08:00:35,737:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515747  0.484253       1  ...  1.041998  -1.0    0.0  1.049187
46     0  0.519271  0.480729       1  ...  1.068192  -1.0    0.0  1.050186
47     0  0.534654  0.465346       1  ...  1.068076  -1.0    0.0  1.049938
48     0  0.528043  0.471957       0  ...  1.069384  -1.0    0.0  1.050058
49     0  0.517319  0.482681       0  ...  1.070676  -1.0    0.0  1.048292

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [18/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20689 

self.closeSec=1681774199, self.tradeDate='20230418', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29451.2', self.close='29455.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20690 

self.closeSec=1681774799, self.tradeDate='20230418', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29455.6', self.close='29435.1'
127.0.0.1 - - [18/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20691 

self.closeSec=1681775399, self.tradeDate='20230418', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29435.1', self.close='29418.9'
127.0.0.1 - - [18/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20692 

self.closeSec=1681775999, self.tradeDate='20230418', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29419', self.close='29420'
127.0.0.1 - - [18/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20693 

self.closeSec=1681776599, self.tradeDate='20230418', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29420.1', self.close='29434.6'
127.0.0.1 - - [18/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20694 

self.closeSec=1681777199, self.tradeDate='20230418', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29434.5', self.close='29382'
127.0.0.1 - - [18/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20690 

self.closeSec=1681774199, self.tradeDate='20230418', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29451.2', self.close='29455.6'
127.0.0.1 - - [18/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20691 

self.closeSec=1681774799, self.tradeDate='20230418', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29455.6', self.close='29435.1'
127.0.0.1 - - [18/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20692 

self.closeSec=1681775399, self.tradeDate='20230418', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29435.1', self.close='29418.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20693 

self.closeSec=1681775999, self.tradeDate='20230418', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29419', self.close='29420'
127.0.0.1 - - [18/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20694 

self.closeSec=1681776599, self.tradeDate='20230418', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29420.1', self.close='29434.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20695 

self.closeSec=1681777199, self.tradeDate='20230418', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29434.5', self.close='29382'
127.0.0.1 - - [18/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [18/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20690 

self.closeSec=1681774199, self.tradeDate='20230418', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29451.2', self.close='29455.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20691 

self.closeSec=1681774799, self.tradeDate='20230418', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29455.6', self.close='29435.1'
127.0.0.1 - - [18/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20692 

self.closeSec=1681775399, self.tradeDate='20230418', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29435.1', self.close='29418.9'
127.0.0.1 - - [18/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20693 

self.closeSec=1681775999, self.tradeDate='20230418', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29419', self.close='29420'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20694 

self.closeSec=1681776599, self.tradeDate='20230418', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29420.1', self.close='29434.6'
127.0.0.1 - - [18/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20695 

self.closeSec=1681777199, self.tradeDate='20230418', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29434.5', self.close='29382'
127.0.0.1 - - [18/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36819
self.closeSec=1681777199, self.tradeDate='20230418', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29435.0, self.close=29381.9, self.high=29435.1, self.low=29374.1, self.vol=1271.507, self.amt=37375805.3493 
127.0.0.1 - - [18/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-18 08:20:07,238:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230418   075500    075959  ...         0.0        0.0       0
5849  20230418   080000    080459  ...         0.0        0.0       0
5850  20230418   080500    080959  ...         0.0        0.0       0
5851  20230418   081000    081459  ...         0.0        0.0       0
5852  20230418   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 08:20:07,249:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681777199, self.tradeDate='20230418', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29435.0, self.close=29381.9, self.high=29435.1, self.low=29374.1, self.vol=1271.507, self.amt=37375805.3493, ukdf['pct'].iloc[-1]=-0.001807 , ukdf['amount'].iloc[-1]=37375805.3493, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [18/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36820
self.closeSec=1681777499, self.tradeDate='20230418', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29381.9, self.close=29423.9, self.high=29429.5, self.low=29373.7, self.vol=1107.975, self.amt=32575902.2404 
2023-04-18 08:25:01,723:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230418   080000    080459  ...         0.0        0.0       0
5850  20230418   080500    080959  ...         0.0        0.0       0
5851  20230418   081000    081459  ...         0.0        0.0       0
5852  20230418   081500    081959  ...         0.0        0.0       0
5853  20230418   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-18 08:25:01,724:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681777499, self.tradeDate='20230418', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29381.9, self.close=29423.9, self.high=29429.5, self.low=29373.7, self.vol=1107.975, self.amt=32575902.2404, ukdf['pct'].iloc[-1]=0.001429 , ukdf['amount'].iloc[-1]=32575902.2404, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230417   200000    235959  1681747199  ...    719  0.416468 -0.132860     NaN
720  20230418   000000    035959  1681761599  ...    720  0.528920  0.103449     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '62781.0051909384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29465.38710256', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [18/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=862
self.closeSec=1681775999, self.tradeDate='20230418', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29459.6, self.close=29420.0, self.high=29524.0, self.low=29370.0, self.vol=29840.92, self.amt=878694385.8403 
2023-04-18 08:00:01,797:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681775999, self.tradeDate='20230418', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29459.6, self.close=29420.0, self.high=29524.0, self.low=29370.0, self.vol=29840.92, self.amt=878694385.8403 
2023-04-18 08:00:01,840:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230417   120000    155959  ...   33276.831  9.956101e+08 -0.004518
718  20230417   160000    195959  ...   93915.835  2.787477e+09 -0.009152
719  20230417   200000    235959  ...  131855.384  3.877899e+09 -0.007159
720  20230418   000000    035959  ...   55045.794  1.621368e+09  0.003854
721  20230418   040000    075959  ...   29840.920  8.786944e+08 -0.001344

[5 rows x 11 columns]
2023-04-18 08:00:04,123:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230417   120000    155959  1681718399  ...    717  0.309766 -0.351132     NaN
718  20230417   160000    195959  1681732799  ...    718  0.278616 -0.425114     NaN
719  20230417   200000    235959  1681747199  ...    719  0.416468 -0.132860     NaN
720  20230418   000000    035959  1681761599  ...    720  0.528920  0.103449     NaN
721  20230418   040000    075959  1681775999  ...    721  0.613656  0.278546     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '60402.753', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29420.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


