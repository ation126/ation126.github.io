# 20230419 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41109
self.closeSec=1681863599, self.tradeDate='20230419', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30349.5, self.close=30369.2, self.high=30410.0, self.low=30336.3, self.vol=2576.422, self.amt=78267806.4031 
127.0.0.1 - - [19/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-19 08:20:07,816:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230419   075500    075959  ...         0.0        0.0       0
5849  20230419   080000    080459  ...         0.0        0.0       0
5850  20230419   080500    080959  ...         0.0        0.0       0
5851  20230419   081000    081459  ...         0.0        0.0       0
5852  20230419   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 08:20:07,826:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681863599, self.tradeDate='20230419', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30349.5, self.close=30369.2, self.high=30410.0, self.low=30336.3, self.vol=2576.422, self.amt=78267806.4031, ukdf['pct'].iloc[-1]=0.000652 , ukdf['amount'].iloc[-1]=78267806.4031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-833359.3712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30378', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=41110
self.closeSec=1681863899, self.tradeDate='20230419', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30369.2, self.close=30309.8, self.high=30379.5, self.low=30301.2, self.vol=1632.814, self.amt=49516292.9455 
127.0.0.1 - - [19/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-04-19 08:25:02,110:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230419   080000    080459  ...         0.0        0.0       0
5850  20230419   080500    080959  ...         0.0        0.0       0
5851  20230419   081000    081459  ...         0.0        0.0       0
5852  20230419   081500    081959  ...         0.0        0.0       0
5853  20230419   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 08:25:02,110:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681863899, self.tradeDate='20230419', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30369.2, self.close=30309.8, self.high=30379.5, self.low=30301.2, self.vol=1632.814, self.amt=49516292.9455, ukdf['pct'].iloc[-1]=-0.001956 , ukdf['amount'].iloc[-1]=49516292.9455, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-829218.3510164272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30309.1848547', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [19/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41671 

self.closeSec=1681862399, self.tradeDate='20230419', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30351.8, self.close=30365.8, self.high=30399.1, self.low=30351.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41672 

self.closeSec=1681862699, self.tradeDate='20230419', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=30365.8, self.close=30331.5, self.high=30365.9, self.low=30329.5 
127.0.0.1 - - [19/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41673 

self.closeSec=1681862999, self.tradeDate='20230419', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=30331.5, self.close=30354.2, self.high=30366.0, self.low=30324.8 
127.0.0.1 - - [19/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41674 

self.closeSec=1681863299, self.tradeDate='20230419', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=30354.3, self.close=30349.4, self.high=30354.3, self.low=30323.9 
127.0.0.1 - - [19/Apr/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41675 

self.closeSec=1681863599, self.tradeDate='20230419', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30349.5, self.close=30369.2, self.high=30410.0, self.low=30336.3 
127.0.0.1 - - [19/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=41676 

self.closeSec=1681863899, self.tradeDate='20230419', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30369.2, self.close=30309.8, self.high=30379.5, self.low=30301.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-19 08:00:35,872:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230419    052959  30416.6  ...  54.583333  0.571172  0.223145
5770  20230419    055959  30337.8  ...  54.583333  0.575258  0.215117
5771  20230419    062959  30365.1  ...  54.166667  0.567321  0.210327
5772  20230419    065959  30326.0  ...  54.583333  0.571972  0.204135
5773  20230419    072959  30357.5  ...  54.166667  0.564545  0.200637

[5 rows x 33 columns]
0.5277777777777778
acc is : 0.5277777777777778
2023-04-19 08:00:36,034:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.506976  0.493024       1  ...  1.050370   1.0    0.0  1.088074
536     0  0.526056  0.473944       0  ...  1.049021   1.0    0.0  1.086677
537     0  0.506458  0.493542       1  ...  1.050062   1.0    0.0  1.087755
538     0  0.519525  0.480475       0  ...  1.048813   1.0    0.0  1.086462
539     1  0.493045  0.506955       1  ...  1.050397   1.0    0.0  1.088103

[5 rows x 10 columns]
2023-04-19 08:00:36,058:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507772  0.492228       1  ...  1.050370   1.0    0.0  1.088546
46     0  0.525612  0.474388       0  ...  1.049021   1.0    0.0  1.085778
47     0  0.507266  0.492734       1  ...  1.050062   1.0    0.0  1.088344
48     0  0.519931  0.480069       0  ...  1.048813   1.0    0.0  1.087916
49     1  0.493045  0.506955       1  ...  1.050397   1.0    0.0  1.088103

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20833 

self.closeSec=1681860599, self.tradeDate='20230419', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30290.4', self.close='30320'
127.0.0.1 - - [19/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20834 

self.closeSec=1681861199, self.tradeDate='20230419', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30320', self.close='30334.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20835 

self.closeSec=1681861799, self.tradeDate='20230419', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30334.3', self.close='30349'
127.0.0.1 - - [19/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20836 

self.closeSec=1681862399, self.tradeDate='20230419', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30349', self.close='30365.8'
127.0.0.1 - - [19/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20837 

self.closeSec=1681862999, self.tradeDate='20230419', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30365.8', self.close='30354.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20838 

self.closeSec=1681863599, self.tradeDate='20230419', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30354.3', self.close='30369.2'
127.0.0.1 - - [19/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20834 

self.closeSec=1681860599, self.tradeDate='20230419', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30290.4', self.close='30320'
127.0.0.1 - - [19/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20835 

self.closeSec=1681861199, self.tradeDate='20230419', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30320', self.close='30334.4'
127.0.0.1 - - [19/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20836 

self.closeSec=1681861799, self.tradeDate='20230419', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30334.3', self.close='30349'
127.0.0.1 - - [19/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20837 

self.closeSec=1681862399, self.tradeDate='20230419', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30349', self.close='30365.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20838 

self.closeSec=1681862999, self.tradeDate='20230419', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30365.8', self.close='30354.2'
127.0.0.1 - - [19/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20839 

self.closeSec=1681863599, self.tradeDate='20230419', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30354.3', self.close='30369.2'
127.0.0.1 - - [19/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20834 

self.closeSec=1681860599, self.tradeDate='20230419', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30290.4', self.close='30320'
127.0.0.1 - - [19/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20835 

self.closeSec=1681861199, self.tradeDate='20230419', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30320', self.close='30334.4'
127.0.0.1 - - [19/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20836 

self.closeSec=1681861799, self.tradeDate='20230419', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30334.3', self.close='30349'
127.0.0.1 - - [19/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20837 

self.closeSec=1681862399, self.tradeDate='20230419', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30349', self.close='30365.8'
127.0.0.1 - - [19/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20838 

self.closeSec=1681862999, self.tradeDate='20230419', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30365.8', self.close='30354.2'
127.0.0.1 - - [19/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20839 

self.closeSec=1681863599, self.tradeDate='20230419', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30354.3', self.close='30369.2'
127.0.0.1 - - [19/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37107
self.closeSec=1681863599, self.tradeDate='20230419', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30349.5, self.close=30369.2, self.high=30410.0, self.low=30336.3, self.vol=2576.422, self.amt=78267806.4031 
127.0.0.1 - - [19/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-19 08:20:07,695:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230419   075500    075959  ...         0.0        0.0       0
5849  20230419   080000    080459  ...         0.0        0.0       0
5850  20230419   080500    080959  ...         0.0        0.0       0
5851  20230419   081000    081459  ...         0.0        0.0       0
5852  20230419   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 08:20:07,707:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681863599, self.tradeDate='20230419', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30349.5, self.close=30369.2, self.high=30410.0, self.low=30336.3, self.vol=2576.422, self.amt=78267806.4031, ukdf['pct'].iloc[-1]=0.000652 , ukdf['amount'].iloc[-1]=78267806.4031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=37108
self.closeSec=1681863899, self.tradeDate='20230419', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30369.2, self.close=30309.8, self.high=30379.5, self.low=30301.2, self.vol=1632.814, self.amt=49516292.9455 
2023-04-19 08:25:02,108:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230419   080000    080459  ...         0.0        0.0       0
5850  20230419   080500    080959  ...         0.0        0.0       0
5851  20230419   081000    081459  ...         0.0        0.0       0
5852  20230419   081500    081959  ...         0.0        0.0       0
5853  20230419   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-19 08:25:02,108:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681863899, self.tradeDate='20230419', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30369.2, self.close=30309.8, self.high=30379.5, self.low=30301.2, self.vol=1632.814, self.amt=49516292.9455, ukdf['pct'].iloc[-1]=-0.001956 , ukdf['amount'].iloc[-1]=49516292.9455, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230418   200000    235959  1681833599  ...    719  0.515898  0.025734     NaN
720  20230419   000000    035959  1681847999  ...    720  0.524155  0.036081     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '101810.11363926615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30208.58634941', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=868
self.closeSec=1681862399, self.tradeDate='20230419', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30205.8, self.close=30365.8, self.high=30450.0, self.low=30132.9, self.vol=54391.463, self.amt=1649457020.19826 
2023-04-19 08:00:01,952:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681862399, self.tradeDate='20230419', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30205.8, self.close=30365.8, self.high=30450.0, self.low=30132.9, self.vol=54391.463, self.amt=1649457020.19826 
127.0.0.1 - - [19/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-19 08:00:02,013:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230418   120000    155959  ...   59863.929  1.773492e+09  0.011049
718  20230418   160000    195959  ...  120369.504  3.613284e+09  0.020594
719  20230418   200000    235959  ...  143790.876  4.354220e+09 -0.006569
720  20230419   000000    035959  ...   89098.270  2.684624e+09  0.001180
721  20230419   040000    075959  ...   54391.463  1.649457e+09  0.005297

[5 rows x 11 columns]
2023-04-19 08:00:04,700:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230418   120000    155959  1681804799  ...    717  0.633434  0.301390     NaN
718  20230418   160000    195959  1681819199  ...    718  0.524906  0.053565     NaN
719  20230418   200000    235959  1681833599  ...    719  0.515898  0.025734     NaN
720  20230419   000000    035959  1681847999  ...    720  0.524155  0.036081     NaN
721  20230419   040000    075959  1681862399  ...    721  0.532673  0.046307     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '110139.06159041085', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30367.18766239', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


