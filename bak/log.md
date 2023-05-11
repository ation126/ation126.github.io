# 20230511 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47445
self.closeSec=1683764399, self.tradeDate='20230511', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27582.7, self.close=27566.9, self.high=27611.5, self.low=27550.0, self.vol=1809.324, self.amt=49894784.309 
127.0.0.1 - - [11/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-11 08:20:06,235:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230511   075500    075959  ...         0.0        0.0       0
5856  20230511   080000    080459  ...         0.0        0.0       0
5857  20230511   080500    080959  ...         0.0        0.0       0
5858  20230511   081000    081459  ...         0.0        0.0       0
5859  20230511   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 08:20:06,240:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683764399, self.tradeDate='20230511', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27582.7, self.close=27566.9, self.high=27611.5, self.low=27550.0, self.vol=1809.324, self.amt=49894784.309, ukdf['pct'].iloc[-1]=-0.000573 , ukdf['amount'].iloc[-1]=49894784.309, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-664355.0752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27569.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47446
self.closeSec=1683764699, self.tradeDate='20230511', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27566.9, self.close=27535.6, self.high=27569.7, self.low=27492.8, self.vol=2682.642, self.amt=73833184.2666 
2023-05-11 08:25:02,232:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230511   080000    080459  ...         0.0        0.0       0
5857  20230511   080500    080959  ...         0.0        0.0       0
5858  20230511   081000    081459  ...         0.0        0.0       0
5859  20230511   081500    081959  ...         0.0        0.0       0
5860  20230511   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 08:25:02,233:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683764699, self.tradeDate='20230511', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27566.9, self.close=27535.6, self.high=27569.7, self.low=27492.8, self.vol=2682.642, self.amt=73833184.2666, ukdf['pct'].iloc[-1]=-0.001135 , ukdf['amount'].iloc[-1]=73833184.2666, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-662445.81737062192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27537.77210467', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48007 

self.closeSec=1683763199, self.tradeDate='20230511', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27613.2, self.close=27582.9, self.high=27617.6, self.low=27566.0 
127.0.0.1 - - [11/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48008 

self.closeSec=1683763499, self.tradeDate='20230511', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27583.0, self.close=27576.2, self.high=27595.4, self.low=27561.1 
127.0.0.1 - - [11/May/2023 08:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48009 

self.closeSec=1683763799, self.tradeDate='20230511', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27576.1, self.close=27575.0, self.high=27592.7, self.low=27566.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48010 

self.closeSec=1683764099, self.tradeDate='20230511', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27575.1, self.close=27582.7, self.high=27592.0, self.low=27564.8 
127.0.0.1 - - [11/May/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48011 

self.closeSec=1683764399, self.tradeDate='20230511', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27582.7, self.close=27566.9, self.high=27611.5, self.low=27550.0 
127.0.0.1 - - [11/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 08:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48012 

self.closeSec=1683764699, self.tradeDate='20230511', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27566.9, self.close=27535.6, self.high=27569.7, self.low=27492.8 


## /root/FIL/strategy/logic/log.txt ----- -----

5770  20230511    055959  27527.3  ...    48.75  0.467830  0.378533
5771  20230511    062959  27497.4  ...    48.75  0.470885  0.384979
5772  20230511    065959  27522.3  ...    48.75  0.487095  0.385544
5773  20230511    072959  27655.5  ...    48.75  0.481015  0.388276

[5 rows x 33 columns]
0.5388888888888889
acc is : 0.5388888888888889
2023-05-11 08:00:22,805:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.450113  0.549887       0  ...  0.954546   1.0    0.0  0.943553
536     1  0.475258  0.524742       1  ...  0.955403   1.0    0.0  0.944401
537     1  0.486000  0.514000       1  ...  0.960031   1.0    0.0  0.948975
538     0  0.504348  0.495652       0  ...  0.958160   1.0    0.0  0.947125
539     1  0.467339  0.532661       0  ...  0.957511   1.0    0.0  0.946484

[5 rows x 10 columns]
2023-05-11 08:00:22,820:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.449475  0.550525       0  ...  0.955086  -1.0 -0.0016  0.939825
46     1  0.474982  0.525018       1  ...  0.954228  -1.0  0.0000  0.940737
47     1  0.485514  0.514486       1  ...  0.949606  -1.0  0.0000  0.944993
48     0  0.504129  0.495871       0  ...  0.951457  -1.0  0.0000  0.944468
49     1  0.467339  0.532661       0  ...  0.957511   1.0  0.0000  0.946484

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-05-11 08:00:23,401:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '27.730', 'buy' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:764987.5382000235', 'result': 'success', 'clientorderid': ''}
2023-05-11 08:00:23,419:INFO:logic:main.py:494:insertFactor:885513: curDateTime:5110800, name:logic, symbol:BTCUSDT, tradeDate:20230511, closeTime:075959, close:27582.9, sign:1, total:767183.2585902, side:buy  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24001 

self.closeSec=1683761399, self.tradeDate='20230511', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27629.8', self.close='27601.6'
127.0.0.1 - - [11/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24002 

self.closeSec=1683761999, self.tradeDate='20230511', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27601.6', self.close='27613.4'
127.0.0.1 - - [11/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24003 

self.closeSec=1683762599, self.tradeDate='20230511', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27613.4', self.close='27583.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24004 

self.closeSec=1683763199, self.tradeDate='20230511', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27583.3', self.close='27582.9'
127.0.0.1 - - [11/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24005 

self.closeSec=1683763799, self.tradeDate='20230511', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27583', self.close='27575'
127.0.0.1 - - [11/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24006 

self.closeSec=1683764399, self.tradeDate='20230511', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27575.1', self.close='27566.9'
127.0.0.1 - - [11/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [11/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24002 

self.closeSec=1683761399, self.tradeDate='20230511', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27629.8', self.close='27601.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24003 

self.closeSec=1683761999, self.tradeDate='20230511', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27601.6', self.close='27613.4'
127.0.0.1 - - [11/May/2023 07:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24004 

self.closeSec=1683762599, self.tradeDate='20230511', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27613.4', self.close='27583.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24005 

self.closeSec=1683763199, self.tradeDate='20230511', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27583.3', self.close='27582.9'
127.0.0.1 - - [11/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24006 

self.closeSec=1683763799, self.tradeDate='20230511', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27583', self.close='27575'
127.0.0.1 - - [11/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24007 

self.closeSec=1683764399, self.tradeDate='20230511', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27575.1', self.close='27566.9'
127.0.0.1 - - [11/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24002 

self.closeSec=1683761399, self.tradeDate='20230511', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27629.8', self.close='27601.6'
127.0.0.1 - - [11/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24003 

self.closeSec=1683761999, self.tradeDate='20230511', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27601.6', self.close='27613.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24004 

self.closeSec=1683762599, self.tradeDate='20230511', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27613.4', self.close='27583.3'
127.0.0.1 - - [11/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24005 

self.closeSec=1683763199, self.tradeDate='20230511', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27583.3', self.close='27582.9'
127.0.0.1 - - [11/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24006 

self.closeSec=1683763799, self.tradeDate='20230511', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27583', self.close='27575'
127.0.0.1 - - [11/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24007 

self.closeSec=1683764399, self.tradeDate='20230511', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27575.1', self.close='27566.9'
127.0.0.1 - - [11/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43443
self.closeSec=1683764399, self.tradeDate='20230511', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27582.7, self.close=27566.9, self.high=27611.5, self.low=27550.0, self.vol=1809.324, self.amt=49894784.309 
127.0.0.1 - - [11/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-11 08:20:06,232:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230511   075500    075959  ...         0.0        0.0       0
5856  20230511   080000    080459  ...         0.0        0.0       0
5857  20230511   080500    080959  ...         0.0        0.0       0
5858  20230511   081000    081459  ...         0.0        0.0       0
5859  20230511   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 08:20:06,236:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683764399, self.tradeDate='20230511', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27582.7, self.close=27566.9, self.high=27611.5, self.low=27550.0, self.vol=1809.324, self.amt=49894784.309, ukdf['pct'].iloc[-1]=-0.000573 , ukdf['amount'].iloc[-1]=49894784.309, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [11/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43444
self.closeSec=1683764699, self.tradeDate='20230511', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27566.9, self.close=27535.6, self.high=27569.7, self.low=27492.8, self.vol=2682.642, self.amt=73833184.2666 
2023-05-11 08:25:02,205:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230511   080000    080459  ...         0.0        0.0       0
5857  20230511   080500    080959  ...         0.0        0.0       0
5858  20230511   081000    081459  ...         0.0        0.0       0
5859  20230511   081500    081959  ...         0.0        0.0       0
5860  20230511   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 08:25:02,205:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683764699, self.tradeDate='20230511', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27566.9, self.close=27535.6, self.high=27569.7, self.low=27492.8, self.vol=2682.642, self.amt=73833184.2666, ukdf['pct'].iloc[-1]=-0.001135 , ukdf['amount'].iloc[-1]=73833184.2666, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230510   200000    235959  1683734399  ...    719  0.862802  1.105271     1.0
720  20230511   000000    035959  1683748799  ...    720  0.488827 -0.165419     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '3293.51387310268', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27672.83240268', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1448108.3022399, self.flagDict['side']='buy', self.tradeCount=34, self.count=1000
self.closeSec=1683763199, self.tradeDate='20230511', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27683.6, self.close=27582.9, self.high=27979.8, self.low=27177.0, self.vol=99430.444, self.amt=2747765930.3402 
127.0.0.1 - - [11/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
2023-05-11 08:00:03,363:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683763199, self.tradeDate='20230511', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27683.6, self.close=27582.9, self.high=27979.8, self.low=27177.0, self.vol=99430.444, self.amt=2747765930.3402 
2023-05-11 08:00:03,385:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230510   120000    155959  ...   32310.414  8.918974e+08 -0.004930
718  20230510   160000    195959  ...   39879.662  1.099456e+09  0.004660
719  20230510   200000    235959  ...  213950.080  6.001232e+09  0.017371
720  20230511   000000    035959  ...  289613.920  7.950327e+09 -0.016261
721  20230511   040000    075959  ...   99430.444  2.747766e+09 -0.003638

[5 rows x 11 columns]
2023-05-11 08:00:04,701:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230510   120000    155959  1683705599  ...    717  0.834112  1.055339     1.0
718  20230510   160000    195959  1683719999  ...    718  0.874225  1.167903     1.0
719  20230510   200000    235959  1683734399  ...    719  0.862802  1.105271     1.0
720  20230511   000000    035959  1683748799  ...    720  0.488827 -0.165419     NaN
721  20230511   040000    075959  1683763199  ...    721  0.442410 -0.312865     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '-1293.77868160907', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27585.45706593', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


