# 20231015 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44308
self.closeSec=1697329199, self.tradeDate='20231015', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26829.9, self.close=26827.4, self.high=26833.6, self.low=26827.0, self.vol=103.827, self.amt=2785764.1711 
127.0.0.1 - - [15/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-15 08:20:18,160:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231015   075500    075959  ...         0.0        0.0       0
5856  20231015   080000    080459  ...         0.0        0.0       0
5857  20231015   080500    080959  ...         0.0        0.0       0
5858  20231015   081000    081459  ...         0.0        0.0       0
5859  20231015   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 08:20:18,171:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697329199, self.tradeDate='20231015', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26829.9, self.close=26827.4, self.high=26833.6, self.low=26827.0, self.vol=103.827, self.amt=2785764.1711, ukdf['pct'].iloc[-1]=-9.3e-05 , ukdf['amount'].iloc[-1]=2785764.1711, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '497.11513857984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26829.20309216', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44309
self.closeSec=1697329499, self.tradeDate='20231015', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26827.3, self.close=26822.1, self.high=26833.0, self.low=26822.0, self.vol=197.43, self.amt=5296383.739 
2023-10-15 08:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231015   080000    080459  ...         0.0        0.0       0
5857  20231015   080500    080959  ...         0.0        0.0       0
5858  20231015   081000    081459  ...         0.0        0.0       0
5859  20231015   081500    081959  ...         0.0        0.0       0
5860  20231015   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 08:25:00,819:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697329499, self.tradeDate='20231015', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26827.3, self.close=26822.1, self.high=26833.0, self.low=26822.0, self.vol=197.43, self.amt=5296383.739, ukdf['pct'].iloc[-1]=-0.000198 , ukdf['amount'].iloc[-1]=5296383.739, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '577.9006292565', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26823.40203725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  127.0.0.1 - - [15/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -
version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44306 

self.closeSec=1697327999, self.tradeDate='20231015', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26846.3, self.close=26836.4, self.high=26846.3, self.low=26836.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44307 

self.closeSec=1697328299, self.tradeDate='20231015', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26836.4, self.close=26831.5, self.high=26842.5, self.low=26830.0 
127.0.0.1 - - [15/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44308 

self.closeSec=1697328599, self.tradeDate='20231015', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26831.5, self.close=26834.5, self.high=26838.0, self.low=26827.5 
127.0.0.1 - - [15/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44309 

self.closeSec=1697328899, self.tradeDate='20231015', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26834.4, self.close=26829.9, self.high=26834.5, self.low=26827.9 
127.0.0.1 - - [15/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44310 

self.closeSec=1697329199, self.tradeDate='20231015', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26829.9, self.close=26827.4, self.high=26833.6, self.low=26827.0 
127.0.0.1 - - [15/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44311 

self.closeSec=1697329499, self.tradeDate='20231015', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26827.3, self.close=26822.1, self.high=26833.0, self.low=26822.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-15 08:00:18,895:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231015    052959  26831.9  ...  49.166667  0.473458  0.638063
5770  20231015    055959  26794.8  ...  49.166667  0.478323  0.651753
5771  20231015    062959  26806.5  ...  49.166667  0.481913  0.661843
5772  20231015    065959  26815.2  ...  49.583333  0.489254  0.665759
5773  20231015    072959  26832.7  ...  50.000000  0.494116  0.665757

[5 rows x 33 columns]
0.5537037037037037
acc is : 0.5537037037037037
2023-10-15 08:00:18,956:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.478775  0.521225       1  ...  0.932624   1.0    0.0  0.977480
536     1  0.494327  0.505673       1  ...  0.932924   1.0    0.0  0.977793
537     1  0.494416  0.505584       1  ...  0.933536   1.0    0.0  0.978435
538     0  0.500935  0.499065       1  ...  0.933943   1.0    0.0  0.978862
539     1  0.499867  0.500133       0  ...  0.933665   1.0    0.0  0.978570

[5 rows x 10 columns]
2023-10-15 08:00:18,968:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.478882  0.521118       1  ...  0.932624   1.0    0.0  0.980644
46     1  0.494145  0.505855       1  ...  0.932924   1.0    0.0  0.978886
47     1  0.494428  0.505572       1  ...  0.933536   1.0    0.0  0.980312
48     0  0.500795  0.499205       1  ...  0.933943   1.0    0.0  0.977899
49     1  0.499867  0.500133       0  ...  0.933665   1.0    0.0  0.978570

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.627', 'enterprice': '27009.6', 'countrevence': '0', 'unrealprofit': '-3983.5122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26841', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [15/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22151 

self.closeSec=1697326199, self.tradeDate='20231015', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26850', self.close='26844.4'
127.0.0.1 - - [15/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22152 

self.closeSec=1697326799, self.tradeDate='20231015', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26847.2', self.close='26847.5'
127.0.0.1 - - [15/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22153 

self.closeSec=1697327399, self.tradeDate='20231015', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26847.5', self.close='26846.3'
127.0.0.1 - - [15/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22154 

self.closeSec=1697327999, self.tradeDate='20231015', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26845.1', self.close='26836.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22155 

self.closeSec=1697328599, self.tradeDate='20231015', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26836.4', self.close='26834.5'
127.0.0.1 - - [15/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22156 

self.closeSec=1697329199, self.tradeDate='20231015', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26834.4', self.close='26827.3'
127.0.0.1 - - [15/Oct/2023 08:20:13] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [15/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22154 

self.closeSec=1697326199, self.tradeDate='20231015', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26850', self.close='26844.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22155 

self.closeSec=1697326799, self.tradeDate='20231015', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26847.2', self.close='26847.5'
127.0.0.1 - - [15/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22156 

self.closeSec=1697327399, self.tradeDate='20231015', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26847.5', self.close='26846.3'
127.0.0.1 - - [15/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22157 

self.closeSec=1697327999, self.tradeDate='20231015', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26845.1', self.close='26836.4'
127.0.0.1 - - [15/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22158 

self.closeSec=1697328599, self.tradeDate='20231015', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26836.4', self.close='26834.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22159 

self.closeSec=1697329199, self.tradeDate='20231015', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26834.4', self.close='26827.3'
127.0.0.1 - - [15/Oct/2023 08:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22154 

self.closeSec=1697326199, self.tradeDate='20231015', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26850', self.close='26844.4'
127.0.0.1 - - [15/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22155 

self.closeSec=1697326799, self.tradeDate='20231015', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26847.2', self.close='26847.5'
127.0.0.1 - - [15/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22156 

self.closeSec=1697327399, self.tradeDate='20231015', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26847.5', self.close='26846.3'
127.0.0.1 - - [15/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22157 

self.closeSec=1697327999, self.tradeDate='20231015', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26845.1', self.close='26836.4'
127.0.0.1 - - [15/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22158 

self.closeSec=1697328599, self.tradeDate='20231015', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26836.4', self.close='26834.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22159 

self.closeSec=1697329199, self.tradeDate='20231015', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26834.4', self.close='26827.3'
127.0.0.1 - - [15/Oct/2023 08:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44308
self.closeSec=1697329199, self.tradeDate='20231015', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26829.9, self.close=26827.4, self.high=26833.6, self.low=26827.0, self.vol=103.827, self.amt=2785764.1711 
127.0.0.1 - - [15/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-15 08:20:18,142:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231015   075500    075959  ...         0.0        0.0       0
5856  20231015   080000    080459  ...         0.0        0.0       0
5857  20231015   080500    080959  ...         0.0        0.0       0
5858  20231015   081000    081459  ...         0.0        0.0       0
5859  20231015   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 08:20:18,171:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697329199, self.tradeDate='20231015', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26829.9, self.close=26827.4, self.high=26833.6, self.low=26827.0, self.vol=103.827, self.amt=2785764.1711, ukdf['pct'].iloc[-1]=-9.3e-05 , ukdf['amount'].iloc[-1]=2785764.1711, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-549.42339008544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26829.20709216', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [15/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44309
self.closeSec=1697329499, self.tradeDate='20231015', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26827.3, self.close=26822.1, self.high=26833.0, self.low=26822.0, self.vol=197.43, self.amt=5296383.739 
2023-10-15 08:25:00,821:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231015   080000    080459  ...         0.0        0.0       0
5857  20231015   080500    080959  ...         0.0        0.0       0
5858  20231015   081000    081459  ...         0.0        0.0       0
5859  20231015   081500    081959  ...         0.0        0.0       0
5860  20231015   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-15 08:25:00,821:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697329499, self.tradeDate='20231015', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26827.3, self.close=26822.1, self.high=26833.0, self.low=26822.0, self.vol=197.43, self.amt=5296383.739, ukdf['pct'].iloc[-1]=-0.000198 , ukdf['amount'].iloc[-1]=5296383.739, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-765.02893449775', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26823.40203725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231014   200000    235959  1697299199  ...    719  0.799389  0.627588     1.0
720  20231015   000000    035959  1697313599  ...    720  0.656992  0.225374     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '1150.3868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26851.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [15/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1263543.0464457, self.flagDict['side']='buy', self.tradeCount=33, self.count=923
self.closeSec=1697327999, self.tradeDate='20231015', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26851.5, self.close=26836.4, self.high=26869.6, self.low=26773.1, self.vol=12128.808, self.amt=325347110.91692 
2023-10-15 08:00:01,515:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697327999, self.tradeDate='20231015', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26851.5, self.close=26836.4, self.high=26869.6, self.low=26773.1, self.vol=12128.808, self.amt=325347110.91692 
2023-10-15 08:00:01,530:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231014   120000    155959  ...  14754.421  3.965367e+08 -0.002140
718  20231014   160000    195959  ...   9363.638  2.515109e+08 -0.000015
719  20231014   200000    235959  ...  13269.386  3.567311e+08  0.002573
720  20231015   000000    035959  ...  12978.954  3.489274e+08 -0.002889
721  20231015   040000    075959  ...  12128.808  3.253471e+08 -0.000559

[5 rows x 11 columns]
2023-10-15 08:00:02,271:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231014   120000    155959  1697270399  ...    717  0.832137  0.715226     1.0
718  20231014   160000    195959  1697284799  ...    718  0.866498  0.815273     1.0
719  20231014   200000    235959  1697299199  ...    719  0.799389  0.627588     1.0
720  20231015   000000    035959  1697313599  ...    720  0.656992  0.225374     NaN
721  20231015   040000    075959  1697327999  ...    721  0.550053 -0.076009     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '563.49336370534', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26838.85183922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


