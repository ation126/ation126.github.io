# 20230912 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34804
self.closeSec=1694477999, self.tradeDate='20230912', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25180.0, self.close=25153.6, self.high=25183.4, self.low=25145.0, self.vol=839.105, self.amt=21111222.7537 
127.0.0.1 - - [12/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-12 08:20:06,157:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230912   075500    075959  ...         0.0        0.0       0
5856  20230912   080000    080459  ...         0.0        0.0       0
5857  20230912   080500    080959  ...         0.0        0.0       0
5858  20230912   081000    081459  ...         0.0        0.0       0
5859  20230912   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 08:20:06,159:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694477999, self.tradeDate='20230912', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25180.0, self.close=25153.6, self.high=25183.4, self.low=25145.0, self.vol=839.105, self.amt=21111222.7537, ukdf['pct'].iloc[-1]=-0.000965 , ukdf['amount'].iloc[-1]=21111222.7537, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '23830.1712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25153.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34805
self.closeSec=1694478299, self.tradeDate='20230912', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25153.6, self.close=25134.1, self.high=25153.7, self.low=25134.1, self.vol=384.939, self.amt=9678070.0248 
127.0.0.1 - - [12/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-12 08:25:00,801:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230912   080000    080459  ...         0.0        0.0       0
5857  20230912   080500    080959  ...         0.0        0.0       0
5858  20230912   081000    081459  ...         0.0        0.0       0
5859  20230912   081500    081959  ...         0.0        0.0       0
5860  20230912   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 08:25:00,801:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694478299, self.tradeDate='20230912', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25153.6, self.close=25134.1, self.high=25153.7, self.low=25134.1, self.vol=384.939, self.amt=9678070.0248, ukdf['pct'].iloc[-1]=-0.000775 , ukdf['amount'].iloc[-1]=9678070.0248, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '24101.7282', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25134.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [12/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34802 

self.closeSec=1694476799, self.tradeDate='20230912', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25132.5, self.close=25150.4, self.high=25167.8, self.low=25132.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34803 

self.closeSec=1694477099, self.tradeDate='20230912', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25150.4, self.close=25148.5, self.high=25172.1, self.low=25146.1 
127.0.0.1 - - [12/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34804 

self.closeSec=1694477399, self.tradeDate='20230912', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25148.6, self.close=25166.4, self.high=25172.1, self.low=25140.8 
127.0.0.1 - - [12/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34805 

self.closeSec=1694477699, self.tradeDate='20230912', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25166.4, self.close=25177.9, self.high=25178.0, self.low=25161.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34806 

self.closeSec=1694477999, self.tradeDate='20230912', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25180.0, self.close=25153.6, self.high=25183.4, self.low=25145.0 
127.0.0.1 - - [12/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34807 

self.closeSec=1694478299, self.tradeDate='20230912', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25153.6, self.close=25134.1, self.high=25153.7, self.low=25134.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-12 08:00:19,646:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230912    052959  25086.3  ...  50.416667  0.390239  0.726694
5770  20230912    055959  25151.3  ...  50.416667  0.387772  0.728383
5771  20230912    062959  25137.8  ...  50.416667  0.395056  0.728292
5772  20230912    065959  25162.8  ...  50.416667  0.390671  0.729749
5773  20230912    072959  25139.7  ...  50.000000  0.384926  0.733141

[5 rows x 33 columns]
0.5481481481481482
acc is : 0.5481481481481482
2023-09-12 08:00:19,716:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.511217  0.488783       0  ...  1.036071  -1.0    0.0  0.955105
536     1  0.493205  0.506795       1  ...  1.035032  -1.0    0.0  0.956063
537     0  0.509967  0.490033       0  ...  1.035990  -1.0    0.0  0.955177
538     1  0.491915  0.508085       0  ...  1.037255  -1.0    0.0  0.954011
539     1  0.489048  0.510952       1  ...  1.035537  -1.0    0.0  0.955592

[5 rows x 10 columns]
2023-09-12 08:00:19,729:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510330  0.489670       0  ...  1.058693  -1.0    0.0  0.934310
46     1  0.492845  0.507155       1  ...  1.049935  -1.0    0.0  0.942170
47     0  0.509902  0.490098       0  ...  1.032052  -1.0    0.0  0.958777
48     1  0.489927  0.510073       0  ...  1.037255  -1.0    0.0  0.952119
49     1  0.489048  0.510952       1  ...  1.035537  -1.0    0.0  0.955592

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '17591.17382591706', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25150.03551099', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17399 

self.closeSec=1694474999, self.tradeDate='20230912', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25133', self.close='25108.9'
127.0.0.1 - - [12/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17400 

self.closeSec=1694475599, self.tradeDate='20230912', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25108.9', self.close='25144.4'
127.0.0.1 - - [12/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17401 

self.closeSec=1694476199, self.tradeDate='20230912', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25144.4', self.close='25118.6'
127.0.0.1 - - [12/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17402 

self.closeSec=1694476799, self.tradeDate='20230912', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25118.6', self.close='25150.4'
127.0.0.1 - - [12/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17403 

self.closeSec=1694477399, self.tradeDate='20230912', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25150.4', self.close='25166.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17404 

self.closeSec=1694477999, self.tradeDate='20230912', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25166.4', self.close='25153.6'
127.0.0.1 - - [12/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17402 

self.closeSec=1694474999, self.tradeDate='20230912', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25133', self.close='25108.9'
127.0.0.1 - - [12/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [12/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17403 

self.closeSec=1694475599, self.tradeDate='20230912', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25108.9', self.close='25144.4'
127.0.0.1 - - [12/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17404 

self.closeSec=1694476199, self.tradeDate='20230912', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25144.4', self.close='25118.6'
127.0.0.1 - - [12/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17405 

self.closeSec=1694476799, self.tradeDate='20230912', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25118.6', self.close='25150.4'
127.0.0.1 - - [12/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17406 

self.closeSec=1694477399, self.tradeDate='20230912', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25150.4', self.close='25166.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17407 

self.closeSec=1694477999, self.tradeDate='20230912', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25166.4', self.close='25153.6'
127.0.0.1 - - [12/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [12/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17402 

self.closeSec=1694474999, self.tradeDate='20230912', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25133', self.close='25108.9'
127.0.0.1 - - [12/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17403 

self.closeSec=1694475599, self.tradeDate='20230912', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25108.9', self.close='25144.4'
127.0.0.1 - - [12/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17404 

self.closeSec=1694476199, self.tradeDate='20230912', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25144.4', self.close='25118.6'
127.0.0.1 - - [12/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17405 

self.closeSec=1694476799, self.tradeDate='20230912', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25118.6', self.close='25150.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17406 

self.closeSec=1694477399, self.tradeDate='20230912', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25150.4', self.close='25166.4'
127.0.0.1 - - [12/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17407 

self.closeSec=1694477999, self.tradeDate='20230912', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25166.4', self.close='25153.6'
127.0.0.1 - - [12/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34804
self.closeSec=1694477999, self.tradeDate='20230912', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25180.0, self.close=25153.6, self.high=25183.4, self.low=25145.0, self.vol=839.105, self.amt=21111222.7537 
127.0.0.1 - - [12/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-12 08:20:06,158:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230912   075500    075959  ...         0.0        0.0       0
5856  20230912   080000    080459  ...         0.0        0.0       0
5857  20230912   080500    080959  ...         0.0        0.0       0
5858  20230912   081000    081459  ...         0.0        0.0       0
5859  20230912   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 08:20:06,162:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694477999, self.tradeDate='20230912', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25180.0, self.close=25153.6, self.high=25183.4, self.low=25145.0, self.vol=839.105, self.amt=21111222.7537, ukdf['pct'].iloc[-1]=-0.000965 , ukdf['amount'].iloc[-1]=21111222.7537, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-62779.4323', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25153.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [12/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34805
self.closeSec=1694478299, self.tradeDate='20230912', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25153.6, self.close=25134.1, self.high=25153.7, self.low=25134.1, self.vol=384.939, self.amt=9678070.0248 
2023-09-12 08:25:00,799:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230912   080000    080459  ...         0.0        0.0       0
5857  20230912   080500    080959  ...         0.0        0.0       0
5858  20230912   081000    081459  ...         0.0        0.0       0
5859  20230912   081500    081959  ...         0.0        0.0       0
5860  20230912   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 08:25:00,799:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694478299, self.tradeDate='20230912', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25153.6, self.close=25134.1, self.high=25153.7, self.low=25134.1, self.vol=384.939, self.amt=9678070.0248, ukdf['pct'].iloc[-1]=-0.000775 , ukdf['amount'].iloc[-1]=9678070.0248, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-63503.6818', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25134.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230911   200000    235959  1694447999  ...    719  0.086707 -0.854904    -1.0
720  20230912   000000    035959  1694462399  ...    720  0.210671 -0.503950     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '50682.0528264159', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25005.8937033', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=725
self.closeSec=1694476799, self.tradeDate='20230912', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25008.2, self.close=25150.4, self.high=25210.0, self.low=24888.0, self.vol=41241.175, self.amt=1034585163.28972 
127.0.0.1 - - [12/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-12 08:00:01,584:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694476799, self.tradeDate='20230912', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25008.2, self.close=25150.4, self.high=25210.0, self.low=24888.0, self.vol=41241.175, self.amt=1034585163.28972 
2023-09-12 08:00:01,602:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230911   120000    155959  ...   25284.435  6.526423e+08  0.002872
718  20230911   160000    195959  ...   60165.089  1.545312e+09 -0.008116
719  20230911   200000    235959  ...  202776.195  5.125212e+09 -0.019084
720  20230912   000000    035959  ...   65270.071  1.639586e+09 -0.003792
721  20230912   040000    075959  ...   41241.175  1.034585e+09  0.005682

[5 rows x 11 columns]
2023-09-12 08:00:02,508:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230911   120000    155959  1694419199  ...    717  0.297896 -0.276374     NaN
718  20230911   160000    195959  1694433599  ...    718  0.290906 -0.294575     NaN
719  20230911   200000    235959  1694447999  ...    719  0.086707 -0.854904    -1.0
720  20230912   000000    035959  1694462399  ...    720  0.210671 -0.503950     NaN
721  20230912   040000    075959  1694476799  ...    721  0.312324 -0.219917     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '42276.14276575365', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25152.90928755', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


