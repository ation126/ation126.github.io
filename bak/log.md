# 20230818 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27700
self.closeSec=1692346799, self.tradeDate='20230818', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26488.0, self.close=26420.0, self.high=26488.9, self.low=26420.0, self.vol=1124.977, self.amt=29765216.6227 
127.0.0.1 - - [18/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-18 16:20:04,772:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230818   155500    155959  ...         0.0        0.0       0
5940  20230818   160000    160459  ...         0.0        0.0       0
5941  20230818   160500    160959  ...         0.0        0.0       0
5942  20230818   161000    161459  ...         0.0        0.0       0
5943  20230818   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 16:20:04,776:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692346799, self.tradeDate='20230818', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26488.0, self.close=26420.0, self.high=26488.9, self.low=26420.0, self.vol=1124.977, self.amt=29765216.6227, ukdf['pct'].iloc[-1]=-0.002567 , ukdf['amount'].iloc[-1]=29765216.6227, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6152.16301148394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26423.12468681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27701
self.closeSec=1692347099, self.tradeDate='20230818', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26424.1, self.close=26418.8, self.high=26439.9, self.low=26413.0, self.vol=852.573, self.amt=22530995.5865 
2023-08-18 16:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230818   160000    160459  ...         0.0        0.0       0
5941  20230818   160500    160959  ...         0.0        0.0       0
5942  20230818   161000    161459  ...         0.0        0.0       0
5943  20230818   161500    161959  ...         0.0        0.0       0
5944  20230818   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 16:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692347099, self.tradeDate='20230818', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26424.1, self.close=26418.8, self.high=26439.9, self.low=26413.0, self.vol=852.573, self.amt=22530995.5865, ukdf['pct'].iloc[-1]=-4.5e-05 , ukdf['amount'].iloc[-1]=22530995.5865, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6210.32482292178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26418.94819597', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [18/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27698 

self.closeSec=1692345599, self.tradeDate='20230818', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26448.5, self.close=26418.5, self.high=26451.1, self.low=26404.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27699 

self.closeSec=1692345899, self.tradeDate='20230818', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26413.8, self.close=26454.3, self.high=26454.4, self.low=26404.1 
127.0.0.1 - - [18/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27700 

self.closeSec=1692346199, self.tradeDate='20230818', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26454.3, self.close=26482.9, self.high=26482.9, self.low=26439.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27701 

self.closeSec=1692346499, self.tradeDate='20230818', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26482.8, self.close=26488.0, self.high=26488.0, self.low=26475.5 
127.0.0.1 - - [18/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27702 

self.closeSec=1692346799, self.tradeDate='20230818', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26488.0, self.close=26420.0, self.high=26488.9, self.low=26420.0 
127.0.0.1 - - [18/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27703 

self.closeSec=1692347099, self.tradeDate='20230818', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26424.1, self.close=26418.8, self.high=26439.9, self.low=26413.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-18 16:00:16,868:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230818    132959  26256.5  ...  44.583333  0.295405  0.621740
5786  20230818    135959  26427.3  ...  45.000000  0.295458  0.616325
5787  20230818    142959  26427.7  ...  45.000000  0.308123  0.610073
5788  20230818    145959  26499.9  ...  44.583333  0.307396  0.604148
5789  20230818    152959  26489.4  ...  44.166667  0.303573  0.599432

[5 rows x 33 columns]
0.5350553505535055
acc is : 0.5350553505535055
2023-08-18 16:00:16,961:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.529188  0.470812       1  ...  1.096342  -1.0    0.0  0.909594
538     1  0.473299  0.526701       1  ...  1.093347  -1.0    0.0  0.912079
539     0  0.510421  0.489579       0  ...  1.093730  -1.0    0.0  0.911759
540     1  0.488788  0.511212       0  ...  1.095741  -1.0    0.0  0.910082
541     1  0.462702  0.537298       0  ...  1.096711  -1.0    0.0  0.909277

[5 rows x 10 columns]
2023-08-18 16:00:16,972:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.529621  0.470379       1  ...  1.096342  -1.0    0.0  0.907479
46     1  0.473986  0.526014       1  ...  1.093347  -1.0    0.0  0.911094
47     0  0.511118  0.488882       0  ...  1.093730  -1.0    0.0  0.910878
48     1  0.489190  0.510810       0  ...  1.095741  -1.0    0.0  0.909406
49     1  0.462702  0.537298       0  ...  1.096711  -1.0    0.0  0.909277

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.207', 'enterprice': '29084.9', 'countrevence': '0', 'unrealprofit': '64702.8903', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26412', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [18/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13847 

self.closeSec=1692343799, self.tradeDate='20230818', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26473.5', self.close='26441.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13848127.0.0.1 - - [18/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
 

self.closeSec=1692344399, self.tradeDate='20230818', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26441.9', self.close='26465'
127.0.0.1 - - [18/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13849 

self.closeSec=1692344999, self.tradeDate='20230818', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26465', self.close='26442.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13850 

self.closeSec=1692345599, self.tradeDate='20230818', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26442.1', self.close='26418.5'
127.0.0.1 - - [18/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13851 

self.closeSec=1692346199, self.tradeDate='20230818', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26413.8', self.close='26482.9'
127.0.0.1 - - [18/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13852 

self.closeSec=1692346799, self.tradeDate='20230818', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26482.8', self.close='26420'
127.0.0.1 - - [18/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [18/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13850 

self.closeSec=1692343799, self.tradeDate='20230818', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26473.5', self.close='26441.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13851 

self.closeSec=1692344399, self.tradeDate='20230818', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26441.9', self.close='26465'
127.0.0.1 - - [18/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13852 

self.closeSec=1692344999, self.tradeDate='20230818', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26465', self.close='26442.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13853 

self.closeSec=1692345599, self.tradeDate='20230818', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26442.1', self.close='26418.5'
127.0.0.1 - - [18/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13854 

self.closeSec=1692346199, self.tradeDate='20230818', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26413.8', self.close='26482.9'
127.0.0.1 - - [18/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13855 

self.closeSec=1692346799, self.tradeDate='20230818', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26482.8', self.close='26420'
127.0.0.1 - - [18/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13850 

self.closeSec=1692343799, self.tradeDate='20230818', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26473.5', self.close='26441.9'
127.0.0.1 - - [18/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13851 

self.closeSec=1692344399, self.tradeDate='20230818', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26441.9', self.close='26465'
127.0.0.1 - - [18/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13852 

self.closeSec=1692344999, self.tradeDate='20230818', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26465', self.close='26442.1'
127.0.0.1 - - [18/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13853 

self.closeSec=1692345599, self.tradeDate='20230818', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26442.1', self.close='26418.5'
127.0.0.1 - - [18/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13854 

self.closeSec=1692346199, self.tradeDate='20230818', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26413.8', self.close='26482.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13855 

self.closeSec=1692346799, self.tradeDate='20230818', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26482.8', self.close='26420'
127.0.0.1 - - [18/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27700
self.closeSec=1692346799, self.tradeDate='20230818', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26488.0, self.close=26420.0, self.high=26488.9, self.low=26420.0, self.vol=1124.977, self.amt=29765216.6227 
127.0.0.1 - - [18/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-18 16:20:04,752:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230818   155500    155959  ...         0.0        0.0       0
5940  20230818   160000    160459  ...         0.0        0.0       0
5941  20230818   160500    160959  ...         0.0        0.0       0
5942  20230818   161000    161459  ...         0.0        0.0       0
5943  20230818   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 16:20:04,756:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692346799, self.tradeDate='20230818', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26488.0, self.close=26420.0, self.high=26488.9, self.low=26420.0, self.vol=1124.977, self.amt=29765216.6227, ukdf['pct'].iloc[-1]=-0.002567 , ukdf['amount'].iloc[-1]=29765216.6227, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-15631.73000718979', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26423.12468681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27701
self.closeSec=1692347099, self.tradeDate='20230818', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26424.1, self.close=26418.8, self.high=26439.9, self.low=26413.0, self.vol=852.573, self.amt=22530995.5865 
2023-08-18 16:25:00,821:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230818   160000    160459  ...         0.0        0.0       0
5941  20230818   160500    160959  ...         0.0        0.0       0
5942  20230818   161000    161459  ...         0.0        0.0       0
5943  20230818   161500    161959  ...         0.0        0.0       0
5944  20230818   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 16:25:00,821:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692347099, self.tradeDate='20230818', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26424.1, self.close=26418.8, self.high=26439.9, self.low=26413.0, self.vol=852.573, self.amt=22530995.5865, ukdf['pct'].iloc[-1]=-4.5e-05 , ukdf['amount'].iloc[-1]=22530995.5865, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-15786.84905347823', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26418.94819597', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230818   040000    075959  1692316799  ...    721  0.117928 -0.871146    -1.0
722  20230818   080000    115959  1692331199  ...    722  0.188193 -0.707026    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '156358.2676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26389.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [18/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=577
self.closeSec=1692345599, self.tradeDate='20230818', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26386.0, self.close=26418.5, self.high=26597.7, self.low=26150.0, self.vol=75859.899, self.amt=2001521600.96324 
2023-08-18 16:00:01,554:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692345599, self.tradeDate='20230818', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26386.0, self.close=26418.5, self.high=26597.7, self.low=26150.0, self.vol=75859.899, self.amt=2001521600.96324 
2023-08-18 16:00:01,570:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230817   200000    235959  ...  182531.640  5.157597e+09 -0.021538
720  20230818   000000    035959  ...  133611.979  3.727531e+09 -0.001286
721  20230818   040000    075959  ...  384716.301  1.021675e+10 -0.045885
722  20230818   080000    115959  ...   78941.126  2.099161e+09 -0.008407
723  20230818   120000    155959  ...   75859.899  2.001522e+09  0.001232

[5 rows x 11 columns]
2023-08-18 16:00:02,349:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230817   200000    235959  1692287999  ...    719  0.423048 -0.179032     NaN
720  20230818   000000    035959  1692302399  ...    720  0.534098  0.066503     NaN
721  20230818   040000    075959  1692316799  ...    721  0.117928 -0.871146    -1.0
722  20230818   080000    115959  1692331199  ...    722  0.188193 -0.707026    -1.0
723  20230818   120000    155959  1692345599  ...    723  0.259513 -0.542461     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '155075.6559492238', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26414.85936115', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


