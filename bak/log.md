# 20231024 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46900
self.closeSec=1698106799, self.tradeDate='20231024', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=32982.1, self.close=33010.1, self.high=33030.0, self.low=32916.5, self.vol=2353.901, self.amt=77636200.6288 
127.0.0.1 - - [24/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -
2023-10-24 08:20:16,613:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231024   075500    075959  ...         0.0        0.0       0
5856  20231024   080000    080459  ...         0.0        0.0       0
5857  20231024   080500    080959  ...         0.0        0.0       0
5858  20231024   081000    081459  ...         0.0        0.0       0
5859  20231024   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 08:20:16,624:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698106799, self.tradeDate='20231024', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=32982.1, self.close=33010.1, self.high=33030.0, self.low=32916.5, self.vol=2353.901, self.amt=77636200.6288, ukdf['pct'].iloc[-1]=0.000373 , ukdf['amount'].iloc[-1]=77636200.6288, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-85750.75412751606', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '33022.50118681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46901
self.closeSec=1698107099, self.tradeDate='20231024', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=33011.5, self.close=33277.7, self.high=33280.0, self.low=33003.7, self.vol=6424.456, self.amt=213120755.95145 
127.0.0.1 - - [24/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-24 08:25:03,132:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231024   080000    080459  ...         0.0        0.0       0
5857  20231024   080500    080959  ...         0.0        0.0       0
5858  20231024   081000    081459  ...         0.0        0.0       0
5859  20231024   081500    081959  ...         0.0        0.0       0
5860  20231024   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 08:25:03,135:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698107099, self.tradeDate='20231024', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=33011.5, self.close=33277.7, self.high=33280.0, self.low=33003.7, self.vol=6424.456, self.amt=213120755.95145, ukdf['pct'].iloc[-1]=0.008107 , ukdf['amount'].iloc[-1]=213120755.95145, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-89373.80018500032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '33282.66534432', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46898 

self.closeSec=1698105599, self.tradeDate='20231024', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=32947.4, self.close=33071.9, self.high=33118.5, self.low=32933.7 
127.0.0.1 - - [24/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46899 

self.closeSec=1698105899, self.tradeDate='20231024', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=33074.0, self.close=33038.5, self.high=33131.1, self.low=33010.0 
127.0.0.1 - - [24/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46900 

self.closeSec=1698106199, self.tradeDate='20231024', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=33029.9, self.close=32880.6, self.high=33032.7, self.low=32833.5 
127.0.0.1 - - [24/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46901 

self.closeSec=1698106499, self.tradeDate='20231024', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=32880.5, self.close=32997.8, self.high=33066.3, self.low=32874.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46902 

self.closeSec=1698106799, self.tradeDate='20231024', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=32982.1, self.close=33010.1, self.high=33030.0, self.low=32916.5 
127.0.0.1 - - [24/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46903 

self.closeSec=1698107099, self.tradeDate='20231024', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=33011.5, self.close=33277.7, self.high=33280.0, self.low=33003.7 
127.0.0.1 - - [24/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-24 08:00:17,011:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231024    052959  31511.5  ...  56.666667  0.645229  0.213670
5770  20231024    055959  31536.9  ...  57.083333  0.652253  0.207850
5771  20231024    062959  31618.7  ...  57.083333  0.693784  0.195095
5772  20231024    065959  32179.2  ...  57.083333  0.756551  0.213128
5773  20231024    072959  33358.8  ...  57.083333  0.725481  0.233049

[5 rows x 33 columns]
0.55
acc is : 0.55
2023-10-24 08:00:17,073:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.557549  0.442451       1  ...  1.043549   1.0    0.0  1.187133
536     0  0.575232  0.424768       1  ...  1.061652   1.0    0.0  1.207727
537     0  0.698205  0.301795       1  ...  1.099950   1.0    0.0  1.251294
538     0  0.839994  0.160006       0  ...  1.092108   1.0    0.0  1.242374
539     0  0.595233  0.404767       0  ...  1.091600   1.0    0.0  1.241795

[5 rows x 10 columns]
2023-10-24 08:00:17,084:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.557460  0.442540       1  ...  1.043549   1.0    0.0  1.185864
46     0  0.575505  0.424495       1  ...  1.061652   1.0    0.0  1.203466
47     0  0.698558  0.301442       1  ...  1.099950   1.0    0.0  1.249933
48     0  0.839154  0.160846       0  ...  1.092108   1.0    0.0  1.244504
49     0  0.595233  0.404767       0  ...  1.091600   1.0    0.0  1.241795

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.157', 'enterprice': '29765.1', 'countrevence': '0', 'unrealprofit': '70350.81087525929', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33090.27894197', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23447 

self.closeSec=1698103799, self.tradeDate='20231024', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='33183.6', self.close='33090'
127.0.0.1 - - [24/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23448 

self.closeSec=1698104399, self.tradeDate='20231024', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='33089.6', self.close='32670.3'
127.0.0.1 - - [24/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23449 

self.closeSec=1698104999, self.tradeDate='20231024', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='32674.2', self.close='32925.2'

--handleKline--:  127.0.0.1 - - [24/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23450 

self.closeSec=1698105599, self.tradeDate='20231024', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='32928.1', self.close='33074.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23451 

self.closeSec=1698106199, self.tradeDate='20231024', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='33074', self.close='32880.6'
127.0.0.1 - - [24/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23452 

self.closeSec=1698106799, self.tradeDate='20231024', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='32880.5', self.close='33011.6'
127.0.0.1 - - [24/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23450 

self.closeSec=1698103799, self.tradeDate='20231024', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='33183.6', self.close='33090'
127.0.0.1 - - [24/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23451 

self.closeSec=1698104399, self.tradeDate='20231024', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='33089.6', self.close='32670.3'
127.0.0.1 - - [24/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23452 

self.closeSec=1698104999, self.tradeDate='20231024', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='32674.2', self.close='32925.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23453 

self.closeSec=1698105599, self.tradeDate='20231024', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='32928.1', self.close='33074.6'
127.0.0.1 - - [24/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23454 

self.closeSec=1698106199, self.tradeDate='20231024', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='33074', self.close='32880.6'
127.0.0.1 - - [24/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23455 

self.closeSec=1698106799, self.tradeDate='20231024', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='32880.5', self.close='33011.6'
127.0.0.1 - - [24/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23450 

self.closeSec=1698103799, self.tradeDate='20231024', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='33183.6', self.close='33090'
127.0.0.1 - - [24/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23451 

self.closeSec=1698104399, self.tradeDate='20231024', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='33089.6', self.close='32670.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23452 

self.closeSec=1698104999, self.tradeDate='20231024', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='32674.2', self.close='32925.2'
127.0.0.1 - - [24/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23453 

self.closeSec=1698105599, self.tradeDate='20231024', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='32928.1', self.close='33074.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23454 

self.closeSec=1698106199, self.tradeDate='20231024', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='33074', self.close='32880.6'
127.0.0.1 - - [24/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23455 

self.closeSec=1698106799, self.tradeDate='20231024', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='32880.5', self.close='33011.6'
127.0.0.1 - - [24/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46900
self.closeSec=1698106799, self.tradeDate='20231024', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=32982.1, self.close=33010.1, self.high=33030.0, self.low=32916.5, self.vol=2353.901, self.amt=77636200.6288 
127.0.0.1 - - [24/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-24 08:20:16,603:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231024   075500    075959  ...         0.0        0.0       0
5856  20231024   080000    080459  ...         0.0        0.0       0
5857  20231024   080500    080959  ...         0.0        0.0       0
5858  20231024   081000    081459  ...         0.0        0.0       0
5859  20231024   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 08:20:16,605:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698106799, self.tradeDate='20231024', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=32982.1, self.close=33010.1, self.high=33030.0, self.low=32916.5, self.vol=2353.901, self.amt=77636200.6288, ukdf['pct'].iloc[-1]=0.000373 , ukdf['amount'].iloc[-1]=77636200.6288, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '229475.71257931021', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33022.50118681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46901
self.closeSec=1698107099, self.tradeDate='20231024', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=33011.5, self.close=33277.7, self.high=33280.0, self.low=33003.7, self.vol=6424.456, self.amt=213120755.95145 
127.0.0.1 - - [24/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-24 08:25:03,126:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231024   080000    080459  ...         0.0        0.0       0
5857  20231024   080500    080959  ...         0.0        0.0       0
5858  20231024   081000    081459  ...         0.0        0.0       0
5859  20231024   081500    081959  ...         0.0        0.0       0
5860  20231024   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 08:25:03,128:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698107099, self.tradeDate='20231024', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=33011.5, self.close=33277.7, self.high=33280.0, self.low=33003.7, self.vol=6424.456, self.amt=213120755.95145, ukdf['pct'].iloc[-1]=0.008107 , ukdf['amount'].iloc[-1]=213120755.95145, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '239138.46955338912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33282.66534432', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231023   200000    235959  1698076799  ...    719  0.790494  0.109719     NaN
720  20231024   000000    035959  1698091199  ...    720  0.865805  0.219781     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '74515.9776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31340.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  127.0.0.1 - - [24/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=977
self.closeSec=1698105599, self.tradeDate='20231024', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=31340.3, self.close=33074.6, self.high=35981.9, self.low=31302.2, self.vol=377945.899, self.amt=12399923198.81281 
2023-10-24 08:00:01,542:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698105599, self.tradeDate='20231024', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=31340.3, self.close=33074.6, self.high=35981.9, self.low=31302.2, self.vol=377945.899, self.amt=12399923198.81281 
2023-10-24 08:00:01,588:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231023   120000    155959  ...  109840.976  3.375397e+09 -0.007011
718  20231023   160000    195959  ...   67535.437  2.062828e+09  0.004451
719  20231023   200000    235959  ...   89649.140  2.751678e+09  0.007248
720  20231024   000000    035959  ...  214045.310  6.646158e+09  0.015314
721  20231024   040000    075959  ...  377945.899  1.239992e+10  0.055375

[5 rows x 11 columns]
2023-10-24 08:00:02,517:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231023   120000    155959  1698047999  ...    717  0.892948  0.299264     NaN
718  20231023   160000    195959  1698062399  ...    718  0.822363  0.173331     NaN
719  20231023   200000    235959  1698076799  ...    719  0.790494  0.109719     NaN
720  20231024   000000    035959  1698091199  ...    720  0.865805  0.219781     NaN
721  20231024   040000    075959  1698105599  ...    721  2.431451  2.654970     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '146202.8628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33074', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


