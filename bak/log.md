# 20230825 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29620
self.closeSec=1692922799, self.tradeDate='20230825', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26129.9, self.close=26142.0, self.high=26143.9, self.low=26120.0, self.vol=629.145, self.amt=16440109.5691 
127.0.0.1 - - [25/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-25 08:20:05,532:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230825   075500    075959  ...         0.0        0.0       0
5844  20230825   080000    080459  ...         0.0        0.0       0
5845  20230825   080500    080959  ...         0.0        0.0       0
5846  20230825   081000    081459  ...         0.0        0.0       0
5847  20230825   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 08:20:05,542:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692922799, self.tradeDate='20230825', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26129.9, self.close=26142.0, self.high=26143.9, self.low=26120.0, self.vol=629.145, self.amt=16440109.5691, ukdf['pct'].iloc[-1]=0.000463 , ukdf['amount'].iloc[-1]=16440109.5691, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10093.32290593704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26140.11736996', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29621
self.closeSec=1692923099, self.tradeDate='20230825', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26142.0, self.close=26120.1, self.high=26142.0, self.low=26113.8, self.vol=391.492, self.amt=10227706.7554 
127.0.0.1 - - [25/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-25 08:25:00,801:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230825   080000    080459  ...         0.0        0.0       0
5845  20230825   080500    080959  ...         0.0        0.0       0
5846  20230825   081000    081459  ...         0.0        0.0       0
5847  20230825   081500    081959  ...         0.0        0.0       0
5848  20230825   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 08:25:00,801:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692923099, self.tradeDate='20230825', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26142.0, self.close=26120.1, self.high=26142.0, self.low=26113.8, self.vol=391.492, self.amt=10227706.7554, ukdf['pct'].iloc[-1]=-0.000838 , ukdf['amount'].iloc[-1]=10227706.7554, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10370.31306088998', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26120.22722527', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [25/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29618 

self.closeSec=1692921599, self.tradeDate='20230825', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26128.0, self.close=26164.5, self.high=26173.0, self.low=26127.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29619 

self.closeSec=1692921899, self.tradeDate='20230825', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26164.6, self.close=26164.4, self.high=26177.0, self.low=26160.1 
127.0.0.1 - - [25/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29620 

self.closeSec=1692922199, self.tradeDate='20230825', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26164.4, self.close=26132.8, self.high=26167.0, self.low=26132.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29621 

self.closeSec=1692922499, self.tradeDate='20230825', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26132.8, self.close=26129.9, self.high=26144.0, self.low=26129.0 
127.0.0.1 - - [25/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29622 

self.closeSec=1692922799, self.tradeDate='20230825', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26129.9, self.close=26142.0, self.high=26143.9, self.low=26120.0 
127.0.0.1 - - [25/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29623 

self.closeSec=1692923099, self.tradeDate='20230825', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26142.0, self.close=26120.1, self.high=26142.0, self.low=26113.8 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-25 08:00:16,994:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230825    052959  26022.0  ...  51.666667  0.464374  0.664571
5770  20230825    055959  26051.4  ...  51.666667  0.471158  0.664677
5771  20230825    062959  26079.8  ...  52.083333  0.477858  0.662213
5772  20230825    065959  26107.9  ...  52.083333  0.477858  0.659913
5773  20230825    072959  26107.9  ...  51.666667  0.475744  0.658630

[5 rows x 33 columns]
0.5259259259259259
acc is : 0.5259259259259259
2023-08-25 08:00:17,056:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.506931  0.493069       1  ...  1.051315  -1.0    0.0  0.887331
536     0  0.500998  0.499002       1  ...  1.050178  -1.0    0.0  0.888290
537     0  0.504567  0.495433       1  ...  1.050178  -1.0    0.0  0.888290
538     1  0.492128  0.507872       0  ...  1.050560  -1.0    0.0  0.887967
539     1  0.485832  0.514168       1  ...  1.047904  -1.0    0.0  0.890212

[5 rows x 10 columns]
2023-08-25 08:00:17,067:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506999  0.493001       1  ...  1.051315  -1.0    0.0  0.888522
46     0  0.501286  0.498714       1  ...  1.050178  -1.0    0.0  0.889149
47     0  0.504648  0.495352       1  ...  1.050178  -1.0    0.0  0.889798
48     1  0.492509  0.507491       0  ...  1.050560  -1.0    0.0  0.889368
49     1  0.485832  0.514168       1  ...  1.047904  -1.0    0.0  0.890212

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '6673.8084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26165.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14807 

self.closeSec=1692919799, self.tradeDate='20230825', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26086', self.close='26098.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14808 

self.closeSec=1692920399, self.tradeDate='20230825', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26098.6', self.close='26112.9'
127.0.0.1 - - [25/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14809 

self.closeSec=1692920999, self.tradeDate='20230825', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26113', self.close='26175.9'
127.0.0.1 - - [25/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14810 

self.closeSec=1692921599, self.tradeDate='20230825', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26175.9', self.close='26164.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14811 

self.closeSec=1692922199, self.tradeDate='20230825', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26164.6', self.close='26132.8'
127.0.0.1 - - [25/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14812 

self.closeSec=1692922799, self.tradeDate='20230825', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26132.8', self.close='26142'
127.0.0.1 - - [25/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [25/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14810 

self.closeSec=1692919799, self.tradeDate='20230825', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26086', self.close='26098.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14811 

self.closeSec=1692920399, self.tradeDate='20230825', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26098.6', self.close='26112.9'
127.0.0.1 - - [25/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14812 

self.closeSec=1692920999, self.tradeDate='20230825', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26113', self.close='26175.9'
127.0.0.1 - - [25/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14813 

self.closeSec=1692921599, self.tradeDate='20230825', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26175.9', self.close='26164.6'
127.0.0.1 - - [25/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14814 

self.closeSec=1692922199, self.tradeDate='20230825', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26164.6', self.close='26132.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14815 

self.closeSec=1692922799, self.tradeDate='20230825', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26132.8', self.close='26142'
127.0.0.1 - - [25/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14810 

self.closeSec=1692919799, self.tradeDate='20230825', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26086', self.close='26098.5'
127.0.0.1 - - [25/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14811 

self.closeSec=1692920399, self.tradeDate='20230825', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26098.6', self.close='26112.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14812 

self.closeSec=1692920999, self.tradeDate='20230825', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26113', self.close='26175.9'
127.0.0.1 - - [25/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14813 

self.closeSec=1692921599, self.tradeDate='20230825', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26175.9', self.close='26164.6'
127.0.0.1 - - [25/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14814 

self.closeSec=1692922199, self.tradeDate='20230825', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26164.6', self.close='26132.8'
127.0.0.1 - - [25/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14815 

self.closeSec=1692922799, self.tradeDate='20230825', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26132.8', self.close='26142'
127.0.0.1 - - [25/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29620
self.closeSec=1692922799, self.tradeDate='20230825', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26129.9, self.close=26142.0, self.high=26143.9, self.low=26120.0, self.vol=629.145, self.amt=16440109.5691 
127.0.0.1 - - [25/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-25 08:20:05,517:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230825   075500    075959  ...         0.0        0.0       0
5844  20230825   080000    080459  ...         0.0        0.0       0
5845  20230825   080500    080959  ...         0.0        0.0       0
5846  20230825   081000    081459  ...         0.0        0.0       0
5847  20230825   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 08:20:05,521:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692922799, self.tradeDate='20230825', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26129.9, self.close=26142.0, self.high=26143.9, self.low=26120.0, self.vol=629.145, self.amt=16440109.5691, ukdf['pct'].iloc[-1]=0.000463 , ukdf['amount'].iloc[-1]=16440109.5691, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26142.90476231564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26140.11736996', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29621
self.closeSec=1692923099, self.tradeDate='20230825', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26142.0, self.close=26120.1, self.high=26142.0, self.low=26113.8, self.vol=391.492, self.amt=10227706.7554 
2023-08-25 08:25:00,801:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230825   080000    080459  ...         0.0        0.0       0
5845  20230825   080500    080959  ...         0.0        0.0       0
5846  20230825   081000    081459  ...         0.0        0.0       0
5847  20230825   081500    081959  ...         0.0        0.0       0
5848  20230825   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 08:25:00,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692923099, self.tradeDate='20230825', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26142.0, self.close=26120.1, self.high=26142.0, self.low=26113.8, self.vol=391.492, self.amt=10227706.7554, ukdf['pct'].iloc[-1]=-0.000838 , ukdf['amount'].iloc[-1]=10227706.7554, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26881.64462624693', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26120.22722527', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230824   200000    235959  1692892799  ...    719  0.180320 -0.580225     NaN
720  20230825   000000    035959  1692907199  ...    720  0.182993 -0.556918     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174904.1968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26029', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=617
self.closeSec=1692921599, self.tradeDate='20230825', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26026.0, self.close=26164.5, self.high=26200.0, self.low=25918.5, self.vol=30501.019, self.amt=795029963.4975 
127.0.0.1 - - [25/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-25 08:00:01,559:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692921599, self.tradeDate='20230825', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26026.0, self.close=26164.5, self.high=26200.0, self.low=25918.5, self.vol=30501.019, self.amt=795029963.4975 
2023-08-25 08:00:01,575:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230824   120000    155959  ...   23503.450  6.214354e+08  0.001158
718  20230824   160000    195959  ...   33863.295  8.963928e+08 -0.001013
719  20230824   200000    235959  ...  100354.824  2.628388e+09 -0.016944
720  20230825   000000    035959  ...   68687.910  1.787758e+09  0.001470
721  20230825   040000    075959  ...   30501.019  7.950300e+08  0.005391

[5 rows x 11 columns]
2023-08-25 08:00:02,276:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230824   120000    155959  1692863999  ...    717  0.141513 -0.704028    -1.0
718  20230824   160000    195959  1692878399  ...    718  0.183111 -0.590625     NaN
719  20230824   200000    235959  1692892799  ...    719  0.180320 -0.580225     NaN
720  20230825   000000    035959  1692907199  ...    720  0.182993 -0.556918     NaN
721  20230825   040000    075959  1692921599  ...    721  0.186231 -0.532023     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '167926.18705663024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26164.79064652', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


