# 20231005 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41428
self.closeSec=1696465199, self.tradeDate='20231005', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27725.1, self.close=27722.6, self.high=27756.4, self.low=27722.5, self.vol=527.129, self.amt=14621544.2678 
127.0.0.1 - - [05/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-05 08:20:06,449:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231005   075500    075959  ...         0.0        0.0       0
5856  20231005   080000    080459  ...         0.0        0.0       0
5857  20231005   080500    080959  ...         0.0        0.0       0
5858  20231005   081000    081459  ...         0.0        0.0       0
5859  20231005   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 08:20:06,453:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696465199, self.tradeDate='20231005', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27725.1, self.close=27722.6, self.high=27756.4, self.low=27722.5, self.vol=527.129, self.amt=14621544.2678, ukdf['pct'].iloc[-1]=-1.8e-05 , ukdf['amount'].iloc[-1]=14621544.2678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11923.17401200398', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27721.08081373', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41429
self.closeSec=1696465499, self.tradeDate='20231005', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27722.5, self.close=27705.0, self.high=27728.4, self.low=27705.0, self.vol=587.966, self.amt=16296094.3836 
127.0.0.1 - - [05/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-05 08:25:00,866:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231005   080000    080459  ...         0.0        0.0       0
5857  20231005   080500    080959  ...         0.0        0.0       0
5858  20231005   081000    081459  ...         0.0        0.0       0
5859  20231005   081500    081959  ...         0.0        0.0       0
5860  20231005   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 08:25:00,867:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696465499, self.tradeDate='20231005', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27722.5, self.close=27705.0, self.high=27728.4, self.low=27705.0, self.vol=587.966, self.amt=16296094.3836, ukdf['pct'].iloc[-1]=-0.000635 , ukdf['amount'].iloc[-1]=16296094.3836, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11702.26936915146', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27705.21806471', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [05/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41426 

self.closeSec=1696463999, self.tradeDate='20231005', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27763.8, self.close=27759.7, self.high=27771.9, self.low=27759.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41427 

self.closeSec=1696464299, self.tradeDate='20231005', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27759.7, self.close=27731.8, self.high=27776.1, self.low=27730.5 
127.0.0.1 - - [05/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41428 

self.closeSec=1696464599, self.tradeDate='20231005', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27732.9, self.close=27723.4, self.high=27745.1, self.low=27720.9 
127.0.0.1 - - [05/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41429 

self.closeSec=1696464899, self.tradeDate='20231005', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27724.2, self.close=27723.1, self.high=27757.1, self.low=27716.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41430 

self.closeSec=1696465199, self.tradeDate='20231005', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27725.1, self.close=27722.6, self.high=27756.4, self.low=27722.5 
127.0.0.1 - - [05/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41431 

self.closeSec=1696465499, self.tradeDate='20231005', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27722.5, self.close=27705.0, self.high=27728.4, self.low=27705.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-05 08:00:20,004:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231005    052959  27633.4  ...  57.083333  0.538944  0.291285
5770  20231005    055959  27715.3  ...  57.083333  0.529974  0.291827
5771  20231005    062959  27671.0  ...  57.083333  0.532002  0.291557
5772  20231005    065959  27682.5  ...  57.083333  0.542376  0.283740
5773  20231005    072959  27740.5  ...  57.083333  0.548101  0.272207

[5 rows x 33 columns]
0.5703703703703704
acc is : 0.5703703703703704
2023-10-05 08:00:20,077:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.522978  0.477022       0  ...  0.952050  -1.0    0.0  1.040866
536     1  0.484458  0.515542       1  ...  0.951662  -1.0    0.0  1.041291
537     0  0.505361  0.494639       1  ...  0.949661  -1.0    0.0  1.043480
538     0  0.517113  0.482887       1  ...  0.948545  -1.0    0.0  1.044706
539     0  0.514291  0.485709       0  ...  0.949006  -1.0    0.0  1.044198

[5 rows x 10 columns]
2023-10-05 08:00:20,092:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.522866  0.477134       0  ...  0.952050  -1.0    0.0  1.041539
46     1  0.484639  0.515361       1  ...  0.951662  -1.0    0.0  1.042695
47     0  0.505337  0.494663       1  ...  0.949661  -1.0    0.0  1.043186
48     0  0.517244  0.482756       1  ...  0.948545  -1.0    0.0  1.044958
49     0  0.514291  0.485709       0  ...  0.949006  -1.0    0.0  1.044198

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.906', 'enterprice': '28298.9', 'countrevence': '0', 'unrealprofit': '12655.8364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27769.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20711 

self.closeSec=1696462199, self.tradeDate='20231005', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27801.6', self.close='27773.2'
127.0.0.1 - - [05/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20712 

self.closeSec=1696462799, self.tradeDate='20231005', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27773.1', self.close='27794.4'
127.0.0.1 - - [05/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20713 

self.closeSec=1696463399, self.tradeDate='20231005', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27793.8', self.close='27770.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20714 

self.closeSec=1696463999, self.tradeDate='20231005', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27770.3', self.close='27759.7'
127.0.0.1 - - [05/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20715 

self.closeSec=1696464599, self.tradeDate='20231005', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27759.7', self.close='27723.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20716 

self.closeSec=1696465199, self.tradeDate='20231005', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27724.2', self.close='27722.6'
127.0.0.1 - - [05/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [05/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20714 

self.closeSec=1696462199, self.tradeDate='20231005', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27801.6', self.close='27773.2'

--handleKline--:  127.0.0.1 - - [05/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20715 

self.closeSec=1696462799, self.tradeDate='20231005', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27773.1', self.close='27794.4'

--handleKline--: 127.0.0.1 - - [05/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20716 

self.closeSec=1696463399, self.tradeDate='20231005', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27793.8', self.close='27770.3'
127.0.0.1 - - [05/Oct/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20717 

self.closeSec=1696463999, self.tradeDate='20231005', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27770.3', self.close='27759.7'
127.0.0.1 - - [05/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20718 

self.closeSec=1696464599, self.tradeDate='20231005', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27759.7', self.close='27723.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20719 

self.closeSec=1696465199, self.tradeDate='20231005', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27724.2', self.close='27722.6'
127.0.0.1 - - [05/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [05/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20714 

self.closeSec=1696462199, self.tradeDate='20231005', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27801.6', self.close='27773.2'
127.0.0.1 - - [05/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20715 

self.closeSec=1696462799, self.tradeDate='20231005', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27773.1', self.close='27794.4'
127.0.0.1 - - [05/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20716 

self.closeSec=1696463399, self.tradeDate='20231005', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27793.8', self.close='27770.3'
127.0.0.1 - - [05/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20717 

self.closeSec=1696463999, self.tradeDate='20231005', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27770.3', self.close='27759.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20718 

self.closeSec=1696464599, self.tradeDate='20231005', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27759.7', self.close='27723.4'
127.0.0.1 - - [05/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20719 

self.closeSec=1696465199, self.tradeDate='20231005', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27724.2', self.close='27722.6'
127.0.0.1 - - [05/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41428
self.closeSec=1696465199, self.tradeDate='20231005', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27725.1, self.close=27722.6, self.high=27756.4, self.low=27722.5, self.vol=527.129, self.amt=14621544.2678 
127.0.0.1 - - [05/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-05 08:20:06,448:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231005   075500    075959  ...         0.0        0.0       0
5856  20231005   080000    080459  ...         0.0        0.0       0
5857  20231005   080500    080959  ...         0.0        0.0       0
5858  20231005   081000    081459  ...         0.0        0.0       0
5859  20231005   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 08:20:06,452:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696465199, self.tradeDate='20231005', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27725.1, self.close=27722.6, self.high=27756.4, self.low=27722.5, self.vol=527.129, self.amt=14621544.2678, ukdf['pct'].iloc[-1]=-1.8e-05 , ukdf['amount'].iloc[-1]=14621544.2678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '32575.65850274593', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27721.08081373', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41429
self.closeSec=1696465499, self.tradeDate='20231005', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27722.5, self.close=27705.0, self.high=27728.4, self.low=27705.0, self.vol=587.966, self.amt=16296094.3836 
2023-10-05 08:25:00,869:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231005   080000    080459  ...         0.0        0.0       0
5857  20231005   080500    080959  ...         0.0        0.0       0
5858  20231005   081000    081459  ...         0.0        0.0       0
5859  20231005   081500    081959  ...         0.0        0.0       0
5860  20231005   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-05 08:25:00,869:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696465499, self.tradeDate='20231005', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27722.5, self.close=27705.0, self.high=27728.4, self.low=27705.0, self.vol=587.966, self.amt=16296094.3836, ukdf['pct'].iloc[-1]=-0.000635 , ukdf['amount'].iloc[-1]=16296094.3836, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '31986.50014139411', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27705.21806471', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231004   200000    235959  1696435199  ...    719  0.955153  0.504670     NaN
720  20231005   000000    035959  1696449599  ...    720  0.921129  0.440461     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-17864.522', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27607', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [05/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1223948.6721539998, self.flagDict['side']='buy', self.tradeCount=29, self.count=863
self.closeSec=1696463999, self.tradeDate='20231005', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27606.3, self.close=27759.7, self.high=27824.0, self.low=27550.0, self.vol=34252.297, self.amt=949015466.64162 
2023-10-05 08:00:01,593:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696463999, self.tradeDate='20231005', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27606.3, self.close=27759.7, self.high=27824.0, self.low=27550.0, self.vol=34252.297, self.amt=949015466.64162 
2023-10-05 08:00:01,606:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231004   120000    155959  ...  18070.915  4.949720e+08  0.000883
718  20231004   160000    195959  ...  43059.184  1.185835e+09  0.004304
719  20231004   200000    235959  ...  55560.010  1.525355e+09 -0.006226
720  20231005   000000    035959  ...  72612.137  2.005745e+09  0.007908
721  20231005   040000    075959  ...  34252.297  9.490155e+08  0.005604

[5 rows x 11 columns]
2023-10-05 08:00:02,320:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231004   120000    155959  1696406399  ...    717  1.082437  0.808364     1.0
718  20231004   160000    195959  1696420799  ...    718  1.012130  0.633837     1.0
719  20231004   200000    235959  1696435199  ...    719  0.955153  0.504670     NaN
720  20231005   000000    035959  1696449599  ...    720  0.921129  0.440461     NaN
721  20231005   040000    075959  1696463999  ...    721  0.842262  0.259653     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-10991.03587961548', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27764.17291961', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


