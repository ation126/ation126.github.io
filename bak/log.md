# 20230901 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31636
self.closeSec=1693527599, self.tradeDate='20230901', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25982.3, self.close=25998.9, self.high=26016.6, self.low=25973.8, self.vol=1535.858, self.amt=39931267.0366 
127.0.0.1 - - [01/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-01 08:20:05,479:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230901   075500    075959  ...         0.0        0.0       0
5844  20230901   080000    080459  ...         0.0        0.0       0
5845  20230901   080500    080959  ...         0.0        0.0       0
5846  20230901   081000    081459  ...         0.0        0.0       0
5847  20230901   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 08:20:05,483:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693527599, self.tradeDate='20230901', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25982.3, self.close=25998.9, self.high=26016.6, self.low=25973.8, self.vol=1535.858, self.amt=39931267.0366, ukdf['pct'].iloc[-1]=0.000978 , ukdf['amount'].iloc[-1]=39931267.0366, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11947.04642257236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26007.00495314', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31637
self.closeSec=1693527899, self.tradeDate='20230901', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25998.8, self.close=25997.8, self.high=26014.3, self.low=25992.2, self.vol=659.926, self.amt=17160890.9792 
127.0.0.1 - - [01/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-01 08:25:00,775:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230901   080000    080459  ...         0.0        0.0       0
5845  20230901   080500    080959  ...         0.0        0.0       0
5846  20230901   081000    081459  ...         0.0        0.0       0
5847  20230901   081500    081959  ...         0.0        0.0       0
5848  20230901   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 08:25:00,775:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693527899, self.tradeDate='20230901', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25998.8, self.close=25997.8, self.high=26014.3, self.low=25992.2, self.vol=659.926, self.amt=17160890.9792, ukdf['pct'].iloc[-1]=-4.2e-05 , ukdf['amount'].iloc[-1]=17160890.9792, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12054.03535058382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25999.32227843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [01/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31634 

self.closeSec=1693526399, self.tradeDate='20230901', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25921.5, self.close=25928.0, self.high=25931.5, self.low=25908.7 
127.0.0.1 - - [01/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31635 

self.closeSec=1693526699, self.tradeDate='20230901', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25928.0, self.close=25956.6, self.high=25956.6, self.low=25918.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31636 

self.closeSec=1693526999, self.tradeDate='20230901', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25956.5, self.close=25965.6, self.high=25965.6, self.low=25951.3 
127.0.0.1 - - [01/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31637 

self.closeSec=1693527299, self.tradeDate='20230901', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25965.6, self.close=25973.5, self.high=25987.8, self.low=25964.6 
127.0.0.1 - - [01/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31638 

self.closeSec=1693527599, self.tradeDate='20230901', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25982.3, self.close=25998.9, self.high=26016.6, self.low=25973.8 
127.0.0.1 - - [01/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31639 

self.closeSec=1693527899, self.tradeDate='20230901', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25998.8, self.close=25997.8, self.high=26014.3, self.low=25992.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-01 08:00:19,878:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230901    052959  26007.4  ...  46.250000  0.324899  0.752458
5770  20230901    055959  25914.8  ...  46.666667  0.346829  0.756165
5771  20230901    062959  26013.0  ...  46.666667  0.343669  0.760504
5772  20230901    065959  25985.4  ...  47.083333  0.356343  0.762693
5773  20230901    072959  26042.8  ...  47.083333  0.344208  0.768065

[5 rows x 33 columns]
0.5314814814814814
acc is : 0.5314814814814814
2023-09-01 08:00:19,979:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.430804  0.569196       1  ...  0.999700  -1.0    0.0  0.996216
536     0  0.504458  0.495542       0  ...  1.000741  -1.0    0.0  0.995178
537     1  0.470128  0.529872       1  ...  0.998531  -1.0    0.0  0.997377
538     1  0.499239  0.500761       0  ...  1.002468  -1.0    0.0  0.993443
539     1  0.456749  0.543251       0  ...  1.002932  -1.0    0.0  0.992984

[5 rows x 10 columns]
2023-09-01 08:00:20,000:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.430777  0.569223       1  ...  0.999700  -1.0    0.0  0.996838
46     0  0.504863  0.495137       0  ...  1.000741  -1.0    0.0  0.996529
47     1  0.470708  0.529292       1  ...  0.998531  -1.0    0.0  1.000269
48     1  0.499805  0.500195       0  ...  1.002468  -1.0    0.0  0.994880
49     1  0.456749  0.543251       0  ...  1.002932  -1.0    0.0  0.992984

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '19799.6757', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25928.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15815 

self.closeSec=1693524599, self.tradeDate='20230901', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25995.6', self.close='25940.1'
127.0.0.1 - - [01/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15816 

self.closeSec=1693525199, self.tradeDate='20230901', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25940.1', self.close='25966.1'
127.0.0.1 - - [01/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15817 

self.closeSec=1693525799, self.tradeDate='20230901', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25966', self.close='25943.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15818 

self.closeSec=1693526399, self.tradeDate='20230901', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25941.9', self.close='25928'
127.0.0.1 - - [01/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15819 

self.closeSec=1693526999, self.tradeDate='20230901', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25928', self.close='25965.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15820 

self.closeSec=1693527599, self.tradeDate='20230901', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25965.6', self.close='25998.9'
127.0.0.1 - - [01/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [01/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15818 

self.closeSec=1693524599, self.tradeDate='20230901', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25995.6', self.close='25940.1'
127.0.0.1 - - [01/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15819 

self.closeSec=1693525199, self.tradeDate='20230901', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25940.1', self.close='25966.1'
127.0.0.1 - - [01/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15820 

self.closeSec=1693525799, self.tradeDate='20230901', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25966', self.close='25943.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15821 

self.closeSec=1693526399, self.tradeDate='20230901', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25941.9', self.close='25928'
127.0.0.1 - - [01/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15822 

self.closeSec=1693526999, self.tradeDate='20230901', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25928', self.close='25965.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15823 

self.closeSec=1693527599, self.tradeDate='20230901', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25965.6', self.close='25998.9'
127.0.0.1 - - [01/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15818 

self.closeSec=1693524599, self.tradeDate='20230901', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25995.6', self.close='25940.1'
127.0.0.1 - - [01/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15819 

self.closeSec=1693525199, self.tradeDate='20230901', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25940.1', self.close='25966.1'
127.0.0.1 - - [01/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15820 

self.closeSec=1693525799, self.tradeDate='20230901', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25966', self.close='25943.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15821 

self.closeSec=1693526399, self.tradeDate='20230901', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25941.9', self.close='25928'
127.0.0.1 - - [01/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15822 

self.closeSec=1693526999, self.tradeDate='20230901', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25928', self.close='25965.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15823 

self.closeSec=1693527599, self.tradeDate='20230901', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25965.6', self.close='25998.9'
127.0.0.1 - - [01/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31636
self.closeSec=1693527599, self.tradeDate='20230901', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25982.3, self.close=25998.9, self.high=26016.6, self.low=25973.8, self.vol=1535.858, self.amt=39931267.0366 
127.0.0.1 - - [01/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-09-01 08:20:05,479:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230901   075500    075959  ...         0.0        0.0       0
5844  20230901   080000    080459  ...         0.0        0.0       0
5845  20230901   080500    080959  ...         0.0        0.0       0
5846  20230901   081000    081459  ...         0.0        0.0       0
5847  20230901   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 08:20:05,491:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693527599, self.tradeDate='20230901', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25982.3, self.close=25998.9, self.high=26016.6, self.low=25973.8, self.vol=1535.858, self.amt=39931267.0366, ukdf['pct'].iloc[-1]=0.000978 , ukdf['amount'].iloc[-1]=39931267.0366, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31086.83303542726', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26007.00495314', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31637
self.closeSec=1693527899, self.tradeDate='20230901', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25998.8, self.close=25997.8, self.high=26014.3, self.low=25992.2, self.vol=659.926, self.amt=17160890.9792 
2023-09-01 08:25:00,771:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230901   080000    080459  ...         0.0        0.0       0
5845  20230901   080500    080959  ...         0.0        0.0       0
5846  20230901   081000    081459  ...         0.0        0.0       0
5847  20230901   081500    081959  ...         0.0        0.0       0
5848  20230901   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-01 08:25:00,771:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693527899, self.tradeDate='20230901', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25998.8, self.close=25997.8, self.high=26014.3, self.low=25992.2, self.vol=659.926, self.amt=17160890.9792, ukdf['pct'].iloc[-1]=-4.2e-05 , ukdf['amount'].iloc[-1]=17160890.9792, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31372.17525683137', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25999.32227843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230831   200000    235959  1693497599  ...    719  0.839319  1.656219     1.0
720  20230901   000000    035959  1693511999  ...    720  0.707481  1.199751     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-96596.86661141868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26146.57742941', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [01/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=659
self.closeSec=1693526399, self.tradeDate='20230901', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26148.7, self.close=25928.0, self.high=26180.0, self.low=25617.8, self.vol=90168.579, self.amt=2339530535.42429 
2023-09-01 08:00:01,590:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693526399, self.tradeDate='20230901', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26148.7, self.close=25928.0, self.high=26180.0, self.low=25617.8, self.vol=90168.579, self.amt=2339530535.42429 
2023-09-01 08:00:01,610:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230831   120000    155959  ...   16560.471  4.511445e+08  0.001514
718  20230831   160000    195959  ...   53026.501  1.449832e+09  0.001567
719  20230831   200000    235959  ...  102882.780  2.784818e+09 -0.014169
720  20230901   000000    035959  ...  224162.459  5.910897e+09 -0.028114
721  20230901   040000    075959  ...   90168.579  2.339531e+09 -0.008440

[5 rows x 11 columns]
2023-09-01 08:00:02,559:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230831   120000    155959  1693468799  ...    717  0.848542  1.788930     1.0
718  20230831   160000    195959  1693483199  ...    718  0.856356  1.760820     1.0
719  20230831   200000    235959  1693497599  ...    719  0.839319  1.656219     1.0
720  20230901   000000    035959  1693511999  ...    720  0.707481  1.199751     1.0
721  20230901   040000    075959  1693526399  ...    721  0.671389  1.059724     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-109110.8616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25928', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


