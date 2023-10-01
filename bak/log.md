# 20231001 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40276
self.closeSec=1696119599, self.tradeDate='20231001', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26965.2, self.close=26966.1, self.high=26969.2, self.low=26962.0, self.vol=182.154, self.amt=4911769.9227 
127.0.0.1 - - [01/Oct/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-10-01 08:20:06,680:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231001   075500    075959  ...         0.0        0.0       0
5856  20231001   080000    080459  ...         0.0        0.0       0
5857  20231001   080500    080959  ...         0.0        0.0       0
5858  20231001   081000    081459  ...         0.0        0.0       0
5859  20231001   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 08:20:06,691:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696119599, self.tradeDate='20231001', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26965.2, self.close=26966.1, self.high=26969.2, self.low=26962.0, self.vol=182.154, self.amt=4911769.9227, ukdf['pct'].iloc[-1]=3.7e-05 , ukdf['amount'].iloc[-1]=4911769.9227, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-1416.26797660986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26966.59955311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40277
self.closeSec=1696119899, self.tradeDate='20231001', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26966.0, self.close=26958.0, self.high=26966.1, self.low=26952.1, self.vol=143.43, self.amt=3866447.5517 
2023-10-01 08:25:00,778:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231001   080000    080459  ...         0.0        0.0       0
5857  20231001   080500    080959  ...         0.0        0.0       0
5858  20231001   081000    081459  ...         0.0        0.0       0
5859  20231001   081500    081959  ...         0.0        0.0       0
5860  20231001   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 08:25:00,778:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696119899, self.tradeDate='20231001', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26966.0, self.close=26958.0, self.high=26966.1, self.low=26952.1, self.vol=143.43, self.amt=3866447.5517, ukdf['pct'].iloc[-1]=-0.0003 , ukdf['amount'].iloc[-1]=3866447.5517, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-1296.5106', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26958', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [01/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40274 

self.closeSec=1696118399, self.tradeDate='20231001', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26952.3, self.close=26950.9, self.high=26955.5, self.low=26949.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40275 

self.closeSec=1696118699, self.tradeDate='20231001', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26951.0, self.close=26956.3, self.high=26956.3, self.low=26942.0 
127.0.0.1 - - [01/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40276 

self.closeSec=1696118999, self.tradeDate='20231001', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26956.2, self.close=26960.1, self.high=26961.4, self.low=26954.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40277 

self.closeSec=1696119299, self.tradeDate='20231001', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26960.1, self.close=26965.1, self.high=26974.2, self.low=26960.0 
127.0.0.1 - - [01/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40278 

self.closeSec=1696119599, self.tradeDate='20231001', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26965.2, self.close=26966.1, self.high=26969.2, self.low=26962.0 
127.0.0.1 - - [01/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40279 

self.closeSec=1696119899, self.tradeDate='20231001', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26966.0, self.close=26958.0, self.high=26966.1, self.low=26952.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-01 08:00:17,272:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231001    052959  27049.0  ...  50.833333  0.561018  0.322894
5770  20231001    055959  27049.6  ...  50.833333  0.534217  0.332744
5771  20231001    062959  26984.0  ...  50.833333  0.546287  0.330816
5772  20231001    065959  27019.8  ...  50.833333  0.537045  0.337333
5773  20231001    072959  26996.5  ...  50.416667  0.519158  0.358428

[5 rows x 33 columns]
0.5407407407407407
acc is : 0.5407407407407407
2023-10-01 08:00:17,334:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.496451  0.503549       0  ...  0.990867  -1.0    0.0  0.994879
536     1  0.474825  0.525175       1  ...  0.989552  -1.0    0.0  0.996199
537     0  0.503061  0.496939       0  ...  0.990406  -1.0    0.0  0.995340
538     1  0.485281  0.514719       0  ...  0.992111  -1.0    0.0  0.993625
539     1  0.474308  0.525692       1  ...  0.992078  -1.0    0.0  0.993658

[5 rows x 10 columns]
2023-10-01 08:00:17,346:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496034  0.503966       0  ...  0.990867  -1.0    0.0  0.984455
46     1  0.474390  0.525610       1  ...  0.989552  -1.0    0.0  0.989041
47     0  0.503164  0.496836       0  ...  0.990406  -1.0    0.0  0.989771
48     1  0.485076  0.514924       0  ...  0.992111  -1.0    0.0  0.992381
49     1  0.474308  0.525692       1  ...  0.992078  -1.0    0.0  0.993658

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.689', 'enterprice': '27080', 'countrevence': '0', 'unrealprofit': '3391.94408403897', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26947.96122527', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [01/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20135 

self.closeSec=1696116599, self.tradeDate='20231001', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26982.3', self.close='26950'

--handleKline--: 127.0.0.1 - - [01/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20136 

self.closeSec=1696117199, self.tradeDate='20231001', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26950.1', self.close='26961.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20137 

self.closeSec=1696117799, self.tradeDate='20231001', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26961.8', self.close='26964'
127.0.0.1 - - [01/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20138 

self.closeSec=1696118399, self.tradeDate='20231001', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26963.9', self.close='26950.9'
127.0.0.1 - - [01/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20139 

self.closeSec=1696118999, self.tradeDate='20231001', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26951', self.close='26960.1'
127.0.0.1 - - [01/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20140 

self.closeSec=1696119599, self.tradeDate='20231001', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26960.1', self.close='26966.1'
127.0.0.1 - - [01/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20138 

self.closeSec=1696116599, self.tradeDate='20231001', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26982.3', self.close='26950'
127.0.0.1 - - [01/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20139 

self.closeSec=1696117199, self.tradeDate='20231001', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26950.1', self.close='26961.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20140 

self.closeSec=1696117799, self.tradeDate='20231001', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26961.8', self.close='26964'
127.0.0.1 - - [01/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20141 

self.closeSec=1696118399, self.tradeDate='20231001', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26963.9', self.close='26950.9'
127.0.0.1 - - [01/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20142 

self.closeSec=1696118999, self.tradeDate='20231001', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26951', self.close='26960.1'
127.0.0.1 - - [01/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20143 

self.closeSec=1696119599, self.tradeDate='20231001', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26960.1', self.close='26966.1'
127.0.0.1 - - [01/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20138 

self.closeSec=1696116599, self.tradeDate='20231001', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26982.3', self.close='26950'
127.0.0.1 - - [01/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20139 

self.closeSec=1696117199, self.tradeDate='20231001', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26950.1', self.close='26961.7'
127.0.0.1 - - [01/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20140 

self.closeSec=1696117799, self.tradeDate='20231001', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26961.8', self.close='26964'
127.0.0.1 - - [01/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20141 

self.closeSec=1696118399, self.tradeDate='20231001', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26963.9', self.close='26950.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20142 

self.closeSec=1696118999, self.tradeDate='20231001', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26951', self.close='26960.1'
127.0.0.1 - - [01/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20143 

self.closeSec=1696119599, self.tradeDate='20231001', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26960.1', self.close='26966.1'
127.0.0.1 - - [01/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40276
self.closeSec=1696119599, self.tradeDate='20231001', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26965.2, self.close=26966.1, self.high=26969.2, self.low=26962.0, self.vol=182.154, self.amt=4911769.9227 
127.0.0.1 - - [01/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-01 08:20:06,670:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231001   075500    075959  ...         0.0        0.0       0
5856  20231001   080000    080459  ...         0.0        0.0       0
5857  20231001   080500    080959  ...         0.0        0.0       0
5858  20231001   081000    081459  ...         0.0        0.0       0
5859  20231001   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 08:20:06,673:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696119599, self.tradeDate='20231001', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26965.2, self.close=26966.1, self.high=26969.2, self.low=26962.0, self.vol=182.154, self.amt=4911769.9227, ukdf['pct'].iloc[-1]=3.7e-05 , ukdf['amount'].iloc[-1]=4911769.9227, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '4553.47000205851', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26966.59955311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40277
self.closeSec=1696119899, self.tradeDate='20231001', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26966.0, self.close=26958.0, self.high=26966.1, self.low=26952.1, self.vol=143.43, self.amt=3866447.5517 
2023-10-01 08:25:00,785:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231001   080000    080459  ...         0.0        0.0       0
5857  20231001   080500    080959  ...         0.0        0.0       0
5858  20231001   081000    081459  ...         0.0        0.0       0
5859  20231001   081500    081959  ...         0.0        0.0       0
5860  20231001   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-01 08:25:00,785:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696119899, self.tradeDate='20231001', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26966.0, self.close=26958.0, self.high=26966.1, self.low=26952.1, self.vol=143.43, self.amt=3866447.5517, ukdf['pct'].iloc[-1]=-0.0003 , ukdf['amount'].iloc[-1]=3866447.5517, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '4234.074', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26958', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230930   200000    235959  1696089599  ...    719  0.577577 -0.161830     NaN
720  20231001   000000    035959  1696103999  ...    720  0.515879 -0.307095     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-6866.3064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27011.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [01/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1272444.8790024, self.flagDict['side']='buy', self.tradeCount=27, self.count=839
self.closeSec=1696118399, self.tradeDate='20231001', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27011.2, self.close=26950.9, self.high=27070.4, self.low=26929.8, self.vol=15733.976, self.amt=424848817.4029 
2023-10-01 08:00:01,518:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696118399, self.tradeDate='20231001', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27011.2, self.close=26950.9, self.high=27070.4, self.low=26929.8, self.vol=15733.976, self.amt=424848817.4029 
2023-10-01 08:00:01,531:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230930   120000    155959  ...   9597.371  2.583907e+08  0.000439
718  20230930   160000    195959  ...  13577.888  3.658304e+08  0.000316
719  20230930   200000    235959  ...  28819.566  7.776740e+08  0.002295
720  20231001   000000    035959  ...  14178.540  3.827586e+08  0.000923
721  20231001   040000    075959  ...  15733.976  4.248488e+08 -0.002229

[5 rows x 11 columns]
2023-10-01 08:00:02,175:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230930   120000    155959  1696060799  ...    717  0.665911  0.052065     NaN
718  20230930   160000    195959  1696075199  ...    718  0.607552 -0.089134     NaN
719  20230930   200000    235959  1696089599  ...    719  0.577577 -0.161830     NaN
720  20231001   000000    035959  1696103999  ...    720  0.515879 -0.307095     NaN
721  20231001   040000    075959  1696118399  ...    721  0.464797 -0.427593     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-9694.4367', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26950.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


