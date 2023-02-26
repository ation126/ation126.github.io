# 20230226 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [26/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26140
self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23089.4, self.close=23123.4, self.high=23125.0, self.low=23086.8, self.vol=880.824, self.amt=20348863.7167 
2023-02-26 08:20:01,763:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230226   075500    075959  ...         0.0        0.0       0
5856  20230226   080000    080459  ...         0.0        0.0       0
5857  20230226   080500    080959  ...         0.0        0.0       0
5858  20230226   081000    081459  ...         0.0        0.0       0
5859  20230226   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 08:20:01,768:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23089.4, self.close=23123.4, self.high=23125.0, self.low=23086.8, self.vol=880.824, self.amt=20348863.7167, ukdf['pct'].iloc[-1]=0.001473 , ukdf['amount'].iloc[-1]=20348863.7167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-396806.5616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23123.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26141
self.closeSec=1677371099, self.tradeDate='20230226', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23123.5, self.close=23098.7, self.high=23123.5, self.low=23090.9, self.vol=622.079, self.amt=14370526.4491 
2023-02-26 08:25:01,602:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230226   080000    080459  ...         0.0        0.0       0
5857  20230226   080500    080959  ...         0.0        0.0       0
5858  20230226   081000    081459  ...         0.0        0.0       0
5859  20230226   081500    081959  ...         0.0        0.0       0
5860  20230226   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 08:25:01,602:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677371099, self.tradeDate='20230226', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23123.5, self.close=23098.7, self.high=23123.5, self.low=23090.9, self.vol=622.079, self.amt=14370526.4491, ukdf['pct'].iloc[-1]=-0.001068 , ukdf['amount'].iloc[-1]=14370526.4491, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-395320.2144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23098.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7432164995019352, self.count=26706 

self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23089.4, self.close=23123.4, self.high=23125.0, self.low=23086.8 
2023-02-26 08:20:01,675:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23089.4, self.close=23123.4, self.high=23125.0, self.low=23086.8   
2023-02-26 08:20:01,716:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230226   075500    075959  1677369599  ...  23146.2 -0.000717   1535    5
1536  20230226   080000    080459  1677369899  ...  23128.3 -0.000773   1536    0
1537  20230226   080500    080959  1677370199  ...  23122.3 -0.000095   1537    1
1538  20230226   081000    081459  1677370499  ...  23072.4 -0.001587   1538    2
1539  20230226   081500    081959  1677370799  ...  23086.8  0.001473   1539    3

[5 rows x 11 columns]
2023-02-26 08:20:01,718:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7432164995019352, self.count=26707 

self.closeSec=1677371099, self.tradeDate='20230226', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23123.5, self.close=23098.7, self.high=23123.5, self.low=23090.9 
2023-02-26 08:25:01,502:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677371099, self.tradeDate='20230226', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23123.5, self.close=23098.7, self.high=23123.5, self.low=23090.9   
2023-02-26 08:25:01,545:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230226   080000    080459  1677369899  ...  23128.3 -0.000773   1536    0
1537  20230226   080500    080959  1677370199  ...  23122.3 -0.000095   1537    1
1538  20230226   081000    081459  1677370499  ...  23072.4 -0.001587   1538    2
1539  20230226   081500    081959  1677370799  ...  23086.8  0.001473   1539    3
1540  20230226   082000    082459  1677371099  ...  23090.9 -0.001068   1540    4

[5 rows x 11 columns]
2023-02-26 08:25:01,553:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-26 08:00:34,898:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230226    052959  22916.3  ...  48.750000  0.404979  0.661842
5771  20230226    055959  22921.9  ...  49.166667  0.406999  0.654728
5772  20230226    062959  22927.2  ...  49.583333  0.438620  0.626242
5773  20230226    065959  23045.8  ...  49.583333  0.454645  0.592443
5774  20230226    072959  23109.9  ...  49.583333  0.470525  0.552947

[5 rows x 33 columns]
0.5378927911275416
acc is : 0.5378927911275416
2023-02-26 08:00:35,061:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.520846  0.479154       1  ...  0.949660   1.0    0.0  1.040641
537     0  0.522451  0.477549       1  ...  0.954576   1.0    0.0  1.046029
538     0  0.547833  0.452167       1  ...  0.957231   1.0    0.0  1.048939
539     0  0.551323  0.448677       1  ...  0.959965   1.0    0.0  1.051934
540     0  0.556486  0.443514       0  ...  0.958735   1.0    0.0  1.050586

[5 rows x 10 columns]
2023-02-26 08:00:35,082:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.521235  0.478765       1  ...  0.968273   1.0    0.0  1.040566
46     0  0.523210  0.476790       1  ...  0.973286   1.0    0.0  1.048733
47     0  0.548490  0.451510       1  ...  0.975993   1.0    0.0  1.050388
48     0  0.551323  0.448677       1  ...  0.959965   1.0    0.0  1.051934
49     0  0.556486  0.443514       0  ...  0.958735   1.0    0.0  1.050586

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.793', 'enterprice': '23035.2', 'countrevence': '0', 'unrealprofit': '3607.93025483547', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23145.22135379', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230226   075000    075959  1677369599  23144.7  23146.2  0.000060
2023-02-26 08:00:02,045:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13352 

self.closeSec=1677370199, self.tradeDate='20230226', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23146.2', self.close='23126.1'
2023-02-26 08:10:01,598:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677370199, self.tradeDate='20230226', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23146.2', self.close='23126.1'
127.0.0.1 - - [26/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-26 08:10:01,625:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230226   072000    072959  1677367799  23142.3  23175.9  0.001456
621  20230226   073000    073959  1677368399  23175.8  23134.6 -0.001782
622  20230226   074000    074959  1677368999  23134.7  23144.8  0.000441
623  20230226   075000    075959  1677369599  23144.7  23146.2  0.000060
624  20230226   080000    080959  1677370199  23146.2  23126.1 -0.000868
2023-02-26 08:10:01,625:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13353 

self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23126.2', self.close='23123.4'
127.0.0.1 - - [26/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-26 08:20:01,849:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23126.2', self.close='23123.4'
2023-02-26 08:20:01,869:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230226   073000    073959  1677368399  23175.8  23134.6 -0.001782
622  20230226   074000    074959  1677368999  23134.7  23144.8  0.000441
623  20230226   075000    075959  1677369599  23144.7  23146.2  0.000060
624  20230226   080000    080959  1677370199  23146.2  23126.1 -0.000868
625  20230226   081000    081959  1677370799  23126.2  23123.4 -0.000117
2023-02-26 08:20:01,870:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230226   075000    075959  1677369599  23144.7  23146.2
2023-02-26 08:00:02,120:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13353 

self.closeSec=1677370199, self.tradeDate='20230226', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23146.2', self.close='23126.1'
2023-02-26 08:10:01,620:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677370199, self.tradeDate='20230226', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23146.2', self.close='23126.1'
127.0.0.1 - - [26/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-26 08:10:01,662:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230226   072000    072959  1677367799  23142.3  23175.9
17469  20230226   073000    073959  1677368399  23175.8  23134.6
17470  20230226   074000    074959  1677368999  23134.7  23144.8
17471  20230226   075000    075959  1677369599  23144.7  23146.2
17472  20230226   080000    080959  1677370199  23146.2  23126.1
2023-02-26 08:10:01,662:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [26/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13354 

self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23126.2', self.close='23123.4'
2023-02-26 08:20:01,881:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23126.2', self.close='23123.4'
2023-02-26 08:20:01,905:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230226   073000    073959  1677368399  23175.8  23134.6
17470  20230226   074000    074959  1677368999  23134.7  23144.8
17471  20230226   075000    075959  1677369599  23144.7  23146.2
17472  20230226   080000    080959  1677370199  23146.2  23126.1
17473  20230226   081000    081959  1677370799  23126.2  23123.4
2023-02-26 08:20:01,905:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230226   075000    075959  1677369599  23144.7  23146.2
2023-02-26 08:00:02,103:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13353 

self.closeSec=1677370199, self.tradeDate='20230226', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23146.2', self.close='23126.1'
2023-02-26 08:10:01,589:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677370199, self.tradeDate='20230226', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23146.2', self.close='23126.1'
127.0.0.1 - - [26/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-26 08:10:01,614:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230226   072000    072959  1677367799  23142.3  23175.9
12141  20230226   073000    073959  1677368399  23175.8  23134.6
12142  20230226   074000    074959  1677368999  23134.7  23144.8
12143  20230226   075000    075959  1677369599  23144.7  23146.2
12144  20230226   080000    080959  1677370199  23146.2  23126.1
2023-02-26 08:10:01,615:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13354 

self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23126.2', self.close='23123.4'
127.0.0.1 - - [26/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-26 08:20:01,876:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23126.2', self.close='23123.4'
2023-02-26 08:20:01,897:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230226   073000    073959  1677368399  23175.8  23134.6
12142  20230226   074000    074959  1677368999  23134.7  23144.8
12143  20230226   075000    075959  1677369599  23144.7  23146.2
12144  20230226   080000    080959  1677370199  23146.2  23126.1
12145  20230226   081000    081959  1677370799  23126.2  23123.4
2023-02-26 08:20:01,897:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [26/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22138
self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23089.4, self.close=23123.4, self.high=23125.0, self.low=23086.8, self.vol=880.824, self.amt=20348863.7167 
2023-02-26 08:20:01,758:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230226   075500    075959  ...         0.0        0.0       0
5856  20230226   080000    080459  ...         0.0        0.0       0
5857  20230226   080500    080959  ...         0.0        0.0       0
5858  20230226   081000    081459  ...         0.0        0.0       0
5859  20230226   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 08:20:01,763:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677370799, self.tradeDate='20230226', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23089.4, self.close=23123.4, self.high=23125.0, self.low=23086.8, self.vol=880.824, self.amt=20348863.7167, ukdf['pct'].iloc[-1]=0.001473 , ukdf['amount'].iloc[-1]=20348863.7167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22139
self.closeSec=1677371099, self.tradeDate='20230226', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23123.5, self.close=23098.7, self.high=23123.5, self.low=23090.9, self.vol=622.079, self.amt=14370526.4491 
127.0.0.1 - - [26/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-26 08:25:01,552:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230226   080000    080459  ...         0.0        0.0       0
5857  20230226   080500    080959  ...         0.0        0.0       0
5858  20230226   081000    081459  ...         0.0        0.0       0
5859  20230226   081500    081959  ...         0.0        0.0       0
5860  20230226   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 08:25:01,553:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677371099, self.tradeDate='20230226', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23123.5, self.close=23098.7, self.high=23123.5, self.low=23090.9, self.vol=622.079, self.amt=14370526.4491, ukdf['pct'].iloc[-1]=-0.001068 , ukdf['amount'].iloc[-1]=14370526.4491, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230225   200000    235959  1677340799  ...    719  0.975081  0.835976     1.0
720  20230226   000000    035959  1677355199  ...    720  1.032533  0.967372     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '-5639.3323', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22975.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=556
self.closeSec=1677369599, self.tradeDate='20230226', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22975.7, self.close=23146.2, self.high=23176.1, self.low=22700.0, self.vol=83386.846, self.amt=1914106046.52202 
127.0.0.1 - - [26/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-26 08:00:01,932:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677369599, self.tradeDate='20230226', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22975.7, self.close=23146.2, self.high=23176.1, self.low=22700.0, self.vol=83386.846, self.amt=1914106046.52202 
2023-02-26 08:00:01,968:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230225   120000    155959  ...  26914.175  6.208548e+08  0.001899
718  20230225   160000    195959  ...  59947.250  1.379336e+09 -0.005829
719  20230225   200000    235959  ...  61274.986  1.407854e+09  0.000975
720  20230226   000000    035959  ...  46659.541  1.072898e+09 -0.000900
721  20230226   040000    075959  ...  83386.846  1.914106e+09  0.007421

[5 rows x 11 columns]
2023-02-26 08:00:04,266:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230225   120000    155959  1677311999  ...    717  0.888594  0.642527     1.0
718  20230225   160000    195959  1677326399  ...    718  1.038801  1.007949     1.0
719  20230225   200000    235959  1677340799  ...    719  0.975081  0.835976     1.0
720  20230226   000000    035959  1677355199  ...    720  1.032533  0.967372     1.0
721  20230226   040000    075959  1677369599  ...    721  0.976690  0.818508     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '1655.23259456167', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23148.04304973', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


