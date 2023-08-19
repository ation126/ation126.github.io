# 20230819 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27988
self.closeSec=1692433199, self.tradeDate='20230819', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25955.6, self.close=25951.0, self.high=25970.0, self.low=25937.2, self.vol=1013.653, self.amt=26308247.4741 
127.0.0.1 - - [19/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-19 16:20:04,686:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230819   155500    155959  ...         0.0        0.0       0
5940  20230819   160000    160459  ...         0.0        0.0       0
5941  20230819   160500    160959  ...         0.0        0.0       0
5942  20230819   161000    161459  ...         0.0        0.0       0
5943  20230819   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 16:20:04,695:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692433199, self.tradeDate='20230819', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25955.6, self.close=25951.0, self.high=25970.0, self.low=25937.2, self.vol=1013.653, self.amt=26308247.4741, ukdf['pct'].iloc[-1]=-0.000181 , ukdf['amount'].iloc[-1]=26308247.4741, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12732.00450121908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25950.63858242', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27989
self.closeSec=1692433499, self.tradeDate='20230819', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25951.0, self.close=25940.7, self.high=25979.2, self.low=25926.8, self.vol=1635.175, self.amt=42436390.7634 
2023-08-19 16:25:00,789:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230819   160000    160459  ...         0.0        0.0       0
5941  20230819   160500    160959  ...         0.0        0.0       0
5942  20230819   161000    161459  ...         0.0        0.0       0
5943  20230819   161500    161959  ...         0.0        0.0       0
5944  20230819   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 16:25:00,789:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692433499, self.tradeDate='20230819', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25951.0, self.close=25940.7, self.high=25979.2, self.low=25926.8, self.vol=1635.175, self.amt=42436390.7634, ukdf['pct'].iloc[-1]=-0.000397 , ukdf['amount'].iloc[-1]=42436390.7634, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12870.4092', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25940.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [19/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27986 

self.closeSec=1692431999, self.tradeDate='20230819', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25894.9, self.close=25906.7, self.high=25909.1, self.low=25892.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27987 

self.closeSec=1692432299, self.tradeDate='20230819', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25906.7, self.close=25902.0, self.high=25919.1, self.low=25901.9 
127.0.0.1 - - [19/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27988 

self.closeSec=1692432599, self.tradeDate='20230819', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25902.0, self.close=25886.5, self.high=25902.1, self.low=25880.4 
127.0.0.1 - - [19/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27989 

self.closeSec=1692432899, self.tradeDate='20230819', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25886.5, self.close=25955.7, self.high=25971.0, self.low=25886.5 
127.0.0.1 - - [19/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27990 

self.closeSec=1692433199, self.tradeDate='20230819', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25955.6, self.close=25951.0, self.high=25970.0, self.low=25937.2 
127.0.0.1 - - [19/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [19/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27991 

self.closeSec=1692433499, self.tradeDate='20230819', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25951.0, self.close=25940.7, self.high=25979.2, self.low=25926.8 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-19 16:00:18,549:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230819    132959  25976.8  ...  43.333333  0.353800  0.588956
5786  20230819    135959  25934.0  ...  42.916667  0.347099  0.596226
5787  20230819    142959  25872.6  ...  42.916667  0.351962  0.601254
5788  20230819    145959  25896.5  ...  42.916667  0.343999  0.611300
5789  20230819    152959  25823.9  ...  42.500000  0.343343  0.621119

[5 rows x 33 columns]
0.514760147601476
acc is : 0.514760147601476
2023-08-19 16:00:18,626:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.465082  0.534918       0  ...  1.109541  -1.0    0.0  0.886489
538     1  0.451060  0.548940       1  ...  1.108520  -1.0    0.0  0.887304
539     1  0.483430  0.516570       0  ...  1.111623  -1.0    0.0  0.884820
540     1  0.437900  0.562100       0  ...  1.111882  -1.0    0.0  0.884614
541     1  0.464548  0.535452       1  ...  1.108062  -1.0    0.0  0.887654

[5 rows x 10 columns]
2023-08-19 16:00:18,641:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.465763  0.534237       0  ...  1.109541  -1.0    0.0  0.887166
46     1  0.451489  0.548511       1  ...  1.108520  -1.0    0.0  0.887760
47     1  0.483520  0.516480       0  ...  1.111623  -1.0    0.0  0.885260
48     1  0.437912  0.562088       0  ...  1.111882  -1.0    0.0  0.884099
49     1  0.464548  0.535452       1  ...  1.108062  -1.0    0.0  0.887654

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.207', 'enterprice': '29084.9', 'countrevence': '0', 'unrealprofit': '76891.1148', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25908.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13991 

self.closeSec=1692430199, self.tradeDate='20230819', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25810.1', self.close='25818'
127.0.0.1 - - [19/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13992 

self.closeSec=1692430799, self.tradeDate='20230819', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25818', self.close='25874.6'
127.0.0.1 - - [19/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13993 

self.closeSec=1692431399, self.tradeDate='20230819', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25874.7', self.close='25899.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13994 

self.closeSec=1692431999, self.tradeDate='20230819', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25899.2', self.close='25906.8'
127.0.0.1 - - [19/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13995 

self.closeSec=1692432599, self.tradeDate='20230819', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25906.7', self.close='25886.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13996 

self.closeSec=1692433199, self.tradeDate='20230819', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25886.5', self.close='25951'
127.0.0.1 - - [19/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13994 

self.closeSec=1692430199, self.tradeDate='20230819', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25810.1', self.close='25818'
127.0.0.1 - - [19/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13995 

self.closeSec=1692430799, self.tradeDate='20230819', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25818', self.close='25874.6'
127.0.0.1 - - [19/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13996 

self.closeSec=1692431399, self.tradeDate='20230819', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25874.7', self.close='25899.2'
127.0.0.1 - - [19/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13997 

self.closeSec=1692431999, self.tradeDate='20230819', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25899.2', self.close='25906.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13998 

self.closeSec=1692432599, self.tradeDate='20230819', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25906.7', self.close='25886.5'
127.0.0.1 - - [19/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13999 

self.closeSec=1692433199, self.tradeDate='20230819', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25886.5', self.close='25951'
127.0.0.1 - - [19/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [19/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13994 

self.closeSec=1692430199, self.tradeDate='20230819', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25810.1', self.close='25818'
127.0.0.1 - - [19/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13995 

self.closeSec=1692430799, self.tradeDate='20230819', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25818', self.close='25874.6'

--handleKline--:  127.0.0.1 - - [19/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13996 

self.closeSec=1692431399, self.tradeDate='20230819', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25874.7', self.close='25899.2'
127.0.0.1 - - [19/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13997 

self.closeSec=1692431999, self.tradeDate='20230819', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25899.2', self.close='25906.8'
127.0.0.1 - - [19/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13998 

self.closeSec=1692432599, self.tradeDate='20230819', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25906.7', self.close='25886.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13999 

self.closeSec=1692433199, self.tradeDate='20230819', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25886.5', self.close='25951'
127.0.0.1 - - [19/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27988
self.closeSec=1692433199, self.tradeDate='20230819', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25955.6, self.close=25951.0, self.high=25970.0, self.low=25937.2, self.vol=1013.653, self.amt=26308247.4741 
127.0.0.1 - - [19/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-19 16:20:04,686:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230819   155500    155959  ...         0.0        0.0       0
5940  20230819   160000    160459  ...         0.0        0.0       0
5941  20230819   160500    160959  ...         0.0        0.0       0
5942  20230819   161000    161459  ...         0.0        0.0       0
5943  20230819   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 16:20:04,695:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692433199, self.tradeDate='20230819', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25955.6, self.close=25951.0, self.high=25970.0, self.low=25937.2, self.vol=1013.653, self.amt=26308247.4741, ukdf['pct'].iloc[-1]=-0.000181 , ukdf['amount'].iloc[-1]=26308247.4741, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-33180.33641033878', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25950.63858242', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27989
self.closeSec=1692433499, self.tradeDate='20230819', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25951.0, self.close=25940.7, self.high=25979.2, self.low=25926.8, self.vol=1635.175, self.amt=42436390.7634 
127.0.0.1 - - [19/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-19 16:25:00,792:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230819   160000    160459  ...         0.0        0.0       0
5941  20230819   160500    160959  ...         0.0        0.0       0
5942  20230819   161000    161459  ...         0.0        0.0       0
5943  20230819   161500    161959  ...         0.0        0.0       0
5944  20230819   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 16:25:00,792:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692433499, self.tradeDate='20230819', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25951.0, self.close=25940.7, self.high=25979.2, self.low=25926.8, self.vol=1635.175, self.amt=42436390.7634, ukdf['pct'].iloc[-1]=-0.000397 , ukdf['amount'].iloc[-1]=42436390.7634, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-33549.4653', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25940.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230819   040000    075959  1692403199  ...    721  0.431456 -0.149531     NaN
722  20230819   080000    115959  1692417599  ...    722  0.463325 -0.078695     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '178521.912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25958.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [19/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=583
self.closeSec=1692431999, self.tradeDate='20230819', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25958.6, self.close=25906.8, self.high=25998.0, self.low=25783.4, self.vol=38367.552, self.amt=993248558.17728 
2023-08-19 16:00:01,557:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692431999, self.tradeDate='20230819', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25958.6, self.close=25906.8, self.high=25998.0, self.low=25783.4, self.vol=38367.552, self.amt=993248558.17728 
2023-08-19 16:00:01,570:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230818   200000    235959  ...  130570.320  3.418381e+09 -0.018369
720  20230819   000000    035959  ...  151020.850  3.919715e+09  0.002320
721  20230819   040000    075959  ...   36849.478  9.618929e+08 -0.000434
722  20230819   080000    115959  ...   28906.008  7.519707e+08 -0.003206
723  20230819   120000    155959  ...   38367.552  9.932486e+08 -0.001995

[5 rows x 11 columns]
2023-08-19 16:00:02,254:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230818   200000    235959  1692374399  ...    719  0.364333 -0.301664     NaN
720  20230819   000000    035959  1692388799  ...    720  0.401023 -0.218074     NaN
721  20230819   040000    075959  1692403199  ...    721  0.431456 -0.149531     NaN
722  20230819   080000    115959  1692417599  ...    722  0.463325 -0.078695     NaN
723  20230819   120000    155959  1692431999  ...    723  0.494699 -0.010184     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '181188.9492', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25906.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


