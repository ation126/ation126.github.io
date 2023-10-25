# 20231025 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47188
self.closeSec=1698193199, self.tradeDate='20231025', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=33844.4, self.close=33925.1, self.high=33934.6, self.low=33831.2, self.vol=1224.09, self.amt=41475792.3035 
127.0.0.1 - - [25/Oct/2023 08:20:07] "POST / HTTP/1.1" 200 -
2023-10-25 08:20:10,813:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231025   075500    075959  ...         0.0        0.0       0
5856  20231025   080000    080459  ...         0.0        0.0       0
5857  20231025   080500    080959  ...         0.0        0.0       0
5858  20231025   081000    081459  ...         0.0        0.0       0
5859  20231025   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 08:20:10,824:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698193199, self.tradeDate='20231025', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=33844.4, self.close=33925.1, self.high=33934.6, self.low=33831.2, self.vol=1224.09, self.amt=41475792.3035, ukdf['pct'].iloc[-1]=0.002284 , ukdf['amount'].iloc[-1]=41475792.3035, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-98640.35713043688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '33948.07945788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47189
self.closeSec=1698193499, self.tradeDate='20231025', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=33925.0, self.close=33914.6, self.high=33955.2, self.low=33872.2, self.vol=676.058, self.amt=22932264.0007 
127.0.0.1 - - [25/Oct/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-10-25 08:25:03,636:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231025   080000    080459  ...         0.0        0.0       0
5857  20231025   080500    080959  ...         0.0        0.0       0
5858  20231025   081000    081459  ...         0.0        0.0       0
5859  20231025   081500    081959  ...         0.0        0.0       0
5860  20231025   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 08:25:03,638:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698193499, self.tradeDate='20231025', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=33925.0, self.close=33914.6, self.high=33955.2, self.low=33872.2, self.vol=676.058, self.amt=22932264.0007, ukdf['pct'].iloc[-1]=-0.00031 , ukdf['amount'].iloc[-1]=22932264.0007, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-98189.4408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '33915.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47186 

self.closeSec=1698191999, self.tradeDate='20231025', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=33854.2, self.close=33922.5, self.high=33930.3, self.low=33853.7 
127.0.0.1 - - [25/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47187 

self.closeSec=1698192299, self.tradeDate='20231025', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=33917.0, self.close=33926.0, self.high=33956.8, self.low=33893.6 
127.0.0.1 - - [25/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47188 

self.closeSec=1698192599, self.tradeDate='20231025', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=33927.3, self.close=33929.6, self.high=33950.0, self.low=33900.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47189127.0.0.1 - - [25/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -
 

self.closeSec=1698192899, self.tradeDate='20231025', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=33929.6, self.close=33847.8, self.high=33967.0, self.low=33831.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47190 

self.closeSec=1698193199, self.tradeDate='20231025', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=33844.4, self.close=33925.1, self.high=33934.6, self.low=33831.2 
127.0.0.1 - - [25/Oct/2023 08:20:07] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47191 

self.closeSec=1698193499, self.tradeDate='20231025', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=33925.0, self.close=33914.6, self.high=33955.2, self.low=33872.2 
127.0.0.1 - - [25/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-25 08:00:17,652:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231025    052959  33659.1  ...  57.083333  0.573805  0.470257
5770  20231025    055959  33702.5  ...  57.500000  0.597513  0.476579
5771  20231025    062959  34123.3  ...  57.083333  0.593599  0.478700
5772  20231025    065959  34087.7  ...  57.500000  0.597059  0.476608
5773  20231025    072959  34152.6  ...  57.083333  0.578040  0.484639

[5 rows x 33 columns]
0.5481481481481482
acc is : 0.5481481481481482
2023-10-25 08:00:17,717:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.532258  0.467742       1  ...  1.098615   1.0    0.0  1.275870
536     0  0.639059  0.360941       0  ...  1.096986   1.0    0.0  1.273979
537     0  0.541839  0.458161       1  ...  1.099078   1.0    0.0  1.276408
538     0  0.560762  0.439238       0  ...  1.091155   1.0    0.0  1.267207
539     1  0.493481  0.506519       1  ...  1.091673   1.0    0.0  1.267809

[5 rows x 10 columns]
2023-10-25 08:00:17,728:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.532158  0.467842       1  ...  1.098615   1.0    0.0  1.278924
46     0  0.639367  0.360633       0  ...  1.096986   1.0    0.0  1.273541
47     0  0.541339  0.458661       1  ...  1.099078   1.0    0.0  1.275083
48     0  0.560408  0.439592       0  ...  1.091155   1.0    0.0  1.269156
49     1  0.493481  0.506519       1  ...  1.091673   1.0    0.0  1.267809

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '20.978', 'enterprice': '33828.2', 'countrevence': '0', 'unrealprofit': '1567.0566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33902.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23591 

self.closeSec=1698190199, self.tradeDate='20231025', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='33989.9', self.close='33906.4'
127.0.0.1 - - [25/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23592 

self.closeSec=1698190799, self.tradeDate='20231025', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='33912.8', self.close='33802'
127.0.0.1 - - [25/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23593 

self.closeSec=1698191399, self.tradeDate='20231025', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='33800.4', self.close='33828'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23594 

self.closeSec=1698191999, self.tradeDate='20231025', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='33827.9', self.close='33922.5'
127.0.0.1 - - [25/Oct/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23595 

self.closeSec=1698192599, self.tradeDate='20231025', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='33917', self.close='33929.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23596 

self.closeSec=1698193199, self.tradeDate='20231025', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='33929.6', self.close='33925.1'
127.0.0.1 - - [25/Oct/2023 08:20:08] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23594 

self.closeSec=1698190199, self.tradeDate='20231025', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='33989.9', self.close='33906.4'
127.0.0.1 - - [25/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23595 

self.closeSec=1698190799, self.tradeDate='20231025', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='33912.8', self.close='33802'
127.0.0.1 - - [25/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23596 

self.closeSec=1698191399, self.tradeDate='20231025', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='33800.4', self.close='33828'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23597 

self.closeSec=1698191999, self.tradeDate='20231025', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='33827.9', self.close='33922.5'
127.0.0.1 - - [25/Oct/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23598 

self.closeSec=1698192599, self.tradeDate='20231025', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='33917', self.close='33929.6'
127.0.0.1 - - [25/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23599 

self.closeSec=1698193199, self.tradeDate='20231025', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='33929.6', self.close='33925.1'
127.0.0.1 - - [25/Oct/2023 08:20:08] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23594 

self.closeSec=1698190199, self.tradeDate='20231025', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='33989.9', self.close='33906.4'
127.0.0.1 - - [25/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23595 

self.closeSec=1698190799, self.tradeDate='20231025', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='33912.8', self.close='33802'
127.0.0.1 - - [25/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23596 

self.closeSec=1698191399, self.tradeDate='20231025', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='33800.4', self.close='33828'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23597 

self.closeSec=1698191999, self.tradeDate='20231025', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='33827.9', self.close='33922.5'
127.0.0.1 - - [25/Oct/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23598 

self.closeSec=1698192599, self.tradeDate='20231025', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='33917', self.close='33929.6'
127.0.0.1 - - [25/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23599 

self.closeSec=1698193199, self.tradeDate='20231025', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='33929.6', self.close='33925.1'
127.0.0.1 - - [25/Oct/2023 08:20:08] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47188
self.closeSec=1698193199, self.tradeDate='20231025', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=33844.4, self.close=33925.1, self.high=33934.6, self.low=33831.2, self.vol=1224.09, self.amt=41475792.3035 
127.0.0.1 - - [25/Oct/2023 08:20:07] "POST / HTTP/1.1" 200 -
2023-10-25 08:20:10,834:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231025   075500    075959  ...         0.0        0.0       0
5856  20231025   080000    080459  ...         0.0        0.0       0
5857  20231025   080500    080959  ...         0.0        0.0       0
5858  20231025   081000    081459  ...         0.0        0.0       0
5859  20231025   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 08:20:10,844:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698193199, self.tradeDate='20231025', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=33844.4, self.close=33925.1, self.high=33934.6, self.low=33831.2, self.vol=1224.09, self.amt=41475792.3035, ukdf['pct'].iloc[-1]=0.002284 , ukdf['amount'].iloc[-1]=41475792.3035, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '263852.61514512108', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33948.07945788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47189
self.closeSec=1698193499, self.tradeDate='20231025', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=33925.0, self.close=33914.6, self.high=33955.2, self.low=33872.2, self.vol=676.058, self.amt=22932264.0007 
127.0.0.1 - - [25/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-25 08:25:03,639:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231025   080000    080459  ...         0.0        0.0       0
5857  20231025   080500    080959  ...         0.0        0.0       0
5858  20231025   081000    081459  ...         0.0        0.0       0
5859  20231025   081500    081959  ...         0.0        0.0       0
5860  20231025   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 08:25:03,641:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698193499, self.tradeDate='20231025', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=33925.0, self.close=33914.6, self.high=33955.2, self.low=33872.2, self.vol=676.058, self.amt=22932264.0007, ukdf['pct'].iloc[-1]=-0.00031 , ukdf['amount'].iloc[-1]=22932264.0007, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '262650.0097', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33915.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231024   200000    235959  1698163199  ...    719  1.481802  0.996100     1.0
720  20231025   000000    035959  1698177599  ...    720  1.422184  0.884482     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '175873.84148635488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33791.36608608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=983
self.closeSec=1698191999, self.tradeDate='20231025', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=33792.0, self.close=33917.0, self.high=34307.5, self.low=33485.3, self.vol=87728.961, self.amt=2975642198.58893 
127.0.0.1 - - [25/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-25 08:00:01,673:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698191999, self.tradeDate='20231025', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=33792.0, self.close=33917.0, self.high=34307.5, self.low=33485.3, self.vol=87728.961, self.amt=2975642198.58893 
2023-10-25 08:00:01,706:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231024   120000    155959  ...  120908.224  4.124627e+09 -0.001212
718  20231024   160000    195959  ...  105260.938  3.621561e+09  0.015403
719  20231024   200000    235959  ...  208256.417  7.087042e+09 -0.025305
720  20231025   000000    035959  ...  118528.892  4.012456e+09  0.003457
721  20231025   040000    075959  ...   87728.961  2.975642e+09  0.003699

[5 rows x 11 columns]
2023-10-25 08:00:02,559:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231024   120000    155959  1698134399  ...    717  1.695636  1.365441     1.0
718  20231024   160000    195959  1698148799  ...    718  1.405727  0.901744     1.0
719  20231024   200000    235959  1698163199  ...    719  1.481802  0.996100     1.0
720  20231025   000000    035959  1698177599  ...    720  1.422184  0.884482     1.0
721  20231025   040000    075959  1698191999  ...    721  1.339134  0.738939     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '181105.17084261015', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33917.84584615', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


