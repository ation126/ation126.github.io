# 20230928 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39508
self.closeSec=1695889199, self.tradeDate='20230928', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26405.0, self.close=26395.0, self.high=26418.1, self.low=26391.5, self.vol=1105.643, self.amt=29190145.4985 
127.0.0.1 - - [28/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-28 16:20:06,369:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230928   155500    155959  ...         0.0        0.0       0
5952  20230928   160000    160459  ...         0.0        0.0       0
5953  20230928   160500    160959  ...         0.0        0.0       0
5954  20230928   161000    161459  ...         0.0        0.0       0
5955  20230928   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 16:20:06,373:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695889199, self.tradeDate='20230928', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26405.0, self.close=26395.0, self.high=26418.1, self.low=26391.5, self.vol=1105.643, self.amt=29190145.4985, ukdf['pct'].iloc[-1]=-0.000477 , ukdf['amount'].iloc[-1]=29190145.4985, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6591.31977854658', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26391.58966117', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39509
self.closeSec=1695889499, self.tradeDate='20230928', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26392.1, self.close=26401.0, self.high=26401.0, self.low=26386.0, self.vol=562.744, self.amt=14851725.9321 
2023-09-28 16:25:00,817:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230928   160000    160459  ...         0.0        0.0       0
5953  20230928   160500    160959  ...         0.0        0.0       0
5954  20230928   161000    161459  ...         0.0        0.0       0
5955  20230928   161500    161959  ...         0.0        0.0       0
5956  20230928   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 16:25:00,817:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695889499, self.tradeDate='20230928', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26392.1, self.close=26401.0, self.high=26401.0, self.low=26386.0, self.vol=562.744, self.amt=14851725.9321, ukdf['pct'].iloc[-1]=0.000227 , ukdf['amount'].iloc[-1]=14851725.9321, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6418.4934', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26404', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39506 

self.closeSec=1695887999, self.tradeDate='20230928', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26448.2, self.close=26445.7, self.high=26448.3, self.low=26438.0 
127.0.0.1 - - [28/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39507 

self.closeSec=1695888299, self.tradeDate='20230928', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26445.7, self.close=26440.1, self.high=26454.3, self.low=26436.0 
127.0.0.1 - - [28/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39508 

self.closeSec=1695888599, self.tradeDate='20230928', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26438.3, self.close=26415.4, self.high=26440.8, self.low=26409.9 
127.0.0.1 - - [28/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39509 

self.closeSec=1695888899, self.tradeDate='20230928', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26415.5, self.close=26407.6, self.high=26425.0, self.low=26407.5 
127.0.0.1 - - [28/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39510 

self.closeSec=1695889199, self.tradeDate='20230928', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26405.0, self.close=26395.0, self.high=26418.1, self.low=26391.5 
127.0.0.1 - - [28/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39511 

127.0.0.1 - - [28/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
self.closeSec=1695889499, self.tradeDate='20230928', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26392.1, self.close=26401.0, self.high=26401.0, self.low=26386.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-28 16:00:17,623:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230928    132959  26431.8  ...  49.166667  0.538175  0.572007
5786  20230928    135959  26468.0  ...  49.166667  0.529535  0.568294
5787  20230928    142959  26437.0  ...  48.750000  0.522485  0.566971
5788  20230928    145959  26411.2  ...  49.166667  0.534925  0.561519
5789  20230928    152959  26461.8  ...  49.166667  0.530687  0.557697

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-09-28 16:00:17,685:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510107  0.489893       0  ...  0.943719   1.0    0.0  0.999429
538     1  0.487822  0.512178       0  ...  0.942802   1.0    0.0  0.998458
539     1  0.487653  0.512347       1  ...  0.944608   1.0    0.0  1.000370
540     0  0.512392  0.487608       0  ...  0.944066   1.0    0.0  0.999796
541     1  0.489152  0.510848       0  ...  0.944033   1.0    0.0  0.999762

[5 rows x 10 columns]
2023-09-28 16:00:17,697:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509644  0.490356       0  ...  0.943719   1.0    0.0  0.995931
46     1  0.487501  0.512499       0  ...  0.942802   1.0    0.0  0.995946
47     1  0.487190  0.512810       1  ...  0.944608   1.0    0.0  0.996791
48     0  0.512193  0.487807       0  ...  0.944066   1.0    0.0  0.998437
49     1  0.489152  0.510848       0  ...  0.944033   1.0    0.0  0.999762

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.704', 'enterprice': '26435.2', 'countrevence': '0', 'unrealprofit': '84.8232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26438.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19751 

self.closeSec=1695886199, self.tradeDate='20230928', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26485.7', self.close='26446.6'
127.0.0.1 - - [28/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19752 

self.closeSec=1695886799, self.tradeDate='20230928', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26446.7', self.close='26462.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19753 

self.closeSec=1695887399, self.tradeDate='20230928', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26462', self.close='26495.3'
127.0.0.1 - - [28/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19754 

self.closeSec=1695887999, self.tradeDate='20230928', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26495.3', self.close='26445.6'
127.0.0.1 - - [28/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19755 

self.closeSec=1695888599, self.tradeDate='20230928', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26445.7', self.close='26415.4'
127.0.0.1 - - [28/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19756 

self.closeSec=1695889199, self.tradeDate='20230928', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26415.5', self.close='26392.1'
127.0.0.1 - - [28/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19754 

self.closeSec=1695886199, self.tradeDate='20230928', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26485.7', self.close='26446.6'
127.0.0.1 - - [28/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19755 

self.closeSec=1695886799, self.tradeDate='20230928', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26446.7', self.close='26462.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19756 

self.closeSec=1695887399, self.tradeDate='20230928', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26462', self.close='26495.3'
127.0.0.1 - - [28/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19757 

self.closeSec=1695887999, self.tradeDate='20230928', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26495.3', self.close='26445.6'
127.0.0.1 - - [28/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19758 

self.closeSec=1695888599, self.tradeDate='20230928', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26445.7', self.close='26415.4'
127.0.0.1 - - [28/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19759 

self.closeSec=1695889199, self.tradeDate='20230928', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26415.5', self.close='26392.1'
127.0.0.1 - - [28/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19754 

self.closeSec=1695886199, self.tradeDate='20230928', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26485.7', self.close='26446.6'
127.0.0.1 - - [28/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19755 

self.closeSec=1695886799, self.tradeDate='20230928', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26446.7', self.close='26462.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19756 

self.closeSec=1695887399, self.tradeDate='20230928', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26462', self.close='26495.3'
127.0.0.1 - - [28/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19757 

self.closeSec=1695887999, self.tradeDate='20230928', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26495.3', self.close='26445.6'
127.0.0.1 - - [28/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19758 

self.closeSec=1695888599, self.tradeDate='20230928', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26445.7', self.close='26415.4'
127.0.0.1 - - [28/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19759 

self.closeSec=1695889199, self.tradeDate='20230928', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26415.5', self.close='26392.1'
127.0.0.1 - - [28/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39508
self.closeSec=1695889199, self.tradeDate='20230928', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26405.0, self.close=26395.0, self.high=26418.1, self.low=26391.5, self.vol=1105.643, self.amt=29190145.4985 
127.0.0.1 - - [28/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-28 16:20:06,367:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230928   155500    155959  ...         0.0        0.0       0
5952  20230928   160000    160459  ...         0.0        0.0       0
5953  20230928   160500    160959  ...         0.0        0.0       0
5954  20230928   161000    161459  ...         0.0        0.0       0
5955  20230928   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 16:20:06,372:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695889199, self.tradeDate='20230928', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26405.0, self.close=26395.0, self.high=26418.1, self.low=26391.5, self.vol=1105.643, self.amt=29190145.4985, ukdf['pct'].iloc[-1]=-0.000477 , ukdf['amount'].iloc[-1]=29190145.4985, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-16802.97239448503', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26391.58966117', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [28/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39509
self.closeSec=1695889499, self.tradeDate='20230928', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26392.1, self.close=26401.0, self.high=26401.0, self.low=26386.0, self.vol=562.744, self.amt=14851725.9321 
2023-09-28 16:25:00,827:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230928   160000    160459  ...         0.0        0.0       0
5953  20230928   160500    160959  ...         0.0        0.0       0
5954  20230928   161000    161459  ...         0.0        0.0       0
5955  20230928   161500    161959  ...         0.0        0.0       0
5956  20230928   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-28 16:25:00,828:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695889499, self.tradeDate='20230928', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26392.1, self.close=26401.0, self.high=26401.0, self.low=26386.0, self.vol=562.744, self.amt=14851725.9321, ukdf['pct'].iloc[-1]=0.000227 , ukdf['amount'].iloc[-1]=14851725.9321, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-16342.04', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26404', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230928   040000    075959  1695859199  ...    721  0.066771 -1.337522    -1.0
722  20230928   080000    115959  1695873599  ...    722  0.065406 -1.331945    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-11016.685449682', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26365.9518845', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [28/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=823
self.closeSec=1695887999, self.tradeDate='20230928', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26363.9, self.close=26445.7, self.high=26496.7, self.low=26331.3, self.vol=28672.219, self.amt=757853177.3268 
2023-09-28 16:00:01,543:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695887999, self.tradeDate='20230928', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26363.9, self.close=26445.7, self.high=26496.7, self.low=26331.3, self.vol=28672.219, self.amt=757853177.3268 
2023-09-28 16:00:01,555:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230927   200000    235959  ...  148743.729  3.936224e+09 -0.017249
720  20230928   000000    035959  ...   42907.809  1.125090e+09 -0.001438
721  20230928   040000    075959  ...   22069.030  5.802622e+08  0.003965
722  20230928   080000    115959  ...   49939.097  1.319449e+09  0.000156
723  20230928   120000    155959  ...   28672.219  7.578532e+08  0.003107

[5 rows x 11 columns]
2023-09-28 16:00:02,280:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230927   200000    235959  1695830399  ...    719  0.070100 -1.344874    -1.0
720  20230928   000000    035959  1695844799  ...    720  0.074724 -1.326279    -1.0
721  20230928   040000    075959  1695859199  ...    721  0.066771 -1.337522    -1.0
722  20230928   080000    115959  1695873599  ...    722  0.065406 -1.331945    -1.0
723  20230928   120000    155959  1695887999  ...    723  0.065127 -1.322621    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-15064.3808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26445.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


