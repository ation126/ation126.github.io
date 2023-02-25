# 20230225 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [25/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25852
self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23166.5, self.close=23177.6, self.high=23188.6, self.low=23160.8, self.vol=484.764, self.amt=11235982.5113 
2023-02-25 08:20:01,803:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230225   075500    075959  ...         0.0        0.0       0
5856  20230225   080000    080459  ...         0.0        0.0       0
5857  20230225   080500    080959  ...         0.0        0.0       0
5858  20230225   081000    081459  ...         0.0        0.0       0
5859  20230225   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 08:20:01,803:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23166.5, self.close=23177.6, self.high=23188.6, self.low=23160.8, self.vol=484.764, self.amt=11235982.5113, ukdf['pct'].iloc[-1]=0.000479 , ukdf['amount'].iloc[-1]=11235982.5113, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-400117.71757045056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23178.42452756', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25853
self.closeSec=1677284699, self.tradeDate='20230225', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23177.7, self.close=23162.9, self.high=23177.7, self.low=23153.7, self.vol=525.607, self.amt=12173512.301 
2023-02-25 08:25:01,724:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230225   080000    080459  ...         0.0        0.0       0
5857  20230225   080500    080959  ...         0.0        0.0       0
5858  20230225   081000    081459  ...         0.0        0.0       0
5859  20230225   081500    081959  ...         0.0        0.0       0
5860  20230225   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 08:25:01,726:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677284699, self.tradeDate='20230225', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23177.7, self.close=23162.9, self.high=23177.7, self.low=23153.7, self.vol=525.607, self.amt=12173512.301, ukdf['pct'].iloc[-1]=-0.000634 , ukdf['amount'].iloc[-1]=12173512.301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-399180.231209816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23162.8454535', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23166.5, self.close=23177.6, self.high=23188.6, self.low=23160.8 
2023-02-25 08:20:01,651:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23166.5, self.close=23177.6, self.high=23188.6, self.low=23160.8   
127.0.0.1 - - [25/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-25 08:20:01,825:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230225   075500    075959  1677283199  ...  23171.4 -0.000423   1535    5
1536  20230225   080000    080459  1677283499  ...  23157.6  0.000147   1536    0
1537  20230225   080500    080959  1677283799  ...  23155.2 -0.001027   1537    1
1538  20230225   081000    081459  1677284099  ...  23155.1  0.000488   1538    2
1539  20230225   081500    081959  1677284399  ...  23160.8  0.000479   1539    3

[5 rows x 11 columns]
2023-02-25 08:20:01,828:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7369542067946808, self.count=26419 

self.closeSec=1677284699, self.tradeDate='20230225', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23177.7, self.close=23162.9, self.high=23177.7, self.low=23153.7 
2023-02-25 08:25:01,652:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677284699, self.tradeDate='20230225', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23177.7, self.close=23162.9, self.high=23177.7, self.low=23153.7   
127.0.0.1 - - [25/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-25 08:25:01,704:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230225   080000    080459  1677283499  ...  23157.6  0.000147   1536    0
1537  20230225   080500    080959  1677283799  ...  23155.2 -0.001027   1537    1
1538  20230225   081000    081459  1677284099  ...  23155.1  0.000488   1538    2
1539  20230225   081500    081959  1677284399  ...  23160.8  0.000479   1539    3
1540  20230225   082000    082459  1677284699  ...  23153.7 -0.000634   1540    4

[5 rows x 11 columns]
2023-02-25 08:25:01,704:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-25 08:00:34,228:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230225    052959  23205.2  ...  47.916667  0.388675  0.739911
5771  20230225    055959  23161.6  ...  47.500000  0.379749  0.741398
5772  20230225    062959  23092.3  ...  47.500000  0.375521  0.744592
5773  20230225    065959  23059.0  ...  47.916667  0.386202  0.744808
5774  20230225    072959  23110.0  ...  48.333333  0.398572  0.741750

[5 rows x 33 columns]
0.5378927911275416
acc is : 0.5378927911275416
2023-02-25 08:00:34,387:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.516913  0.483087       0  ...  1.030358   1.0    0.0  1.075546
537     0  0.508138  0.491862       0  ...  1.028873   1.0    0.0  1.073995
538     1  0.499063  0.500937       1  ...  1.031148   1.0    0.0  1.076371
539     0  0.507937  0.492063       1  ...  1.033830   1.0    0.0  1.079170
540     0  0.521804  0.478196       1  ...  1.034075   1.0    0.0  1.079426

[5 rows x 10 columns]
2023-02-25 08:00:34,422:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515425  0.484575       0  ...  1.029927  -1.0    0.0  1.071404
46     0  0.507096  0.492904       0  ...  1.048521  -1.0    0.0  1.071450
47     1  0.498644  0.501356       1  ...  1.031148   1.0    0.0  1.075039
48     0  0.507841  0.492159       1  ...  1.033830   1.0    0.0  1.079170
49     0  0.521804  0.478196       1  ...  1.034075   1.0    0.0  1.079426

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.035', 'enterprice': '23090.7', 'countrevence': '0', 'unrealprofit': '2578.3970088665', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23168.7504619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230225   075000    075959  1677283199    23170  23175.6  0.000237
2023-02-25 08:00:02,327:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13208 

self.closeSec=1677283799, self.tradeDate='20230225', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23175.5', self.close='23155.2'
2023-02-25 08:10:01,608:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677283799, self.tradeDate='20230225', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23175.5', self.close='23155.2'
2023-02-25 08:10:01,651:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230225   072000    072959  1677281399    23145  23170.1  0.001089
621  20230225   073000    073959  1677281999  23170.2  23163.2 -0.000298
622  20230225   074000    074959  1677282599  23163.2  23170.1  0.000298
623  20230225   075000    075959  1677283199    23170  23175.6  0.000237
624  20230225   080000    080959  1677283799  23175.5  23155.2 -0.000880
2023-02-25 08:10:01,652:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13209 

self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23155.3', self.close='23177.6'
2023-02-25 08:20:01,745:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23155.3', self.close='23177.6'
127.0.0.1 - - [25/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-25 08:20:01,771:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230225   073000    073959  1677281999  23170.2  23163.2 -0.000298
622  20230225   074000    074959  1677282599  23163.2  23170.1  0.000298
623  20230225   075000    075959  1677283199    23170  23175.6  0.000237
624  20230225   080000    080959  1677283799  23175.5  23155.2 -0.000880
625  20230225   081000    081959  1677284399  23155.3  23177.6  0.000967
2023-02-25 08:20:01,773:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230225   075000    075959  1677283199    23170  23175.6
2023-02-25 08:00:02,384:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13209 

self.closeSec=1677283799, self.tradeDate='20230225', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23175.5', self.close='23155.2'
2023-02-25 08:10:01,597:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677283799, self.tradeDate='20230225', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23175.5', self.close='23155.2'
127.0.0.1 - - [25/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-25 08:10:01,646:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230225   072000    072959  1677281399    23145  23170.1
17469  20230225   073000    073959  1677281999  23170.2  23163.2
17470  20230225   074000    074959  1677282599  23163.2  23170.1
17471  20230225   075000    075959  1677283199    23170  23175.6
17472  20230225   080000    080959  1677283799  23175.5  23155.2
2023-02-25 08:10:01,646:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13210 

self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23155.3', self.close='23177.6'
2023-02-25 08:20:01,790:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23155.3', self.close='23177.6'
2023-02-25 08:20:01,847:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230225   073000    073959  1677281999  23170.2  23163.2
17470  20230225   074000    074959  1677282599  23163.2  23170.1
17471  20230225   075000    075959  1677283199    23170  23175.6
17472  20230225   080000    080959  1677283799  23175.5  23155.2
17473  20230225   081000    081959  1677284399  23155.3  23177.6
2023-02-25 08:20:01,850:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230225   075000    075959  1677283199    23170  23175.6
2023-02-25 08:00:02,371:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13209 

self.closeSec=1677283799, self.tradeDate='20230225', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23175.5', self.close='23155.2'
2023-02-25 08:10:01,608:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677283799, self.tradeDate='20230225', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23175.5', self.close='23155.2'
127.0.0.1 - - [25/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-25 08:10:01,648:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230225   072000    072959  1677281399    23145  23170.1
12141  20230225   073000    073959  1677281999  23170.2  23163.2
12142  20230225   074000    074959  1677282599  23163.2  23170.1
12143  20230225   075000    075959  1677283199    23170  23175.6
12144  20230225   080000    080959  1677283799  23175.5  23155.2
2023-02-25 08:10:01,648:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13210 

self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23155.3', self.close='23177.6'
127.0.0.1 - - [25/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-25 08:20:01,820:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23155.3', self.close='23177.6'
2023-02-25 08:20:01,876:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230225   073000    073959  1677281999  23170.2  23163.2
12142  20230225   074000    074959  1677282599  23163.2  23170.1
12143  20230225   075000    075959  1677283199    23170  23175.6
12144  20230225   080000    080959  1677283799  23175.5  23155.2
12145  20230225   081000    081959  1677284399  23155.3  23177.6
2023-02-25 08:20:01,876:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [25/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21850
self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23166.5, self.close=23177.6, self.high=23188.6, self.low=23160.8, self.vol=484.764, self.amt=11235982.5113 
2023-02-25 08:20:01,871:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230225   075500    075959  ...         0.0        0.0       0
5856  20230225   080000    080459  ...         0.0        0.0       0
5857  20230225   080500    080959  ...         0.0        0.0       0
5858  20230225   081000    081459  ...         0.0        0.0       0
5859  20230225   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 08:20:01,880:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677284399, self.tradeDate='20230225', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23166.5, self.close=23177.6, self.high=23188.6, self.low=23160.8, self.vol=484.764, self.amt=11235982.5113, ukdf['pct'].iloc[-1]=0.000479 , ukdf['amount'].iloc[-1]=11235982.5113, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [25/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21851
self.closeSec=1677284699, self.tradeDate='20230225', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23177.7, self.close=23162.9, self.high=23177.7, self.low=23153.7, self.vol=525.607, self.amt=12173512.301 
2023-02-25 08:25:01,718:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230225   080000    080459  ...         0.0        0.0       0
5857  20230225   080500    080959  ...         0.0        0.0       0
5858  20230225   081000    081459  ...         0.0        0.0       0
5859  20230225   081500    081959  ...         0.0        0.0       0
5860  20230225   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-25 08:25:01,718:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677284699, self.tradeDate='20230225', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23177.7, self.close=23162.9, self.high=23177.7, self.low=23153.7, self.vol=525.607, self.amt=12173512.301, ukdf['pct'].iloc[-1]=-0.000634 , ukdf['amount'].iloc[-1]=12173512.301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230224   200000    235959  1677254399  ...    719  0.622744  0.003444     NaN
720  20230225   000000    035959  1677268799  ...    720  0.644271  0.046288     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '64309.674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23171.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=550
self.closeSec=1677283199, self.tradeDate='20230225', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23172.3, self.close=23175.6, self.high=23333.0, self.low=22966.0, self.vol=89582.293, self.amt=2075755568.78078 
127.0.0.1 - - [25/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-02-25 08:00:02,051:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677283199, self.tradeDate='20230225', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23172.3, self.close=23175.6, self.high=23333.0, self.low=22966.0, self.vol=89582.293, self.amt=2075755568.78078 
2023-02-25 08:00:02,130:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230224   120000    155959  ...   55400.746  1.321314e+09 -0.005162
718  20230224   160000    195959  ...   60283.249  1.437744e+09  0.002305
719  20230224   200000    235959  ...  231711.797  5.483991e+09 -0.022587
720  20230225   000000    035959  ...  235085.841  5.429878e+09 -0.007079
721  20230225   040000    075959  ...   89582.293  2.075756e+09  0.000160

[5 rows x 11 columns]
2023-02-25 08:00:04,297:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230224   120000    155959  1677225599  ...    717  0.630339  0.043797     NaN
718  20230224   160000    195959  1677239999  ...    718  0.696564  0.198814     NaN
719  20230224   200000    235959  1677254399  ...    719  0.622744  0.003444     NaN
720  20230225   000000    035959  1677268799  ...    720  0.644271  0.046288     NaN
721  20230225   040000    075959  1677283199  ...    721  0.698404  0.175532     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '64123.35497068215', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23176.30953049', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


