# 20231008 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42292
self.closeSec=1696724399, self.tradeDate='20231008', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27948.1, self.close=27946.7, self.high=27948.1, self.low=27938.8, self.vol=198.794, self.amt=5555145.0472 
127.0.0.1 - - [08/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -
2023-10-08 08:20:09,974:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231008   075500    075959  ...         0.0        0.0       0
5856  20231008   080000    080459  ...         0.0        0.0       0
5857  20231008   080500    080959  ...         0.0        0.0       0
5858  20231008   081000    081459  ...         0.0        0.0       0
5859  20231008   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 08:20:09,993:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696724399, self.tradeDate='20231008', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27948.1, self.close=27946.7, self.high=27948.1, self.low=27938.8, self.vol=198.794, self.amt=5555145.0472, ukdf['pct'].iloc[-1]=-0.000104 , ukdf['amount'].iloc[-1]=5555145.0472, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-15141.7398', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27952.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42293
self.closeSec=1696724699, self.tradeDate='20231008', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27946.6, self.close=27954.3, self.high=27954.4, self.low=27945.1, self.vol=183.897, self.amt=5140054.2347 
2023-10-08 08:25:00,817:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231008   080000    080459  ...         0.0        0.0       0
5857  20231008   080500    080959  ...         0.0        0.0       0
5858  20231008   081000    081459  ...         0.0        0.0       0
5859  20231008   081500    081959  ...         0.0        0.0       0
5860  20231008   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 08:25:00,817:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696724699, self.tradeDate='20231008', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27946.6, self.close=27954.3, self.high=27954.4, self.low=27945.1, self.vol=183.897, self.amt=5140054.2347, ukdf['pct'].iloc[-1]=0.000272 , ukdf['amount'].iloc[-1]=5140054.2347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-15170.9844', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27954.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [08/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42290 

self.closeSec=1696723199, self.tradeDate='20231008', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27940.4, self.close=27943.1, self.high=27943.1, self.low=27936.8 
127.0.0.1 - - [08/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42291 

self.closeSec=1696723499, self.tradeDate='20231008', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27943.0, self.close=27935.8, self.high=27945.0, self.low=27935.8 
127.0.0.1 - - [08/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42292 

self.closeSec=1696723799, self.tradeDate='20231008', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27935.8, self.close=27949.0, self.high=27949.0, self.low=27935.5 
127.0.0.1 - - [08/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42293 

self.closeSec=1696724099, self.tradeDate='20231008', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27949.0, self.close=27949.6, self.high=27952.5, self.low=27944.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42294 

self.closeSec=1696724399, self.tradeDate='20231008', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27948.1, self.close=27946.7, self.high=27948.1, self.low=27938.8 
127.0.0.1 - - [08/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42295 

self.closeSec=1696724699, self.tradeDate='20231008', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27946.6, self.close=27954.3, self.high=27954.4, self.low=27945.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-08 08:00:18,190:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231008    052959  27909.9  ...  51.666667  0.533198  0.669122
5770  20231008    055959  27926.4  ...  51.666667  0.530545  0.660433
5771  20231008    062959  27918.0  ...  51.666667  0.532551  0.649791
5772  20231008    065959  27925.2  ...  51.666667  0.536367  0.635078
5773  20231008    072959  27938.5  ...  51.666667  0.536034  0.621704

[5 rows x 33 columns]
0.5462962962962963
acc is : 0.5462962962962963
2023-10-08 08:00:18,252:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.504086  0.495914       0  ...  0.954694   1.0    0.0  1.067084
536     1  0.497668  0.502332       1  ...  0.954937   1.0    0.0  1.067355
537     0  0.502916  0.497084       1  ...  0.955395   1.0    0.0  1.067867
538     0  0.504950  0.495050       0  ...  0.955361   1.0    0.0  1.067829
539     1  0.498596  0.501404       1  ...  0.955552   1.0    0.0  1.068043

[5 rows x 10 columns]
2023-10-08 08:00:18,264:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503795  0.496205       0  ...  0.954694   1.0    0.0  1.069049
46     1  0.497388  0.502612       1  ...  0.954937   1.0    0.0  1.064937
47     0  0.502819  0.497181       1  ...  0.955395   1.0    0.0  1.066103
48     0  0.504843  0.495157       0  ...  0.955361   1.0    0.0  1.066272
49     1  0.498596  0.501404       1  ...  0.955552   1.0    0.0  1.068043

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.669', 'enterprice': '27936.3', 'countrevence': '0', 'unrealprofit': '108.8774', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27940.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [08/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21143 

self.closeSec=1696721399, self.tradeDate='20231008', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27937.8', self.close='27937.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21144 

self.closeSec=1696721999, self.tradeDate='20231008', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27937.4', self.close='27937.1'
127.0.0.1 - - [08/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21145 

self.closeSec=1696722599, self.tradeDate='20231008', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27937.1', self.close='27935.3'
127.0.0.1 - - [08/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21146 

self.closeSec=1696723199, self.tradeDate='20231008', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27935.3', self.close='27943.1'
127.0.0.1 - - [08/Oct/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21147 

self.closeSec=1696723799, self.tradeDate='20231008', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27943', self.close='27949'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21148 

self.closeSec=1696724399, self.tradeDate='20231008', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27949', self.close='27946.7'
127.0.0.1 - - [08/Oct/2023 08:20:07] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [08/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21146 

self.closeSec=1696721399, self.tradeDate='20231008', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27937.8', self.close='27937.5'
127.0.0.1 - - [08/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21147 

self.closeSec=1696721999, self.tradeDate='20231008', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27937.4', self.close='27937.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21148 

self.closeSec=1696722599, self.tradeDate='20231008', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27937.1', self.close='27935.3'
127.0.0.1 - - [08/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21149 

self.closeSec=1696723199, self.tradeDate='20231008', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27935.3', self.close='27943.1'
127.0.0.1 - - [08/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21150 

self.closeSec=1696723799, self.tradeDate='20231008', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27943', self.close='27949'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21151 

self.closeSec=1696724399, self.tradeDate='20231008', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27949', self.close='27946.7'
127.0.0.1 - - [08/Oct/2023 08:20:07] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [08/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21146 

self.closeSec=1696721399, self.tradeDate='20231008', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27937.8', self.close='27937.5'
127.0.0.1 - - [08/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21147 

self.closeSec=1696721999, self.tradeDate='20231008', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27937.4', self.close='27937.1'

--handleKline--: 127.0.0.1 - - [08/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21148 

self.closeSec=1696722599, self.tradeDate='20231008', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27937.1', self.close='27935.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21149 

self.closeSec=1696723199, self.tradeDate='20231008', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27935.3', self.close='27943.1'
127.0.0.1 - - [08/Oct/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21150 

self.closeSec=1696723799, self.tradeDate='20231008', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27943', self.close='27949'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21151 

self.closeSec=1696724399, self.tradeDate='20231008', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27949', self.close='27946.7'
127.0.0.1 - - [08/Oct/2023 08:20:07] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42292
self.closeSec=1696724399, self.tradeDate='20231008', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27948.1, self.close=27946.7, self.high=27948.1, self.low=27938.8, self.vol=198.794, self.amt=5555145.0472 
127.0.0.1 - - [08/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -
2023-10-08 08:20:09,955:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231008   075500    075959  ...         0.0        0.0       0
5856  20231008   080000    080459  ...         0.0        0.0       0
5857  20231008   080500    080959  ...         0.0        0.0       0
5858  20231008   081000    081459  ...         0.0        0.0       0
5859  20231008   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 08:20:09,966:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696724399, self.tradeDate='20231008', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27948.1, self.close=27946.7, self.high=27948.1, self.low=27938.8, self.vol=198.794, self.amt=5555145.0472, ukdf['pct'].iloc[-1]=-0.000104 , ukdf['amount'].iloc[-1]=5555145.0472, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '41159.6562', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27952.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42293
self.closeSec=1696724699, self.tradeDate='20231008', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27946.6, self.close=27954.3, self.high=27954.4, self.low=27945.1, self.vol=183.897, self.amt=5140054.2347 
127.0.0.1 - - [08/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-08 08:25:00,814:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231008   080000    080459  ...         0.0        0.0       0
5857  20231008   080500    080959  ...         0.0        0.0       0
5858  20231008   081000    081459  ...         0.0        0.0       0
5859  20231008   081500    081959  ...         0.0        0.0       0
5860  20231008   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-08 08:25:00,814:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696724699, self.tradeDate='20231008', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27946.6, self.close=27954.3, self.high=27954.4, self.low=27945.1, self.vol=183.897, self.amt=5140054.2347, ukdf['pct'].iloc[-1]=0.000272 , ukdf['amount'].iloc[-1]=5140054.2347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '41237.6523', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27954.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231007   200000    235959  1696694399  ...    719  0.233707 -1.051917    -1.0
720  20231008   000000    035959  1696708799  ...    720  0.219918 -1.063583    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '4132.9956', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27849.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=881
self.closeSec=1696723199, self.tradeDate='20231008', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27849.7, self.close=27943.1, self.high=27947.8, self.low=27838.5, self.vol=10265.905, self.amt=286559019.4746 
127.0.0.1 - - [08/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-08 08:00:01,577:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696723199, self.tradeDate='20231008', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27849.7, self.close=27943.1, self.high=27947.8, self.low=27838.5, self.vol=10265.905, self.amt=286559019.4746 
2023-10-08 08:00:01,594:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231007   120000    155959  ...  13365.886  3.727963e+08 -0.000455
718  20231007   160000    195959  ...  28790.238  8.048066e+08  0.001837
719  20231007   200000    235959  ...  17899.597  4.998671e+08 -0.000107
720  20231008   000000    035959  ...  19858.010  5.539527e+08 -0.002750
721  20231008   040000    075959  ...  10265.905  2.865590e+08  0.003357

[5 rows x 11 columns]
2023-10-08 08:00:02,388:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231007   120000    155959  1696665599  ...    717  0.227771 -1.107926    -1.0
718  20231007   160000    195959  1696679999  ...    718  0.243351 -1.049194    -1.0
719  20231007   200000    235959  1696694399  ...    719  0.233707 -1.051917    -1.0
720  20231008   000000    035959  1696708799  ...    720  0.219918 -1.063583    -1.0
721  20231008   040000    075959  1696723199  ...    721  0.187564 -1.120572    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '61.0358', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27943', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


