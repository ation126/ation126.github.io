# 20230414 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39669
self.closeSec=1681431599, self.tradeDate='20230414', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30347.2, self.close=30335.9, self.high=30371.3, self.low=30334.3, self.vol=652.612, self.amt=19809490.6705 
127.0.0.1 - - [14/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-14 08:20:07,403:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230414   075500    075959  ...         0.0        0.0       0
5849  20230414   080000    080459  ...         0.0        0.0       0
5850  20230414   080500    080959  ...         0.0        0.0       0
5851  20230414   081000    081459  ...         0.0        0.0       0
5852  20230414   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 08:20:07,412:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681431599, self.tradeDate='20230414', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30347.2, self.close=30335.9, self.high=30371.3, self.low=30334.3, self.vol=652.612, self.amt=19809490.6705, ukdf['pct'].iloc[-1]=-0.000369 , ukdf['amount'].iloc[-1]=19809490.6705, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-830733.12292711504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30334.35721429', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39670
self.closeSec=1681431899, self.tradeDate='20230414', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30335.9, self.close=30383.1, self.high=30390.0, self.low=30293.0, self.vol=1697.753, self.amt=51520080.0643 
2023-04-14 08:25:01,579:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230414   080000    080459  ...         0.0        0.0       0
5850  20230414   080500    080959  ...         0.0        0.0       0
5851  20230414   081000    081459  ...         0.0        0.0       0
5852  20230414   081500    081959  ...         0.0        0.0       0
5853  20230414   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 08:25:01,583:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681431899, self.tradeDate='20230414', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30335.9, self.close=30383.1, self.high=30390.0, self.low=30293.0, self.vol=1697.753, self.amt=51520080.0643, ukdf['pct'].iloc[-1]=0.001556 , ukdf['amount'].iloc[-1]=51520080.0643, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-833840.7792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30386', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [14/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40231 

self.closeSec=1681430399, self.tradeDate='20230414', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30342.5, self.close=30362.7, self.high=30380.0, self.low=30342.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40232 

self.closeSec=1681430699, self.tradeDate='20230414', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=30362.7, self.close=30353.0, self.high=30370.3, self.low=30353.0 
127.0.0.1 - - [14/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40233 

self.closeSec=1681430999, self.tradeDate='20230414', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=30353.0, self.close=30336.0, self.high=30354.0, self.low=30336.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40234 

self.closeSec=1681431299, self.tradeDate='20230414', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=30336.0, self.close=30347.1, self.high=30350.1, self.low=30334.1 
127.0.0.1 - - [14/Apr/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40235 

self.closeSec=1681431599, self.tradeDate='20230414', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30347.2, self.close=30335.9, self.high=30371.3, self.low=30334.3 
127.0.0.1 - - [14/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40236 

self.closeSec=1681431899, self.tradeDate='20230414', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30335.9, self.close=30383.1, self.high=30390.0, self.low=30293.0 


## /root/FIL/strategy/logic/log.txt ----- -----

5770  20230414    055959  30262.2  ...  54.583333  0.546907  0.395573
5771  20230414    062959  30265.0  ...  54.583333  0.559251  0.400770
5772  20230414    065959  30332.1  ...  54.583333  0.549157  0.410057
5773  20230414    072959  30287.8  ...  54.583333  0.549213  0.418695

[5 rows x 33 columns]
0.5777777777777777
acc is : 0.5777777777777777
2023-04-14 08:00:36,932:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.502723  0.497277       1  ...  0.997899   1.0    0.0  1.077238
536     0  0.502864  0.497136       1  ...  1.000118   1.0    0.0  1.079634
537     0  0.521150  0.478850       0  ...  0.998651   1.0    0.0  1.078050
538     0  0.500559  0.499441       1  ...  0.998661   1.0    0.0  1.078060
539     0  0.510292  0.489708       1  ...  1.001124   1.0    0.0  1.080719

[5 rows x 10 columns]
2023-04-14 08:00:36,973:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502550  0.497450       1  ...  1.010286  -1.0    0.0  1.077468
46     0  0.501793  0.498207       1  ...  1.008040  -1.0    0.0  1.079046
47     0  0.521021  0.478979       0  ...  0.998651   1.0    0.0  1.082690
48     1  0.499930  0.500070       1  ...  1.009508  -1.0    0.0  1.077416
49     0  0.510292  0.489708       1  ...  1.001124   1.0    0.0  1.080719

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-04-14 08:00:37,212:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '25.191', 'buy' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:765000.288', 'result': 'success', 'clientorderid': ''}
2023-04-14 08:00:37,230:INFO:logic:main.py:494:insertFactor:885513: curDateTime:4140800, name:logic, symbol:BTCUSDT, tradeDate:20230414, closeTime:075959, close:30362.7, sign:1, total:767183.2585902, side:buy  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [14/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20113 

self.closeSec=1681428599, self.tradeDate='20230414', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30289.2', self.close='30288'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20114 

self.closeSec=1681429199, self.tradeDate='20230414', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30287.9', self.close='30302.7'
127.0.0.1 - - [14/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20115 

self.closeSec=1681429799, self.tradeDate='20230414', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30302.6', self.close='30330.1'
127.0.0.1 - - [14/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20116 

self.closeSec=1681430399, self.tradeDate='20230414', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30330.1', self.close='30362.7'
127.0.0.1 - - [14/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20117 

self.closeSec=1681430999, self.tradeDate='20230414', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30362.7', self.close='30336'
127.0.0.1 - - [14/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20118 

self.closeSec=1681431599, self.tradeDate='20230414', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30336', self.close='30335.9'
127.0.0.1 - - [14/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20114 

self.closeSec=1681428599, self.tradeDate='20230414', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30289.2', self.close='30288'
127.0.0.1 - - [14/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20115 

self.closeSec=1681429199, self.tradeDate='20230414', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30287.9', self.close='30302.7'
127.0.0.1 - - [14/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20116 

self.closeSec=1681429799, self.tradeDate='20230414', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30302.6', self.close='30330.1'
127.0.0.1 - - [14/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20117 

self.closeSec=1681430399, self.tradeDate='20230414', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30330.1', self.close='30362.7'
127.0.0.1 - - [14/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20118 

self.closeSec=1681430999, self.tradeDate='20230414', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30362.7', self.close='30336'
127.0.0.1 - - [14/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20119 

self.closeSec=1681431599, self.tradeDate='20230414', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30336', self.close='30335.9'
127.0.0.1 - - [14/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20114 

self.closeSec=1681428599, self.tradeDate='20230414', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30289.2', self.close='30288'
127.0.0.1 - - [14/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20115 

self.closeSec=1681429199, self.tradeDate='20230414', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30287.9', self.close='30302.7'
127.0.0.1 - - [14/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20116 

self.closeSec=1681429799, self.tradeDate='20230414', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30302.6', self.close='30330.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20117 

self.closeSec=1681430399, self.tradeDate='20230414', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30330.1', self.close='30362.7'
127.0.0.1 - - [14/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20118 

self.closeSec=1681430999, self.tradeDate='20230414', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30362.7', self.close='30336'
127.0.0.1 - - [14/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20119 

self.closeSec=1681431599, self.tradeDate='20230414', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30336', self.close='30335.9'
127.0.0.1 - - [14/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35667
self.closeSec=1681431599, self.tradeDate='20230414', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30347.2, self.close=30335.9, self.high=30371.3, self.low=30334.3, self.vol=652.612, self.amt=19809490.6705 
127.0.0.1 - - [14/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-14 08:20:07,106:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230414   075500    075959  ...         0.0        0.0       0
5849  20230414   080000    080459  ...         0.0        0.0       0
5850  20230414   080500    080959  ...         0.0        0.0       0
5851  20230414   081000    081459  ...         0.0        0.0       0
5852  20230414   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 08:20:07,120:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681431599, self.tradeDate='20230414', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30347.2, self.close=30335.9, self.high=30371.3, self.low=30334.3, self.vol=652.612, self.amt=19809490.6705, ukdf['pct'].iloc[-1]=-0.000369 , ukdf['amount'].iloc[-1]=19809490.6705, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35668
self.closeSec=1681431899, self.tradeDate='20230414', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30335.9, self.close=30383.1, self.high=30390.0, self.low=30293.0, self.vol=1697.753, self.amt=51520080.0643 
127.0.0.1 - - [14/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-14 08:25:01,591:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230414   080000    080459  ...         0.0        0.0       0
5850  20230414   080500    080959  ...         0.0        0.0       0
5851  20230414   081000    081459  ...         0.0        0.0       0
5852  20230414   081500    081959  ...         0.0        0.0       0
5853  20230414   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-14 08:25:01,591:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681431899, self.tradeDate='20230414', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30335.9, self.close=30383.1, self.high=30390.0, self.low=30293.0, self.vol=1697.753, self.amt=51520080.0643, ukdf['pct'].iloc[-1]=0.001556 , ukdf['amount'].iloc[-1]=51520080.0643, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230413   200000    235959  1681401599  ...    719  0.949147  0.982769     1.0
720  20230414   000000    035959  1681415999  ...    720  0.887913  0.834126     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '107685.46698181605', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30320.46587607', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=838
self.closeSec=1681430399, self.tradeDate='20230414', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30323.0, self.close=30362.7, self.high=30385.2, self.low=30185.0, self.vol=39042.382, self.amt=1182255820.14909 
127.0.0.1 - - [14/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-14 08:00:01,801:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681430399, self.tradeDate='20230414', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30323.0, self.close=30362.7, self.high=30385.2, self.low=30185.0, self.vol=39042.382, self.amt=1182255820.14909 
2023-04-14 08:00:01,842:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230413   120000    155959  ...   28859.962  8.672803e+08 -0.000077
718  20230413   160000    195959  ...   92038.937  2.779242e+09  0.003134
719  20230413   200000    235959  ...  147335.344  4.469851e+09  0.009065
720  20230414   000000    035959  ...   76467.563  2.322848e+09 -0.003267
721  20230414   040000    075959  ...   39042.382  1.182256e+09  0.001306

[5 rows x 11 columns]
2023-04-14 08:00:04,265:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230413   120000    155959  1681372799  ...    717  1.003784  1.144108     1.0
718  20230413   160000    195959  1681387199  ...    718  0.976496  1.061582     1.0
719  20230413   200000    235959  1681401599  ...    719  0.949147  0.982769     1.0
720  20230414   000000    035959  1681415999  ...    720  0.887913  0.834126     1.0
721  20230414   040000    075959  1681430399  ...    721  0.853519  0.747101     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '109903.392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30362.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


