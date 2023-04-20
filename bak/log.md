# 20230420 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41397
self.closeSec=1681949999, self.tradeDate='20230420', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28713.8, self.close=28792.3, self.high=28795.3, self.low=28704.2, self.vol=2111.563, self.amt=60708570.843 
127.0.0.1 - - [20/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-20 08:20:05,027:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230420   075500    075959  ...         0.0        0.0       0
5849  20230420   080000    080459  ...         0.0        0.0       0
5850  20230420   080500    080959  ...         0.0        0.0       0
5851  20230420   081000    081459  ...         0.0        0.0       0
5852  20230420   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 08:20:05,029:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681949999, self.tradeDate='20230420', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28713.8, self.close=28792.3, self.high=28795.3, self.low=28704.2, self.vol=2111.563, self.amt=60708570.843, ukdf['pct'].iloc[-1]=0.002734 , ukdf['amount'].iloc[-1]=60708570.843, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-737938.288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28792.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41398
self.closeSec=1681950299, self.tradeDate='20230420', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28792.3, self.close=28832.1, self.high=28877.0, self.low=28792.3, self.vol=2701.693, self.amt=77900769.6593 
127.0.0.1 - - [20/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-20 08:25:01,686:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230420   080000    080459  ...         0.0        0.0       0
5850  20230420   080500    080959  ...         0.0        0.0       0
5851  20230420   081000    081459  ...         0.0        0.0       0
5852  20230420   081500    081959  ...         0.0        0.0       0
5853  20230420   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 08:25:01,687:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681950299, self.tradeDate='20230420', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28792.3, self.close=28832.1, self.high=28877.0, self.low=28792.3, self.vol=2701.693, self.amt=77900769.6593, ukdf['pct'].iloc[-1]=0.001382 , ukdf['amount'].iloc[-1]=77900769.6593, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-740649.10408914848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28837.34812698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41959 

self.closeSec=1681948799, self.tradeDate='20230420', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28791.6, self.close=28800.0, self.high=28863.9, self.low=28786.2 
127.0.0.1 - - [20/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41960 

self.closeSec=1681949099, self.tradeDate='20230420', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28795.0, self.close=28794.9, self.high=28809.3, self.low=28759.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41961 

self.closeSec=1681949399, self.tradeDate='20230420', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28794.9, self.close=28789.9, self.high=28806.0, self.low=28762.2 
127.0.0.1 - - [20/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41962 

self.closeSec=1681949699, self.tradeDate='20230420', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28789.9, self.close=28713.8, self.high=28789.9, self.low=28710.6 
127.0.0.1 - - [20/Apr/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41963 

self.closeSec=1681949999, self.tradeDate='20230420', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28713.8, self.close=28792.3, self.high=28795.3, self.low=28704.2 
127.0.0.1 - - [20/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41964 

self.closeSec=1681950299, self.tradeDate='20230420', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28792.3, self.close=28832.1, self.high=28877.0, self.low=28792.3 
127.0.0.1 - - [20/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

5770  20230420    055959  29043.9  ...  50.833333  0.413173  0.675297
5771  20230420    062959  29165.0  ...  50.833333  0.400696  0.685155
5772  20230420    065959  29069.2  ...  50.416667  0.400436  0.694443
5773  20230420    072959  29068.0  ...  50.416667  0.358803  0.708790

[5 rows x 33 columns]
0.49074074074074076
acc is : 0.49074074074074076
2023-04-20 08:00:21,298:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
535     1  0.481504  0.518496       1  ...  1.024556  -1.0  0.0000  1.042221
536     0  0.552167  0.447833       0  ...  1.019580   1.0 -0.0016  1.038826
537     0  0.505347  0.494653       0  ...  1.019510   1.0  0.0000  1.038755
538     0  0.526012  0.473988       0  ...  1.007206   1.0  0.0000  1.026219
539     1  0.428152  0.571848       1  ...  1.002862  -1.0 -0.0016  1.029003

[5 rows x 10 columns]
2023-04-20 08:00:21,326:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.481607  0.518393       1  ...  1.024556  -1.0  0.0000  1.041968
46     0  0.551832  0.448168       0  ...  1.019580   1.0 -0.0016  1.038055
47     0  0.505328  0.494672       0  ...  1.019510   1.0  0.0000  1.038666
48     0  0.525646  0.474354       0  ...  1.007206   1.0  0.0000  1.025948
49     1  0.428152  0.571848       1  ...  1.002862  -1.0 -0.0016  1.029003

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-04-20 08:00:21,564:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '26.562', 'sell' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:764619.0444', 'result': 'success', 'clientorderid': ''}
2023-04-20 08:00:21,580:INFO:logic:main.py:494:insertFactor:885513: curDateTime:4200800, name:logic, symbol:BTCUSDT, tradeDate:20230420, closeTime:075959, close:28795.1, sign:-1, total:767183.2585902, side:sell  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20977 

self.closeSec=1681946999, self.tradeDate='20230420', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28872.4', self.close='28719'
127.0.0.1 - - [20/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20978 

self.closeSec=1681947599, self.tradeDate='20230420', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28719', self.close='28682.8'
127.0.0.1 - - [20/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20979 

self.closeSec=1681948199, self.tradeDate='20230420', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28715', self.close='28805'
127.0.0.1 - - [20/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20980 

self.closeSec=1681948799, self.tradeDate='20230420', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28804.9', self.close='28795.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20981 

self.closeSec=1681949399, self.tradeDate='20230420', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28795', self.close='28789.9'
127.0.0.1 - - [20/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20982 

self.closeSec=1681949999, self.tradeDate='20230420', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28789.9', self.close='28792.3'
127.0.0.1 - - [20/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20978 

self.closeSec=1681946999, self.tradeDate='20230420', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28872.4', self.close='28719'
127.0.0.1 - - [20/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20979 

self.closeSec=1681947599, self.tradeDate='20230420', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28719', self.close='28682.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20980 

self.closeSec=1681948199, self.tradeDate='20230420', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28715', self.close='28805'
127.0.0.1 - - [20/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20981 

self.closeSec=1681948799, self.tradeDate='20230420', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28804.9', self.close='28795.1'
127.0.0.1 - - [20/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20982 

self.closeSec=1681949399, self.tradeDate='20230420', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28795', self.close='28789.9'
127.0.0.1 - - [20/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20983 

self.closeSec=1681949999, self.tradeDate='20230420', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28789.9', self.close='28792.3'
127.0.0.1 - - [20/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20978 

self.closeSec=1681946999, self.tradeDate='20230420', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28872.4', self.close='28719'
127.0.0.1 - - [20/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20979 

self.closeSec=1681947599, self.tradeDate='20230420', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28719', self.close='28682.8'
127.0.0.1 - - [20/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20980 

self.closeSec=1681948199, self.tradeDate='20230420', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28715', self.close='28805'
127.0.0.1 - - [20/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20981 

self.closeSec=1681948799, self.tradeDate='20230420', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28804.9', self.close='28795.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20982 

self.closeSec=1681949399, self.tradeDate='20230420', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28795', self.close='28789.9'
127.0.0.1 - - [20/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20983 

self.closeSec=1681949999, self.tradeDate='20230420', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28789.9', self.close='28792.3'
127.0.0.1 - - [20/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [20/Apr/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37395
self.closeSec=1681949999, self.tradeDate='20230420', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28713.8, self.close=28792.3, self.high=28795.3, self.low=28704.2, self.vol=2111.563, self.amt=60708570.843 
2023-04-20 08:20:01,975:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230420   075500    075959  ...         0.0        0.0       0
5849  20230420   080000    080459  ...         0.0        0.0       0
5850  20230420   080500    080959  ...         0.0        0.0       0
5851  20230420   081000    081459  ...         0.0        0.0       0
5852  20230420   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 08:20:02,005:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681949999, self.tradeDate='20230420', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28713.8, self.close=28792.3, self.high=28795.3, self.low=28704.2, self.vol=2111.563, self.amt=60708570.843, ukdf['pct'].iloc[-1]=0.002734 , ukdf['amount'].iloc[-1]=60708570.843, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37396
self.closeSec=1681950299, self.tradeDate='20230420', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28792.3, self.close=28832.1, self.high=28877.0, self.low=28792.3, self.vol=2701.693, self.amt=77900769.6593 
127.0.0.1 - - [20/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-20 08:25:01,678:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230420   080000    080459  ...         0.0        0.0       0
5850  20230420   080500    080959  ...         0.0        0.0       0
5851  20230420   081000    081459  ...         0.0        0.0       0
5852  20230420   081500    081959  ...         0.0        0.0       0
5853  20230420   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-20 08:25:01,678:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681950299, self.tradeDate='20230420', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28792.3, self.close=28832.1, self.high=28877.0, self.low=28792.3, self.vol=2701.693, self.amt=77900769.6593, ukdf['pct'].iloc[-1]=0.001382 , ukdf['amount'].iloc[-1]=77900769.6593, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230419   200000    235959  1681919999  ...    719  0.310800 -0.475507     NaN
720  20230420   000000    035959  1681934399  ...    720  0.359029 -0.370344     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '48812.6925', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29199.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=874
self.closeSec=1681948799, self.tradeDate='20230420', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29210.5, self.close=28795.1, self.high=29309.7, self.low=28557.3, self.vol=159240.579, self.amt=4607686531.00936 
127.0.0.1 - - [20/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-20 08:00:01,909:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681948799, self.tradeDate='20230420', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29210.5, self.close=28795.1, self.high=29309.7, self.low=28557.3, self.vol=159240.579, self.amt=4607686531.00936 
2023-04-20 08:00:01,986:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230419   120000    155959  ...   57670.911  1.737069e+09 -0.004474
718  20230419   160000    195959  ...  224711.270  6.583421e+09 -0.025438
719  20230419   200000    235959  ...   98329.802  2.880595e+09 -0.001778
720  20230420   000000    035959  ...   61620.315  1.802690e+09 -0.001275
721  20230420   040000    075959  ...  159240.579  4.607687e+09 -0.014224

[5 rows x 11 columns]
2023-04-20 08:00:03,775:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230419   120000    155959  1681891199  ...    717  0.515285 -0.009071     NaN
718  20230419   160000    195959  1681905599  ...    718  0.272167 -0.558491     NaN
719  20230419   200000    235959  1681919999  ...    719  0.310800 -0.475507     NaN
720  20230420   000000    035959  1681934399  ...    720  0.359029 -0.370344     NaN
721  20230420   040000    075959  1681948799  ...    721  0.375786 -0.336869     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '27355.57427086785', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28790.80972619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


