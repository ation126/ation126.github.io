# 20230429 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43989
self.closeSec=1682727599, self.tradeDate='20230429', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29291.9, self.close=29291.1, self.high=29305.8, self.low=29287.9, self.vol=524.382, self.amt=15361398.5716 
127.0.0.1 - - [29/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-29 08:20:06,602:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230429   075500    075959  ...         0.0        0.0       0
5849  20230429   080000    080459  ...         0.0        0.0       0
5850  20230429   080500    080959  ...         0.0        0.0       0
5851  20230429   081000    081459  ...         0.0        0.0       0
5852  20230429   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 08:20:06,623:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682727599, self.tradeDate='20230429', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29291.9, self.close=29291.1, self.high=29305.8, self.low=29287.9, self.vol=524.382, self.amt=15361398.5716, ukdf['pct'].iloc[-1]=-2.4e-05 , ukdf['amount'].iloc[-1]=15361398.5716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-767960.0944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29291.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43990
self.closeSec=1682727899, self.tradeDate='20230429', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29291.1, self.close=29291.4, self.high=29315.0, self.low=29289.9, self.vol=614.971, self.amt=18016793.9023 
127.0.0.1 - - [29/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-04-29 08:25:02,122:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230429   080000    080459  ...         0.0        0.0       0
5850  20230429   080500    080959  ...         0.0        0.0       0
5851  20230429   081000    081459  ...         0.0        0.0       0
5852  20230429   081500    081959  ...         0.0        0.0       0
5853  20230429   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 08:25:02,122:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682727899, self.tradeDate='20230429', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29291.1, self.close=29291.4, self.high=29315.0, self.low=29289.9, self.vol=614.971, self.amt=18016793.9023, ukdf['pct'].iloc[-1]=1e-05 , ukdf['amount'].iloc[-1]=18016793.9023, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-768187.99655114064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29294.98725989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44551 

self.closeSec=1682726399, self.tradeDate='20230429', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29311.1, self.close=29300.0, self.high=29320.0, self.low=29291.1 
127.0.0.1 - - [29/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44552 

self.closeSec=1682726699, self.tradeDate='20230429', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29300.0, self.close=29307.6, self.high=29307.9, self.low=29292.6 
127.0.0.1 - - [29/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44553 

self.closeSec=1682726999, self.tradeDate='20230429', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29307.5, self.close=29301.2, self.high=29339.0, self.low=29301.2 
127.0.0.1 - - [29/Apr/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44554 

self.closeSec=1682727299, self.tradeDate='20230429', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29301.3, self.close=29291.8, self.high=29309.1, self.low=29285.1 
127.0.0.1 - - [29/Apr/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44555 

self.closeSec=1682727599, self.tradeDate='20230429', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29291.9, self.close=29291.1, self.high=29305.8, self.low=29287.9 
127.0.0.1 - - [29/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44556 

self.closeSec=1682727899, self.tradeDate='20230429', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29291.1, self.close=29291.4, self.high=29315.0, self.low=29289.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-29 08:00:22,903:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230429    052959  29322.3  ...  52.500000  0.523248  0.520887
5770  20230429    055959  29316.3  ...  52.083333  0.522469  0.510361
5771  20230429    062959  29310.1  ...  52.083333  0.529526  0.494632
5772  20230429    065959  29371.4  ...  51.666667  0.523847  0.484197
5773  20230429    072959  29327.3  ...  51.250000  0.518865  0.478183

[5 rows x 33 columns]
0.5518518518518518
acc is : 0.5518518518518518
2023-04-29 08:00:23,004:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.517214  0.482786       0  ...  0.807831  -1.0    0.0  0.995250
536     0  0.509484  0.490516       1  ...  0.806144  -1.0    0.0  0.997328
537     0  0.524532  0.475468       0  ...  0.807351  -1.0    0.0  0.995834
538     0  0.502680  0.497320       0  ...  0.808414  -1.0    0.0  0.994523
539     0  0.502303  0.497697       1  ...  0.808102  -1.0    0.0  0.994907

[5 rows x 10 columns]
2023-04-29 08:00:23,029:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518333  0.481667       0  ...  0.808481  -1.0    0.0  0.998760
46     0  0.509404  0.490596       1  ...  0.806793  -1.0    0.0  0.999024
47     0  0.524817  0.475183       0  ...  0.808001  -1.0    0.0  0.995810
48     0  0.502527  0.497473       0  ...  0.808414  -1.0    0.0  0.994141
49     0  0.502303  0.497697       1  ...  0.808102  -1.0    0.0  0.994907

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22273 

self.closeSec=1682724599, self.tradeDate='20230429', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29346.5', self.close='29288.7'
127.0.0.1 - - [29/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22274 

self.closeSec=1682725199, self.tradeDate='20230429', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29288.7', self.close='29305.4'
127.0.0.1 - - [29/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22275 

self.closeSec=1682725799, self.tradeDate='20230429', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29305.4', self.close='29307.3'
127.0.0.1 - - [29/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22276 

self.closeSec=1682726399, self.tradeDate='20230429', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29307.4', self.close='29300'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22277 

self.closeSec=1682726999, self.tradeDate='20230429', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29300', self.close='29301.2'
127.0.0.1 - - [29/Apr/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22278 

self.closeSec=1682727599, self.tradeDate='20230429', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29301.3', self.close='29291.1'
127.0.0.1 - - [29/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [29/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22274 

self.closeSec=1682724599, self.tradeDate='20230429', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29346.5', self.close='29288.7'
127.0.0.1 - - [29/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22275 

self.closeSec=1682725199, self.tradeDate='20230429', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29288.7', self.close='29305.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22276 

self.closeSec=1682725799, self.tradeDate='20230429', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29305.4', self.close='29307.3'
127.0.0.1 - - [29/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22277 

self.closeSec=1682726399, self.tradeDate='20230429', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29307.4', self.close='29300'
127.0.0.1 - - [29/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22278 

self.closeSec=1682726999, self.tradeDate='20230429', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29300', self.close='29301.2'
127.0.0.1 - - [29/Apr/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22279 

self.closeSec=1682727599, self.tradeDate='20230429', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29301.3', self.close='29291.1'
127.0.0.1 - - [29/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22274 

self.closeSec=1682724599, self.tradeDate='20230429', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29346.5', self.close='29288.7'
127.0.0.1 - - [29/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22275 

self.closeSec=1682725199, self.tradeDate='20230429', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29288.7', self.close='29305.4'
127.0.0.1 - - [29/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22276 

self.closeSec=1682725799, self.tradeDate='20230429', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29305.4', self.close='29307.3'
127.0.0.1 - - [29/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22277 

self.closeSec=1682726399, self.tradeDate='20230429', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29307.4', self.close='29300'
127.0.0.1 - - [29/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Apr/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22278 

self.closeSec=1682726999, self.tradeDate='20230429', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29300', self.close='29301.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22279 

self.closeSec=1682727599, self.tradeDate='20230429', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29301.3', self.close='29291.1'
127.0.0.1 - - [29/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39987
self.closeSec=1682727599, self.tradeDate='20230429', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29291.9, self.close=29291.1, self.high=29305.8, self.low=29287.9, self.vol=524.382, self.amt=15361398.5716 
127.0.0.1 - - [29/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-29 08:20:06,529:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230429   075500    075959  ...         0.0        0.0       0
5849  20230429   080000    080459  ...         0.0        0.0       0
5850  20230429   080500    080959  ...         0.0        0.0       0
5851  20230429   081000    081459  ...         0.0        0.0       0
5852  20230429   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 08:20:06,535:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682727599, self.tradeDate='20230429', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29291.9, self.close=29291.1, self.high=29305.8, self.low=29287.9, self.vol=524.382, self.amt=15361398.5716, ukdf['pct'].iloc[-1]=-2.4e-05 , ukdf['amount'].iloc[-1]=15361398.5716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [29/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39988
self.closeSec=1682727899, self.tradeDate='20230429', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29291.1, self.close=29291.4, self.high=29315.0, self.low=29289.9, self.vol=614.971, self.amt=18016793.9023 
2023-04-29 08:25:02,124:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230429   080000    080459  ...         0.0        0.0       0
5850  20230429   080500    080959  ...         0.0        0.0       0
5851  20230429   081000    081459  ...         0.0        0.0       0
5852  20230429   081500    081959  ...         0.0        0.0       0
5853  20230429   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-29 08:25:02,124:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682727899, self.tradeDate='20230429', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29291.1, self.close=29291.4, self.high=29315.0, self.low=29289.9, self.vol=614.971, self.amt=18016793.9023, ukdf['pct'].iloc[-1]=1e-05 , ukdf['amount'].iloc[-1]=18016793.9023, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230428   200000    235959  1682697599  ...    719  0.693585  0.086854     NaN
720  20230429   000000    035959  1682711999  ...    720  0.649444 -0.061526     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '17406.4659', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29320.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1352827.6996185002, self.flagDict['side']='buy', self.tradeCount=32, self.count=928
self.closeSec=1682726399, self.tradeDate='20230429', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29317.6, self.close=29300.0, self.high=29417.9, self.low=29250.0, self.vol=33331.207, self.amt=977662609.5933 
127.0.0.1 - - [29/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -
2023-04-29 08:00:03,197:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682726399, self.tradeDate='20230429', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29317.6, self.close=29300.0, self.high=29417.9, self.low=29250.0, self.vol=33331.207, self.amt=977662609.5933 
2023-04-29 08:00:03,247:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230428   120000    155959  ...   49552.737  1.460039e+09  0.002077
718  20230428   160000    195959  ...   86710.553  2.537331e+09 -0.008411
719  20230428   200000    235959  ...  170065.295  4.955369e+09 -0.003151
720  20230429   000000    035959  ...   89994.009  2.631370e+09  0.006305
721  20230429   040000    075959  ...   33331.207  9.776626e+08 -0.000600

[5 rows x 11 columns]
2023-04-29 08:00:04,962:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230428   120000    155959  1682668799  ...    717  0.759440  0.298279     NaN
718  20230428   160000    195959  1682683199  ...    718  0.722649  0.179516     NaN
719  20230428   200000    235959  1682697599  ...    719  0.693585  0.086854     NaN
720  20230429   000000    035959  1682711999  ...    720  0.649444 -0.061526     NaN
721  20230429   040000    075959  1682726399  ...    721  0.588055 -0.271519     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '16447.4964', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29300.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


