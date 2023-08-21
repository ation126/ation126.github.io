# 20230821 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28564
self.closeSec=1692605999, self.tradeDate='20230821', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26000.0, self.close=25994.0, self.high=26000.1, self.low=25967.8, self.vol=1537.177, self.amt=39941852.5405 
127.0.0.1 - - [21/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-21 16:20:05,197:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230821   155500    155959  ...         0.0        0.0       0
5940  20230821   160000    160459  ...         0.0        0.0       0
5941  20230821   160500    160959  ...         0.0        0.0       0
5942  20230821   161000    161459  ...         0.0        0.0       0
5943  20230821   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 16:20:05,204:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692605999, self.tradeDate='20230821', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26000.0, self.close=25994.0, self.high=26000.1, self.low=25967.8, self.vol=1537.177, self.amt=39941852.5405, ukdf['pct'].iloc[-1]=-0.000231 , ukdf['amount'].iloc[-1]=39941852.5405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12148.1576909682', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25992.5635293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28565
self.closeSec=1692606299, self.tradeDate='20230821', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25994.0, self.close=26029.8, self.high=26038.0, self.low=25987.4, self.vol=1114.48, self.amt=29000180.319 
127.0.0.1 - - [21/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-21 16:25:00,761:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230821   160000    160459  ...         0.0        0.0       0
5941  20230821   160500    160959  ...         0.0        0.0       0
5942  20230821   161000    161459  ...         0.0        0.0       0
5943  20230821   161500    161959  ...         0.0        0.0       0
5944  20230821   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 16:25:00,761:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692606299, self.tradeDate='20230821', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25994.0, self.close=26029.8, self.high=26038.0, self.low=25987.4, self.vol=1114.48, self.amt=29000180.319, ukdf['pct'].iloc[-1]=0.001377 , ukdf['amount'].iloc[-1]=29000180.319, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11625.67118310906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26030.08230769', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28562 

self.closeSec=1692604799, self.tradeDate='20230821', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26014.9, self.close=26012.0, self.high=26016.9, self.low=25993.6 
127.0.0.1 - - [21/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28563 

self.closeSec=1692605099, self.tradeDate='20230821', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26011.9, self.close=26021.0, self.high=26021.1, self.low=26004.0 
127.0.0.1 - - [21/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28564 

self.closeSec=1692605399, self.tradeDate='20230821', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26021.1, self.close=26009.0, self.high=26021.1, self.low=26007.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28565 

self.closeSec=1692605699, self.tradeDate='20230821', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26009.0, self.close=26000.0, self.high=26010.6, self.low=26000.0 
127.0.0.1 - - [21/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28566 

self.closeSec=1692605999, self.tradeDate='20230821', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26000.0, self.close=25994.0, self.high=26000.1, self.low=25967.8 
127.0.0.1 - - [21/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28567 

self.closeSec=1692606299, self.tradeDate='20230821', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25994.0, self.close=26029.8, self.high=26038.0, self.low=25987.4 
127.0.0.1 - - [21/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-21 16:00:17,817:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230821    132959  26043.7  ...  45.000000  0.474001  0.479878
5786  20230821    135959  26122.4  ...  45.000000  0.464807  0.487390
5787  20230821    142959  26093.8  ...  45.416667  0.466430  0.493392
5788  20230821    145959  26090.7  ...  45.000000  0.447749  0.512624
5789  20230821    152959  26021.8  ...  44.583333  0.439448  0.536874

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-08-21 16:00:17,881:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.521345  0.478655       0  ...  1.091646  -1.0    0.0  0.880827
538     1  0.478335  0.521665       1  ...  1.091433  -1.0    0.0  0.880999
539     1  0.492424  0.507576       0  ...  1.094311  -1.0    0.0  0.878676
540     1  0.461171  0.538829       0  ...  1.095648  -1.0    0.0  0.877602
541     1  0.473726  0.526274       1  ...  1.094725  -1.0    0.0  0.878342

[5 rows x 10 columns]
2023-08-21 16:00:17,893:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.520985  0.479015       0  ...  1.091646  -1.0    0.0  0.881994
46     1  0.477713  0.522287       1  ...  1.091433  -1.0    0.0  0.881580
47     1  0.492460  0.507540       0  ...  1.094311  -1.0    0.0  0.878878
48     1  0.461235  0.538765       0  ...  1.095648  -1.0    0.0  0.878852
49     1  0.473726  0.526274       1  ...  1.094725  -1.0    0.0  0.878342

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '1712.8511807639', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26009.4962381', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14279 

self.closeSec=1692602999, self.tradeDate='20230821', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26038.1', self.close='25990.1'
127.0.0.1 - - [21/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14280 

self.closeSec=1692603599, self.tradeDate='20230821', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25990', self.close='26018.7'
127.0.0.1 - - [21/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14281 

self.closeSec=1692604199, self.tradeDate='20230821', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26018.7', self.close='26033.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14282 

self.closeSec=1692604799, self.tradeDate='20230821', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26033.1', self.close='26012'
127.0.0.1 - - [21/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14283 

self.closeSec=1692605399, self.tradeDate='20230821', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26011.9', self.close='26009'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14284 

self.closeSec=1692605999, self.tradeDate='20230821', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26009', self.close='25994'
127.0.0.1 - - [21/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14282 

self.closeSec=1692602999, self.tradeDate='20230821', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26038.1', self.close='25990.1'
127.0.0.1 - - [21/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14283 

self.closeSec=1692603599, self.tradeDate='20230821', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25990', self.close='26018.7'
127.0.0.1 - - [21/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14284 

self.closeSec=1692604199, self.tradeDate='20230821', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26018.7', self.close='26033.1'
127.0.0.1 - - [21/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14285 

self.closeSec=1692604799, self.tradeDate='20230821', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26033.1', self.close='26012'
127.0.0.1 - - [21/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14286 

self.closeSec=1692605399, self.tradeDate='20230821', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26011.9', self.close='26009'
127.0.0.1 - - [21/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14287 

self.closeSec=1692605999, self.tradeDate='20230821', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26009', self.close='25994'
127.0.0.1 - - [21/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14282 

self.closeSec=1692602999, self.tradeDate='20230821', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26038.1', self.close='25990.1'
127.0.0.1 - - [21/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14283 

self.closeSec=1692603599, self.tradeDate='20230821', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25990', self.close='26018.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14284 

self.closeSec=1692604199, self.tradeDate='20230821', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26018.7', self.close='26033.1'
127.0.0.1 - - [21/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14285 

self.closeSec=1692604799, self.tradeDate='20230821', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26033.1', self.close='26012'
127.0.0.1 - - [21/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14286 

self.closeSec=1692605399, self.tradeDate='20230821', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26011.9', self.close='26009'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14287 

self.closeSec=1692605999, self.tradeDate='20230821', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26009', self.close='25994'
127.0.0.1 - - [21/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28564
self.closeSec=1692605999, self.tradeDate='20230821', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26000.0, self.close=25994.0, self.high=26000.1, self.low=25967.8, self.vol=1537.177, self.amt=39941852.5405 
127.0.0.1 - - [21/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-21 16:20:05,223:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230821   155500    155959  ...         0.0        0.0       0
5940  20230821   160000    160459  ...         0.0        0.0       0
5941  20230821   160500    160959  ...         0.0        0.0       0
5942  20230821   161000    161459  ...         0.0        0.0       0
5943  20230821   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 16:20:05,234:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692605999, self.tradeDate='20230821', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26000.0, self.close=25994.0, self.high=26000.1, self.low=25967.8, self.vol=1537.177, self.amt=39941852.5405, ukdf['pct'].iloc[-1]=-0.000231 , ukdf['amount'].iloc[-1]=39941852.5405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31623.2019582687', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25992.5635293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28565
self.closeSec=1692606299, self.tradeDate='20230821', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25994.0, self.close=26029.8, self.high=26038.0, self.low=25987.4, self.vol=1114.48, self.amt=29000180.319 
127.0.0.1 - - [21/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-21 16:25:00,762:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230821   160000    160459  ...         0.0        0.0       0
5941  20230821   160500    160959  ...         0.0        0.0       0
5942  20230821   161000    161459  ...         0.0        0.0       0
5943  20230821   161500    161959  ...         0.0        0.0       0
5944  20230821   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 16:25:00,762:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692606299, self.tradeDate='20230821', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25994.0, self.close=26029.8, self.high=26038.0, self.low=25987.4, self.vol=1114.48, self.amt=29000180.319, ukdf['pct'].iloc[-1]=0.001377 , ukdf['amount'].iloc[-1]=29000180.319, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-30229.71701008571', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26030.08230769', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230821   040000    075959  1692575999  ...    721  0.460951 -0.080190     NaN
722  20230821   080000    115959  1692590399  ...    722  0.384638 -0.242202     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '172395.44951065944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26077.81971062', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [21/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=595
self.closeSec=1692604799, self.tradeDate='20230821', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26076.8, self.close=26012.0, self.high=26174.4, self.low=25985.0, self.vol=32357.559, self.amt=843233525.3708 
2023-08-21 16:00:01,545:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692604799, self.tradeDate='20230821', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26076.8, self.close=26012.0, self.high=26174.4, self.low=25985.0, self.vol=32357.559, self.amt=843233525.3708 
2023-08-21 16:00:01,558:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230820   200000    235959  ...  40356.224  1.052823e+09 -0.002633
720  20230821   000000    035959  ...  21311.523  5.558716e+08  0.001039
721  20230821   040000    075959  ...  28522.998  7.469668e+08  0.002060
722  20230821   080000    115959  ...  19223.035  5.018794e+08 -0.003790
723  20230821   120000    155959  ...  32357.559  8.432335e+08 -0.002481

[5 rows x 11 columns]
2023-08-21 16:00:02,241:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230820   200000    235959  1692547199  ...    719  0.535197  0.074747     NaN
720  20230821   000000    035959  1692561599  ...    720  0.512028  0.026201     NaN
721  20230821   040000    075959  1692575999  ...    721  0.460951 -0.080190     NaN
722  20230821   080000    115959  1692590399  ...    722  0.384638 -0.242202     NaN
723  20230821   120000    155959  1692604799  ...    723  0.306959 -0.414992     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '175777.7928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26012', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


