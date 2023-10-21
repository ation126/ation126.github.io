# 20231021 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46036
self.closeSec=1697847599, self.tradeDate='20231021', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29646.6, self.close=29648.7, self.high=29673.5, self.low=29641.1, self.vol=359.645, self.amt=10665362.3428 
127.0.0.1 - - [21/Oct/2023 08:20:12] "POST / HTTP/1.1" 200 -
2023-10-21 08:20:19,384:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231021   075500    075959  ...         0.0        0.0       0
5856  20231021   080000    080459  ...         0.0        0.0       0
5857  20231021   080500    080959  ...         0.0        0.0       0
5858  20231021   081000    081459  ...         0.0        0.0       0
5859  20231021   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 08:20:19,402:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697847599, self.tradeDate='20231021', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29646.6, self.close=29648.7, self.high=29673.5, self.low=29641.1, self.vol=359.645, self.amt=10665362.3428, ukdf['pct'].iloc[-1]=7.1e-05 , ukdf['amount'].iloc[-1]=10665362.3428, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-38783.06689043688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29649.83945788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46037
self.closeSec=1697847899, self.tradeDate='20231021', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29648.7, self.close=29658.8, self.high=29660.5, self.low=29635.3, self.vol=442.296, self.amt=13113181.0963 
127.0.0.1 - - [21/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-21 08:25:03,564:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231021   080000    080459  ...         0.0        0.0       0
5857  20231021   080500    080959  ...         0.0        0.0       0
5858  20231021   081000    081459  ...         0.0        0.0       0
5859  20231021   081500    081959  ...         0.0        0.0       0
5860  20231021   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 08:25:03,565:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697847899, self.tradeDate='20231021', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29648.7, self.close=29658.8, self.high=29660.5, self.low=29635.3, self.vol=442.296, self.amt=13113181.0963, ukdf['pct'].iloc[-1]=0.000341 , ukdf['amount'].iloc[-1]=13113181.0963, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-38875.33197103116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29656.46484066', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [21/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46034 

self.closeSec=1697846399, self.tradeDate='20231021', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29655.1, self.close=29653.1, self.high=29657.9, self.low=29638.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46035 

self.closeSec=1697846699, self.tradeDate='20231021', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29653.0, self.close=29658.6, self.high=29667.5, self.low=29638.7 
127.0.0.1 - - [21/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46036 

self.closeSec=1697846999, self.tradeDate='20231021', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29659.0, self.close=29668.6, self.high=29678.6, self.low=29656.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46037 

self.closeSec=1697847299, self.tradeDate='20231021', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29667.8, self.close=29646.6, self.high=29667.8, self.low=29645.5 
127.0.0.1 - - [21/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46038 

self.closeSec=1697847599, self.tradeDate='20231021', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29646.6, self.close=29648.7, self.high=29673.5, self.low=29641.1 
127.0.0.1 - - [21/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46039 

self.closeSec=1697847899, self.tradeDate='20231021', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29648.7, self.close=29658.8, self.high=29660.5, self.low=29635.3 
127.0.0.1 - - [21/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-21 08:00:17,619:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231021    052959  29565.9  ...  53.333333  0.597728  0.363429
5770  20231021    055959  29593.4  ...  53.333333  0.598335  0.365726
5771  20231021    062959  29597.9  ...  53.333333  0.601176  0.369276
5772  20231021    065959  29619.1  ...  53.750000  0.607067  0.373602
5773  20231021    072959  29649.3  ...  54.166667  0.617580  0.378251

[5 rows x 33 columns]
0.562962962962963
acc is : 0.562962962962963
2023-10-21 08:00:17,687:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.524963  0.475037       1  ...  0.977004  -1.0    0.0  1.073305
536     0  0.521470  0.478530       1  ...  0.976318  -1.0    0.0  1.074060
537     0  0.519796  0.480204       1  ...  0.974894  -1.0    0.0  1.075626
538     0  0.528246  0.471754       1  ...  0.972304  -1.0    0.0  1.078484
539     0  0.542796  0.457204       0  ...  0.975168  -1.0    0.0  1.075307

[5 rows x 10 columns]
2023-10-21 08:00:17,699:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524789  0.475211       1  ...  0.977004  -1.0    0.0  1.078912
46     0  0.520903  0.479097       1  ...  0.976318  -1.0    0.0  1.081847
47     0  0.519282  0.480718       1  ...  0.974894  -1.0    0.0  1.082958
48     0  0.527725  0.472275       1  ...  0.972304  -1.0    0.0  1.083237
49     0  0.542796  0.457204       0  ...  0.975168  -1.0    0.0  1.075307

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.539', 'enterprice': '29526.5', 'countrevence': '0', 'unrealprofit': '-2722.5296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29652.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [21/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23015 

self.closeSec=1697844599, self.tradeDate='20231021', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29690.1', self.close='29740.7'
127.0.0.1 - - [21/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23016 

self.closeSec=1697845199, self.tradeDate='20231021', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29740.7', self.close='29657.1'
127.0.0.1 - - [21/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23017 

self.closeSec=1697845799, self.tradeDate='20231021', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29657.1', self.close='29681.2'
127.0.0.1 - - [21/Oct/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23018 

self.closeSec=1697846399, self.tradeDate='20231021', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29681.3', self.close='29653'
127.0.0.1 - - [21/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23019 

self.closeSec=1697846999, self.tradeDate='20231021', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29653', self.close='29668.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23020 

self.closeSec=1697847599, self.tradeDate='20231021', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29667.8', self.close='29648.7'
127.0.0.1 - - [21/Oct/2023 08:20:13] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [21/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23018 

self.closeSec=1697844599, self.tradeDate='20231021', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29690.1', self.close='29740.7'
127.0.0.1 - - [21/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23019 

self.closeSec=1697845199, self.tradeDate='20231021', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29740.7', self.close='29657.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23020 

self.closeSec=1697845799, self.tradeDate='20231021', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29657.1', self.close='29681.2'
127.0.0.1 - - [21/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23021 

self.closeSec=1697846399, self.tradeDate='20231021', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29681.3', self.close='29653'
127.0.0.1 - - [21/Oct/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23022 

self.closeSec=1697846999, self.tradeDate='20231021', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29653', self.close='29668.6'
127.0.0.1 - - [21/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23023 

self.closeSec=1697847599, self.tradeDate='20231021', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29667.8', self.close='29648.7'
127.0.0.1 - - [21/Oct/2023 08:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23018 

self.closeSec=1697844599, self.tradeDate='20231021', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29690.1', self.close='29740.7'
127.0.0.1 - - [21/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23019 

self.closeSec=1697845199, self.tradeDate='20231021', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29740.7', self.close='29657.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23020 

self.closeSec=1697845799, self.tradeDate='20231021', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29657.1', self.close='29681.2'
127.0.0.1 - - [21/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Oct/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23021 

self.closeSec=1697846399, self.tradeDate='20231021', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29681.3', self.close='29653'
127.0.0.1 - - [21/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23022 

self.closeSec=1697846999, self.tradeDate='20231021', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29653', self.close='29668.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23023 

self.closeSec=1697847599, self.tradeDate='20231021', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29667.8', self.close='29648.7'
127.0.0.1 - - [21/Oct/2023 08:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46036
self.closeSec=1697847599, self.tradeDate='20231021', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29646.6, self.close=29648.7, self.high=29673.5, self.low=29641.1, self.vol=359.645, self.amt=10665362.3428 
127.0.0.1 - - [21/Oct/2023 08:20:12] "POST / HTTP/1.1" 200 -
2023-10-21 08:20:19,383:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231021   075500    075959  ...         0.0        0.0       0
5856  20231021   080000    080459  ...         0.0        0.0       0
5857  20231021   080500    080959  ...         0.0        0.0       0
5858  20231021   081000    081459  ...         0.0        0.0       0
5859  20231021   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 08:20:19,402:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697847599, self.tradeDate='20231021', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29646.6, self.close=29648.7, self.high=29673.5, self.low=29641.1, self.vol=359.645, self.amt=10665362.3428, ukdf['pct'].iloc[-1]=7.1e-05 , ukdf['amount'].iloc[-1]=10665362.3428, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '104209.62626494966', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29649.78407326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46037
self.closeSec=1697847899, self.tradeDate='20231021', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29648.7, self.close=29658.8, self.high=29660.5, self.low=29635.3, self.vol=442.296, self.amt=13113181.0963 
127.0.0.1 - - [21/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-21 08:25:03,563:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231021   080000    080459  ...         0.0        0.0       0
5857  20231021   080500    080959  ...         0.0        0.0       0
5858  20231021   081000    081459  ...         0.0        0.0       0
5859  20231021   081500    081959  ...         0.0        0.0       0
5860  20231021   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-21 08:25:03,565:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697847899, self.tradeDate='20231021', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29648.7, self.close=29658.8, self.high=29660.5, self.low=29635.3, self.vol=442.296, self.amt=13113181.0963, ukdf['pct'].iloc[-1]=0.000341 , ukdf['amount'].iloc[-1]=13113181.0963, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '104457.75664695306', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29656.46484066', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

127.0.0.1 - - [21/Oct/2023 04:00:10] "POST / HTTP/1.1" 200 -
2023-10-21 04:00:10,810:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43035F1697832005205I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697832005615011, 'quantity': '43.755', 'price': '29539.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697832004275, 'updatetime': 1697832005615, 'tradetype': 'usdt', 'selfid': 43035, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697832005615, 'clientorderid': '43035F1697832005205I0L65', 'price': '29539.2', 'quantity': '43.755', 'commission': '1292.487696', 'commissionasset': 'USDT', 'tradetime': 1697832005615, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697832005615}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Oct/2023 04:00:11] "POST / HTTP/1.1" 200 -
2023-10-21 04:00:11,267:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43036F1697832010775I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697832011236808, 'quantity': '41.361', 'price': '29539.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697832010311, 'updatetime': 1697832011236, 'tradetype': 'usdt', 'selfid': 43036, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697832011236, 'clientorderid': '43036F1697832010775I0L65', 'price': '29539.2', 'quantity': '41.361', 'commission': '1221.7708512', 'commissionasset': 'USDT', 'tradetime': 1697832011236, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697832011236}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-21 04:00:11,424:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43036F1697832010775I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697832011236808, 'quantity': '41.361', 'price': '29539.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697832010311, 'updatetime': 1697832011236, 'tradetype': 'usdt', 'selfid': 43036, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697832011236, 'clientorderid': '43036F1697832010775I0L65', 'price': '29539.2', 'quantity': '41.361', 'commission': '1221.7708512', 'commissionasset': 'USDT', 'tradetime': 1697832011236, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697832011236}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Oct/2023 04:00:11] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=959
self.closeSec=1697846399, self.tradeDate='20231021', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29549.8, self.close=29653.1, self.high=29784.5, self.low=29493.9, self.vol=34230.291, self.amt=1014653660.59158 
127.0.0.1 - - [21/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-21 08:00:01,592:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697846399, self.tradeDate='20231021', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29549.8, self.close=29653.1, self.high=29784.5, self.low=29493.9, self.vol=34230.291, self.amt=1014653660.59158 
2023-10-21 08:00:01,605:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231020   120000    155959  ...   65199.235  1.906398e+09  0.000195
718  20231020   160000    195959  ...  187716.424  5.594120e+09  0.020463
719  20231020   200000    235959  ...  114979.415  3.399972e+09 -0.009649
720  20231021   000000    035959  ...   37888.713  1.116360e+09  0.000376
721  20231021   040000    075959  ...   34230.291  1.014654e+09  0.003492

[5 rows x 11 columns]
2023-10-21 08:00:02,306:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231020   120000    155959  1697788799  ...    717  0.008180 -0.962225    -1.0
718  20231020   160000    195959  1697803199  ...    718  0.074023 -0.844133    -1.0
719  20231020   200000    235959  1697817599  ...    719  0.094832 -0.801326    -1.0
720  20231021   000000    035959  1697831999  ...    720  1.157761  0.882013     1.0
721  20231021   040000    075959  1697846399  ...    721  1.157986  0.864808     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '4845.51523623681', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29656.35179121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


