# 20230926 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38836
self.closeSec=1695687599, self.tradeDate='20230926', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26270.6, self.close=26267.4, self.high=26275.8, self.low=26263.5, self.vol=279.164, self.amt=7333255.6441 
127.0.0.1 - - [26/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-26 08:20:07,007:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230926   075500    075959  ...         0.0        0.0       0
5856  20230926   080000    080459  ...         0.0        0.0       0
5857  20230926   080500    080959  ...         0.0        0.0       0
5858  20230926   081000    081459  ...         0.0        0.0       0
5859  20230926   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 08:20:07,018:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695687599, self.tradeDate='20230926', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26270.6, self.close=26267.4, self.high=26275.8, self.low=26263.5, self.vol=279.164, self.amt=7333255.6441, ukdf['pct'].iloc[-1]=-0.000122 , ukdf['amount'].iloc[-1]=7333255.6441, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8320.785', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26267.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38837
self.closeSec=1695687899, self.tradeDate='20230926', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26267.4, self.close=26265.9, self.high=26269.9, self.low=26256.4, self.vol=226.926, self.amt=5959602.8083 
2023-09-26 08:25:00,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230926   080000    080459  ...         0.0        0.0       0
5857  20230926   080500    080959  ...         0.0        0.0       0
5858  20230926   081000    081459  ...         0.0        0.0       0
5859  20230926   081500    081959  ...         0.0        0.0       0
5860  20230926   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 08:25:00,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695687899, self.tradeDate='20230926', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26267.4, self.close=26265.9, self.high=26269.9, self.low=26256.4, self.vol=226.926, self.amt=5959602.8083, ukdf['pct'].iloc[-1]=-5.7e-05 , ukdf['amount'].iloc[-1]=5959602.8083, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8327.53349879682', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26266.91540293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [26/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38834 

self.closeSec=1695686399, self.tradeDate='20230926', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26292.0, self.close=26290.4, self.high=26297.8, self.low=26290.4 
127.0.0.1 - - [26/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38835 

self.closeSec=1695686699, self.tradeDate='20230926', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26290.5, self.close=26285.0, self.high=26294.8, self.low=26278.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38836 

self.closeSec=1695686999, self.tradeDate='20230926', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26285.1, self.close=26292.6, self.high=26293.0, self.low=26278.7 
127.0.0.1 - - [26/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38837 

self.closeSec=1695687299, self.tradeDate='20230926', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26292.7, self.close=26270.6, self.high=26292.7, self.low=26270.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38838 

self.closeSec=1695687599, self.tradeDate='20230926', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26270.6, self.close=26267.4, self.high=26275.8, self.low=26263.5 
127.0.0.1 - - [26/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38839 

self.closeSec=1695687899, self.tradeDate='20230926', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26267.4, self.close=26265.9, self.high=26269.9, self.low=26256.4 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-26 08:00:16,210:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230926    052959  26275.2  ...  45.833333  0.483681  0.516903
5770  20230926    055959  26290.4  ...  45.833333  0.477319  0.507252
5771  20230926    062959  26267.7  ...  46.250000  0.477878  0.497985
5772  20230926    065959  26269.5  ...  45.833333  0.477213  0.489667
5773  20230926    072959  26267.2  ...  45.833333  0.481435  0.480003

[5 rows x 33 columns]
0.5425925925925926
acc is : 0.5425925925925926
2023-09-26 08:00:16,273:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.495425  0.504575       0  ...  0.977522  -1.0    0.0  0.986339
536     1  0.484181  0.515819       1  ...  0.977455  -1.0    0.0  0.986407
537     1  0.489274  0.510726       0  ...  0.977541  -1.0    0.0  0.986321
538     1  0.487402  0.512598       1  ...  0.977049  -1.0    0.0  0.986816
539     1  0.494380  0.505620       1  ...  0.976677  -1.0    0.0  0.987192

[5 rows x 10 columns]
2023-09-26 08:00:16,284:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495091  0.504909       0  ...  0.977522  -1.0    0.0  0.984546
46     1  0.483944  0.516056       1  ...  0.977455  -1.0    0.0  0.986355
47     1  0.489318  0.510682       0  ...  0.977541  -1.0    0.0  0.987207
48     1  0.487664  0.512336       1  ...  0.977049  -1.0    0.0  0.989205
49     1  0.494380  0.505620       1  ...  0.976677  -1.0    0.0  0.987192

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '21475.522', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26294.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19415 

self.closeSec=1695684599, self.tradeDate='20230926', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26290', self.close='26280.4'
127.0.0.1 - - [26/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19416 

self.closeSec=1695685199, self.tradeDate='20230926', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26280.4', self.close='26271.5'
127.0.0.1 - - [26/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19417 

self.closeSec=1695685799, self.tradeDate='20230926', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26271.5', self.close='26286.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19418 

self.closeSec=1695686399, self.tradeDate='20230926', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26286.2', self.close='26290.4'
127.0.0.1 - - [26/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19419 

self.closeSec=1695686999, self.tradeDate='20230926', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26290.5', self.close='26292.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19420 

self.closeSec=1695687599, self.tradeDate='20230926', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26292.7', self.close='26267.4'
127.0.0.1 - - [26/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19418 

self.closeSec=1695684599, self.tradeDate='20230926', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26290', self.close='26280.4'
127.0.0.1 - - [26/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19419 

self.closeSec=1695685199, self.tradeDate='20230926', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26280.4', self.close='26271.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19420 

self.closeSec=1695685799, self.tradeDate='20230926', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26271.5', self.close='26286.1'
127.0.0.1 - - [26/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19421 

self.closeSec=1695686399, self.tradeDate='20230926', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26286.2', self.close='26290.4'
127.0.0.1 - - [26/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19422 

self.closeSec=1695686999, self.tradeDate='20230926', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26290.5', self.close='26292.6'
127.0.0.1 - - [26/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19423 

self.closeSec=1695687599, self.tradeDate='20230926', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26292.7', self.close='26267.4'
127.0.0.1 - - [26/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19418 

self.closeSec=1695684599, self.tradeDate='20230926', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26290', self.close='26280.4'
127.0.0.1 - - [26/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19419 

self.closeSec=1695685199, self.tradeDate='20230926', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26280.4', self.close='26271.5'
127.0.0.1 - - [26/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19420 

self.closeSec=1695685799, self.tradeDate='20230926', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26271.5', self.close='26286.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19421 

self.closeSec=1695686399, self.tradeDate='20230926', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26286.2', self.close='26290.4'
127.0.0.1 - - [26/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19422 

self.closeSec=1695686999, self.tradeDate='20230926', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26290.5', self.close='26292.6'
127.0.0.1 - - [26/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19423 

self.closeSec=1695687599, self.tradeDate='20230926', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26292.7', self.close='26267.4'
127.0.0.1 - - [26/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38836
self.closeSec=1695687599, self.tradeDate='20230926', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26270.6, self.close=26267.4, self.high=26275.8, self.low=26263.5, self.vol=279.164, self.amt=7333255.6441 
127.0.0.1 - - [26/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-26 08:20:07,028:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230926   075500    075959  ...         0.0        0.0       0
5856  20230926   080000    080459  ...         0.0        0.0       0
5857  20230926   080500    080959  ...         0.0        0.0       0
5858  20230926   081000    081459  ...         0.0        0.0       0
5859  20230926   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 08:20:07,048:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695687599, self.tradeDate='20230926', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26270.6, self.close=26267.4, self.high=26275.8, self.low=26263.5, self.vol=279.164, self.amt=7333255.6441, ukdf['pct'].iloc[-1]=-0.000122 , ukdf['amount'].iloc[-1]=7333255.6441, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-21415.5006', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26267.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38837
self.closeSec=1695687899, self.tradeDate='20230926', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26267.4, self.close=26265.9, self.high=26269.9, self.low=26256.4, self.vol=226.926, self.amt=5959602.8083 
2023-09-26 08:25:00,808:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230926   080000    080459  ...         0.0        0.0       0
5857  20230926   080500    080959  ...         0.0        0.0       0
5858  20230926   081000    081459  ...         0.0        0.0       0
5859  20230926   081500    081959  ...         0.0        0.0       0
5860  20230926   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-26 08:25:00,808:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695687899, self.tradeDate='20230926', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26267.4, self.close=26265.9, self.high=26269.9, self.low=26256.4, self.vol=226.926, self.amt=5959602.8083, ukdf['pct'].iloc[-1]=-5.7e-05 , ukdf['amount'].iloc[-1]=5959602.8083, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-21433.49901977687', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26266.91540293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230925   200000    235959  1695657599  ...    719  0.217799 -0.959629    -1.0
720  20230926   000000    035959  1695671999  ...    720  0.257942 -0.870637    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-8714.8052', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26320.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=809
self.closeSec=1695686399, self.tradeDate='20230926', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26318.6, self.close=26290.4, self.high=26440.0, self.low=26247.6, self.vol=23377.527, self.amt=615358401.8706 
127.0.0.1 - - [26/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-26 08:00:01,591:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695686399, self.tradeDate='20230926', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26318.6, self.close=26290.4, self.high=26440.0, self.low=26247.6, self.vol=23377.527, self.amt=615358401.8706 
2023-09-26 08:00:01,607:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230925   120000    155959  ...  29109.864  7.602567e+08  0.001078
718  20230925   160000    195959  ...  33858.819  8.832737e+08 -0.004290
719  20230925   200000    235959  ...  58168.921  1.520600e+09  0.006338
720  20230926   000000    035959  ...  53444.241  1.406415e+09  0.003225
721  20230926   040000    075959  ...  23377.527  6.153584e+08 -0.000908

[5 rows x 11 columns]
2023-09-26 08:00:02,364:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230925   120000    155959  1695628799  ...    717  0.251184 -0.866226    -1.0
718  20230925   160000    195959  1695643199  ...    718  0.218555 -0.951504    -1.0
719  20230925   200000    235959  1695657599  ...    719  0.217799 -0.959629    -1.0
720  20230926   000000    035959  1695671999  ...    720  0.257942 -0.870637    -1.0
721  20230926   040000    075959  1695686399  ...    721  0.255654 -0.872703    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-7187.0496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26290.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


