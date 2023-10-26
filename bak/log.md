# 20231026 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47572
self.closeSec=1698308399, self.tradeDate='20231026', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=34552.7, self.close=34602.1, self.high=34611.5, self.low=34538.1, self.vol=1134.647, self.amt=39233897.422 
127.0.0.1 - - [26/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -
2023-10-26 16:20:19,189:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231026   155500    155959  ...         0.0        0.0       0
5952  20231026   160000    160459  ...         0.0        0.0       0
5953  20231026   160500    160959  ...         0.0        0.0       0
5954  20231026   161000    161459  ...         0.0        0.0       0
5955  20231026   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 16:20:19,210:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698308399, self.tradeDate='20231026', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=34552.7, self.close=34602.1, self.high=34611.5, self.low=34538.1, self.vol=1134.647, self.amt=39233897.422, ukdf['pct'].iloc[-1]=0.001296 , ukdf['amount'].iloc[-1]=39233897.422, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-107734.3212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34601.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47573
self.closeSec=1698308699, self.tradeDate='20231026', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=34602.1, self.close=34576.4, self.high=34608.2, self.low=34531.2, self.vol=894.318, self.amt=30916486.9018 
127.0.0.1 - - [26/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-26 16:25:03,119:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231026   160000    160459  ...         0.0        0.0       0
5953  20231026   160500    160959  ...         0.0        0.0       0
5954  20231026   161000    161459  ...         0.0        0.0       0
5955  20231026   161500    161959  ...         0.0        0.0       0
5956  20231026   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 16:25:03,128:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698308699, self.tradeDate='20231026', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=34602.1, self.close=34576.4, self.high=34608.2, self.low=34531.2, self.vol=894.318, self.amt=30916486.9018, ukdf['pct'].iloc[-1]=-0.000743 , ukdf['amount'].iloc[-1]=30916486.9018, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-107353.69038170172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34573.76761322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47570 

self.closeSec=1698307199, self.tradeDate='20231026', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=34665.6, self.close=34663.6, self.high=34691.2, self.low=34617.2 
127.0.0.1 - - [26/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47571 

self.closeSec=1698307499, self.tradeDate='20231026', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=34648.6, self.close=34718.8, self.high=34745.0, self.low=34626.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47572 

self.closeSec=1698307799, self.tradeDate='20231026', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=34709.9, self.close=34651.1, self.high=34741.7, self.low=34646.0 
127.0.0.1 - - [26/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47573 

self.closeSec=1698308099, self.tradeDate='20231026', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=34648.0, self.close=34557.3, self.high=34657.7, self.low=34500.6 
127.0.0.1 - - [26/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47574 

self.closeSec=1698308399, self.tradeDate='20231026', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=34552.7, self.close=34602.1, self.high=34611.5, self.low=34538.1 
127.0.0.1 - - [26/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47575 

self.closeSec=1698308699, self.tradeDate='20231026', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=34602.1, self.close=34576.4, self.high=34608.2, self.low=34531.2 
127.0.0.1 - - [26/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-26 16:00:20,100:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231026    132959  34699.8  ...  57.916667  0.564363  0.338572
5786  20231026    135959  34620.1  ...  57.500000  0.553784  0.354032
5787  20231026    142959  34518.7  ...  57.083333  0.550471  0.373281
5788  20231026    145959  34488.1  ...  57.083333  0.561397  0.384726
5789  20231026    152959  34613.8  ...  57.083333  0.575161  0.384566

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-10-26 16:00:20,179:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.508516  0.491484       0  ...  1.079759   1.0    0.0  1.286335
538     1  0.497146  0.502854       0  ...  1.078795   1.0    0.0  1.285187
539     0  0.508630  0.491370       1  ...  1.082727   1.0    0.0  1.289871
540     0  0.551778  0.448222       1  ...  1.087864   1.0    0.0  1.295990
541     0  0.569829  0.430171       0  ...  1.084288   1.0    0.0  1.291731

[5 rows x 10 columns]
2023-10-26 16:00:20,194:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508508  0.491492       0  ...  1.079759   1.0    0.0  1.286445
46     1  0.497216  0.502784       0  ...  1.078795   1.0    0.0  1.284737
47     0  0.509585  0.490415       1  ...  1.082727   1.0    0.0  1.289804
48     0  0.551668  0.448332       1  ...  1.087864   1.0    0.0  1.296652
49     0  0.569829  0.430171       0  ...  1.084288   1.0    0.0  1.291731

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '20.978', 'enterprice': '33828.2', 'countrevence': '0', 'unrealprofit': '17019.4514', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34639.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23783 

self.closeSec=1698305399, self.tradeDate='20231026', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='34671', self.close='34778.9'
127.0.0.1 - - [26/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23784 

self.closeSec=1698305999, self.tradeDate='20231026', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='34778.9', self.close='34730.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23785 

self.closeSec=1698306599, self.tradeDate='20231026', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='34730.1', self.close='34673.7'
127.0.0.1 - - [26/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23786 

self.closeSec=1698307199, self.tradeDate='20231026', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='34673.8', self.close='34663.6'
127.0.0.1 - - [26/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23787 

self.closeSec=1698307799, self.tradeDate='20231026', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='34648.6', self.close='34648'
127.0.0.1 - - [26/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23788 

self.closeSec=1698308399, self.tradeDate='20231026', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='34648', self.close='34602.1'
127.0.0.1 - - [26/Oct/2023 16:20:13] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [26/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23786 

self.closeSec=1698305399, self.tradeDate='20231026', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='34671', self.close='34778.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23787 

self.closeSec=1698305999, self.tradeDate='20231026', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='34778.9', self.close='34730.1'
127.0.0.1 - - [26/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23788 

self.closeSec=1698306599, self.tradeDate='20231026', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='34730.1', self.close='34673.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23789 

self.closeSec=1698307199, self.tradeDate='20231026', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='34673.8', self.close='34663.6'
127.0.0.1 - - [26/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23790 

self.closeSec=1698307799, self.tradeDate='20231026', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='34648.6', self.close='34648'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23791 

self.closeSec=1698308399, self.tradeDate='20231026', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='34648', self.close='34602.1'
127.0.0.1 - - [26/Oct/2023 16:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23786 

self.closeSec=1698305399, self.tradeDate='20231026', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='34671', self.close='34778.9'
127.0.0.1 - - [26/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [26/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23787 

self.closeSec=1698305999, self.tradeDate='20231026', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='34778.9', self.close='34730.1'

--handleKline--: 127.0.0.1 - - [26/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23788 

self.closeSec=1698306599, self.tradeDate='20231026', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='34730.1', self.close='34673.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23789 

self.closeSec=1698307199, self.tradeDate='20231026', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='34673.8', self.close='34663.6'
127.0.0.1 - - [26/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23790 

self.closeSec=1698307799, self.tradeDate='20231026', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='34648.6', self.close='34648'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23791 

self.closeSec=1698308399, self.tradeDate='20231026', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='34648', self.close='34602.1'
127.0.0.1 - - [26/Oct/2023 16:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47572
self.closeSec=1698308399, self.tradeDate='20231026', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=34552.7, self.close=34602.1, self.high=34611.5, self.low=34538.1, self.vol=1134.647, self.amt=39233897.422 
127.0.0.1 - - [26/Oct/2023 16:20:11] "POST / HTTP/1.1" 200 -
2023-10-26 16:20:19,170:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231026   155500    155959  ...         0.0        0.0       0
5952  20231026   160000    160459  ...         0.0        0.0       0
5953  20231026   160500    160959  ...         0.0        0.0       0
5954  20231026   161000    161459  ...         0.0        0.0       0
5955  20231026   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 16:20:19,189:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698308399, self.tradeDate='20231026', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=34552.7, self.close=34602.1, self.high=34611.5, self.low=34538.1, self.vol=1134.647, self.amt=39233897.422, ukdf['pct'].iloc[-1]=0.001296 , ukdf['amount'].iloc[-1]=39233897.422, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '288106.4511', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34601.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47573
self.closeSec=1698308699, self.tradeDate='20231026', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=34602.1, self.close=34576.4, self.high=34608.2, self.low=34531.2, self.vol=894.318, self.amt=30916486.9018 
127.0.0.1 - - [26/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-26 16:25:03,116:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231026   160000    160459  ...         0.0        0.0       0
5953  20231026   160500    160959  ...         0.0        0.0       0
5954  20231026   161000    161459  ...         0.0        0.0       0
5955  20231026   161500    161959  ...         0.0        0.0       0
5956  20231026   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 16:25:03,126:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698308699, self.tradeDate='20231026', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=34602.1, self.close=34576.4, self.high=34608.2, self.low=34531.2, self.vol=894.318, self.amt=30916486.9018, ukdf['pct'].iloc[-1]=-0.000743 , ukdf['amount'].iloc[-1]=30916486.9018, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '287091.29892260402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34573.76761322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231026   040000    075959  1698278399  ...    721  0.998519  0.124421     NaN
722  20231026   080000    115959  1698292799  ...    722  0.940070  0.020946     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '216959.1255', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34784.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [26/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=991
self.closeSec=1698307199, self.tradeDate='20231026', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=34783.4, self.close=34663.6, self.high=34809.4, self.low=34401.7, self.vol=42890.458, self.amt=1484707469.45132 
2023-10-26 16:00:01,550:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698307199, self.tradeDate='20231026', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=34783.4, self.close=34663.6, self.high=34809.4, self.low=34401.7, self.vol=42890.458, self.amt=1484707469.45132 
2023-10-26 16:00:01,588:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231025   200000    235959  ...  133242.385  4.610593e+09  0.018795
720  20231026   000000    035959  ...   96954.612  3.363552e+09 -0.003212
721  20231026   040000    075959  ...   49659.588  1.716450e+09 -0.006871
722  20231026   080000    115959  ...   35395.767  1.226934e+09  0.008571
723  20231026   120000    155959  ...   42890.458  1.484707e+09 -0.003444

[5 rows x 11 columns]
2023-10-26 16:00:02,500:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231025   200000    235959  1698249599  ...    719  1.072746  0.263102     NaN
720  20231026   000000    035959  1698263999  ...    720  1.033059  0.189144     NaN
721  20231026   040000    075959  1698278399  ...    721  0.998519  0.124421     NaN
722  20231026   080000    115959  1698292799  ...    722  0.940070  0.020946     NaN
723  20231026   120000    155959  1698307199  ...    723  0.880106 -0.082705     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '211376.95396110357', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34649.73780037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


