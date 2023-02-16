# 20230216 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23260
self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24608.1, self.close=24813.4, self.high=24863.0, self.low=24604.6, self.vol=17813.697, self.amt=440849153.02471 
127.0.0.1 - - [16/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-16 08:20:01,627:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230216   075500    075959  ...         0.0        0.0       0
5856  20230216   080000    080459  ...         0.0        0.0       0
5857  20230216   080500    080959  ...         0.0        0.0       0
5858  20230216   081000    081459  ...         0.0        0.0       0
5859  20230216   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 08:20:01,633:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24608.1, self.close=24813.4, self.high=24863.0, self.low=24604.6, self.vol=17813.697, self.amt=440849153.02471, ukdf['pct'].iloc[-1]=0.008347 , ukdf['amount'].iloc[-1]=440849153.02471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-498495.4952018776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24813.25864135', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23261
self.closeSec=1676507099, self.tradeDate='20230216', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24813.4, self.close=24798.6, self.high=24934.1, self.low=24766.5, self.vol=14366.269, self.amt=357000684.0221 
2023-02-16 08:25:01,639:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230216   080000    080459  ...         0.0        0.0       0
5857  20230216   080500    080959  ...         0.0        0.0       0
5858  20230216   081000    081459  ...         0.0        0.0       0
5859  20230216   081500    081959  ...         0.0        0.0       0
5860  20230216   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 08:25:01,640:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676507099, self.tradeDate='20230216', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24813.4, self.close=24798.6, self.high=24934.1, self.low=24766.5, self.vol=14366.269, self.amt=357000684.0221, ukdf['pct'].iloc[-1]=-0.000596 , ukdf['amount'].iloc[-1]=357000684.0221, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-497523.1328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24797.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24608.1, self.close=24813.4, self.high=24863.0, self.low=24604.6 
127.0.0.1 - - [16/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-16 08:20:01,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24608.1, self.close=24813.4, self.high=24863.0, self.low=24604.6   
2023-02-16 08:20:01,556:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230216   075500    075959  1676505599  ...  24313.3 -0.000296   1535    5
1536  20230216   080000    080459  1676505899  ...  24287.0  0.000366   1536    0
1537  20230216   080500    080959  1676506199  ...  24336.2  0.003106   1537    1
1538  20230216   081000    081459  1676506499  ...  24384.4  0.007818   1538    2
1539  20230216   081500    081959  1676506799  ...  24604.6  0.008347   1539    3

[5 rows x 11 columns]
2023-02-16 08:20:01,556:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=55, self.factor=0.16678335144171955, self.count=23827 

self.closeSec=1676507099, self.tradeDate='20230216', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24813.4, self.close=24798.6, self.high=24934.1, self.low=24766.5 
2023-02-16 08:25:01,508:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676507099, self.tradeDate='20230216', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24813.4, self.close=24798.6, self.high=24934.1, self.low=24766.5   
127.0.0.1 - - [16/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-16 08:25:01,599:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230216   080000    080459  1676505899  ...  24287.0  0.000366   1536    0
1537  20230216   080500    080959  1676506199  ...  24336.2  0.003106   1537    1
1538  20230216   081000    081459  1676506499  ...  24384.4  0.007818   1538    2
1539  20230216   081500    081959  1676506799  ...  24604.6  0.008347   1539    3
1540  20230216   082000    082459  1676507099  ...  24766.5 -0.000596   1540    4

[5 rows x 11 columns]
2023-02-16 08:25:01,601:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-16 08:00:33,200:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230216    052959  24144.8  ...  51.666667  0.784543  0.150660
5771  20230216    055959  24100.0  ...  52.083333  0.789972  0.145676
5772  20230216    062959  24181.0  ...  52.083333  0.794778  0.140595
5773  20230216    065959  24254.6  ...  51.666667  0.770599  0.138687
5774  20230216    072959  24155.6  ...  51.666667  0.780335  0.132920

[5 rows x 33 columns]
0.5231053604436229
acc is : 0.5231053604436229
2023-02-16 08:00:33,388:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.614054  0.385946       1  ...  1.136004   1.0    0.0  1.032110
537     0  0.616727  0.383273       1  ...  1.139462   1.0    0.0  1.035252
538     0  0.613384  0.386616       0  ...  1.134816   1.0    0.0  1.031030
539     0  0.532474  0.467526       1  ...  1.141449   1.0    0.0  1.037057
540     0  0.558117  0.441883       1  ...  1.143126   1.0    0.0  1.038581

[5 rows x 10 columns]
2023-02-16 08:00:33,412:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.614624  0.385376       1  ...  1.136004   1.0    0.0  1.032489
46     0  0.616817  0.383183       1  ...  1.139462   1.0    0.0  1.035305
47     0  0.613805  0.386195       0  ...  1.134816   1.0    0.0  1.031810
48     0  0.532474  0.467526       1  ...  1.141449   1.0    0.0  1.037057
49     0  0.558117  0.441883       1  ...  1.143126   1.0    0.0  1.038581

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.557', 'enterprice': '21695.5', 'countrevence': '0', 'unrealprofit': '94709.17022080611', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24359.08720423', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230216   075000    075959  1676505599  24309.9  24332.6  0.000934
2023-02-16 08:00:02,087:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11912 

self.closeSec=1676506199, self.tradeDate='20230216', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24332.7', self.close='24417.1'
2023-02-16 08:10:01,658:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676506199, self.tradeDate='20230216', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24332.7', self.close='24417.1'
127.0.0.1 - - [16/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-16 08:10:01,681:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230216   072000    072959  1676503799    24264  24296.9  0.001723
621  20230216   073000    073959  1676504399  24296.9  24284.4 -0.000514
622  20230216   074000    074959  1676504999  24284.5  24309.9  0.001050
623  20230216   075000    075959  1676505599  24309.9  24332.6  0.000934
624  20230216   080000    080959  1676506199  24332.7  24417.1  0.003473
2023-02-16 08:10:01,683:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11913 

self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24413.6', self.close='24813.4'
127.0.0.1 - - [16/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-16 08:20:01,610:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24413.6', self.close='24813.4'
2023-02-16 08:20:01,637:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230216   073000    073959  1676504399  24296.9  24284.4 -0.000514
622  20230216   074000    074959  1676504999  24284.5  24309.9  0.001050
623  20230216   075000    075959  1676505599  24309.9  24332.6  0.000934
624  20230216   080000    080959  1676506199  24332.7  24417.1  0.003473
625  20230216   081000    081959  1676506799  24413.6  24813.4  0.016230
2023-02-16 08:20:01,637:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 07:00:01] "POST / HTTP/1.1" 200 -
2023-02-16 07:00:03,312:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/16 04:30:00  043000  24146.1  ...     NaN     NaN       0
145  2023/02/16 05:00:00  050000  24100.2  ...     NaN     NaN       0
146  2023/02/16 05:30:00  053000  24181.0  ...     NaN     NaN       0
147  2023/02/16 06:00:00  060000  24254.6  ...     NaN     NaN       0
148  2023/02/16 06:30:00  063000  24155.7  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [16/Feb/2023 07:30:01] "POST / HTTP/1.1" 200 -
2023-02-16 07:30:02,388:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/16 05:00:00  050000  24100.2  ...     NaN     NaN       0
145  2023/02/16 05:30:00  053000  24181.0  ...     NaN     NaN       0
146  2023/02/16 06:00:00  060000  24254.6  ...     NaN     NaN       0
147  2023/02/16 06:30:00  063000  24155.7  ...     NaN     NaN       0
148  2023/02/16 07:00:00  070000  24296.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [16/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-16 08:00:02,872:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/16 05:30:00  053000  24181.0  ...     NaN     NaN       0
145  2023/02/16 06:00:00  060000  24254.6  ...     NaN     NaN       0
146  2023/02/16 06:30:00  063000  24155.7  ...     NaN     NaN       0
147  2023/02/16 07:00:00  070000  24296.9  ...     NaN     NaN       0
148  2023/02/16 07:30:00  073000  24332.6  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17471  20230216   075000    075959  1676505599  24309.9  24332.6
2023-02-16 08:00:02,088:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11913 

self.closeSec=1676506199, self.tradeDate='20230216', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24332.7', self.close='24417.1'
2023-02-16 08:10:01,627:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676506199, self.tradeDate='20230216', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24332.7', self.close='24417.1'
2023-02-16 08:10:01,697:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230216   072000    072959  1676503799    24264  24296.9
17469  20230216   073000    073959  1676504399  24296.9  24284.4
17470  20230216   074000    074959  1676504999  24284.5  24309.9
17471  20230216   075000    075959  1676505599  24309.9  24332.6
17472  20230216   080000    080959  1676506199  24332.7  24417.1
2023-02-16 08:10:01,701:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11914 

self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24413.6', self.close='24813.4'
2023-02-16 08:20:01,643:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24413.6', self.close='24813.4'
2023-02-16 08:20:01,675:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230216   073000    073959  1676504399  24296.9  24284.4
17470  20230216   074000    074959  1676504999  24284.5  24309.9
17471  20230216   075000    075959  1676505599  24309.9  24332.6
17472  20230216   080000    080959  1676506199  24332.7  24417.1
17473  20230216   081000    081959  1676506799  24413.6  24813.4
2023-02-16 08:20:01,675:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230216   075000    075959  1676505599  24309.9  24332.6
2023-02-16 08:00:02,091:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11913 

self.closeSec=1676506199, self.tradeDate='20230216', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24332.7', self.close='24417.1'
2023-02-16 08:10:01,609:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676506199, self.tradeDate='20230216', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24332.7', self.close='24417.1'
2023-02-16 08:10:01,692:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230216   072000    072959  1676503799    24264  24296.9
12141  20230216   073000    073959  1676504399  24296.9  24284.4
12142  20230216   074000    074959  1676504999  24284.5  24309.9
12143  20230216   075000    075959  1676505599  24309.9  24332.6
12144  20230216   080000    080959  1676506199  24332.7  24417.1
2023-02-16 08:10:01,692:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11914 

self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24413.6', self.close='24813.4'
2023-02-16 08:20:01,642:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24413.6', self.close='24813.4'
2023-02-16 08:20:01,665:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230216   073000    073959  1676504399  24296.9  24284.4
12142  20230216   074000    074959  1676504999  24284.5  24309.9
12143  20230216   075000    075959  1676505599  24309.9  24332.6
12144  20230216   080000    080959  1676506199  24332.7  24417.1
12145  20230216   081000    081959  1676506799  24413.6  24813.4
2023-02-16 08:20:01,665:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19258
self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24608.1, self.close=24813.4, self.high=24863.0, self.low=24604.6, self.vol=17813.697, self.amt=440849153.02471 
2023-02-16 08:20:01,636:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230216   075500    075959  ...         0.0        0.0       0
5856  20230216   080000    080459  ...         0.0        0.0       0
5857  20230216   080500    080959  ...         0.0        0.0       0
5858  20230216   081000    081459  ...         0.0        0.0       0
5859  20230216   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 08:20:01,636:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676506799, self.tradeDate='20230216', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24608.1, self.close=24813.4, self.high=24863.0, self.low=24604.6, self.vol=17813.697, self.amt=440849153.02471, ukdf['pct'].iloc[-1]=0.008347 , ukdf['amount'].iloc[-1]=440849153.02471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19259
self.closeSec=1676507099, self.tradeDate='20230216', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24813.4, self.close=24798.6, self.high=24934.1, self.low=24766.5, self.vol=14366.269, self.amt=357000684.0221 
2023-02-16 08:25:01,634:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230216   080000    080459  ...         0.0        0.0       0
5857  20230216   080500    080959  ...         0.0        0.0       0
5858  20230216   081000    081459  ...         0.0        0.0       0
5859  20230216   081500    081959  ...         0.0        0.0       0
5860  20230216   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 08:25:01,647:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676507099, self.tradeDate='20230216', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24813.4, self.close=24798.6, self.high=24934.1, self.low=24766.5, self.vol=14366.269, self.amt=357000684.0221, ukdf['pct'].iloc[-1]=-0.000596 , ukdf['amount'].iloc[-1]=357000684.0221, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-02-16 04:00:10,397:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41742F1676491205043I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676491205146890, 'quantity': '42.891', 'price': '23329.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676491204644, 'updatetime': 1676491205146, 'tradetype': 'usdt', 'selfid': 41742, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676491205146, 'clientorderid': '41742F1676491205043I0L65', 'price': '23329.7', 'quantity': '42.891', 'commission': '1000.6341627', 'commissionasset': 'USDT', 'tradetime': 1676491205146, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676491205146}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-16 04:00:10,397:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41742F1676491205043I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676491205146890, 'quantity': '42.891', 'price': '23329.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676491204644, 'updatetime': 1676491205146, 'tradetype': 'usdt', 'selfid': 41742, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676491205146, 'clientorderid': '41742F1676491205043I0L65', 'price': '23329.7', 'quantity': '42.891', 'commission': '1000.6341627', 'commissionasset': 'USDT', 'tradetime': 1676491205146, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676491205146}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Feb/2023 04:00:10] "POST / HTTP/1.1" 200 -
2023-02-16 04:00:10,490:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41743F1676491210376I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676491210477112, 'quantity': '36.518', 'price': '23318.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676491210161, 'updatetime': 1676491210477, 'tradetype': 'usdt', 'selfid': 41743, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676491210477, 'clientorderid': '41743F1676491210376I0L65', 'price': '23318.2', 'quantity': '36.518', 'commission': '851.5340276', 'commissionasset': 'USDT', 'tradetime': 1676491210477, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676491210477}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Feb/2023 04:00:10] "POST / HTTP/1.1" 200 -
2023-02-16 04:00:10,740:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41743F1676491210376I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676491210477112, 'quantity': '36.518', 'price': '23318.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676491210161, 'updatetime': 1676491210477, 'tradetype': 'usdt', 'selfid': 41743, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676491210477, 'clientorderid': '41743F1676491210376I0L65', 'price': '23318.2', 'quantity': '36.518', 'commission': '851.5340276', 'commissionasset': 'USDT', 'tradetime': 1676491210477, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676491210477}], 'gatetype': 'simulator', 'handletime': 0}
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=496
self.closeSec=1676505599, self.tradeDate='20230216', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23310.6, self.close=24332.6, self.high=24420.0, self.low=23285.9, self.vol=306935.488, self.amt=7368612711.94118 
127.0.0.1 - - [16/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-16 08:00:01,949:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676505599, self.tradeDate='20230216', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23310.6, self.close=24332.6, self.high=24420.0, self.low=23285.9, self.vol=306935.488, self.amt=7368612711.94118 
2023-02-16 08:00:01,978:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230215   120000    155959  ...   23896.173  5.284312e+08  0.000389
718  20230215   160000    195959  ...   86066.327  1.918943e+09  0.015183
719  20230215   200000    235959  ...  207159.107  4.704555e+09  0.016275
720  20230216   000000    035959  ...  165009.408  3.797764e+09  0.022620
721  20230216   040000    075959  ...  306935.488  7.368613e+09  0.043699

[5 rows x 11 columns]
2023-02-16 08:00:03,949:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230215   120000    155959  1676447999  ...    717  0.154039 -1.681050    -1.0
718  20230215   160000    195959  1676462399  ...    718  0.255446 -1.249438    -1.0
719  20230215   200000    235959  1676476799  ...    719  0.558057 -0.052169     NaN
720  20230216   000000    035959  1676491199  ...    720  0.933373  1.400510     1.0
721  20230216   040000    075959  1676505599  ...    721  1.530634  3.435158     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '37043.8592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24332.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


