# 20230821 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28468
self.closeSec=1692577199, self.tradeDate='20230821', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26120.3, self.close=26119.8, self.high=26133.6, self.low=26107.8, self.vol=573.926, self.amt=14990806.3053 
127.0.0.1 - - [21/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-21 08:20:05,070:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230821   075500    075959  ...         0.0        0.0       0
5844  20230821   080000    080459  ...         0.0        0.0       0
5845  20230821   080500    080959  ...         0.0        0.0       0
5846  20230821   081000    081459  ...         0.0        0.0       0
5847  20230821   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 08:20:05,074:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692577199, self.tradeDate='20230821', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26120.3, self.close=26119.8, self.high=26133.6, self.low=26107.8, self.vol=573.926, self.amt=14990806.3053, ukdf['pct'].iloc[-1]=-1.9e-05 , ukdf['amount'].iloc[-1]=14990806.3053, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10376.2626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26119.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28469
self.closeSec=1692577499, self.tradeDate='20230821', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26119.8, self.close=26122.7, self.high=26122.7, self.low=26107.1, self.vol=386.474, self.amt=10092111.7816 
2023-08-21 08:25:00,802:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230821   080000    080459  ...         0.0        0.0       0
5845  20230821   080500    080959  ...         0.0        0.0       0
5846  20230821   081000    081459  ...         0.0        0.0       0
5847  20230821   081500    081959  ...         0.0        0.0       0
5848  20230821   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 08:25:00,803:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692577499, self.tradeDate='20230821', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26119.8, self.close=26122.7, self.high=26122.7, self.low=26107.1, self.vol=386.474, self.amt=10092111.7816, ukdf['pct'].iloc[-1]=0.000111 , ukdf['amount'].iloc[-1]=10092111.7816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10337.2698', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26122.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [21/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28466 

self.closeSec=1692575999, self.tradeDate='20230821', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26168.0, self.close=26175.9, self.high=26179.1, self.low=26167.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28467 

self.closeSec=1692576299, self.tradeDate='20230821', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26175.9, self.close=26172.0, self.high=26179.0, self.low=26154.7 
127.0.0.1 - - [21/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28468 

self.closeSec=1692576599, self.tradeDate='20230821', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26171.9, self.close=26137.8, self.high=26183.2, self.low=26137.7 
127.0.0.1 - - [21/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28469 

self.closeSec=1692576899, self.tradeDate='20230821', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26137.7, self.close=26120.3, self.high=26139.4, self.low=26120.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28470 

self.closeSec=1692577199, self.tradeDate='20230821', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26120.3, self.close=26119.8, self.high=26133.6, self.low=26107.8 
127.0.0.1 - - [21/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28471 

self.closeSec=1692577499, self.tradeDate='20230821', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26119.8, self.close=26122.7, self.high=26122.7, self.low=26107.1 
127.0.0.1 - - [21/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-21 08:00:17,220:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230821    052959  26222.8  ...  45.833333  0.485385  0.405229
5770  20230821    055959  26184.6  ...  45.416667  0.480925  0.401532
5771  20230821    062959  26167.3  ...  45.833333  0.488602  0.392594
5772  20230821    065959  26195.0  ...  45.833333  0.488309  0.384469
5773  20230821    072959  26194.0  ...  45.833333  0.479988  0.383068

[5 rows x 33 columns]
0.5333333333333333
acc is : 0.5333333333333333
2023-08-21 08:00:17,285:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.488150  0.511850       0  ...  1.088264  -1.0    0.0  0.888105
536     1  0.485037  0.514963       1  ...  1.087112  -1.0    0.0  0.889045
537     0  0.505699  0.494301       0  ...  1.087158  -1.0    0.0  0.889008
538     1  0.489366  0.510634       0  ...  1.088453  -1.0    0.0  0.887949
539     1  0.476596  0.523404       1  ...  1.087904  -1.0    0.0  0.888397

[5 rows x 10 columns]
2023-08-21 08:00:17,297:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487969  0.512031       0  ...  1.081429  -1.0    0.0  0.879928
46     1  0.485133  0.514867       1  ...  1.080285  -1.0    0.0  0.880522
47     0  0.505867  0.494133       0  ...  1.080330  -1.0    0.0  0.882012
48     1  0.489361  0.510639       0  ...  1.081617  -1.0    0.0  0.886796
49     1  0.476596  0.523404       1  ...  1.087904  -1.0    0.0  0.888397

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '-3259.39440407233', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26177.58540293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14231 

self.closeSec=1692574199, self.tradeDate='20230821', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26151', self.close='26162.7'
127.0.0.1 - - [21/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [21/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14232 

self.closeSec=1692574799, self.tradeDate='20230821', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26162.7', self.close='26171.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14233 

self.closeSec=1692575399, self.tradeDate='20230821', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26171.4', self.close='26162.6'
127.0.0.1 - - [21/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14234 

self.closeSec=1692575999, self.tradeDate='20230821', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26162.6', self.close='26175.9'
127.0.0.1 - - [21/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14235 

self.closeSec=1692576599, self.tradeDate='20230821', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26175.9', self.close='26137.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14236 

self.closeSec=1692577199, self.tradeDate='20230821', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26137.7', self.close='26119.8'
127.0.0.1 - - [21/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [21/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14234 

self.closeSec=1692574199, self.tradeDate='20230821', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26151', self.close='26162.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14235 

self.closeSec=1692574799, self.tradeDate='20230821', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26162.7', self.close='26171.4'
127.0.0.1 - - [21/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14236 

self.closeSec=1692575399, self.tradeDate='20230821', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26171.4', self.close='26162.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14237 

self.closeSec=1692575999, self.tradeDate='20230821', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26162.6', self.close='26175.9'
127.0.0.1 - - [21/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14238 

self.closeSec=1692576599, self.tradeDate='20230821', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26175.9', self.close='26137.8'
127.0.0.1 - - [21/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14239 

self.closeSec=1692577199, self.tradeDate='20230821', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26137.7', self.close='26119.8'
127.0.0.1 - - [21/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [21/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14234 

self.closeSec=1692574199, self.tradeDate='20230821', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26151', self.close='26162.7'
127.0.0.1 - - [21/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14235 

self.closeSec=1692574799, self.tradeDate='20230821', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26162.7', self.close='26171.4'
127.0.0.1 - - [21/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14236 

self.closeSec=1692575399, self.tradeDate='20230821', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26171.4', self.close='26162.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14237 

self.closeSec=1692575999, self.tradeDate='20230821', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26162.6', self.close='26175.9'
127.0.0.1 - - [21/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14238 

self.closeSec=1692576599, self.tradeDate='20230821', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26175.9', self.close='26137.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14239 

self.closeSec=1692577199, self.tradeDate='20230821', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26137.7', self.close='26119.8'
127.0.0.1 - - [21/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28468
self.closeSec=1692577199, self.tradeDate='20230821', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26120.3, self.close=26119.8, self.high=26133.6, self.low=26107.8, self.vol=573.926, self.amt=14990806.3053 
127.0.0.1 - - [21/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-21 08:20:05,073:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230821   075500    075959  ...         0.0        0.0       0
5844  20230821   080000    080459  ...         0.0        0.0       0
5845  20230821   080500    080959  ...         0.0        0.0       0
5846  20230821   081000    081459  ...         0.0        0.0       0
5847  20230821   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 08:20:05,080:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692577199, self.tradeDate='20230821', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26120.3, self.close=26119.8, self.high=26133.6, self.low=26107.8, self.vol=573.926, self.amt=14990806.3053, ukdf['pct'].iloc[-1]=-1.9e-05 , ukdf['amount'].iloc[-1]=14990806.3053, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26897.5122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26119.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [21/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28469
self.closeSec=1692577499, self.tradeDate='20230821', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26119.8, self.close=26122.7, self.high=26122.7, self.low=26107.1, self.vol=386.474, self.amt=10092111.7816 
2023-08-21 08:25:00,816:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230821   080000    080459  ...         0.0        0.0       0
5845  20230821   080500    080959  ...         0.0        0.0       0
5846  20230821   081000    081459  ...         0.0        0.0       0
5847  20230821   081500    081959  ...         0.0        0.0       0
5848  20230821   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 08:25:00,816:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692577499, self.tradeDate='20230821', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26119.8, self.close=26122.7, self.high=26122.7, self.low=26107.1, self.vol=386.474, self.amt=10092111.7816, ukdf['pct'].iloc[-1]=0.000111 , ukdf['amount'].iloc[-1]=10092111.7816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26793.5174', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26122.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230820   200000    235959  1692547199  ...    719  0.535197  0.074747     NaN
720  20230821   000000    035959  1692561599  ...    720  0.512028  0.026201     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '169986.3652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26124.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [21/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=593
self.closeSec=1692575999, self.tradeDate='20230821', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26122.1, self.close=26175.9, self.high=26285.0, self.low=26122.0, self.vol=28522.998, self.amt=746966843.50324 
2023-08-21 08:00:01,557:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692575999, self.tradeDate='20230821', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26122.1, self.close=26175.9, self.high=26285.0, self.low=26122.0, self.vol=28522.998, self.amt=746966843.50324 
2023-08-21 08:00:01,571:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230820   120000    155959  ...  13250.553  3.456046e+08 -0.000663
718  20230820   160000    195959  ...  19743.709  5.157573e+08  0.003463
719  20230820   200000    235959  ...  40356.224  1.052823e+09 -0.002633
720  20230821   000000    035959  ...  21311.523  5.558716e+08  0.001039
721  20230821   040000    075959  ...  28522.998  7.469668e+08  0.002060

[5 rows x 11 columns]
2023-08-21 08:00:02,286:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230820   120000    155959  1692518399  ...    717  0.548425  0.103157     NaN
718  20230820   160000    195959  1692532799  ...    718  0.543268  0.092481     NaN
719  20230820   200000    235959  1692547199  ...    719  0.535197  0.074747     NaN
720  20230821   000000    035959  1692561599  ...    720  0.512028  0.026201     NaN
721  20230821   040000    075959  1692575999  ...    721  0.460951 -0.080190     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '167257.58804721668', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26177.80144689', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


