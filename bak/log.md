# 20230416 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40245
self.closeSec=1681604399, self.tradeDate='20230416', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30268.0, self.close=30298.5, self.high=30298.6, self.low=30264.1, self.vol=368.158, self.amt=11146943.7205 
127.0.0.1 - - [16/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-16 08:20:07,668:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230416   075500    075959  ...         0.0        0.0       0
5849  20230416   080000    080459  ...         0.0        0.0       0
5850  20230416   080500    080959  ...         0.0        0.0       0
5851  20230416   081000    081459  ...         0.0        0.0       0
5852  20230416   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 08:20:07,687:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681604399, self.tradeDate='20230416', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30268.0, self.close=30298.5, self.high=30298.6, self.low=30264.1, self.vol=368.158, self.amt=11146943.7205, ukdf['pct'].iloc[-1]=0.001004 , ukdf['amount'].iloc[-1]=11146943.7205, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-828635.5552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30299.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=40246
self.closeSec=1681604699, self.tradeDate='20230416', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30298.6, self.close=30278.3, self.high=30307.8, self.low=30278.3, self.vol=333.864, self.amt=10114011.5654 
2023-04-16 08:25:01,638:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230416   080000    080459  ...         0.0        0.0       0
5850  20230416   080500    080959  ...         0.0        0.0       0
5851  20230416   081000    081459  ...         0.0        0.0       0
5852  20230416   081500    081959  ...         0.0        0.0       0
5853  20230416   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 08:25:01,641:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681604699, self.tradeDate='20230416', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30298.6, self.close=30278.3, self.high=30307.8, self.low=30278.3, self.vol=333.864, self.amt=10114011.5654, ukdf['pct'].iloc[-1]=-0.000667 , ukdf['amount'].iloc[-1]=10114011.5654, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-827421.54069635792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30279.32560317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [16/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40807 

self.closeSec=1681603199, self.tradeDate='20230416', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30290.9, self.close=30280.4, self.high=30291.0, self.low=30274.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40808 

self.closeSec=1681603499, self.tradeDate='20230416', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=30280.4, self.close=30284.1, self.high=30284.3, self.low=30274.3 
127.0.0.1 - - [16/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40809 

self.closeSec=1681603799, self.tradeDate='20230416', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=30284.2, self.close=30294.4, self.high=30296.7, self.low=30284.1 
127.0.0.1 - - [16/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40810 

self.closeSec=1681604099, self.tradeDate='20230416', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=30294.3, self.close=30268.1, self.high=30298.6, self.low=30268.0 
127.0.0.1 - - [16/Apr/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40811 

self.closeSec=1681604399, self.tradeDate='20230416', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30268.0, self.close=30298.5, self.high=30298.6, self.low=30264.1 
127.0.0.1 - - [16/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40812 

self.closeSec=1681604699, self.tradeDate='20230416', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30298.6, self.close=30278.3, self.high=30307.8, self.low=30278.3 
127.0.0.1 - - [16/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-16 08:00:36,327:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230416    052959  30268.2  ...  54.583333  0.480075  0.637894
5770  20230416    055959  30272.3  ...  54.166667  0.475090  0.646231
5771  20230416    062959  30251.9  ...  54.166667  0.495074  0.635739
5772  20230416    065959  30328.1  ...  54.166667  0.496588  0.624531
5773  20230416    072959  30334.1  ...  53.750000  0.492121  0.618268

[5 rows x 33 columns]
0.5592592592592592
acc is : 0.5592592592592592
2023-04-16 08:00:36,490:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.510500  0.489500       0  ...  1.028492  -1.0    0.0  1.075734
536     0  0.505419  0.494581       1  ...  1.025902  -1.0    0.0  1.078444
537     0  0.526086  0.473914       1  ...  1.025702  -1.0    0.0  1.078653
538     0  0.511883  0.488117       0  ...  1.026294  -1.0    0.0  1.078031
539     0  0.510135  0.489865       0  ...  1.027516  -1.0    0.0  1.076747

[5 rows x 10 columns]
2023-04-16 08:00:36,526:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512218  0.487782       0  ...  1.019256  -1.0    0.0  1.080927
46     0  0.506656  0.493344       1  ...  1.016689  -1.0    0.0  1.082694
47     0  0.526822  0.473178       1  ...  1.041989  -1.0    0.0  1.081619
48     0  0.512198  0.487802       0  ...  1.026294  -1.0    0.0  1.079413
49     0  0.510135  0.489865       0  ...  1.027516  -1.0    0.0  1.076747

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20401 

self.closeSec=1681601399, self.tradeDate='20230416', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30314.8', self.close='30316.5'
127.0.0.1 - - [16/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20402 

self.closeSec=1681601999, self.tradeDate='20230416', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30316.5', self.close='30311.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20403 

self.closeSec=1681602599, self.tradeDate='20230416', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30311.4', self.close='30280.2'
127.0.0.1 - - [16/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20404 

self.closeSec=1681603199, self.tradeDate='20230416', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30280.2', self.close='30280.4'
127.0.0.1 - - [16/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20405 

self.closeSec=1681603799, self.tradeDate='20230416', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30280.4', self.close='30294.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20406 

self.closeSec=1681604399, self.tradeDate='20230416', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30294.3', self.close='30298.5'
127.0.0.1 - - [16/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20402 

self.closeSec=1681601399, self.tradeDate='20230416', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30314.8', self.close='30316.5'
127.0.0.1 - - [16/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20403 

self.closeSec=1681601999, self.tradeDate='20230416', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30316.5', self.close='30311.4'
127.0.0.1 - - [16/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20404 

self.closeSec=1681602599, self.tradeDate='20230416', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30311.4', self.close='30280.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20405 

self.closeSec=1681603199, self.tradeDate='20230416', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30280.2', self.close='30280.4'
127.0.0.1 - - [16/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20406 

self.closeSec=1681603799, self.tradeDate='20230416', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30280.4', self.close='30294.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20407 

self.closeSec=1681604399, self.tradeDate='20230416', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30294.3', self.close='30298.5'
127.0.0.1 - - [16/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20402 

self.closeSec=1681601399, self.tradeDate='20230416', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30314.8', self.close='30316.5'
127.0.0.1 - - [16/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20403 

self.closeSec=1681601999, self.tradeDate='20230416', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30316.5', self.close='30311.4'
127.0.0.1 - - [16/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20404 

self.closeSec=1681602599, self.tradeDate='20230416', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30311.4', self.close='30280.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20405 

self.closeSec=1681603199, self.tradeDate='20230416', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30280.2', self.close='30280.4'
127.0.0.1 - - [16/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20406 

self.closeSec=1681603799, self.tradeDate='20230416', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30280.4', self.close='30294.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20407 

self.closeSec=1681604399, self.tradeDate='20230416', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30294.3', self.close='30298.5'
127.0.0.1 - - [16/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36243
self.closeSec=1681604399, self.tradeDate='20230416', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30268.0, self.close=30298.5, self.high=30298.6, self.low=30264.1, self.vol=368.158, self.amt=11146943.7205 
127.0.0.1 - - [16/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-16 08:20:07,299:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230416   075500    075959  ...         0.0        0.0       0
5849  20230416   080000    080459  ...         0.0        0.0       0
5850  20230416   080500    080959  ...         0.0        0.0       0
5851  20230416   081000    081459  ...         0.0        0.0       0
5852  20230416   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 08:20:07,307:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681604399, self.tradeDate='20230416', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30268.0, self.close=30298.5, self.high=30298.6, self.low=30264.1, self.vol=368.158, self.amt=11146943.7205, ukdf['pct'].iloc[-1]=0.001004 , ukdf['amount'].iloc[-1]=11146943.7205, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=36244
self.closeSec=1681604699, self.tradeDate='20230416', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30298.6, self.close=30278.3, self.high=30307.8, self.low=30278.3, self.vol=333.864, self.amt=10114011.5654 
2023-04-16 08:25:01,642:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230416   080000    080459  ...         0.0        0.0       0
5850  20230416   080500    080959  ...         0.0        0.0       0
5851  20230416   081000    081459  ...         0.0        0.0       0
5852  20230416   081500    081959  ...         0.0        0.0       0
5853  20230416   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-16 08:25:01,642:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681604699, self.tradeDate='20230416', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30298.6, self.close=30278.3, self.high=30307.8, self.low=30278.3, self.vol=333.864, self.amt=10114011.5654, ukdf['pct'].iloc[-1]=-0.000667 , ukdf['amount'].iloc[-1]=10114011.5654, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230415   200000    235959  1681574399  ...    719  0.323811 -0.377998     NaN
720  20230416   000000    035959  1681588799  ...    720  0.300235 -0.416641     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '107997.0975', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30326.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [16/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=850
self.closeSec=1681603199, self.tradeDate='20230416', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30318.9, self.close=30280.4, self.high=30350.0, self.low=30220.4, self.vol=22141.798, self.amt=670811100.034 
2023-04-16 08:00:01,927:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681603199, self.tradeDate='20230416', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30318.9, self.close=30280.4, self.high=30350.0, self.low=30220.4, self.vol=22141.798, self.amt=670811100.034 
2023-04-16 08:00:02,012:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230415   120000    155959  ...  20229.732  6.146483e+08  0.001630
718  20230415   160000    195959  ...  24960.612  7.588878e+08 -0.001499
719  20230415   200000    235959  ...  32820.069  9.963811e+08 -0.001683
720  20230416   000000    035959  ...  38861.466  1.176269e+09 -0.000033
721  20230416   040000    075959  ...  22141.798  6.708111e+08 -0.001270

[5 rows x 11 columns]
2023-04-16 08:00:05,044:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230415   120000    155959  1681545599  ...    717  0.409521 -0.207092     NaN
718  20230415   160000    195959  1681559999  ...    718  0.356162 -0.316022     NaN
719  20230415   200000    235959  1681574399  ...    719  0.323811 -0.377998     NaN
720  20230416   000000    035959  1681588799  ...    720  0.300235 -0.416641     NaN
721  20230416   040000    075959  1681603199  ...    721  0.295218 -0.415715     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '105642.630820881', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30281.5658254', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


