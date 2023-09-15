# 20230915 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35668
self.closeSec=1694737199, self.tradeDate='20230915', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26490.7, self.close=26476.6, self.high=26499.4, self.low=26472.3, self.vol=500.69, self.amt=13260058.4541 
127.0.0.1 - - [15/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-15 08:20:06,742:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230915   075500    075959  ...         0.0        0.0       0
5856  20230915   080000    080459  ...         0.0        0.0       0
5857  20230915   080500    080959  ...         0.0        0.0       0
5858  20230915   081000    081459  ...         0.0        0.0       0
5859  20230915   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 08:20:06,752:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694737199, self.tradeDate='20230915', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26490.7, self.close=26476.6, self.high=26499.4, self.low=26472.3, self.vol=500.69, self.amt=13260058.4541, ukdf['pct'].iloc[-1]=-0.000532 , ukdf['amount'].iloc[-1]=13260058.4541, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5391.57442306296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26477.74113004', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35669
self.closeSec=1694737499, self.tradeDate='20230915', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26476.5, self.close=26466.2, self.high=26482.8, self.low=26451.6, self.vol=968.147, self.amt=25622228.308 
2023-09-15 08:25:00,804:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230915   080000    080459  ...         0.0        0.0       0
5857  20230915   080500    080959  ...         0.0        0.0       0
5858  20230915   081000    081459  ...         0.0        0.0       0
5859  20230915   081500    081959  ...         0.0        0.0       0
5860  20230915   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 08:25:00,805:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694737499, self.tradeDate='20230915', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26476.5, self.close=26466.2, self.high=26482.8, self.low=26451.6, self.vol=968.147, self.amt=25622228.308, ukdf['pct'].iloc[-1]=-0.000393 , ukdf['amount'].iloc[-1]=25622228.308, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5550.9036', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26466.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [15/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35666 

self.closeSec=1694735999, self.tradeDate='20230915', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26515.9, self.close=26510.3, self.high=26519.4, self.low=26503.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35667 

self.closeSec=1694736299, self.tradeDate='20230915', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26510.3, self.close=26499.5, self.high=26512.6, self.low=26475.0 
127.0.0.1 - - [15/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35668 

self.closeSec=1694736599, self.tradeDate='20230915', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26499.6, self.close=26509.9, self.high=26510.0, self.low=26498.2 
127.0.0.1 - - [15/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35669 

self.closeSec=1694736899, self.tradeDate='20230915', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26509.9, self.close=26490.7, self.high=26510.6, self.low=26482.7 
127.0.0.1 - - [15/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35670 

self.closeSec=1694737199, self.tradeDate='20230915', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26490.7, self.close=26476.6, self.high=26499.4, self.low=26472.3 
127.0.0.1 - - [15/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35671 

self.closeSec=1694737499, self.tradeDate='20230915', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26476.5, self.close=26466.2, self.high=26482.8, self.low=26451.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-15 08:00:17,316:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230915    052959  26554.3  ...  49.583333  0.557369  0.332282
5770  20230915    055959  26581.1  ...  49.166667  0.546272  0.342614
5771  20230915    062959  26524.8  ...  49.166667  0.558366  0.345252
5772  20230915    065959  26601.1  ...  48.750000  0.555784  0.348911
5773  20230915    072959  26587.9  ...  48.750000  0.552224  0.353961

[5 rows x 33 columns]
0.5537037037037037
acc is : 0.5537037037037037
2023-09-15 08:00:17,375:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.496284  0.503716       0  ...  0.943400   1.0    0.0  1.025018
536     1  0.471650  0.528350       1  ...  0.946128   1.0    0.0  1.027982
537     0  0.503099  0.496901       0  ...  0.945662   1.0    0.0  1.027476
538     1  0.486618  0.513382       0  ...  0.945026   1.0    0.0  1.026785
539     1  0.488074  0.511926       0  ...  0.942902   1.0    0.0  1.024477

[5 rows x 10 columns]
2023-09-15 08:00:17,387:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496255  0.503745       0  ...  0.943400   1.0    0.0  1.025760
46     1  0.471954  0.528046       1  ...  0.946128   1.0    0.0  1.028929
47     0  0.503486  0.496514       0  ...  0.945662   1.0    0.0  1.029238
48     1  0.487019  0.512981       0  ...  0.945026   1.0    0.0  1.028868
49     1  0.488074  0.511926       0  ...  0.942902   1.0    0.0  1.024477

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '-2248.4364069681', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26508.30610806', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [15/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17831 

self.closeSec=1694734199, self.tradeDate='20230915', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26592.3', self.close='26570'
127.0.0.1 - - [15/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17832 

self.closeSec=1694734799, self.tradeDate='20230915', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26570.1', self.close='26525.8'
127.0.0.1 - - [15/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17833 

self.closeSec=1694735399, self.tradeDate='20230915', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26525.8', self.close='26507.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17834 

self.closeSec=1694735999, self.tradeDate='20230915', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26507.8', self.close='26510.3'
127.0.0.1 - - [15/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17835 

self.closeSec=1694736599, self.tradeDate='20230915', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26510.3', self.close='26510'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17836 

self.closeSec=1694737199, self.tradeDate='20230915', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26509.9', self.close='26476.6'
127.0.0.1 - - [15/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [15/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17834 

self.closeSec=1694734199, self.tradeDate='20230915', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26592.3', self.close='26570'
127.0.0.1 - - [15/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17835 

self.closeSec=1694734799, self.tradeDate='20230915', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26570.1', self.close='26525.8'
127.0.0.1 - - [15/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17836 

self.closeSec=1694735399, self.tradeDate='20230915', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26525.8', self.close='26507.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17837 

self.closeSec=1694735999, self.tradeDate='20230915', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26507.8', self.close='26510.3'
127.0.0.1 - - [15/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17838 

self.closeSec=1694736599, self.tradeDate='20230915', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26510.3', self.close='26510'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17839 

self.closeSec=1694737199, self.tradeDate='20230915', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26509.9', self.close='26476.6'
127.0.0.1 - - [15/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [15/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17834 

self.closeSec=1694734199, self.tradeDate='20230915', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26592.3', self.close='26570'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17835 127.0.0.1 - - [15/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -


self.closeSec=1694734799, self.tradeDate='20230915', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26570.1', self.close='26525.8'
127.0.0.1 - - [15/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17836 

self.closeSec=1694735399, self.tradeDate='20230915', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26525.8', self.close='26507.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17837 

self.closeSec=1694735999, self.tradeDate='20230915', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26507.8', self.close='26510.3'
127.0.0.1 - - [15/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17838 

self.closeSec=1694736599, self.tradeDate='20230915', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26510.3', self.close='26510'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17839 

self.closeSec=1694737199, self.tradeDate='20230915', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26509.9', self.close='26476.6'
127.0.0.1 - - [15/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35668
self.closeSec=1694737199, self.tradeDate='20230915', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26490.7, self.close=26476.6, self.high=26499.4, self.low=26472.3, self.vol=500.69, self.amt=13260058.4541 
127.0.0.1 - - [15/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-15 08:20:06,731:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230915   075500    075959  ...         0.0        0.0       0
5856  20230915   080000    080459  ...         0.0        0.0       0
5857  20230915   080500    080959  ...         0.0        0.0       0
5858  20230915   081000    081459  ...         0.0        0.0       0
5859  20230915   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 08:20:06,735:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694737199, self.tradeDate='20230915', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26490.7, self.close=26476.6, self.high=26499.4, self.low=26472.3, self.vol=500.69, self.amt=13260058.4541, ukdf['pct'].iloc[-1]=-0.000532 , ukdf['amount'].iloc[-1]=13260058.4541, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-13603.22068918436', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26477.74113004', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [15/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35669
self.closeSec=1694737499, self.tradeDate='20230915', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26476.5, self.close=26466.2, self.high=26482.8, self.low=26451.6, self.vol=968.147, self.amt=25622228.308 
2023-09-15 08:25:00,817:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230915   080000    080459  ...         0.0        0.0       0
5857  20230915   080500    080959  ...         0.0        0.0       0
5858  20230915   081000    081459  ...         0.0        0.0       0
5859  20230915   081500    081959  ...         0.0        0.0       0
5860  20230915   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 08:25:00,817:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694737499, self.tradeDate='20230915', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26476.5, self.close=26466.2, self.high=26482.8, self.low=26451.6, self.vol=968.147, self.amt=25622228.308, ukdf['pct'].iloc[-1]=-0.000393 , ukdf['amount'].iloc[-1]=25622228.308, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14028.1557', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26466.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230914   200000    235959  1694707199  ...    719  0.552260  0.623661     1.0
720  20230915   000000    035959  1694721599  ...    720  0.602464  0.822162     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-697.048518222', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26665.42562088', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1431863.74296, self.flagDict['side']='buy', self.tradeCount=23, self.count=743
self.closeSec=1694735999, self.tradeDate='20230915', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26662.0, self.close=26510.3, self.high=26713.2, self.low=26461.0, self.vol=30652.131, self.amt=814216049.3155 
127.0.0.1 - - [15/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-15 08:00:01,564:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694735999, self.tradeDate='20230915', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26662.0, self.close=26510.3, self.high=26713.2, self.low=26461.0, self.vol=30652.131, self.amt=814216049.3155 
2023-09-15 08:00:01,578:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230914   120000    155959  ...   31772.605  8.340425e+08  0.002986
718  20230914   160000    195959  ...   35924.143  9.462548e+08  0.003771
719  20230914   200000    235959  ...  143119.371  3.803643e+09  0.009402
720  20230915   000000    035959  ...   62676.122  1.670001e+09 -0.000675
721  20230915   040000    075959  ...   30652.131  8.142160e+08 -0.005690

[5 rows x 11 columns]
2023-09-15 08:00:02,350:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230914   120000    155959  1694678399  ...    717  0.454654  0.251118     NaN
718  20230914   160000    195959  1694692799  ...    718  0.473310  0.335618     NaN
719  20230914   200000    235959  1694707199  ...    719  0.552260  0.623661     1.0
720  20230915   000000    035959  1694721599  ...    720  0.602464  0.822162     1.0
721  20230915   040000    075959  1694735999  ...    721  0.598445  0.837164     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-9031.1725', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26510.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


