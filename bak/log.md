# 20230921 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37396
self.closeSec=1695255599, self.tradeDate='20230921', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27100.1, self.close=27085.2, self.high=27100.1, self.low=27072.6, self.vol=521.278, self.amt=14117336.7479 
127.0.0.1 - - [21/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-21 08:20:06,359:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230921   075500    075959  ...         0.0        0.0       0
5856  20230921   080000    080459  ...         0.0        0.0       0
5857  20230921   080500    080959  ...         0.0        0.0       0
5858  20230921   081000    081459  ...         0.0        0.0       0
5859  20230921   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 08:20:06,367:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695255599, self.tradeDate='20230921', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27100.1, self.close=27085.2, self.high=27100.1, self.low=27072.6, self.vol=521.278, self.amt=14117336.7479, ukdf['pct'].iloc[-1]=-0.000546 , ukdf['amount'].iloc[-1]=14117336.7479, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3067.8978', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27085.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37397
self.closeSec=1695255899, self.tradeDate='20230921', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27085.2, self.close=27086.9, self.high=27101.4, self.low=27081.6, self.vol=379.848, self.amt=10290734.907 
127.0.0.1 - - [21/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-21 08:25:00,809:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230921   080000    080459  ...         0.0        0.0       0
5857  20230921   080500    080959  ...         0.0        0.0       0
5858  20230921   081000    081459  ...         0.0        0.0       0
5859  20230921   081500    081959  ...         0.0        0.0       0
5860  20230921   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 08:25:00,810:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695255899, self.tradeDate='20230921', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27085.2, self.close=27086.9, self.high=27101.4, self.low=27081.6, self.vol=379.848, self.amt=10290734.907, ukdf['pct'].iloc[-1]=6.3e-05 , ukdf['amount'].iloc[-1]=10290734.907, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3094.50885567186', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27087.11089011', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [21/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37394 

self.closeSec=1695254399, self.tradeDate='20230921', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27115.9, self.close=27107.7, self.high=27119.0, self.low=27106.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37395 

self.closeSec=1695254699, self.tradeDate='20230921', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27107.7, self.close=27090.7, self.high=27111.1, self.low=27075.3 
127.0.0.1 - - [21/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37396 

self.closeSec=1695254999, self.tradeDate='20230921', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27091.4, self.close=27095.4, self.high=27101.3, self.low=27071.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37397 

self.closeSec=1695255299, self.tradeDate='20230921', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27094.1, self.close=27100.0, self.high=27104.9, self.low=27090.5 
127.0.0.1 - - [21/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37398 

self.closeSec=1695255599, self.tradeDate='20230921', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27100.1, self.close=27085.2, self.high=27100.1, self.low=27072.6 
127.0.0.1 - - [21/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37399 

self.closeSec=1695255899, self.tradeDate='20230921', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27085.2, self.close=27086.9, self.high=27101.4, self.low=27081.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-21 08:00:16,953:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230921    052959  27085.8  ...  52.083333  0.526708  0.551168
5770  20230921    055959  27170.0  ...  51.666667  0.512483  0.543607
5771  20230921    062959  27100.4  ...  51.250000  0.506924  0.534277
5772  20230921    065959  27072.7  ...  51.250000  0.508221  0.524780
5773  20230921    072959  27079.3  ...  51.666667  0.519249  0.509177

[5 rows x 33 columns]
0.5351851851851852
acc is : 0.5351851851851852
2023-09-21 08:00:17,012:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.517339  0.482661       0  ...  0.883316  -1.0    0.0  1.047626
536     1  0.480505  0.519495       0  ...  0.884219  -1.0    0.0  1.046555
537     1  0.491483  0.508517       1  ...  0.884003  -1.0    0.0  1.046810
538     1  0.498902  0.501098       1  ...  0.882162  -1.0    0.0  1.048990
539     0  0.512517  0.487483       0  ...  0.883073  -1.0    0.0  1.047908

[5 rows x 10 columns]
2023-09-21 08:00:17,024:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.517200  0.482800       0  ...  0.883316  -1.0    0.0  1.047079
46     1  0.479997  0.520003       0  ...  0.884219  -1.0    0.0  1.045657
47     1  0.491624  0.508376       1  ...  0.884003  -1.0    0.0  1.046215
48     1  0.498874  0.501126       1  ...  0.882162  -1.0    0.0  1.049047
49     0  0.512517  0.487483       0  ...  0.883073  -1.0    0.0  1.047908

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '543.4434910821', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27110.22962637', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18695 

self.closeSec=1695252599, self.tradeDate='20230921', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27120', self.close='27135.7'
127.0.0.1 - - [21/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18696 

self.closeSec=1695253199, self.tradeDate='20230921', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27135.7', self.close='27124.8'
127.0.0.1 - - [21/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18697 

self.closeSec=1695253799, self.tradeDate='20230921', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27124.7', self.close='27139'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18698 

self.closeSec=1695254399, self.tradeDate='20230921', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27139', self.close='27107.7'
127.0.0.1 - - [21/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18699 

self.closeSec=1695254999, self.tradeDate='20230921', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27107.7', self.close='27094.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18700 

self.closeSec=1695255599, self.tradeDate='20230921', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27094.1', self.close='27085.2'
127.0.0.1 - - [21/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18698 

self.closeSec=1695252599, self.tradeDate='20230921', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27120', self.close='27135.7'
127.0.0.1 - - [21/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18699 

self.closeSec=1695253199, self.tradeDate='20230921', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27135.7', self.close='27124.8'
127.0.0.1 - - [21/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18700 

self.closeSec=1695253799, self.tradeDate='20230921', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27124.7', self.close='27139'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18701 

self.closeSec=1695254399, self.tradeDate='20230921', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27139', self.close='27107.7'
127.0.0.1 - - [21/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18702 

self.closeSec=1695254999, self.tradeDate='20230921', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27107.7', self.close='27094.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18703 

self.closeSec=1695255599, self.tradeDate='20230921', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27094.1', self.close='27085.2'
127.0.0.1 - - [21/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18698 

self.closeSec=1695252599, self.tradeDate='20230921', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27120', self.close='27135.7'
127.0.0.1 - - [21/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18699 

self.closeSec=1695253199, self.tradeDate='20230921', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27135.7', self.close='27124.8'
127.0.0.1 - - [21/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18700 

self.closeSec=1695253799, self.tradeDate='20230921', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27124.7', self.close='27139'
127.0.0.1 - - [21/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18701 

self.closeSec=1695254399, self.tradeDate='20230921', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27139', self.close='27107.7'
127.0.0.1 - - [21/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18702 

self.closeSec=1695254999, self.tradeDate='20230921', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27107.7', self.close='27094.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18703 

self.closeSec=1695255599, self.tradeDate='20230921', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27094.1', self.close='27085.2'
127.0.0.1 - - [21/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37396
self.closeSec=1695255599, self.tradeDate='20230921', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27100.1, self.close=27085.2, self.high=27100.1, self.low=27072.6, self.vol=521.278, self.amt=14117336.7479 
127.0.0.1 - - [21/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-21 08:20:06,361:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230921   075500    075959  ...         0.0        0.0       0
5856  20230921   080000    080459  ...         0.0        0.0       0
5857  20230921   080500    080959  ...         0.0        0.0       0
5858  20230921   081000    081459  ...         0.0        0.0       0
5859  20230921   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 08:20:06,368:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695255599, self.tradeDate='20230921', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27100.1, self.close=27085.2, self.high=27100.1, self.low=27072.6, self.vol=521.278, self.amt=14117336.7479, ukdf['pct'].iloc[-1]=-0.000546 , ukdf['amount'].iloc[-1]=14117336.7479, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8958.4092', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27085.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [21/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37397
self.closeSec=1695255899, self.tradeDate='20230921', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27085.2, self.close=27086.9, self.high=27101.4, self.low=27081.6, self.vol=379.848, self.amt=10290734.907 
2023-09-21 08:25:00,817:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230921   080000    080459  ...         0.0        0.0       0
5857  20230921   080500    080959  ...         0.0        0.0       0
5858  20230921   081000    081459  ...         0.0        0.0       0
5859  20230921   081500    081959  ...         0.0        0.0       0
5860  20230921   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-21 08:25:00,817:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695255899, self.tradeDate='20230921', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27085.2, self.close=27086.9, self.high=27101.4, self.low=27081.6, self.vol=379.848, self.amt=10290734.907, ukdf['pct'].iloc[-1]=6.3e-05 , ukdf['amount'].iloc[-1]=10290734.907, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '9029.38156957551', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27087.11089011', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230920   200000    235959  1695225599  ...    719  1.263330  2.615045     1.0
720  20230921   000000    035959  1695239999  ...    720  1.206814  2.349063     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-16873.21354989699', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26919.16510623', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [21/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=779
self.closeSec=1695254399, self.tradeDate='20230921', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26916.5, self.close=27107.7, self.high=27235.0, self.low=26901.5, self.vol=45455.539, self.amt=1231101628.86808 
2023-09-21 08:00:01,559:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695254399, self.tradeDate='20230921', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26916.5, self.close=27107.7, self.high=27235.0, self.low=26901.5, self.vol=45455.539, self.amt=1231101628.86808 
2023-09-21 08:00:01,573:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230920   120000    155959  ...   42439.459  1.147899e+09 -0.000623
718  20230920   160000    195959  ...   49754.746  1.346007e+09 -0.000148
719  20230920   200000    235959  ...   57520.038  1.559204e+09  0.002991
720  20230921   000000    035959  ...  107623.432  2.913957e+09 -0.009272
721  20230921   040000    075959  ...   45455.539  1.231102e+09  0.007175

[5 rows x 11 columns]
2023-09-21 08:00:02,298:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230920   120000    155959  1695196799  ...    717  1.389618  3.322454     1.0
718  20230920   160000    195959  1695211199  ...    718  1.333400  2.958932     1.0
719  20230920   200000    235959  1695225599  ...    719  1.263330  2.615045     1.0
720  20230921   000000    035959  1695239999  ...    720  1.206814  2.349063     1.0
721  20230921   040000    075959  1695254399  ...    721  1.168680  2.155180     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-7165.08772310232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27110.31886264', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


