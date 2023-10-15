# 20231015 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44404
self.closeSec=1697357999, self.tradeDate='20231015', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26874.5, self.close=26876.6, self.high=26876.7, self.low=26874.5, self.vol=78.861, self.amt=2119370.6305 
127.0.0.1 - - [15/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-15 16:20:09,315:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231015   155500    155959  ...         0.0        0.0       0
5952  20231015   160000    160459  ...         0.0        0.0       0
5953  20231015   160500    160959  ...         0.0        0.0       0
5954  20231015   161000    161459  ...         0.0        0.0       0
5955  20231015   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 16:20:09,334:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697357999, self.tradeDate='20231015', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26874.5, self.close=26876.6, self.high=26876.7, self.low=26874.5, self.vol=78.861, self.amt=2119370.6305, ukdf['pct'].iloc[-1]=7.8e-05 , ukdf['amount'].iloc[-1]=2119370.6305, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-164.3268', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26876.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44405
self.closeSec=1697358299, self.tradeDate='20231015', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26876.6, self.close=26868.7, self.high=26876.7, self.low=26868.5, self.vol=124.854, self.amt=3355076.2819 
127.0.0.1 - - [15/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-15 16:25:02,981:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231015   160000    160459  ...         0.0        0.0       0
5953  20231015   160500    160959  ...         0.0        0.0       0
5954  20231015   161000    161459  ...         0.0        0.0       0
5955  20231015   161500    161959  ...         0.0        0.0       0
5956  20231015   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 16:25:02,984:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697358299, self.tradeDate='20231015', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26876.6, self.close=26868.7, self.high=26876.7, self.low=26868.5, self.vol=124.854, self.amt=3355076.2819, ukdf['pct'].iloc[-1]=-0.000294 , ukdf['amount'].iloc[-1]=3355076.2819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-71.80737104244', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26870.05635294', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [15/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44402 

self.closeSec=1697356799, self.tradeDate='20231015', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26867.6, self.close=26872.7, self.high=26872.7, self.low=26867.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44403 

self.closeSec=1697357099, self.tradeDate='20231015', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26872.7, self.close=26889.9, self.high=26890.0, self.low=26872.6 
127.0.0.1 - - [15/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44404 

self.closeSec=1697357399, self.tradeDate='20231015', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26889.9, self.close=26888.0, self.high=26890.0, self.low=26885.5 
127.0.0.1 - - [15/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [15/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44405 

self.closeSec=1697357699, self.tradeDate='20231015', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26888.0, self.close=26874.5, self.high=26888.1, self.low=26871.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44406 

self.closeSec=1697357999, self.tradeDate='20231015', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26874.5, self.close=26876.6, self.high=26876.7, self.low=26874.5 
127.0.0.1 - - [15/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44407 

self.closeSec=1697358299, self.tradeDate='20231015', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26876.6, self.close=26868.7, self.high=26876.7, self.low=26868.5 
127.0.0.1 - - [15/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-15 16:00:17,713:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231015    132959  26873.2  ...  50.833333  0.506969  0.544024
5786  20231015    135959  26873.8  ...  50.416667  0.504370  0.535871
5787  20231015    142959  26868.4  ...  50.000000  0.502230  0.530041
5788  20231015    145959  26864.1  ...  50.000000  0.504424  0.522779
5789  20231015    152959  26868.5  ...  49.583333  0.502615  0.517458

[5 rows x 33 columns]
0.5627306273062731
acc is : 0.5627306273062731
2023-10-15 16:00:17,773:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.496046  0.503954       0  ...  0.919543   1.0    0.0  0.984295
538     1  0.492821  0.507179       0  ...  0.919393   1.0    0.0  0.984134
539     1  0.493327  0.506673       1  ...  0.919547   1.0    0.0  0.984299
540     1  0.496168  0.503832       0  ...  0.919423   1.0    0.0  0.984167
541     1  0.493684  0.506316       1  ...  0.919690   1.0    0.0  0.984453

[5 rows x 10 columns]
2023-10-15 16:00:17,785:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495824  0.504176       0  ...  0.953143   1.0    0.0  0.980838
46     1  0.492428  0.507572       0  ...  0.952987   1.0    0.0  0.979259
47     1  0.493024  0.506976       1  ...  0.953147   1.0    0.0  0.980173
48     1  0.496030  0.503970       0  ...  0.953019   1.0    0.0  0.982148
49     1  0.493684  0.506316       1  ...  0.919690   1.0    0.0  0.984453

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.627', 'enterprice': '27009.6', 'countrevence': '0', 'unrealprofit': '-3182.5569', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26874.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22199 

self.closeSec=1697354999, self.tradeDate='20231015', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26862.4', self.close='26864.9'
127.0.0.1 - - [15/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22200 

self.closeSec=1697355599, self.tradeDate='20231015', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26864.9', self.close='26867'
127.0.0.1 - - [15/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22201 

self.closeSec=1697356199, self.tradeDate='20231015', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26867', self.close='26864'
127.0.0.1 - - [15/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22202 

self.closeSec=1697356799, self.tradeDate='20231015', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26863.9', self.close='26872.7'
127.0.0.1 - - [15/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22203 

self.closeSec=1697357399, self.tradeDate='20231015', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26872.7', self.close='26888'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22204 

self.closeSec=1697357999, self.tradeDate='20231015', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26888', self.close='26876.6'
127.0.0.1 - - [15/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22202 

self.closeSec=1697354999, self.tradeDate='20231015', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26862.4', self.close='26864.9'
127.0.0.1 - - [15/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22203 

self.closeSec=1697355599, self.tradeDate='20231015', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26864.9', self.close='26867'
127.0.0.1 - - [15/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22204 

self.closeSec=1697356199, self.tradeDate='20231015', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26867', self.close='26864'
127.0.0.1 - - [15/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22205 

self.closeSec=1697356799, self.tradeDate='20231015', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26863.9', self.close='26872.7'
127.0.0.1 - - [15/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22206 

self.closeSec=1697357399, self.tradeDate='20231015', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26872.7', self.close='26888'
127.0.0.1 - - [15/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22207 

self.closeSec=1697357999, self.tradeDate='20231015', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26888', self.close='26876.6'
127.0.0.1 - - [15/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22202 

self.closeSec=1697354999, self.tradeDate='20231015', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26862.4', self.close='26864.9'
127.0.0.1 - - [15/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22203 

self.closeSec=1697355599, self.tradeDate='20231015', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26864.9', self.close='26867'
127.0.0.1 - - [15/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22204 

self.closeSec=1697356199, self.tradeDate='20231015', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26867', self.close='26864'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22205 

self.closeSec=1697356799, self.tradeDate='20231015', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26863.9', self.close='26872.7'
127.0.0.1 - - [15/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22206 

self.closeSec=1697357399, self.tradeDate='20231015', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26872.7', self.close='26888'
127.0.0.1 - - [15/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22207 

self.closeSec=1697357999, self.tradeDate='20231015', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26888', self.close='26876.6'
127.0.0.1 - - [15/Oct/2023 16:20:07] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44404
self.closeSec=1697357999, self.tradeDate='20231015', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26874.5, self.close=26876.6, self.high=26876.7, self.low=26874.5, self.vol=78.861, self.amt=2119370.6305 
127.0.0.1 - - [15/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -
2023-10-15 16:20:09,326:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231015   155500    155959  ...         0.0        0.0       0
5952  20231015   160000    160459  ...         0.0        0.0       0
5953  20231015   160500    160959  ...         0.0        0.0       0
5954  20231015   161000    161459  ...         0.0        0.0       0
5955  20231015   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 16:20:09,345:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697357999, self.tradeDate='20231015', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26874.5, self.close=26876.6, self.high=26876.7, self.low=26874.5, self.vol=78.861, self.amt=2119370.6305, ukdf['pct'].iloc[-1]=7.8e-05 , ukdf['amount'].iloc[-1]=2119370.6305, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '1214.5107', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26876.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44405
self.closeSec=1697358299, self.tradeDate='20231015', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26876.6, self.close=26868.7, self.high=26876.7, self.low=26868.5, self.vol=124.854, self.amt=3355076.2819 
127.0.0.1 - - [15/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-15 16:25:02,981:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231015   160000    160459  ...         0.0        0.0       0
5953  20231015   160500    160959  ...         0.0        0.0       0
5954  20231015   161000    161459  ...         0.0        0.0       0
5955  20231015   161500    161959  ...         0.0        0.0       0
5956  20231015   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 16:25:02,985:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697358299, self.tradeDate='20231015', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26876.6, self.close=26868.7, self.high=26876.7, self.low=26868.5, self.vol=124.854, self.amt=3355076.2819, ukdf['pct'].iloc[-1]=-0.000294 , ukdf['amount'].iloc[-1]=3355076.2819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '967.75900454454', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26870.05635294', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231014   200000    235959  ...  13269.386  3.567311e+08  0.002573
720  20231015   000000    035959  ...  12978.954  3.489274e+08 -0.002889
721  20231015   040000    075959  ...  12128.808  3.253471e+08 -0.000559
722  20231015   080000    115959  ...  10724.887  2.880777e+08  0.001304
723  20231015   120000    155959  ...   4448.772  1.195294e+08  0.000048

[5 rows x 11 columns]
2023-10-15 16:00:02,302:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231014   200000    235959  1697299199  ...    719  0.799389  0.627588     1.0
720  20231015   000000    035959  1697313599  ...    720  0.656992  0.225374     NaN
721  20231015   040000    075959  1697327999  ...    721  0.550053 -0.076009     NaN
722  20231015   080000    115959  1697342399  ...    722  0.450608 -0.355997     NaN
723  20231015   120000    155959  1697356799  ...    723  0.155730 -1.188482    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '2159.3326', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26872.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '2159.3326', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26872.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-15 16:00:09,172:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1269531.4533979', 'total': '1269531.4533979', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-15 16:00:09,641:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 47.100, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '43008F1697356809638I0L65'}
2023-10-15 16:00:09,669:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:10151600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20231015, closeTime:155959, close:26872.7, sign:-1, total:1269531.4533979, side:sell  
127.0.0.1 - - [15/Oct/2023 16:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 16:00:09] "POST / HTTP/1.1" 200 -
2023-10-15 16:00:09,674:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43007F1697356804085I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697356804483477, 'quantity': '47.147', 'price': '26872.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697356803144, 'updatetime': 1697356804483, 'tradetype': 'usdt', 'selfid': 43007, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697356804483, 'clientorderid': '43007F1697356804085I0L65', 'price': '26872.6', 'quantity': '47.147', 'commission': '1266.9624722', 'commissionasset': 'USDT', 'tradetime': 1697356804483, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697356804483}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-15 16:00:09,674:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43007F1697356804085I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697356804483477, 'quantity': '47.147', 'price': '26872.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697356803144, 'updatetime': 1697356804483, 'tradetype': 'usdt', 'selfid': 43007, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697356804483, 'clientorderid': '43007F1697356804085I0L65', 'price': '26872.6', 'quantity': '47.147', 'commission': '1266.9624722', 'commissionasset': 'USDT', 'tradetime': 1697356804483, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697356804483}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Oct/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-10-15 16:00:10,140:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43008F1697356809638I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697356810095204, 'quantity': '47.1', 'price': '26874.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697356809184, 'updatetime': 1697356810095, 'tradetype': 'usdt', 'selfid': 43008, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697356810095, 'clientorderid': '43008F1697356809638I0L65', 'price': '26874.8', 'quantity': '47.1', 'commission': '1265.80308', 'commissionasset': 'USDT', 'tradetime': 1697356810095, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697356810095}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-15 16:00:10,264:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43008F1697356809638I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697356810095204, 'quantity': '47.1', 'price': '26874.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697356809184, 'updatetime': 1697356810095, 'tradetype': 'usdt', 'selfid': 43008, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697356810095, 'clientorderid': '43008F1697356809638I0L65', 'price': '26874.8', 'quantity': '47.1', 'commission': '1265.80308', 'commissionasset': 'USDT', 'tradetime': 1697356810095, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697356810095}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Oct/2023 16:00:10] "POST / HTTP/1.1" 200 -


