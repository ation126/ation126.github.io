# 20230930 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39988
self.closeSec=1696033199, self.tradeDate='20230930', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26905.5, self.close=26904.6, self.high=26915.7, self.low=26902.8, self.vol=420.471, self.amt=11314680.4607 
127.0.0.1 - - [30/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-30 08:20:06,549:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230930   075500    075959  ...         0.0        0.0       0
5856  20230930   080000    080459  ...         0.0        0.0       0
5857  20230930   080500    080959  ...         0.0        0.0       0
5858  20230930   081000    081459  ...         0.0        0.0       0
5859  20230930   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 08:20:06,555:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696033199, self.tradeDate='20230930', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26905.5, self.close=26904.6, self.high=26915.7, self.low=26902.8, self.vol=420.471, self.amt=11314680.4607, ukdf['pct'].iloc[-1]=-3.3e-05 , ukdf['amount'].iloc[-1]=11314680.4607, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-594.6402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26907.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39989
self.closeSec=1696033499, self.tradeDate='20230930', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26904.6, self.close=26891.2, self.high=26907.6, self.low=26891.1, self.vol=170.587, self.amt=4588714.4417 
2023-09-30 08:25:00,774:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230930   080000    080459  ...         0.0        0.0       0
5857  20230930   080500    080959  ...         0.0        0.0       0
5858  20230930   081000    081459  ...         0.0        0.0       0
5859  20230930   081500    081959  ...         0.0        0.0       0
5860  20230930   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 08:25:00,774:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696033499, self.tradeDate='20230930', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26904.6, self.close=26891.2, self.high=26907.6, self.low=26891.1, self.vol=170.587, self.amt=4588714.4417, ukdf['pct'].iloc[-1]=-0.000498 , ukdf['amount'].iloc[-1]=4588714.4417, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-385.52821148292', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26892.58405942', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39986 

self.closeSec=1696031999, self.tradeDate='20230930', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26892.5, self.close=26890.9, self.high=26897.6, self.low=26890.9 
127.0.0.1 - - [30/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39987 

self.closeSec=1696032299, self.tradeDate='20230930', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26890.9, self.close=26879.9, self.high=26894.4, self.low=26879.8 
127.0.0.1 - - [30/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39988 

self.closeSec=1696032599, self.tradeDate='20230930', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26879.8, self.close=26885.7, self.high=26887.6, self.low=26875.1 
127.0.0.1 - - [30/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39989 

self.closeSec=1696032899, self.tradeDate='20230930', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26885.7, self.close=26905.5, self.high=26905.5, self.low=26885.7 
127.0.0.1 - - [30/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39990 

self.closeSec=1696033199, self.tradeDate='20230930', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26905.5, self.close=26904.6, self.high=26915.7, self.low=26902.8 
127.0.0.1 - - [30/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39991 

self.closeSec=1696033499, self.tradeDate='20230930', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26904.6, self.close=26891.2, self.high=26907.6, self.low=26891.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-30 08:00:17,547:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230930    052959  26898.0  ...  50.416667  0.527344  0.550664
5770  20230930    055959  26909.6  ...  50.000000  0.515865  0.554931
5771  20230930    062959  26858.7  ...  50.416667  0.518966  0.557287
5772  20230930    065959  26873.4  ...  50.833333  0.519284  0.559321
5773  20230930    072959  26875.1  ...  51.250000  0.520342  0.560681

[5 rows x 33 columns]
0.5370370370370371
acc is : 0.5370370370370371
2023-09-30 08:00:17,614:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.496971  0.503029       0  ...  0.961120  -1.0    0.0  1.004146
536     1  0.475966  0.524034       1  ...  0.960591  -1.0    0.0  1.004699
537     1  0.495900  0.504100       1  ...  0.960537  -1.0    0.0  1.004756
538     1  0.494346  0.505654       1  ...  0.960362  -1.0    0.0  1.004939
539     1  0.494746  0.505254       1  ...  0.959969  -1.0    0.0  1.005350

[5 rows x 10 columns]
2023-09-30 08:00:17,625:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497044  0.502956       0  ...  0.966440  -1.0    0.0  0.985322
46     1  0.475545  0.524455       1  ...  0.965907  -1.0    0.0  0.988116
47     1  0.495612  0.504388       1  ...  0.965853  -1.0    0.0  0.986963
48     1  0.494164  0.505836       1  ...  0.965677  -1.0    0.0  0.999383
49     1  0.494746  0.505254       1  ...  0.959969  -1.0    0.0  1.005350

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.689', 'enterprice': '27080', 'countrevence': '0', 'unrealprofit': '4770.4473', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26894.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [30/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19991 

self.closeSec=1696030199, self.tradeDate='20230930', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26894.6', self.close='26879.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19992 

self.closeSec=1696030799, self.tradeDate='20230930', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26880', self.close='26898.7'
127.0.0.1 - - [30/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [30/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19993 

self.closeSec=1696031399, self.tradeDate='20230930', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26898.7', self.close='26906'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19994 

self.closeSec=1696031999, self.tradeDate='20230930', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26905.9', self.close='26890.9'
127.0.0.1 - - [30/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19995 

self.closeSec=1696032599, self.tradeDate='20230930', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26890.9', self.close='26885.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19996 

self.closeSec=1696033199, self.tradeDate='20230930', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26885.7', self.close='26904.6'
127.0.0.1 - - [30/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19994 

self.closeSec=1696030199, self.tradeDate='20230930', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26894.6', self.close='26879.9'
127.0.0.1 - - [30/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19995 

self.closeSec=1696030799, self.tradeDate='20230930', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26880', self.close='26898.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19996 

self.closeSec=1696031399, self.tradeDate='20230930', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26898.7', self.close='26906'
127.0.0.1 - - [30/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19997 

self.closeSec=1696031999, self.tradeDate='20230930', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26905.9', self.close='26890.9'
127.0.0.1 - - [30/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19998 

self.closeSec=1696032599, self.tradeDate='20230930', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26890.9', self.close='26885.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19999 

self.closeSec=1696033199, self.tradeDate='20230930', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26885.7', self.close='26904.6'
127.0.0.1 - - [30/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19994 

self.closeSec=1696030199, self.tradeDate='20230930', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26894.6', self.close='26879.9'
127.0.0.1 - - [30/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19995 

self.closeSec=1696030799, self.tradeDate='20230930', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26880', self.close='26898.7'
127.0.0.1 - - [30/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19996 

self.closeSec=1696031399, self.tradeDate='20230930', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26898.7', self.close='26906'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19997 

self.closeSec=1696031999, self.tradeDate='20230930', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26905.9', self.close='26890.9'
127.0.0.1 - - [30/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19998 

self.closeSec=1696032599, self.tradeDate='20230930', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26890.9', self.close='26885.7'
127.0.0.1 - - [30/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19999 

self.closeSec=1696033199, self.tradeDate='20230930', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26885.7', self.close='26904.6'
127.0.0.1 - - [30/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39988
self.closeSec=1696033199, self.tradeDate='20230930', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26905.5, self.close=26904.6, self.high=26915.7, self.low=26902.8, self.vol=420.471, self.amt=11314680.4607 
127.0.0.1 - - [30/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-30 08:20:06,554:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230930   075500    075959  ...         0.0        0.0       0
5856  20230930   080000    080459  ...         0.0        0.0       0
5857  20230930   080500    080959  ...         0.0        0.0       0
5858  20230930   081000    081459  ...         0.0        0.0       0
5859  20230930   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 08:20:06,557:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696033199, self.tradeDate='20230930', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26905.5, self.close=26904.6, self.high=26915.7, self.low=26902.8, self.vol=420.471, self.amt=11314680.4607, ukdf['pct'].iloc[-1]=-3.3e-05 , ukdf['amount'].iloc[-1]=11314680.4607, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '2362.1676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26907.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [30/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39989
self.closeSec=1696033499, self.tradeDate='20230930', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26904.6, self.close=26891.2, self.high=26907.6, self.low=26891.1, self.vol=170.587, self.amt=4588714.4417 
2023-09-30 08:25:00,774:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230930   080000    080459  ...         0.0        0.0       0
5857  20230930   080500    080959  ...         0.0        0.0       0
5858  20230930   081000    081459  ...         0.0        0.0       0
5859  20230930   081500    081959  ...         0.0        0.0       0
5860  20230930   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-30 08:25:00,774:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696033499, self.tradeDate='20230930', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26904.6, self.close=26891.2, self.high=26907.6, self.low=26891.1, self.vol=170.587, self.amt=4588714.4417, ukdf['pct'].iloc[-1]=-0.000498 , ukdf['amount'].iloc[-1]=4588714.4417, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '1804.46055091822', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26892.58405942', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230929   200000    235959  1696003199  ...    719  0.913452  0.669172     1.0
720  20230930   000000    035959  1696017599  ...    720  0.900775  0.629290     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-11457.9143', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26913.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1272444.8790024, self.flagDict['side']='buy', self.tradeCount=27, self.count=833
self.closeSec=1696031999, self.tradeDate='20230930', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26912.6, self.close=26890.9, self.high=26979.0, self.low=26850.1, self.vol=14104.96, self.amt=379305744.9164 
127.0.0.1 - - [30/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-30 08:00:01,554:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696031999, self.tradeDate='20230930', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26912.6, self.close=26890.9, self.high=26979.0, self.low=26850.1, self.vol=14104.96, self.amt=379305744.9164 
2023-09-30 08:00:01,566:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230929   120000    155959  ...   39116.334  1.058424e+09  0.008332
718  20230929   160000    195959  ...   35285.051  9.539245e+08 -0.007744
719  20230929   200000    235959  ...  112689.694  3.029300e+09 -0.003112
720  20230930   000000    035959  ...   33352.761  8.954973e+08  0.001455
721  20230930   040000    075959  ...   14104.960  3.793057e+08 -0.000855

[5 rows x 11 columns]
2023-09-30 08:00:02,240:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230929   120000    155959  1695974399  ...    717  0.948493  0.777177     1.0
718  20230929   160000    195959  1695988799  ...    718  0.888722  0.620769     1.0
719  20230929   200000    235959  1696003199  ...    719  0.913452  0.669172     1.0
720  20230930   000000    035959  1696017599  ...    720  0.900775  0.629290     1.0
721  20230930   040000    075959  1696031999  ...    721  0.827709  0.447244     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.901', 'enterprice': '27157.6', 'countrevence': '0', 'unrealprofit': '-12396.23460381993', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26893.29359707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


