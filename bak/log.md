# 20230907 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33460
self.closeSec=1694074799, self.tradeDate='20230907', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25727.6, self.close=25729.8, self.high=25745.9, self.low=25726.1, self.vol=379.679, self.amt=9771817.3885 
127.0.0.1 - - [07/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-07 16:20:06,033:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230907   155500    155959  ...         0.0        0.0       0
5952  20230907   160000    160459  ...         0.0        0.0       0
5953  20230907   160500    160959  ...         0.0        0.0       0
5954  20230907   161000    161459  ...         0.0        0.0       0
5955  20230907   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 16:20:06,037:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694074799, self.tradeDate='20230907', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25727.6, self.close=25729.8, self.high=25745.9, self.low=25726.1, self.vol=379.679, self.amt=9771817.3885, ukdf['pct'].iloc[-1]=8.6e-05 , ukdf['amount'].iloc[-1]=9771817.3885, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15807.4026', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25729.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33461
self.closeSec=1694075099, self.tradeDate='20230907', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25729.9, self.close=25725.0, self.high=25731.6, self.low=25725.0, self.vol=166.391, self.amt=4281024.3893 
127.0.0.1 - - [07/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-07 16:25:00,782:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230907   160000    160459  ...         0.0        0.0       0
5953  20230907   160500    160959  ...         0.0        0.0       0
5954  20230907   161000    161459  ...         0.0        0.0       0
5955  20230907   161500    161959  ...         0.0        0.0       0
5956  20230907   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 16:25:00,782:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694075099, self.tradeDate='20230907', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25729.9, self.close=25725.0, self.high=25731.6, self.low=25725.0, self.vol=166.391, self.amt=4281024.3893, ukdf['pct'].iloc[-1]=-0.000187 , ukdf['amount'].iloc[-1]=4281024.3893, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15851.01719959428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25726.66811722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [07/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33458 

self.closeSec=1694073599, self.tradeDate='20230907', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25758.1, self.close=25750.9, self.high=25758.1, self.low=25750.0 
127.0.0.1 - - [07/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33459 

self.closeSec=1694073899, self.tradeDate='20230907', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25751.0, self.close=25742.5, self.high=25751.0, self.low=25736.8 
127.0.0.1 - - [07/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33460 

self.closeSec=1694074199, self.tradeDate='20230907', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25742.5, self.close=25736.6, self.high=25742.5, self.low=25730.9 
127.0.0.1 - - [07/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33461 

self.closeSec=1694074499, self.tradeDate='20230907', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25736.6, self.close=25727.6, self.high=25736.6, self.low=25724.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33462 

self.closeSec=1694074799, self.tradeDate='20230907', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25727.6, self.close=25729.8, self.high=25745.9, self.low=25726.1 
127.0.0.1 - - [07/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33463 

self.closeSec=1694075099, self.tradeDate='20230907', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25729.9, self.close=25725.0, self.high=25731.6, self.low=25725.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-07 16:00:17,143:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230907    132959  25803.6  ...  49.166667  0.509678  0.460592
5786  20230907    135959  25774.4  ...  49.583333  0.510386  0.455175
5787  20230907    142959  25776.5  ...  50.000000  0.513414  0.449265
5788  20230907    145959  25785.9  ...  49.583333  0.501237  0.447037
5789  20230907    152959  25750.0  ...  49.583333  0.497370  0.446013

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-09-07 16:00:17,207:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.486806  0.513194       1  ...  0.997867   1.0    0.0  0.991881
538     1  0.490166  0.509834       1  ...  0.998227   1.0    0.0  0.992239
539     1  0.489392  0.510608       0  ...  0.996841   1.0    0.0  0.990861
540     1  0.476887  0.523113       0  ...  0.996396   1.0    0.0  0.990419
541     1  0.479762  0.520238       1  ...  0.996872   1.0    0.0  0.990892

[5 rows x 10 columns]
2023-09-07 16:00:17,218:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486158  0.513842       1  ...  0.997867   1.0    0.0  0.990707
46     1  0.489826  0.510174       1  ...  0.998227   1.0    0.0  0.991563
47     1  0.489412  0.510588       0  ...  0.996841   1.0    0.0  0.990229
48     1  0.476395  0.523605       0  ...  0.996396   1.0    0.0  0.989364
49     1  0.479762  0.520238       1  ...  0.996872   1.0    0.0  0.990892

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.331', 'enterprice': '25653.5', 'countrevence': '0', 'unrealprofit': '2776.52781521951', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25751.50317021', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16727 

self.closeSec=1694071799, self.tradeDate='20230907', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25755.2', self.close='25738.6'
127.0.0.1 - - [07/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16728 

self.closeSec=1694072399, self.tradeDate='20230907', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25738.6', self.close='25751.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16729 

self.closeSec=1694072999, self.tradeDate='20230907', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25750.4', self.close='25744.4'
127.0.0.1 - - [07/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16730 

self.closeSec=1694073599, self.tradeDate='20230907', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25744.5', self.close='25750.9'
127.0.0.1 - - [07/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16731 

self.closeSec=1694074199, self.tradeDate='20230907', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25751', self.close='25736.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16732 

self.closeSec=1694074799, self.tradeDate='20230907', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25736.6', self.close='25729.8'
127.0.0.1 - - [07/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16730 

self.closeSec=1694071799, self.tradeDate='20230907', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25755.2', self.close='25738.6'
127.0.0.1 - - [07/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16731 

self.closeSec=1694072399, self.tradeDate='20230907', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25738.6', self.close='25751.6'
127.0.0.1 - - [07/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16732 

self.closeSec=1694072999, self.tradeDate='20230907', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25750.4', self.close='25744.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16733 

self.closeSec=1694073599, self.tradeDate='20230907', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25744.5', self.close='25750.9'
127.0.0.1 - - [07/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16734 

self.closeSec=1694074199, self.tradeDate='20230907', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25751', self.close='25736.5'
127.0.0.1 - - [07/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16735 

self.closeSec=1694074799, self.tradeDate='20230907', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25736.6', self.close='25729.8'
127.0.0.1 - - [07/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16730 

self.closeSec=1694071799, self.tradeDate='20230907', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25755.2', self.close='25738.6'
127.0.0.1 - - [07/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16731 

self.closeSec=1694072399, self.tradeDate='20230907', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25738.6', self.close='25751.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16732 

self.closeSec=1694072999, self.tradeDate='20230907', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25750.4', self.close='25744.4'
127.0.0.1 - - [07/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16733 

self.closeSec=1694073599, self.tradeDate='20230907', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25744.5', self.close='25750.9'
127.0.0.1 - - [07/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16734 

self.closeSec=1694074199, self.tradeDate='20230907', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25751', self.close='25736.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16735 

self.closeSec=1694074799, self.tradeDate='20230907', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25736.6', self.close='25729.8'
127.0.0.1 - - [07/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33460
self.closeSec=1694074799, self.tradeDate='20230907', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25727.6, self.close=25729.8, self.high=25745.9, self.low=25726.1, self.vol=379.679, self.amt=9771817.3885 
127.0.0.1 - - [07/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-07 16:20:06,032:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230907   155500    155959  ...         0.0        0.0       0
5952  20230907   160000    160459  ...         0.0        0.0       0
5953  20230907   160500    160959  ...         0.0        0.0       0
5954  20230907   161000    161459  ...         0.0        0.0       0
5955  20230907   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 16:20:06,034:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694074799, self.tradeDate='20230907', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25727.6, self.close=25729.8, self.high=25745.9, self.low=25726.1, self.vol=379.679, self.amt=9771817.3885, ukdf['pct'].iloc[-1]=8.6e-05 , ukdf['amount'].iloc[-1]=9771817.3885, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-41382.5022', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25729.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33461
self.closeSec=1694075099, self.tradeDate='20230907', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25729.9, self.close=25725.0, self.high=25731.6, self.low=25725.0, self.vol=166.391, self.amt=4281024.3893 
127.0.0.1 - - [07/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-07 16:25:00,776:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230907   160000    160459  ...         0.0        0.0       0
5953  20230907   160500    160959  ...         0.0        0.0       0
5954  20230907   161000    161459  ...         0.0        0.0       0
5955  20230907   161500    161959  ...         0.0        0.0       0
5956  20230907   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-07 16:25:00,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694075099, self.tradeDate='20230907', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25729.9, self.close=25725.0, self.high=25731.6, self.low=25725.0, self.vol=166.391, self.amt=4281024.3893, ukdf['pct'].iloc[-1]=-0.000187 , ukdf['amount'].iloc[-1]=4281024.3893, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-41498.82345833198', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25726.66811722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230907   040000    075959  1694044799  ...    721  0.022021 -1.049607    -1.0
722  20230907   080000    115959  1694059199  ...    722  0.023655 -1.045281    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '3813.7059', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25825.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=697
self.closeSec=1694073599, self.tradeDate='20230907', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25824.6, self.close=25750.9, self.high=25838.0, self.low=25735.2, self.vol=15151.927, self.amt=390637438.2959 
127.0.0.1 - - [07/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-07 16:00:01,533:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694073599, self.tradeDate='20230907', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25824.6, self.close=25750.9, self.high=25838.0, self.low=25735.2, self.vol=15151.927, self.amt=390637438.2959 
2023-09-07 16:00:01,546:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230906   200000    235959  ...   58993.312  1.512453e+09 -0.005668
720  20230907   000000    035959  ...  127581.603  3.276441e+09  0.004031
721  20230907   040000    075959  ...   19974.218  5.138199e+08  0.002648
722  20230907   080000    115959  ...   14048.498  3.619145e+08  0.003002
723  20230907   120000    155959  ...   15151.927  3.906374e+08 -0.002858

[5 rows x 11 columns]
2023-09-07 16:00:02,223:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230906   200000    235959  1694015999  ...    719  0.281480 -0.322471     NaN
720  20230907   000000    035959  1694030399  ...    720  0.018381 -1.059710    -1.0
721  20230907   040000    075959  1694044799  ...    721  0.022021 -1.049607    -1.0
722  20230907   080000    115959  1694059199  ...    722  0.023655 -1.045281    -1.0
723  20230907   120000    155959  1694073599  ...    723  0.024359 -1.043592    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '8012.59167668967', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25752.16337729', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


