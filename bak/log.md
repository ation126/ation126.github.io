# 20230920 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37108
self.closeSec=1695169199, self.tradeDate='20230920', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27231.3, self.close=27212.3, self.high=27237.7, self.low=27210.5, self.vol=661.405, self.amt=18004916.6371 
127.0.0.1 - - [20/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-20 08:20:06,502:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230920   075500    075959  ...         0.0        0.0       0
5856  20230920   080000    080459  ...         0.0        0.0       0
5857  20230920   080500    080959  ...         0.0        0.0       0
5858  20230920   081000    081459  ...         0.0        0.0       0
5859  20230920   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 08:20:06,507:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695169199, self.tradeDate='20230920', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27231.3, self.close=27212.3, self.high=27237.7, self.low=27210.5, self.vol=661.405, self.amt=18004916.6371, ukdf['pct'].iloc[-1]=-0.000698 , ukdf['amount'].iloc[-1]=18004916.6371, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4837.8924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27212.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37109
self.closeSec=1695169499, self.tradeDate='20230920', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27212.3, self.close=27174.1, self.high=27214.5, self.low=27165.6, self.vol=842.713, self.amt=22907238.5481 
2023-09-20 08:25:00,825:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230920   080000    080459  ...         0.0        0.0       0
5857  20230920   080500    080959  ...         0.0        0.0       0
5858  20230920   081000    081459  ...         0.0        0.0       0
5859  20230920   081500    081959  ...         0.0        0.0       0
5860  20230920   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 08:25:00,826:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695169499, self.tradeDate='20230920', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27212.3, self.close=27174.1, self.high=27214.5, self.low=27165.6, self.vol=842.713, self.amt=22907238.5481, ukdf['pct'].iloc[-1]=-0.001404 , ukdf['amount'].iloc[-1]=22907238.5481, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4304.5266', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27174', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [20/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37106 

self.closeSec=1695167999, self.tradeDate='20230920', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27202.8, self.close=27195.9, self.high=27205.8, self.low=27186.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37107 

self.closeSec=1695168299, self.tradeDate='20230920', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27195.9, self.close=27181.3, self.high=27197.9, self.low=27181.0 
127.0.0.1 - - [20/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37108 

self.closeSec=1695168599, self.tradeDate='20230920', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27181.3, self.close=27191.8, self.high=27191.9, self.low=27170.0 
127.0.0.1 - - [20/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37109 

self.closeSec=1695168899, self.tradeDate='20230920', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27191.9, self.close=27231.3, self.high=27247.5, self.low=27191.8 
127.0.0.1 - - [20/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37110 

self.closeSec=1695169199, self.tradeDate='20230920', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27231.3, self.close=27212.3, self.high=27237.7, self.low=27210.5 
127.0.0.1 - - [20/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37111 

self.closeSec=1695169499, self.tradeDate='20230920', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27212.3, self.close=27174.1, self.high=27214.5, self.low=27165.6 
127.0.0.1 - - [20/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-20 08:00:17,767:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230920    052959  27171.5  ...  52.083333  0.516920  0.424773
5770  20230920    055959  27012.0  ...  52.500000  0.539265  0.423976
5771  20230920    062959  27145.8  ...  52.083333  0.534047  0.427579
5772  20230920    065959  27118.0  ...  52.500000  0.543055  0.426704
5773  20230920    072959  27173.1  ...  52.916667  0.547174  0.423591

[5 rows x 33 columns]
0.5425925925925926
acc is : 0.5425925925925926
2023-09-20 08:00:17,824:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.438582  0.561418       1  ...  0.921461  -1.0    0.0  1.051548
536     0  0.517590  0.482410       0  ...  0.922401  -1.0    0.0  1.050475
537     1  0.476668  0.523332       1  ...  0.920520  -1.0    0.0  1.052617
538     0  0.500194  0.499806       1  ...  0.919656  -1.0    0.0  1.053604
539     0  0.500519  0.499481       0  ...  0.919754  -1.0    0.0  1.053492

[5 rows x 10 columns]
2023-09-20 08:00:17,834:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.438913  0.561087       1  ...  0.911301  -1.0    0.0  1.050945
46     0  0.517367  0.482633       0  ...  0.922401  -1.0    0.0  1.050202
47     1  0.476557  0.523443       1  ...  0.910370  -1.0    0.0  1.053984
48     1  0.499589  0.500411       1  ...  0.919656  -1.0    0.0  1.054205
49     0  0.500519  0.499481       0  ...  0.919754  -1.0    0.0  1.053492

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '-1599.241', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27193.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18551 

self.closeSec=1695166199, self.tradeDate='20230920', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27202.6', self.close='27198.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18552 

self.closeSec=1695166799, self.tradeDate='20230920', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27198.9', self.close='27194.9'
127.0.0.1 - - [20/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18553 

self.closeSec=1695167399, self.tradeDate='20230920', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27196', self.close='27204.1'
127.0.0.1 - - [20/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18554 

self.closeSec=1695167999, self.tradeDate='20230920', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27204.1', self.close='27195.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18555 

self.closeSec=1695168599, self.tradeDate='20230920', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27195.9', self.close='27191.8'
127.0.0.1 - - [20/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18556 

self.closeSec=1695169199, self.tradeDate='20230920', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27191.9', self.close='27212.4'
127.0.0.1 - - [20/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18554 

self.closeSec=1695166199, self.tradeDate='20230920', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27202.6', self.close='27198.8'
127.0.0.1 - - [20/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18555 

127.0.0.1 - - [20/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
self.closeSec=1695166799, self.tradeDate='20230920', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27198.9', self.close='27194.9'
127.0.0.1 - - [20/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18556 

self.closeSec=1695167399, self.tradeDate='20230920', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27196', self.close='27204.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18557 

self.closeSec=1695167999, self.tradeDate='20230920', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27204.1', self.close='27195.9'
127.0.0.1 - - [20/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18558 

self.closeSec=1695168599, self.tradeDate='20230920', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27195.9', self.close='27191.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18559 

self.closeSec=1695169199, self.tradeDate='20230920', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27191.9', self.close='27212.4'
127.0.0.1 - - [20/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18554 

self.closeSec=1695166199, self.tradeDate='20230920', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27202.6', self.close='27198.8'
127.0.0.1 - - [20/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18555 

self.closeSec=1695166799, self.tradeDate='20230920', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27198.9', self.close='27194.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18556 

self.closeSec=1695167399, self.tradeDate='20230920', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27196', self.close='27204.1'
127.0.0.1 - - [20/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18557 

self.closeSec=1695167999, self.tradeDate='20230920', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27204.1', self.close='27195.9'
127.0.0.1 - - [20/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18558 

self.closeSec=1695168599, self.tradeDate='20230920', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27195.9', self.close='27191.8'
127.0.0.1 - - [20/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18559 

self.closeSec=1695169199, self.tradeDate='20230920', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27191.9', self.close='27212.4'
127.0.0.1 - - [20/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37108
self.closeSec=1695169199, self.tradeDate='20230920', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27231.3, self.close=27212.3, self.high=27237.7, self.low=27210.5, self.vol=661.405, self.amt=18004916.6371 
127.0.0.1 - - [20/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-20 08:20:06,493:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230920   075500    075959  ...         0.0        0.0       0
5856  20230920   080000    080459  ...         0.0        0.0       0
5857  20230920   080500    080959  ...         0.0        0.0       0
5858  20230920   081000    081459  ...         0.0        0.0       0
5859  20230920   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 08:20:06,502:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695169199, self.tradeDate='20230920', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27231.3, self.close=27212.3, self.high=27237.7, self.low=27210.5, self.vol=661.405, self.amt=18004916.6371, ukdf['pct'].iloc[-1]=-0.000698 , ukdf['amount'].iloc[-1]=18004916.6371, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '13679.0303', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27212.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [20/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37109
self.closeSec=1695169499, self.tradeDate='20230920', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27212.3, self.close=27174.1, self.high=27214.5, self.low=27165.6, self.vol=842.713, self.amt=22907238.5481 
2023-09-20 08:25:00,832:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230920   080000    080459  ...         0.0        0.0       0
5857  20230920   080500    080959  ...         0.0        0.0       0
5858  20230920   081000    081459  ...         0.0        0.0       0
5859  20230920   081500    081959  ...         0.0        0.0       0
5860  20230920   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 08:25:00,833:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695169499, self.tradeDate='20230920', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27212.3, self.close=27174.1, self.high=27214.5, self.low=27165.6, self.vol=842.713, self.amt=22907238.5481, ukdf['pct'].iloc[-1]=-0.001404 , ukdf['amount'].iloc[-1]=22907238.5481, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '12256.53', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27174', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230919   200000    235959  1695139199  ...    719  1.189022  3.968225     1.0
720  20230920   000000    035959  1695153599  ...    720  1.395255  4.296544     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-3930.9138', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27174', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=773127.0.0.1 - - [20/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1695167999, self.tradeDate='20230920', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27172.1, self.close=27195.9, self.high=27213.0, self.low=26970.0, self.vol=32685.998, self.amt=886521881.14398 
2023-09-20 08:00:01,567:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695167999, self.tradeDate='20230920', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27172.1, self.close=27195.9, self.high=27213.0, self.low=26970.0, self.vol=32685.998, self.amt=886521881.14398 
2023-09-20 08:00:01,582:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230919   120000    155959  ...   18919.447  5.073238e+08  0.001156
718  20230919   160000    195959  ...  126162.588  3.427120e+09  0.014399
719  20230919   200000    235959  ...  148476.423  4.037187e+09  0.007005
720  20230920   000000    035959  ...   78548.985  2.138192e+09 -0.008912
721  20230920   040000    075959  ...   32685.998  8.865219e+08  0.000994

[5 rows x 11 columns]
2023-09-20 08:00:02,300:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230919   120000    155959  1695110399  ...    717  0.641258  1.818063     1.0
718  20230919   160000    195959  1695124799  ...    718  0.899522  3.024665     1.0
719  20230919   200000    235959  1695139199  ...    719  1.189022  3.968225     1.0
720  20230920   000000    035959  1695153599  ...    720  1.395255  4.296544     1.0
721  20230920   040000    075959  1695167999  ...    721  1.258084  3.471109     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-2818.6785', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27195.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


