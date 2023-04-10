# 20230410 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38613
self.closeSec=1681114799, self.tradeDate='20230410', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28329.9, self.close=28309.0, self.high=28336.4, self.low=28309.0, self.vol=1074.249, self.amt=30427965.8758 
127.0.0.1 - - [10/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-10 16:20:06,457:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230410   155500    155959  ...         0.0        0.0       0
5945  20230410   160000    160459  ...         0.0        0.0       0
5946  20230410   160500    160959  ...         0.0        0.0       0
5947  20230410   161000    161459  ...         0.0        0.0       0
5948  20230410   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 16:20:06,460:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681114799, self.tradeDate='20230410', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28329.9, self.close=28309.0, self.high=28336.4, self.low=28309.0, self.vol=1074.249, self.amt=30427965.8758, ukdf['pct'].iloc[-1]=-0.000738 , ukdf['amount'].iloc[-1]=30427965.8758, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-708841.06506483776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28308.76465476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38614
self.closeSec=1681115099, self.tradeDate='20230410', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28309.0, self.close=28310.0, self.high=28315.1, self.low=28304.5, self.vol=471.384, self.amt=13344946.2424 
2023-04-10 16:25:01,660:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230410   160000    160459  ...         0.0        0.0       0
5946  20230410   160500    160959  ...         0.0        0.0       0
5947  20230410   161000    161459  ...         0.0        0.0       0
5948  20230410   161500    161959  ...         0.0        0.0       0
5949  20230410   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 16:25:01,667:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681115099, self.tradeDate='20230410', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28309.0, self.close=28310.0, self.high=28315.1, self.low=28304.5, self.vol=471.384, self.amt=13344946.2424, ukdf['pct'].iloc[-1]=3.5e-05 , ukdf['amount'].iloc[-1]=13344946.2424, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-708915.4032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28310', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [10/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39175 

self.closeSec=1681113599, self.tradeDate='20230410', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28280.0, self.close=28278.2, self.high=28296.9, self.low=28270.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39176 

self.closeSec=1681113899, self.tradeDate='20230410', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28278.3, self.close=28288.4, self.high=28290.0, self.low=28277.3 
127.0.0.1 - - [10/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39177 

self.closeSec=1681114199, self.tradeDate='20230410', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28288.3, self.close=28277.1, self.high=28288.4, self.low=28276.6 
127.0.0.1 - - [10/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39178 

self.closeSec=1681114499, self.tradeDate='20230410', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28277.1, self.close=28329.9, self.high=28349.0, self.low=28275.9 
127.0.0.1 - - [10/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39179 

self.closeSec=1681114799, self.tradeDate='20230410', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28329.9, self.close=28309.0, self.high=28336.4, self.low=28309.0 
127.0.0.1 - - [10/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39180 

self.closeSec=1681115099, self.tradeDate='20230410', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28309.0, self.close=28310.0, self.high=28315.1, self.low=28304.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-10 16:00:34,601:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230410    125959  28289.0  ...  47.083333  0.548863  0.360914
5786  20230410    132959  28228.5  ...  46.666667  0.547038  0.364531
5787  20230410    135959  28222.7  ...  47.083333  0.559661  0.363620
5788  20230410    145959  28242.8  ...  47.083333  0.553335  0.364494
5789  20230410    152959  28251.9  ...  47.500000  0.554847  0.364802

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-04-10 16:00:34,694:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.490639  0.509361       0  ...  0.933890   1.0    0.0  0.993526
538     0  0.502434  0.497566       1  ...  0.935511   1.0    0.0  0.995251
539     0  0.515144  0.484856       0  ...  0.934860   1.0    0.0  0.994558
540     0  0.502498  0.497502       1  ...  0.935051   1.0    0.0  0.994762
541     0  0.506923  0.493077       1  ...  0.935726   1.0    0.0  0.995480

[5 rows x 10 columns]
2023-04-10 16:00:34,715:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491816  0.508184       0  ...  0.933890   1.0    0.0  0.994594
46     0  0.503124  0.496876       1  ...  0.935511   1.0    0.0  0.996307
47     0  0.515067  0.484933       0  ...  0.934860   1.0    0.0  0.994376
48     0  0.502796  0.497204       1  ...  0.935051   1.0    0.0  0.997152
49     0  0.506923  0.493077       1  ...  0.935726   1.0    0.0  0.995480

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19585 

self.closeSec=1681111799, self.tradeDate='20230410', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28261.4', self.close='28257.8'
127.0.0.1 - - [10/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19586 

self.closeSec=1681112399, self.tradeDate='20230410', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28257.8', self.close='28227.2'
127.0.0.1 - - [10/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19587 

self.closeSec=1681112999, self.tradeDate='20230410', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28227.3', self.close='28263.5'
127.0.0.1 - - [10/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19588 

self.closeSec=1681113599, self.tradeDate='20230410', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28263.4', self.close='28278.2'
127.0.0.1 - - [10/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19589 

self.closeSec=1681114199, self.tradeDate='20230410', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28278.3', self.close='28277.1'
127.0.0.1 - - [10/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19590 

self.closeSec=1681114799, self.tradeDate='20230410', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28277.1', self.close='28309'
127.0.0.1 - - [10/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19586 

self.closeSec=1681111799, self.tradeDate='20230410', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28261.4', self.close='28257.8'
127.0.0.1 - - [10/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19587 

self.closeSec=1681112399, self.tradeDate='20230410', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28257.8', self.close='28227.2'
127.0.0.1 - - [10/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19588 

self.closeSec=1681112999, self.tradeDate='20230410', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28227.3', self.close='28263.5'
127.0.0.1 - - [10/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19589 

self.closeSec=1681113599, self.tradeDate='20230410', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28263.4', self.close='28278.2'
127.0.0.1 - - [10/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19590 

self.closeSec=1681114199, self.tradeDate='20230410', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28278.3', self.close='28277.1'
127.0.0.1 - - [10/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19591 

self.closeSec=1681114799, self.tradeDate='20230410', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28277.1', self.close='28309'
127.0.0.1 - - [10/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [10/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19586 

self.closeSec=1681111799, self.tradeDate='20230410', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28261.4', self.close='28257.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19587 

self.closeSec=1681112399, self.tradeDate='20230410', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28257.8', self.close='28227.2'
127.0.0.1 - - [10/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19588 

self.closeSec=1681112999, self.tradeDate='20230410', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28227.3', self.close='28263.5'
127.0.0.1 - - [10/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19589 

self.closeSec=1681113599, self.tradeDate='20230410', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28263.4', self.close='28278.2'
127.0.0.1 - - [10/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19590 

self.closeSec=1681114199, self.tradeDate='20230410', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28278.3', self.close='28277.1'
127.0.0.1 - - [10/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19591 

self.closeSec=1681114799, self.tradeDate='20230410', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28277.1', self.close='28309'
127.0.0.1 - - [10/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34611
self.closeSec=1681114799, self.tradeDate='20230410', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28329.9, self.close=28309.0, self.high=28336.4, self.low=28309.0, self.vol=1074.249, self.amt=30427965.8758 
127.0.0.1 - - [10/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-10 16:20:06,456:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230410   155500    155959  ...         0.0        0.0       0
5945  20230410   160000    160459  ...         0.0        0.0       0
5946  20230410   160500    160959  ...         0.0        0.0       0
5947  20230410   161000    161459  ...         0.0        0.0       0
5948  20230410   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 16:20:06,460:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681114799, self.tradeDate='20230410', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28329.9, self.close=28309.0, self.high=28336.4, self.low=28309.0, self.vol=1074.249, self.amt=30427965.8758, ukdf['pct'].iloc[-1]=-0.000738 , ukdf['amount'].iloc[-1]=30427965.8758, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34612
self.closeSec=1681115099, self.tradeDate='20230410', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28309.0, self.close=28310.0, self.high=28315.1, self.low=28304.5, self.vol=471.384, self.amt=13344946.2424 
127.0.0.1 - - [10/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-10 16:25:01,660:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230410   160000    160459  ...         0.0        0.0       0
5946  20230410   160500    160959  ...         0.0        0.0       0
5947  20230410   161000    161459  ...         0.0        0.0       0
5948  20230410   161500    161959  ...         0.0        0.0       0
5949  20230410   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 16:25:01,670:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681115099, self.tradeDate='20230410', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28309.0, self.close=28310.0, self.high=28315.1, self.low=28304.5, self.vol=471.384, self.amt=13344946.2424, ukdf['pct'].iloc[-1]=3.5e-05 , ukdf['amount'].iloc[-1]=13344946.2424, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-04-10 12:00:13,802:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42143F1681099208158I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1681099208524630, 'quantity': '52.088', 'price': '28269.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1681099207293, 'updatetime': 1681099208524, 'tradetype': 'usdt', 'selfid': 42143, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1681099208524, 'clientorderid': '42143F1681099208158I0L65', 'price': '28269.9', 'quantity': '52.088', 'commission': '1472.5225512', 'commissionasset': 'USDT', 'tradetime': 1681099208524, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1681099208524}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Apr/2023 12:00:13] "POST / HTTP/1.1" 200 -
2023-04-10 12:00:14,175:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42144F1681099213781I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1681099214151511, 'quantity': '52.515', 'price': '28269.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1681099213270, 'updatetime': 1681099214151, 'tradetype': 'usdt', 'selfid': 42144, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1681099214151, 'clientorderid': '42144F1681099213781I0L65', 'price': '28269.9', 'quantity': '52.515', 'commission': '1484.5937985', 'commissionasset': 'USDT', 'tradetime': 1681099214151, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1681099214151}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Apr/2023 12:00:14] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Apr/2023 12:00:14] "POST / HTTP/1.1" 200 -
2023-04-10 12:00:14,392:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42144F1681099213781I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1681099214151511, 'quantity': '52.515', 'price': '28269.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1681099213270, 'updatetime': 1681099214151, 'tradetype': 'usdt', 'selfid': 42144, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1681099214151, 'clientorderid': '42144F1681099213781I0L65', 'price': '28269.9', 'quantity': '52.515', 'commission': '1484.5937985', 'commissionasset': 'USDT', 'tradetime': 1681099214151, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1681099214151}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=816
self.closeSec=1681113599, self.tradeDate='20230410', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28269.8, self.close=28278.2, self.high=28308.0, self.low=28180.0, self.vol=32457.91, self.amt=916926200.6026 
2023-04-10 16:00:01,884:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681113599, self.tradeDate='20230410', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28269.8, self.close=28278.2, self.high=28308.0, self.low=28180.0, self.vol=32457.91, self.amt=916926200.6026 
2023-04-10 16:00:01,939:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230409   200000    235959  ...  35449.263  9.880658e+08 -0.001637
720  20230410   000000    035959  ...  69130.038  1.941111e+09  0.009285
721  20230410   040000    075959  ...  91999.792  2.607345e+09  0.006292
722  20230410   080000    115959  ...  39158.156  1.108645e+09 -0.001399
723  20230410   120000    155959  ...  32457.910  9.169262e+08  0.000297

[5 rows x 11 columns]
2023-04-10 16:00:04,481:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230409   200000    235959  1681055999  ...    719  0.009779 -1.214057    -1.0
720  20230410   000000    035959  1681070399  ...    720  0.044729 -1.044944    -1.0
721  20230410   040000    075959  1681084799  ...    721  0.359606  0.471012     NaN
722  20230410   080000    115959  1681099199  ...    722  0.436473  0.827504     1.0
723  20230410   120000    155959  1681113599  ...    723  0.421837  0.737938     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '441.126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28278.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


