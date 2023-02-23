# 20230223 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25276
self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24194.0, self.close=24225.0, self.high=24229.9, self.low=24156.6, self.vol=2155.829, self.amt=52177302.73797 
127.0.0.1 - - [23/Feb/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-02-23 08:20:05,459:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230223   075500    075959  ...         0.0        0.0       0
5856  20230223   080000    080459  ...         0.0        0.0       0
5857  20230223   080500    080959  ...         0.0        0.0       0
5858  20230223   081000    081459  ...         0.0        0.0       0
5859  20230223   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 08:20:05,477:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24194.0, self.close=24225.0, self.high=24229.9, self.low=24156.6, self.vol=2155.829, self.amt=52177302.73797, ukdf['pct'].iloc[-1]=0.001277 , ukdf['amount'].iloc[-1]=52177302.73797, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-463108.4784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24225.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25277
self.closeSec=1677111899, self.tradeDate='20230223', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24225.0, self.close=24202.6, self.high=24240.0, self.low=24202.6, self.vol=2018.981, self.amt=48900292.7084 
127.0.0.1 - - [23/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-23 08:25:01,618:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230223   080000    080459  ...         0.0        0.0       0
5857  20230223   080500    080959  ...         0.0        0.0       0
5858  20230223   081000    081459  ...         0.0        0.0       0
5859  20230223   081500    081959  ...         0.0        0.0       0
5860  20230223   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 08:25:01,619:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677111899, self.tradeDate='20230223', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24225.0, self.close=24202.6, self.high=24240.0, self.low=24202.6, self.vol=2018.981, self.amt=48900292.7084, ukdf['pct'].iloc[-1]=-0.000925 , ukdf['amount'].iloc[-1]=48900292.7084, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-461748.5008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24202.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24194.0, self.close=24225.0, self.high=24229.9, self.low=24156.6 
127.0.0.1 - - [23/Feb/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-02-23 08:20:04,177:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24194.0, self.close=24225.0, self.high=24229.9, self.low=24156.6   
2023-02-23 08:20:04,757:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230223   075500    075959  1677110399  ...  24170.0 -0.000327   1535    5
1536  20230223   080000    080459  1677110699  ...  24171.3  0.000294   1536    0
1537  20230223   080500    080959  1677110999  ...  24146.3 -0.000906   1537    1
1538  20230223   081000    081459  1677111299  ...  24156.5  0.001557   1538    2
1539  20230223   081500    081959  1677111599  ...  24156.6  0.001277   1539    3

[5 rows x 11 columns]
2023-02-23 08:20:04,766:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6990418040060691, self.count=25843 

self.closeSec=1677111899, self.tradeDate='20230223', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24225.0, self.close=24202.6, self.high=24240.0, self.low=24202.6 
2023-02-23 08:25:01,528:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677111899, self.tradeDate='20230223', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24225.0, self.close=24202.6, self.high=24240.0, self.low=24202.6   
2023-02-23 08:25:01,598:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230223   080000    080459  1677110699  ...  24171.3  0.000294   1536    0
1537  20230223   080500    080959  1677110999  ...  24146.3 -0.000906   1537    1
1538  20230223   081000    081459  1677111299  ...  24156.5  0.001557   1538    2
1539  20230223   081500    081959  1677111599  ...  24156.6  0.001277   1539    3
1540  20230223   082000    082459  1677111899  ...  24202.6 -0.000925   1540    4

[5 rows x 11 columns]
2023-02-23 08:25:01,599:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-23 08:00:34,172:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230223    052959  23792.8  ...  48.333333  0.433666  0.782902
5771  20230223    055959  23819.9  ...  48.333333  0.430356  0.775823
5772  20230223    062959  23795.4  ...  48.750000  0.459746  0.752565
5773  20230223    065959  23967.9  ...  48.750000  0.479416  0.718909
5774  20230223    072959  24093.0  ...  49.166667  0.491785  0.678704

[5 rows x 33 columns]
0.5212569316081331
acc is : 0.5212569316081331
2023-02-23 08:00:34,329:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.538142  0.461858       0  ...  1.042024   1.0    0.0  1.097372
537     0  0.521302  0.478698       1  ...  1.049578   1.0    0.0  1.105327
538     0  0.570689  0.429311       1  ...  1.054999   1.0    0.0  1.111036
539     0  0.571636  0.428364       1  ...  1.058551   1.0    0.0  1.114776
540     0  0.574433  0.425567       0  ...  1.058490   1.0    0.0  1.114712

[5 rows x 10 columns]
2023-02-23 08:00:34,365:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.537665  0.462335       0  ...  1.002793   1.0    0.0  1.095200
46     0  0.521684  0.478316       1  ...  0.970753   1.0    0.0  1.103637
47     0  0.571286  0.428714       1  ...  1.054999   1.0    0.0  1.111011
48     0  0.572559  0.427441       1  ...  1.011284   1.0    0.0  1.114776
49     0  0.574433  0.425567       0  ...  1.058490   1.0    0.0  1.114712

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.835', 'enterprice': '24119', 'countrevence': '0', 'unrealprofit': '2046.54836723615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24179.48613469', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230223   075000    075959  1677110399  24146.7  24171.3  0.001019
2023-02-23 08:00:02,083:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12920 

self.closeSec=1677110999, self.tradeDate='20230223', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24171.3', self.close='24156.5'
2023-02-23 08:10:01,623:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677110999, self.tradeDate='20230223', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24171.3', self.close='24156.5'
2023-02-23 08:10:01,687:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230223   072000    072959  1677108599  24143.1  24172.7  0.001151
621  20230223   073000    073959  1677109199  24172.7  24111.8 -0.002519
622  20230223   074000    074959  1677109799  24111.8  24146.7  0.001447
623  20230223   075000    075959  1677110399  24146.7  24171.3  0.001019
624  20230223   080000    080959  1677110999  24171.3  24156.5 -0.000612
2023-02-23 08:10:01,691:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12921 

self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24156.6', self.close='24225'
127.0.0.1 - - [23/Feb/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-02-23 08:20:05,592:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24156.6', self.close='24225'
2023-02-23 08:20:06,037:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230223   073000    073959  1677109199  24172.7  24111.8 -0.002519
622  20230223   074000    074959  1677109799  24111.8  24146.7  0.001447
623  20230223   075000    075959  1677110399  24146.7  24171.3  0.001019
624  20230223   080000    080959  1677110999  24171.3  24156.5 -0.000612
625  20230223   081000    081959  1677111599  24156.6    24225  0.002836
2023-02-23 08:20:06,038:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230223   075000    075959  1677110399  24146.7  24171.3
2023-02-23 08:00:02,031:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12921 

self.closeSec=1677110999, self.tradeDate='20230223', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24171.3', self.close='24156.5'
2023-02-23 08:10:01,646:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677110999, self.tradeDate='20230223', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24171.3', self.close='24156.5'
127.0.0.1 - - [23/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-23 08:10:01,663:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230223   072000    072959  1677108599  24143.1  24172.7
17469  20230223   073000    073959  1677109199  24172.7  24111.8
17470  20230223   074000    074959  1677109799  24111.8  24146.7
17471  20230223   075000    075959  1677110399  24146.7  24171.3
17472  20230223   080000    080959  1677110999  24171.3  24156.5
2023-02-23 08:10:01,663:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12922 

self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24156.6', self.close='24225'
127.0.0.1 - - [23/Feb/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-02-23 08:20:07,099:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24156.6', self.close='24225'
2023-02-23 08:20:07,135:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230223   073000    073959  1677109199  24172.7  24111.8
17470  20230223   074000    074959  1677109799  24111.8  24146.7
17471  20230223   075000    075959  1677110399  24146.7  24171.3
17472  20230223   080000    080959  1677110999  24171.3  24156.5
17473  20230223   081000    081959  1677111599  24156.6    24225
2023-02-23 08:20:07,136:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230223   075000    075959  1677110399  24146.7  24171.3
2023-02-23 08:00:02,097:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [23/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12921 

self.closeSec=1677110999, self.tradeDate='20230223', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24171.3', self.close='24156.5'
2023-02-23 08:10:01,636:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677110999, self.tradeDate='20230223', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24171.3', self.close='24156.5'
2023-02-23 08:10:01,652:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230223   072000    072959  1677108599  24143.1  24172.7
12141  20230223   073000    073959  1677109199  24172.7  24111.8
12142  20230223   074000    074959  1677109799  24111.8  24146.7
12143  20230223   075000    075959  1677110399  24146.7  24171.3
12144  20230223   080000    080959  1677110999  24171.3  24156.5
2023-02-23 08:10:01,652:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12922 

self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24156.6', self.close='24225'
127.0.0.1 - - [23/Feb/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-02-23 08:20:07,018:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24156.6', self.close='24225'
2023-02-23 08:20:07,091:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230223   073000    073959  1677109199  24172.7  24111.8
12142  20230223   074000    074959  1677109799  24111.8  24146.7
12143  20230223   075000    075959  1677110399  24146.7  24171.3
12144  20230223   080000    080959  1677110999  24171.3  24156.5
12145  20230223   081000    081959  1677111599  24156.6    24225
2023-02-23 08:20:07,091:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [23/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21274
self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24194.0, self.close=24225.0, self.high=24229.9, self.low=24156.6, self.vol=2155.829, self.amt=52177302.73797 
2023-02-23 08:20:01,606:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230223   075500    075959  ...         0.0        0.0       0
5856  20230223   080000    080459  ...         0.0        0.0       0
5857  20230223   080500    080959  ...         0.0        0.0       0
5858  20230223   081000    081459  ...         0.0        0.0       0
5859  20230223   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 08:20:01,608:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677111599, self.tradeDate='20230223', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24194.0, self.close=24225.0, self.high=24229.9, self.low=24156.6, self.vol=2155.829, self.amt=52177302.73797, ukdf['pct'].iloc[-1]=0.001277 , ukdf['amount'].iloc[-1]=52177302.73797, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21275
self.closeSec=1677111899, self.tradeDate='20230223', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24225.0, self.close=24202.6, self.high=24240.0, self.low=24202.6, self.vol=2018.981, self.amt=48900292.7084 
127.0.0.1 - - [23/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-23 08:25:01,592:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230223   080000    080459  ...         0.0        0.0       0
5857  20230223   080500    080959  ...         0.0        0.0       0
5858  20230223   081000    081459  ...         0.0        0.0       0
5859  20230223   081500    081959  ...         0.0        0.0       0
5860  20230223   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 08:25:01,595:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677111899, self.tradeDate='20230223', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24225.0, self.close=24202.6, self.high=24240.0, self.low=24202.6, self.vol=2018.981, self.amt=48900292.7084, ukdf['pct'].iloc[-1]=-0.000925 , ukdf['amount'].iloc[-1]=48900292.7084, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230222   200000    235959  1677081599  ...    719  0.330927 -0.651380    -1.0
720  20230223   000000    035959  1677095999  ...    720  0.430758 -0.405187     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '41843.5875', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23787.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [23/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=538
self.closeSec=1677110399, self.tradeDate='20230223', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23781.7, self.close=24171.3, self.high=24209.6, self.low=23730.0, self.vol=82007.956, self.amt=1966414037.53882 
2023-02-23 08:00:01,910:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677110399, self.tradeDate='20230223', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23781.7, self.close=24171.3, self.high=24209.6, self.low=23730.0, self.vol=82007.956, self.amt=1966414037.53882 
2023-02-23 08:00:01,952:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230222   120000    155959  ...   84541.648  2.033516e+09 -0.005752
718  20230222   160000    195959  ...   93248.828  2.242632e+09  0.004023
719  20230222   200000    235959  ...  185020.734  4.423616e+09 -0.018475
720  20230223   000000    035959  ...  157258.798  3.734329e+09  0.003020
721  20230223   040000    075959  ...   82007.956  1.966414e+09  0.016382

[5 rows x 11 columns]
2023-02-23 08:00:04,556:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230222   120000    155959  1677052799  ...    717  0.211909 -0.964276    -1.0
718  20230222   160000    195959  1677067199  ...    718  0.289427 -0.762059    -1.0
719  20230222   200000    235959  1677081599  ...    719  0.330927 -0.651380    -1.0
720  20230223   000000    035959  1677095999  ...    720  0.430758 -0.405187     NaN
721  20230223   040000    075959  1677110399  ...    721  0.459757 -0.335653     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '27695.9190115608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24175.27939088', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


