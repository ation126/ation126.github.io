# 20230902 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32020
self.closeSec=1693642799, self.tradeDate='20230902', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25781.2, self.close=25766.6, self.high=25782.0, self.low=25764.5, self.vol=192.83, self.amt=4969013.5666 
127.0.0.1 - - [02/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-02 16:20:05,476:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230902   155500    155959  ...         0.0        0.0       0
5940  20230902   160000    160459  ...         0.0        0.0       0
5941  20230902   160500    160959  ...         0.0        0.0       0
5942  20230902   161000    161459  ...         0.0        0.0       0
5943  20230902   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 16:20:05,490:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693642799, self.tradeDate='20230902', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25781.2, self.close=25766.6, self.high=25782.0, self.low=25764.5, self.vol=192.83, self.amt=4969013.5666, ukdf['pct'].iloc[-1]=-0.000562 , ukdf['amount'].iloc[-1]=4969013.5666, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15225.2958', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25771.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32021
self.closeSec=1693643099, self.tradeDate='20230902', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25766.6, self.close=25765.8, self.high=25775.4, self.low=25761.5, self.vol=282.539, self.amt=7280113.9494 
2023-09-02 16:25:00,777:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230902   160000    160459  ...         0.0        0.0       0
5941  20230902   160500    160959  ...         0.0        0.0       0
5942  20230902   161000    161459  ...         0.0        0.0       0
5943  20230902   161500    161959  ...         0.0        0.0       0
5944  20230902   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 16:25:00,777:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693643099, self.tradeDate='20230902', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25766.6, self.close=25765.8, self.high=25775.4, self.low=25761.5, self.vol=282.539, self.amt=7280113.9494, ukdf['pct'].iloc[-1]=-3.1e-05 , ukdf['amount'].iloc[-1]=7280113.9494, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15304.674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25765.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32018 

self.closeSec=1693641599, self.tradeDate='20230902', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25793.2, self.close=25783.9, self.high=25794.5, self.low=25780.8 
127.0.0.1 - - [02/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32019 

self.closeSec=1693641899, self.tradeDate='20230902', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25783.9, self.close=25770.0, self.high=25786.0, self.low=25770.0 
127.0.0.1 - - [02/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32020 

self.closeSec=1693642199, self.tradeDate='20230902', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25770.0, self.close=25769.1, self.high=25775.2, self.low=25765.7 
127.0.0.1 - - [02/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32021 

self.closeSec=1693642499, self.tradeDate='20230902', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25769.2, self.close=25781.1, self.high=25786.0, self.low=25767.0 
127.0.0.1 - - [02/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32022 

self.closeSec=1693642799, self.tradeDate='20230902', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25781.2, self.close=25766.6, self.high=25782.0, self.low=25764.5 
127.0.0.1 - - [02/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32023 

self.closeSec=1693643099, self.tradeDate='20230902', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25766.6, self.close=25765.8, self.high=25775.4, self.low=25761.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-02 16:00:17,142:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230902    132959  25768.5  ...  45.833333  0.436055  0.511984
5786  20230902    135959  25822.8  ...  45.833333  0.433600  0.505071
5787  20230902    142959  25808.8  ...  45.833333  0.430299  0.500104
5788  20230902    145959  25790.1  ...  45.833333  0.430512  0.495396
5789  20230902    152959  25791.0  ...  45.833333  0.428876  0.491717

[5 rows x 33 columns]
0.5166051660516605
acc is : 0.5166051660516605
2023-09-02 16:00:17,204:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.526841  0.473159       0  ...  1.005802  -1.0    0.0  0.989374
538     0  0.504032  0.495968       0  ...  1.006531  -1.0    0.0  0.988657
539     1  0.497614  0.502386       1  ...  1.006496  -1.0    0.0  0.988691
540     0  0.503848  0.496152       0  ...  1.006847  -1.0    0.0  0.988346
541     0  0.501341  0.498659       1  ...  1.006773  -1.0    0.0  0.988419

[5 rows x 10 columns]
2023-09-02 16:00:17,216:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526288  0.473712       0  ...  1.005802  -1.0    0.0  0.988146
46     0  0.503217  0.496783       0  ...  1.006531  -1.0    0.0  0.987737
47     1  0.497023  0.502977       1  ...  1.006496  -1.0    0.0  0.987578
48     0  0.503556  0.496444       0  ...  1.006847  -1.0    0.0  0.988259
49     0  0.501341  0.498659       1  ...  1.006773  -1.0    0.0  0.988419

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '23552.6584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25785.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16007 

self.closeSec=1693639799, self.tradeDate='20230902', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25783.7', self.close='25782'
127.0.0.1 - - [02/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16008 

self.closeSec=1693640399, self.tradeDate='20230902', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25781.9', self.close='25786'
127.0.0.1 - - [02/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16009 

self.closeSec=1693640999, self.tradeDate='20230902', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25786', self.close='25795.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16010 

self.closeSec=1693641599, self.tradeDate='20230902', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25795.4', self.close='25783.9'
127.0.0.1 - - [02/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16011 

self.closeSec=1693642199, self.tradeDate='20230902', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25783.9', self.close='25769.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16012 

self.closeSec=1693642799, self.tradeDate='20230902', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25769.2', self.close='25766.6'
127.0.0.1 - - [02/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [02/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16010 

self.closeSec=1693639799, self.tradeDate='20230902', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25783.7', self.close='25782'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16011 

self.closeSec=1693640399, self.tradeDate='20230902', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25781.9', self.close='25786'
127.0.0.1 - - [02/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [02/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16012 

self.closeSec=1693640999, self.tradeDate='20230902', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25786', self.close='25795.4'
127.0.0.1 - - [02/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16013 

self.closeSec=1693641599, self.tradeDate='20230902', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25795.4', self.close='25783.9'
127.0.0.1 - - [02/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16014 

self.closeSec=1693642199, self.tradeDate='20230902', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25783.9', self.close='25769.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16015 

self.closeSec=1693642799, self.tradeDate='20230902', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25769.2', self.close='25766.6'
127.0.0.1 - - [02/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16010 

self.closeSec=1693639799, self.tradeDate='20230902', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25783.7', self.close='25782'
127.0.0.1 - - [02/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16011 

self.closeSec=1693640399, self.tradeDate='20230902', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25781.9', self.close='25786'
127.0.0.1 - - [02/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16012 

self.closeSec=1693640999, self.tradeDate='20230902', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25786', self.close='25795.4'
127.0.0.1 - - [02/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16013 

self.closeSec=1693641599, self.tradeDate='20230902', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25795.4', self.close='25783.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16014 

self.closeSec=1693642199, self.tradeDate='20230902', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25783.9', self.close='25769.1'
127.0.0.1 - - [02/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16015 

self.closeSec=1693642799, self.tradeDate='20230902', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25769.2', self.close='25766.6'
127.0.0.1 - - [02/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32020
self.closeSec=1693642799, self.tradeDate='20230902', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25781.2, self.close=25766.6, self.high=25782.0, self.low=25764.5, self.vol=192.83, self.amt=4969013.5666 
127.0.0.1 - - [02/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-02 16:20:05,469:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230902   155500    155959  ...         0.0        0.0       0
5940  20230902   160000    160459  ...         0.0        0.0       0
5941  20230902   160500    160959  ...         0.0        0.0       0
5942  20230902   161000    161459  ...         0.0        0.0       0
5943  20230902   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 16:20:05,475:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693642799, self.tradeDate='20230902', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25781.2, self.close=25766.6, self.high=25782.0, self.low=25764.5, self.vol=192.83, self.amt=4969013.5666, ukdf['pct'].iloc[-1]=-0.000562 , ukdf['amount'].iloc[-1]=4969013.5666, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-39830.0084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25771.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32021
self.closeSec=1693643099, self.tradeDate='20230902', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25766.6, self.close=25765.8, self.high=25775.4, self.low=25761.5, self.vol=282.539, self.amt=7280113.9494 
127.0.0.1 - - [02/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-02 16:25:00,791:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230902   160000    160459  ...         0.0        0.0       0
5941  20230902   160500    160959  ...         0.0        0.0       0
5942  20230902   161000    161459  ...         0.0        0.0       0
5943  20230902   161500    161959  ...         0.0        0.0       0
5944  20230902   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 16:25:00,792:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693643099, self.tradeDate='20230902', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25766.6, self.close=25765.8, self.high=25775.4, self.low=25761.5, self.vol=282.539, self.amt=7280113.9494, ukdf['pct'].iloc[-1]=-3.1e-05 , ukdf['amount'].iloc[-1]=7280113.9494, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-40041.7121', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25765.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230902   040000    075959  1693612799  ...    721  0.614138  0.799056     1.0
722  20230902   080000    115959  1693627199  ...    722  0.633890  0.843596     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-117189.39057867912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25786.89525294', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=667
self.closeSec=1693641599, self.tradeDate='20230902', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25786.1, self.close=25783.9, self.high=25841.4, self.low=25754.7, self.vol=13773.944, self.amt=355274981.076 
127.0.0.1 - - [02/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-02 16:00:01,521:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693641599, self.tradeDate='20230902', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25786.1, self.close=25783.9, self.high=25841.4, self.low=25754.7, self.vol=13773.944, self.amt=355274981.076 
2023-09-02 16:00:01,541:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230901   200000    235959  ...  118639.495  3.069677e+09 -0.009054
720  20230902   000000    035959  ...  134918.148  3.454822e+09 -0.006237
721  20230902   040000    075959  ...   37989.932  9.790657e+08  0.006182
722  20230902   080000    115959  ...   12086.818  3.116060e+08 -0.000368
723  20230902   120000    155959  ...   13773.944  3.552750e+08 -0.000085

[5 rows x 11 columns]
2023-09-02 16:00:02,343:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230901   200000    235959  1693583999  ...    719  0.627829  0.863870     1.0
720  20230902   000000    035959  1693598399  ...    720  0.605634  0.790027     1.0
721  20230902   040000    075959  1693612799  ...    721  0.614138  0.799056     1.0
722  20230902   080000    115959  1693627199  ...    722  0.633890  0.843596     1.0
723  20230902   120000    155959  1693641599  ...    723  0.654133  0.889894     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-117360.8748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25783.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


