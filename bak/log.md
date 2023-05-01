# 20230501 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44565
self.closeSec=1682900399, self.tradeDate='20230501', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29280.7, self.close=29267.9, self.high=29305.0, self.low=29267.9, self.vol=1446.499, self.amt=42372387.738 
127.0.0.1 - - [01/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-01 08:20:06,720:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230501   075500    075959  ...         0.0        0.0       0
5856  20230501   080000    080459  ...         0.0        0.0       0
5857  20230501   080500    080959  ...         0.0        0.0       0
5858  20230501   081000    081459  ...         0.0        0.0       0
5859  20230501   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 08:20:06,730:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682900399, self.tradeDate='20230501', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29280.7, self.close=29267.9, self.high=29305.0, self.low=29267.9, self.vol=1446.499, self.amt=42372387.738, ukdf['pct'].iloc[-1]=-0.000441 , ukdf['amount'].iloc[-1]=42372387.738, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-766612.152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29268.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44566
self.closeSec=1682900699, self.tradeDate='20230501', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29267.9, self.close=29283.0, self.high=29285.0, self.low=29260.0, self.vol=915.848, self.amt=26807954.7609 
127.0.0.1 - - [01/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-05-01 08:25:01,639:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230501   080000    080459  ...         0.0        0.0       0
5857  20230501   080500    080959  ...         0.0        0.0       0
5858  20230501   081000    081459  ...         0.0        0.0       0
5859  20230501   081500    081959  ...         0.0        0.0       0
5860  20230501   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 08:25:01,640:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682900699, self.tradeDate='20230501', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29267.9, self.close=29283.0, self.high=29285.0, self.low=29260.0, self.vol=915.848, self.amt=26807954.7609, ukdf['pct'].iloc[-1]=0.000516 , ukdf['amount'].iloc[-1]=26807954.7609, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-767538.3666640944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29284.1917619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45127 

self.closeSec=1682899199, self.tradeDate='20230501', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29294.0, self.close=29216.0, self.high=29294.0, self.low=29145.5 
127.0.0.1 - - [01/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45128 

self.closeSec=1682899499, self.tradeDate='20230501', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29223.0, self.close=29287.4, self.high=29287.4, self.low=29198.2 
127.0.0.1 - - [01/May/2023 08:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45129 

self.closeSec=1682899799, self.tradeDate='20230501', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29287.3, self.close=29298.4, self.high=29313.2, self.low=29266.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45130 

self.closeSec=1682900099, self.tradeDate='20230501', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29299.7, self.close=29280.8, self.high=29309.9, self.low=29257.7 
127.0.0.1 - - [01/May/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45131 

self.closeSec=1682900399, self.tradeDate='20230501', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29280.7, self.close=29267.9, self.high=29305.0, self.low=29267.9 
127.0.0.1 - - [01/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45132 

self.closeSec=1682900699, self.tradeDate='20230501', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29267.9, self.close=29283.0, self.high=29285.0, self.low=29260.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-01 08:00:18,457:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230501    052959  29314.9  ...  50.416667  0.532359  0.451765
5770  20230501    055959  29462.6  ...  50.000000  0.519917  0.463486
5771  20230501    062959  29399.7  ...  50.416667  0.521371  0.475323
5772  20230501    065959  29407.8  ...  50.416667  0.512540  0.491371
5773  20230501    072959  29363.2  ...  50.416667  0.515395  0.505433

[5 rows x 33 columns]
0.5611111111111111
acc is : 0.5611111111111111
2023-05-01 08:00:18,569:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.526754  0.473246       0  ...  0.828895  -1.0    0.0  1.003235
536     0  0.501332  0.498668       1  ...  0.828670  -1.0    0.0  1.003508
537     0  0.514062  0.485938       0  ...  0.829926  -1.0    0.0  1.001986
538     0  0.505540  0.494460       1  ...  0.829497  -1.0    0.0  1.002505
539     0  0.515257  0.484743       0  ...  0.834082  -1.0    0.0  0.996963

[5 rows x 10 columns]
2023-05-01 08:00:18,595:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526497  0.473503       0  ...  0.828895  -1.0    0.0  1.005194
46     0  0.501028  0.498972       1  ...  0.828670  -1.0    0.0  1.003737
47     0  0.514214  0.485786       0  ...  0.829926  -1.0    0.0  1.002280
48     0  0.505835  0.494165       1  ...  0.829497  -1.0    0.0  1.004613
49     0  0.515257  0.484743       0  ...  0.834082  -1.0    0.0  0.996963

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22561 

self.closeSec=1682897399, self.tradeDate='20230501', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29346.5', self.close='29378.4'
127.0.0.1 - - [01/May/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22562 

self.closeSec=1682897999, self.tradeDate='20230501', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29378.4', self.close='29396.4'
127.0.0.1 - - [01/May/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22563 

self.closeSec=1682898599, self.tradeDate='20230501', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29396.5', self.close='29306'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22564 

self.closeSec=1682899199, self.tradeDate='20230501', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29305.9', self.close='29216'
127.0.0.1 - - [01/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22565 

self.closeSec=1682899799, self.tradeDate='20230501', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29223', self.close='29298.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22566 

self.closeSec=1682900399, self.tradeDate='20230501', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29299.7', self.close='29268'
127.0.0.1 - - [01/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22562 

self.closeSec=1682897399, self.tradeDate='20230501', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29346.5', self.close='29378.4'
127.0.0.1 - - [01/May/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22563 

self.closeSec=1682897999, self.tradeDate='20230501', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29378.4', self.close='29396.4'
127.0.0.1 - - [01/May/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22564 

self.closeSec=1682898599, self.tradeDate='20230501', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29396.5', self.close='29306'
127.0.0.1 - - [01/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22565 

self.closeSec=1682899199, self.tradeDate='20230501', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29305.9', self.close='29216'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22566 

self.closeSec=1682899799, self.tradeDate='20230501', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29223', self.close='29298.4'
127.0.0.1 - - [01/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22567 

self.closeSec=1682900399, self.tradeDate='20230501', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29299.7', self.close='29268'
127.0.0.1 - - [01/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22562 

self.closeSec=1682897399, self.tradeDate='20230501', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29346.5', self.close='29378.4'
127.0.0.1 - - [01/May/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22563 

self.closeSec=1682897999, self.tradeDate='20230501', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29378.4', self.close='29396.4'
127.0.0.1 - - [01/May/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22564 

self.closeSec=1682898599, self.tradeDate='20230501', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29396.5', self.close='29306'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22565 

self.closeSec=1682899199, self.tradeDate='20230501', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29305.9', self.close='29216'
127.0.0.1 - - [01/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22566 

self.closeSec=1682899799, self.tradeDate='20230501', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29223', self.close='29298.4'
127.0.0.1 - - [01/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22567 

self.closeSec=1682900399, self.tradeDate='20230501', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29299.7', self.close='29268'
127.0.0.1 - - [01/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40563
self.closeSec=1682900399, self.tradeDate='20230501', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29280.7, self.close=29267.9, self.high=29305.0, self.low=29267.9, self.vol=1446.499, self.amt=42372387.738 
127.0.0.1 - - [01/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-01 08:20:06,778:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230501   075500    075959  ...         0.0        0.0       0
5856  20230501   080000    080459  ...         0.0        0.0       0
5857  20230501   080500    080959  ...         0.0        0.0       0
5858  20230501   081000    081459  ...         0.0        0.0       0
5859  20230501   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 08:20:06,790:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682900399, self.tradeDate='20230501', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29280.7, self.close=29267.9, self.high=29305.0, self.low=29267.9, self.vol=1446.499, self.amt=42372387.738, ukdf['pct'].iloc[-1]=-0.000441 , ukdf['amount'].iloc[-1]=42372387.738, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40564
self.closeSec=1682900699, self.tradeDate='20230501', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29267.9, self.close=29283.0, self.high=29285.0, self.low=29260.0, self.vol=915.848, self.amt=26807954.7609 
2023-05-01 08:25:01,638:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230501   080000    080459  ...         0.0        0.0       0
5857  20230501   080500    080959  ...         0.0        0.0       0
5858  20230501   081000    081459  ...         0.0        0.0       0
5859  20230501   081500    081959  ...         0.0        0.0       0
5860  20230501   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-01 08:25:01,639:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682900699, self.tradeDate='20230501', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29267.9, self.close=29283.0, self.high=29285.0, self.low=29260.0, self.vol=915.848, self.amt=26807954.7609, ukdf['pct'].iloc[-1]=0.000516 , ukdf['amount'].iloc[-1]=26807954.7609, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230430   200000    235959  1682870399  ...    719  0.001188 -1.987370    -1.0
720  20230501   000000    035959  1682884799  ...    720  0.001936 -1.943589    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '-19.02127060722', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29341.70715079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [01/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=940
self.closeSec=1682899199, self.tradeDate='20230501', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29346.0, self.close=29216.0, self.high=29471.0, self.low=29145.3, self.vol=75149.932, self.amt=2202845583.15159 
2023-05-01 08:00:01,847:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682899199, self.tradeDate='20230501', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29346.0, self.close=29216.0, self.high=29471.0, self.low=29145.3, self.vol=75149.932, self.amt=2202845583.15159 
2023-05-01 08:00:01,881:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230430   120000    155959  ...   24448.044  7.146395e+08  0.002880
718  20230430   160000    195959  ...   33318.971  9.743884e+08 -0.002304
719  20230430   200000    235959  ...  142401.479  4.216874e+09  0.015748
720  20230501   000000    035959  ...  117019.249  3.458024e+09 -0.010059
721  20230501   040000    075959  ...   75149.932  2.202846e+09 -0.004430

[5 rows x 11 columns]
2023-05-01 08:00:03,420:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230430   120000    155959  1682841599  ...    717  0.005092 -2.073333    -1.0
718  20230430   160000    195959  1682855999  ...    718  0.001353 -2.033160    -1.0
719  20230430   200000    235959  1682870399  ...    719  0.001188 -1.987370    -1.0
720  20230501   000000    035959  1682884799  ...    720  0.001936 -1.943589    -1.0
721  20230501   040000    075959  1682899199  ...    721  0.035905 -1.805191    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '5690.2524', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29219.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


