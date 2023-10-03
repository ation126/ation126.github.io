# 20231003 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40852
self.closeSec=1696292399, self.tradeDate='20231003', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27483.5, self.close=27502.2, self.high=27512.5, self.low=27470.0, self.vol=727.601, self.amt=20004175.3216 
127.0.0.1 - - [03/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-03 08:20:05,855:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231003   075500    075959  ...         0.0        0.0       0
5856  20231003   080000    080459  ...         0.0        0.0       0
5857  20231003   080500    080959  ...         0.0        0.0       0
5858  20231003   081000    081459  ...         0.0        0.0       0
5859  20231003   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 08:20:05,858:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696292399, self.tradeDate='20231003', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27483.5, self.close=27502.2, self.high=27512.5, self.low=27470.0, self.vol=727.601, self.amt=20004175.3216, ukdf['pct'].iloc[-1]=0.000677 , ukdf['amount'].iloc[-1]=20004175.3216, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-8953.5791360565', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27507.83976275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40853
self.closeSec=1696292699, self.tradeDate='20231003', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27504.9, self.close=27510.8, self.high=27520.0, self.low=27495.8, self.vol=477.4, self.amt=13131769.9066 
2023-10-03 08:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231003   080000    080459  ...         0.0        0.0       0
5857  20231003   080500    080959  ...         0.0        0.0       0
5858  20231003   081000    081459  ...         0.0        0.0       0
5859  20231003   081500    081959  ...         0.0        0.0       0
5860  20231003   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 08:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696292699, self.tradeDate='20231003', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27504.9, self.close=27510.8, self.high=27520.0, self.low=27495.8, self.vol=477.4, self.amt=13131769.9066, ukdf['pct'].iloc[-1]=0.000313 , ukdf['amount'].iloc[-1]=13131769.9066, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-9024.60165403236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27512.93975686', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [03/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40850 

self.closeSec=1696291199, self.tradeDate='20231003', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27592.1, self.close=27481.7, self.high=27592.1, self.low=27467.2 
127.0.0.1 - - [03/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40851 

self.closeSec=1696291499, self.tradeDate='20231003', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27477.7, self.close=27492.6, self.high=27526.8, self.low=27476.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40852 

self.closeSec=1696291799, self.tradeDate='20231003', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27492.6, self.close=27501.1, self.high=27517.6, self.low=27465.1 
127.0.0.1 - - [03/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40853 

self.closeSec=1696292099, self.tradeDate='20231003', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27502.3, self.close=27483.6, self.high=27508.5, self.low=27473.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40854 

self.closeSec=1696292399, self.tradeDate='20231003', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27483.5, self.close=27502.2, self.high=27512.5, self.low=27470.0 
127.0.0.1 - - [03/Oct/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40855 

self.closeSec=1696292699, self.tradeDate='20231003', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27504.9, self.close=27510.8, self.high=27520.0, self.low=27495.8 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-03 08:00:16,464:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5769  20231003    052959  27836.6  ...    56.25  0.530030  0.448108
5770  20231003    055959  27855.5  ...    56.25  0.468550  0.475004
5771  20231003    062959  27456.7  ...    56.25  0.477693  0.497225
5772  20231003    065959  27512.1  ...    56.25  0.481615  0.516723
5773  20231003    072959  27537.1  ...    56.25  0.478341  0.536030

[5 rows x 33 columns]
0.5518518518518518
acc is : 0.5518518518518518
2023-10-03 08:00:16,524:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.496796  0.503204       0  ...  0.936216  -1.0    0.0  1.030808
536     1  0.366141  0.633859       1  ...  0.934214  -1.0    0.0  1.033012
537     1  0.479141  0.520859       1  ...  0.933355  -1.0    0.0  1.033962
538     1  0.477609  0.522391       0  ...  0.934121  -1.0    0.0  1.033113
539     1  0.464597  0.535403       0  ...  0.935353  -1.0    0.0  1.031750

[5 rows x 10 columns]
2023-10-03 08:00:16,535:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496997  0.503003       0  ...  0.936216  -1.0    0.0  1.033458
46     1  0.366398  0.633602       1  ...  0.952221  -1.0    0.0  1.036225
47     1  0.479050  0.520950       1  ...  0.933355  -1.0    0.0  1.036635
48     1  0.477522  0.522478       0  ...  0.934121  -1.0    0.0  1.033342
49     1  0.464597  0.535403       0  ...  0.935353  -1.0    0.0  1.031750

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.906', 'enterprice': '28298.9', 'countrevence': '0', 'unrealprofit': '19215.6428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27495.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [03/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20423 

self.closeSec=1696289399, self.tradeDate='20231003', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27497.3', self.close='27518'
127.0.0.1 - - [03/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20424 

self.closeSec=1696289999, self.tradeDate='20231003', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27518', self.close='27568.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20425 

self.closeSec=1696290599, self.tradeDate='20231003', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27568.6', self.close='27595.9'
127.0.0.1 - - [03/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20426 

self.closeSec=1696291199, self.tradeDate='20231003', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27595.9', self.close='27481.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20427 

self.closeSec=1696291799, self.tradeDate='20231003', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27477.7', self.close='27501.1'
127.0.0.1 - - [03/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20428 

self.closeSec=1696292399, self.tradeDate='20231003', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27502.3', self.close='27504.8'
127.0.0.1 - - [03/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [03/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20426 

self.closeSec=1696289399, self.tradeDate='20231003', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27497.3', self.close='27518'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20427127.0.0.1 - - [03/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 

self.closeSec=1696289999, self.tradeDate='20231003', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27518', self.close='27568.6'
127.0.0.1 - - [03/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20428 

self.closeSec=1696290599, self.tradeDate='20231003', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27568.6', self.close='27595.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20429 

self.closeSec=1696291199, self.tradeDate='20231003', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27595.9', self.close='27481.7'
127.0.0.1 - - [03/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20430 

self.closeSec=1696291799, self.tradeDate='20231003', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27477.7', self.close='27501.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20431 

self.closeSec=1696292399, self.tradeDate='20231003', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27502.3', self.close='27504.8'
127.0.0.1 - - [03/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [03/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20426 

self.closeSec=1696289399, self.tradeDate='20231003', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27497.3', self.close='27518'
127.0.0.1 - - [03/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20427 

self.closeSec=1696289999, self.tradeDate='20231003', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27518', self.close='27568.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20428 

self.closeSec=1696290599, self.tradeDate='20231003', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27568.6', self.close='27595.9'
127.0.0.1 - - [03/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20429 

self.closeSec=1696291199, self.tradeDate='20231003', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27595.9', self.close='27481.7'
127.0.0.1 - - [03/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20430 

self.closeSec=1696291799, self.tradeDate='20231003', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27477.7', self.close='27501.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20431 

self.closeSec=1696292399, self.tradeDate='20231003', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27502.3', self.close='27504.8'
127.0.0.1 - - [03/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40852
self.closeSec=1696292399, self.tradeDate='20231003', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27483.5, self.close=27502.2, self.high=27512.5, self.low=27470.0, self.vol=727.601, self.amt=20004175.3216 
127.0.0.1 - - [03/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-03 08:20:05,854:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231003   075500    075959  ...         0.0        0.0       0
5856  20231003   080000    080459  ...         0.0        0.0       0
5857  20231003   080500    080959  ...         0.0        0.0       0
5858  20231003   081000    081459  ...         0.0        0.0       0
5859  20231003   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 08:20:05,857:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696292399, self.tradeDate='20231003', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27483.5, self.close=27502.2, self.high=27512.5, self.low=27470.0, self.vol=727.601, self.amt=20004175.3216, ukdf['pct'].iloc[-1]=0.000677 , ukdf['amount'].iloc[-1]=20004175.3216, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '24655.67262829775', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27507.83976275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40853
self.closeSec=1696292699, self.tradeDate='20231003', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27504.9, self.close=27510.8, self.high=27520.0, self.low=27495.8, self.vol=477.4, self.amt=13131769.9066 
127.0.0.1 - - [03/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-03 08:25:00,783:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231003   080000    080459  ...         0.0        0.0       0
5857  20231003   080500    080959  ...         0.0        0.0       0
5858  20231003   081000    081459  ...         0.0        0.0       0
5859  20231003   081500    081959  ...         0.0        0.0       0
5860  20231003   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 08:25:00,784:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696292699, self.tradeDate='20231003', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27504.9, self.close=27510.8, self.high=27520.0, self.low=27495.8, self.vol=477.4, self.amt=13131769.9066, ukdf['pct'].iloc[-1]=0.000313 , ukdf['amount'].iloc[-1]=13131769.9066, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '24845.09150953726', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27512.93975686', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231002   200000    235959  1696262399  ...    719  0.947660  0.684216     1.0
720  20231003   000000    035959  1696276799  ...    720  1.130921  1.105921     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-2706.72980047132', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27953.60642549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [03/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1223948.6721539998, self.flagDict['side']='buy', self.tradeCount=29, self.count=851
self.closeSec=1696291199, self.tradeDate='20231003', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27955.3, self.close=27481.7, self.high=27955.4, self.low=27255.0, self.vol=88961.527, self.amt=2450606500.45204 
2023-10-03 08:00:01,561:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696291199, self.tradeDate='20231003', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27955.3, self.close=27481.7, self.high=27955.4, self.low=27255.0, self.vol=88961.527, self.amt=2450606500.45204 
2023-10-03 08:00:01,577:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231002   120000    155959  ...   82485.833  2.322852e+09  0.006401
718  20231002   160000    195959  ...   85552.741  2.421877e+09 -0.004131
719  20231002   200000    235959  ...  142170.052  4.021523e+09 -0.005503
720  20231003   000000    035959  ...  130185.968  3.631271e+09 -0.002594
721  20231003   040000    075959  ...   88961.527  2.450607e+09 -0.016941

[5 rows x 11 columns]
2023-10-03 08:00:02,415:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231002   120000    155959  1696233599  ...    717  0.815649  0.396154     NaN
718  20231002   160000    195959  1696247999  ...    718  0.807842  0.363571     NaN
719  20231002   200000    235959  1696262399  ...    719  0.947660  0.684216     1.0
720  20231003   000000    035959  1696276799  ...    720  1.130921  1.105921     1.0
721  20231003   040000    075959  1696291199  ...    721  1.177827  1.194833     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-23490.59389391624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27478.35114118', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


