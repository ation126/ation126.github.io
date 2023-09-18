# 20230918 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36532
self.closeSec=1694996399, self.tradeDate='20230918', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26515.4, self.close=26502.0, self.high=26526.9, self.low=26502.0, self.vol=350.775, self.amt=9300876.0921 
127.0.0.1 - - [18/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-18 08:20:06,490:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230918   075500    075959  ...         0.0        0.0       0
5856  20230918   080000    080459  ...         0.0        0.0       0
5857  20230918   080500    080959  ...         0.0        0.0       0
5858  20230918   081000    081459  ...         0.0        0.0       0
5859  20230918   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 08:20:06,504:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694996399, self.tradeDate='20230918', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26515.4, self.close=26502.0, self.high=26526.9, self.low=26502.0, self.vol=350.775, self.amt=9300876.0921, ukdf['pct'].iloc[-1]=-0.000509 , ukdf['amount'].iloc[-1]=9300876.0921, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5020.7873568996', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26504.3666554', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36533
self.closeSec=1694996699, self.tradeDate='20230918', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26502.0, self.close=26494.6, self.high=26502.1, self.low=26494.6, self.vol=351.465, self.amt=9313332.5751 
127.0.0.1 - - [18/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-18 08:25:00,790:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230918   080000    080459  ...         0.0        0.0       0
5857  20230918   080500    080959  ...         0.0        0.0       0
5858  20230918   081000    081459  ...         0.0        0.0       0
5859  20230918   081500    081959  ...         0.0        0.0       0
5860  20230918   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 08:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694996699, self.tradeDate='20230918', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26502.0, self.close=26494.6, self.high=26502.1, self.low=26494.6, self.vol=351.465, self.amt=9313332.5751, ukdf['pct'].iloc[-1]=-0.000279 , ukdf['amount'].iloc[-1]=9313332.5751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5144.84169132846', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26495.45854579', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36530 

self.closeSec=1694995199, self.tradeDate='20230918', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26524.4, self.close=26514.3, self.high=26526.0, self.low=26505.8 
127.0.0.1 - - [18/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36531 

self.closeSec=1694995499, self.tradeDate='20230918', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26514.2, self.close=26524.6, self.high=26524.7, self.low=26512.2 
127.0.0.1 - - [18/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36532 

self.closeSec=1694995799, self.tradeDate='20230918', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26521.9, self.close=26534.7, self.high=26544.6, self.low=26516.9 
127.0.0.1 - - [18/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36533 

self.closeSec=1694996099, self.tradeDate='20230918', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26534.7, self.close=26515.5, self.high=26534.8, self.low=26506.9 
127.0.0.1 - - [18/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36534 

self.closeSec=1694996399, self.tradeDate='20230918', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26515.4, self.close=26502.0, self.high=26526.9, self.low=26502.0 
127.0.0.1 - - [18/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36535 

self.closeSec=1694996699, self.tradeDate='20230918', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26502.0, self.close=26494.6, self.high=26502.1, self.low=26494.6 
127.0.0.1 - - [18/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-18 08:00:17,035:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230918    052959  26420.4  ...  52.500000  0.474307  0.515764
5770  20230918    055959  26441.0  ...  52.916667  0.489561  0.520242
5771  20230918    062959  26476.2  ...  52.916667  0.488700  0.525014
5772  20230918    065959  26474.1  ...  52.916667  0.492430  0.527047
5773  20230918    072959  26482.7  ...  52.916667  0.486659  0.532799

[5 rows x 33 columns]
0.5574074074074075
acc is : 0.5574074074074075
2023-09-18 08:00:17,101:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.497324  0.502676       1  ...  0.941690   1.0    0.0  1.024359
536     0  0.503852  0.496148       0  ...  0.941615   1.0    0.0  1.024278
537     1  0.494398  0.505602       1  ...  0.941921   1.0    0.0  1.024611
538     1  0.496692  0.503308       0  ...  0.941434   1.0    0.0  1.024081
539     1  0.493764  0.506236       1  ...  0.943041   1.0    0.0  1.025829

[5 rows x 10 columns]
2023-09-18 08:00:17,114:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497919  0.502081       1  ...  0.941690   1.0    0.0  1.035185
46     0  0.504657  0.495343       0  ...  0.941615   1.0    0.0  1.035868
47     1  0.495025  0.504975       1  ...  0.941921   1.0    0.0  1.035055
48     1  0.497003  0.502997       0  ...  0.941434   1.0    0.0  1.033509
49     1  0.493764  0.506236       1  ...  0.943041   1.0    0.0  1.025829

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '-1992.66256532475', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26517.82681685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18263 

self.closeSec=1694993399, self.tradeDate='20230918', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26458.5', self.close='26469'
127.0.0.1 - - [18/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18264 

self.closeSec=1694993999, self.tradeDate='20230918', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26469', self.close='26471.4'
127.0.0.1 - - [18/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18265 

self.closeSec=1694994599, self.tradeDate='20230918', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26471.4', self.close='26489.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18266 

self.closeSec=1694995199, self.tradeDate='20230918', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26489.8', self.close='26514.2'
127.0.0.1 - - [18/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18267 

self.closeSec=1694995799, self.tradeDate='20230918', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26514.2', self.close='26534.8'
127.0.0.1 - - [18/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18268 

self.closeSec=1694996399, self.tradeDate='20230918', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26534.7', self.close='26502'
127.0.0.1 - - [18/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18266 

self.closeSec=1694993399, self.tradeDate='20230918', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26458.5', self.close='26469'
127.0.0.1 - - [18/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18267127.0.0.1 - - [18/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
 

self.closeSec=1694993999, self.tradeDate='20230918', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26469', self.close='26471.4'
127.0.0.1 - - [18/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18268 

self.closeSec=1694994599, self.tradeDate='20230918', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26471.4', self.close='26489.8'
127.0.0.1 - - [18/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18269 

self.closeSec=1694995199, self.tradeDate='20230918', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26489.8', self.close='26514.2'
127.0.0.1 - - [18/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18270 

self.closeSec=1694995799, self.tradeDate='20230918', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26514.2', self.close='26534.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18271 

self.closeSec=1694996399, self.tradeDate='20230918', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26534.7', self.close='26502'
127.0.0.1 - - [18/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18266 

self.closeSec=1694993399, self.tradeDate='20230918', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26458.5', self.close='26469'
127.0.0.1 - - [18/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18267 

self.closeSec=1694993999, self.tradeDate='20230918', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26469', self.close='26471.4'
127.0.0.1 - - [18/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18268 

self.closeSec=1694994599, self.tradeDate='20230918', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26471.4', self.close='26489.8'
127.0.0.1 - - [18/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18269 

self.closeSec=1694995199, self.tradeDate='20230918', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26489.8', self.close='26514.2'
127.0.0.1 - - [18/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18270 

self.closeSec=1694995799, self.tradeDate='20230918', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26514.2', self.close='26534.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18271 

self.closeSec=1694996399, self.tradeDate='20230918', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26534.7', self.close='26502'
127.0.0.1 - - [18/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36532
self.closeSec=1694996399, self.tradeDate='20230918', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26515.4, self.close=26502.0, self.high=26526.9, self.low=26502.0, self.vol=350.775, self.amt=9300876.0921 
127.0.0.1 - - [18/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-18 08:20:06,496:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230918   075500    075959  ...         0.0        0.0       0
5856  20230918   080000    080459  ...         0.0        0.0       0
5857  20230918   080500    080959  ...         0.0        0.0       0
5858  20230918   081000    081459  ...         0.0        0.0       0
5859  20230918   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 08:20:06,506:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694996399, self.tradeDate='20230918', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26515.4, self.close=26502.0, self.high=26526.9, self.low=26502.0, self.vol=350.775, self.amt=9300876.0921, ukdf['pct'].iloc[-1]=-0.000509 , ukdf['amount'].iloc[-1]=9300876.0921, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12614.3220517886', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26504.3666554', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36533
self.closeSec=1694996699, self.tradeDate='20230918', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26502.0, self.close=26494.6, self.high=26502.1, self.low=26494.6, self.vol=351.465, self.amt=9313332.5751 
2023-09-18 08:25:00,794:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230918   080000    080459  ...         0.0        0.0       0
5857  20230918   080500    080959  ...         0.0        0.0       0
5858  20230918   081000    081459  ...         0.0        0.0       0
5859  20230918   081500    081959  ...         0.0        0.0       0
5860  20230918   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-18 08:25:00,795:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694996699, self.tradeDate='20230918', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26502.0, self.close=26494.6, self.high=26502.1, self.low=26494.6, self.vol=351.465, self.amt=9313332.5751, ukdf['pct'].iloc[-1]=-0.000279 , ukdf['amount'].iloc[-1]=9313332.5751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12945.17815081361', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26495.45854579', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230917   200000    235959  1694966399  ...    719  0.153439 -0.627340    -1.0
720  20230918   000000    035959  1694980799  ...    720  0.123332 -0.735192    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.675', 'enterprice': '26538.7', 'countrevence': '0', 'unrealprofit': '2544.195', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26491.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [18/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1423040.2577775, self.flagDict['side']='sell', self.tradeCount=24, self.count=761
self.closeSec=1694995199, self.tradeDate='20230918', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26491.2, self.close=26514.2, self.high=26526.0, self.low=26377.4, self.vol=24458.481, self.amt=647040706.4158 
2023-09-18 08:00:01,543:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694995199, self.tradeDate='20230918', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26491.2, self.close=26514.2, self.high=26526.0, self.low=26377.4, self.vol=24458.481, self.amt=647040706.4158 
2023-09-18 08:00:01,554:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230917   120000    155959  ...  12207.039  3.237591e+08 -0.001075
718  20230917   160000    195959  ...  18581.011  4.934868e+08  0.002692
719  20230917   200000    235959  ...  15182.625  4.030439e+08 -0.000636
720  20230918   000000    035959  ...  18907.419  5.009485e+08 -0.001726
721  20230918   040000    075959  ...  24458.481  6.470407e+08  0.000868

[5 rows x 11 columns]
2023-09-18 08:00:02,161:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230917   120000    155959  1694937599  ...    717  0.321356  0.008056     NaN
718  20230917   160000    195959  1694951999  ...    718  0.216169 -0.393143     NaN
719  20230917   200000    235959  1694966399  ...    719  0.153439 -0.627340    -1.0
720  20230918   000000    035959  1694980799  ...    720  0.123332 -0.735192    -1.0
721  20230918   040000    075959  1694995199  ...    721  0.105896 -0.793562    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.675', 'enterprice': '26538.7', 'countrevence': '0', 'unrealprofit': '1263.00735373575', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26515.16935531', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


