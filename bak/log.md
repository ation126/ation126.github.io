# 20230831 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31348
self.closeSec=1693441199, self.tradeDate='20230831', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27253.3, self.close=27249.1, self.high=27255.9, self.low=27245.1, self.vol=251.463, self.amt=6852413.5266 
127.0.0.1 - - [31/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-31 08:20:05,086:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230831   075500    075959  ...         0.0        0.0       0
5844  20230831   080000    080459  ...         0.0        0.0       0
5845  20230831   080500    080959  ...         0.0        0.0       0
5846  20230831   081000    081459  ...         0.0        0.0       0
5847  20230831   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 08:20:05,089:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693441199, self.tradeDate='20230831', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27253.3, self.close=27249.1, self.high=27255.9, self.low=27245.1, self.vol=251.463, self.amt=6852413.5266, ukdf['pct'].iloc[-1]=-0.000158 , ukdf['amount'].iloc[-1]=6852413.5266, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5372.6508', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27250.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [31/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31349
self.closeSec=1693441499, self.tradeDate='20230831', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27249.1, self.close=27236.0, self.high=27251.9, self.low=27235.9, self.vol=257.424, self.amt=7012563.1968 
2023-08-31 08:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230831   080000    080459  ...         0.0        0.0       0
5845  20230831   080500    080959  ...         0.0        0.0       0
5846  20230831   081000    081459  ...         0.0        0.0       0
5847  20230831   081500    081959  ...         0.0        0.0       0
5848  20230831   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 08:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693441499, self.tradeDate='20230831', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27249.1, self.close=27236.0, self.high=27251.9, self.low=27235.9, self.vol=257.424, self.amt=7012563.1968, ukdf['pct'].iloc[-1]=-0.000481 , ukdf['amount'].iloc[-1]=7012563.1968, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5170.76310390684', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27236.20282234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31346 

self.closeSec=1693439999, self.tradeDate='20230831', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27286.4, self.close=27290.5, self.high=27290.5, self.low=27272.7 
127.0.0.1 - - [31/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31347 

self.closeSec=1693440299, self.tradeDate='20230831', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27290.4, self.close=27271.6, self.high=27290.5, self.low=27270.1 
127.0.0.1 - - [31/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31348 

self.closeSec=1693440599, self.tradeDate='20230831', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27271.7, self.close=27259.6, self.high=27274.0, self.low=27255.9 
127.0.0.1 - - [31/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31349 

self.closeSec=1693440899, self.tradeDate='20230831', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27259.6, self.close=27253.4, self.high=27263.0, self.low=27251.1 
127.0.0.1 - - [31/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31350 

self.closeSec=1693441199, self.tradeDate='20230831', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27253.3, self.close=27249.1, self.high=27255.9, self.low=27245.1 
127.0.0.1 - - [31/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31351 

self.closeSec=1693441499, self.tradeDate='20230831', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27249.1, self.close=27236.0, self.high=27251.9, self.low=27235.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-31 08:00:19,701:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230831    052959  27234.0  ...  51.250000  0.541742  0.629575
5770  20230831    055959  27257.2  ...  50.833333  0.539591  0.621595
5771  20230831    062959  27245.4  ...  50.833333  0.539441  0.610680
5772  20230831    065959  27244.7  ...  50.416667  0.535713  0.602909
5773  20230831    072959  27225.1  ...  50.833333  0.546795  0.587280

[5 rows x 33 columns]
0.5425925925925926
acc is : 0.5425925925925926
2023-08-31 08:00:19,768:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.488057  0.511943       0  ...  0.980824   1.0    0.0  1.045026
536     1  0.480143  0.519857       0  ...  0.980795   1.0    0.0  1.044995
537     1  0.477413  0.522587       0  ...  0.980086   1.0    0.0  1.044240
538     1  0.462993  0.537007       1  ...  0.982545   1.0    0.0  1.046859
539     1  0.495410  0.504590       0  ...  0.982444   1.0    0.0  1.046752

[5 rows x 10 columns]
2023-08-31 08:00:19,780:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487789  0.512211       0  ...  0.966469   1.0    0.0  1.039865
46     1  0.479960  0.520040       0  ...  0.964994   1.0    0.0  1.042229
47     1  0.477264  0.522736       0  ...  0.964296   1.0    0.0  1.037534
48     1  0.462569  0.537431       1  ...  0.982545   1.0    0.0  1.046932
49     1  0.495410  0.504590       0  ...  0.982444   1.0    0.0  1.046752

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.311', 'enterprice': '27227', 'countrevence': '0', 'unrealprofit': '1601.77623734212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27287.87857692', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [31/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15671 

self.closeSec=1693438199, self.tradeDate='20230831', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27256.2', self.close='27293.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15672 

self.closeSec=1693438799, self.tradeDate='20230831', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27293.4', self.close='27281.3'
127.0.0.1 - - [31/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15673 

self.closeSec=1693439399, self.tradeDate='20230831', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27281.2', self.close='27302.2'
127.0.0.1 - - [31/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15674 

self.closeSec=1693439999, self.tradeDate='20230831', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27302.3', self.close='27290.4'
127.0.0.1 - - [31/Aug/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15675 

self.closeSec=1693440599, self.tradeDate='20230831', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27290.4', self.close='27259.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15676 

self.closeSec=1693441199, self.tradeDate='20230831', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27259.6', self.close='27249.1'
127.0.0.1 - - [31/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15674 

self.closeSec=1693438199, self.tradeDate='20230831', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27256.2', self.close='27293.4'
127.0.0.1 - - [31/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [31/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15675 

self.closeSec=1693438799, self.tradeDate='20230831', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27293.4', self.close='27281.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15676 

self.closeSec=1693439399, self.tradeDate='20230831', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27281.2', self.close='27302.2'
127.0.0.1 - - [31/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15677 

self.closeSec=1693439999, self.tradeDate='20230831', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27302.3', self.close='27290.4'
127.0.0.1 - - [31/Aug/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15678 

self.closeSec=1693440599, self.tradeDate='20230831', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27290.4', self.close='27259.6'
127.0.0.1 - - [31/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15679 

self.closeSec=1693441199, self.tradeDate='20230831', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27259.6', self.close='27249.1'
127.0.0.1 - - [31/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [31/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15674 

self.closeSec=1693438199, self.tradeDate='20230831', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27256.2', self.close='27293.4'
127.0.0.1 - - [31/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15675 

self.closeSec=1693438799, self.tradeDate='20230831', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27293.4', self.close='27281.3'
127.0.0.1 - - [31/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15676 

self.closeSec=1693439399, self.tradeDate='20230831', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27281.2', self.close='27302.2'
127.0.0.1 - - [31/Aug/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15677 

self.closeSec=1693439999, self.tradeDate='20230831', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27302.3', self.close='27290.4'
127.0.0.1 - - [31/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15678 

self.closeSec=1693440599, self.tradeDate='20230831', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27290.4', self.close='27259.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15679 

self.closeSec=1693441199, self.tradeDate='20230831', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27259.6', self.close='27249.1'
127.0.0.1 - - [31/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31348
self.closeSec=1693441199, self.tradeDate='20230831', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27253.3, self.close=27249.1, self.high=27255.9, self.low=27245.1, self.vol=251.463, self.amt=6852413.5266 
127.0.0.1 - - [31/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-31 08:20:05,088:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230831   075500    075959  ...         0.0        0.0       0
5844  20230831   080000    080459  ...         0.0        0.0       0
5845  20230831   080500    080959  ...         0.0        0.0       0
5846  20230831   081000    081459  ...         0.0        0.0       0
5847  20230831   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 08:20:05,090:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693441199, self.tradeDate='20230831', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27253.3, self.close=27249.1, self.high=27255.9, self.low=27245.1, self.vol=251.463, self.amt=6852413.5266, ukdf['pct'].iloc[-1]=-0.000158 , ukdf['amount'].iloc[-1]=6852413.5266, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '15105.2447', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27250.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [31/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31349
self.closeSec=1693441499, self.tradeDate='20230831', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27249.1, self.close=27236.0, self.high=27251.9, self.low=27235.9, self.vol=257.424, self.amt=7012563.1968 
2023-08-31 08:25:00,815:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230831   080000    080459  ...         0.0        0.0       0
5845  20230831   080500    080959  ...         0.0        0.0       0
5846  20230831   081000    081459  ...         0.0        0.0       0
5847  20230831   081500    081959  ...         0.0        0.0       0
5848  20230831   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 08:25:00,816:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693441499, self.tradeDate='20230831', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27249.1, self.close=27236.0, self.high=27251.9, self.low=27235.9, self.vol=257.424, self.amt=7012563.1968, ukdf['pct'].iloc[-1]=-0.000481 , ukdf['amount'].iloc[-1]=7012563.1968, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '14566.80502452994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27236.20282234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230830   200000    235959  1693411199  ...    719  1.008007  2.675917     1.0
720  20230831   000000    035959  1693425599  ...    720  0.982513  2.467692     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-37899.37319653368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27171.82534066', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=653
self.closeSec=1693439999, self.tradeDate='20230831', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27167.4, self.close=27290.5, self.high=27335.6, self.low=27165.5, self.vol=21666.717, self.amt=590701076.0617 
127.0.0.1 - - [31/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-31 08:00:01,579:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693439999, self.tradeDate='20230831', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27167.4, self.close=27290.5, self.high=27335.6, self.low=27165.5, self.vol=21666.717, self.amt=590701076.0617 
2023-08-31 08:00:01,597:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230830   120000    155959  ...   23307.828  6.391418e+08  0.001753
718  20230830   160000    195959  ...   35589.834  9.748422e+08 -0.003781
719  20230830   200000    235959  ...  125823.008  3.427674e+09 -0.004813
720  20230831   000000    035959  ...   42830.020  1.163731e+09 -0.000908
721  20230831   040000    075959  ...   21666.717  5.907011e+08  0.004535

[5 rows x 11 columns]
2023-08-31 08:00:02,333:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230830   120000    155959  1693382399  ...    717  1.016004  3.002526     1.0
718  20230830   160000    195959  1693396799  ...    718  0.980226  2.713822     1.0
719  20230830   200000    235959  1693411199  ...    719  1.008007  2.675917     1.0
720  20230831   000000    035959  1693425599  ...    720  0.982513  2.467692     1.0
721  20230831   040000    075959  1693439999  ...    721  0.943311  2.238721     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-31110.7368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27290.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


