# 20231006 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41812
self.closeSec=1696580399, self.tradeDate='20231006', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27626.1, self.close=27607.6, self.high=27626.2, self.low=27587.1, self.vol=1139.533, self.amt=31454258.9659 
127.0.0.1 - - [06/Oct/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-10-06 16:20:06,264:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231006   155500    155959  ...         0.0        0.0       0
5952  20231006   160000    160459  ...         0.0        0.0       0
5953  20231006   160500    160959  ...         0.0        0.0       0
5954  20231006   161000    161459  ...         0.0        0.0       0
5955  20231006   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 16:20:06,268:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696580399, self.tradeDate='20231006', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27626.1, self.close=27607.6, self.high=27626.2, self.low=27587.1, self.vol=1139.533, self.amt=31454258.9659, ukdf['pct'].iloc[-1]=-0.000673 , ukdf['amount'].iloc[-1]=31454258.9659, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-10341.4476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27607.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41813
self.closeSec=1696580699, self.tradeDate='20231006', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27607.6, self.close=27639.0, self.high=27646.9, self.low=27607.5, self.vol=930.835, self.amt=25721710.0466 
2023-10-06 16:25:00,805:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231006   160000    160459  ...         0.0        0.0       0
5953  20231006   160500    160959  ...         0.0        0.0       0
5954  20231006   161000    161459  ...         0.0        0.0       0
5955  20231006   161500    161959  ...         0.0        0.0       0
5956  20231006   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 16:25:00,805:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696580699, self.tradeDate='20231006', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27607.6, self.close=27639.0, self.high=27646.9, self.low=27607.5, self.vol=930.835, self.amt=25721710.0466, ukdf['pct'].iloc[-1]=0.001137 , ukdf['amount'].iloc[-1]=25721710.0466, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-10780.1166', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27639', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [06/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41810 

self.closeSec=1696579199, self.tradeDate='20231006', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27607.8, self.close=27627.1, self.high=27629.4, self.low=27602.1 
127.0.0.1 - - [06/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41811 

self.closeSec=1696579499, self.tradeDate='20231006', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27626.8, self.close=27619.9, self.high=27634.0, self.low=27614.1 

--handleKline--: 127.0.0.1 - - [06/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41812 

self.closeSec=1696579799, self.tradeDate='20231006', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27619.9, self.close=27619.5, self.high=27629.6, self.low=27606.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41813 

self.closeSec=1696580099, self.tradeDate='20231006', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27619.5, self.close=27626.2, self.high=27648.4, self.low=27611.9 
127.0.0.1 - - [06/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41814 

self.closeSec=1696580399, self.tradeDate='20231006', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27626.1, self.close=27607.6, self.high=27626.2, self.low=27587.1 
127.0.0.1 - - [06/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41815 

self.closeSec=1696580699, self.tradeDate='20231006', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27607.6, self.close=27639.0, self.high=27646.9, self.low=27607.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-06 16:00:18,142:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231006    132959  27516.1  ...  55.000000  0.478294  0.745116
5786  20231006    135959  27464.4  ...  55.000000  0.484027  0.748835
5787  20231006    142959  27488.2  ...  54.583333  0.483775  0.752401
5788  20231006    145959  27487.1  ...  54.166667  0.481683  0.756501
5789  20231006    152959  27478.1  ...  54.583333  0.492507  0.756594

[5 rows x 33 columns]
0.5608856088560885
acc is : 0.5608856088560885
2023-10-06 16:00:18,201:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.476806  0.523194       1  ...  0.939881  -1.0    0.0  1.047589
538     1  0.498920  0.501080       0  ...  0.939919  -1.0    0.0  1.047547
539     1  0.493173  0.506827       0  ...  0.940226  -1.0    0.0  1.047204
540     1  0.492833  0.507167       1  ...  0.938738  -1.0    0.0  1.048862
541     0  0.509529  0.490471       1  ...  0.935136  -1.0    0.0  1.052886

[5 rows x 10 columns]
2023-10-06 16:00:18,212:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.477012  0.522988       1  ...  0.942534  -1.0    0.0  1.038137
46     1  0.499040  0.500960       0  ...  0.942572  -1.0    0.0  1.048038
47     1  0.493175  0.506825       0  ...  0.939423  -1.0    0.0  1.047471
48     1  0.493019  0.506981       1  ...  0.937936  -1.0    0.0  1.053225
49     0  0.509529  0.490471       1  ...  0.935136  -1.0    0.0  1.052886

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.386', 'enterprice': '27541.7', 'countrevence': '0', 'unrealprofit': '-2177.3112453262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27630.9852967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20903 

self.closeSec=1696577399, self.tradeDate='20231006', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27509.4', self.close='27521.5'
127.0.0.1 - - [06/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20904 

self.closeSec=1696577999, self.tradeDate='20231006', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27521.4', self.close='27561.9'
127.0.0.1 - - [06/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20905 

self.closeSec=1696578599, self.tradeDate='20231006', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27561.8', self.close='27601.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20906 

self.closeSec=1696579199, self.tradeDate='20231006', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27601.3', self.close='27627.1'
127.0.0.1 - - [06/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20907 

self.closeSec=1696579799, self.tradeDate='20231006', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27626.8', self.close='27619.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20908 

self.closeSec=1696580399, self.tradeDate='20231006', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27619.5', self.close='27607.6'
127.0.0.1 - - [06/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20906 

self.closeSec=1696577399, self.tradeDate='20231006', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27509.4', self.close='27521.5'
127.0.0.1 - - [06/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20907 

self.closeSec=1696577999, self.tradeDate='20231006', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27521.4', self.close='27561.9'
127.0.0.1 - - [06/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20908 

self.closeSec=1696578599, self.tradeDate='20231006', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27561.8', self.close='27601.4'
127.0.0.1 - - [06/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20909 

self.closeSec=1696579199, self.tradeDate='20231006', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27601.3', self.close='27627.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20910 

self.closeSec=1696579799, self.tradeDate='20231006', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27626.8', self.close='27619.5'
127.0.0.1 - - [06/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20911 

self.closeSec=1696580399, self.tradeDate='20231006', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27619.5', self.close='27607.6'
127.0.0.1 - - [06/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20906 

self.closeSec=1696577399, self.tradeDate='20231006', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27509.4', self.close='27521.5'
127.0.0.1 - - [06/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20907 

self.closeSec=1696577999, self.tradeDate='20231006', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27521.4', self.close='27561.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20908 

self.closeSec=1696578599, self.tradeDate='20231006', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27561.8', self.close='27601.4'
127.0.0.1 - - [06/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20909 

self.closeSec=1696579199, self.tradeDate='20231006', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27601.3', self.close='27627.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20910 

self.closeSec=1696579799, self.tradeDate='20231006', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27626.8', self.close='27619.5'
127.0.0.1 - - [06/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20911 

self.closeSec=1696580399, self.tradeDate='20231006', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27619.5', self.close='27607.6'
127.0.0.1 - - [06/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41812
self.closeSec=1696580399, self.tradeDate='20231006', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27626.1, self.close=27607.6, self.high=27626.2, self.low=27587.1, self.vol=1139.533, self.amt=31454258.9659 
127.0.0.1 - - [06/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-06 16:20:06,267:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231006   155500    155959  ...         0.0        0.0       0
5952  20231006   160000    160459  ...         0.0        0.0       0
5953  20231006   160500    160959  ...         0.0        0.0       0
5954  20231006   161000    161459  ...         0.0        0.0       0
5955  20231006   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 16:20:06,271:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696580399, self.tradeDate='20231006', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27626.1, self.close=27607.6, self.high=27626.2, self.low=27587.1, self.vol=1139.533, self.amt=31454258.9659, ukdf['pct'].iloc[-1]=-0.000673 , ukdf['amount'].iloc[-1]=31454258.9659, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '28357.1535', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27607.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41813
self.closeSec=1696580699, self.tradeDate='20231006', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27607.6, self.close=27639.0, self.high=27646.9, self.low=27607.5, self.vol=930.835, self.amt=25721710.0466 
127.0.0.1 - - [06/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-10-06 16:25:00,814:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231006   160000    160459  ...         0.0        0.0       0
5953  20231006   160500    160959  ...         0.0        0.0       0
5954  20231006   161000    161459  ...         0.0        0.0       0
5955  20231006   161500    161959  ...         0.0        0.0       0
5956  20231006   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 16:25:00,814:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696580699, self.tradeDate='20231006', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27607.6, self.close=27639.0, self.high=27646.9, self.low=27607.5, self.vol=930.835, self.amt=25721710.0466, ukdf['pct'].iloc[-1]=0.001137 , ukdf['amount'].iloc[-1]=25721710.0466, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '29527.095', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27639', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

127.0.0.1 - - [06/Oct/2023 12:00:10] "POST / HTTP/1.1" 200 -
2023-10-06 12:00:10,138:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42991F1696564804577I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696564804975015, 'quantity': '43.706', 'price': '27544.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696564803681, 'updatetime': 1696564804975, 'tradetype': 'usdt', 'selfid': 42991, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696564804975, 'clientorderid': '42991F1696564804577I0L65', 'price': '27544.8', 'quantity': '43.706', 'commission': '1203.8730288', 'commissionasset': 'USDT', 'tradetime': 1696564804975, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696564804975}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Oct/2023 12:00:10] "POST / HTTP/1.1" 200 -
2023-10-06 12:00:10,567:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42992F1696564810106I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696564810523797, 'quantity': '43.642', 'price': '27544.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696564809658, 'updatetime': 1696564810523, 'tradetype': 'usdt', 'selfid': 42992, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696564810523, 'clientorderid': '42992F1696564810106I0L65', 'price': '27544.8', 'quantity': '43.642', 'commission': '1202.1101616', 'commissionasset': 'USDT', 'tradetime': 1696564810523, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696564810523}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-06 12:00:10,689:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42992F1696564810106I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696564810523797, 'quantity': '43.642', 'price': '27544.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696564809658, 'updatetime': 1696564810523, 'tradetype': 'usdt', 'selfid': 42992, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696564810523, 'clientorderid': '42992F1696564810106I0L65', 'price': '27544.8', 'quantity': '43.642', 'commission': '1202.1101616', 'commissionasset': 'USDT', 'tradetime': 1696564810523, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696564810523}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Oct/2023 12:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1200908.0514384, self.flagDict['side']='buy', self.tradeCount=31, self.count=871
self.closeSec=1696579199, self.tradeDate='20231006', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27544.8, self.close=27627.1, self.high=27644.0, self.low=27450.0, self.vol=29146.062, self.amt=802377894.7283 
2023-10-06 16:00:01,558:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696579199, self.tradeDate='20231006', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27544.8, self.close=27627.1, self.high=27644.0, self.low=27450.0, self.vol=29146.062, self.amt=802377894.7283 
2023-10-06 16:00:01,570:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231005   200000    235959  ...  182212.597  5.068501e+09 -0.006160
720  20231006   000000    035959  ...   80767.492  2.217417e+09 -0.003101
721  20231006   040000    075959  ...   22243.134  6.101185e+08 -0.002047
722  20231006   080000    115959  ...   28560.574  7.856097e+08  0.005340
723  20231006   120000    155959  ...   29146.062  8.023779e+08  0.002992

[5 rows x 11 columns]
2023-10-06 16:00:02,340:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231005   200000    235959  1696521599  ...    719  0.468945 -0.620412    -1.0
720  20231006   000000    035959  1696535999  ...    720  0.405187 -0.770041    -1.0
721  20231006   040000    075959  1696550399  ...    721  0.315995 -0.984895    -1.0
722  20231006   080000    115959  1696564799  ...    722  0.935658  0.670697     1.0
723  20231006   120000    155959  1696579199  ...    723  0.892012  0.555175     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.642', 'enterprice': '27544.8', 'countrevence': '0', 'unrealprofit': '3599.94936889716', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27627.28818498', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


