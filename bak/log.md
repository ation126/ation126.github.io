# 20230328 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34780
self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27078.1, self.close=27062.1, self.high=27090.0, self.low=27050.0, self.vol=1035.963, self.amt=28037841.8105 
127.0.0.1 - - [28/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-28 08:20:07,230:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230328   075500    075959  ...         0.0        0.0       0
5856  20230328   080000    080459  ...         0.0        0.0       0
5857  20230328   080500    080959  ...         0.0        0.0       0
5858  20230328   081000    081459  ...         0.0        0.0       0
5859  20230328   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 08:20:07,252:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27078.1, self.close=27062.1, self.high=27090.0, self.low=27050.0, self.vol=1035.963, self.amt=28037841.8105, ukdf['pct'].iloc[-1]=-0.000587 , ukdf['amount'].iloc[-1]=28037841.8105, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-633827.7904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27062.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34781
self.closeSec=1679963099, self.tradeDate='20230328', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27062.1, self.close=27050.5, self.high=27084.5, self.low=27036.6, self.vol=1488.159, self.amt=40266784.8001 
2023-03-28 08:25:01,573:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230328   080000    080459  ...         0.0        0.0       0
5857  20230328   080500    080959  ...         0.0        0.0       0
5858  20230328   081000    081459  ...         0.0        0.0       0
5859  20230328   081500    081959  ...         0.0        0.0       0
5860  20230328   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 08:25:01,573:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679963099, self.tradeDate='20230328', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27062.1, self.close=27050.5, self.high=27084.5, self.low=27036.6, self.vol=1488.159, self.amt=40266784.8001, ukdf['pct'].iloc[-1]=-0.000429 , ukdf['amount'].iloc[-1]=40266784.8001, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-633269.24782594176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27052.91818376', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27078.1, self.close=27062.1, self.high=27090.0, self.low=27050.0 
127.0.0.1 - - [28/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-28 08:20:04,912:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27078.1, self.close=27062.1, self.high=27090.0, self.low=27050.0   
2023-03-28 08:20:05,871:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230328   075500    075959  1679961599  ...  27106.5 -0.000616   1535    5
1536  20230328   080000    080459  1679961899  ...  27090.8 -0.000295   1536    0
1537  20230328   080500    080959  1679962199  ...  27071.6 -0.001092   1537    1
1538  20230328   081000    081459  1679962499  ...  27065.6  0.000129   1538    2
1539  20230328   081500    081959  1679962799  ...  27050.0 -0.000587   1539    3

[5 rows x 11 columns]
2023-03-28 08:20:05,880:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6029199784819073, self.count=35347 

self.closeSec=1679963099, self.tradeDate='20230328', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27062.1, self.close=27050.5, self.high=27084.5, self.low=27036.6 
2023-03-28 08:25:01,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679963099, self.tradeDate='20230328', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27062.1, self.close=27050.5, self.high=27084.5, self.low=27036.6   
2023-03-28 08:25:01,554:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230328   080000    080459  1679961899  ...  27090.8 -0.000295   1536    0
1537  20230328   080500    080959  1679962199  ...  27071.6 -0.001092   1537    1
1538  20230328   081000    081459  1679962499  ...  27065.6  0.000129   1538    2
1539  20230328   081500    081959  1679962799  ...  27050.0 -0.000587   1539    3
1540  20230328   082000    082459  1679963099  ...  27036.6 -0.000429   1540    4

[5 rows x 11 columns]
2023-03-28 08:25:01,554:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-28 08:00:34,523:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230328    052959  27032.8  ...  48.750000  0.430966  0.632547
5771  20230328    055959  27104.0  ...  49.166667  0.439283  0.627210
5772  20230328    062959  27154.3  ...  48.750000  0.436688  0.623114
5773  20230328    065959  27134.3  ...  48.333333  0.430282  0.621476
5774  20230328    072959  27084.8  ...  48.333333  0.438366  0.617847

[5 rows x 33 columns]
0.5027726432532348
acc is : 0.5027726432532348
2023-03-28 08:00:34,679:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.559188  0.440812       1  ...  0.965692   1.0    0.0  1.099013
537     0  0.557112  0.442888       0  ...  0.964981   1.0    0.0  1.098203
538     0  0.552726  0.447274       0  ...  0.963224   1.0    0.0  1.096204
539     0  0.534464  0.465536       1  ...  0.964913   1.0    0.0  1.098127
540     0  0.560346  0.439654       0  ...  0.964191   1.0    0.0  1.097305

[5 rows x 10 columns]
2023-03-28 08:00:34,716:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.558574  0.441426       1  ...  0.969399   1.0    0.0  1.091380
46     0  0.557345  0.442655       0  ...  0.980245   1.0    0.0  1.094778
47     0  0.552722  0.447278       0  ...  0.963224   1.0    0.0  1.093235
48     0  0.534703  0.465297       1  ...  0.980176   1.0    0.0  1.098127
49     0  0.560346  0.439654       0  ...  0.964191   1.0    0.0  1.097305

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230328   075000    075959  1679961599  27141.6  27112.1 -0.001087
2023-03-28 08:00:02,119:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17672 

self.closeSec=1679962199, self.tradeDate='20230328', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27112', self.close='27074.5'
2023-03-28 08:10:01,596:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679962199, self.tradeDate='20230328', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27112', self.close='27074.5'
2023-03-28 08:10:01,622:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230328   072000    072959  1679959799  27115.1  27132.4  0.000634
621  20230328   073000    073959  1679960399  27132.5  27153.4  0.000774
622  20230328   074000    074959  1679960999  27153.4  27141.6 -0.000435
623  20230328   075000    075959  1679961599  27141.6  27112.1 -0.001087
624  20230328   080000    080959  1679962199    27112  27074.5 -0.001387
2023-03-28 08:10:01,623:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17673 

self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27074.3', self.close='27062.1'
127.0.0.1 - - [28/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-28 08:20:06,860:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27074.3', self.close='27062.1'
2023-03-28 08:20:07,520:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230328   073000    073959  1679960399  27132.5  27153.4  0.000774
622  20230328   074000    074959  1679960999  27153.4  27141.6 -0.000435
623  20230328   075000    075959  1679961599  27141.6  27112.1 -0.001087
624  20230328   080000    080959  1679962199    27112  27074.5 -0.001387
625  20230328   081000    081959  1679962799  27074.3  27062.1 -0.000458
2023-03-28 08:20:07,521:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230328   075000    075959  1679961599  27141.6  27112.1
2023-03-28 08:00:02,173:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17673 

self.closeSec=1679962199, self.tradeDate='20230328', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27112', self.close='27074.5'
2023-03-28 08:10:01,612:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679962199, self.tradeDate='20230328', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27112', self.close='27074.5'
2023-03-28 08:10:01,635:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230328   072000    072959  1679959799  27115.1  27132.4
17469  20230328   073000    073959  1679960399  27132.5  27153.4
17470  20230328   074000    074959  1679960999  27153.4  27141.6
17471  20230328   075000    075959  1679961599  27141.6  27112.1
17472  20230328   080000    080959  1679962199    27112  27074.5
2023-03-28 08:10:01,636:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17674 

self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27074.3', self.close='27062.1'
127.0.0.1 - - [28/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-28 08:20:09,430:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27074.3', self.close='27062.1'
2023-03-28 08:20:09,552:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230328   073000    073959  1679960399  27132.5  27153.4
17470  20230328   074000    074959  1679960999  27153.4  27141.6
17471  20230328   075000    075959  1679961599  27141.6  27112.1
17472  20230328   080000    080959  1679962199    27112  27074.5
17473  20230328   081000    081959  1679962799  27074.3  27062.1
2023-03-28 08:20:09,553:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230328   075000    075959  1679961599  27141.6  27112.1
2023-03-28 08:00:02,146:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17673 

self.closeSec=1679962199, self.tradeDate='20230328', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27112', self.close='27074.5'
2023-03-28 08:10:01,603:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679962199, self.tradeDate='20230328', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27112', self.close='27074.5'
127.0.0.1 - - [28/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-28 08:10:01,610:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230328   072000    072959  1679959799  27115.1  27132.4
12141  20230328   073000    073959  1679960399  27132.5  27153.4
12142  20230328   074000    074959  1679960999  27153.4  27141.6
12143  20230328   075000    075959  1679961599  27141.6  27112.1
12144  20230328   080000    080959  1679962199    27112  27074.5
2023-03-28 08:10:01,610:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17674 

self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27074.3', self.close='27062.1'
127.0.0.1 - - [28/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-28 08:20:08,874:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27074.3', self.close='27062.1'
2023-03-28 08:20:09,212:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230328   073000    073959  1679960399  27132.5  27153.4
12142  20230328   074000    074959  1679960999  27153.4  27141.6
12143  20230328   075000    075959  1679961599  27141.6  27112.1
12144  20230328   080000    080959  1679962199    27112  27074.5
12145  20230328   081000    081959  1679962799  27074.3  27062.1
2023-03-28 08:20:09,220:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30778
self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27078.1, self.close=27062.1, self.high=27090.0, self.low=27050.0, self.vol=1035.963, self.amt=28037841.8105 
127.0.0.1 - - [28/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-28 08:20:05,721:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230328   075500    075959  ...         0.0        0.0       0
5856  20230328   080000    080459  ...         0.0        0.0       0
5857  20230328   080500    080959  ...         0.0        0.0       0
5858  20230328   081000    081459  ...         0.0        0.0       0
5859  20230328   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 08:20:05,745:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679962799, self.tradeDate='20230328', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27078.1, self.close=27062.1, self.high=27090.0, self.low=27050.0, self.vol=1035.963, self.amt=28037841.8105, ukdf['pct'].iloc[-1]=-0.000587 , ukdf['amount'].iloc[-1]=28037841.8105, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [28/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30779
self.closeSec=1679963099, self.tradeDate='20230328', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27062.1, self.close=27050.5, self.high=27084.5, self.low=27036.6, self.vol=1488.159, self.amt=40266784.8001 
2023-03-28 08:25:01,577:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230328   080000    080459  ...         0.0        0.0       0
5857  20230328   080500    080959  ...         0.0        0.0       0
5858  20230328   081000    081459  ...         0.0        0.0       0
5859  20230328   081500    081959  ...         0.0        0.0       0
5860  20230328   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-28 08:25:01,578:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679963099, self.tradeDate='20230328', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27062.1, self.close=27050.5, self.high=27084.5, self.low=27036.6, self.vol=1488.159, self.amt=40266784.8001, ukdf['pct'].iloc[-1]=-0.000429 , ukdf['amount'].iloc[-1]=40266784.8001, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230327   200000    235959  1679932799  ...    719  0.038575 -1.277641    -1.0
720  20230328   000000    035959  1679947199  ...    720  0.129919 -1.044061    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '60956.31', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26956.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=736
self.closeSec=1679961599, self.tradeDate='20230328', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26956.9, self.close=27112.1, self.high=27246.9, self.low=26860.0, self.vol=53997.391, self.amt=1461751527.14598 
127.0.0.1 - - [28/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-03-28 08:00:01,942:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679961599, self.tradeDate='20230328', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26956.9, self.close=27112.1, self.high=27246.9, self.low=26860.0, self.vol=53997.391, self.amt=1461751527.14598 
2023-03-28 08:00:02,009:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230327   120000    155959  ...   50007.614  1.389256e+09 -0.003009
718  20230327   160000    195959  ...   51239.037  1.428795e+09  0.003073
719  20230327   200000    235959  ...  308699.095  8.393002e+09 -0.035603
720  20230328   000000    035959  ...  134144.056  3.633684e+09  0.002544
721  20230328   040000    075959  ...   53997.391  1.461752e+09  0.005802

[5 rows x 11 columns]
2023-03-28 08:00:04,904:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230327   120000    155959  1679903999  ...    717  0.136958 -1.101054    -1.0
718  20230327   160000    195959  1679918399  ...    718  0.110154 -1.139628    -1.0
719  20230327   200000    235959  1679932799  ...    719  0.038575 -1.277641    -1.0
720  20230328   000000    035959  1679947199  ...    720  0.129919 -1.044061    -1.0
721  20230328   040000    075959  1679961599  ...    721  0.151166 -0.975929    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '52583.5446', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27112', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


