# 20231020 08:26:11

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45748
self.closeSec=1697761199, self.tradeDate='20231020', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28698.6, self.close=28667.7, self.high=28706.1, self.low=28665.1, self.vol=869.511, self.amt=24939993.05 
127.0.0.1 - - [20/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -
2023-10-20 08:20:16,027:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231020   075500    075959  ...         0.0        0.0       0
5856  20231020   080000    080459  ...         0.0        0.0       0
5857  20231020   080500    080959  ...         0.0        0.0       0
5858  20231020   081000    081459  ...         0.0        0.0       0
5859  20231020   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 08:20:16,037:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697761199, self.tradeDate='20231020', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28698.6, self.close=28667.7, self.high=28706.1, self.low=28665.1, self.vol=869.511, self.amt=24939993.05, ukdf['pct'].iloc[-1]=-0.001077 , ukdf['amount'].iloc[-1]=24939993.05, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-25197.7044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28674.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45749
self.closeSec=1697761499, self.tradeDate='20231020', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28667.7, self.close=28660.2, self.high=28677.6, self.low=28656.3, self.vol=537.143, self.amt=15398389.415 
127.0.0.1 - - [20/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-20 08:25:03,188:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231020   080000    080459  ...         0.0        0.0       0
5857  20231020   080500    080959  ...         0.0        0.0       0
5858  20231020   081000    081459  ...         0.0        0.0       0
5859  20231020   081500    081959  ...         0.0        0.0       0
5860  20231020   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 08:25:03,191:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697761499, self.tradeDate='20231020', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28667.7, self.close=28660.2, self.high=28677.6, self.low=28656.3, self.vol=537.143, self.amt=15398389.415, ukdf['pct'].iloc[-1]=-0.000262 , ukdf['amount'].iloc[-1]=15398389.415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-25017.02091223236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28661.32545686', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [20/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45746 

self.closeSec=1697759999, self.tradeDate='20231020', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28677.9, self.close=28696.9, self.high=28700.0, self.low=28671.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45747 

self.closeSec=1697760299, self.tradeDate='20231020', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28697.0, self.close=28739.6, self.high=28749.0, self.low=28686.3 
127.0.0.1 - - [20/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45748 

self.closeSec=1697760599, self.tradeDate='20231020', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28739.6, self.close=28739.3, self.high=28756.8, self.low=28722.1 
127.0.0.1 - - [20/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45749 

self.closeSec=1697760899, self.tradeDate='20231020', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28739.3, self.close=28698.6, self.high=28743.0, self.low=28692.6 
127.0.0.1 - - [20/Oct/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45750 

self.closeSec=1697761199, self.tradeDate='20231020', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28698.6, self.close=28667.7, self.high=28706.1, self.low=28665.1 
127.0.0.1 - - [20/Oct/2023 08:20:08] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45751 

self.closeSec=1697761499, self.tradeDate='20231020', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28667.7, self.close=28660.2, self.high=28677.6, self.low=28656.3 
127.0.0.1 - - [20/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-20 08:00:17,825:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231020    052959  28699.5  ...  53.750000  0.548320  0.330649
5770  20231020    055959  28626.7  ...  53.333333  0.540291  0.337899
5771  20231020    062959  28590.1  ...  53.333333  0.553296  0.338530
5772  20231020    065959  28661.9  ...  52.916667  0.546472  0.342836
5773  20231020    072959  28630.8  ...  52.916667  0.547242  0.347570

[5 rows x 33 columns]
0.5814814814814815
acc is : 0.5814814814814815
2023-10-20 08:00:17,904:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.485833  0.514167       0  ...  0.926156   1.0    0.0  1.026099
536     1  0.489084  0.510916       1  ...  0.928485   1.0    0.0  1.028680
537     0  0.519171  0.480829       0  ...  0.927478   1.0    0.0  1.027564
538     1  0.491999  0.508001       1  ...  0.927614   1.0    0.0  1.027714
539     0  0.501209  0.498791       1  ...  0.929616   1.0    0.0  1.029932

[5 rows x 10 columns]
2023-10-20 08:00:17,920:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485900  0.514100       0  ...  0.926156   1.0    0.0  1.025337
46     1  0.489105  0.510895       1  ...  0.928485   1.0    0.0  1.028440
47     0  0.519035  0.480965       0  ...  0.927478   1.0    0.0  1.026094
48     1  0.491956  0.508044       1  ...  0.927614   1.0    0.0  1.027062
49     0  0.501209  0.498791       1  ...  0.929616   1.0    0.0  1.029932

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.528', 'enterprice': '28565.1', 'countrevence': '0', 'unrealprofit': '2872.25955476928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28698.51971176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22871 

self.closeSec=1697758199, self.tradeDate='20231020', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28653', self.close='28635.1'
127.0.0.1 - - [20/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22872 

self.closeSec=1697758799, self.tradeDate='20231020', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28635', self.close='28625'
127.0.0.1 - - [20/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22873 

self.closeSec=1697759399, self.tradeDate='20231020', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28625', self.close='28663.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22874 

self.closeSec=1697759999, self.tradeDate='20231020', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28663.2', self.close='28696.9'
127.0.0.1 - - [20/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22875 

self.closeSec=1697760599, self.tradeDate='20231020', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28697', self.close='28739.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22876 

self.closeSec=1697761199, self.tradeDate='20231020', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28739.3', self.close='28667.6'
127.0.0.1 - - [20/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [20/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22874 

self.closeSec=1697758199, self.tradeDate='20231020', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28653', self.close='28635.1'
127.0.0.1 - - [20/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22875 

self.closeSec=1697758799, self.tradeDate='20231020', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28635', self.close='28625'
127.0.0.1 - - [20/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22876 

self.closeSec=1697759399, self.tradeDate='20231020', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28625', self.close='28663.2'
127.0.0.1 - - [20/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22877 

self.closeSec=1697759999, self.tradeDate='20231020', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28663.2', self.close='28696.9'
127.0.0.1 - - [20/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22878 

self.closeSec=1697760599, self.tradeDate='20231020', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28697', self.close='28739.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22879 

self.closeSec=1697761199, self.tradeDate='20231020', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28739.3', self.close='28667.6'
127.0.0.1 - - [20/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22874 

self.closeSec=1697758199, self.tradeDate='20231020', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28653', self.close='28635.1'
127.0.0.1 - - [20/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22875 

self.closeSec=1697758799, self.tradeDate='20231020', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28635', self.close='28625'
127.0.0.1 - - [20/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22876 

self.closeSec=1697759399, self.tradeDate='20231020', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28625', self.close='28663.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22877 

self.closeSec=1697759999, self.tradeDate='20231020', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28663.2', self.close='28696.9'
127.0.0.1 - - [20/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22878 

self.closeSec=1697760599, self.tradeDate='20231020', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28697', self.close='28739.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22879 

self.closeSec=1697761199, self.tradeDate='20231020', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28739.3', self.close='28667.6'
127.0.0.1 - - [20/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45748
self.closeSec=1697761199, self.tradeDate='20231020', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28698.6, self.close=28667.7, self.high=28706.1, self.low=28665.1, self.vol=869.511, self.amt=24939993.05 
127.0.0.1 - - [20/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -
2023-10-20 08:20:16,026:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231020   075500    075959  ...         0.0        0.0       0
5856  20231020   080000    080459  ...         0.0        0.0       0
5857  20231020   080500    080959  ...         0.0        0.0       0
5858  20231020   081000    081459  ...         0.0        0.0       0
5859  20231020   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 08:20:16,037:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697761199, self.tradeDate='20231020', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28698.6, self.close=28667.7, self.high=28706.1, self.low=28665.1, self.vol=869.511, self.amt=24939993.05, ukdf['pct'].iloc[-1]=-0.001077 , ukdf['amount'].iloc[-1]=24939993.05, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '67979.1723', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28674.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45749
self.closeSec=1697761499, self.tradeDate='20231020', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28667.7, self.close=28660.2, self.high=28677.6, self.low=28656.3, self.vol=537.143, self.amt=15398389.415 
127.0.0.1 - - [20/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-20 08:25:03,187:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231020   080000    080459  ...         0.0        0.0       0
5857  20231020   080500    080959  ...         0.0        0.0       0
5858  20231020   081000    081459  ...         0.0        0.0       0
5859  20231020   081500    081959  ...         0.0        0.0       0
5860  20231020   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 08:25:03,191:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697761499, self.tradeDate='20231020', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28667.7, self.close=28660.2, self.high=28677.6, self.low=28656.3, self.vol=537.143, self.amt=15398389.415, ukdf['pct'].iloc[-1]=-0.000262 , ukdf['amount'].iloc[-1]=15398389.415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '67497.28479323726', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28661.32545686', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-10-20 04:00:10,416:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43031F1697745604816I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697745605229871, 'quantity': '43.806', 'price': '28745.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697745603894, 'updatetime': 1697745605229, 'tradetype': 'usdt', 'selfid': 43031, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697745605229, 'clientorderid': '43031F1697745604816I0L65', 'price': '28745.4', 'quantity': '43.806', 'commission': '1259.2209924', 'commissionasset': 'USDT', 'tradetime': 1697745605229, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697745605229}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-20 04:00:10,416:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43031F1697745604816I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697745605229871, 'quantity': '43.806', 'price': '28745.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697745603894, 'updatetime': 1697745605229, 'tradetype': 'usdt', 'selfid': 43031, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697745605229, 'clientorderid': '43031F1697745604816I0L65', 'price': '28745.4', 'quantity': '43.806', 'commission': '1259.2209924', 'commissionasset': 'USDT', 'tradetime': 1697745605229, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697745605229}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Oct/2023 04:00:10] "POST / HTTP/1.1" 200 -
2023-10-20 04:00:10,879:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43032F1697745610391I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697745610825733, 'quantity': '43.755', 'price': '28761.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697745609926, 'updatetime': 1697745610825, 'tradetype': 'usdt', 'selfid': 43032, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697745610825, 'clientorderid': '43032F1697745610391I0L65', 'price': '28761.1', 'quantity': '43.755', 'commission': '1258.4419305', 'commissionasset': 'USDT', 'tradetime': 1697745610825, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697745610825}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-20 04:00:11,063:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43032F1697745610391I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697745610825733, 'quantity': '43.755', 'price': '28761.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697745609926, 'updatetime': 1697745610825, 'tradetype': 'usdt', 'selfid': 43032, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697745610825, 'clientorderid': '43032F1697745610391I0L65', 'price': '28761.1', 'quantity': '43.755', 'commission': '1258.4419305', 'commissionasset': 'USDT', 'tradetime': 1697745610825, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697745610825}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Oct/2023 04:00:11] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1257183.4885695, self.flagDict['side']='sell', self.tradeCount=36, self.count=953
self.closeSec=1697759999, self.tradeDate='20231020', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28734.6, self.close=28696.9, self.high=28883.7, self.low=28579.1, self.vol=36228.044, self.amt=1039869151.8596 
2023-10-20 08:00:01,558:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697759999, self.tradeDate='20231020', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28734.6, self.close=28696.9, self.high=28883.7, self.low=28579.1, self.vol=36228.044, self.amt=1039869151.8596 
2023-10-20 08:00:01,577:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231019   120000    155959  ...   20030.161  5.664727e+08  0.002379
718  20231019   160000    195959  ...   41213.352  1.170375e+09  0.004277
719  20231019   200000    235959  ...  110931.187  3.171937e+09  0.007881
720  20231020   000000    035959  ...   87657.153  2.513027e+09  0.002732
721  20231020   040000    075959  ...   36228.044  1.039869e+09 -0.001448

[5 rows x 11 columns]
2023-10-20 08:00:02,265:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231019   120000    155959  1697702399  ...    717  0.524652 -0.206264     NaN
718  20231019   160000    195959  1697716799  ...    718  0.410138 -0.382959     NaN
719  20231019   200000    235959  1697731199  ...    719  0.301781 -0.548275     NaN
720  20231020   000000    035959  1697745599  ...    720  0.190537 -0.715793    -1.0
721  20231020   040000    075959  1697759999  ...    721  0.082168 -0.875769    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.755', 'enterprice': '28761.1', 'countrevence': '0', 'unrealprofit': '2783.1175073505', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28697.4931549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


