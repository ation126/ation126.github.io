# 20230924 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38356
self.closeSec=1695543599, self.tradeDate='20230924', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26556.1, self.close=26559.9, self.high=26560.0, self.low=26556.0, self.vol=83.157, self.amt=2208496.8636 
127.0.0.1 - - [24/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-24 16:20:06,369:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230924   155500    155959  ...         0.0        0.0       0
5952  20230924   160000    160459  ...         0.0        0.0       0
5953  20230924   160500    160959  ...         0.0        0.0       0
5954  20230924   161000    161459  ...         0.0        0.0       0
5955  20230924   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 16:20:06,371:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695543599, self.tradeDate='20230924', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26556.1, self.close=26559.9, self.high=26560.0, self.low=26556.0, self.vol=83.157, self.amt=2208496.8636, ukdf['pct'].iloc[-1]=0.000143 , ukdf['amount'].iloc[-1]=2208496.8636, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4247.43', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26559.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38357
self.closeSec=1695543899, self.tradeDate='20230924', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26559.9, self.close=26560.0, self.high=26560.0, self.low=26557.0, self.vol=91.177, self.amt=2421537.5669 
2023-09-24 16:25:00,794:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230924   160000    160459  ...         0.0        0.0       0
5953  20230924   160500    160959  ...         0.0        0.0       0
5954  20230924   161000    161459  ...         0.0        0.0       0
5955  20230924   161500    161959  ...         0.0        0.0       0
5956  20230924   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 16:25:00,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695543899, self.tradeDate='20230924', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26559.9, self.close=26560.0, self.high=26560.0, self.low=26557.0, self.vol=91.177, self.amt=2421537.5669, ukdf['pct'].iloc[-1]=4e-06 , ukdf['amount'].iloc[-1]=2421537.5669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4246.0374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26560', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38354 

self.closeSec=1695542399, self.tradeDate='20230924', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26553.9, self.close=26552.4, self.high=26554.0, self.low=26551.5 
127.0.0.1 - - [24/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38355 

self.closeSec=1695542699, self.tradeDate='20230924', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26552.4, self.close=26556.6, self.high=26558.8, self.low=26552.4 
127.0.0.1 - - [24/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38356 

self.closeSec=1695542999, self.tradeDate='20230924', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26556.5, self.close=26559.2, self.high=26559.3, self.low=26556.5 
127.0.0.1 - - [24/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38357 

self.closeSec=1695543299, self.tradeDate='20230924', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26559.3, self.close=26556.1, self.high=26559.3, self.low=26555.8 
127.0.0.1 - - [24/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38358 

self.closeSec=1695543599, self.tradeDate='20230924', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26556.1, self.close=26559.9, self.high=26560.0, self.low=26556.0 
127.0.0.1 - - [24/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38359 

self.closeSec=1695543899, self.tradeDate='20230924', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26559.9, self.close=26560.0, self.high=26560.0, self.low=26557.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-24 16:00:17,382:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230924    132959  26558.5  ...  45.416667  0.471707  0.514248
5786  20230924    135959  26554.3  ...  45.416667  0.467673  0.534035
5787  20230924    142959  26547.2  ...  45.833333  0.468783  0.551250
5788  20230924    145959  26548.9  ...  45.416667  0.462474  0.575013
5789  20230924    152959  26537.9  ...  45.416667  0.468765  0.590305

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-09-24 16:00:17,442:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493120  0.506880       0  ...  0.961409  -1.0    0.0  1.024565
538     1  0.492123  0.507877       1  ...  0.961348  -1.0    0.0  1.024631
539     1  0.494396  0.505604       0  ...  0.961743  -1.0    0.0  1.024210
540     1  0.491102  0.508898       1  ...  0.961402  -1.0    0.0  1.024573
541     1  0.496791  0.503209       1  ...  0.961221  -1.0    0.0  1.024766

[5 rows x 10 columns]
2023-09-24 16:00:17,453:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493046  0.506954       0  ...  0.961409  -1.0    0.0  1.022734
46     1  0.492293  0.507707       1  ...  0.961348  -1.0    0.0  1.026961
47     1  0.494806  0.505194       0  ...  0.961743  -1.0    0.0  1.027573
48     1  0.491145  0.508855       1  ...  0.961402  -1.0    0.0  1.025907
49     1  0.496791  0.503209       1  ...  0.961221  -1.0    0.0  1.024766

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '14856.4408419383', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26552.65279151', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [24/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19175 

self.closeSec=1695540599, self.tradeDate='20230924', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26545', self.close='26547.4'
127.0.0.1 - - [24/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19176 

self.closeSec=1695541199, self.tradeDate='20230924', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26547.4', self.close='26547.2'
127.0.0.1 - - [24/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19177 

self.closeSec=1695541799, self.tradeDate='20230924', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26547.2', self.close='26554.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19178 

self.closeSec=1695542399, self.tradeDate='20230924', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26554.2', self.close='26552.4'
127.0.0.1 - - [24/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19179 

self.closeSec=1695542999, self.tradeDate='20230924', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26552.4', self.close='26559.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19180 

self.closeSec=1695543599, self.tradeDate='20230924', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26559.3', self.close='26559.9'
127.0.0.1 - - [24/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19178 

self.closeSec=1695540599, self.tradeDate='20230924', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26545', self.close='26547.4'
127.0.0.1 - - [24/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19179 

self.closeSec=1695541199, self.tradeDate='20230924', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26547.4', self.close='26547.2'
127.0.0.1 - - [24/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19180 

self.closeSec=1695541799, self.tradeDate='20230924', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26547.2', self.close='26554.3'
127.0.0.1 - - [24/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19181 

self.closeSec=1695542399, self.tradeDate='20230924', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26554.2', self.close='26552.4'
127.0.0.1 - - [24/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19182 

self.closeSec=1695542999, self.tradeDate='20230924', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26552.4', self.close='26559.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19183 

self.closeSec=1695543599, self.tradeDate='20230924', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26559.3', self.close='26559.9'
127.0.0.1 - - [24/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19178 

self.closeSec=1695540599, self.tradeDate='20230924', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26545', self.close='26547.4'
127.0.0.1 - - [24/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19179 

self.closeSec=1695541199, self.tradeDate='20230924', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26547.4', self.close='26547.2'
127.0.0.1 - - [24/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19180 

self.closeSec=1695541799, self.tradeDate='20230924', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26547.2', self.close='26554.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19181 

self.closeSec=1695542399, self.tradeDate='20230924', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26554.2', self.close='26552.4'
127.0.0.1 - - [24/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19182 

self.closeSec=1695542999, self.tradeDate='20230924', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26552.4', self.close='26559.2'
127.0.0.1 - - [24/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19183 

self.closeSec=1695543599, self.tradeDate='20230924', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26559.3', self.close='26559.9'
127.0.0.1 - - [24/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38356
self.closeSec=1695543599, self.tradeDate='20230924', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26556.1, self.close=26559.9, self.high=26560.0, self.low=26556.0, self.vol=83.157, self.amt=2208496.8636 
127.0.0.1 - - [24/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-24 16:20:06,369:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230924   155500    155959  ...         0.0        0.0       0
5952  20230924   160000    160459  ...         0.0        0.0       0
5953  20230924   160500    160959  ...         0.0        0.0       0
5954  20230924   161000    161459  ...         0.0        0.0       0
5955  20230924   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 16:20:06,371:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695543599, self.tradeDate='20230924', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26556.1, self.close=26559.9, self.high=26560.0, self.low=26556.0, self.vol=83.157, self.amt=2208496.8636, ukdf['pct'].iloc[-1]=0.000143 , ukdf['amount'].iloc[-1]=2208496.8636, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10551.7581', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26559.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38357
self.closeSec=1695543899, self.tradeDate='20230924', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26559.9, self.close=26560.0, self.high=26560.0, self.low=26557.0, self.vol=91.177, self.amt=2421537.5669 
2023-09-24 16:25:00,799:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230924   160000    160459  ...         0.0        0.0       0
5953  20230924   160500    160959  ...         0.0        0.0       0
5954  20230924   161000    161459  ...         0.0        0.0       0
5955  20230924   161500    161959  ...         0.0        0.0       0
5956  20230924   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 16:25:00,799:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695543899, self.tradeDate='20230924', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26559.9, self.close=26560.0, self.high=26560.0, self.low=26557.0, self.vol=91.177, self.amt=2421537.5669, ukdf['pct'].iloc[-1]=4e-06 , ukdf['amount'].iloc[-1]=2421537.5669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10548.044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26560', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230924   040000    075959  1695513599  ...    721  1.214685  1.621132     1.0
722  20230924   080000    115959  1695527999  ...    722  1.231993  1.617838     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-35109.58668142662', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26560.08949374', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=799
self.closeSec=1695542399, self.tradeDate='20230924', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26559.9, self.close=26552.4, self.high=26563.7, self.low=26529.6, self.vol=7565.14, self.amt=200837455.1639 
127.0.0.1 - - [24/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-24 16:00:01,586:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695542399, self.tradeDate='20230924', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26559.9, self.close=26552.4, self.high=26563.7, self.low=26529.6, self.vol=7565.14, self.amt=200837455.1639 
2023-09-24 16:00:01,606:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230923   200000    235959  ...   9319.372  2.474898e+08  0.000188
720  20230924   000000    035959  ...  11673.004  3.103720e+08  0.001013
721  20230924   040000    075959  ...   7650.769  2.032407e+08 -0.001181
722  20230924   080000    115959  ...   5355.769  1.422734e+08 -0.000113
723  20230924   120000    155959  ...   7565.140  2.008375e+08 -0.000286

[5 rows x 11 columns]
2023-09-24 16:00:02,518:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230923   200000    235959  1695484799  ...    719  1.332019  2.020627     1.0
720  20230924   000000    035959  1695499199  ...    720  1.302909  1.884848     1.0
721  20230924   040000    075959  1695513599  ...    721  1.214685  1.621132     1.0
722  20230924   080000    115959  1695527999  ...    722  1.231993  1.617838     1.0
723  20230924   120000    155959  1695542399  ...    723  1.179588  1.453880     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-35481.33620151219', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26552.76971663', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


