# 20230828 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30484
self.closeSec=1693181999, self.tradeDate='20230828', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26081.7, self.close=26076.7, self.high=26092.1, self.low=26076.7, self.vol=307.956, self.amt=8033452.151 
127.0.0.1 - - [28/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-28 08:20:04,717:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230828   075500    075959  ...         0.0        0.0       0
5844  20230828   080000    080459  ...         0.0        0.0       0
5845  20230828   080500    080959  ...         0.0        0.0       0
5846  20230828   081000    081459  ...         0.0        0.0       0
5847  20230828   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 08:20:04,726:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693181999, self.tradeDate='20230828', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26081.7, self.close=26076.7, self.high=26092.1, self.low=26076.7, self.vol=307.956, self.amt=8033452.151, ukdf['pct'].iloc[-1]=-0.000192 , ukdf['amount'].iloc[-1]=8033452.151, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11005.93416310938', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26074.58446337', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30485
self.closeSec=1693182299, self.tradeDate='20230828', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26076.7, self.close=26057.8, self.high=26076.7, self.low=26043.3, self.vol=560.147, self.amt=14595531.6319 
2023-08-28 08:25:00,838:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230828   080000    080459  ...         0.0        0.0       0
5845  20230828   080500    080959  ...         0.0        0.0       0
5846  20230828   081000    081459  ...         0.0        0.0       0
5847  20230828   081500    081959  ...         0.0        0.0       0
5848  20230828   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 08:25:00,838:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693182299, self.tradeDate='20230828', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26076.7, self.close=26057.8, self.high=26076.7, self.low=26043.3, self.vol=560.147, self.amt=14595531.6319, ukdf['pct'].iloc[-1]=-0.000725 , ukdf['amount'].iloc[-1]=14595531.6319, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11241.0672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26057.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30482 

self.closeSec=1693180799, self.tradeDate='20230828', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26083.5, self.close=26087.7, self.high=26088.9, self.low=26081.1 
127.0.0.1 - - [28/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30483 

self.closeSec=1693181099, self.tradeDate='20230828', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26087.6, self.close=26051.3, self.high=26090.7, self.low=26048.5 
127.0.0.1 - - [28/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30484 

self.closeSec=1693181399, self.tradeDate='20230828', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26051.3, self.close=26062.4, self.high=26072.5, self.low=26051.3 
127.0.0.1 - - [28/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30485 

self.closeSec=1693181699, self.tradeDate='20230828', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26062.4, self.close=26081.7, self.high=26081.8, self.low=26054.3 
127.0.0.1 - - [28/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30486 

self.closeSec=1693181999, self.tradeDate='20230828', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26081.7, self.close=26076.7, self.high=26092.1, self.low=26076.7 
127.0.0.1 - - [28/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30487 

self.closeSec=1693182299, self.tradeDate='20230828', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26076.7, self.close=26057.8, self.high=26076.7, self.low=26043.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-28 08:00:16,987:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230828    052959  26083.2  ...  51.250000  0.521266  0.316102
5770  20230828    055959  26103.4  ...  50.833333  0.497925  0.334897
5771  20230828    062959  26058.6  ...  50.416667  0.493795  0.356352
5772  20230828    065959  26050.4  ...  50.416667  0.507172  0.367251
5773  20230828    072959  26076.8  ...  50.416667  0.507576  0.380432

[5 rows x 33 columns]
0.5407407407407407
acc is : 0.5407407407407407
2023-08-28 08:00:17,047:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.498867  0.501133       0  ...  1.062097  -1.0    0.0  0.893608
536     1  0.471159  0.528841       0  ...  1.062432  -1.0    0.0  0.893327
537     1  0.483056  0.516944       1  ...  1.061359  -1.0    0.0  0.894229
538     1  0.498638  0.501362       1  ...  1.061326  -1.0    0.0  0.894256
539     1  0.492056  0.507944       1  ...  1.060911  -1.0    0.0  0.894606

[5 rows x 10 columns]
2023-08-28 08:00:17,059:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498963  0.501037       0  ...  1.063194  -1.0    0.0  0.894439
46     1  0.471257  0.528743       0  ...  1.063529  -1.0    0.0  0.899440
47     1  0.483138  0.516862       1  ...  1.061359  -1.0    0.0  0.896720
48     1  0.498698  0.501302       1  ...  1.061326  -1.0    0.0  0.894996
49     1  0.492056  0.507944       1  ...  1.060911  -1.0    0.0  0.894606

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '8887.90301172809', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26087.17222161', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15239 

self.closeSec=1693178999, self.tradeDate='20230828', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26087.6', self.close='26077.5'
127.0.0.1 - - [28/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15240 

self.closeSec=1693179599, self.tradeDate='20230828', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26077.5', self.close='26082.5'
127.0.0.1 - - [28/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15241 

self.closeSec=1693180199, self.tradeDate='20230828', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26082.5', self.close='26083.7'
127.0.0.1 - - [28/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15242 

self.closeSec=1693180799, self.tradeDate='20230828', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26083.6', self.close='26087.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15243 

self.closeSec=1693181399, self.tradeDate='20230828', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26087.6', self.close='26062.4'
127.0.0.1 - - [28/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15244 

self.closeSec=1693181999, self.tradeDate='20230828', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26062.4', self.close='26076.7'
127.0.0.1 - - [28/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15242 

self.closeSec=1693178999, self.tradeDate='20230828', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26087.6', self.close='26077.5'
127.0.0.1 - - [28/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15243 

self.closeSec=1693179599, self.tradeDate='20230828', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26077.5', self.close='26082.5'
127.0.0.1 - - [28/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15244 

self.closeSec=1693180199, self.tradeDate='20230828', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26082.5', self.close='26083.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15245 

self.closeSec=1693180799, self.tradeDate='20230828', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26083.6', self.close='26087.7'
127.0.0.1 - - [28/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15246 

self.closeSec=1693181399, self.tradeDate='20230828', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26087.6', self.close='26062.4'
127.0.0.1 - - [28/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15247 

self.closeSec=1693181999, self.tradeDate='20230828', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26062.4', self.close='26076.7'
127.0.0.1 - - [28/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [28/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15242 

self.closeSec=1693178999, self.tradeDate='20230828', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26087.6', self.close='26077.5'
127.0.0.1 - - [28/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15243 

self.closeSec=1693179599, self.tradeDate='20230828', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26077.5', self.close='26082.5'
127.0.0.1 - - [28/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15244 

self.closeSec=1693180199, self.tradeDate='20230828', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26082.5', self.close='26083.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15245 

self.closeSec=1693180799, self.tradeDate='20230828', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26083.6', self.close='26087.7'
127.0.0.1 - - [28/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15246 

self.closeSec=1693181399, self.tradeDate='20230828', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26087.6', self.close='26062.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15247 

self.closeSec=1693181999, self.tradeDate='20230828', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26062.4', self.close='26076.7'
127.0.0.1 - - [28/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30484
self.closeSec=1693181999, self.tradeDate='20230828', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26081.7, self.close=26076.7, self.high=26092.1, self.low=26076.7, self.vol=307.956, self.amt=8033452.151 
127.0.0.1 - - [28/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-28 08:20:04,720:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230828   075500    075959  ...         0.0        0.0       0
5844  20230828   080000    080459  ...         0.0        0.0       0
5845  20230828   080500    080959  ...         0.0        0.0       0
5846  20230828   081000    081459  ...         0.0        0.0       0
5847  20230828   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 08:20:04,726:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693181999, self.tradeDate='20230828', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26081.7, self.close=26076.7, self.high=26092.1, self.low=26076.7, self.vol=307.956, self.amt=8033452.151, ukdf['pct'].iloc[-1]=-0.000192 , ukdf['amount'].iloc[-1]=8033452.151, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-28576.86244597483', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26074.58446337', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [28/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30485
self.closeSec=1693182299, self.tradeDate='20230828', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26076.7, self.close=26057.8, self.high=26076.7, self.low=26043.3, self.vol=560.147, self.amt=14595531.6319 
2023-08-28 08:25:00,840:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230828   080000    080459  ...         0.0        0.0       0
5845  20230828   080500    080959  ...         0.0        0.0       0
5846  20230828   081000    081459  ...         0.0        0.0       0
5847  20230828   081500    081959  ...         0.0        0.0       0
5848  20230828   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-28 08:25:00,840:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693182299, self.tradeDate='20230828', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26076.7, self.close=26057.8, self.high=26076.7, self.low=26043.3, self.vol=560.147, self.amt=14595531.6319, ukdf['pct'].iloc[-1]=-0.000725 , ukdf['amount'].iloc[-1]=14595531.6319, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29203.9683', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26057.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230827   200000    235959  1693151999  ...    719  0.315218  0.156514     NaN
720  20230828   000000    035959  1693166399  ...    720  0.375165  0.435366     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '170448.8572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26115.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=635
self.closeSec=1693180799, self.tradeDate='20230828', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26112.2, self.close=26087.7, self.high=26123.8, self.low=26025.2, self.vol=11740.215, self.amt=306115076.2424 
127.0.0.1 - - [28/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-28 08:00:01,570:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693180799, self.tradeDate='20230828', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26112.2, self.close=26087.7, self.high=26123.8, self.low=26025.2, self.vol=11740.215, self.amt=306115076.2424 
2023-08-28 08:00:01,588:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230827   120000    155959  ...   7936.958  2.065765e+08  0.000727
718  20230827   160000    195959  ...  13550.247  3.530646e+08  0.000788
719  20230827   200000    235959  ...  21791.010  5.691195e+08  0.002372
720  20230828   000000    035959  ...  22000.852  5.742453e+08  0.000050
721  20230828   040000    075959  ...  11740.215  3.061151e+08 -0.000934

[5 rows x 11 columns]
2023-08-28 08:00:02,306:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230827   120000    155959  1693123199  ...    717  0.341607  0.162127     NaN
718  20230827   160000    195959  1693137599  ...    718  0.331191  0.162233     NaN
719  20230827   200000    235959  1693151999  ...    719  0.315218  0.156514     NaN
720  20230828   000000    035959  1693166399  ...    720  0.375165  0.435366     NaN
721  20230828   040000    075959  1693180799  ...    721  0.356459  0.461291     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '171887.7212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26087.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


