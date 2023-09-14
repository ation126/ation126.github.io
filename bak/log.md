# 20230914 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35476
self.closeSec=1694679599, self.tradeDate='20230914', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26328.5, self.close=26317.7, self.high=26330.5, self.low=26313.6, self.vol=443.712, self.amt=11678967.983 
127.0.0.1 - - [14/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-14 16:20:06,597:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230914   155500    155959  ...         0.0        0.0       0
5952  20230914   160000    160459  ...         0.0        0.0       0
5953  20230914   160500    160959  ...         0.0        0.0       0
5954  20230914   161000    161459  ...         0.0        0.0       0
5955  20230914   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 16:20:06,601:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694679599, self.tradeDate='20230914', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26328.5, self.close=26317.7, self.high=26330.5, self.low=26313.6, self.vol=443.712, self.amt=11678967.983, ukdf['pct'].iloc[-1]=-0.00041 , ukdf['amount'].iloc[-1]=11678967.983, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7586.32186818792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26320.14042308', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35477
self.closeSec=1694679899, self.tradeDate='20230914', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26317.8, self.close=26309.5, self.high=26326.0, self.low=26301.7, self.vol=658.756, self.amt=17333460.6963 
2023-09-14 16:25:00,779:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230914   160000    160459  ...         0.0        0.0       0
5953  20230914   160500    160959  ...         0.0        0.0       0
5954  20230914   161000    161459  ...         0.0        0.0       0
5955  20230914   161500    161959  ...         0.0        0.0       0
5956  20230914   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 16:25:00,779:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694679899, self.tradeDate='20230914', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26317.8, self.close=26309.5, self.high=26326.0, self.low=26301.7, self.vol=658.756, self.amt=17333460.6963, ukdf['pct'].iloc[-1]=-0.000312 , ukdf['amount'].iloc[-1]=17333460.6963, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7734.5004', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26309.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35474 

self.closeSec=1694678399, self.tradeDate='20230914', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26351.2, self.close=26328.3, self.high=26355.0, self.low=26319.8 
127.0.0.1 - - [14/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35475 

self.closeSec=1694678699, self.tradeDate='20230914', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26332.2, self.close=26346.5, self.high=26346.5, self.low=26318.9 
127.0.0.1 - - [14/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35476 

self.closeSec=1694678999, self.tradeDate='20230914', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26346.5, self.close=26329.2, self.high=26346.5, self.low=26322.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35477 

self.closeSec=1694679299, self.tradeDate='20230914', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26329.2, self.close=26328.5, self.high=26331.0, self.low=26316.8 
127.0.0.1 - - [14/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35478 

self.closeSec=1694679599, self.tradeDate='20230914', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26328.5, self.close=26317.7, self.high=26330.5, self.low=26313.6 
127.0.0.1 - - [14/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [14/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35479 

self.closeSec=1694679899, self.tradeDate='20230914', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26317.8, self.close=26309.5, self.high=26326.0, self.low=26301.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-14 16:00:18,353:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230914    132959  26201.6  ...  49.583333  0.522917  0.421253
5786  20230914    135959  26167.4  ...  50.000000  0.525376  0.437887
5787  20230914    142959  26182.0  ...  50.000000  0.536561  0.444966
5788  20230914    145959  26249.0  ...  50.000000  0.541790  0.447563
5789  20230914    152959  26280.8  ...  50.000000  0.537065  0.453051

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-09-14 16:00:18,416:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.479823  0.520177       1  ...  0.966349  -1.0    0.0  1.012452
538     1  0.495289  0.504711       1  ...  0.963876  -1.0    0.0  1.015043
539     0  0.512558  0.487442       1  ...  0.962708  -1.0    0.0  1.016272
540     0  0.506369  0.493631       0  ...  0.963599  -1.0    0.0  1.015333
541     1  0.495097  0.504903       1  ...  0.960820  -1.0    0.0  1.018260

[5 rows x 10 columns]
2023-09-14 16:00:18,428:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.479771  0.520229       1  ...  0.966349  -1.0    0.0  1.012855
46     1  0.494981  0.505019       1  ...  0.963876  -1.0    0.0  1.014344
47     0  0.513094  0.486906       1  ...  0.962708  -1.0    0.0  1.016433
48     0  0.506675  0.493325       0  ...  0.963599  -1.0    0.0  1.015714
49     1  0.495097  0.504903       1  ...  0.960820  -1.0    0.0  1.018260

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.754', 'enterprice': '26169.9', 'countrevence': '0', 'unrealprofit': '-4274.1177790314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26323.9000641', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17735 

self.closeSec=1694676599, self.tradeDate='20230914', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26263.8', self.close='26256.5'
127.0.0.1 - - [14/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17736 

self.closeSec=1694677199, self.tradeDate='20230914', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26256.5', self.close='26299'
127.0.0.1 - - [14/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17737 

self.closeSec=1694677799, self.tradeDate='20230914', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26299.1', self.close='26355'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17738 

self.closeSec=1694678399, self.tradeDate='20230914', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26355', self.close='26332.3'
127.0.0.1 - - [14/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17739 

self.closeSec=1694678999, self.tradeDate='20230914', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26332.2', self.close='26329.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17740 

self.closeSec=1694679599, self.tradeDate='20230914', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26329.2', self.close='26317.7'
127.0.0.1 - - [14/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17738 

self.closeSec=1694676599, self.tradeDate='20230914', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26263.8', self.close='26256.5'
127.0.0.1 - - [14/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17739 

self.closeSec=1694677199, self.tradeDate='20230914', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26256.5', self.close='26299'
127.0.0.1 - - [14/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17740 

self.closeSec=1694677799, self.tradeDate='20230914', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26299.1', self.close='26355'
127.0.0.1 - - [14/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17741 

self.closeSec=1694678399, self.tradeDate='20230914', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26355', self.close='26332.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17742 

self.closeSec=1694678999, self.tradeDate='20230914', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26332.2', self.close='26329.2'
127.0.0.1 - - [14/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17743 

self.closeSec=1694679599, self.tradeDate='20230914', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26329.2', self.close='26317.7'
127.0.0.1 - - [14/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17738 

self.closeSec=1694676599, self.tradeDate='20230914', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26263.8', self.close='26256.5'
127.0.0.1 - - [14/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17739 

self.closeSec=1694677199, self.tradeDate='20230914', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26256.5', self.close='26299'
127.0.0.1 - - [14/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17740 

self.closeSec=1694677799, self.tradeDate='20230914', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26299.1', self.close='26355'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17741 

self.closeSec=1694678399, self.tradeDate='20230914', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26355', self.close='26332.3'
127.0.0.1 - - [14/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17742 

self.closeSec=1694678999, self.tradeDate='20230914', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26332.2', self.close='26329.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17743 

self.closeSec=1694679599, self.tradeDate='20230914', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26329.2', self.close='26317.7'
127.0.0.1 - - [14/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35476
self.closeSec=1694679599, self.tradeDate='20230914', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26328.5, self.close=26317.7, self.high=26330.5, self.low=26313.6, self.vol=443.712, self.amt=11678967.983 
127.0.0.1 - - [14/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-14 16:20:06,591:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230914   155500    155959  ...         0.0        0.0       0
5952  20230914   160000    160459  ...         0.0        0.0       0
5953  20230914   160500    160959  ...         0.0        0.0       0
5954  20230914   161000    161459  ...         0.0        0.0       0
5955  20230914   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 16:20:06,599:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694679599, self.tradeDate='20230914', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26328.5, self.close=26317.7, self.high=26330.5, self.low=26313.6, self.vol=443.712, self.amt=11678967.983, ukdf['pct'].iloc[-1]=-0.00041 , ukdf['amount'].iloc[-1]=11678967.983, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-19456.66854638572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26320.14042308', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35477
self.closeSec=1694679899, self.tradeDate='20230914', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26317.8, self.close=26309.5, self.high=26326.0, self.low=26301.7, self.vol=658.756, self.amt=17333460.6963 
127.0.0.1 - - [14/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-14 16:25:00,784:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230914   160000    160459  ...         0.0        0.0       0
5953  20230914   160500    160959  ...         0.0        0.0       0
5954  20230914   161000    161459  ...         0.0        0.0       0
5955  20230914   161500    161959  ...         0.0        0.0       0
5956  20230914   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 16:25:00,785:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694679899, self.tradeDate='20230914', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26317.8, self.close=26309.5, self.high=26326.0, self.low=26301.7, self.vol=658.756, self.amt=17333460.6963, ukdf['pct'].iloc[-1]=-0.000312 , ukdf['amount'].iloc[-1]=17333460.6963, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-19851.8645', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26309.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230914   040000    075959  1694649599  ...    721  0.356106 -0.103098     NaN
722  20230914   080000    115959  1694663999  ...    722  0.425970  0.136540     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-20737.26275958729', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26254.98539377', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=739
self.closeSec=1694678399, self.tradeDate='20230914', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26253.8, self.close=26332.2, self.high=26380.0, self.low=26150.0, self.vol=31772.605, self.amt=834042471.5674 
127.0.0.1 - - [14/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-14 16:00:01,507:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694678399, self.tradeDate='20230914', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26253.8, self.close=26332.2, self.high=26380.0, self.low=26150.0, self.vol=31772.605, self.amt=834042471.5674 
2023-09-14 16:00:01,522:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230913   200000    235959  ...  100568.464  2.633161e+09  0.001711
720  20230914   000000    035959  ...   70495.521  1.847116e+09 -0.003797
721  20230914   040000    075959  ...   19635.224  5.148223e+08  0.003081
722  20230914   080000    115959  ...   76521.139  2.012899e+09  0.001671
723  20230914   120000    155959  ...   31772.605  8.340425e+08  0.002986

[5 rows x 11 columns]
2023-09-14 16:00:02,177:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230913   200000    235959  1694620799  ...    719  0.293882 -0.326290     NaN
720  20230914   000000    035959  1694635199  ...    720  0.337860 -0.178121     NaN
721  20230914   040000    075959  1694649599  ...    721  0.356106 -0.103098     NaN
722  20230914   080000    115959  1694663999  ...    722  0.425970  0.136540     NaN
723  20230914   120000    155959  1694678399  ...    723  0.454654  0.251118     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-25152.1623', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26332.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


