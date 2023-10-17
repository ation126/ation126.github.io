# 20231017 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44884
self.closeSec=1697501999, self.tradeDate='20231017', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28447.5, self.close=28431.4, self.high=28449.9, self.low=28426.6, self.vol=752.215, self.amt=21389075.9525 
127.0.0.1 - - [17/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-10-17 08:20:08,979:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231017   075500    075959  ...         0.0        0.0       0
5856  20231017   080000    080459  ...         0.0        0.0       0
5857  20231017   080500    080959  ...         0.0        0.0       0
5858  20231017   081000    081459  ...         0.0        0.0       0
5859  20231017   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 08:20:08,989:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697501999, self.tradeDate='20231017', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28447.5, self.close=28431.4, self.high=28449.9, self.low=28426.6, self.vol=752.215, self.amt=21389075.9525, ukdf['pct'].iloc[-1]=-0.000562 , ukdf['amount'].iloc[-1]=21389075.9525, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-21815.079', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28431.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44885
self.closeSec=1697502299, self.tradeDate='20231017', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28431.5, self.close=28443.9, self.high=28453.8, self.low=28431.4, self.vol=416.466, self.amt=11845593.7776 
127.0.0.1 - - [17/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-17 08:25:02,884:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231017   080000    080459  ...         0.0        0.0       0
5857  20231017   080500    080959  ...         0.0        0.0       0
5858  20231017   081000    081459  ...         0.0        0.0       0
5859  20231017   081500    081959  ...         0.0        0.0       0
5860  20231017   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 08:25:02,893:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697502299, self.tradeDate='20231017', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28431.5, self.close=28443.9, self.high=28453.8, self.low=28431.4, self.vol=416.466, self.amt=11845593.7776, ukdf['pct'].iloc[-1]=0.00044 , ukdf['amount'].iloc[-1]=11845593.7776, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-21990.5466', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [17/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44882 

self.closeSec=1697500799, self.tradeDate='20231017', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28484.4, self.close=28486.3, self.high=28492.6, self.low=28471.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44883 

self.closeSec=1697501099, self.tradeDate='20231017', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28486.3, self.close=28525.5, self.high=28526.3, self.low=28472.8 
127.0.0.1 - - [17/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44884 

self.closeSec=1697501399, self.tradeDate='20231017', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28524.9, self.close=28465.9, self.high=28534.4, self.low=28459.0 
127.0.0.1 - - [17/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [17/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44885 

self.closeSec=1697501699, self.tradeDate='20231017', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28465.9, self.close=28447.4, self.high=28487.0, self.low=28442.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44886 

self.closeSec=1697501999, self.tradeDate='20231017', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28447.5, self.close=28431.4, self.high=28449.9, self.low=28426.6 
127.0.0.1 - - [17/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44887 

self.closeSec=1697502299, self.tradeDate='20231017', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28431.5, self.close=28443.9, self.high=28453.8, self.low=28431.4 
127.0.0.1 - - [17/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-17 08:00:17,170:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231017    052959  28390.8  ...  52.916667  0.582805  0.537085
5770  20231017    055959  28348.6  ...  52.916667  0.588070  0.544294
5771  20231017    062959  28411.9  ...  52.500000  0.586011  0.551345
5772  20231017    065959  28394.6  ...  52.500000  0.594207  0.556104
5773  20231017    072959  28492.5  ...  52.083333  0.589338  0.561692

[5 rows x 33 columns]
0.5518518518518518
acc is : 0.5518518518518518
2023-10-17 08:00:17,230:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.486141  0.513859       1  ...  0.956755   1.0    0.0  1.034149
536     0  0.515824  0.484176       0  ...  0.956173   1.0    0.0  1.033519
537     1  0.498823  0.501177       1  ...  0.959466   1.0    0.0  1.037079
538     0  0.531411  0.468589       0  ...  0.958119   1.0    0.0  1.035623
539     0  0.501600  0.498400       1  ...  0.959261   1.0    0.0  1.036857

[5 rows x 10 columns]
2023-10-17 08:00:17,241:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485704  0.514296       1  ...  0.932917   1.0    0.0  1.031656
46     0  0.516519  0.483481       0  ...  0.963706   1.0    0.0  1.033933
47     1  0.499682  0.500318       1  ...  0.965991   1.0    0.0  1.038603
48     0  0.531963  0.468037       0  ...  0.958119   1.0    0.0  1.036381
49     0  0.501600  0.498400       1  ...  0.959261   1.0    0.0  1.036857

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '22.687', 'enterprice': '28423.9', 'countrevence': '0', 'unrealprofit': '1635.7327', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28496', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22439 

self.closeSec=1697498999, self.tradeDate='20231017', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28471.7', self.close='28452.4'
127.0.0.1 - - [17/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22440 

self.closeSec=1697499599, self.tradeDate='20231017', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28454.6', self.close='28449.9'
127.0.0.1 - - [17/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22441 

self.closeSec=1697500199, self.tradeDate='20231017', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28449.9', self.close='28471.2'
127.0.0.1 - - [17/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22442 

self.closeSec=1697500799, self.tradeDate='20231017', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28471.3', self.close='28486.3'
127.0.0.1 - - [17/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22443 

self.closeSec=1697501399, self.tradeDate='20231017', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28486.3', self.close='28465.9'
127.0.0.1 - - [17/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22444 

self.closeSec=1697501999, self.tradeDate='20231017', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28465.9', self.close='28431.4'
127.0.0.1 - - [17/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22442 

self.closeSec=1697498999, self.tradeDate='20231017', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28471.7', self.close='28452.4'
127.0.0.1 - - [17/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22443127.0.0.1 - - [17/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 

self.closeSec=1697499599, self.tradeDate='20231017', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28454.6', self.close='28449.9'
127.0.0.1 - - [17/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22444 

self.closeSec=1697500199, self.tradeDate='20231017', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28449.9', self.close='28471.2'
127.0.0.1 - - [17/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22445 

self.closeSec=1697500799, self.tradeDate='20231017', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28471.3', self.close='28486.3'
127.0.0.1 - - [17/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22446 

self.closeSec=1697501399, self.tradeDate='20231017', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28486.3', self.close='28465.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22447 

self.closeSec=1697501999, self.tradeDate='20231017', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28465.9', self.close='28431.4'
127.0.0.1 - - [17/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [17/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22442 

self.closeSec=1697498999, self.tradeDate='20231017', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28471.7', self.close='28452.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22443 

self.closeSec=1697499599, self.tradeDate='20231017', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28454.6', self.close='28449.9'
127.0.0.1 - - [17/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22444 

self.closeSec=1697500199, self.tradeDate='20231017', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28449.9', self.close='28471.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22445 

self.closeSec=1697500799, self.tradeDate='20231017', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28471.3', self.close='28486.3'
127.0.0.1 - - [17/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22446 

self.closeSec=1697501399, self.tradeDate='20231017', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28486.3', self.close='28465.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22447 

self.closeSec=1697501999, self.tradeDate='20231017', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28465.9', self.close='28431.4'
127.0.0.1 - - [17/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44884
self.closeSec=1697501999, self.tradeDate='20231017', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28447.5, self.close=28431.4, self.high=28449.9, self.low=28426.6, self.vol=752.215, self.amt=21389075.9525 
127.0.0.1 - - [17/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-10-17 08:20:08,970:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231017   075500    075959  ...         0.0        0.0       0
5856  20231017   080000    080459  ...         0.0        0.0       0
5857  20231017   080500    080959  ...         0.0        0.0       0
5858  20231017   081000    081459  ...         0.0        0.0       0
5859  20231017   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 08:20:08,977:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697501999, self.tradeDate='20231017', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28447.5, self.close=28431.4, self.high=28449.9, self.low=28426.6, self.vol=752.215, self.amt=21389075.9525, ukdf['pct'].iloc[-1]=-0.000562 , ukdf['amount'].iloc[-1]=21389075.9525, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '58961.3375', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28431.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44885
self.closeSec=1697502299, self.tradeDate='20231017', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28431.5, self.close=28443.9, self.high=28453.8, self.low=28431.4, self.vol=416.466, self.amt=11845593.7776 
127.0.0.1 - - [17/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-17 08:25:02,882:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231017   080000    080459  ...         0.0        0.0       0
5857  20231017   080500    080959  ...         0.0        0.0       0
5858  20231017   081000    081459  ...         0.0        0.0       0
5859  20231017   081500    081959  ...         0.0        0.0       0
5860  20231017   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-17 08:25:02,884:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697502299, self.tradeDate='20231017', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28431.5, self.close=28443.9, self.high=28453.8, self.low=28431.4, self.vol=416.466, self.amt=11845593.7776, ukdf['pct'].iloc[-1]=0.00044 , ukdf['amount'].iloc[-1]=11845593.7776, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '59425.6', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231016   200000    235959  1697471999  ...    719  4.305991  6.740435     1.0
720  20231017   000000    035959  1697486399  ...    720  2.848707  3.703573     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '26708.5182', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28450.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=935
self.closeSec=1697500799, self.tradeDate='20231017', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28457.9, self.close=28486.3, self.high=28633.3, self.low=28220.7, self.vol=45745.44, self.amt=1300854259.22117 127.0.0.1 - - [17/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

2023-10-17 08:00:01,524:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697500799, self.tradeDate='20231017', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28457.9, self.close=28486.3, self.high=28633.3, self.low=28220.7, self.vol=45745.44, self.amt=1300854259.22117 
2023-10-17 08:00:01,542:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231016   120000    155959  ...  135348.480  3.756989e+09  0.022427
718  20231016   160000    195959  ...   51668.099  1.433204e+09 -0.003410
719  20231016   200000    235959  ...  460426.856  1.314773e+10  0.011432
720  20231017   000000    035959  ...   99392.957  2.822350e+09  0.014187
721  20231017   040000    075959  ...   45745.440  1.300854e+09  0.001202

[5 rows x 11 columns]
2023-10-17 08:00:02,370:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231016   120000    155959  1697443199  ...    717  1.659620  2.908893     1.0
718  20231016   160000    195959  1697457599  ...    718  1.193590  1.624672     1.0
719  20231016   200000    235959  1697471999  ...    719  4.305991  6.740435     1.0
720  20231017   000000    035959  1697486399  ...    720  2.848707  3.703573     1.0
721  20231017   040000    075959  1697500799  ...    721  1.974534  2.149736     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '28272.3924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28486.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


