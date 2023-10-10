# 20231010 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42868
self.closeSec=1696897199, self.tradeDate='20231010', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27566.0, self.close=27580.4, self.high=27580.4, self.low=27560.8, self.vol=291.992, self.amt=8050181.3728 
127.0.0.1 - - [10/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-10-10 08:20:07,519:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231010   075500    075959  ...         0.0        0.0       0
5856  20231010   080000    080459  ...         0.0        0.0       0
5857  20231010   080500    080959  ...         0.0        0.0       0
5858  20231010   081000    081459  ...         0.0        0.0       0
5859  20231010   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 08:20:07,522:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696897199, self.tradeDate='20231010', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27566.0, self.close=27580.4, self.high=27580.4, self.low=27560.8, self.vol=291.992, self.amt=8050181.3728, ukdf['pct'].iloc[-1]=0.000522 , ukdf['amount'].iloc[-1]=8050181.3728, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-9995.80357966146', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27582.67994971', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42869
self.closeSec=1696897499, self.tradeDate='20231010', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27582.0, self.close=27605.3, self.high=27613.1, self.low=27577.9, self.vol=385.861, self.amt=10650372.3845 
2023-10-10 08:25:00,780:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231010   080000    080459  ...         0.0        0.0       0
5857  20231010   080500    080959  ...         0.0        0.0       0
5858  20231010   081000    081459  ...         0.0        0.0       0
5859  20231010   081500    081959  ...         0.0        0.0       0
5860  20231010   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 08:25:00,780:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696897499, self.tradeDate='20231010', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27582.0, self.close=27605.3, self.high=27613.1, self.low=27577.9, self.vol=385.861, self.amt=10650372.3845, ukdf['pct'].iloc[-1]=0.000903 , ukdf['amount'].iloc[-1]=10650372.3845, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-10369.13656887504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27609.48829304', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  127.0.0.1 - - [10/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -
version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42866 

self.closeSec=1696895999, self.tradeDate='20231010', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27574.0, self.close=27578.4, self.high=27582.1, self.low=27561.8 
127.0.0.1 - - [10/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42867 

self.closeSec=1696896299, self.tradeDate='20231010', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27578.4, self.close=27579.1, self.high=27596.2, self.low=27570.8 
127.0.0.1 - - [10/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42868 

self.closeSec=1696896599, self.tradeDate='20231010', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27579.1, self.close=27618.7, self.high=27623.8, self.low=27569.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42869 

self.closeSec=1696896899, self.tradeDate='20231010', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27618.8, self.close=27566.0, self.high=27620.0, self.low=27560.5 
127.0.0.1 - - [10/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42870 

self.closeSec=1696897199, self.tradeDate='20231010', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27566.0, self.close=27580.4, self.high=27580.4, self.low=27560.8 
127.0.0.1 - - [10/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42871 

self.closeSec=1696897499, self.tradeDate='20231010', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27582.0, self.close=27605.3, self.high=27613.1, self.low=27577.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-10 08:00:18,689:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231010    052959  27556.1  ...  49.583333  0.458824  0.630888
5770  20231010    055959  27582.5  ...  50.000000  0.466214  0.622586
5771  20231010    062959  27607.4  ...  50.000000  0.466453  0.613633
5772  20231010    065959  27608.2  ...  49.583333  0.458009  0.608352
5773  20231010    072959  27575.9  ...  49.166667  0.454810  0.603897

[5 rows x 33 columns]
0.5592592592592592
acc is : 0.5592592592592592
2023-10-10 08:00:18,759:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.505566  0.494434       1  ...  0.949217  -1.0    0.0  1.017109
536     0  0.504722  0.495278       1  ...  0.949189  -1.0    0.0  1.017139
537     1  0.499039  0.500961       0  ...  0.950300  -1.0    0.0  1.015949
538     1  0.489682  0.510318       0  ...  0.950723  -1.0    0.0  1.015496
539     1  0.495066  0.504934       1  ...  0.950213  -1.0    0.0  1.016041

[5 rows x 10 columns]
2023-10-10 08:00:18,771:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505555  0.494445       1  ...  0.945271  -1.0    0.0  1.021804
46     0  0.504538  0.495462       1  ...  0.938150  -1.0    0.0  1.014187
47     1  0.499225  0.500775       0  ...  0.950300  -1.0    0.0  1.019551
48     1  0.489585  0.510415       0  ...  0.950723  -1.0    0.0  1.017911
49     1  0.495066  0.504934       1  ...  0.950213  -1.0    0.0  1.016041

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.618', 'enterprice': '27520.8', 'countrevence': '0', 'unrealprofit': '-1348.5878', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27577.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [10/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21431 

self.closeSec=1696894199, self.tradeDate='20231010', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27580.8', self.close='27563.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21432 

self.closeSec=1696894799, self.tradeDate='20231010', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27564.3', self.close='27567.4'
127.0.0.1 - - [10/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21433 

self.closeSec=1696895399, self.tradeDate='20231010', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27567.4', self.close='27576.4'
127.0.0.1 - - [10/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21434 

self.closeSec=1696895999, self.tradeDate='20231010', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27576.4', self.close='27578.4'
127.0.0.1 - - [10/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21435 

self.closeSec=1696896599, self.tradeDate='20231010', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27578.4', self.close='27618.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21436 

self.closeSec=1696897199, self.tradeDate='20231010', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27618.8', self.close='27580.4'
127.0.0.1 - - [10/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [10/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21434 

self.closeSec=1696894199, self.tradeDate='20231010', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27580.8', self.close='27563.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21435 

self.closeSec=1696894799, self.tradeDate='20231010', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27564.3', self.close='27567.4'
127.0.0.1 - - [10/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21436 

self.closeSec=1696895399, self.tradeDate='20231010', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27567.4', self.close='27576.4'
127.0.0.1 - - [10/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21437 

self.closeSec=1696895999, self.tradeDate='20231010', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27576.4', self.close='27578.4'
127.0.0.1 - - [10/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21438 

self.closeSec=1696896599, self.tradeDate='20231010', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27578.4', self.close='27618.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21439 

self.closeSec=1696897199, self.tradeDate='20231010', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27618.8', self.close='27580.4'
127.0.0.1 - - [10/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21434 

self.closeSec=1696894199, self.tradeDate='20231010', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27580.8', self.close='27563.6'
127.0.0.1 - - [10/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21435 

self.closeSec=1696894799, self.tradeDate='20231010', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27564.3', self.close='27567.4'
127.0.0.1 - - [10/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21436 

self.closeSec=1696895399, self.tradeDate='20231010', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27567.4', self.close='27576.4'
127.0.0.1 - - [10/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21437 

self.closeSec=1696895999, self.tradeDate='20231010', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27576.4', self.close='27578.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21438 

self.closeSec=1696896599, self.tradeDate='20231010', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27578.4', self.close='27618.7'
127.0.0.1 - - [10/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21439 

self.closeSec=1696897199, self.tradeDate='20231010', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27618.8', self.close='27580.4'
127.0.0.1 - - [10/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42868
self.closeSec=1696897199, self.tradeDate='20231010', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27566.0, self.close=27580.4, self.high=27580.4, self.low=27560.8, self.vol=291.992, self.amt=8050181.3728 
127.0.0.1 - - [10/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-10-10 08:20:07,521:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231010   075500    075959  ...         0.0        0.0       0
5856  20231010   080000    080459  ...         0.0        0.0       0
5857  20231010   080500    080959  ...         0.0        0.0       0
5858  20231010   081000    081459  ...         0.0        0.0       0
5859  20231010   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 08:20:07,524:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696897199, self.tradeDate='20231010', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27566.0, self.close=27580.4, self.high=27580.4, self.low=27560.8, self.vol=291.992, self.amt=8050181.3728, ukdf['pct'].iloc[-1]=0.000522 , ukdf['amount'].iloc[-1]=8050181.3728, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '27435.31201217911', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27582.67994971', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42869
self.closeSec=1696897499, self.tradeDate='20231010', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27582.0, self.close=27605.3, self.high=27613.1, self.low=27577.9, self.vol=385.861, self.amt=10650372.3845 
127.0.0.1 - - [10/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-10 08:25:00,798:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231010   080000    080459  ...         0.0        0.0       0
5857  20231010   080500    080959  ...         0.0        0.0       0
5858  20231010   081000    081459  ...         0.0        0.0       0
5859  20231010   081500    081959  ...         0.0        0.0       0
5860  20231010   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-10 08:25:00,799:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696897499, self.tradeDate='20231010', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27582.0, self.close=27605.3, self.high=27613.1, self.low=27577.9, self.vol=385.861, self.amt=10650372.3845, ukdf['pct'].iloc[-1]=0.000903 , ukdf['amount'].iloc[-1]=10650372.3845, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '28431.00069179864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27609.48829304', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231009   200000    235959  1696867199  ...    719  0.091458 -1.143627    -1.0
720  20231010   000000    035959  1696881599  ...    720  0.150387 -0.960126    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '14766.12911265148', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27605.70400916', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=893
self.closeSec=1696895999, self.tradeDate='20231010', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27607.7, self.close=27578.4, self.high=27644.0, self.low=27542.3, self.vol=15212.963, self.amt=419686182.73 
127.0.0.1 - - [10/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-10 08:00:01,548:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696895999, self.tradeDate='20231010', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27607.7, self.close=27578.4, self.high=27644.0, self.low=27542.3, self.vol=15212.963, self.amt=419686182.73 
2023-10-10 08:00:01,565:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231009   120000    155959  ...  18808.510  5.240199e+08 -0.003876
718  20231009   160000    195959  ...  93264.706  2.572383e+09 -0.012509
719  20231009   200000    235959  ...  60969.452  1.674700e+09 -0.000830
720  20231010   000000    035959  ...  99576.614  2.736496e+09  0.006139
721  20231010   040000    075959  ...  15212.963  4.196862e+08 -0.000837

[5 rows x 11 columns]
2023-10-10 08:00:02,477:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231009   120000    155959  1696838399  ...    717  0.080186 -1.217978    -1.0
718  20231009   160000    195959  1696852799  ...    718  0.067976 -1.229082    -1.0
719  20231009   200000    235959  1696867199  ...    719  0.091458 -1.143627    -1.0
720  20231010   000000    035959  1696881599  ...    720  0.150387 -0.960126    -1.0
721  20231010   040000    075959  1696895999  ...    721  0.134666 -0.990590    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '15960.8617', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27578.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


