# 20230910 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34228
self.closeSec=1694305199, self.tradeDate='20230910', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25878.5, self.close=25865.8, self.high=25878.5, self.low=25865.8, self.vol=236.721, self.amt=6124518.5322 
127.0.0.1 - - [10/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-10 08:20:05,790:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230910   075500    075959  ...         0.0        0.0       0
5856  20230910   080000    080459  ...         0.0        0.0       0
5857  20230910   080500    080959  ...         0.0        0.0       0
5858  20230910   081000    081459  ...         0.0        0.0       0
5859  20230910   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 08:20:05,794:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694305199, self.tradeDate='20230910', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25878.5, self.close=25865.8, self.high=25878.5, self.low=25865.8, self.vol=236.721, self.amt=6124518.5322, ukdf['pct'].iloc[-1]=-0.000491 , ukdf['amount'].iloc[-1]=6124518.5322, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13898.82825710874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25866.85115201', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34229
self.closeSec=1694305499, self.tradeDate='20230910', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25865.8, self.close=25862.1, self.high=25867.0, self.low=25852.1, self.vol=638.028, self.amt=16498823.7959 
127.0.0.1 - - [10/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-10 08:25:00,805:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230910   080000    080459  ...         0.0        0.0       0
5857  20230910   080500    080959  ...         0.0        0.0       0
5858  20230910   081000    081459  ...         0.0        0.0       0
5859  20230910   081500    081959  ...         0.0        0.0       0
5860  20230910   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 08:25:00,806:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694305499, self.tradeDate='20230910', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25865.8, self.close=25862.1, self.high=25867.0, self.low=25852.1, self.vol=638.028, self.amt=16498823.7959, ukdf['pct'].iloc[-1]=-0.000143 , ukdf['amount'].iloc[-1]=16498823.7959, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13946.27987773482', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25863.44373993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34226 

self.closeSec=1694303999, self.tradeDate='20230910', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25879.1, self.close=25892.7, self.high=25892.7, self.low=25879.0 
127.0.0.1 - - [10/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34227 

self.closeSec=1694304299, self.tradeDate='20230910', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25892.6, self.close=25879.9, self.high=25893.9, self.low=25879.9 
127.0.0.1 - - [10/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34228 

self.closeSec=1694304599, self.tradeDate='20230910', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25879.9, self.close=25877.5, self.high=25885.0, self.low=25877.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34229 

self.closeSec=1694304899, self.tradeDate='20230910', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25877.6, self.close=25878.5, self.high=25878.6, self.low=25877.5 
127.0.0.1 - - [10/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34230 

self.closeSec=1694305199, self.tradeDate='20230910', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25878.5, self.close=25865.8, self.high=25878.5, self.low=25865.8 
127.0.0.1 - - [10/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34231 

self.closeSec=1694305499, self.tradeDate='20230910', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25865.8, self.close=25862.1, self.high=25867.0, self.low=25852.1 
127.0.0.1 - - [10/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-10 08:00:17,196:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230910    052959  25850.4  ...  54.166667  0.493182  0.474671
5770  20230910    055959  25864.5  ...  54.583333  0.498922  0.469802
5771  20230910    062959  25876.6  ...  54.583333  0.506173  0.458763
5772  20230910    065959  25892.2  ...  54.583333  0.509398  0.445568
5773  20230910    072959  25899.0  ...  54.166667  0.503418  0.438407

[5 rows x 33 columns]
0.5370370370370371
acc is : 0.5370370370370371
2023-09-10 08:00:17,258:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.496555  0.503445       1  ...  1.053460  -1.0    0.0  0.928046
536     1  0.497476  0.502524       1  ...  1.052829  -1.0    0.0  0.928602
537     1  0.499438  0.500562       1  ...  1.052548  -1.0    0.0  0.928849
538     1  0.498424  0.501576       0  ...  1.053048  -1.0    0.0  0.928408
539     1  0.493833  0.506167       1  ...  1.052808  -1.0    0.0  0.928620

[5 rows x 10 columns]
2023-09-10 08:00:17,270:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497002  0.502998       1  ...  1.076887  -1.0    0.0  0.944016
46     1  0.497668  0.502332       1  ...  1.038202  -1.0    0.0  0.927913
47     1  0.498920  0.501080       1  ...  1.034854  -1.0    0.0  0.925421
48     1  0.498085  0.501915       0  ...  1.053048  -1.0    0.0  0.926759
49     1  0.493833  0.506167       1  ...  1.052808  -1.0    0.0  0.928620

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '-3458.9932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25893.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [10/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17111 

self.closeSec=1694302199, self.tradeDate='20230910', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25886.8', self.close='25886.8'
127.0.0.1 - - [10/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17112 

self.closeSec=1694302799, self.tradeDate='20230910', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25886.9', self.close='25878.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17113 

self.closeSec=1694303399, self.tradeDate='20230910', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25878.3', self.close='25883.6'
127.0.0.1 - - [10/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17114 

self.closeSec=1694303999, self.tradeDate='20230910', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25883.7', self.close='25892.6'
127.0.0.1 - - [10/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17115 

self.closeSec=1694304599, self.tradeDate='20230910', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25892.6', self.close='25877.5'
127.0.0.1 - - [10/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17116 

self.closeSec=1694305199, self.tradeDate='20230910', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25877.6', self.close='25865.8'
127.0.0.1 - - [10/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [10/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17114 

self.closeSec=1694302199, self.tradeDate='20230910', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25886.8', self.close='25886.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17115 

self.closeSec=1694302799, self.tradeDate='20230910', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25886.9', self.close='25878.3'
127.0.0.1 - - [10/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17116 

self.closeSec=1694303399, self.tradeDate='20230910', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25878.3', self.close='25883.6'
127.0.0.1 - - [10/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17117 

self.closeSec=1694303999, self.tradeDate='20230910', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25883.7', self.close='25892.6'
127.0.0.1 - - [10/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17118 

self.closeSec=1694304599, self.tradeDate='20230910', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25892.6', self.close='25877.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17119 

self.closeSec=1694305199, self.tradeDate='20230910', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25877.6', self.close='25865.8'
127.0.0.1 - - [10/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17114 

self.closeSec=1694302199, self.tradeDate='20230910', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25886.8', self.close='25886.8'
127.0.0.1 - - [10/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17115 

self.closeSec=1694302799, self.tradeDate='20230910', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25886.9', self.close='25878.3'
127.0.0.1 - - [10/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17116 

self.closeSec=1694303399, self.tradeDate='20230910', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25878.3', self.close='25883.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17117 

self.closeSec=1694303999, self.tradeDate='20230910', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25883.7', self.close='25892.6'
127.0.0.1 - - [10/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17118 

self.closeSec=1694304599, self.tradeDate='20230910', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25892.6', self.close='25877.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17119 

self.closeSec=1694305199, self.tradeDate='20230910', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25877.6', self.close='25865.8'
127.0.0.1 - - [10/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34228
self.closeSec=1694305199, self.tradeDate='20230910', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25878.5, self.close=25865.8, self.high=25878.5, self.low=25865.8, self.vol=236.721, self.amt=6124518.5322 
127.0.0.1 - - [10/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-10 08:20:05,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230910   075500    075959  ...         0.0        0.0       0
5856  20230910   080000    080459  ...         0.0        0.0       0
5857  20230910   080500    080959  ...         0.0        0.0       0
5858  20230910   081000    081459  ...         0.0        0.0       0
5859  20230910   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 08:20:05,792:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694305199, self.tradeDate='20230910', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25878.5, self.close=25865.8, self.high=25878.5, self.low=25865.8, self.vol=236.721, self.amt=6124518.5322, ukdf['pct'].iloc[-1]=-0.000491 , ukdf['amount'].iloc[-1]=6124518.5322, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36292.28536319659', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25866.85115201', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [10/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34229
self.closeSec=1694305499, self.tradeDate='20230910', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25865.8, self.close=25862.1, self.high=25867.0, self.low=25852.1, self.vol=638.028, self.amt=16498823.7959 
2023-09-10 08:25:00,805:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230910   080000    080459  ...         0.0        0.0       0
5857  20230910   080500    080959  ...         0.0        0.0       0
5858  20230910   081000    081459  ...         0.0        0.0       0
5859  20230910   081500    081959  ...         0.0        0.0       0
5860  20230910   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-10 08:25:00,806:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694305499, self.tradeDate='20230910', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25865.8, self.close=25862.1, self.high=25867.0, self.low=25852.1, self.vol=638.028, self.amt=16498823.7959, ukdf['pct'].iloc[-1]=-0.000143 , ukdf['amount'].iloc[-1]=16498823.7959, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36418.84005525987', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25863.44373993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230909   200000    235959  1694275199  ...    719  0.141142 -0.724742    -1.0
720  20230910   000000    035959  1694289599  ...    720  0.139596 -0.727565    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '1860.18981571206', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25859.76611722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [10/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=713
self.closeSec=1694303999, self.tradeDate='20230910', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25858.0, self.close=25892.6, self.high=25908.5, self.low=25843.7, self.vol=6773.836, self.amt=175285106.4541 
2023-09-10 08:00:01,533:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694303999, self.tradeDate='20230910', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25858.0, self.close=25892.6, self.high=25908.5, self.low=25843.7, self.vol=6773.836, self.amt=175285106.4541 
2023-09-10 08:00:01,546:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230909   120000    155959  ...  10439.267  2.699424e+08  0.000178
718  20230909   160000    195959  ...  10348.675  2.676785e+08 -0.000777
719  20230909   200000    235959  ...  19660.804  5.082788e+08  0.001203
720  20230910   000000    035959  ...  10147.831  2.625691e+08 -0.000923
721  20230910   040000    075959  ...   6773.836  1.752851e+08  0.001338

[5 rows x 11 columns]
2023-09-10 08:00:02,240:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230909   120000    155959  1694246399  ...    717  0.172586 -0.639120    -1.0
718  20230909   160000    195959  1694260799  ...    718  0.151505 -0.696459    -1.0
719  20230909   200000    235959  1694275199  ...    719  0.141142 -0.724742    -1.0
720  20230910   000000    035959  1694289599  ...    720  0.139596 -0.727565    -1.0
721  20230910   040000    075959  1694303999  ...    721  0.125757 -0.764330    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-17.1531', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25892.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


