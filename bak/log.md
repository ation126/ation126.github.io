# 20230822 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28756
self.closeSec=1692663599, self.tradeDate='20230822', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26118.0, self.close=26101.1, self.high=26122.2, self.low=26101.1, self.vol=212.624, self.amt=5551930.8861 
127.0.0.1 - - [22/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-22 08:20:04,581:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230822   075500    075959  ...         0.0        0.0       0
5844  20230822   080000    080459  ...         0.0        0.0       0
5845  20230822   080500    080959  ...         0.0        0.0       0
5846  20230822   081000    081459  ...         0.0        0.0       0
5847  20230822   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 08:20:04,587:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692663599, self.tradeDate='20230822', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26118.0, self.close=26101.1, self.high=26122.2, self.low=26101.1, self.vol=212.624, self.amt=5551930.8861, ukdf['pct'].iloc[-1]=-0.000651 , ukdf['amount'].iloc[-1]=5551930.8861, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10610.2194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26103', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28757
self.closeSec=1692663899, self.tradeDate='20230822', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26101.1, self.close=26092.9, self.high=26109.2, self.low=26077.1, self.vol=1254.503, self.amt=32735815.573 
2023-08-22 08:25:00,793:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230822   080000    080459  ...         0.0        0.0       0
5845  20230822   080500    080959  ...         0.0        0.0       0
5846  20230822   081000    081459  ...         0.0        0.0       0
5847  20230822   081500    081959  ...         0.0        0.0       0
5848  20230822   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 08:25:00,793:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692663899, self.tradeDate='20230822', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26101.1, self.close=26092.9, self.high=26109.2, self.low=26077.1, self.vol=1254.503, self.amt=32735815.573, ukdf['pct'].iloc[-1]=-0.000314 , ukdf['amount'].iloc[-1]=32735815.573, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10699.87039701558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26096.56232967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28754 

self.closeSec=1692662399, self.tradeDate='20230822', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26103.9, self.close=26115.4, self.high=26116.4, self.low=26103.9 
127.0.0.1 - - [22/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28755 

self.closeSec=1692662699, self.tradeDate='20230822', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26115.4, self.close=26120.6, self.high=26128.2, self.low=26115.4 
127.0.0.1 - - [22/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28756 

self.closeSec=1692662999, self.tradeDate='20230822', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26120.7, self.close=26116.3, self.high=26120.7, self.low=26102.2 
127.0.0.1 - - [22/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28757 

self.closeSec=1692663299, self.tradeDate='20230822', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26116.2, self.close=26118.1, self.high=26128.0, self.low=26116.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28758 

self.closeSec=1692663599, self.tradeDate='20230822', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26118.0, self.close=26101.1, self.high=26122.2, self.low=26101.1 
127.0.0.1 - - [22/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28759 

self.closeSec=1692663899, self.tradeDate='20230822', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26101.1, self.close=26092.9, self.high=26109.2, self.low=26077.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-22 08:00:17,425:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230822    052959  26092.8  ...  47.500000  0.495767  0.486823
5770  20230822    055959  26106.5  ...  47.500000  0.515967  0.467979
5771  20230822    062959  26182.1  ...  47.083333  0.506937  0.454961
5772  20230822    065959  26149.2  ...  47.083333  0.498628  0.447075
5773  20230822    072959  26118.4  ...  47.083333  0.496437  0.440839

[5 rows x 33 columns]
0.5444444444444444
acc is : 0.5444444444444444
2023-08-22 08:00:17,488:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.505613  0.494387       1  ...  1.087439  -1.0    0.0  0.890726
536     0  0.528892  0.471108       0  ...  1.088805  -1.0    0.0  0.889607
537     1  0.485092  0.514908       0  ...  1.090083  -1.0    0.0  0.888562
538     1  0.484161  0.515839       0  ...  1.090421  -1.0    0.0  0.888287
539     1  0.490552  0.509448       1  ...  1.090208  -1.0    0.0  0.888460

[5 rows x 10 columns]
2023-08-22 08:00:17,500:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506398  0.493602       1  ...  1.087439  -1.0    0.0  0.888221
46     0  0.529550  0.470450       0  ...  1.088805  -1.0    0.0  0.887828
47     1  0.485602  0.514398       0  ...  1.090083  -1.0    0.0  0.887629
48     1  0.484189  0.515811       0  ...  1.090421  -1.0    0.0  0.887517
49     1  0.490552  0.509448       1  ...  1.090208  -1.0    0.0  0.888460

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '-1535.43783317895', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26119.30621795', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14375 

self.closeSec=1692660599, self.tradeDate='20230822', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26140.7', self.close='26110.3'
127.0.0.1 - - [22/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14376 

self.closeSec=1692661199, self.tradeDate='20230822', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26110.4', self.close='26107.8'
127.0.0.1 - - [22/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14377 

self.closeSec=1692661799, self.tradeDate='20230822', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26107.8', self.close='26110.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14378 

self.closeSec=1692662399, self.tradeDate='20230822', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26110.4', self.close='26115.4'
127.0.0.1 - - [22/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14379 

self.closeSec=1692662999, self.tradeDate='20230822', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26115.4', self.close='26116.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14380 

self.closeSec=1692663599, self.tradeDate='20230822', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26116.2', self.close='26101.1'
127.0.0.1 - - [22/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14378 

self.closeSec=1692660599, self.tradeDate='20230822', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26140.7', self.close='26110.3'
127.0.0.1 - - [22/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [22/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14379 

self.closeSec=1692661199, self.tradeDate='20230822', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26110.4', self.close='26107.8'
127.0.0.1 - - [22/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14380 

self.closeSec=1692661799, self.tradeDate='20230822', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26107.8', self.close='26110.5'
127.0.0.1 - - [22/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14381 

self.closeSec=1692662399, self.tradeDate='20230822', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26110.4', self.close='26115.4'
127.0.0.1 - - [22/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14382 

self.closeSec=1692662999, self.tradeDate='20230822', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26115.4', self.close='26116.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14383 

self.closeSec=1692663599, self.tradeDate='20230822', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26116.2', self.close='26101.1'
127.0.0.1 - - [22/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14378 

self.closeSec=1692660599, self.tradeDate='20230822', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26140.7', self.close='26110.3'
127.0.0.1 - - [22/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14379 

self.closeSec=1692661199, self.tradeDate='20230822', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26110.4', self.close='26107.8'

--handleKline--:  127.0.0.1 - - [22/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14380 

self.closeSec=1692661799, self.tradeDate='20230822', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26107.8', self.close='26110.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14381 

self.closeSec=1692662399, self.tradeDate='20230822', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26110.4', self.close='26115.4'
127.0.0.1 - - [22/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14382 

self.closeSec=1692662999, self.tradeDate='20230822', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26115.4', self.close='26116.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14383 

self.closeSec=1692663599, self.tradeDate='20230822', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26116.2', self.close='26101.1'
127.0.0.1 - - [22/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28756
self.closeSec=1692663599, self.tradeDate='20230822', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26118.0, self.close=26101.1, self.high=26122.2, self.low=26101.1, self.vol=212.624, self.amt=5551930.8861 
127.0.0.1 - - [22/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-22 08:20:04,596:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230822   075500    075959  ...         0.0        0.0       0
5844  20230822   080000    080459  ...         0.0        0.0       0
5845  20230822   080500    080959  ...         0.0        0.0       0
5846  20230822   081000    081459  ...         0.0        0.0       0
5847  20230822   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 08:20:04,604:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692663599, self.tradeDate='20230822', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26118.0, self.close=26101.1, self.high=26122.2, self.low=26101.1, self.vol=212.624, self.amt=5551930.8861, ukdf['pct'].iloc[-1]=-0.000651 , ukdf['amount'].iloc[-1]=5551930.8861, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27521.481', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26103', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28757
self.closeSec=1692663899, self.tradeDate='20230822', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26101.1, self.close=26092.9, self.high=26109.2, self.low=26077.1, self.vol=1254.503, self.amt=32735815.573 
2023-08-22 08:25:00,792:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230822   080000    080459  ...         0.0        0.0       0
5845  20230822   080500    080959  ...         0.0        0.0       0
5846  20230822   081000    081459  ...         0.0        0.0       0
5847  20230822   081500    081959  ...         0.0        0.0       0
5848  20230822   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-22 08:25:00,792:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692663899, self.tradeDate='20230822', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26101.1, self.close=26092.9, self.high=26109.2, self.low=26077.1, self.vol=1254.503, self.amt=32735815.573, ukdf['pct'].iloc[-1]=-0.000314 , ukdf['amount'].iloc[-1]=32735815.573, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27760.58251372653', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26096.56232967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230821   200000    235959  1692633599  ...    719  0.088583 -0.907845    -1.0
720  20230822   000000    035959  1692647999  ...    720  0.002066 -1.101779    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '171826.0556', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26088.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [22/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=599
self.closeSec=1692662399, self.tradeDate='20230822', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26086.2, self.close=26115.4, self.high=26280.0, self.low=26067.5, self.vol=24701.899, self.amt=645883179.97024 
2023-08-22 08:00:01,509:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692662399, self.tradeDate='20230822', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26086.2, self.close=26115.4, self.high=26280.0, self.low=26067.5, self.vol=24701.899, self.amt=645883179.97024 
2023-08-22 08:00:01,527:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230821   120000    155959  ...  32357.559  8.432335e+08 -0.002481
718  20230821   160000    195959  ...  43891.556  1.140098e+09  0.000338
719  20230821   200000    235959  ...  78006.038  2.027997e+09 -0.003674
720  20230822   000000    035959  ...  34319.441  8.935149e+08  0.006210
721  20230822   040000    075959  ...  24701.899  6.458832e+08  0.001119

[5 rows x 11 columns]
2023-08-22 08:00:02,460:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230821   120000    155959  1692604799  ...    717  0.306959 -0.414992     NaN
718  20230821   160000    195959  1692619199  ...    718  0.217729 -0.616238    -1.0
719  20230821   200000    235959  1692633599  ...    719  0.088583 -0.907845    -1.0
720  20230822   000000    035959  1692647999  ...    720  0.002066 -1.101779    -1.0
721  20230822   040000    075959  1692662399  ...    721  0.187173 -0.684183    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '170464.2736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26115.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


