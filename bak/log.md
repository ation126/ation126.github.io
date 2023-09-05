# 20230905 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32788
self.closeSec=1693873199, self.tradeDate='20230905', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25797.4, self.close=25799.4, self.high=25800.5, self.low=25778.0, self.vol=1031.988, self.amt=26612711.6722 
127.0.0.1 - - [05/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-05 08:20:06,007:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230905   075500    075959  ...         0.0        0.0       0
5844  20230905   080000    080459  ...         0.0        0.0       0
5845  20230905   080500    080959  ...         0.0        0.0       0
5846  20230905   081000    081459  ...         0.0        0.0       0
5847  20230905   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 08:20:06,010:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693873199, self.tradeDate='20230905', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25797.4, self.close=25799.4, self.high=25800.5, self.low=25778.0, self.vol=1031.988, self.amt=26612711.6722, ukdf['pct'].iloc[-1]=7.4e-05 , ukdf['amount'].iloc[-1]=26612711.6722, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14888.2866', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25795.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32789
self.closeSec=1693873499, self.tradeDate='20230905', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25799.4, self.close=25763.4, self.high=25799.5, self.low=25747.2, self.vol=1371.083, self.amt=35321391.9002 
2023-09-05 08:25:00,858:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230905   080000    080459  ...         0.0        0.0       0
5845  20230905   080500    080959  ...         0.0        0.0       0
5846  20230905   081000    081459  ...         0.0        0.0       0
5847  20230905   081500    081959  ...         0.0        0.0       0
5848  20230905   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 08:25:00,858:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693873499, self.tradeDate='20230905', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25799.4, self.close=25763.4, self.high=25799.5, self.low=25747.2, self.vol=1371.083, self.amt=35321391.9002, ukdf['pct'].iloc[-1]=-0.001395 , ukdf['amount'].iloc[-1]=35321391.9002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15345.0594', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25763', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [05/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32786 

self.closeSec=1693871999, self.tradeDate='20230905', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25821.9, self.close=25814.1, self.high=25823.1, self.low=25800.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32787 

self.closeSec=1693872299, self.tradeDate='20230905', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25814.0, self.close=25817.2, self.high=25825.0, self.low=25807.4 
127.0.0.1 - - [05/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32788 

self.closeSec=1693872599, self.tradeDate='20230905', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25817.1, self.close=25824.5, self.high=25826.4, self.low=25817.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32789 

self.closeSec=1693872899, self.tradeDate='20230905', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25824.4, self.close=25797.5, self.high=25833.1, self.low=25791.9 
127.0.0.1 - - [05/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32790 

self.closeSec=1693873199, self.tradeDate='20230905', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25797.4, self.close=25799.4, self.high=25800.5, self.low=25778.0 
127.0.0.1 - - [05/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32791 

self.closeSec=1693873499, self.tradeDate='20230905', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25799.4, self.close=25763.4, self.high=25799.5, self.low=25747.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-05 08:00:16,916:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230905    052959  25823.2  ...  44.166667  0.440668  0.640264
5770  20230905    055959  25757.9  ...  44.166667  0.410387  0.656876
5771  20230905    062959  25664.1  ...  44.583333  0.443265  0.661616
5772  20230905    065959  25743.0  ...  45.000000  0.451366  0.663247
5773  20230905    072959  25763.5  ...  45.000000  0.454094  0.659080

[5 rows x 33 columns]
0.524074074074074
acc is : 0.524074074074074
2023-09-05 08:00:16,980:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.462160  0.537840       0  ...  0.994855  -1.0    0.0  0.985322
536     1  0.451042  0.548958       1  ...  0.991793  -1.0    0.0  0.988355
537     1  0.497878  0.502122       1  ...  0.991003  -1.0    0.0  0.989142
538     1  0.489062  0.510938       1  ...  0.990738  -1.0    0.0  0.989407
539     1  0.490426  0.509574       1  ...  0.989061  -1.0    0.0  0.991081

[5 rows x 10 columns]
2023-09-05 08:00:16,991:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.462285  0.537715       0  ...  1.000970  -1.0    0.0  0.987613
46     1  0.450510  0.549490       1  ...  0.991793  -1.0    0.0  0.987506
47     1  0.497012  0.502988       1  ...  0.991003  -1.0    0.0  0.986964
48     1  0.488671  0.511329       1  ...  0.990738  -1.0    0.0  0.988648
49     1  0.490426  0.509574       1  ...  0.989061  -1.0    0.0  0.991081

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '22686.74660421068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25818.87078764', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16391 

self.closeSec=1693870199, self.tradeDate='20230905', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25758.6', self.close='25770.5'
127.0.0.1 - - [05/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16392 

self.closeSec=1693870799, self.tradeDate='20230905', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25770.4', self.close='25816.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16393 127.0.0.1 - - [05/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -


self.closeSec=1693871399, self.tradeDate='20230905', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25816.6', self.close='25802.4'
127.0.0.1 - - [05/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16394 

self.closeSec=1693871999, self.tradeDate='20230905', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25802.3', self.close='25814.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16395 

self.closeSec=1693872599, self.tradeDate='20230905', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25814', self.close='25824.5'
127.0.0.1 - - [05/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16396 

self.closeSec=1693873199, self.tradeDate='20230905', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25824.4', self.close='25799.4'
127.0.0.1 - - [05/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16394 

self.closeSec=1693870199, self.tradeDate='20230905', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25758.6', self.close='25770.5'
127.0.0.1 - - [05/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [05/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16395 

self.closeSec=1693870799, self.tradeDate='20230905', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25770.4', self.close='25816.6'
127.0.0.1 - - [05/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16396 

self.closeSec=1693871399, self.tradeDate='20230905', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25816.6', self.close='25802.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16397 

self.closeSec=1693871999, self.tradeDate='20230905', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25802.3', self.close='25814.1'
127.0.0.1 - - [05/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16398 

self.closeSec=1693872599, self.tradeDate='20230905', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25814', self.close='25824.5'
127.0.0.1 - - [05/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16399 

self.closeSec=1693873199, self.tradeDate='20230905', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25824.4', self.close='25799.4'
127.0.0.1 - - [05/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [05/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16394 

self.closeSec=1693870199, self.tradeDate='20230905', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25758.6', self.close='25770.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16395 

self.closeSec=1693870799, self.tradeDate='20230905', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25770.4', self.close='25816.6'
127.0.0.1 - - [05/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16396 

self.closeSec=1693871399, self.tradeDate='20230905', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25816.6', self.close='25802.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16397 

self.closeSec=1693871999, self.tradeDate='20230905', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25802.3', self.close='25814.1'
127.0.0.1 - - [05/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16398 

self.closeSec=1693872599, self.tradeDate='20230905', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25814', self.close='25824.5'
127.0.0.1 - - [05/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16399 

self.closeSec=1693873199, self.tradeDate='20230905', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25824.4', self.close='25799.4'
127.0.0.1 - - [05/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32788
self.closeSec=1693873199, self.tradeDate='20230905', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25797.4, self.close=25799.4, self.high=25800.5, self.low=25778.0, self.vol=1031.988, self.amt=26612711.6722 
127.0.0.1 - - [05/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-05 08:20:06,005:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230905   075500    075959  ...         0.0        0.0       0
5844  20230905   080000    080459  ...         0.0        0.0       0
5845  20230905   080500    080959  ...         0.0        0.0       0
5846  20230905   081000    081459  ...         0.0        0.0       0
5847  20230905   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 08:20:06,007:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693873199, self.tradeDate='20230905', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25797.4, self.close=25799.4, self.high=25800.5, self.low=25778.0, self.vol=1031.988, self.amt=26612711.6722, ukdf['pct'].iloc[-1]=7.4e-05 , ukdf['amount'].iloc[-1]=26612711.6722, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38931.1962', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25795.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32789
self.closeSec=1693873499, self.tradeDate='20230905', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25799.4, self.close=25763.4, self.high=25799.5, self.low=25747.2, self.vol=1371.083, self.amt=35321391.9002 
2023-09-05 08:25:00,858:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230905   080000    080459  ...         0.0        0.0       0
5845  20230905   080500    080959  ...         0.0        0.0       0
5846  20230905   081000    081459  ...         0.0        0.0       0
5847  20230905   081500    081959  ...         0.0        0.0       0
5848  20230905   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 08:25:00,859:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693873499, self.tradeDate='20230905', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25799.4, self.close=25763.4, self.high=25799.5, self.low=25747.2, self.vol=1371.083, self.amt=35321391.9002, ukdf['pct'].iloc[-1]=-0.001395 , ukdf['amount'].iloc[-1]=35321391.9002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-40149.421', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25763', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-09-05 04:00:10,383:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42933F1693857604807I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1693857605211529, 'quantity': '57.252', 'price': '25881', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1693857603907, 'updatetime': 1693857605211, 'tradetype': 'usdt', 'selfid': 42933, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1693857605211, 'clientorderid': '42933F1693857604807I0L65', 'price': '25881', 'quantity': '57.252', 'commission': '1481.739012', 'commissionasset': 'USDT', 'tradetime': 1693857605211, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1693857605211}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-05 04:00:10,384:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42933F1693857604807I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1693857605211529, 'quantity': '57.252', 'price': '25881', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1693857603907, 'updatetime': 1693857605211, 'tradetype': 'usdt', 'selfid': 42933, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1693857605211, 'clientorderid': '42933F1693857604807I0L65', 'price': '25881', 'quantity': '57.252', 'commission': '1481.739012', 'commissionasset': 'USDT', 'tradetime': 1693857605211, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1693857605211}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Sep/2023 04:00:10] "POST / HTTP/1.1" 200 -
2023-09-05 04:00:10,811:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42934F1693857610354I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1693857610764830, 'quantity': '57.177', 'price': '25892.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1693857609897, 'updatetime': 1693857610764, 'tradetype': 'usdt', 'selfid': 42934, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1693857610764, 'clientorderid': '42934F1693857610354I0L65', 'price': '25892.3', 'quantity': '57.177', 'commission': '1480.4440371', 'commissionasset': 'USDT', 'tradetime': 1693857610764, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1693857610764}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Sep/2023 04:00:10] "POST / HTTP/1.1" 200 -
2023-09-05 04:00:10,979:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42934F1693857610354I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1693857610764830, 'quantity': '57.177', 'price': '25892.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1693857609897, 'updatetime': 1693857610764, 'tradetype': 'usdt', 'selfid': 42934, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1693857610764, 'clientorderid': '42934F1693857610354I0L65', 'price': '25892.3', 'quantity': '57.177', 'commission': '1480.4440371', 'commissionasset': 'USDT', 'tradetime': 1693857610764, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1693857610764}], 'gatetype': 'simulator', 'handletime': 0}
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=683
self.closeSec=1693871999, self.tradeDate='20230905', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25881.1, self.close=25814.0, self.high=25911.2, self.low=25610.0, self.vol=39711.73, self.amt=1022569773.28737 
127.0.0.1 - - [05/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-05 08:00:01,580:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693871999, self.tradeDate='20230905', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25881.1, self.close=25814.0, self.high=25911.2, self.low=25610.0, self.vol=39711.73, self.amt=1022569773.28737 
2023-09-05 08:00:01,596:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230904   120000    155959  ...  14593.385  3.788325e+08 -0.000782
718  20230904   160000    195959  ...  20972.285  5.434324e+08 -0.002921
719  20230904   200000    235959  ...  53696.797  1.386592e+09 -0.002863
720  20230905   000000    035959  ...  22170.000  5.734570e+08  0.002988
721  20230905   040000    075959  ...  39711.730  1.022570e+09 -0.002589

[5 rows x 11 columns]
2023-09-05 08:00:02,320:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230904   120000    155959  1693814399  ...    717  0.755318  0.994791     1.0
718  20230904   160000    195959  1693828799  ...    718  0.824849  1.177341     1.0
719  20230904   200000    235959  1693843199  ...    719  0.426232  0.042741     NaN
720  20230905   000000    035959  1693857599  ...    720  0.002563 -1.143484    -1.0
721  20230905   040000    075959  1693871999  ...    721  0.000329 -1.127232    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '4467.8445258654', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25814.1594098', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


