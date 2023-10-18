# 20231018 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45172
self.closeSec=1697588399, self.tradeDate='20231018', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28361.7, self.close=28410.9, self.high=28417.1, self.low=28361.6, self.vol=477.51, self.amt=13557094.8788 
127.0.0.1 - - [18/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-18 08:20:17,031:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231018   075500    075959  ...         0.0        0.0       0
5856  20231018   080000    080459  ...         0.0        0.0       0
5857  20231018   080500    080959  ...         0.0        0.0       0
5858  20231018   081000    081459  ...         0.0        0.0       0
5859  20231018   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 08:20:17,199:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697588399, self.tradeDate='20231018', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28361.7, self.close=28410.9, self.high=28417.1, self.low=28361.6, self.vol=477.51, self.amt=13557094.8788, ukdf['pct'].iloc[-1]=0.001735 , ukdf['amount'].iloc[-1]=13557094.8788, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-21583.9074', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28414.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45173
self.closeSec=1697588699, self.tradeDate='20231018', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28410.9, self.close=28418.9, self.high=28418.9, self.low=28403.4, self.vol=292.93, self.amt=8322620.1096 
127.0.0.1 - - [18/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-18 08:25:03,276:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231018   080000    080459  ...         0.0        0.0       0
5857  20231018   080500    080959  ...         0.0        0.0       0
5858  20231018   081000    081459  ...         0.0        0.0       0
5859  20231018   081500    081959  ...         0.0        0.0       0
5860  20231018   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 08:25:03,287:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697588699, self.tradeDate='20231018', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28410.9, self.close=28418.9, self.high=28418.9, self.low=28403.4, self.vol=292.93, self.amt=8322620.1096, ukdf['pct'].iloc[-1]=0.000282 , ukdf['amount'].iloc[-1]=8322620.1096, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-21641.004', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28418.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45170 

self.closeSec=1697587199, self.tradeDate='20231018', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28389.4, self.close=28382.0, self.high=28394.5, self.low=28381.9 
127.0.0.1 - - [18/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45171 

self.closeSec=1697587499, self.tradeDate='20231018', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28382.0, self.close=28392.0, self.high=28393.5, self.low=28375.5 
127.0.0.1 - - [18/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45172 

self.closeSec=1697587799, self.tradeDate='20231018', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28392.0, self.close=28417.4, self.high=28417.4, self.low=28380.0 
127.0.0.1 - - [18/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45173 

self.closeSec=1697588099, self.tradeDate='20231018', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28417.4, self.close=28361.7, self.high=28424.1, self.low=28355.2 
127.0.0.1 - - [18/Oct/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45174 

self.closeSec=1697588399, self.tradeDate='20231018', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28361.7, self.close=28410.9, self.high=28417.1, self.low=28361.6 
127.0.0.1 - - [18/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45175 

self.closeSec=1697588699, self.tradeDate='20231018', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28410.9, self.close=28418.9, self.high=28418.9, self.low=28403.4 
127.0.0.1 - - [18/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-18 08:00:16,843:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231018    052959  28431.4  ...  52.083333  0.565993  0.421130
5770  20231018    055959  28537.4  ...  51.666667  0.555451  0.409588
5771  20231018    062959  28468.6  ...  51.666667  0.550862  0.402476
5772  20231018    065959  28437.4  ...  51.666667  0.545818  0.399850
5773  20231018    072959  28405.4  ...  52.083333  0.547771  0.395545

[5 rows x 33 columns]
0.5740740740740741
acc is : 0.5740740740740741
2023-10-18 08:00:16,914:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.543362  0.456638       0  ...  0.971518  -1.0    0.0  1.018675
536     1  0.485478  0.514522       0  ...  0.972548  -1.0    0.0  1.017594
537     1  0.488551  0.511449       0  ...  0.973680  -1.0    0.0  1.016410
538     1  0.484321  0.515679       1  ...  0.973156  -1.0    0.0  1.016957
539     0  0.502837  0.497163       0  ...  0.974481  -1.0    0.0  1.015573

[5 rows x 10 columns]
2023-10-18 08:00:16,927:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.543827  0.456173       0  ...  0.956275  -1.0    0.0  1.019412
46     1  0.486296  0.513704       0  ...  0.972548  -1.0    0.0  1.020845
47     1  0.488800  0.511200       0  ...  0.973680  -1.0    0.0  1.019529
48     1  0.484290  0.515710       1  ...  0.973156  -1.0    0.0  1.018879
49     0  0.502837  0.497163       0  ...  0.974481  -1.0    0.0  1.015573

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '22.655', 'enterprice': '28244.6', 'countrevence': '0', 'unrealprofit': '-3112.797', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28382', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22583 

self.closeSec=1697585399, self.tradeDate='20231018', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28424.7', self.close='28420.6'
127.0.0.1 - - [18/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22584 127.0.0.1 - - [18/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -


self.closeSec=1697585999, self.tradeDate='20231018', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28420.6', self.close='28413.6'
127.0.0.1 - - [18/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22585 

self.closeSec=1697586599, self.tradeDate='20231018', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28413.6', self.close='28383.8'
127.0.0.1 - - [18/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22586 

self.closeSec=1697587199, self.tradeDate='20231018', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28387.1', self.close='28381.9'
127.0.0.1 - - [18/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22587 

self.closeSec=1697587799, self.tradeDate='20231018', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28382', self.close='28417.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22588 

self.closeSec=1697588399, self.tradeDate='20231018', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28417.4', self.close='28410.9'
127.0.0.1 - - [18/Oct/2023 08:20:13] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22586 

self.closeSec=1697585399, self.tradeDate='20231018', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28424.7', self.close='28420.6'
127.0.0.1 - - [18/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22587 

self.closeSec=1697585999, self.tradeDate='20231018', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28420.6', self.close='28413.6'
127.0.0.1 - - [18/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22588 

self.closeSec=1697586599, self.tradeDate='20231018', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28413.6', self.close='28383.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22589 

self.closeSec=1697587199, self.tradeDate='20231018', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28387.1', self.close='28381.9'
127.0.0.1 - - [18/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22590 

self.closeSec=1697587799, self.tradeDate='20231018', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28382', self.close='28417.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22591 

self.closeSec=1697588399, self.tradeDate='20231018', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28417.4', self.close='28410.9'
127.0.0.1 - - [18/Oct/2023 08:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [18/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22586 

self.closeSec=1697585399, self.tradeDate='20231018', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28424.7', self.close='28420.6'
127.0.0.1 - - [18/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22587 

self.closeSec=1697585999, self.tradeDate='20231018', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28420.6', self.close='28413.6'
127.0.0.1 - - [18/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22588 

self.closeSec=1697586599, self.tradeDate='20231018', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28413.6', self.close='28383.8'
127.0.0.1 - - [18/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22589 

self.closeSec=1697587199, self.tradeDate='20231018', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28387.1', self.close='28381.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22590 

self.closeSec=1697587799, self.tradeDate='20231018', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28382', self.close='28417.4'
127.0.0.1 - - [18/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22591 

self.closeSec=1697588399, self.tradeDate='20231018', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28417.4', self.close='28410.9'
127.0.0.1 - - [18/Oct/2023 08:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45172
self.closeSec=1697588399, self.tradeDate='20231018', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28361.7, self.close=28410.9, self.high=28417.1, self.low=28361.6, self.vol=477.51, self.amt=13557094.8788 
127.0.0.1 - - [18/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-18 08:20:17,031:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231018   075500    075959  ...         0.0        0.0       0
5856  20231018   080000    080459  ...         0.0        0.0       0
5857  20231018   080500    080959  ...         0.0        0.0       0
5858  20231018   081000    081459  ...         0.0        0.0       0
5859  20231018   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 08:20:17,199:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697588399, self.tradeDate='20231018', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28361.7, self.close=28410.9, self.high=28417.1, self.low=28361.6, self.vol=477.51, self.amt=13557094.8788, ukdf['pct'].iloc[-1]=0.001735 , ukdf['amount'].iloc[-1]=13557094.8788, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '58341.0828', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28414.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45173
self.closeSec=1697588699, self.tradeDate='20231018', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28410.9, self.close=28418.9, self.high=28418.9, self.low=28403.4, self.vol=292.93, self.amt=8322620.1096 
127.0.0.1 - - [18/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-18 08:25:03,270:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231018   080000    080459  ...         0.0        0.0       0
5857  20231018   080500    080959  ...         0.0        0.0       0
5858  20231018   081000    081459  ...         0.0        0.0       0
5859  20231018   081500    081959  ...         0.0        0.0       0
5860  20231018   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-18 08:25:03,275:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697588699, self.tradeDate='20231018', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28410.9, self.close=28418.9, self.high=28418.9, self.low=28403.4, self.vol=292.93, self.amt=8322620.1096, ukdf['pct'].iloc[-1]=0.000282 , ukdf['amount'].iloc[-1]=8322620.1096, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '58493.3609', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28418.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231017   200000    235959  1697558399  ...    719  1.170284  0.775830     1.0
720  20231018   000000    035959  1697572799  ...    720  1.104558  0.671671     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '28802.445', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28498.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [18/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=941
self.closeSec=1697587199, self.tradeDate='20231018', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28499.0, self.close=28381.9, self.high=28544.3, self.low=28360.0, self.vol=24541.976, self.amt=698314764.88826 
2023-10-18 08:00:01,527:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697587199, self.tradeDate='20231018', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28499.0, self.close=28381.9, self.high=28544.3, self.low=28360.0, self.vol=24541.976, self.amt=698314764.88826 
2023-10-18 08:00:01,553:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231017   120000    155959  ...  53558.993  1.511652e+09  0.005266
718  20231017   160000    195959  ...  53721.483  1.528497e+09  0.000018
719  20231017   200000    235959  ...  98853.837  2.801737e+09  0.001306
720  20231018   000000    035959  ...  47386.641  1.347540e+09  0.001870
721  20231018   040000    075959  ...  24541.976  6.983148e+08 -0.004109

[5 rows x 11 columns]
2023-10-18 08:00:02,270:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231017   120000    155959  1697529599  ...    717  1.401377  1.162817     1.0
718  20231017   160000    195959  1697543999  ...    718  1.211667  0.847822     1.0
719  20231017   200000    235959  1697558399  ...    719  1.170284  0.775830     1.0
720  20231018   000000    035959  1697572799  ...    720  1.104558  0.671671     1.0
721  20231018   040000    075959  1697587199  ...    721  0.992506  0.497216     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '23730.03689989128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28382.60745788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


