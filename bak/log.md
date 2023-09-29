# 20230929 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39796
self.closeSec=1695975599, self.tradeDate='20230929', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27126.5, self.close=27097.6, self.high=27126.6, self.low=27091.1, self.vol=1261.702, self.amt=34200799.2065 
127.0.0.1 - - [29/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-29 16:20:06,233:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230929   155500    155959  ...         0.0        0.0       0
5952  20230929   160000    160459  ...         0.0        0.0       0
5953  20230929   160500    160959  ...         0.0        0.0       0
5954  20230929   161000    161459  ...         0.0        0.0       0
5955  20230929   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 16:20:06,238:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695975599, self.tradeDate='20230929', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27126.5, self.close=27097.6, self.high=27126.6, self.low=27091.1, self.vol=1261.702, self.amt=34200799.2065, ukdf['pct'].iloc[-1]=-0.001065 , ukdf['amount'].iloc[-1]=34200799.2065, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3152.8464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27091.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39797
self.closeSec=1695975899, self.tradeDate='20230929', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27097.5, self.close=27084.4, self.high=27097.6, self.low=27070.9, self.vol=1735.527, self.amt=47000873.0169 
127.0.0.1 - - [29/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-29 16:25:00,843:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230929   160000    160459  ...         0.0        0.0       0
5953  20230929   160500    160959  ...         0.0        0.0       0
5954  20230929   161000    161459  ...         0.0        0.0       0
5955  20230929   161500    161959  ...         0.0        0.0       0
5956  20230929   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 16:25:00,843:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695975899, self.tradeDate='20230929', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27097.5, self.close=27084.4, self.high=27097.6, self.low=27070.9, self.vol=1735.527, self.amt=47000873.0169, ukdf['pct'].iloc[-1]=-0.000487 , ukdf['amount'].iloc[-1]=47000873.0169, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3048.4014', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27083.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [29/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39794 

self.closeSec=1695974399, self.tradeDate='20230929', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27173.1, self.close=27169.1, self.high=27199.0, self.low=27143.0 
127.0.0.1 - - [29/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39795 

self.closeSec=1695974699, self.tradeDate='20230929', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27167.9, self.close=27118.7, self.high=27168.0, self.low=27116.1 
127.0.0.1 - - [29/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39796 

self.closeSec=1695974999, self.tradeDate='20230929', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27121.0, self.close=27122.7, self.high=27139.5, self.low=27102.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39797 

self.closeSec=1695975299, self.tradeDate='20230929', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27122.8, self.close=27126.5, self.high=27145.2, self.low=27117.6 
127.0.0.1 - - [29/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39798 

self.closeSec=1695975599, self.tradeDate='20230929', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27126.5, self.close=27097.6, self.high=27126.6, self.low=27091.1 
127.0.0.1 - - [29/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39799 

self.closeSec=1695975899, self.tradeDate='20230929', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27097.5, self.close=27084.4, self.high=27097.6, self.low=27070.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-29 16:00:22,158:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230929    132959  26962.8  ...  50.833333  0.558750  0.334463
5786  20230929    135959  26941.4  ...  51.250000  0.562965  0.337399
5787  20230929    142959  26964.8  ...  50.833333  0.557897  0.342448
5788  20230929    145959  26942.9  ...  51.250000  0.578698  0.338296
5789  20230929    152959  27060.6  ...  50.833333  0.572440  0.336438

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2023-09-29 16:00:22,241:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485109  0.514891       1  ...  0.959787  -1.0    0.0  1.019467
538     0  0.501215  0.498785       0  ...  0.960567  -1.0    0.0  1.018639
539     1  0.483610  0.516390       1  ...  0.956370  -1.0    0.0  1.023089
540     0  0.534882  0.465118       0  ...  0.957318  -1.0    0.0  1.022076
541     1  0.489539  0.510461       1  ...  0.952530  -1.0    0.0  1.027187

[5 rows x 10 columns]
2023-09-29 16:00:22,257:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484708  0.515292       1  ...  0.959787  -1.0    0.0  1.018208
46     0  0.500981  0.499019       0  ...  0.960567  -1.0    0.0  1.017908
47     1  0.483164  0.516836       1  ...  0.956370  -1.0    0.0  1.020612
48     0  0.534569  0.465431       0  ...  0.957318  -1.0    0.0  1.021226
49     1  0.489539  0.510461       1  ...  0.952530  -1.0    0.0  1.027187

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.689', 'enterprice': '27080', 'countrevence': '0', 'unrealprofit': '-2060.92538466702', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27160.22598718', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19895 

self.closeSec=1695972599, self.tradeDate='20230929', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27035.9', self.close='27033.9'
127.0.0.1 - - [29/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19896 

self.closeSec=1695973199, self.tradeDate='20230929', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27033.9', self.close='27215.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19897 

self.closeSec=1695973799, self.tradeDate='20230929', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27217.8', self.close='27157.3'
127.0.0.1 - - [29/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19898 

self.closeSec=1695974399, self.tradeDate='20230929', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27157.3', self.close='27169.1'
127.0.0.1 - - [29/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19899 

self.closeSec=1695974999, self.tradeDate='20230929', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27167.9', self.close='27122.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19900 

self.closeSec=1695975599, self.tradeDate='20230929', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27122.8', self.close='27097.6'
127.0.0.1 - - [29/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [29/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19898 

self.closeSec=1695972599, self.tradeDate='20230929', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27035.9', self.close='27033.9'
127.0.0.1 - - [29/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19899 

self.closeSec=1695973199, self.tradeDate='20230929', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27033.9', self.close='27215.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19900 

self.closeSec=1695973799, self.tradeDate='20230929', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27217.8', self.close='27157.3'
127.0.0.1 - - [29/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19901 

self.closeSec=1695974399, self.tradeDate='20230929', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27157.3', self.close='27169.1'
127.0.0.1 - - [29/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19902 

self.closeSec=1695974999, self.tradeDate='20230929', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27167.9', self.close='27122.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19903 

self.closeSec=1695975599, self.tradeDate='20230929', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27122.8', self.close='27097.6'
127.0.0.1 - - [29/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [29/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19898 

self.closeSec=1695972599, self.tradeDate='20230929', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27035.9', self.close='27033.9'
127.0.0.1 - - [29/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19899 

self.closeSec=1695973199, self.tradeDate='20230929', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27033.9', self.close='27215.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19900 

self.closeSec=1695973799, self.tradeDate='20230929', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27217.8', self.close='27157.3'
127.0.0.1 - - [29/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19901 

self.closeSec=1695974399, self.tradeDate='20230929', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27157.3', self.close='27169.1'
127.0.0.1 - - [29/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19902 

self.closeSec=1695974999, self.tradeDate='20230929', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27167.9', self.close='27122.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19903 

self.closeSec=1695975599, self.tradeDate='20230929', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27122.8', self.close='27097.6'
127.0.0.1 - - [29/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39796
self.closeSec=1695975599, self.tradeDate='20230929', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27126.5, self.close=27097.6, self.high=27126.6, self.low=27091.1, self.vol=1261.702, self.amt=34200799.2065 
127.0.0.1 - - [29/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-29 16:20:06,234:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230929   155500    155959  ...         0.0        0.0       0
5952  20230929   160000    160459  ...         0.0        0.0       0
5953  20230929   160500    160959  ...         0.0        0.0       0
5954  20230929   161000    161459  ...         0.0        0.0       0
5955  20230929   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 16:20:06,238:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695975599, self.tradeDate='20230929', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27126.5, self.close=27097.6, self.high=27126.6, self.low=27091.1, self.vol=1261.702, self.amt=34200799.2065, ukdf['pct'].iloc[-1]=-0.001065 , ukdf['amount'].iloc[-1]=34200799.2065, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '9184.9693', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27091.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [29/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39797
self.closeSec=1695975899, self.tradeDate='20230929', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27097.5, self.close=27084.4, self.high=27097.6, self.low=27070.9, self.vol=1735.527, self.amt=47000873.0169 
2023-09-29 16:25:00,853:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230929   160000    160459  ...         0.0        0.0       0
5953  20230929   160500    160959  ...         0.0        0.0       0
5954  20230929   161000    161459  ...         0.0        0.0       0
5955  20230929   161500    161959  ...         0.0        0.0       0
5956  20230929   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 16:25:00,854:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695975899, self.tradeDate='20230929', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27097.5, self.close=27084.4, self.high=27097.6, self.low=27070.9, self.vol=1735.527, self.amt=47000873.0169, ukdf['pct'].iloc[-1]=-0.000487 , ukdf['amount'].iloc[-1]=47000873.0169, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8906.4118', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27083.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

720  20230929   000000    035959  ...  134967.954  3.657050e+09  0.002598
721  20230929   040000    075959  ...   38159.338  1.031164e+09 -0.002831
722  20230929   080000    115959  ...   42838.866  1.155957e+09 -0.002488
723  20230929   120000    155959  ...   39116.334  1.058424e+09  0.008332

[5 rows x 11 columns]
2023-09-29 16:00:02,498:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230928   200000    235959  1695916799  ...    719  0.241155 -0.884063    -1.0
720  20230929   000000    035959  1695931199  ...    720  0.772181  0.387749     NaN
721  20230929   040000    075959  1695945599  ...    721  0.776522  0.387464     NaN
722  20230929   080000    115959  1695959999  ...    722  0.846240  0.544805     NaN
723  20230929   120000    155959  1695974399  ...    723  0.948493  0.777177     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-51725.4396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27168', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-51725.4396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27168', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-09-29 16:00:09,401:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1278097.7934802', 'total': '1278097.7934802', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-09-29 16:00:09,918:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-09-29 16:00:09,918:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 46.901, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42972F1695974409914I0L65'}
2023-09-29 16:00:09,948:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:9291600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230929, closeTime:155959, close:27169.1, sign:1, total:1278097.7934802, side:buy  
127.0.0.1 - - [29/Sep/2023 16:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 16:00:09] "POST / HTTP/1.1" 200 -
2023-09-29 16:00:09,954:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42971F1695974404322I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695974404728748, 'quantity': '50.756', 'price': '27168', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1695974403393, 'updatetime': 1695974404728, 'tradetype': 'usdt', 'selfid': 42971, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695974404728, 'clientorderid': '42971F1695974404322I0L65', 'price': '27168', 'quantity': '50.756', 'commission': '1378.939008', 'commissionasset': 'USDT', 'tradetime': 1695974404728, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695974404728}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-29 16:00:09,955:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42971F1695974404322I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695974404728748, 'quantity': '50.756', 'price': '27168', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1695974403393, 'updatetime': 1695974404728, 'tradetype': 'usdt', 'selfid': 42971, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695974404728, 'clientorderid': '42971F1695974404322I0L65', 'price': '27168', 'quantity': '50.756', 'commission': '1378.939008', 'commissionasset': 'USDT', 'tradetime': 1695974404728, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695974404728}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-29 16:00:10,368:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42972F1695974409914I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695974410324922, 'quantity': '46.901', 'price': '27157.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1695974409417, 'updatetime': 1695974410324, 'tradetype': 'usdt', 'selfid': 42972, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695974410324, 'clientorderid': '42972F1695974409914I0L65', 'price': '27157.6', 'quantity': '46.901', 'commission': '1273.7185976', 'commissionasset': 'USDT', 'tradetime': 1695974410324, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695974410324}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Sep/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-09-29 16:00:10,554:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42972F1695974409914I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695974410324922, 'quantity': '46.901', 'price': '27157.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1695974409417, 'updatetime': 1695974410324, 'tradetype': 'usdt', 'selfid': 42972, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695974410324, 'clientorderid': '42972F1695974409914I0L65', 'price': '27157.6', 'quantity': '46.901', 'commission': '1273.7185976', 'commissionasset': 'USDT', 'tradetime': 1695974410324, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695974410324}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Sep/2023 16:00:10] "POST / HTTP/1.1" 200 -


