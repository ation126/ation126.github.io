# 20230902 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31924
self.closeSec=1693613999, self.tradeDate='20230902', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25796.8, self.close=25797.9, self.high=25799.3, self.low=25790.0, self.vol=148.788, self.amt=3838191.9783 
127.0.0.1 - - [02/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-09-02 08:20:05,264:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230902   075500    075959  ...         0.0        0.0       0
5844  20230902   080000    080459  ...         0.0        0.0       0
5845  20230902   080500    080959  ...         0.0        0.0       0
5846  20230902   081000    081459  ...         0.0        0.0       0
5847  20230902   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 08:20:05,272:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693613999, self.tradeDate='20230902', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25796.8, self.close=25797.9, self.high=25799.3, self.low=25790.0, self.vol=148.788, self.amt=3838191.9783, ukdf['pct'].iloc[-1]=4.3e-05 , ukdf['amount'].iloc[-1]=3838191.9783, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14857.6494', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25798', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31925
self.closeSec=1693614299, self.tradeDate='20230902', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25798.0, self.close=25814.3, self.high=25820.0, self.low=25797.9, self.vol=484.817, self.amt=12514264.7657 
2023-09-02 08:25:00,782:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230902   080000    080459  ...         0.0        0.0       0
5845  20230902   080500    080959  ...         0.0        0.0       0
5846  20230902   081000    081459  ...         0.0        0.0       0
5847  20230902   081500    081959  ...         0.0        0.0       0
5848  20230902   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 08:25:00,782:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693614299, self.tradeDate='20230902', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25798.0, self.close=25814.3, self.high=25820.0, self.low=25797.9, self.vol=484.817, self.amt=12514264.7657, ukdf['pct'].iloc[-1]=0.000636 , ukdf['amount'].iloc[-1]=12514264.7657, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14586.05696710338', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25817.50254437', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31922 

self.closeSec=1693612799, self.tradeDate='20230902', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25808.4, self.close=25795.7, self.high=25808.4, self.low=25787.6 
127.0.0.1 - - [02/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31923 

self.closeSec=1693613099, self.tradeDate='20230902', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25795.6, self.close=25792.4, self.high=25801.4, self.low=25788.8 
127.0.0.1 - - [02/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31924 

self.closeSec=1693613399, self.tradeDate='20230902', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25792.3, self.close=25791.1, self.high=25792.9, self.low=25777.7 
127.0.0.1 - - [02/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31925 

self.closeSec=1693613699, self.tradeDate='20230902', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25791.0, self.close=25796.8, self.high=25800.3, self.low=25785.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31926 

self.closeSec=1693613999, self.tradeDate='20230902', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25796.8, self.close=25797.9, self.high=25799.3, self.low=25790.0 
127.0.0.1 - - [02/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31927 

self.closeSec=1693614299, self.tradeDate='20230902', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25798.0, self.close=25814.3, self.high=25820.0, self.low=25797.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-02 08:00:17,821:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230902    052959  25763.5  ...  43.750000  0.407969  0.653192
5770  20230902    055959  25743.1  ...  44.166667  0.417828  0.638191
5771  20230902    062959  25792.1  ...  44.583333  0.418996  0.623730
5772  20230902    065959  25796.4  ...  44.166667  0.412012  0.614044
5773  20230902    072959  25750.0  ...  44.166667  0.420776  0.601614

[5 rows x 33 columns]
0.512962962962963
acc is : 0.512962962962963
2023-09-02 08:00:17,882:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.486267  0.513733       1  ...  1.006475  -1.0    0.0  0.990518
536     0  0.513475  0.486525       1  ...  1.006249  -1.0    0.0  0.990741
537     0  0.507723  0.492277       0  ...  1.008121  -1.0    0.0  0.988897
538     1  0.491002  0.508998       1  ...  1.006450  -1.0    0.0  0.990537
539     0  0.513153  0.486847       1  ...  1.006332  -1.0    0.0  0.990652

[5 rows x 10 columns]
2023-09-02 08:00:17,893:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486224  0.513776       1  ...  1.006475  -1.0    0.0  0.994866
46     0  0.513331  0.486669       1  ...  1.006249  -1.0    0.0  0.992651
47     0  0.507380  0.492620       0  ...  1.008121  -1.0    0.0  0.990305
48     1  0.490640  0.509360       1  ...  1.006450  -1.0    0.0  0.990081
49     0  0.513153  0.486847       1  ...  1.006332  -1.0    0.0  0.990652

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '23279.5232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25796.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15959 

self.closeSec=1693610999, self.tradeDate='20230902', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25787.6', self.close='25792.6'
127.0.0.1 - - [02/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [02/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15960 

self.closeSec=1693611599, self.tradeDate='20230902', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25792.6', self.close='25811.5'
127.0.0.1 - - [02/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15961 

self.closeSec=1693612199, self.tradeDate='20230902', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25811.5', self.close='25822.4'
127.0.0.1 - - [02/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15962 

self.closeSec=1693612799, self.tradeDate='20230902', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25822.4', self.close='25795.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15963 

self.closeSec=1693613399, self.tradeDate='20230902', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25795.6', self.close='25791'
127.0.0.1 - - [02/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15964 

self.closeSec=1693613999, self.tradeDate='20230902', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25791', self.close='25797.9'
127.0.0.1 - - [02/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [02/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15962 

self.closeSec=1693610999, self.tradeDate='20230902', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25787.6', self.close='25792.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15963 

self.closeSec=1693611599, self.tradeDate='20230902', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25792.6', self.close='25811.5'
127.0.0.1 - - [02/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15964 

self.closeSec=1693612199, self.tradeDate='20230902', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25811.5', self.close='25822.4'
127.0.0.1 - - [02/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15965 

self.closeSec=1693612799, self.tradeDate='20230902', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25822.4', self.close='25795.6'
127.0.0.1 - - [02/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15966 

self.closeSec=1693613399, self.tradeDate='20230902', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25795.6', self.close='25791'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15967 

self.closeSec=1693613999, self.tradeDate='20230902', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25791', self.close='25797.9'
127.0.0.1 - - [02/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [02/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15962 

self.closeSec=1693610999, self.tradeDate='20230902', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25787.6', self.close='25792.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15963 

self.closeSec=1693611599, self.tradeDate='20230902', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25792.6', self.close='25811.5'
127.0.0.1 - - [02/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15964 

self.closeSec=1693612199, self.tradeDate='20230902', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25811.5', self.close='25822.4'
127.0.0.1 - - [02/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15965 

self.closeSec=1693612799, self.tradeDate='20230902', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25822.4', self.close='25795.6'
127.0.0.1 - - [02/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15966 

self.closeSec=1693613399, self.tradeDate='20230902', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25795.6', self.close='25791'
127.0.0.1 - - [02/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15967 

self.closeSec=1693613999, self.tradeDate='20230902', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25791', self.close='25797.9'
127.0.0.1 - - [02/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31924
self.closeSec=1693613999, self.tradeDate='20230902', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25796.8, self.close=25797.9, self.high=25799.3, self.low=25790.0, self.vol=148.788, self.amt=3838191.9783 
127.0.0.1 - - [02/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-09-02 08:20:05,261:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230902   075500    075959  ...         0.0        0.0       0
5844  20230902   080000    080459  ...         0.0        0.0       0
5845  20230902   080500    080959  ...         0.0        0.0       0
5846  20230902   081000    081459  ...         0.0        0.0       0
5847  20230902   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 08:20:05,265:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693613999, self.tradeDate='20230902', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25796.8, self.close=25797.9, self.high=25799.3, self.low=25790.0, self.vol=148.788, self.amt=3838191.9783, ukdf['pct'].iloc[-1]=4.3e-05 , ukdf['amount'].iloc[-1]=3838191.9783, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38849.486', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25798', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31925
self.closeSec=1693614299, self.tradeDate='20230902', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25798.0, self.close=25814.3, self.high=25820.0, self.low=25797.9, self.vol=484.817, self.amt=12514264.7657 
2023-09-02 08:25:00,784:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230902   080000    080459  ...         0.0        0.0       0
5845  20230902   080500    080959  ...         0.0        0.0       0
5846  20230902   081000    081459  ...         0.0        0.0       0
5847  20230902   081500    081959  ...         0.0        0.0       0
5848  20230902   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 08:25:00,785:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693614299, self.tradeDate='20230902', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25798.0, self.close=25814.3, self.high=25820.0, self.low=25797.9, self.vol=484.817, self.amt=12514264.7657, ukdf['pct'].iloc[-1]=0.000636 , ukdf['amount'].iloc[-1]=12514264.7657, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38125.14199955383', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25817.50254437', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230901   200000    235959  1693583999  ...    719  0.627829  0.863870     1.0
720  20230902   000000    035959  1693598399  ...    720  0.605634  0.790027     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-125668.14', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25638.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [02/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=665
self.closeSec=1693612799, self.tradeDate='20230902', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25637.2, self.close=25795.6, self.high=25928.5, self.low=25557.3, self.vol=37989.932, self.amt=979065651.47218 
2023-09-02 08:00:01,574:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693612799, self.tradeDate='20230902', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25637.2, self.close=25795.6, self.high=25928.5, self.low=25557.3, self.vol=37989.932, self.amt=979065651.47218 
2023-09-02 08:00:01,588:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230901   120000    155959  ...   18796.654  4.888930e+08 -0.003694
718  20230901   160000    195959  ...   23768.858  6.180220e+08  0.002252
719  20230901   200000    235959  ...  118639.495  3.069677e+09 -0.009054
720  20230902   000000    035959  ...  134918.148  3.454822e+09 -0.006237
721  20230902   040000    075959  ...   37989.932  9.790657e+08  0.006182

[5 rows x 11 columns]
2023-09-02 08:00:02,401:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230901   120000    155959  1693555199  ...    717  0.673651  1.030149     1.0
718  20230901   160000    195959  1693569599  ...    718  0.671384  1.012377     1.0
719  20230901   200000    235959  1693583999  ...    719  0.627829  0.863870     1.0
720  20230902   000000    035959  1693598399  ...    720  0.605634  0.790027     1.0
721  20230902   040000    075959  1693612799  ...    721  0.614138  0.799056     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-116691.0264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25795.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


