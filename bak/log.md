# 20230903 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32212
self.closeSec=1693700399, self.tradeDate='20230903', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25858.5, self.close=25855.7, self.high=25859.5, self.low=25855.6, self.vol=54.889, self.amt=1419271.7485 
127.0.0.1 - - [03/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-09-03 08:20:05,216:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230903   075500    075959  ...         0.0        0.0       0
5844  20230903   080000    080459  ...         0.0        0.0       0
5845  20230903   080500    080959  ...         0.0        0.0       0
5846  20230903   081000    081459  ...         0.0        0.0       0
5847  20230903   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 08:20:05,219:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693700399, self.tradeDate='20230903', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25858.5, self.close=25855.7, self.high=25859.5, self.low=25855.6, self.vol=54.889, self.amt=1419271.7485, ukdf['pct'].iloc[-1]=-0.000108 , ukdf['amount'].iloc[-1]=1419271.7485, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14049.45568298382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25856.03487843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32213
self.closeSec=1693700699, self.tradeDate='20230903', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25855.7, self.close=25847.1, self.high=25855.7, self.low=25834.6, self.vol=411.267, self.amt=10628152.7305 
2023-09-03 08:25:00,764:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230903   080000    080459  ...         0.0        0.0       0
5845  20230903   080500    080959  ...         0.0        0.0       0
5846  20230903   081000    081459  ...         0.0        0.0       0
5847  20230903   081500    081959  ...         0.0        0.0       0
5848  20230903   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 08:25:00,765:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693700699, self.tradeDate='20230903', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25855.7, self.close=25847.1, self.high=25855.7, self.low=25834.6, self.vol=411.267, self.amt=10628152.7305, ukdf['pct'].iloc[-1]=-0.000333 , ukdf['amount'].iloc[-1]=10628152.7305, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14144.58360673776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25849.20392024', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [03/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32210 

self.closeSec=1693699199, self.tradeDate='20230903', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25846.1, self.close=25855.9, self.high=25858.6, self.low=25846.1 
127.0.0.1 - - [03/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32211 

self.closeSec=1693699499, self.tradeDate='20230903', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25855.8, self.close=25845.4, self.high=25862.9, self.low=25844.4 
127.0.0.1 - - [03/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32212 

self.closeSec=1693699799, self.tradeDate='20230903', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25845.4, self.close=25857.2, self.high=25860.8, self.low=25845.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32213 

self.closeSec=1693700099, self.tradeDate='20230903', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25857.2, self.close=25858.5, self.high=25860.0, self.low=25850.9 
127.0.0.1 - - [03/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32214 

self.closeSec=1693700399, self.tradeDate='20230903', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25858.5, self.close=25855.7, self.high=25859.5, self.low=25855.6 
127.0.0.1 - - [03/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32215 

self.closeSec=1693700699, self.tradeDate='20230903', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25855.7, self.close=25847.1, self.high=25855.7, self.low=25834.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-03 08:00:17,112:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230903    052959  25839.6  ...  45.416667  0.463929  0.484644
5770  20230903    055959  25858.2  ...  45.416667  0.461640  0.488085
5771  20230903    062959  25849.3  ...  45.000000  0.458438  0.494767
5772  20230903    065959  25837.2  ...  45.000000  0.462367  0.498436
5773  20230903    072959  25849.8  ...  45.000000  0.471099  0.494123

[5 rows x 33 columns]
0.5277777777777778
acc is : 0.5277777777777778
2023-09-03 08:00:17,170:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.508962  0.491038       0  ...  1.004190  -1.0    0.0  1.000960
536     0  0.501729  0.498271       0  ...  1.004664  -1.0    0.0  1.000488
537     1  0.494935  0.505065       1  ...  1.004174  -1.0    0.0  1.000976
538     0  0.505381  0.494619       1  ...  1.003083  -1.0    0.0  1.002064
539     0  0.520265  0.479735       0  ...  1.003932  -1.0    0.0  1.001216

[5 rows x 10 columns]
2023-09-03 08:00:17,181:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508331  0.491669       0  ...  1.004190  -1.0    0.0  0.997157
46     0  0.501391  0.498609       0  ...  1.004664  -1.0    0.0  0.999408
47     1  0.494302  0.505698       1  ...  1.004174  -1.0    0.0  0.993902
48     0  0.505036  0.494964       1  ...  1.003083  -1.0    0.0  0.998079
49     0  0.520265  0.479735       0  ...  1.003932  -1.0    0.0  1.001216

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '21577.6808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25861.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16103 

self.closeSec=1693697399, self.tradeDate='20230903', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25866.6', self.close='25877.8'
127.0.0.1 - - [03/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16104 

self.closeSec=1693697999, self.tradeDate='20230903', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25877.9', self.close='25854'
127.0.0.1 - - [03/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16105 

self.closeSec=1693698599, self.tradeDate='20230903', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25854', self.close='25849.9'
127.0.0.1 - - [03/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16106 

self.closeSec=1693699199, self.tradeDate='20230903', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25850', self.close='25855.8'
127.0.0.1 - - [03/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16107 

self.closeSec=1693699799, self.tradeDate='20230903', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25855.8', self.close='25857.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16108 

self.closeSec=1693700399, self.tradeDate='20230903', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25857.2', self.close='25855.7'
127.0.0.1 - - [03/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [03/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16106 

self.closeSec=1693697399, self.tradeDate='20230903', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25866.6', self.close='25877.8'
127.0.0.1 - - [03/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16107 

self.closeSec=1693697999, self.tradeDate='20230903', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25877.9', self.close='25854'
127.0.0.1 - - [03/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16108 

self.closeSec=1693698599, self.tradeDate='20230903', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25854', self.close='25849.9'
127.0.0.1 - - [03/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16109 

self.closeSec=1693699199, self.tradeDate='20230903', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25850', self.close='25855.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16110 

self.closeSec=1693699799, self.tradeDate='20230903', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25855.8', self.close='25857.2'
127.0.0.1 - - [03/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16111 

self.closeSec=1693700399, self.tradeDate='20230903', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25857.2', self.close='25855.7'
127.0.0.1 - - [03/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16106 

self.closeSec=1693697399, self.tradeDate='20230903', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25866.6', self.close='25877.8'
127.0.0.1 - - [03/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16107 

self.closeSec=1693697999, self.tradeDate='20230903', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25877.9', self.close='25854'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16108127.0.0.1 - - [03/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
 

self.closeSec=1693698599, self.tradeDate='20230903', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25854', self.close='25849.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16109 

self.closeSec=1693699199, self.tradeDate='20230903', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25850', self.close='25855.8'
127.0.0.1 - - [03/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16110 

self.closeSec=1693699799, self.tradeDate='20230903', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25855.8', self.close='25857.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16111 

self.closeSec=1693700399, self.tradeDate='20230903', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25857.2', self.close='25855.7'
127.0.0.1 - - [03/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32212
self.closeSec=1693700399, self.tradeDate='20230903', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25858.5, self.close=25855.7, self.high=25859.5, self.low=25855.6, self.vol=54.889, self.amt=1419271.7485 
127.0.0.1 - - [03/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-09-03 08:20:05,213:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230903   075500    075959  ...         0.0        0.0       0
5844  20230903   080000    080459  ...         0.0        0.0       0
5845  20230903   080500    080959  ...         0.0        0.0       0
5846  20230903   081000    081459  ...         0.0        0.0       0
5847  20230903   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 08:20:05,217:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693700399, self.tradeDate='20230903', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25858.5, self.close=25855.7, self.high=25859.5, self.low=25855.6, self.vol=54.889, self.amt=1419271.7485, ukdf['pct'].iloc[-1]=-0.000108 , ukdf['amount'].iloc[-1]=1419271.7485, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36694.01258023137', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25856.03487843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32213
self.closeSec=1693700699, self.tradeDate='20230903', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25855.7, self.close=25847.1, self.high=25855.7, self.low=25834.6, self.vol=411.267, self.amt=10628152.7305 
2023-09-03 08:25:00,769:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230903   080000    080459  ...         0.0        0.0       0
5845  20230903   080500    080959  ...         0.0        0.0       0
5846  20230903   081000    081459  ...         0.0        0.0       0
5847  20230903   081500    081959  ...         0.0        0.0       0
5848  20230903   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-03 08:25:00,769:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693700699, self.tradeDate='20230903', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25855.7, self.close=25847.1, self.high=25855.7, self.low=25834.6, self.vol=411.267, self.amt=10628152.7305, ukdf['pct'].iloc[-1]=-0.000333 , ukdf['amount'].iloc[-1]=10628152.7305, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36947.72119836616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25849.20392024', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230902   200000    235959  1693670399  ...    719  0.671203  0.911753     1.0
720  20230903   000000    035959  1693684799  ...    720  0.869357  1.490222     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-115193.67431874432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25821.75370784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [03/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=671
self.closeSec=1693699199, self.tradeDate='20230903', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25821.6, self.close=25855.9, self.high=25899.3, self.low=25805.4, self.vol=9378.742, self.amt=242415570.0344 
2023-09-03 08:00:01,557:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693699199, self.tradeDate='20230903', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25821.6, self.close=25855.9, self.high=25899.3, self.low=25805.4, self.vol=9378.742, self.amt=242415570.0344 
2023-09-03 08:00:01,570:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230902   120000    155959  ...  13773.944  3.552750e+08 -0.000085
718  20230902   160000    195959  ...  18478.625  4.768100e+08  0.000628
719  20230902   200000    235959  ...  31794.939  8.226471e+08  0.003097
720  20230903   000000    035959  ...  22126.255  5.714335e+08 -0.002257
721  20230903   040000    075959  ...   9378.742  2.424156e+08  0.001328

[5 rows x 11 columns]
2023-09-03 08:00:02,310:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230902   120000    155959  1693641599  ...    717  0.654133  0.889894     1.0
718  20230902   160000    195959  1693655999  ...    718  0.668007  0.916750     1.0
719  20230902   200000    235959  1693670399  ...    719  0.671203  0.911753     1.0
720  20230903   000000    035959  1693684799  ...    720  0.869357  1.490222     1.0
721  20230903   040000    075959  1693699199  ...    721  0.829327  1.340573     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-113109.5124749304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25858.1570098', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


