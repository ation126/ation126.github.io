# 20230914 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35380
self.closeSec=1694650799, self.tradeDate='20230914', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26207.5, self.close=26193.9, self.high=26210.5, self.low=26191.8, self.vol=338.825, self.amt=8878262.9551 
127.0.0.1 - - [14/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-14 08:20:06,627:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230914   075500    075959  ...         0.0        0.0       0
5856  20230914   080000    080459  ...         0.0        0.0       0
5857  20230914   080500    080959  ...         0.0        0.0       0
5858  20230914   081000    081459  ...         0.0        0.0       0
5859  20230914   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 08:20:06,629:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694650799, self.tradeDate='20230914', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26207.5, self.close=26193.9, self.high=26210.5, self.low=26191.8, self.vol=338.825, self.amt=8878262.9551, ukdf['pct'].iloc[-1]=-0.000462 , ukdf['amount'].iloc[-1]=8878262.9551, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9344.346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26193.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35381
self.closeSec=1694651099, self.tradeDate='20230914', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26194.0, self.close=26180.5, self.high=26194.0, self.low=26176.5, self.vol=290.459, self.amt=7605967.5678 
127.0.0.1 - - [14/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-14 08:25:00,764:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230914   080000    080459  ...         0.0        0.0       0
5857  20230914   080500    080959  ...         0.0        0.0       0
5858  20230914   081000    081459  ...         0.0        0.0       0
5859  20230914   081500    081959  ...         0.0        0.0       0
5860  20230914   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 08:25:00,765:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694651099, self.tradeDate='20230914', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26194.0, self.close=26180.5, self.high=26194.0, self.low=26176.5, self.vol=290.459, self.amt=7605967.5678, ukdf['pct'].iloc[-1]=-0.000512 , ukdf['amount'].iloc[-1]=7605967.5678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9530.9544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26180.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [14/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35378 

self.closeSec=1694649599, self.tradeDate='20230914', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26208.9, self.close=26210.0, self.high=26210.0, self.low=26208.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35379 

self.closeSec=1694649899, self.tradeDate='20230914', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26209.9, self.close=26188.6, self.high=26217.0, self.low=26186.5 
127.0.0.1 - - [14/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35380 

self.closeSec=1694650199, self.tradeDate='20230914', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26188.7, self.close=26180.1, self.high=26204.4, self.low=26176.9 
127.0.0.1 - - [14/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35381 

self.closeSec=1694650499, self.tradeDate='20230914', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26180.1, self.close=26206.0, self.high=26206.0, self.low=26180.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35382 

self.closeSec=1694650799, self.tradeDate='20230914', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26207.5, self.close=26193.9, self.high=26210.5, self.low=26191.8 
127.0.0.1 - - [14/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35383 

self.closeSec=1694651099, self.tradeDate='20230914', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26194.0, self.close=26180.5, self.high=26194.0, self.low=26176.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-14 08:00:17,119:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230914    052959  26204.0  ...  51.250000  0.551967  0.407312
5770  20230914    055959  26233.2  ...  50.833333  0.547950  0.401644
5771  20230914    062959  26214.1  ...  50.833333  0.557548  0.389940
5772  20230914    065959  26269.6  ...  50.416667  0.548554  0.383870
5773  20230914    072959  26227.6  ...  50.000000  0.542453  0.381522

[5 rows x 33 columns]
0.55
acc is : 0.55
2023-09-14 08:00:17,175:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.498750  0.501250       0  ...  0.992498  -1.0    0.0  1.015905
536     1  0.483824  0.516176       1  ...  0.990397  -1.0    0.0  1.018056
537     0  0.504135  0.495865       0  ...  0.991980  -1.0    0.0  1.016428
538     1  0.476468  0.523532       0  ...  0.993065  -1.0    0.0  1.015316
539     1  0.479491  0.520509       1  ...  0.992645  -1.0    0.0  1.015746

[5 rows x 10 columns]
2023-09-14 08:00:17,187:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498827  0.501173       0  ...  0.992498  -1.0    0.0  1.012910
46     1  0.483647  0.516353       1  ...  0.990397  -1.0    0.0  1.015658
47     0  0.504161  0.495839       0  ...  0.991980  -1.0    0.0  1.014556
48     1  0.476409  0.523591       0  ...  0.993065  -1.0    0.0  1.013360
49     1  0.479491  0.520509       1  ...  0.992645  -1.0    0.0  1.015746

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.172', 'enterprice': '26023.2', 'countrevence': '0', 'unrealprofit': '-5318.8736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26212', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17687 

self.closeSec=1694647799, self.tradeDate='20230914', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26219.8', self.close='26198.9'
127.0.0.1 - - [14/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17688 

self.closeSec=1694648399, self.tradeDate='20230914', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26198.9', self.close='26195'
127.0.0.1 - - [14/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17689 

self.closeSec=1694648999, self.tradeDate='20230914', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26195', self.close='26206.4'
127.0.0.1 - - [14/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17690 

self.closeSec=1694649599, self.tradeDate='20230914', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26206.5', self.close='26209.9'
127.0.0.1 - - [14/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17691 

self.closeSec=1694650199, self.tradeDate='20230914', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26209.9', self.close='26180.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17692 

self.closeSec=1694650799, self.tradeDate='20230914', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26180.1', self.close='26193.9'
127.0.0.1 - - [14/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17690 

self.closeSec=1694647799, self.tradeDate='20230914', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26219.8', self.close='26198.9'
127.0.0.1 - - [14/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [14/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17691 

self.closeSec=1694648399, self.tradeDate='20230914', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26198.9', self.close='26195'

--handleKline--: 127.0.0.1 - - [14/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17692 

self.closeSec=1694648999, self.tradeDate='20230914', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26195', self.close='26206.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17693 

self.closeSec=1694649599, self.tradeDate='20230914', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26206.5', self.close='26209.9'
127.0.0.1 - - [14/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17694 

self.closeSec=1694650199, self.tradeDate='20230914', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26209.9', self.close='26180.1'
127.0.0.1 - - [14/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17695 

self.closeSec=1694650799, self.tradeDate='20230914', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26180.1', self.close='26193.9'
127.0.0.1 - - [14/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17690 

self.closeSec=1694647799, self.tradeDate='20230914', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26219.8', self.close='26198.9'
127.0.0.1 - - [14/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17691 

self.closeSec=1694648399, self.tradeDate='20230914', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26198.9', self.close='26195'
127.0.0.1 - - [14/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17692 

self.closeSec=1694648999, self.tradeDate='20230914', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26195', self.close='26206.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17693 

self.closeSec=1694649599, self.tradeDate='20230914', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26206.5', self.close='26209.9'
127.0.0.1 - - [14/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17694 

self.closeSec=1694650199, self.tradeDate='20230914', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26209.9', self.close='26180.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17695 

self.closeSec=1694650799, self.tradeDate='20230914', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26180.1', self.close='26193.9'
127.0.0.1 - - [14/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35380
self.closeSec=1694650799, self.tradeDate='20230914', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26207.5, self.close=26193.9, self.high=26210.5, self.low=26191.8, self.vol=338.825, self.amt=8878262.9551 
127.0.0.1 - - [14/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-14 08:20:06,625:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230914   075500    075959  ...         0.0        0.0       0
5856  20230914   080000    080459  ...         0.0        0.0       0
5857  20230914   080500    080959  ...         0.0        0.0       0
5858  20230914   081000    081459  ...         0.0        0.0       0
5859  20230914   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 08:20:06,629:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694650799, self.tradeDate='20230914', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26207.5, self.close=26193.9, self.high=26210.5, self.low=26191.8, self.vol=338.825, self.amt=8878262.9551, ukdf['pct'].iloc[-1]=-0.000462 , ukdf['amount'].iloc[-1]=8878262.9551, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-24145.3641', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26193.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35381
self.closeSec=1694651099, self.tradeDate='20230914', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26194.0, self.close=26180.5, self.high=26194.0, self.low=26176.5, self.vol=290.459, self.amt=7605967.5678 
127.0.0.1 - - [14/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-14 08:25:00,770:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230914   080000    080459  ...         0.0        0.0       0
5857  20230914   080500    080959  ...         0.0        0.0       0
5858  20230914   081000    081459  ...         0.0        0.0       0
5859  20230914   081500    081959  ...         0.0        0.0       0
5860  20230914   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-14 08:25:00,771:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694651099, self.tradeDate='20230914', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26194.0, self.close=26180.5, self.high=26194.0, self.low=26176.5, self.vol=290.459, self.amt=7605967.5678, ukdf['pct'].iloc[-1]=-0.000512 , ukdf['amount'].iloc[-1]=7605967.5678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-24643.0535', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26180.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230913   200000    235959  1694620799  ...    719  0.293882 -0.326290     NaN
720  20230914   000000    035959  1694635199  ...    720  0.337860 -0.178121     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-13584.46299494013', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26129.88614469', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=737
self.closeSec=1694649599, self.tradeDate='20230914', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26129.4, self.close=26210.0, self.high=26294.0, self.low=26129.4, self.vol=19635.224, self.amt=514822339.72774 
127.0.0.1 - - [14/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-14 08:00:01,527:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694649599, self.tradeDate='20230914', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26129.4, self.close=26210.0, self.high=26294.0, self.low=26129.4, self.vol=19635.224, self.amt=514822339.72774 
2023-09-14 08:00:01,548:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230913   120000    155959  ...   46656.095  1.210204e+09 -0.000054
718  20230913   160000    195959  ...   64365.198  1.679536e+09  0.012267
719  20230913   200000    235959  ...  100568.464  2.633161e+09  0.001711
720  20230914   000000    035959  ...   70495.521  1.847116e+09 -0.003797
721  20230914   040000    075959  ...   19635.224  5.148223e+08  0.003081

[5 rows x 11 columns]
2023-09-14 08:00:02,279:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230913   120000    155959  1694591999  ...    717  0.210407 -0.542773     NaN
718  20230913   160000    195959  1694606399  ...    718  0.240837 -0.466636     NaN
719  20230913   200000    235959  1694620799  ...    719  0.293882 -0.326290     NaN
720  20230914   000000    035959  1694635199  ...    720  0.337860 -0.178121     NaN
721  20230914   040000    075959  1694649599  ...    721  0.356106 -0.103098     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-18173.17240702272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26210.14060736', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


