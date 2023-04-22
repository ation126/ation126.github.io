# 20230422 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41973
self.closeSec=1682122799, self.tradeDate='20230422', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27311.2, self.close=27288.1, self.high=27325.0, self.low=27288.1, self.vol=1133.431, self.amt=30951230.8664 
127.0.0.1 - - [22/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-22 08:20:04,139:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230422   075500    075959  ...         0.0        0.0       0
5849  20230422   080000    080459  ...         0.0        0.0       0
5850  20230422   080500    080959  ...         0.0        0.0       0
5851  20230422   081000    081459  ...         0.0        0.0       0
5852  20230422   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 08:20:04,142:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682122799, self.tradeDate='20230422', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27311.2, self.close=27288.1, self.high=27325.0, self.low=27288.1, self.vol=1133.431, self.amt=30951230.8664, ukdf['pct'].iloc[-1]=-0.000849 , ukdf['amount'].iloc[-1]=30951230.8664, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-647677.79659537856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27292.35830556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41974
self.closeSec=1682123099, self.tradeDate='20230422', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27288.0, self.close=27276.8, self.high=27311.9, self.low=27274.9, self.vol=712.818, self.amt=19454018.8996 
2023-04-22 08:25:01,551:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230422   080000    080459  ...         0.0        0.0       0
5850  20230422   080500    080959  ...         0.0        0.0       0
5851  20230422   081000    081459  ...         0.0        0.0       0
5852  20230422   081500    081959  ...         0.0        0.0       0
5853  20230422   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 08:25:01,551:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682123099, self.tradeDate='20230422', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27288.0, self.close=27276.8, self.high=27311.9, self.low=27274.9, self.vol=712.818, self.amt=19454018.8996, ukdf['pct'].iloc[-1]=-0.000414 , ukdf['amount'].iloc[-1]=19454018.8996, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-646973.73572368928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27280.65827778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [22/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42535 

self.closeSec=1682121599, self.tradeDate='20230422', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27265.0, self.close=27252.5, self.high=27273.0, self.low=27250.5 
127.0.0.1 - - [22/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42536 

self.closeSec=1682121899, self.tradeDate='20230422', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27252.6, self.close=27271.8, self.high=27274.3, self.low=27246.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42537 

self.closeSec=1682122199, self.tradeDate='20230422', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27271.7, self.close=27272.1, self.high=27288.3, self.low=27270.0 
127.0.0.1 - - [22/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42538 

self.closeSec=1682122499, self.tradeDate='20230422', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27272.0, self.close=27311.3, self.high=27312.4, self.low=27272.0 
127.0.0.1 - - [22/Apr/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42539 

self.closeSec=1682122799, self.tradeDate='20230422', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27311.2, self.close=27288.1, self.high=27325.0, self.low=27288.1 
127.0.0.1 - - [22/Apr/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42540 

self.closeSec=1682123099, self.tradeDate='20230422', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27288.0, self.close=27276.8, self.high=27311.9, self.low=27274.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-22 08:00:21,193:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230422    052959  27263.7  ...  48.750000  0.364098  0.744239
5770  20230422    055959  27349.1  ...  48.333333  0.357498  0.754523
5771  20230422    062959  27279.1  ...  48.333333  0.354910  0.765690
5772  20230422    065959  27251.4  ...  48.333333  0.356340  0.772671
5773  20230422    072959  27259.8  ...  48.750000  0.361422  0.777607

[5 rows x 33 columns]
0.524074074074074
acc is : 0.524074074074074
2023-04-22 08:00:21,311:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.518433  0.481567       0  ...  0.920916  -1.0    0.0  0.935686
536     0  0.506480  0.493520       0  ...  0.921847  -1.0    0.0  0.934740
537     0  0.521708  0.478292       1  ...  0.921567  -1.0    0.0  0.935024
538     0  0.522564  0.477436       1  ...  0.920579  -1.0    0.0  0.936026
539     0  0.536935  0.463065       0  ...  0.921807  -1.0    0.0  0.934777

[5 rows x 10 columns]
2023-04-22 08:00:21,337:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518917  0.481083       0  ...  0.911968  -1.0    0.0  0.959592
46     0  0.506558  0.493442       0  ...  0.909800  -1.0    0.0  0.958510
47     0  0.522467  0.477533       1  ...  0.925390  -1.0    0.0  0.938899
48     0  0.522987  0.477013       1  ...  0.922626  -1.0    0.0  0.938101
49     0  0.536935  0.463065       0  ...  0.921807  -1.0    0.0  0.934777

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21265 

self.closeSec=1682119799, self.tradeDate='20230422', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27320', self.close='27288.9'
127.0.0.1 - - [22/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21266 

self.closeSec=1682120399, self.tradeDate='20230422', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27288.8', self.close='27299.1'
127.0.0.1 - - [22/Apr/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21267 

self.closeSec=1682120999, self.tradeDate='20230422', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27299.2', self.close='27259'
127.0.0.1 - - [22/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21268 

self.closeSec=1682121599, self.tradeDate='20230422', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27259', self.close='27252.5'
127.0.0.1 - - [22/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21269 

self.closeSec=1682122199, self.tradeDate='20230422', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27252.6', self.close='27272.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21270 

self.closeSec=1682122799, self.tradeDate='20230422', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27272', self.close='27288.1'
127.0.0.1 - - [22/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21266 

self.closeSec=1682119799, self.tradeDate='20230422', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27320', self.close='27288.9'
127.0.0.1 - - [22/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21267 

self.closeSec=1682120399, self.tradeDate='20230422', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27288.8', self.close='27299.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21268 

self.closeSec=1682120999, self.tradeDate='20230422', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27299.2', self.close='27259'
127.0.0.1 - - [22/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21269 

self.closeSec=1682121599, self.tradeDate='20230422', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27259', self.close='27252.5'
127.0.0.1 - - [22/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21270 

self.closeSec=1682122199, self.tradeDate='20230422', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27252.6', self.close='27272.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21271 

self.closeSec=1682122799, self.tradeDate='20230422', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27272', self.close='27288.1'
127.0.0.1 - - [22/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [22/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21266 

self.closeSec=1682119799, self.tradeDate='20230422', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27320', self.close='27288.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21267 

self.closeSec=1682120399, self.tradeDate='20230422', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27288.8', self.close='27299.1'
127.0.0.1 - - [22/Apr/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21268 

self.closeSec=1682120999, self.tradeDate='20230422', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27299.2', self.close='27259'
127.0.0.1 - - [22/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21269 

self.closeSec=1682121599, self.tradeDate='20230422', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27259', self.close='27252.5'
127.0.0.1 - - [22/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21270 

self.closeSec=1682122199, self.tradeDate='20230422', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27252.6', self.close='27272.1'
127.0.0.1 - - [22/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21271 

self.closeSec=1682122799, self.tradeDate='20230422', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27272', self.close='27288.1'
127.0.0.1 - - [22/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37971
self.closeSec=1682122799, self.tradeDate='20230422', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27311.2, self.close=27288.1, self.high=27325.0, self.low=27288.1, self.vol=1133.431, self.amt=30951230.8664 
127.0.0.1 - - [22/Apr/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-04-22 08:20:01,712:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230422   075500    075959  ...         0.0        0.0       0
5849  20230422   080000    080459  ...         0.0        0.0       0
5850  20230422   080500    080959  ...         0.0        0.0       0
5851  20230422   081000    081459  ...         0.0        0.0       0
5852  20230422   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 08:20:01,713:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682122799, self.tradeDate='20230422', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27311.2, self.close=27288.1, self.high=27325.0, self.low=27288.1, self.vol=1133.431, self.amt=30951230.8664, ukdf['pct'].iloc[-1]=-0.000849 , ukdf['amount'].iloc[-1]=30951230.8664, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37972
self.closeSec=1682123099, self.tradeDate='20230422', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27288.0, self.close=27276.8, self.high=27311.9, self.low=27274.9, self.vol=712.818, self.amt=19454018.8996 
2023-04-22 08:25:01,531:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230422   080000    080459  ...         0.0        0.0       0
5850  20230422   080500    080959  ...         0.0        0.0       0
5851  20230422   081000    081459  ...         0.0        0.0       0
5852  20230422   081500    081959  ...         0.0        0.0       0
5853  20230422   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 08:25:01,532:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682123099, self.tradeDate='20230422', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27288.0, self.close=27276.8, self.high=27311.9, self.low=27274.9, self.vol=712.818, self.amt=19454018.8996, ukdf['pct'].iloc[-1]=-0.000414 , ukdf['amount'].iloc[-1]=19454018.8996, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230421   200000    235959  1682092799  ...    719  0.809080  0.543306     NaN
720  20230422   000000    035959  1682107199  ...    720  0.754491  0.399747     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-52609.7345592357', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27268.09604762', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [22/Apr/2023 08:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=886
self.closeSec=1682121599, self.tradeDate='20230422', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27273.6, self.close=27252.5, self.high=27400.0, self.low=27100.0, self.vol=91017.726, self.amt=2482799699.93759 
2023-04-22 08:00:03,095:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682121599, self.tradeDate='20230422', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27273.6, self.close=27252.5, self.high=27400.0, self.low=27100.0, self.vol=91017.726, self.amt=2482799699.93759 
2023-04-22 08:00:03,165:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230421   120000    155959  ...  119795.709  3.357784e+09 -0.005892
718  20230421   160000    195959  ...   80831.360  2.267150e+09 -0.003120
719  20230421   200000    235959  ...  126677.763  3.563100e+09 -0.000773
720  20230422   000000    035959  ...  211114.720  5.835342e+09 -0.027083
721  20230422   040000    075959  ...   91017.726  2.482800e+09 -0.000774

[5 rows x 11 columns]
2023-04-22 08:00:04,521:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230421   120000    155959  1682063999  ...    717  0.725958  0.377815     NaN
718  20230421   160000    195959  1682078399  ...    718  0.788889  0.510818     NaN
719  20230421   200000    235959  1682092799  ...    719  0.809080  0.543306     NaN
720  20230422   000000    035959  1682107199  ...    720  0.754491  0.399747     NaN
721  20230422   040000    075959  1682121599  ...    721  0.820729  0.542145     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-53413.2271879857', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27252.79579762', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


