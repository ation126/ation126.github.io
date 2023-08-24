# 20230824 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29428
self.closeSec=1692865199, self.tradeDate='20230824', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26455.6, self.close=26451.6, self.high=26455.7, self.low=26450.6, self.vol=235.944, self.amt=6241317.7944 
127.0.0.1 - - [24/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-24 16:20:05,435:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230824   155500    155959  ...         0.0        0.0       0
5940  20230824   160000    160459  ...         0.0        0.0       0
5941  20230824   160500    160959  ...         0.0        0.0       0
5942  20230824   161000    161459  ...         0.0        0.0       0
5943  20230824   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 16:20:05,446:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692865199, self.tradeDate='20230824', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26455.6, self.close=26451.6, self.high=26455.7, self.low=26450.6, self.vol=235.944, self.amt=6241317.7944, ukdf['pct'].iloc[-1]=-0.000147 , ukdf['amount'].iloc[-1]=6241317.7944, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5755.6158', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26451.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29429
self.closeSec=1692865499, self.tradeDate='20230824', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26451.6, self.close=26418.6, self.high=26451.7, self.low=26414.0, self.vol=1267.338, self.amt=33493027.1882 
2023-08-24 16:25:00,766:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230824   160000    160459  ...         0.0        0.0       0
5941  20230824   160500    160959  ...         0.0        0.0       0
5942  20230824   161000    161459  ...         0.0        0.0       0
5943  20230824   161500    161959  ...         0.0        0.0       0
5944  20230824   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 16:25:00,767:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692865499, self.tradeDate='20230824', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26451.6, self.close=26418.6, self.high=26451.7, self.low=26414.0, self.vol=1267.338, self.amt=33493027.1882, ukdf['pct'].iloc[-1]=-0.001248 , ukdf['amount'].iloc[-1]=33493027.1882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6185.9292', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26420.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29426 

self.closeSec=1692863999, self.tradeDate='20230824', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26457.9, self.close=26460.8, self.high=26467.9, self.low=26456.5 
127.0.0.1 - - [24/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29427 

self.closeSec=1692864299, self.tradeDate='20230824', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26460.8, self.close=26472.1, self.high=26472.1, self.low=26460.7 
127.0.0.1 - - [24/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29428 

self.closeSec=1692864599, self.tradeDate='20230824', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26472.1, self.close=26465.5, self.high=26479.3, self.low=26465.5 
127.0.0.1 - - [24/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29429 

self.closeSec=1692864899, self.tradeDate='20230824', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26465.6, self.close=26455.5, self.high=26465.6, self.low=26453.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29430 

self.closeSec=1692865199, self.tradeDate='20230824', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26455.6, self.close=26451.6, self.high=26455.7, self.low=26450.6 
127.0.0.1 - - [24/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29431 

self.closeSec=1692865499, self.tradeDate='20230824', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26451.6, self.close=26418.6, self.high=26451.7, self.low=26414.0 
127.0.0.1 - - [24/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-24 16:00:16,719:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230824    132959  26440.2  ...  53.333333  0.552954  0.323257
5786  20230824    135959  26435.4  ...  53.333333  0.547350  0.327823
5787  20230824    142959  26411.9  ...  53.333333  0.548408  0.331734
5788  20230824    145959  26417.2  ...  53.750000  0.552215  0.334131
5789  20230824    152959  26436.1  ...  54.166667  0.560517  0.333618

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-08-24 16:00:16,779:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.499493  0.500507       0  ...  1.024045  -1.0    0.0  0.897765
538     1  0.483015  0.516985       1  ...  1.023839  -1.0    0.0  0.897946
539     1  0.491450  0.508550       1  ...  1.023107  -1.0    0.0  0.898588
540     0  0.502293  0.497707       1  ...  1.021500  -1.0    0.0  0.899999
541     0  0.515627  0.484373       0  ...  1.022152  -1.0    0.0  0.899424

[5 rows x 10 columns]
2023-08-24 16:00:16,790:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499790  0.500210       0  ...  1.024045  -1.0    0.0  0.897872
46     1  0.483356  0.516644       1  ...  1.023839  -1.0    0.0  0.897964
47     1  0.491394  0.508606       1  ...  1.023107  -1.0    0.0  0.898493
48     0  0.502224  0.497776       1  ...  1.021500  -1.0    0.0  0.899962
49     0  0.515627  0.484373       0  ...  1.022152  -1.0    0.0  0.899424

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '-1732.47516864198', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26463.36782858', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [24/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14711 

self.closeSec=1692862199, self.tradeDate='20230824', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26471.7', self.close='26477.6'
127.0.0.1 - - [24/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14712 

self.closeSec=1692862799, self.tradeDate='20230824', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26477.6', self.close='26460.2'

--handleKline--:  127.0.0.1 - - [24/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14713 

self.closeSec=1692863399, self.tradeDate='20230824', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26460.1', self.close='26452.8'
127.0.0.1 - - [24/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14714 

self.closeSec=1692863999, self.tradeDate='20230824', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26452.8', self.close='26460.7'
127.0.0.1 - - [24/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14715 

self.closeSec=1692864599, self.tradeDate='20230824', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26460.8', self.close='26465.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14716 

self.closeSec=1692865199, self.tradeDate='20230824', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26465.6', self.close='26451.6'
127.0.0.1 - - [24/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14714 

self.closeSec=1692862199, self.tradeDate='20230824', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26471.7', self.close='26477.6'
127.0.0.1 - - [24/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14715 

self.closeSec=1692862799, self.tradeDate='20230824', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26477.6', self.close='26460.2'
127.0.0.1 - - [24/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14716 

self.closeSec=1692863399, self.tradeDate='20230824', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26460.1', self.close='26452.8'
127.0.0.1 - - [24/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14717 

self.closeSec=1692863999, self.tradeDate='20230824', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26452.8', self.close='26460.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14718 

self.closeSec=1692864599, self.tradeDate='20230824', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26460.8', self.close='26465.5'
127.0.0.1 - - [24/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14719 

self.closeSec=1692865199, self.tradeDate='20230824', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26465.6', self.close='26451.6'
127.0.0.1 - - [24/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14714 

self.closeSec=1692862199, self.tradeDate='20230824', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26471.7', self.close='26477.6'
127.0.0.1 - - [24/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14715 

self.closeSec=1692862799, self.tradeDate='20230824', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26477.6', self.close='26460.2'
127.0.0.1 - - [24/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14716 

self.closeSec=1692863399, self.tradeDate='20230824', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26460.1', self.close='26452.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14717 

self.closeSec=1692863999, self.tradeDate='20230824', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26452.8', self.close='26460.7'
127.0.0.1 - - [24/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14718 

self.closeSec=1692864599, self.tradeDate='20230824', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26460.8', self.close='26465.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14719 

self.closeSec=1692865199, self.tradeDate='20230824', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26465.6', self.close='26451.6'
127.0.0.1 - - [24/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29428
self.closeSec=1692865199, self.tradeDate='20230824', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26455.6, self.close=26451.6, self.high=26455.7, self.low=26450.6, self.vol=235.944, self.amt=6241317.7944 
127.0.0.1 - - [24/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-24 16:20:05,422:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230824   155500    155959  ...         0.0        0.0       0
5940  20230824   160000    160459  ...         0.0        0.0       0
5941  20230824   160500    160959  ...         0.0        0.0       0
5942  20230824   161000    161459  ...         0.0        0.0       0
5943  20230824   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 16:20:05,425:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692865199, self.tradeDate='20230824', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26455.6, self.close=26451.6, self.high=26455.7, self.low=26450.6, self.vol=235.944, self.amt=6241317.7944, ukdf['pct'].iloc[-1]=-0.000147 , ukdf['amount'].iloc[-1]=6241317.7944, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14574.1284', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26451.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29429
self.closeSec=1692865499, self.tradeDate='20230824', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26451.6, self.close=26418.6, self.high=26451.7, self.low=26414.0, self.vol=1267.338, self.amt=33493027.1882 
2023-08-24 16:25:00,777:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230824   160000    160459  ...         0.0        0.0       0
5941  20230824   160500    160959  ...         0.0        0.0       0
5942  20230824   161000    161459  ...         0.0        0.0       0
5943  20230824   161500    161959  ...         0.0        0.0       0
5944  20230824   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-24 16:25:00,778:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692865499, self.tradeDate='20230824', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26451.6, self.close=26418.6, self.high=26451.7, self.low=26414.0, self.vol=1267.338, self.amt=33493027.1882, ukdf['pct'].iloc[-1]=-0.001248 , ukdf['amount'].iloc[-1]=33493027.1882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-15721.7853', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26420.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230824   040000    075959  1692835199  ...    721  0.066786 -0.908375    -1.0
722  20230824   080000    115959  1692849599  ...    722  0.111271 -0.790753    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '154186.23800591928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26432.16725294', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=613
self.closeSec=1692863999, self.tradeDate='20230824', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26430.0, self.close=26460.7, self.high=26509.6, self.low=26370.1, self.vol=23503.45, self.amt=621435423.8244 
127.0.0.1 - - [24/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-08-24 16:00:01,554:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692863999, self.tradeDate='20230824', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26430.0, self.close=26460.7, self.high=26509.6, self.low=26370.1, self.vol=23503.45, self.amt=621435423.8244 
2023-08-24 16:00:01,567:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230823   200000    235959  ...   89252.364  2.321153e+09  0.007953
720  20230824   000000    035959  ...  149537.665  3.958385e+09  0.018401
721  20230824   040000    075959  ...   70672.879  1.870824e+09 -0.007364
722  20230824   080000    115959  ...   29657.298  7.837921e+08  0.000413
723  20230824   120000    155959  ...   23503.450  6.214354e+08  0.001158

[5 rows x 11 columns]
2023-08-24 16:00:02,257:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230823   200000    235959  1692806399  ...    719  0.012680 -1.068013    -1.0
720  20230824   000000    035959  1692820799  ...    720  0.025848 -1.019798    -1.0
721  20230824   040000    075959  1692835199  ...    721  0.066786 -0.908375    -1.0
722  20230824   080000    115959  1692849599  ...    722  0.111271 -0.790753    -1.0
723  20230824   120000    155959  1692863999  ...    723  0.141513 -0.704028    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '152530.78981681908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26464.38193709', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


