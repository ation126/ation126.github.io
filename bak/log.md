# 20230827 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30196
self.closeSec=1693095599, self.tradeDate='20230827', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26000.9, self.close=26006.5, self.high=26008.5, self.low=26000.9, self.vol=240.371, self.amt=6250731.6395 
127.0.0.1 - - [27/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-27 08:20:05,329:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230827   075500    075959  ...         0.0        0.0       0
5844  20230827   080000    080459  ...         0.0        0.0       0
5845  20230827   080500    080959  ...         0.0        0.0       0
5846  20230827   081000    081459  ...         0.0        0.0       0
5847  20230827   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 08:20:05,333:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693095599, self.tradeDate='20230827', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26000.9, self.close=26006.5, self.high=26008.5, self.low=26000.9, self.vol=240.371, self.amt=6250731.6395, ukdf['pct'].iloc[-1]=0.000212 , ukdf['amount'].iloc[-1]=6250731.6395, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11928.3327485817', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26008.34874705', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30197
self.closeSec=1693095899, self.tradeDate='20230827', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26006.5, self.close=26014.2, self.high=26014.2, self.low=26004.7, self.vol=191.388, self.amt=4977981.112 
2023-08-27 08:25:00,816:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230827   080000    080459  ...         0.0        0.0       0
5845  20230827   080500    080959  ...         0.0        0.0       0
5846  20230827   081000    081459  ...         0.0        0.0       0
5847  20230827   081500    081959  ...         0.0        0.0       0
5848  20230827   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 08:25:00,816:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693095899, self.tradeDate='20230827', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26006.5, self.close=26014.2, self.high=26014.2, self.low=26004.7, self.vol=191.388, self.amt=4977981.112, ukdf['pct'].iloc[-1]=0.000296 , ukdf['amount'].iloc[-1]=4977981.112, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11835.7074', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26015', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30194 

self.closeSec=1693094399, self.tradeDate='20230827', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26005.6, self.close=26004.2, self.high=26005.7, self.low=26004.2 
127.0.0.1 - - [27/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30195 

self.closeSec=1693094699, self.tradeDate='20230827', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26004.3, self.close=25995.3, self.high=26004.3, self.low=25995.2 
127.0.0.1 - - [27/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30196 

self.closeSec=1693094999, self.tradeDate='20230827', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25995.3, self.close=25997.4, self.high=25999.0, self.low=25995.2 
127.0.0.1 - - [27/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30197 

self.closeSec=1693095299, self.tradeDate='20230827', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25997.4, self.close=26001.0, self.high=26001.0, self.low=25997.3 
127.0.0.1 - - [27/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30198 

self.closeSec=1693095599, self.tradeDate='20230827', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26000.9, self.close=26006.5, self.high=26008.5, self.low=26000.9 
127.0.0.1 - - [27/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30199 

self.closeSec=1693095899, self.tradeDate='20230827', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26006.5, self.close=26014.2, self.high=26014.2, self.low=26004.7 
127.0.0.1 - - [27/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-27 08:00:18,030:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230827    052959  26018.0  ...  50.000000  0.490462  0.571248
5770  20230827    055959  26033.7  ...  49.583333  0.487882  0.575850
5771  20230827    062959  26026.7  ...  49.583333  0.486576  0.574411
5772  20230827    065959  26023.2  ...  49.583333  0.484759  0.575701
5773  20230827    072959  26018.5  ...  49.583333  0.479772  0.584086

[5 rows x 33 columns]
0.5407407407407407
acc is : 0.5407407407407407
2023-08-27 08:00:18,097:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.500198  0.499802       0  ...  1.071842  -1.0    0.0  0.888026
536     1  0.495258  0.504742       0  ...  1.071986  -1.0    0.0  0.887906
537     1  0.491369  0.508631       0  ...  1.072184  -1.0    0.0  0.887742
538     1  0.492871  0.507129       0  ...  1.072724  -1.0    0.0  0.887295
539     1  0.490481  0.509519       0  ...  1.072769  -1.0    0.0  0.887258

[5 rows x 10 columns]
2023-08-27 08:00:18,110:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500272  0.499728       0  ...  1.071842  -1.0    0.0  0.886024
46     1  0.495292  0.504708       0  ...  1.071986  -1.0    0.0  0.887706
47     1  0.491376  0.508624       0  ...  1.072184  -1.0    0.0  0.886823
48     1  0.492872  0.507128       0  ...  1.072724  -1.0    0.0  0.888405
49     1  0.490481  0.509519       0  ...  1.072769  -1.0    0.0  0.887258

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '11360.510703451', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25999.587379', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [27/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15095 

self.closeSec=1693092599, self.tradeDate='20230827', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25999.6', self.close='26005.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15096 

self.closeSec=1693093199, self.tradeDate='20230827', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26005.3', self.close='26012.7'
127.0.0.1 - - [27/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15097 

self.closeSec=1693093799, self.tradeDate='20230827', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26012.6', self.close='25998.6'
127.0.0.1 - - [27/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15098 

self.closeSec=1693094399, self.tradeDate='20230827', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25998.6', self.close='26004.2'
127.0.0.1 - - [27/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15099 

self.closeSec=1693094999, self.tradeDate='20230827', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26004.3', self.close='25997.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15100 

self.closeSec=1693095599, self.tradeDate='20230827', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25997.4', self.close='26006.6'
127.0.0.1 - - [27/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [27/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15098 

self.closeSec=1693092599, self.tradeDate='20230827', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25999.6', self.close='26005.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15099 

self.closeSec=1693093199, self.tradeDate='20230827', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26005.3', self.close='26012.7'
127.0.0.1 - - [27/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15100 

self.closeSec=1693093799, self.tradeDate='20230827', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26012.6', self.close='25998.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15101 

self.closeSec=1693094399, self.tradeDate='20230827', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25998.6', self.close='26004.2'
127.0.0.1 - - [27/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15102 

self.closeSec=1693094999, self.tradeDate='20230827', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26004.3', self.close='25997.4'
127.0.0.1 - - [27/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15103 

self.closeSec=1693095599, self.tradeDate='20230827', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25997.4', self.close='26006.6'
127.0.0.1 - - [27/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [27/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15098 

self.closeSec=1693092599, self.tradeDate='20230827', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25999.6', self.close='26005.3'
127.0.0.1 - - [27/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15099 

self.closeSec=1693093199, self.tradeDate='20230827', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26005.3', self.close='26012.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15100 

self.closeSec=1693093799, self.tradeDate='20230827', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26012.6', self.close='25998.6'
127.0.0.1 - - [27/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15101 

self.closeSec=1693094399, self.tradeDate='20230827', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25998.6', self.close='26004.2'
127.0.0.1 - - [27/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15102 

self.closeSec=1693094999, self.tradeDate='20230827', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26004.3', self.close='25997.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15103 

self.closeSec=1693095599, self.tradeDate='20230827', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25997.4', self.close='26006.6'
127.0.0.1 - - [27/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30196
self.closeSec=1693095599, self.tradeDate='20230827', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26000.9, self.close=26006.5, self.high=26008.5, self.low=26000.9, self.vol=240.371, self.amt=6250731.6395 
127.0.0.1 - - [27/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-27 08:20:05,329:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230827   075500    075959  ...         0.0        0.0       0
5844  20230827   080000    080459  ...         0.0        0.0       0
5845  20230827   080500    080959  ...         0.0        0.0       0
5846  20230827   081000    081459  ...         0.0        0.0       0
5847  20230827   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 08:20:05,331:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693095599, self.tradeDate='20230827', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26000.9, self.close=26006.5, self.high=26008.5, self.low=26000.9, self.vol=240.371, self.amt=6250731.6395, ukdf['pct'].iloc[-1]=0.000212 , ukdf['amount'].iloc[-1]=6250731.6395, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31036.92318581595', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26008.34874705', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30197
self.closeSec=1693095899, self.tradeDate='20230827', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26006.5, self.close=26014.2, self.high=26014.2, self.low=26004.7, self.vol=191.388, self.amt=4977981.112 
127.0.0.1 - - [27/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-27 08:25:00,844:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230827   080000    080459  ...         0.0        0.0       0
5845  20230827   080500    080959  ...         0.0        0.0       0
5846  20230827   081000    081459  ...         0.0        0.0       0
5847  20230827   081500    081959  ...         0.0        0.0       0
5848  20230827   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-27 08:25:00,845:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693095899, self.tradeDate='20230827', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26006.5, self.close=26014.2, self.high=26014.2, self.low=26004.7, self.vol=191.388, self.amt=4977981.112, ukdf['pct'].iloc[-1]=0.000296 , ukdf['amount'].iloc[-1]=4977981.112, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-30789.889', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26015', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230826   200000    235959  1693065599  ...    719  0.155291 -0.455290     NaN
720  20230827   000000    035959  1693079999  ...    720  0.143820 -0.471517     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '175160.46366704636', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26024.01309903', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [27/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=629
self.closeSec=1693094399, self.tradeDate='20230827', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26023.1, self.close=26004.2, self.high=26038.7, self.low=25975.5, self.vol=7354.576, self.amt=191305627.1449 
2023-08-27 08:00:01,526:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693094399, self.tradeDate='20230827', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26023.1, self.close=26004.2, self.high=26038.7, self.low=25975.5, self.vol=7354.576, self.amt=191305627.1449 
2023-08-27 08:00:01,540:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230826   120000    155959  ...   8045.871  2.096201e+08 -0.001407
718  20230826   160000    195959  ...  12714.098  3.307631e+08 -0.000146
719  20230826   200000    235959  ...  12983.287  3.379272e+08  0.000161
720  20230827   000000    035959  ...   8874.796  2.308703e+08 -0.000657
721  20230827   040000    075959  ...   7354.576  1.913056e+08 -0.000722

[5 rows x 11 columns]
2023-08-27 08:00:02,241:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230826   120000    155959  1693036799  ...    717  0.154498 -0.485747     NaN
718  20230826   160000    195959  1693051199  ...    718  0.150684 -0.481358     NaN
719  20230826   200000    235959  1693065599  ...    719  0.155291 -0.455290     NaN
720  20230827   000000    035959  1693079999  ...    720  0.143820 -0.471517     NaN
721  20230827   040000    075959  1693094399  ...    721  0.130818 -0.490147     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '176178.6192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26004.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


