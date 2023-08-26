# 20230826 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29908
self.closeSec=1693009199, self.tradeDate='20230826', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26043.6, self.close=26049.1, self.high=26050.8, self.low=26036.6, self.vol=233.686, self.amt=6086199.4785 
127.0.0.1 - - [26/Aug/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-08-26 08:20:05,479:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230826   075500    075959  ...         0.0        0.0       0
5844  20230826   080000    080459  ...         0.0        0.0       0
5845  20230826   080500    080959  ...         0.0        0.0       0
5846  20230826   081000    081459  ...         0.0        0.0       0
5847  20230826   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 08:20:05,493:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693009199, self.tradeDate='20230826', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26043.6, self.close=26049.1, self.high=26050.8, self.low=26036.6, self.vol=233.686, self.amt=6086199.4785, ukdf['pct'].iloc[-1]=0.000211 , ukdf['amount'].iloc[-1]=6086199.4785, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11360.8308', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26049.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29909
self.closeSec=1693009499, self.tradeDate='20230826', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26049.0, self.close=26055.4, self.high=26055.5, self.low=26048.1, self.vol=209.92, self.amt=5468939.8021 
2023-08-26 08:25:00,782:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230826   080000    080459  ...         0.0        0.0       0
5845  20230826   080500    080959  ...         0.0        0.0       0
5846  20230826   081000    081459  ...         0.0        0.0       0
5847  20230826   081500    081959  ...         0.0        0.0       0
5848  20230826   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 08:25:00,783:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693009499, self.tradeDate='20230826', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26049.0, self.close=26055.4, self.high=26055.5, self.low=26048.1, self.vol=209.92, self.amt=5468939.8021, ukdf['pct'].iloc[-1]=0.000242 , ukdf['amount'].iloc[-1]=5468939.8021, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11261.9562', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26056.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29906 

self.closeSec=1693007999, self.tradeDate='20230826', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26048.5, self.close=26051.8, self.high=26053.9, self.low=26045.7 
127.0.0.1 - - [26/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29907 

self.closeSec=1693008299, self.tradeDate='20230826', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26051.7, self.close=26040.1, self.high=26054.0, self.low=26040.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29908 

self.closeSec=1693008599, self.tradeDate='20230826', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26040.2, self.close=26038.2, self.high=26040.2, self.low=26035.0 
127.0.0.1 - - [26/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29909 

self.closeSec=1693008899, self.tradeDate='20230826', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26038.2, self.close=26043.6, self.high=26050.0, self.low=26038.1 
127.0.0.1 - - [26/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29910 

self.closeSec=1693009199, self.tradeDate='20230826', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26043.6, self.close=26049.1, self.high=26050.8, self.low=26036.6 
127.0.0.1 - - [26/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29911 

self.closeSec=1693009499, self.tradeDate='20230826', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26049.0, self.close=26055.4, self.high=26055.5, self.low=26048.1 
127.0.0.1 - - [26/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-26 08:00:18,735:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230826    052959  26045.9  ...  49.583333  0.482263  0.564222
5770  20230826    055959  26020.4  ...  50.000000  0.492850  0.554919
5771  20230826    062959  26068.4  ...  49.583333  0.485797  0.550317
5772  20230826    065959  26034.8  ...  50.000000  0.487768  0.544946
5773  20230826    072959  26043.6  ...  50.000000  0.483896  0.542133

[5 rows x 33 columns]
0.5296296296296297
acc is : 0.5296296296296297
2023-08-26 08:00:18,797:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.482845  0.517155       1  ...  1.070157  -1.0    0.0  0.882355
536     0  0.514999  0.485001       0  ...  1.071528  -1.0    0.0  0.881225
537     1  0.487046  0.512954       1  ...  1.071166  -1.0    0.0  0.881522
538     1  0.495062  0.504938       0  ...  1.071906  -1.0    0.0  0.880913
539     1  0.486431  0.513569       1  ...  1.070831  -1.0    0.0  0.881797

[5 rows x 10 columns]
2023-08-26 08:00:18,809:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.482875  0.517125       1  ...  1.051479  -1.0    0.0  0.879666
46     0  0.514893  0.485107       0  ...  1.071528  -1.0    0.0  0.879768
47     1  0.486946  0.513054       1  ...  1.071166  -1.0    0.0  0.878581
48     1  0.495024  0.504976       0  ...  1.071906  -1.0    0.0  0.878104
49     1  0.486431  0.513569       1  ...  1.070831  -1.0    0.0  0.881797

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '9838.5035', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26053.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14951 

self.closeSec=1693006199, self.tradeDate='20230826', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26032.1', self.close='26025.7'
127.0.0.1 - - [26/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14952 

self.closeSec=1693006799, self.tradeDate='20230826', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26025.7', self.close='26024.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14953 

self.closeSec=1693007399, self.tradeDate='20230826', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26024.1', self.close='26032.9'
127.0.0.1 - - [26/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14954 

self.closeSec=1693007999, self.tradeDate='20230826', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26032.9', self.close='26051.7'
127.0.0.1 - - [26/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14955 

self.closeSec=1693008599, self.tradeDate='20230826', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26051.7', self.close='26038.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14956 

self.closeSec=1693009199, self.tradeDate='20230826', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26038.2', self.close='26049.1'
127.0.0.1 - - [26/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14954 

self.closeSec=1693006199, self.tradeDate='20230826', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26032.1', self.close='26025.7'
127.0.0.1 - - [26/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14955 

self.closeSec=1693006799, self.tradeDate='20230826', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26025.7', self.close='26024.1'
127.0.0.1 - - [26/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14956 

self.closeSec=1693007399, self.tradeDate='20230826', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26024.1', self.close='26032.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14957 

self.closeSec=1693007999, self.tradeDate='20230826', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26032.9', self.close='26051.7'
127.0.0.1 - - [26/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14958 

self.closeSec=1693008599, self.tradeDate='20230826', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26051.7', self.close='26038.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14959 

self.closeSec=1693009199, self.tradeDate='20230826', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26038.2', self.close='26049.1'
127.0.0.1 - - [26/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14954 

self.closeSec=1693006199, self.tradeDate='20230826', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26032.1', self.close='26025.7'
127.0.0.1 - - [26/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [26/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14955 

self.closeSec=1693006799, self.tradeDate='20230826', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26025.7', self.close='26024.1'

--handleKline--: 127.0.0.1 - - [26/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14956 

self.closeSec=1693007399, self.tradeDate='20230826', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26024.1', self.close='26032.9'
127.0.0.1 - - [26/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14957 

self.closeSec=1693007999, self.tradeDate='20230826', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26032.9', self.close='26051.7'
127.0.0.1 - - [26/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14958 

self.closeSec=1693008599, self.tradeDate='20230826', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26051.7', self.close='26038.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14959 

self.closeSec=1693009199, self.tradeDate='20230826', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26038.2', self.close='26049.1'
127.0.0.1 - - [26/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29908
self.closeSec=1693009199, self.tradeDate='20230826', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26043.6, self.close=26049.1, self.high=26050.8, self.low=26036.6, self.vol=233.686, self.amt=6086199.4785 
127.0.0.1 - - [26/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-26 08:20:05,477:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230826   075500    075959  ...         0.0        0.0       0
5844  20230826   080000    080459  ...         0.0        0.0       0
5845  20230826   080500    080959  ...         0.0        0.0       0
5846  20230826   081000    081459  ...         0.0        0.0       0
5847  20230826   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 08:20:05,481:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693009199, self.tradeDate='20230826', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26043.6, self.close=26049.1, self.high=26050.8, self.low=26036.6, self.vol=233.686, self.amt=6086199.4785, ukdf['pct'].iloc[-1]=0.000211 , ukdf['amount'].iloc[-1]=6086199.4785, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29523.3809', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26049.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29909
self.closeSec=1693009499, self.tradeDate='20230826', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26049.0, self.close=26055.4, self.high=26055.5, self.low=26048.1, self.vol=209.92, self.amt=5468939.8021 
2023-08-26 08:25:00,783:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230826   080000    080459  ...         0.0        0.0       0
5845  20230826   080500    080959  ...         0.0        0.0       0
5846  20230826   081000    081459  ...         0.0        0.0       0
5847  20230826   081500    081959  ...         0.0        0.0       0
5848  20230826   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 08:25:00,783:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693009499, self.tradeDate='20230826', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26049.0, self.close=26055.4, self.high=26055.5, self.low=26048.1, self.vol=209.92, self.amt=5468939.8021, ukdf['pct'].iloc[-1]=0.000242 , ukdf['amount'].iloc[-1]=5468939.8021, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29259.6798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26056.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230825   200000    235959  1692979199  ...    719  0.159068 -0.535499     NaN
720  20230826   000000    035959  1692993599  ...    720  0.172074 -0.485241     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '178299.13692587612', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25962.93515751', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=623
self.closeSec=1693007999, self.tradeDate='20230826', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25961.8, self.close=26051.7, self.high=26078.0, self.low=25944.4, self.vol=17754.194, self.amt=462176213.04896 
127.0.0.1 - - [26/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-26 08:00:01,598:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693007999, self.tradeDate='20230826', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25961.8, self.close=26051.7, self.high=26078.0, self.low=25944.4, self.vol=17754.194, self.amt=462176213.04896 
2023-08-26 08:00:01,613:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230825   120000    155959  ...   28254.409  7.352599e+08 -0.004817
718  20230825   160000    195959  ...   23053.719  6.011113e+08  0.004555
719  20230825   200000    235959  ...  138297.912  3.598672e+09 -0.006528
720  20230826   000000    035959  ...   45731.022  1.186422e+09  0.001717
721  20230826   040000    075959  ...   17754.194  4.621762e+08  0.003459

[5 rows x 11 columns]
2023-08-26 08:00:02,387:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230825   120000    155959  1692950399  ...    717  0.195809 -0.474029     NaN
718  20230825   160000    195959  1692964799  ...    718  0.195125 -0.459209     NaN
719  20230825   200000    235959  1692979199  ...    719  0.159068 -0.535499     NaN
720  20230826   000000    035959  1692993599  ...    720  0.172074 -0.485241     NaN
721  20230826   040000    075959  1693007999  ...    721  0.169228 -0.477095     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '173773.6608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26051', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


