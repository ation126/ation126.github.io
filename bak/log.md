# 20230818 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27508
self.closeSec=1692289199, self.tradeDate='20230818', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27802.7, self.close=27812.9, self.high=27845.1, self.low=27782.7, self.vol=5009.54, self.amt=139364240.1279 
127.0.0.1 - - [18/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-18 00:20:04,856:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230817   235500    235959  ...         0.0        0.0       0
5748  20230818   000000    000459  ...         0.0        0.0       0
5749  20230818   000500    000959  ...         0.0        0.0       0
5750  20230818   001000    001459  ...         0.0        0.0       0
5751  20230818   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 00:20:04,866:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692289199, self.tradeDate='20230818', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27802.7, self.close=27812.9, self.high=27845.1, self.low=27782.7, self.vol=5009.54, self.amt=139364240.1279, ukdf['pct'].iloc[-1]=0.000288 , ukdf['amount'].iloc[-1]=139364240.1279, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13091.63758503084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27804.98599634', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27509
self.closeSec=1692289499, self.tradeDate='20230818', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27814.6, self.close=27796.8, self.high=27814.9, self.low=27771.5, self.vol=3870.731, self.amt=107580881.5027 
2023-08-18 00:25:00,817:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230818   000000    000459  ...         0.0        0.0       0
5749  20230818   000500    000959  ...         0.0        0.0       0
5750  20230818   001000    001459  ...         0.0        0.0       0
5751  20230818   001500    001959  ...         0.0        0.0       0
5752  20230818   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 00:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692289499, self.tradeDate='20230818', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27814.6, self.close=27796.8, self.high=27814.9, self.low=27771.5, self.vol=3870.731, self.amt=107580881.5027, ukdf['pct'].iloc[-1]=-0.000579 , ukdf['amount'].iloc[-1]=107580881.5027, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13101.5808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27805.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
      tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1065  20230816   164500    164959  1692175799  ...  29182.4 -0.000524   1641    3
1066  20230816   165000    165459  1692176099  ...  29171.7 -0.000164   1642    4
1067  20230816   165500    165959  1692176399  ...  29171.0 -0.000288   1643    5
1068  20230816   170000    170459  1692176699  ...  29165.1 -0.000120   1644    0
1069  20230816   170500    170959  1692176999  ...  29150.7 -0.000576   1645    1

[5 rows x 11 columns] 

127.0.0.1 - - [18/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27508 

self.closeSec=1692288599, self.tradeDate='20230818', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27741.9, self.close=27764.9, self.high=27865.4, self.low=27700.0 
127.0.0.1 - - [18/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27509 

self.closeSec=1692288899, self.tradeDate='20230818', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27770.0, self.close=27804.9, self.high=27830.0, self.low=27750.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27510 

self.closeSec=1692289199, self.tradeDate='20230818', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27802.7, self.close=27812.9, self.high=27845.1, self.low=27782.7 
127.0.0.1 - - [18/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27511 

self.closeSec=1692289499, self.tradeDate='20230818', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27814.6, self.close=27796.8, self.high=27814.9, self.low=27771.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-18 00:00:17,813:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230817    212959  28490.1  ...  45.833333  0.373378  0.696272
5802  20230817    215959  28516.5  ...  45.833333  0.347692  0.709103
5803  20230817    222959  28393.4  ...  45.833333  0.345018  0.722031
5804  20230817    225959  28379.8  ...  45.833333  0.348140  0.733006
5805  20230817    232959  28388.0  ...  45.833333  0.349854  0.738855

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-08-18 00:00:17,899:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.498237  0.501763       0  ...  0.998189  -1.0    0.0  0.976722
540     1  0.449289  0.550711       0  ...  0.998668  -1.0    0.0  0.976254
541     1  0.474329  0.525671       1  ...  0.998375  -1.0    0.0  0.976539
542     1  0.481198  0.518802       1  ...  0.998217  -1.0    0.0  0.976694
543     1  0.482478  0.517522       0  ...  1.014643  -1.0    0.0  0.960623

[5 rows x 10 columns]
2023-08-18 00:00:17,914:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498042  0.501958       0  ...  0.998189  -1.0    0.0  0.975986
46     1  0.449600  0.550400       0  ...  0.998668  -1.0    0.0  0.976822
47     1  0.474187  0.525813       1  ...  0.998375  -1.0    0.0  0.976849
48     1  0.481315  0.518685       1  ...  0.998217  -1.0    0.0  0.977003
49     1  0.482478  0.517522       0  ...  1.014643  -1.0    0.0  0.960623

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.207', 'enterprice': '29084.9', 'countrevence': '0', 'unrealprofit': '27654.0768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27942.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13751 

self.closeSec=1692286199, self.tradeDate='20230817', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28417.4', self.close='28392.5'
127.0.0.1 - - [17/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13752 

self.closeSec=1692286799, self.tradeDate='20230817', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28392.5', self.close='28026.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13753 

self.closeSec=1692287399, self.tradeDate='20230817', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28024.3', self.close='28031.8'
127.0.0.1 - - [17/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13754 

self.closeSec=1692287999, self.tradeDate='20230817', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28030.6', self.close='27925.3'
127.0.0.1 - - [18/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13755 

self.closeSec=1692288599, self.tradeDate='20230818', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27920.9', self.close='27764.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13756 

self.closeSec=1692289199, self.tradeDate='20230818', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27770', self.close='27814.5'
127.0.0.1 - - [18/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [17/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13754 

self.closeSec=1692286199, self.tradeDate='20230817', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28417.4', self.close='28392.5'
127.0.0.1 - - [17/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13755 

self.closeSec=1692286799, self.tradeDate='20230817', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28392.5', self.close='28026.2'
127.0.0.1 - - [17/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13756 

self.closeSec=1692287399, self.tradeDate='20230817', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28024.3', self.close='28031.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13757 

self.closeSec=1692287999, self.tradeDate='20230817', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28030.6', self.close='27925.3'
127.0.0.1 - - [18/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13758 

self.closeSec=1692288599, self.tradeDate='20230818', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27920.9', self.close='27764.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13759 

self.closeSec=1692289199, self.tradeDate='20230818', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27770', self.close='27814.5'
127.0.0.1 - - [18/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13754 

self.closeSec=1692286199, self.tradeDate='20230817', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28417.4', self.close='28392.5'
127.0.0.1 - - [17/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13755 

self.closeSec=1692286799, self.tradeDate='20230817', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28392.5', self.close='28026.2'
127.0.0.1 - - [17/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13756 

self.closeSec=1692287399, self.tradeDate='20230817', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28024.3', self.close='28031.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13757 

self.closeSec=1692287999, self.tradeDate='20230817', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28030.6', self.close='27925.3'
127.0.0.1 - - [18/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13758 

self.closeSec=1692288599, self.tradeDate='20230818', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27920.9', self.close='27764.9'
127.0.0.1 - - [18/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13759 

self.closeSec=1692289199, self.tradeDate='20230818', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27770', self.close='27814.5'
127.0.0.1 - - [18/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27508
self.closeSec=1692289199, self.tradeDate='20230818', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27802.7, self.close=27812.9, self.high=27845.1, self.low=27782.7, self.vol=5009.54, self.amt=139364240.1279 
127.0.0.1 - - [18/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-18 00:20:04,844:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230817   235500    235959  ...         0.0        0.0       0
5748  20230818   000000    000459  ...         0.0        0.0       0
5749  20230818   000500    000959  ...         0.0        0.0       0
5750  20230818   001000    001459  ...         0.0        0.0       0
5751  20230818   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 00:20:04,846:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692289199, self.tradeDate='20230818', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27802.7, self.close=27812.9, self.high=27845.1, self.low=27782.7, self.vol=5009.54, self.amt=139364240.1279, ukdf['pct'].iloc[-1]=0.000288 , ukdf['amount'].iloc[-1]=139364240.1279, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '35691.98089006394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27804.98599634', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27509
self.closeSec=1692289499, self.tradeDate='20230818', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27814.6, self.close=27796.8, self.high=27814.9, self.low=27771.5, self.vol=3870.731, self.amt=107580881.5027 
127.0.0.1 - - [18/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-18 00:25:00,820:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230818   000000    000459  ...         0.0        0.0       0
5749  20230818   000500    000959  ...         0.0        0.0       0
5750  20230818   001000    001459  ...         0.0        0.0       0
5751  20230818   001500    001959  ...         0.0        0.0       0
5752  20230818   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 00:25:00,821:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692289499, self.tradeDate='20230818', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27814.6, self.close=27796.8, self.high=27814.9, self.low=27771.5, self.vol=3870.731, self.amt=107580881.5027, ukdf['pct'].iloc[-1]=-0.000579 , ukdf['amount'].iloc[-1]=107580881.5027, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '35718.4997', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27805.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230817   120000    155959  1692259199  ...    723  0.389168 -0.246678     NaN
724  20230817   160000    195959  1692273599  ...    724  0.502190  0.003736     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '45868.9288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28540', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=573
self.closeSec=1692287999, self.tradeDate='20230817', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28540.0, self.close=27925.3, self.high=28569.3, self.low=27855.0, self.vol=182531.64, self.amt=5157597232.88357 
127.0.0.1 - - [18/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-18 00:00:01,606:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692287999, self.tradeDate='20230817', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28540.0, self.close=27925.3, self.high=28569.3, self.low=27855.0, self.vol=182531.64, self.amt=5157597232.88357 
2023-08-18 00:00:01,621:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230817   040000    075959  ...   81121.615  2.344017e+09 -0.013437
722  20230817   080000    115959  ...  100604.312  2.873872e+09 -0.002469
723  20230817   120000    155959  ...   27424.778  7.854386e+08 -0.001061
724  20230817   160000    195959  ...   39605.705  1.130810e+09 -0.002555
725  20230817   200000    235959  ...  182531.640  5.157597e+09 -0.021538

[5 rows x 11 columns]
2023-08-18 00:00:02,403:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230817   040000    075959  1692230399  ...    721  0.147228 -0.788914    -1.0
722  20230817   080000    115959  1692244799  ...    722  0.272425 -0.507407     NaN
723  20230817   120000    155959  1692259199  ...    723  0.389168 -0.246678     NaN
724  20230817   160000    195959  1692273599  ...    724  0.502190  0.003736     NaN
725  20230817   200000    235959  1692287999  ...    725  0.423048 -0.179032     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '77385.1892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27926.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


