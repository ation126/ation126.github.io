# 20230425 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42837
self.closeSec=1682381999, self.tradeDate='20230425', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27518.7, self.close=27548.5, self.high=27557.1, self.low=27495.3, self.vol=1367.66, self.amt=37647962.791 
127.0.0.1 - - [25/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-25 08:20:05,265:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230425   075500    075959  ...         0.0        0.0       0
5849  20230425   080000    080459  ...         0.0        0.0       0
5850  20230425   080500    080959  ...         0.0        0.0       0
5851  20230425   081000    081459  ...         0.0        0.0       0
5852  20230425   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 08:20:05,281:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682381999, self.tradeDate='20230425', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27518.7, self.close=27548.5, self.high=27557.1, self.low=27495.3, self.vol=1367.66, self.amt=37647962.791, ukdf['pct'].iloc[-1]=0.001083 , ukdf['amount'].iloc[-1]=37647962.791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-663494.5584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27555.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42838
self.closeSec=1682382299, self.tradeDate='20230425', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27548.6, self.close=27479.8, self.high=27583.6, self.low=27468.3, self.vol=3299.32, self.amt=90795621.2566 
127.0.0.1 - - [25/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-25 08:25:01,692:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230425   080000    080459  ...         0.0        0.0       0
5850  20230425   080500    080959  ...         0.0        0.0       0
5851  20230425   081000    081459  ...         0.0        0.0       0
5852  20230425   081500    081959  ...         0.0        0.0       0
5853  20230425   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 08:25:01,698:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682382299, self.tradeDate='20230425', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27548.6, self.close=27479.8, self.high=27583.6, self.low=27468.3, self.vol=3299.32, self.amt=90795621.2566, ukdf['pct'].iloc[-1]=-0.002494 , ukdf['amount'].iloc[-1]=90795621.2566, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-659155.8308319528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27483.09936905', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [25/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43399 

self.closeSec=1682380799, self.tradeDate='20230425', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27505.0, self.close=27497.5, self.high=27515.0, self.low=27491.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43400 

self.closeSec=1682381099, self.tradeDate='20230425', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27497.4, self.close=27511.4, self.high=27513.4, self.low=27496.0 
127.0.0.1 - - [25/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43401 

self.closeSec=1682381399, self.tradeDate='20230425', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27511.5, self.close=27504.3, self.high=27513.2, self.low=27483.1 
127.0.0.1 - - [25/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43402 

self.closeSec=1682381699, self.tradeDate='20230425', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27504.4, self.close=27518.7, self.high=27562.8, self.low=27504.3 
127.0.0.1 - - [25/Apr/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43403 

self.closeSec=1682381999, self.tradeDate='20230425', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27518.7, self.close=27548.5, self.high=27557.1, self.low=27495.3 
127.0.0.1 - - [25/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43404 

self.closeSec=1682382299, self.tradeDate='20230425', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27548.6, self.close=27479.8, self.high=27583.6, self.low=27468.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-25 08:00:18,893:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230425    052959  27446.7  ...  51.666667  0.474185  0.618274
5770  20230425    055959  27358.9  ...  51.666667  0.480694  0.608104
5771  20230425    062959  27400.0  ...  52.083333  0.486612  0.594199
5772  20230425    065959  27437.5  ...  52.500000  0.488246  0.580426
5773  20230425    072959  27447.9  ...  52.916667  0.501668  0.560974

[5 rows x 33 columns]
0.5314814814814814
acc is : 0.5314814814814814
2023-04-25 08:00:19,012:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.495065  0.504935       1  ...  0.824681   1.0    0.0  0.900726
536     0  0.525979  0.474021       1  ...  0.825810   1.0    0.0  0.901959
537     0  0.525513  0.474487       1  ...  0.826120   1.0    0.0  0.902298
538     0  0.518686  0.481314       1  ...  0.828690   1.0    0.0  0.905105
539     0  0.536865  0.463135       0  ...  0.827615   1.0    0.0  0.903931

[5 rows x 10 columns]
2023-04-25 08:00:19,038:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494987  0.505013       1  ...  0.824681   1.0    0.0  0.900649
46     0  0.526365  0.473635       1  ...  0.825810   1.0    0.0  0.904215
47     0  0.526217  0.473783       1  ...  0.836221   1.0    0.0  0.905488
48     0  0.519056  0.480944       1  ...  0.838823   1.0    0.0  0.907261
49     0  0.536865  0.463135       0  ...  0.827615   1.0    0.0  0.903931

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21697 

self.closeSec=1682378999, self.tradeDate='20230425', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27464.5', self.close='27533.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21698 

self.closeSec=1682379599, self.tradeDate='20230425', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27533.1', self.close='27519.7'
127.0.0.1 - - [25/Apr/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21699 

self.closeSec=1682380199, self.tradeDate='20230425', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27519.6', self.close='27486'
127.0.0.1 - - [25/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21700 

self.closeSec=1682380799, self.tradeDate='20230425', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27486', self.close='27497.5'
127.0.0.1 - - [25/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21701 

self.closeSec=1682381399, self.tradeDate='20230425', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27497.4', self.close='27504.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21702 

self.closeSec=1682381999, self.tradeDate='20230425', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27504.4', self.close='27548.5'
127.0.0.1 - - [25/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21698 

self.closeSec=1682378999, self.tradeDate='20230425', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27464.5', self.close='27533.1'
127.0.0.1 - - [25/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21699 

self.closeSec=1682379599, self.tradeDate='20230425', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27533.1', self.close='27519.7'
127.0.0.1 - - [25/Apr/2023 07:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21700 

self.closeSec=1682380199, self.tradeDate='20230425', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27519.6', self.close='27486'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21701 

self.closeSec=1682380799, self.tradeDate='20230425', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27486', self.close='27497.5'
127.0.0.1 - - [25/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21702 

self.closeSec=1682381399, self.tradeDate='20230425', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27497.4', self.close='27504.3'
127.0.0.1 - - [25/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21703 

self.closeSec=1682381999, self.tradeDate='20230425', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27504.4', self.close='27548.5'
127.0.0.1 - - [25/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21698 

self.closeSec=1682378999, self.tradeDate='20230425', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27464.5', self.close='27533.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21699 

self.closeSec=1682379599, self.tradeDate='20230425', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27533.1', self.close='27519.7'
127.0.0.1 - - [25/Apr/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21700 

self.closeSec=1682380199, self.tradeDate='20230425', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27519.6', self.close='27486'
127.0.0.1 - - [25/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21701 

self.closeSec=1682380799, self.tradeDate='20230425', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27486', self.close='27497.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21702 

self.closeSec=1682381399, self.tradeDate='20230425', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27497.4', self.close='27504.3'
127.0.0.1 - - [25/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21703 

self.closeSec=1682381999, self.tradeDate='20230425', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27504.4', self.close='27548.5'
127.0.0.1 - - [25/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38835
self.closeSec=1682381999, self.tradeDate='20230425', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27518.7, self.close=27548.5, self.high=27557.1, self.low=27495.3, self.vol=1367.66, self.amt=37647962.791 
127.0.0.1 - - [25/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-25 08:20:05,918:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230425   075500    075959  ...         0.0        0.0       0
5849  20230425   080000    080459  ...         0.0        0.0       0
5850  20230425   080500    080959  ...         0.0        0.0       0
5851  20230425   081000    081459  ...         0.0        0.0       0
5852  20230425   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 08:20:05,922:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682381999, self.tradeDate='20230425', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27518.7, self.close=27548.5, self.high=27557.1, self.low=27495.3, self.vol=1367.66, self.amt=37647962.791, ukdf['pct'].iloc[-1]=0.001083 , ukdf['amount'].iloc[-1]=37647962.791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38836
self.closeSec=1682382299, self.tradeDate='20230425', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27548.6, self.close=27479.8, self.high=27583.6, self.low=27468.3, self.vol=3299.32, self.amt=90795621.2566 
127.0.0.1 - - [25/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-25 08:25:01,710:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230425   080000    080459  ...         0.0        0.0       0
5850  20230425   080500    080959  ...         0.0        0.0       0
5851  20230425   081000    081459  ...         0.0        0.0       0
5852  20230425   081500    081959  ...         0.0        0.0       0
5853  20230425   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-25 08:25:01,711:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682382299, self.tradeDate='20230425', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27548.6, self.close=27479.8, self.high=27583.6, self.low=27468.3, self.vol=3299.32, self.amt=90795621.2566, ukdf['pct'].iloc[-1]=-0.002494 , ukdf['amount'].iloc[-1]=90795621.2566, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230424   200000    235959  1682351999  ...    719  1.016895  0.705436     1.0
720  20230425   000000    035959  1682366399  ...    720  0.742974 -0.015014     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-47016.6795', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27374.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [25/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=904
self.closeSec=1682380799, self.tradeDate='20230425', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27373.8, self.close=27497.5, self.high=27547.1, self.low=27305.2, self.vol=37313.066, self.amt=1023683974.8875 
2023-04-25 08:00:01,797:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682380799, self.tradeDate='20230425', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27373.8, self.close=27497.5, self.high=27547.1, self.low=27305.2, self.vol=37313.066, self.amt=1023683974.8875 
2023-04-25 08:00:01,851:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230424   120000    155959  ...   65884.391  1.814763e+09 -0.012210
718  20230424   160000    195959  ...  101737.772  2.780949e+09  0.003615
719  20230424   200000    235959  ...  135196.378  3.711698e+09 -0.010312
720  20230425   000000    035959  ...  141565.215  3.860182e+09  0.004322
721  20230425   040000    075959  ...   37313.066  1.023684e+09  0.004519

[5 rows x 11 columns]
2023-04-25 08:00:03,615:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230424   120000    155959  1682323199  ...    717  0.946303  0.563779     NaN
718  20230424   160000    195959  1682337599  ...    718  1.007050  0.697512     1.0
719  20230424   200000    235959  1682351999  ...    719  1.016895  0.705436     1.0
720  20230425   000000    035959  1682366399  ...    720  0.742974 -0.015014     NaN
721  20230425   040000    075959  1682380799  ...    721  0.628881 -0.321602     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-40527.5695399548', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27498.16678968', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


