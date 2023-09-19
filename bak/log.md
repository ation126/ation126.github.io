# 20230919 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36916
self.closeSec=1695111599, self.tradeDate='20230919', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26889.6, self.close=26882.0, self.high=26890.0, self.low=26870.2, self.vol=860.697, self.amt=23135098.3922 
127.0.0.1 - - [19/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-19 16:20:05,983:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230919   155500    155959  ...         0.0        0.0       0
5952  20230919   160000    160459  ...         0.0        0.0       0
5953  20230919   160500    160959  ...         0.0        0.0       0
5954  20230919   161000    161459  ...         0.0        0.0       0
5955  20230919   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-19 16:20:05,990:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695111599, self.tradeDate='20230919', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26889.6, self.close=26882.0, self.high=26890.0, self.low=26870.2, self.vol=860.697, self.amt=23135098.3922, ukdf['pct'].iloc[-1]=-0.000283 , ukdf['amount'].iloc[-1]=23135098.3922, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-236.742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26881.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36917
self.closeSec=1695111899, self.tradeDate='20230919', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26882.0, self.close=26910.6, self.high=26920.0, self.low=26879.2, self.vol=1656.493, self.amt=44565085.0321 
2023-09-19 16:25:00,788:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230919   160000    160459  ...         0.0        0.0       0
5953  20230919   160500    160959  ...         0.0        0.0       0
5954  20230919   161000    161459  ...         0.0        0.0       0
5955  20230919   161500    161959  ...         0.0        0.0       0
5956  20230919   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-19 16:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695111899, self.tradeDate='20230919', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26882.0, self.close=26910.6, self.high=26920.0, self.low=26879.2, self.vol=1656.493, self.amt=44565085.0321, ukdf['pct'].iloc[-1]=0.001064 , ukdf['amount'].iloc[-1]=44565085.0321, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-703.77596824854', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26915.43683529', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36914 

self.closeSec=1695110399, self.tradeDate='20230919', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26852.7, self.close=26836.0, self.high=26852.8, self.low=26829.0 
127.0.0.1 - - [19/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36915 

self.closeSec=1695110699, self.tradeDate='20230919', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26836.0, self.close=26856.8, self.high=26859.9, self.low=26834.3 
127.0.0.1 - - [19/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36916 

self.closeSec=1695110999, self.tradeDate='20230919', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26856.3, self.close=26869.0, self.high=26879.7, self.low=26856.2 
127.0.0.1 - - [19/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36917 

self.closeSec=1695111299, self.tradeDate='20230919', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26866.9, self.close=26889.6, self.high=26889.7, self.low=26862.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36918 

self.closeSec=1695111599, self.tradeDate='20230919', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26889.6, self.close=26882.0, self.high=26890.0, self.low=26870.2 
127.0.0.1 - - [19/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36919 

self.closeSec=1695111899, self.tradeDate='20230919', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26882.0, self.close=26910.6, self.high=26920.0, self.low=26879.2 
127.0.0.1 - - [19/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-19 16:00:17,717:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230919    132959  26848.1  ...  52.500000  0.523223  0.645496
5786  20230919    135959  26829.7  ...  52.083333  0.511489  0.654563
5787  20230919    142959  26782.9  ...  51.666667  0.506426  0.664756
5788  20230919    145959  26762.5  ...  51.666667  0.519371  0.669654
5789  20230919    152959  26816.9  ...  52.083333  0.525210  0.672105

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-09-19 16:00:17,772:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.504547  0.495453       0  ...  0.962604  -1.0    0.0  1.016664
538     1  0.496202  0.503798       0  ...  0.963337  -1.0    0.0  1.015890
539     0  0.501883  0.498117       1  ...  0.961379  -1.0    0.0  1.017955
540     0  0.522847  0.477153       1  ...  0.960483  -1.0    0.0  1.018904
541     0  0.514677  0.485323       0  ...  0.960694  -1.0    0.0  1.018680

[5 rows x 10 columns]
2023-09-19 16:00:17,783:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504377  0.495623       0  ...  0.962604  -1.0    0.0  1.017924
46     1  0.496229  0.503771       0  ...  0.963337  -1.0    0.0  1.022172
47     0  0.501547  0.498453       1  ...  0.961379  -1.0    0.0  1.021993
48     0  0.522565  0.477435       1  ...  0.960483  -1.0    0.0  1.022155
49     0  0.514677  0.485323       0  ...  0.960694  -1.0    0.0  1.018680

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.796', 'enterprice': '26728.8', 'countrevence': '0', 'unrealprofit': '-2923.4436', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26837.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [19/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18455 

self.closeSec=1695108599, self.tradeDate='20230919', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26809.9', self.close='26841.9'
127.0.0.1 - - [19/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18456 

self.closeSec=1695109199, self.tradeDate='20230919', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26841.9', self.close='26842.4'

--handleKline--: 127.0.0.1 - - [19/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18457 

self.closeSec=1695109799, self.tradeDate='20230919', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26842.4', self.close='26846.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18458 

self.closeSec=1695110399, self.tradeDate='20230919', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26846.3', self.close='26836.1'
127.0.0.1 - - [19/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18459 

self.closeSec=1695110999, self.tradeDate='20230919', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26836', self.close='26869'
127.0.0.1 - - [19/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18460 

self.closeSec=1695111599, self.tradeDate='20230919', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26866.9', self.close='26882'
127.0.0.1 - - [19/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [19/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18458 

self.closeSec=1695108599, self.tradeDate='20230919', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26809.9', self.close='26841.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18459 

self.closeSec=1695109199, self.tradeDate='20230919', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26841.9', self.close='26842.4'
127.0.0.1 - - [19/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18460 

self.closeSec=1695109799, self.tradeDate='20230919', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26842.4', self.close='26846.2'
127.0.0.1 - - [19/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18461 

self.closeSec=1695110399, self.tradeDate='20230919', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26846.3', self.close='26836.1'
127.0.0.1 - - [19/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18462 

self.closeSec=1695110999, self.tradeDate='20230919', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26836', self.close='26869'
127.0.0.1 - - [19/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18463 

self.closeSec=1695111599, self.tradeDate='20230919', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26866.9', self.close='26882'
127.0.0.1 - - [19/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18458 

self.closeSec=1695108599, self.tradeDate='20230919', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26809.9', self.close='26841.9'
127.0.0.1 - - [19/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18459 

self.closeSec=1695109199, self.tradeDate='20230919', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26841.9', self.close='26842.4'
127.0.0.1 - - [19/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18460 

self.closeSec=1695109799, self.tradeDate='20230919', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26842.4', self.close='26846.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18461 

self.closeSec=1695110399, self.tradeDate='20230919', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26846.3', self.close='26836.1'
127.0.0.1 - - [19/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18462 

self.closeSec=1695110999, self.tradeDate='20230919', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26836', self.close='26869'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18463 

self.closeSec=1695111599, self.tradeDate='20230919', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26866.9', self.close='26882'
127.0.0.1 - - [19/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36916
self.closeSec=1695111599, self.tradeDate='20230919', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26889.6, self.close=26882.0, self.high=26890.0, self.low=26870.2, self.vol=860.697, self.amt=23135098.3922 
127.0.0.1 - - [19/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-19 16:20:05,981:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230919   155500    155959  ...         0.0        0.0       0
5952  20230919   160000    160459  ...         0.0        0.0       0
5953  20230919   160500    160959  ...         0.0        0.0       0
5954  20230919   161000    161459  ...         0.0        0.0       0
5955  20230919   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-19 16:20:05,985:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695111599, self.tradeDate='20230919', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26889.6, self.close=26882.0, self.high=26890.0, self.low=26870.2, self.vol=860.697, self.amt=23135098.3922, ukdf['pct'].iloc[-1]=-0.000283 , ukdf['amount'].iloc[-1]=23135098.3922, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '1407.6439', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26881.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [19/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36917
self.closeSec=1695111899, self.tradeDate='20230919', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26882.0, self.close=26910.6, self.high=26920.0, self.low=26879.2, self.vol=1656.493, self.amt=44565085.0321 
2023-09-19 16:25:00,788:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230919   160000    160459  ...         0.0        0.0       0
5953  20230919   160500    160959  ...         0.0        0.0       0
5954  20230919   161000    161459  ...         0.0        0.0       0
5955  20230919   161500    161959  ...         0.0        0.0       0
5956  20230919   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-19 16:25:00,788:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695111899, self.tradeDate='20230919', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26882.0, self.close=26910.6, self.high=26920.0, self.low=26879.2, self.vol=1656.493, self.amt=44565085.0321, ukdf['pct'].iloc[-1]=0.001064 , ukdf['amount'].iloc[-1]=44565085.0321, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2653.23549950589', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26915.43683529', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230919   040000    075959  1695081599  ...    721  0.718198  2.142217     1.0
722  20230919   080000    115959  1695095999  ...    722  0.701469  2.075714     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-22856.19087457926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26801.35981502', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [19/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=769
self.closeSec=1695110399, self.tradeDate='20230919', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26805.1, self.close=26836.1, self.high=26860.0, self.low=26740.0, self.vol=18919.447, self.amt=507323801.9865 
2023-09-19 16:00:01,543:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695110399, self.tradeDate='20230919', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26805.1, self.close=26836.1, self.high=26860.0, self.low=26740.0, self.vol=18919.447, self.amt=507323801.9865 
2023-09-19 16:00:01,555:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230918   200000    235959  ...   99944.871  2.725819e+09  0.002796
720  20230919   000000    035959  ...  131939.186  3.544338e+09 -0.016714
721  20230919   040000    075959  ...   29198.239  7.819548e+08 -0.001989
722  20230919   080000    115959  ...   28690.386  7.669091e+08  0.002064
723  20230919   120000    155959  ...   18919.447  5.073238e+08  0.001156

[5 rows x 11 columns]
2023-09-19 16:00:02,328:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230918   200000    235959  1695052799  ...    719  0.582874  1.495848     1.0
720  20230919   000000    035959  1695067199  ...    720  0.775069  2.400372     1.0
721  20230919   040000    075959  1695081599  ...    721  0.718198  2.142217     1.0
722  20230919   080000    115959  1695095999  ...    722  0.701469  2.075714     1.0
723  20230919   120000    155959  1695110399  ...    723  0.641258  1.818063     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-21091.8411', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26836.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


