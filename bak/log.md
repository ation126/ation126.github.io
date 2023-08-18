# 20230819 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27796
self.closeSec=1692375599, self.tradeDate='20230819', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26083.8, self.close=26069.1, self.high=26096.5, self.low=26029.7, self.vol=1864.245, self.amt=48580056.9111 
127.0.0.1 - - [19/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-19 00:20:05,152:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230818   235500    235959  ...         0.0        0.0       0
5748  20230819   000000    000459  ...         0.0        0.0       0
5749  20230819   000500    000959  ...         0.0        0.0       0
5750  20230819   001000    001459  ...         0.0        0.0       0
5751  20230819   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 00:20:05,162:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692375599, self.tradeDate='20230819', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26083.8, self.close=26069.1, self.high=26096.5, self.low=26029.7, self.vol=1864.245, self.amt=48580056.9111, ukdf['pct'].iloc[-1]=-0.000414 , ukdf['amount'].iloc[-1]=48580056.9111, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11203.467', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26060.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27797
self.closeSec=1692375899, self.tradeDate='20230819', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26069.2, self.close=26025.5, self.high=26069.2, self.low=26010.3, self.vol=1696.826, self.amt=44168139.1962 
127.0.0.1 - - [19/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-19 00:25:00,852:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230819   000000    000459  ...         0.0        0.0       0
5749  20230819   000500    000959  ...         0.0        0.0       0
5750  20230819   001000    001459  ...         0.0        0.0       0
5751  20230819   001500    001959  ...         0.0        0.0       0
5752  20230819   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 00:25:00,852:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692375899, self.tradeDate='20230819', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26069.2, self.close=26025.5, self.high=26069.2, self.low=26010.3, self.vol=1696.826, self.amt=44168139.1962, ukdf['pct'].iloc[-1]=-0.001672 , ukdf['amount'].iloc[-1]=44168139.1962, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11689.4844', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26025.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
777  20230816   164500    164959  1692175799  ...  29182.4 -0.000524   1641    3
778  20230816   165000    165459  1692176099  ...  29171.7 -0.000164   1642    4
779  20230816   165500    165959  1692176399  ...  29171.0 -0.000288   1643    5
780  20230816   170000    170459  1692176699  ...  29165.1 -0.000120   1644    0
781  20230816   170500    170959  1692176999  ...  29150.7 -0.000576   1645    1

[5 rows x 11 columns] 

127.0.0.1 - - [19/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27796 

self.closeSec=1692374999, self.tradeDate='20230819', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26071.5, self.close=26088.0, self.high=26109.6, self.low=26057.8 
127.0.0.1 - - [19/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27797 

self.closeSec=1692375299, self.tradeDate='20230819', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26084.9, self.close=26079.9, self.high=26134.7, self.low=26073.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27798 

self.closeSec=1692375599, self.tradeDate='20230819', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26083.8, self.close=26069.1, self.high=26096.5, self.low=26029.7 
127.0.0.1 - - [19/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27799 

self.closeSec=1692375899, self.tradeDate='20230819', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26069.2, self.close=26025.5, self.high=26069.2, self.low=26010.3 
127.0.0.1 - - [19/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-19 00:00:17,243:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230818    212959  26318.0  ...  44.166667  0.313851  0.549207
5802  20230818    215959  26245.8  ...  44.166667  0.312377  0.547295
5803  20230818    222959  26227.9  ...  43.750000  0.305925  0.546557
5804  20230818    225959  26151.8  ...  43.333333  0.293558  0.548881
5805  20230818    232959  25998.7  ...  43.750000  0.311911  0.549097

[5 rows x 33 columns]
0.5165441176470589
acc is : 0.5165441176470589
2023-08-19 00:00:17,304:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.392745  0.607255       0  ...  1.105814  -1.0    0.0  0.902197
540     1  0.422864  0.577136       0  ...  1.109043  -1.0    0.0  0.899562
541     1  0.385015  0.614985       0  ...  1.115536  -1.0    0.0  0.894296
542     1  0.353143  0.646857       1  ...  1.111288  -1.0    0.0  0.897701
543     1  0.458921  0.541079       0  ...  1.115742  -1.0    0.0  0.894103

[5 rows x 10 columns]
2023-08-19 00:00:17,315:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.392902  0.607098       0  ...  1.105814  -1.0    0.0  0.900840
46     1  0.423310  0.576690       0  ...  1.109043  -1.0    0.0  0.899222
47     1  0.385284  0.614716       0  ...  1.115536  -1.0    0.0  0.895229
48     1  0.353413  0.646587       1  ...  1.111288  -1.0    0.0  0.898638
49     1  0.458921  0.541079       0  ...  1.115742  -1.0    0.0  0.894103

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.207', 'enterprice': '29084.9', 'countrevence': '0', 'unrealprofit': '75111.81003354942', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25982.00372894', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [18/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13895 

self.closeSec=1692372599, self.tradeDate='20230818', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26189.8', self.close='26097.7'
127.0.0.1 - - [18/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13896 

self.closeSec=1692373199, self.tradeDate='20230818', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26097.7', self.close='26044'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13897 

self.closeSec=1692373799, self.tradeDate='20230818', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26044', self.close='25972.4'
127.0.0.1 - - [18/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13898 

self.closeSec=1692374399, self.tradeDate='20230818', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25970.2', self.close='25993.1'
127.0.0.1 - - [19/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13899 

self.closeSec=1692374999, self.tradeDate='20230819', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25993.1', self.close='26088'
127.0.0.1 - - [19/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13900 

self.closeSec=1692375599, self.tradeDate='20230819', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26084.9', self.close='26069.1'
127.0.0.1 - - [19/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13898 

self.closeSec=1692372599, self.tradeDate='20230818', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26189.8', self.close='26097.7'
127.0.0.1 - - [18/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13899 

self.closeSec=1692373199, self.tradeDate='20230818', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26097.7', self.close='26044'
127.0.0.1 - - [18/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13900 

self.closeSec=1692373799, self.tradeDate='20230818', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26044', self.close='25972.4'
127.0.0.1 - - [19/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13901 

self.closeSec=1692374399, self.tradeDate='20230818', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25970.2', self.close='25993.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13902 

self.closeSec=1692374999, self.tradeDate='20230819', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25993.1', self.close='26088'
127.0.0.1 - - [19/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13903 

self.closeSec=1692375599, self.tradeDate='20230819', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26084.9', self.close='26069.1'
127.0.0.1 - - [19/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [18/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13898 

self.closeSec=1692372599, self.tradeDate='20230818', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26189.8', self.close='26097.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13899 

self.closeSec=1692373199, self.tradeDate='20230818', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26097.7', self.close='26044'
127.0.0.1 - - [18/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13900 

self.closeSec=1692373799, self.tradeDate='20230818', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26044', self.close='25972.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13901 

self.closeSec=1692374399, self.tradeDate='20230818', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25970.2', self.close='25993.1'
127.0.0.1 - - [19/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13902 

self.closeSec=1692374999, self.tradeDate='20230819', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25993.1', self.close='26088'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13903 

self.closeSec=1692375599, self.tradeDate='20230819', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26084.9', self.close='26069.1'
127.0.0.1 - - [19/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27796
self.closeSec=1692375599, self.tradeDate='20230819', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26083.8, self.close=26069.1, self.high=26096.5, self.low=26029.7, self.vol=1864.245, self.amt=48580056.9111 
127.0.0.1 - - [19/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-19 00:20:05,147:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230818   235500    235959  ...         0.0        0.0       0
5748  20230819   000000    000459  ...         0.0        0.0       0
5749  20230819   000500    000959  ...         0.0        0.0       0
5750  20230819   001000    001459  ...         0.0        0.0       0
5751  20230819   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 00:20:05,150:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692375599, self.tradeDate='20230819', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26083.8, self.close=26069.1, self.high=26096.5, self.low=26029.7, self.vol=1864.245, self.amt=48580056.9111, ukdf['pct'].iloc[-1]=-0.000414 , ukdf['amount'].iloc[-1]=48580056.9111, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29103.6876', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26060.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27797
self.closeSec=1692375899, self.tradeDate='20230819', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26069.2, self.close=26025.5, self.high=26069.2, self.low=26010.3, self.vol=1696.826, self.amt=44168139.1962 
127.0.0.1 - - [19/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-19 00:25:00,859:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230819   000000    000459  ...         0.0        0.0       0
5749  20230819   000500    000959  ...         0.0        0.0       0
5750  20230819   001000    001459  ...         0.0        0.0       0
5751  20230819   001500    001959  ...         0.0        0.0       0
5752  20230819   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 00:25:00,860:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692375899, self.tradeDate='20230819', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26069.2, self.close=26025.5, self.high=26069.2, self.low=26010.3, self.vol=1696.826, self.amt=44168139.1962, ukdf['pct'].iloc[-1]=-0.001672 , ukdf['amount'].iloc[-1]=44168139.1962, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-30399.9085', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26025.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230818   120000    155959  1692345599  ...    723  0.259513 -0.542461     NaN
724  20230818   160000    195959  1692359999  ...    724  0.315037 -0.414487     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '151430.1584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26485.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=579
self.closeSec=1692374399, self.tradeDate='20230818', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26479.5, self.close=25993.1, self.high=26489.6, self.low=25918.2, self.vol=130570.32, self.amt=3418381447.875 
127.0.0.1 - - [19/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-19 00:00:01,557:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692374399, self.tradeDate='20230818', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26479.5, self.close=25993.1, self.high=26489.6, self.low=25918.2, self.vol=130570.32, self.amt=3418381447.875 
2023-08-19 00:00:01,578:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230818   040000    075959  ...  384716.301  1.021675e+10 -0.045885
722  20230818   080000    115959  ...   78941.126  2.099161e+09 -0.008407
723  20230818   120000    155959  ...   75859.899  2.001522e+09  0.001232
724  20230818   160000    195959  ...   49121.525  1.300346e+09  0.002309
725  20230818   200000    235959  ...  130570.320  3.418381e+09 -0.018369

[5 rows x 11 columns]
2023-08-19 00:00:02,439:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230818   040000    075959  1692316799  ...    721  0.117928 -0.871146    -1.0
722  20230818   080000    115959  1692331199  ...    722  0.188193 -0.707026    -1.0
723  20230818   120000    155959  1692345599  ...    723  0.259513 -0.542461     NaN
724  20230818   160000    195959  1692359999  ...    724  0.315037 -0.414487     NaN
725  20230818   200000    235959  1692374399  ...    725  0.364333 -0.301664     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '176795.2752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25992.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


