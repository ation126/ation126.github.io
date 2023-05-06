# 20230506 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46005
self.closeSec=1683332399, self.tradeDate='20230506', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29497.2, self.close=29502.6, self.high=29503.3, self.low=29482.5, self.vol=411.499, self.amt=12136589.1542 
127.0.0.1 - - [06/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-06 08:20:06,600:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230506   075500    075959  ...         0.0        0.0       0
5856  20230506   080000    080459  ...         0.0        0.0       0
5857  20230506   080500    080959  ...         0.0        0.0       0
5858  20230506   081000    081459  ...         0.0        0.0       0
5859  20230506   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 08:20:06,606:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683332399, self.tradeDate='20230506', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29497.2, self.close=29502.6, self.high=29503.3, self.low=29482.5, self.vol=411.499, self.amt=12136589.1542, ukdf['pct'].iloc[-1]=0.00018 , ukdf['amount'].iloc[-1]=12136589.1542, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-780753.512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29503.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46006
self.closeSec=1683332699, self.tradeDate='20230506', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29502.5, self.close=29570.1, self.high=29585.0, self.low=29502.5, self.vol=2019.544, self.amt=59671928.6331 
127.0.0.1 - - [06/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-05-06 08:25:02,101:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230506   080000    080459  ...         0.0        0.0       0
5857  20230506   080500    080959  ...         0.0        0.0       0
5858  20230506   081000    081459  ...         0.0        0.0       0
5859  20230506   081500    081959  ...         0.0        0.0       0
5860  20230506   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 08:25:02,103:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683332699, self.tradeDate='20230506', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29502.5, self.close=29570.1, self.high=29585.0, self.low=29502.5, self.vol=2019.544, self.amt=59671928.6331, ukdf['pct'].iloc[-1]=0.002288 , ukdf['amount'].iloc[-1]=59671928.6331, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-784820.81880948304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29571.39018229', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46567 

self.closeSec=1683331199, self.tradeDate='20230506', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29482.3, self.close=29491.5, self.high=29497.6, self.low=29476.8 
127.0.0.1 - - [06/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46568 

self.closeSec=1683331499, self.tradeDate='20230506', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29491.5, self.close=29480.7, self.high=29500.0, self.low=29460.0 
127.0.0.1 - - [06/May/2023 08:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46569 

self.closeSec=1683331799, self.tradeDate='20230506', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29480.7, self.close=29484.2, self.high=29494.0, self.low=29472.7 
127.0.0.1 - - [06/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46570 

self.closeSec=1683332099, self.tradeDate='20230506', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29484.1, self.close=29497.3, self.high=29506.6, self.low=29482.4 
127.0.0.1 - - [06/May/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46571 

self.closeSec=1683332399, self.tradeDate='20230506', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29497.2, self.close=29502.6, self.high=29503.3, self.low=29482.5 
127.0.0.1 - - [06/May/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [06/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46572 

self.closeSec=1683332699, self.tradeDate='20230506', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29502.5, self.close=29570.1, self.high=29585.0, self.low=29502.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-06 08:00:19,300:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230506    052959  29483.0  ...  52.083333  0.577782  0.315945
5770  20230506    055959  29511.1  ...  52.083333  0.570707  0.308393
5771  20230506    062959  29475.1  ...  52.083333  0.575043  0.299521
5772  20230506    065959  29504.6  ...  52.500000  0.585972  0.286568
5773  20230506    072959  29579.8  ...  52.083333  0.575286  0.277786

[5 rows x 33 columns]
0.5574074074074075
acc is : 0.5574074074074075
2023-05-06 08:00:19,409:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.504742  0.495258       0  ...  0.994698   1.0    0.0  1.077101
536     1  0.488475  0.511525       1  ...  0.995690   1.0    0.0  1.078176
537     1  0.490882  0.509118       1  ...  0.998231   1.0    0.0  1.080927
538     0  0.510645  0.489355       0  ...  0.996432   1.0    0.0  1.078980
539     1  0.483313  0.516687       0  ...  0.995248   1.0    0.0  1.077697

[5 rows x 10 columns]
2023-05-06 08:00:19,445:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505091  0.494909       0  ...  0.974397   1.0    0.0  1.081421
46     1  0.488549  0.511451       1  ...  0.975369   1.0    0.0  1.080280
47     1  0.491339  0.508661       1  ...  0.977858   1.0    0.0  1.091501
48     0  0.511011  0.488989       0  ...  0.996432   1.0    0.0  1.080282
49     1  0.483313  0.516687       0  ...  0.995248   1.0    0.0  1.077697

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23281 

self.closeSec=1683329399, self.tradeDate='20230506', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29535.3', self.close='29526.6'
127.0.0.1 - - [06/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23282 

self.closeSec=1683329999, self.tradeDate='20230506', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29526.6', self.close='29489'
127.0.0.1 - - [06/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23283 

self.closeSec=1683330599, self.tradeDate='20230506', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29488.9', self.close='29471.3'
127.0.0.1 - - [06/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23284 

self.closeSec=1683331199, self.tradeDate='20230506', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29471.2', self.close='29491.5'
127.0.0.1 - - [06/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23285 

self.closeSec=1683331799, self.tradeDate='20230506', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29491.5', self.close='29484.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23286 

self.closeSec=1683332399, self.tradeDate='20230506', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29484.1', self.close='29502.6'
127.0.0.1 - - [06/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23282 

self.closeSec=1683329399, self.tradeDate='20230506', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29535.3', self.close='29526.6'
127.0.0.1 - - [06/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23283 

self.closeSec=1683329999, self.tradeDate='20230506', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29526.6', self.close='29489'
127.0.0.1 - - [06/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23284 

self.closeSec=1683330599, self.tradeDate='20230506', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29488.9', self.close='29471.3'
127.0.0.1 - - [06/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23285 

self.closeSec=1683331199, self.tradeDate='20230506', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29471.2', self.close='29491.5'
127.0.0.1 - - [06/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23286 

self.closeSec=1683331799, self.tradeDate='20230506', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29491.5', self.close='29484.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23287 

self.closeSec=1683332399, self.tradeDate='20230506', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29484.1', self.close='29502.6'
127.0.0.1 - - [06/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23282 

self.closeSec=1683329399, self.tradeDate='20230506', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29535.3', self.close='29526.6'
127.0.0.1 - - [06/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23283 

self.closeSec=1683329999, self.tradeDate='20230506', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29526.6', self.close='29489'
127.0.0.1 - - [06/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23284 

self.closeSec=1683330599, self.tradeDate='20230506', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29488.9', self.close='29471.3'
127.0.0.1 - - [06/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23285 

self.closeSec=1683331199, self.tradeDate='20230506', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29471.2', self.close='29491.5'
127.0.0.1 - - [06/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23286 

self.closeSec=1683331799, self.tradeDate='20230506', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29491.5', self.close='29484.2'
127.0.0.1 - - [06/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23287 

self.closeSec=1683332399, self.tradeDate='20230506', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29484.1', self.close='29502.6'
127.0.0.1 - - [06/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42003
self.closeSec=1683332399, self.tradeDate='20230506', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29497.2, self.close=29502.6, self.high=29503.3, self.low=29482.5, self.vol=411.499, self.amt=12136589.1542 
127.0.0.1 - - [06/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-06 08:20:06,597:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230506   075500    075959  ...         0.0        0.0       0
5856  20230506   080000    080459  ...         0.0        0.0       0
5857  20230506   080500    080959  ...         0.0        0.0       0
5858  20230506   081000    081459  ...         0.0        0.0       0
5859  20230506   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 08:20:06,602:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683332399, self.tradeDate='20230506', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29497.2, self.close=29502.6, self.high=29503.3, self.low=29482.5, self.vol=411.499, self.amt=12136589.1542, ukdf['pct'].iloc[-1]=0.00018 , ukdf['amount'].iloc[-1]=12136589.1542, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [06/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42004
self.closeSec=1683332699, self.tradeDate='20230506', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29502.5, self.close=29570.1, self.high=29585.0, self.low=29502.5, self.vol=2019.544, self.amt=59671928.6331 
2023-05-06 08:25:02,100:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230506   080000    080459  ...         0.0        0.0       0
5857  20230506   080500    080959  ...         0.0        0.0       0
5858  20230506   081000    081459  ...         0.0        0.0       0
5859  20230506   081500    081959  ...         0.0        0.0       0
5860  20230506   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-06 08:25:02,102:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683332699, self.tradeDate='20230506', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29502.5, self.close=29570.1, self.high=29585.0, self.low=29502.5, self.vol=2019.544, self.amt=59671928.6331, ukdf['pct'].iloc[-1]=0.002288 , ukdf['amount'].iloc[-1]=59671928.6331, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230505   200000    235959  1683302399  ...    719  0.502555 -0.420950     NaN
720  20230506   000000    035959  1683316799  ...    720  0.555457 -0.254955     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '-9978.9648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29554.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [06/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=970
self.closeSec=1683331199, self.tradeDate='20230506', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29548.7, self.close=29491.5, self.high=29650.0, self.low=29440.0, self.vol=40781.438, self.amt=1203950677.0544 
2023-05-06 08:00:01,823:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683331199, self.tradeDate='20230506', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29548.7, self.close=29491.5, self.high=29650.0, self.low=29440.0, self.vol=40781.438, self.amt=1203950677.0544 
2023-05-06 08:00:01,881:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230505   120000    155959  ...   52721.949  1.537098e+09 -0.004386
718  20230505   160000    195959  ...   44104.482  1.282999e+09  0.002705
719  20230505   200000    235959  ...  192645.919  5.611956e+09  0.007200
720  20230506   000000    035959  ...  133203.275  3.931405e+09  0.006859
721  20230506   040000    075959  ...   40781.438  1.203951e+09 -0.001936

[5 rows x 11 columns]
2023-05-06 08:00:03,637:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230505   120000    155959  1683273599  ...    717  0.498481 -0.439408     NaN
718  20230505   160000    195959  1683287999  ...    718  0.483032 -0.484612     NaN
719  20230505   200000    235959  1683302399  ...    719  0.502555 -0.420950     NaN
720  20230506   000000    035959  1683316799  ...    720  0.555457 -0.254955     NaN
721  20230506   040000    075959  1683331199  ...    721  0.566793 -0.216533     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '-7137.47433911862', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29494.07782309', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


