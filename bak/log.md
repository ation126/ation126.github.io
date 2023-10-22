# 20231022 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46324
self.closeSec=1697933999, self.tradeDate='20231022', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29932.7, self.close=29940.5, self.high=29944.3, self.low=29928.6, self.vol=661.543, self.amt=19804986.7697 
127.0.0.1 - - [22/Oct/2023 08:20:07] "POST / HTTP/1.1" 200 -
2023-10-22 08:20:10,295:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231022   075500    075959  ...         0.0        0.0       0
5856  20231022   080000    080459  ...         0.0        0.0       0
5857  20231022   080500    080959  ...         0.0        0.0       0
5858  20231022   081000    081459  ...         0.0        0.0       0
5859  20231022   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 08:20:10,304:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697933999, self.tradeDate='20231022', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29932.7, self.close=29940.5, self.high=29944.3, self.low=29928.6, self.vol=661.543, self.amt=19804986.7697, ukdf['pct'].iloc[-1]=0.00019 , ukdf['amount'].iloc[-1]=19804986.7697, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42814.34004335994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29939.31763919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46325
self.closeSec=1697934299, self.tradeDate='20231022', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29940.5, self.close=29940.8, self.high=29945.7, self.low=29931.1, self.vol=427.035, self.amt=12785612.389 
127.0.0.1 - - [22/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-22 08:25:03,062:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231022   080000    080459  ...         0.0        0.0       0
5857  20231022   080500    080959  ...         0.0        0.0       0
5858  20231022   081000    081459  ...         0.0        0.0       0
5859  20231022   081500    081959  ...         0.0        0.0       0
5860  20231022   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 08:25:03,064:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697934299, self.tradeDate='20231022', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29940.5, self.close=29940.8, self.high=29945.7, self.low=29931.1, self.vol=427.035, self.amt=12785612.389, ukdf['pct'].iloc[-1]=1e-05 , ukdf['amount'].iloc[-1]=12785612.389, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42851.6946', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29942', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [22/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46322 

self.closeSec=1697932799, self.tradeDate='20231022', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29881.5, self.close=29895.2, self.high=29899.7, self.low=29877.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46323 

self.closeSec=1697933099, self.tradeDate='20231022', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29895.4, self.close=29874.8, self.high=29901.3, self.low=29872.9 
127.0.0.1 - - [22/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46324 

self.closeSec=1697933399, self.tradeDate='20231022', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29874.8, self.close=29899.6, self.high=29899.9, self.low=29870.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46325 

self.closeSec=1697933699, self.tradeDate='20231022', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29897.9, self.close=29934.8, self.high=29934.9, self.low=29893.1 
127.0.0.1 - - [22/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46326 

self.closeSec=1697933999, self.tradeDate='20231022', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29932.7, self.close=29940.5, self.high=29944.3, self.low=29928.6 
127.0.0.1 - - [22/Oct/2023 08:20:07] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46327 

self.closeSec=1697934299, self.tradeDate='20231022', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29940.5, self.close=29940.8, self.high=29945.7, self.low=29931.1 
127.0.0.1 - - [22/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-22 08:00:17,220:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231022    052959  30001.7  ...  53.333333  0.590390  0.289436
5770  20231022    055959  30020.6  ...  52.916667  0.580963  0.298974
5771  20231022    062959  29971.9  ...  52.916667  0.577185  0.309207
5772  20231022    065959  29953.3  ...  52.916667  0.581411  0.316820
5773  20231022    072959  29981.6  ...  52.916667  0.569025  0.331251

[5 rows x 33 columns]
0.5537037037037037
acc is : 0.5537037037037037
2023-10-22 08:00:17,279:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.506031  0.493969       0  ...  0.972391   1.0    0.0  1.095588
536     1  0.494929  0.505071       0  ...  0.971787   1.0    0.0  1.094908
537     1  0.495471  0.504529       1  ...  0.972706   1.0    0.0  1.095943
538     0  0.516472  0.483528       0  ...  0.970746   1.0    0.0  1.093735
539     1  0.491370  0.508630       0  ...  0.969902   1.0    0.0  1.092785

[5 rows x 10 columns]
2023-10-22 08:00:17,291:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506165  0.493835       0  ...  0.972391   1.0    0.0  1.094045
46     1  0.495064  0.504936       0  ...  0.971787   1.0    0.0  1.090631
47     1  0.495757  0.504243       1  ...  0.972706   1.0    0.0  1.093513
48     0  0.516483  0.483517       0  ...  0.970746   1.0    0.0  1.093008
49     1  0.491370  0.508630       0  ...  0.969902   1.0    0.0  1.092785

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.157', 'enterprice': '29765.1', 'countrevence': '0', 'unrealprofit': '2791.72907853452', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29897.05297436', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23159 

self.closeSec=1697930999, self.tradeDate='20231022', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29914.5', self.close='29921.2'
127.0.0.1 - - [22/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [22/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23160 

self.closeSec=1697931599, self.tradeDate='20231022', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29922.2', self.close='29860.3'
127.0.0.1 - - [22/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23161 

self.closeSec=1697932199, self.tradeDate='20231022', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29863.1', self.close='29892.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23162 

self.closeSec=1697932799, self.tradeDate='20231022', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29892.8', self.close='29895.2'
127.0.0.1 - - [22/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23163 

self.closeSec=1697933399, self.tradeDate='20231022', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29895.4', self.close='29899.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23164 

self.closeSec=1697933999, self.tradeDate='20231022', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29897.9', self.close='29940.5'
127.0.0.1 - - [22/Oct/2023 08:20:08] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23162 

self.closeSec=1697930999, self.tradeDate='20231022', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29914.5', self.close='29921.2'
127.0.0.1 - - [22/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23163 

self.closeSec=1697931599, self.tradeDate='20231022', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29922.2', self.close='29860.3'
127.0.0.1 - - [22/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23164 

self.closeSec=1697932199, self.tradeDate='20231022', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29863.1', self.close='29892.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23165 

self.closeSec=1697932799, self.tradeDate='20231022', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29892.8', self.close='29895.2'
127.0.0.1 - - [22/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23166 

self.closeSec=1697933399, self.tradeDate='20231022', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29895.4', self.close='29899.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23167 

self.closeSec=1697933999, self.tradeDate='20231022', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29897.9', self.close='29940.5'
127.0.0.1 - - [22/Oct/2023 08:20:08] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [22/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23162 

self.closeSec=1697930999, self.tradeDate='20231022', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29914.5', self.close='29921.2'
127.0.0.1 - - [22/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23163 

self.closeSec=1697931599, self.tradeDate='20231022', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29922.2', self.close='29860.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23164 

self.closeSec=1697932199, self.tradeDate='20231022', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29863.1', self.close='29892.8'
127.0.0.1 - - [22/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23165 

self.closeSec=1697932799, self.tradeDate='20231022', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29892.8', self.close='29895.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23166 

self.closeSec=1697933399, self.tradeDate='20231022', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29895.4', self.close='29899.6'
127.0.0.1 - - [22/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23167 

self.closeSec=1697933999, self.tradeDate='20231022', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29897.9', self.close='29940.5'
127.0.0.1 - - [22/Oct/2023 08:20:08] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46324
self.closeSec=1697933999, self.tradeDate='20231022', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29932.7, self.close=29940.5, self.high=29944.3, self.low=29928.6, self.vol=661.543, self.amt=19804986.7697 
127.0.0.1 - - [22/Oct/2023 08:20:07] "POST / HTTP/1.1" 200 -
2023-10-22 08:20:10,324:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231022   075500    075959  ...         0.0        0.0       0
5856  20231022   080000    080459  ...         0.0        0.0       0
5857  20231022   080500    080959  ...         0.0        0.0       0
5858  20231022   081000    081459  ...         0.0        0.0       0
5859  20231022   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 08:20:10,333:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697933999, self.tradeDate='20231022', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29932.7, self.close=29940.5, self.high=29944.3, self.low=29928.6, self.vol=661.543, self.amt=19804986.7697, ukdf['pct'].iloc[-1]=0.00019 , ukdf['amount'].iloc[-1]=19804986.7697, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '114963.19243715579', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29939.31763919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46325
self.closeSec=1697934299, self.tradeDate='20231022', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29940.5, self.close=29940.8, self.high=29945.7, self.low=29931.1, self.vol=427.035, self.amt=12785612.389 
127.0.0.1 - - [22/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-22 08:25:03,066:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231022   080000    080459  ...         0.0        0.0       0
5857  20231022   080500    080959  ...         0.0        0.0       0
5858  20231022   081000    081459  ...         0.0        0.0       0
5859  20231022   081500    081959  ...         0.0        0.0       0
5860  20231022   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-22 08:25:03,069:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697934299, self.tradeDate='20231022', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29940.5, self.close=29940.8, self.high=29945.7, self.low=29931.1, self.vol=427.035, self.amt=12785612.389, ukdf['pct'].iloc[-1]=1e-05 , ukdf['amount'].iloc[-1]=12785612.389, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '115062.818', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29942', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231021   200000    235959  1697903999  ...    719  0.947711  0.509605     NaN
720  20231022   000000    035959  1697918399  ...    720  1.012641  0.597133     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '24684.2448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30136', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [22/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=965
self.closeSec=1697932799, self.tradeDate='20231022', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30128.7, self.close=29895.2, self.high=30145.1, self.low=29828.5, self.vol=28156.934, self.amt=843943891.56794 
2023-10-22 08:00:01,505:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697932799, self.tradeDate='20231022', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30128.7, self.close=29895.2, self.high=30145.1, self.low=29828.5, self.vol=28156.934, self.amt=843943891.56794 
2023-10-22 08:00:01,519:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231021   120000    155959  ...  23430.769  6.943455e+08  0.003089
718  20231021   160000    195959  ...  35531.108  1.057606e+09  0.003780
719  20231021   200000    235959  ...  45910.776  1.368944e+09  0.004165
720  20231022   000000    035959  ...  95226.326  2.864382e+09  0.007016
721  20231022   040000    075959  ...  28156.934  8.439439e+08 -0.007750

[5 rows x 11 columns]
2023-10-22 08:00:02,278:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231021   120000    155959  1697875199  ...    717  0.992068  0.595616     NaN
718  20231021   160000    195959  1697889599  ...    718  0.963248  0.545161     NaN
719  20231021   200000    235959  1697903999  ...    719  0.947711  0.509605     NaN
720  20231022   000000    035959  1697918399  ...    720  1.012641  0.597133     NaN
721  20231022   040000    075959  1697932799  ...    721  0.991878  0.550760     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '14768.88877773285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29896.27281685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


