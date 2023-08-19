# 20230819 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27892
self.closeSec=1692404399, self.tradeDate='20230819', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26061.7, self.close=26035.4, self.high=26061.7, self.low=26034.2, self.vol=529.506, self.amt=13791831.1223 
127.0.0.1 - - [19/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-19 08:20:04,950:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230819   075500    075959  ...         0.0        0.0       0
5844  20230819   080000    080459  ...         0.0        0.0       0
5845  20230819   080500    080959  ...         0.0        0.0       0
5846  20230819   081000    081459  ...         0.0        0.0       0
5847  20230819   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 08:20:04,960:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692404399, self.tradeDate='20230819', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26061.7, self.close=26035.4, self.high=26061.7, self.low=26034.2, self.vol=529.506, self.amt=13791831.1223, ukdf['pct'].iloc[-1]=-0.001009 , ukdf['amount'].iloc[-1]=13791831.1223, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11543.6991763434', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26035.9685641', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27893
self.closeSec=1692404699, self.tradeDate='20230819', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26035.5, self.close=26017.6, self.high=26035.5, self.low=26012.2, self.vol=539.255, self.amt=14032685.8888 
2023-08-19 08:25:00,848:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230819   080000    080459  ...         0.0        0.0       0
5845  20230819   080500    080959  ...         0.0        0.0       0
5846  20230819   081000    081459  ...         0.0        0.0       0
5847  20230819   081500    081959  ...         0.0        0.0       0
5848  20230819   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 08:25:00,849:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692404699, self.tradeDate='20230819', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26035.5, self.close=26017.6, self.high=26035.5, self.low=26012.2, self.vol=539.255, self.amt=14032685.8888, ukdf['pct'].iloc[-1]=-0.000684 , ukdf['amount'].iloc[-1]=14032685.8888, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11799.4998', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26017.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [19/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27890 

self.closeSec=1692403199, self.tradeDate='20230819', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26050.2, self.close=26042.0, self.high=26050.3, self.low=26030.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27891 

self.closeSec=1692403499, self.tradeDate='20230819', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26042.0, self.close=26064.2, self.high=26064.2, self.low=26036.3 
127.0.0.1 - - [19/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27892 

self.closeSec=1692403799, self.tradeDate='20230819', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26064.2, self.close=26070.7, self.high=26070.8, self.low=26054.0 
127.0.0.1 - - [19/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27893 

self.closeSec=1692404099, self.tradeDate='20230819', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26070.8, self.close=26061.7, self.high=26071.7, self.low=26052.8 
127.0.0.1 - - [19/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27894 

self.closeSec=1692404399, self.tradeDate='20230819', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26061.7, self.close=26035.4, self.high=26061.7, self.low=26034.2 
127.0.0.1 - - [19/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27895 

self.closeSec=1692404699, self.tradeDate='20230819', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26035.5, self.close=26017.6, self.high=26035.5, self.low=26012.2 
127.0.0.1 - - [19/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-19 08:00:16,429:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230819    052959  26072.6  ...  43.750000  0.354590  0.572278
5770  20230819    055959  26112.2  ...  43.750000  0.348737  0.572772
5771  20230819    062959  26050.2  ...  44.166667  0.353872  0.569217
5772  20230819    065959  26080.1  ...  44.166667  0.351526  0.567519
5773  20230819    072959  26055.1  ...  44.166667  0.347675  0.568594

[5 rows x 33 columns]
0.5222222222222223
acc is : 0.5222222222222223
2023-08-19 08:00:16,489:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.456171  0.543829       0  ...  1.113149  -1.0    0.0  0.901975
536     1  0.429913  0.570087       1  ...  1.111896  -1.0    0.0  0.902989
537     1  0.467732  0.532268       0  ...  1.112933  -1.0    0.0  0.902148
538     1  0.430363  0.569637       0  ...  1.114633  -1.0    0.0  0.900770
539     1  0.430672  0.569328       1  ...  1.113493  -1.0    0.0  0.901691

[5 rows x 10 columns]
2023-08-19 08:00:16,501:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.455971  0.544029       0  ...  1.113149  -1.0    0.0  0.900528
46     1  0.429994  0.570006       1  ...  1.111896  -1.0    0.0  0.903869
47     1  0.467566  0.532434       0  ...  1.112933  -1.0    0.0  0.901149
48     1  0.429882  0.570118       0  ...  1.114633  -1.0    0.0  0.899244
49     1  0.430672  0.569328       1  ...  1.113493  -1.0    0.0  0.901691

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.207', 'enterprice': '29084.9', 'countrevence': '0', 'unrealprofit': '73635.2733', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26043', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [19/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13943 

self.closeSec=1692401399, self.tradeDate='20230819', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26021.7', self.close='26015.4'
127.0.0.1 - - [19/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13944 

self.closeSec=1692401999, self.tradeDate='20230819', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26015.4', self.close='26023.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13945 

self.closeSec=1692402599, self.tradeDate='20230819', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26023.9', self.close='26047.5'
127.0.0.1 - - [19/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13946 

self.closeSec=1692403199, self.tradeDate='20230819', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26047.5', self.close='26042.1'
127.0.0.1 - - [19/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13947 

self.closeSec=1692403799, self.tradeDate='20230819', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26042', self.close='26070.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13948 

self.closeSec=1692404399, self.tradeDate='20230819', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26070.8', self.close='26035.4'
127.0.0.1 - - [19/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [19/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13946 

self.closeSec=1692401399, self.tradeDate='20230819', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26021.7', self.close='26015.4'
127.0.0.1 - - [19/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13947 

self.closeSec=1692401999, self.tradeDate='20230819', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26015.4', self.close='26023.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13948 

self.closeSec=1692402599, self.tradeDate='20230819', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26023.9', self.close='26047.5'
127.0.0.1 - - [19/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13949 

self.closeSec=1692403199, self.tradeDate='20230819', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26047.5', self.close='26042.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13950 

self.closeSec=1692403799, self.tradeDate='20230819', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26042', self.close='26070.7'
127.0.0.1 - - [19/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13951 

self.closeSec=1692404399, self.tradeDate='20230819', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26070.8', self.close='26035.4'
127.0.0.1 - - [19/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [19/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13946 

self.closeSec=1692401399, self.tradeDate='20230819', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26021.7', self.close='26015.4'
127.0.0.1 - - [19/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13947 

self.closeSec=1692401999, self.tradeDate='20230819', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26015.4', self.close='26023.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13948 

self.closeSec=1692402599, self.tradeDate='20230819', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26023.9', self.close='26047.5'
127.0.0.1 - - [19/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13949 

self.closeSec=1692403199, self.tradeDate='20230819', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26047.5', self.close='26042.1'
127.0.0.1 - - [19/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13950 

self.closeSec=1692403799, self.tradeDate='20230819', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26042', self.close='26070.7'
127.0.0.1 - - [19/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13951 

self.closeSec=1692404399, self.tradeDate='20230819', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26070.8', self.close='26035.4'
127.0.0.1 - - [19/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27892
self.closeSec=1692404399, self.tradeDate='20230819', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26061.7, self.close=26035.4, self.high=26061.7, self.low=26034.2, self.vol=529.506, self.amt=13791831.1223 
127.0.0.1 - - [19/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-19 08:20:04,948:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230819   075500    075959  ...         0.0        0.0       0
5844  20230819   080000    080459  ...         0.0        0.0       0
5845  20230819   080500    080959  ...         0.0        0.0       0
5846  20230819   081000    081459  ...         0.0        0.0       0
5847  20230819   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 08:20:04,959:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692404399, self.tradeDate='20230819', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26061.7, self.close=26035.4, self.high=26061.7, self.low=26034.2, self.vol=529.506, self.amt=13791831.1223, ukdf['pct'].iloc[-1]=-0.001009 , ukdf['amount'].iloc[-1]=13791831.1223, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-30011.0955607619', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26035.9685641', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [19/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27893
self.closeSec=1692404699, self.tradeDate='20230819', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26035.5, self.close=26017.6, self.high=26035.5, self.low=26012.2, self.vol=539.255, self.amt=14032685.8888 
2023-08-19 08:25:00,805:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230819   080000    080459  ...         0.0        0.0       0
5845  20230819   080500    080959  ...         0.0        0.0       0
5846  20230819   081000    081459  ...         0.0        0.0       0
5847  20230819   081500    081959  ...         0.0        0.0       0
5848  20230819   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-19 08:25:00,805:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692404699, self.tradeDate='20230819', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26035.5, self.close=26017.6, self.high=26035.5, self.low=26012.2, self.vol=539.255, self.amt=14032685.8888, ukdf['pct'].iloc[-1]=-0.000684 , ukdf['amount'].iloc[-1]=14032685.8888, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-30693.3224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26017.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230818   200000    235959  1692374399  ...    719  0.364333 -0.301664     NaN
720  20230819   000000    035959  1692388799  ...    720  0.401023 -0.218074     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '173655.4684', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26053.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=581
self.closeSec=1692403199, self.tradeDate='20230819', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26053.4, self.close=26042.1, self.high=26235.0, self.low=25989.5, self.vol=36849.478, self.amt=961892930.6829 
127.0.0.1 - - [19/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-19 08:00:01,566:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692403199, self.tradeDate='20230819', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26053.4, self.close=26042.1, self.high=26235.0, self.low=25989.5, self.vol=36849.478, self.amt=961892930.6829 
2023-08-19 08:00:01,580:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230818   120000    155959  ...   75859.899  2.001522e+09  0.001232
718  20230818   160000    195959  ...   49121.525  1.300346e+09  0.002309
719  20230818   200000    235959  ...  130570.320  3.418381e+09 -0.018369
720  20230819   000000    035959  ...  151020.850  3.919715e+09  0.002320
721  20230819   040000    075959  ...   36849.478  9.618929e+08 -0.000434

[5 rows x 11 columns]
2023-08-19 08:00:02,339:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230818   120000    155959  1692345599  ...    717  0.259513 -0.542461     NaN
718  20230818   160000    195959  1692359999  ...    718  0.315037 -0.414487     NaN
719  20230818   200000    235959  1692374399  ...    719  0.364333 -0.301664     NaN
720  20230819   000000    035959  1692388799  ...    720  0.401023 -0.218074     NaN
721  20230819   040000    075959  1692403199  ...    721  0.431456 -0.149531     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174236.1528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26042', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


