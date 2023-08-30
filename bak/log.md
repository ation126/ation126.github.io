# 20230830 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31060
self.closeSec=1693354799, self.tradeDate='20230830', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27687.5, self.close=27700.3, self.high=27700.3, self.low=27677.8, self.vol=524.115, self.amt=14511727.1637 
127.0.0.1 - - [30/Aug/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-08-30 08:20:05,458:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230830   075500    075959  ...         0.0        0.0       0
5844  20230830   080000    080459  ...         0.0        0.0       0
5845  20230830   080500    080959  ...         0.0        0.0       0
5846  20230830   081000    081459  ...         0.0        0.0       0
5847  20230830   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 08:20:05,465:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693354799, self.tradeDate='20230830', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27687.5, self.close=27700.3, self.high=27700.3, self.low=27677.8, self.vol=524.115, self.amt=14511727.1637, ukdf['pct'].iloc[-1]=0.000462 , ukdf['amount'].iloc[-1]=14511727.1637, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11625.4248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27699.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31061
self.closeSec=1693355099, self.tradeDate='20230830', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27700.3, self.close=27689.1, self.high=27758.2, self.low=27688.3, self.vol=1986.449, self.amt=55072580.2443 
2023-08-30 08:25:00,802:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230830   080000    080459  ...         0.0        0.0       0
5845  20230830   080500    080959  ...         0.0        0.0       0
5846  20230830   081000    081459  ...         0.0        0.0       0
5847  20230830   081500    081959  ...         0.0        0.0       0
5848  20230830   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 08:25:00,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693355099, self.tradeDate='20230830', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27700.3, self.close=27689.1, self.high=27758.2, self.low=27688.3, self.vol=1986.449, self.amt=55072580.2443, ukdf['pct'].iloc[-1]=-0.000404 , ukdf['amount'].iloc[-1]=55072580.2443, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11549.8795539435', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27694.27523725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31058 

self.closeSec=1693353599, self.tradeDate='20230830', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27705.1, self.close=27701.1, self.high=27720.0, self.low=27695.6 
127.0.0.1 - - [30/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31059 

self.closeSec=1693353899, self.tradeDate='20230830', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27700.1, self.close=27712.7, self.high=27726.9, self.low=27694.5 
127.0.0.1 - - [30/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31060 

self.closeSec=1693354199, self.tradeDate='20230830', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27712.7, self.close=27690.4, self.high=27735.5, self.low=27683.2 

--handleKline--: 127.0.0.1 - - [30/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31061 

self.closeSec=1693354499, self.tradeDate='20230830', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27690.3, self.close=27687.5, self.high=27700.0, self.low=27680.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31062 

self.closeSec=1693354799, self.tradeDate='20230830', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27687.5, self.close=27700.3, self.high=27700.3, self.low=27677.8 
127.0.0.1 - - [30/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31063 

self.closeSec=1693355099, self.tradeDate='20230830', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27700.3, self.close=27689.1, self.high=27758.2, self.low=27688.3 
127.0.0.1 - - [30/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-30 08:00:17,622:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230830    052959  27560.1  ...  51.250000  0.687120  0.319338
5770  20230830    055959  27673.8  ...  50.833333  0.682321  0.313271
5771  20230830    062959  27651.4  ...  50.416667  0.661536  0.310532
5772  20230830    065959  27552.1  ...  50.833333  0.669064  0.305837
5773  20230830    072959  27624.8  ...  50.833333  0.665113  0.302014

[5 rows x 33 columns]
0.5555555555555556
acc is : 0.5555555555555556
2023-08-30 08:00:17,688:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.508193  0.491807       0  ...  0.941830  -1.0    0.0  1.063585
536     1  0.475165  0.524835       0  ...  0.945209  -1.0    0.0  1.059770
537     1  0.452048  0.547952       1  ...  0.942718  -1.0    0.0  1.062562
538     1  0.499209  0.500791       0  ...  0.943367  -1.0    0.0  1.061831
539     1  0.493578  0.506422       1  ...  0.940141  -1.0    0.0  1.065462

[5 rows x 10 columns]
2023-08-30 08:00:17,700:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507903  0.492097       0  ...  0.931684  -1.0    0.0  1.063794
46     1  0.474566  0.525434       0  ...  0.931313  -1.0    0.0  1.060108
47     1  0.451411  0.548589       1  ...  0.941192  -1.0    0.0  1.067023
48     1  0.498639  0.501361       0  ...  0.943367  -1.0    0.0  1.065623
49     1  0.493578  0.506422       1  ...  0.940141  -1.0    0.0  1.065462

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.499', 'enterprice': '27668.5', 'countrevence': '0', 'unrealprofit': '-1101.89553662069', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27711.71328431', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [30/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15527 

self.closeSec=1693351799, self.tradeDate='20230830', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27589.8', self.close='27605.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15528 

self.closeSec=1693352399, self.tradeDate='20230830', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27605.8', self.close='27639.7'
127.0.0.1 - - [30/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15529 

self.closeSec=1693352999, self.tradeDate='20230830', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27639.8', self.close='27686.4'
127.0.0.1 - - [30/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15530 

self.closeSec=1693353599, self.tradeDate='20230830', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27686.4', self.close='27700.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15531 

self.closeSec=1693354199, self.tradeDate='20230830', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27700.1', self.close='27690.4'
127.0.0.1 - - [30/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15532 

self.closeSec=1693354799, self.tradeDate='20230830', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27690.3', self.close='27700.3'
127.0.0.1 - - [30/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [30/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15530 

self.closeSec=1693351799, self.tradeDate='20230830', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27589.8', self.close='27605.7'
127.0.0.1 - - [30/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15531 

self.closeSec=1693352399, self.tradeDate='20230830', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27605.8', self.close='27639.7'
127.0.0.1 - - [30/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15532 

self.closeSec=1693352999, self.tradeDate='20230830', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27639.8', self.close='27686.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15533 

self.closeSec=1693353599, self.tradeDate='20230830', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27686.4', self.close='27700.1'
127.0.0.1 - - [30/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15534 

self.closeSec=1693354199, self.tradeDate='20230830', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27700.1', self.close='27690.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15535 

self.closeSec=1693354799, self.tradeDate='20230830', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27690.3', self.close='27700.3'
127.0.0.1 - - [30/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [30/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15530 

self.closeSec=1693351799, self.tradeDate='20230830', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27589.8', self.close='27605.7'
127.0.0.1 - - [30/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15531 

self.closeSec=1693352399, self.tradeDate='20230830', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27605.8', self.close='27639.7'
127.0.0.1 - - [30/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15532 

self.closeSec=1693352999, self.tradeDate='20230830', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27639.8', self.close='27686.4'
127.0.0.1 - - [30/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15533 

self.closeSec=1693353599, self.tradeDate='20230830', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27686.4', self.close='27700.1'
127.0.0.1 - - [30/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15534 

self.closeSec=1693354199, self.tradeDate='20230830', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27700.1', self.close='27690.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15535 

self.closeSec=1693354799, self.tradeDate='20230830', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27690.3', self.close='27700.3'
127.0.0.1 - - [30/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31060
self.closeSec=1693354799, self.tradeDate='20230830', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27687.5, self.close=27700.3, self.high=27700.3, self.low=27677.8, self.vol=524.115, self.amt=14511727.1637 
127.0.0.1 - - [30/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-30 08:20:05,458:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230830   075500    075959  ...         0.0        0.0       0
5844  20230830   080000    080459  ...         0.0        0.0       0
5845  20230830   080500    080959  ...         0.0        0.0       0
5846  20230830   081000    081459  ...         0.0        0.0       0
5847  20230830   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 08:20:05,465:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693354799, self.tradeDate='20230830', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27687.5, self.close=27700.3, self.high=27700.3, self.low=27677.8, self.vol=524.115, self.amt=14511727.1637, ukdf['pct'].iloc[-1]=0.000462 , ukdf['amount'].iloc[-1]=14511727.1637, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '31781.5537', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27699.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [30/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31061
self.closeSec=1693355099, self.tradeDate='20230830', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27700.3, self.close=27689.1, self.high=27758.2, self.low=27688.3, self.vol=1986.449, self.amt=55072580.2443 
2023-08-30 08:25:00,813:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230830   080000    080459  ...         0.0        0.0       0
5845  20230830   080500    080959  ...         0.0        0.0       0
5846  20230830   081000    081459  ...         0.0        0.0       0
5847  20230830   081500    081959  ...         0.0        0.0       0
5848  20230830   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 08:25:00,814:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693355099, self.tradeDate='20230830', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27700.3, self.close=27689.1, self.high=27758.2, self.low=27688.3, self.vol=1986.449, self.amt=55072580.2443, ukdf['pct'].iloc[-1]=-0.000404 , ukdf['amount'].iloc[-1]=55072580.2443, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '31580.07258670225', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27694.27523725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

127.0.0.1 - - [30/Aug/2023 04:00:10] "POST / HTTP/1.1" 200 -
2023-08-30 04:00:10,372:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42925F1693339204777I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1693339205178282, 'quantity': '51.388', 'price': '27831.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1693339203862, 'updatetime': 1693339205178, 'tradetype': 'usdt', 'selfid': 42925, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1693339205178, 'clientorderid': '42925F1693339204777I0L65', 'price': '27831.8', 'quantity': '51.388', 'commission': '1430.2205384', 'commissionasset': 'USDT', 'tradetime': 1693339205178, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1693339205178}], 'gatetype': 'simulator', 'handletime': 0}
2023-08-30 04:00:10,831:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42926F1693339210344I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1693339210787649, 'quantity': '57.252', 'price': '27833.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1693339209871, 'updatetime': 1693339210787, 'tradetype': 'usdt', 'selfid': 42926, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1693339210787, 'clientorderid': '42926F1693339210344I0L65', 'price': '27833.8', 'quantity': '57.252', 'commission': '1593.5407176', 'commissionasset': 'USDT', 'tradetime': 1693339210787, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1693339210787}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Aug/2023 04:00:10] "POST / HTTP/1.1" 200 -
2023-08-30 04:00:11,014:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42926F1693339210344I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1693339210787649, 'quantity': '57.252', 'price': '27833.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1693339209871, 'updatetime': 1693339210787, 'tradetype': 'usdt', 'selfid': 42926, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1693339210787, 'clientorderid': '42926F1693339210344I0L65', 'price': '27833.8', 'quantity': '57.252', 'commission': '1593.5407176', 'commissionasset': 'USDT', 'tradetime': 1693339210787, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1693339210787}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Aug/2023 04:00:11] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=647
self.closeSec=1693353599, self.tradeDate='20230830', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27820.0, self.close=27700.1, self.high=27875.0, self.low=27517.5, self.vol=60294.869, self.amt=1667632270.22422 
127.0.0.1 - - [30/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-30 08:00:01,587:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693353599, self.tradeDate='20230830', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27820.0, self.close=27700.1, self.high=27875.0, self.low=27517.5, self.vol=60294.869, self.amt=1667632270.22422 
2023-08-30 08:00:01,603:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230829   120000    155959  ...   20248.279  5.270296e+08 -0.002927
718  20230829   160000    195959  ...   33052.011  8.583218e+08 -0.001093
719  20230829   200000    235959  ...  362946.286  9.819943e+09  0.055759
720  20230830   000000    035959  ...  200945.529  5.596983e+09  0.014910
721  20230830   040000    075959  ...   60294.869  1.667632e+09 -0.004310

[5 rows x 11 columns]
2023-08-30 08:00:02,377:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime  ...          beta    zscore  signal
717  20230829   120000    155959  ...  5.307007e-06 -1.103177    -1.0
718  20230829   160000    195959  ...  1.459807e-07 -1.102574    -1.0
719  20230829   200000    235959  ...  2.902323e-06 -1.102490    -1.0
720  20230830   000000    035959  ...  1.145245e+00  4.487494     1.0
721  20230830   040000    075959  ...  1.062729e+00  3.723992     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-7573.0884528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27701.5236', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


