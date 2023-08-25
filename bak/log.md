# 20230825 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29716
self.closeSec=1692951599, self.tradeDate='20230825', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26027.9, self.close=26039.7, self.high=26039.8, self.low=26025.5, self.vol=467.878, self.amt=12180553.2012 
127.0.0.1 - - [25/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-25 16:20:05,157:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230825   155500    155959  ...         0.0        0.0       0
5940  20230825   160000    160459  ...         0.0        0.0       0
5941  20230825   160500    160959  ...         0.0        0.0       0
5942  20230825   161000    161459  ...         0.0        0.0       0
5943  20230825   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 16:20:05,164:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692951599, self.tradeDate='20230825', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26027.9, self.close=26039.7, self.high=26039.8, self.low=26025.5, self.vol=467.878, self.amt=12180553.2012, ukdf['pct'].iloc[-1]=0.000453 , ukdf['amount'].iloc[-1]=12180553.2012, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11470.17369660954', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26041.24829121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29717
self.closeSec=1692951899, self.tradeDate='20230825', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26039.7, self.close=26058.2, self.high=26067.0, self.low=26039.6, self.vol=986.461, self.amt=25700197.5741 
2023-08-25 16:25:00,869:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230825   160000    160459  ...         0.0        0.0       0
5941  20230825   160500    160959  ...         0.0        0.0       0
5942  20230825   161000    161459  ...         0.0        0.0       0
5943  20230825   161500    161959  ...         0.0        0.0       0
5944  20230825   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 16:25:00,869:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692951899, self.tradeDate='20230825', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26039.7, self.close=26058.2, self.high=26067.0, self.low=26039.6, self.vol=986.461, self.amt=25700197.5741, ukdf['pct'].iloc[-1]=0.00071 , ukdf['amount'].iloc[-1]=25700197.5741, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11196.06714193704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26060.93136996', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29714 

self.closeSec=1692950399, self.tradeDate='20230825', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25982.3, self.close=25969.4, self.high=25982.3, self.low=25960.0 
127.0.0.1 - - [25/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29715 

self.closeSec=1692950699, self.tradeDate='20230825', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25969.4, self.close=26019.9, self.high=26020.6, self.low=25968.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29716 

self.closeSec=1692950999, self.tradeDate='20230825', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26020.1, self.close=26018.1, self.high=26028.9, self.low=26005.9 
127.0.0.1 - - [25/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29717 

self.closeSec=1692951299, self.tradeDate='20230825', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26018.1, self.close=26027.9, self.high=26031.0, self.low=26014.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29718 

self.closeSec=1692951599, self.tradeDate='20230825', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26027.9, self.close=26039.7, self.high=26039.8, self.low=26025.5 
127.0.0.1 - - [25/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29719 

self.closeSec=1692951899, self.tradeDate='20230825', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26039.7, self.close=26058.2, self.high=26067.0, self.low=26039.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-25 16:00:17,477:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230825    132959  26013.8  ...  50.416667  0.467698  0.653826
5786  20230825    135959  26045.6  ...  50.416667  0.467562  0.656836
5787  20230825    142959  26045.0  ...  50.416667  0.463489  0.661336
5788  20230825    145959  26027.4  ...  50.416667  0.458311  0.667687
5789  20230825    152959  26004.7  ...  50.416667  0.468491  0.670001

[5 rows x 33 columns]
0.522140221402214
acc is : 0.522140221402214
2023-08-25 16:00:17,550:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.486341  0.513659       0  ...  1.052685  -1.0    0.0  0.888477
538     1  0.480586  0.519414       0  ...  1.053400  -1.0    0.0  0.887873
539     1  0.467155  0.532845       0  ...  1.054311  -1.0    0.0  0.887106
540     1  0.464969  0.535031       1  ...  1.052778  -1.0    0.0  0.888395
541     1  0.494899  0.505101       0  ...  1.055737  -1.0    0.0  0.885898

[5 rows x 10 columns]
2023-08-25 16:00:17,563:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486289  0.513711       0  ...  1.052685  -1.0    0.0  0.887366
46     1  0.480632  0.519368       0  ...  1.053400  -1.0    0.0  0.888092
47     1  0.467160  0.532840       0  ...  1.054311  -1.0    0.0  0.886728
48     1  0.465068  0.534932       1  ...  1.052778  -1.0    0.0  0.889029
49     1  0.494899  0.505101       0  ...  1.055737  -1.0    0.0  0.885898

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '12221.42776454033', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25969.09192857', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14855 

self.closeSec=1692948599, self.tradeDate='20230825', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26029.9', self.close='26042.6'
127.0.0.1 - - [25/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14856 

self.closeSec=1692949199, self.tradeDate='20230825', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26042.6', self.close='26020.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14857 

127.0.0.1 - - [25/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
self.closeSec=1692949799, self.tradeDate='20230825', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26020.7', self.close='25980.1'
127.0.0.1 - - [25/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14858 

self.closeSec=1692950399, self.tradeDate='20230825', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25980.1', self.close='25969.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14859 

self.closeSec=1692950999, self.tradeDate='20230825', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25969.4', self.close='26018.1'
127.0.0.1 - - [25/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14860 

self.closeSec=1692951599, self.tradeDate='20230825', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26018.1', self.close='26039.7'
127.0.0.1 - - [25/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [25/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14858 

self.closeSec=1692948599, self.tradeDate='20230825', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26029.9', self.close='26042.6'

--handleKline--: 127.0.0.1 - - [25/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14859 

self.closeSec=1692949199, self.tradeDate='20230825', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26042.6', self.close='26020.7'
127.0.0.1 - - [25/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14860 

self.closeSec=1692949799, self.tradeDate='20230825', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26020.7', self.close='25980.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14861 

self.closeSec=1692950399, self.tradeDate='20230825', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25980.1', self.close='25969.4'
127.0.0.1 - - [25/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14862 

self.closeSec=1692950999, self.tradeDate='20230825', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25969.4', self.close='26018.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14863 

self.closeSec=1692951599, self.tradeDate='20230825', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26018.1', self.close='26039.7'
127.0.0.1 - - [25/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14858 

self.closeSec=1692948599, self.tradeDate='20230825', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26029.9', self.close='26042.6'
127.0.0.1 - - [25/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14859 

self.closeSec=1692949199, self.tradeDate='20230825', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26042.6', self.close='26020.7'
127.0.0.1 - - [25/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14860 

self.closeSec=1692949799, self.tradeDate='20230825', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26020.7', self.close='25980.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14861 

self.closeSec=1692950399, self.tradeDate='20230825', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25980.1', self.close='25969.4'
127.0.0.1 - - [25/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14862 

self.closeSec=1692950999, self.tradeDate='20230825', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25969.4', self.close='26018.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14863 

self.closeSec=1692951599, self.tradeDate='20230825', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26018.1', self.close='26039.7'
127.0.0.1 - - [25/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29716
self.closeSec=1692951599, self.tradeDate='20230825', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26027.9, self.close=26039.7, self.high=26039.8, self.low=26025.5, self.vol=467.878, self.amt=12180553.2012 
127.0.0.1 - - [25/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-25 16:20:05,143:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230825   155500    155959  ...         0.0        0.0       0
5940  20230825   160000    160459  ...         0.0        0.0       0
5941  20230825   160500    160959  ...         0.0        0.0       0
5942  20230825   161000    161459  ...         0.0        0.0       0
5943  20230825   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 16:20:05,150:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692951599, self.tradeDate='20230825', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26027.9, self.close=26039.7, self.high=26039.8, self.low=26025.5, self.vol=467.878, self.amt=12180553.2012, ukdf['pct'].iloc[-1]=0.000453 , ukdf['amount'].iloc[-1]=12180553.2012, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29815.00121616939', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26041.24829121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29717
self.closeSec=1692951899, self.tradeDate='20230825', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26039.7, self.close=26058.2, self.high=26067.0, self.low=26039.6, self.vol=986.461, self.amt=25700197.5741 
2023-08-25 16:25:00,873:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230825   160000    160459  ...         0.0        0.0       0
5941  20230825   160500    160959  ...         0.0        0.0       0
5942  20230825   161000    161459  ...         0.0        0.0       0
5943  20230825   161500    161959  ...         0.0        0.0       0
5944  20230825   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 16:25:00,874:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692951899, self.tradeDate='20230825', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26039.7, self.close=26058.2, self.high=26067.0, self.low=26039.6, self.vol=986.461, self.amt=25700197.5741, ukdf['pct'].iloc[-1]=0.00071 , ukdf['amount'].iloc[-1]=25700197.5741, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29083.95198831564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26060.93136996', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230825   040000    075959  1692921599  ...    721  0.186231 -0.532023     NaN
722  20230825   080000    115959  1692935999  ...    722  0.188793 -0.508607     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '171502.3112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26095.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [25/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=619
self.closeSec=1692950399, self.tradeDate='20230825', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26095.2, self.close=25969.4, self.high=26102.9, self.low=25960.0, self.vol=28254.409, self.amt=735259853.0969 
2023-08-25 16:00:01,574:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692950399, self.tradeDate='20230825', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26095.2, self.close=25969.4, self.high=26102.9, self.low=25960.0, self.vol=28254.409, self.amt=735259853.0969 
2023-08-25 16:00:01,587:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230824   200000    235959  ...  100354.824  2.628388e+09 -0.016944
720  20230825   000000    035959  ...   68687.910  1.787758e+09  0.001470
721  20230825   040000    075959  ...   30501.019  7.950300e+08  0.005391
722  20230825   080000    115959  ...   21737.921  5.674885e+08 -0.002652
723  20230825   120000    155959  ...   28254.409  7.352599e+08 -0.004817

[5 rows x 11 columns]
2023-08-25 16:00:02,433:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230824   200000    235959  1692892799  ...    719  0.180320 -0.580225     NaN
720  20230825   000000    035959  1692907199  ...    720  0.182993 -0.556918     NaN
721  20230825   040000    075959  1692921599  ...    721  0.186231 -0.532023     NaN
722  20230825   080000    115959  1692935999  ...    722  0.188793 -0.508607     NaN
723  20230825   120000    155959  1692950399  ...    723  0.195809 -0.474029     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '177966.9216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25969.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


