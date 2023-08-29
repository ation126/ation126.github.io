# 20230829 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30772
self.closeSec=1693268399, self.tradeDate='20230829', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26110.2, self.close=26111.1, self.high=26114.7, self.low=26103.5, self.vol=158.391, self.amt=4135667.9098 
127.0.0.1 - - [29/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-29 08:20:05,476:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230829   075500    075959  ...         0.0        0.0       0
5844  20230829   080000    080459  ...         0.0        0.0       0
5845  20230829   080500    080959  ...         0.0        0.0       0
5846  20230829   081000    081459  ...         0.0        0.0       0
5847  20230829   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 08:20:05,479:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693268399, self.tradeDate='20230829', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26110.2, self.close=26111.1, self.high=26114.7, self.low=26103.5, self.vol=158.391, self.amt=4135667.9098, ukdf['pct'].iloc[-1]=3.4e-05 , ukdf['amount'].iloc[-1]=4135667.9098, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10484.8854', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26112', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30773
self.closeSec=1693268699, self.tradeDate='20230829', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26111.1, self.close=26109.5, self.high=26120.0, self.low=26109.4, self.vol=315.436, self.amt=8238076.3293 
127.0.0.1 - - [29/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-29 08:25:00,785:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230829   080000    080459  ...         0.0        0.0       0
5845  20230829   080500    080959  ...         0.0        0.0       0
5846  20230829   081000    081459  ...         0.0        0.0       0
5847  20230829   081500    081959  ...         0.0        0.0       0
5848  20230829   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 08:25:00,785:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693268699, self.tradeDate='20230829', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26111.1, self.close=26109.5, self.high=26120.0, self.low=26109.4, self.vol=315.436, self.amt=8238076.3293, ukdf['pct'].iloc[-1]=-6.1e-05 , ukdf['amount'].iloc[-1]=8238076.3293, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10484.16609313392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26112.05165208', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [29/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30770 

self.closeSec=1693267199, self.tradeDate='20230829', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26116.6, self.close=26106.5, self.high=26118.8, self.low=26106.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30771 

self.closeSec=1693267499, self.tradeDate='20230829', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26106.5, self.close=26097.6, self.high=26113.1, self.low=26096.0 
127.0.0.1 - - [29/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30772 

self.closeSec=1693267799, self.tradeDate='20230829', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26097.5, self.close=26103.7, self.high=26120.0, self.low=26097.5 
127.0.0.1 - - [29/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30773 

self.closeSec=1693268099, self.tradeDate='20230829', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26103.7, self.close=26110.2, self.high=26123.4, self.low=26103.7 
127.0.0.1 - - [29/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30774 

self.closeSec=1693268399, self.tradeDate='20230829', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26110.2, self.close=26111.1, self.high=26114.7, self.low=26103.5 
127.0.0.1 - - [29/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30775 

self.closeSec=1693268699, self.tradeDate='20230829', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26111.1, self.close=26109.5, self.high=26120.0, self.low=26109.4 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-29 08:00:17,951:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5769  20230829    052959  25979.4  ...     50.0  0.477966  0.506924
5770  20230829    055959  25992.6  ...     50.0  0.467838  0.520093
5771  20230829    062959  25966.9  ...     50.0  0.487749  0.524571
5772  20230829    065959  26013.1  ...     50.0  0.501347  0.523170
5773  20230829    072959  26046.1  ...     50.0  0.530047  0.509279

[5 rows x 33 columns]
0.5462962962962963
acc is : 0.5462962962962963
2023-08-29 08:00:18,014:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.478508  0.521492       0  ...  1.012242  -1.0    0.0  0.928513
536     1  0.477585  0.522415       1  ...  1.010441  -1.0    0.0  0.930165
537     0  0.501950  0.498050       1  ...  1.009159  -1.0    0.0  0.931345
538     0  0.500120  0.499880       1  ...  1.006276  -1.0    0.0  0.934006
539     0  0.522981  0.477019       0  ...  1.006816  -1.0    0.0  0.933505

[5 rows x 10 columns]
2023-08-29 08:00:18,025:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.478459  0.521541       0  ...  1.010754  -1.0    0.0  0.929870
46     1  0.477566  0.522434       1  ...  1.007320  -1.0    0.0  0.933035
47     0  0.501748  0.498252       1  ...  1.009159  -1.0    0.0  0.932636
48     1  0.499839  0.500161       1  ...  1.006276  -1.0    0.0  0.933035
49     0  0.522981  0.477019       0  ...  1.006816  -1.0    0.0  0.933505

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.758', 'enterprice': '25982.3', 'countrevence': '0', 'unrealprofit': '-3761.5464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26113.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15383 

self.closeSec=1693265399, self.tradeDate='20230829', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26135.7', self.close='26120.5'
127.0.0.1 - - [29/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15384 

self.closeSec=1693265999, self.tradeDate='20230829', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26120.6', self.close='26112.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15385127.0.0.1 - - [29/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -
 

self.closeSec=1693266599, self.tradeDate='20230829', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26112.6', self.close='26106.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15386 

self.closeSec=1693267199, self.tradeDate='20230829', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26106.4', self.close='26106.5'
127.0.0.1 - - [29/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15387 

self.closeSec=1693267799, self.tradeDate='20230829', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26106.5', self.close='26103.7'
127.0.0.1 - - [29/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15388 

self.closeSec=1693268399, self.tradeDate='20230829', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26103.7', self.close='26111.1'
127.0.0.1 - - [29/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15386 

self.closeSec=1693265399, self.tradeDate='20230829', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26135.7', self.close='26120.5'
127.0.0.1 - - [29/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15387 

self.closeSec=1693265999, self.tradeDate='20230829', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26120.6', self.close='26112.6'

--handleKline--: 127.0.0.1 - - [29/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15388 

self.closeSec=1693266599, self.tradeDate='20230829', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26112.6', self.close='26106.5'
127.0.0.1 - - [29/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15389 

self.closeSec=1693267199, self.tradeDate='20230829', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26106.4', self.close='26106.5'
127.0.0.1 - - [29/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15390 

self.closeSec=1693267799, self.tradeDate='20230829', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26106.5', self.close='26103.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15391 

self.closeSec=1693268399, self.tradeDate='20230829', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26103.7', self.close='26111.1'
127.0.0.1 - - [29/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15386 

self.closeSec=1693265399, self.tradeDate='20230829', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26135.7', self.close='26120.5'
127.0.0.1 - - [29/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15387 

self.closeSec=1693265999, self.tradeDate='20230829', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26120.6', self.close='26112.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15388 

self.closeSec=1693266599, self.tradeDate='20230829', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26112.6', self.close='26106.5'
127.0.0.1 - - [29/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15389 

self.closeSec=1693267199, self.tradeDate='20230829', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26106.4', self.close='26106.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15390 

self.closeSec=1693267799, self.tradeDate='20230829', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26106.5', self.close='26103.7'
127.0.0.1 - - [29/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15391 

self.closeSec=1693268399, self.tradeDate='20230829', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26103.7', self.close='26111.1'
127.0.0.1 - - [29/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30772
self.closeSec=1693268399, self.tradeDate='20230829', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26110.2, self.close=26111.1, self.high=26114.7, self.low=26103.5, self.vol=158.391, self.amt=4135667.9098 
127.0.0.1 - - [29/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-29 08:20:05,477:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230829   075500    075959  ...         0.0        0.0       0
5844  20230829   080000    080459  ...         0.0        0.0       0
5845  20230829   080500    080959  ...         0.0        0.0       0
5846  20230829   081000    081459  ...         0.0        0.0       0
5847  20230829   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 08:20:05,486:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693268399, self.tradeDate='20230829', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26110.2, self.close=26111.1, self.high=26114.7, self.low=26103.5, self.vol=158.391, self.amt=4135667.9098, ukdf['pct'].iloc[-1]=3.4e-05 , ukdf['amount'].iloc[-1]=4135667.9098, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27187.212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26112', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30773
self.closeSec=1693268699, self.tradeDate='20230829', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26111.1, self.close=26109.5, self.high=26120.0, self.low=26109.4, self.vol=315.436, self.amt=8238076.3293 
127.0.0.1 - - [29/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-29 08:25:00,791:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230829   080000    080459  ...         0.0        0.0       0
5845  20230829   080500    080959  ...         0.0        0.0       0
5846  20230829   081000    081459  ...         0.0        0.0       0
5847  20230829   081500    081959  ...         0.0        0.0       0
5848  20230829   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 08:25:00,791:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693268699, self.tradeDate='20230829', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26111.1, self.close=26109.5, self.high=26120.0, self.low=26109.4, self.vol=315.436, self.amt=8238076.3293, ukdf['pct'].iloc[-1]=-6.1e-05 , ukdf['amount'].iloc[-1]=8238076.3293, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27185.29359009672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26112.05165208', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230828   200000    235959  1693238399  ...    719  0.000009 -1.132751    -1.0
720  20230829   000000    035959  1693252799  ...    720  0.000300 -1.122435    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '177211.9153628488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25984.0922674', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=641
self.closeSec=1693267199, self.tradeDate='20230829', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25981.7, self.close=26106.5, self.high=26170.0, self.low=25931.8, self.vol=25253.358, self.amt=657835231.892 
127.0.0.1 - - [29/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-29 08:00:01,522:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693267199, self.tradeDate='20230829', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25981.7, self.close=26106.5, self.high=26170.0, self.low=25931.8, self.vol=25253.358, self.amt=657835231.892 
2023-08-29 08:00:01,537:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230828   120000    155959  ...  30904.881  8.016251e+08 -0.003038
718  20230828   160000    195959  ...  27052.356  7.015093e+08  0.002693
719  20230828   200000    235959  ...  68566.281  1.790877e+09  0.003790
720  20230829   000000    035959  ...  41869.582  1.090798e+09 -0.004204
721  20230829   040000    075959  ...  25253.358  6.578352e+08  0.004807

[5 rows x 11 columns]
2023-08-29 08:00:02,232:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230828   120000    155959  1693209599  ...    717  0.170310 -0.261334     NaN
718  20230828   160000    195959  1693223999  ...    718  0.076940 -0.697728    -1.0
719  20230828   200000    235959  1693238399  ...    719  0.000009 -1.132751    -1.0
720  20230829   000000    035959  1693252799  ...    720  0.000300 -1.122435    -1.0
721  20230829   040000    075959  1693267199  ...    721  0.000189 -1.110704    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '170833.28883465948', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26108.21903879', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


