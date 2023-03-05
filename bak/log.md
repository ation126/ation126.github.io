# 20230305 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28156
self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22330.0, self.close=22331.7, self.high=22332.6, self.low=22325.8, self.vol=319.517, self.amt=7134331.861 
127.0.0.1 - - [05/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 08:20:01,736:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230305   075500    075959  ...         0.0        0.0       0
5856  20230305   080000    080459  ...         0.0        0.0       0
5857  20230305   080500    080959  ...         0.0        0.0       0
5858  20230305   081000    081459  ...         0.0        0.0       0
5859  20230305   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 08:20:01,746:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22330.0, self.close=22331.7, self.high=22332.6, self.low=22325.8, self.vol=319.517, self.amt=7134331.861, ukdf['pct'].iloc[-1]=8.1e-05 , ukdf['amount'].iloc[-1]=7134331.861, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-349225.73899134592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22332.70565992', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28157
self.closeSec=1677975899, self.tradeDate='20230305', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22331.7, self.close=22305.1, self.high=22333.0, self.low=22305.0, self.vol=693.273, self.amt=15473219.5156 
2023-03-05 08:25:01,651:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230305   080000    080459  ...         0.0        0.0       0
5857  20230305   080500    080959  ...         0.0        0.0       0
5858  20230305   081000    081459  ...         0.0        0.0       0
5859  20230305   081500    081959  ...         0.0        0.0       0
5860  20230305   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 08:25:01,652:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677975899, self.tradeDate='20230305', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22331.7, self.close=22305.1, self.high=22333.0, self.low=22305.0, self.vol=693.273, self.amt=15473219.5156, ukdf['pct'].iloc[-1]=-0.001191 , ukdf['amount'].iloc[-1]=15473219.5156, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-347792.52939697344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22308.88869644', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.5563527681019893, self.count=28722 

self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22330.0, self.close=22331.7, self.high=22332.6, self.low=22325.8 
2023-03-05 08:20:01,630:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22330.0, self.close=22331.7, self.high=22332.6, self.low=22325.8   
2023-03-05 08:20:01,687:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230305   075500    075959  1677974399  ...  22327.0  0.000390   1535    5
1536  20230305   080000    080459  1677974699  ...  22327.1 -0.000018   1536    0
1537  20230305   080500    080959  1677974999  ...  22326.9 -0.000210   1537    1
1538  20230305   081000    081459  1677975299  ...  22326.8 -0.000031   1538    2
1539  20230305   081500    081959  1677975599  ...  22325.8  0.000081   1539    3

[5 rows x 11 columns]
2023-03-05 08:20:01,687:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [05/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.5563527681019893, self.count=28723 

self.closeSec=1677975899, self.tradeDate='20230305', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22331.7, self.close=22305.1, self.high=22333.0, self.low=22305.0 
2023-03-05 08:25:01,484:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677975899, self.tradeDate='20230305', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22331.7, self.close=22305.1, self.high=22333.0, self.low=22305.0   
2023-03-05 08:25:01,606:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230305   080000    080459  1677974699  ...  22327.1 -0.000018   1536    0
1537  20230305   080500    080959  1677974999  ...  22326.9 -0.000210   1537    1
1538  20230305   081000    081459  1677975299  ...  22326.8 -0.000031   1538    2
1539  20230305   081500    081959  1677975599  ...  22325.8  0.000081   1539    3
1540  20230305   082000    082459  1677975899  ...  22305.0 -0.001191   1540    4

[5 rows x 11 columns]
2023-03-05 08:25:01,612:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-05 08:00:32,244:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230305    052959  22243.2  ...  46.250000  0.386037  0.492570
5771  20230305    055959  22218.9  ...  45.833333  0.381666  0.511428
5772  20230305    062959  22204.3  ...  46.250000  0.425879  0.503155
5773  20230305    065959  22302.2  ...  45.833333  0.423608  0.497334
5774  20230305    072959  22295.0  ...  45.833333  0.427588  0.489472

[5 rows x 33 columns]
0.5489833641404805
acc is : 0.5489833641404805
2023-03-05 08:00:32,458:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.487353  0.512647       0  ...  0.933727   1.0    0.0  0.909982
537     1  0.492237  0.507763       1  ...  0.937848   1.0    0.0  0.913998
538     0  0.553155  0.446845       0  ...  0.937545   1.0    0.0  0.913703
539     0  0.515894  0.484106       1  ...  0.937932   1.0    0.0  0.914080
540     0  0.521399  0.478601       1  ...  0.939257   1.0    0.0  0.915371

[5 rows x 10 columns]
2023-03-05 08:00:32,489:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487739  0.512261       0  ...  0.921372   1.0    0.0  0.904301
46     1  0.493021  0.506979       1  ...  0.902729   1.0    0.0  0.915082
47     0  0.553529  0.446471       0  ...  0.937545   1.0    0.0  0.913853
48     0  0.515894  0.484106       1  ...  0.937932   1.0    0.0  0.914080
49     0  0.521399  0.478601       1  ...  0.939257   1.0    0.0  0.915371

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.837', 'enterprice': '22365.6', 'countrevence': '0', 'unrealprofit': '-1112.35887391473', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22330.66081371', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230305   075000    075959  1677974399  22315.7  22335.7  0.000896
2023-03-05 08:00:02,067:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14360 

self.closeSec=1677974999, self.tradeDate='20230305', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22335.8', self.close='22330.6'
2023-03-05 08:10:01,590:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677974999, self.tradeDate='20230305', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22335.8', self.close='22330.6'
2023-03-05 08:10:01,615:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230305   072000    072959  1677972599  22316.5  22304.2 -0.000556
621  20230305   073000    073959  1677973199  22304.2  22320.1  0.000713
622  20230305   074000    074959  1677973799    22320  22315.7 -0.000197
623  20230305   075000    075959  1677974399  22315.7  22335.7  0.000896
624  20230305   080000    080959  1677974999  22335.8  22330.6 -0.000228
2023-03-05 08:10:01,615:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14361 

self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22330.6', self.close='22331.7'
127.0.0.1 - - [05/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 08:20:01,740:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22330.6', self.close='22331.7'
2023-03-05 08:20:01,765:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230305   073000    073959  1677973199  22304.2  22320.1  0.000713
622  20230305   074000    074959  1677973799    22320  22315.7 -0.000197
623  20230305   075000    075959  1677974399  22315.7  22335.7  0.000896
624  20230305   080000    080959  1677974999  22335.8  22330.6 -0.000228
625  20230305   081000    081959  1677975599  22330.6  22331.7  0.000049
2023-03-05 08:20:01,765:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230305   075000    075959  1677974399  22315.7  22335.7
2023-03-05 08:00:02,032:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14361 

self.closeSec=1677974999, self.tradeDate='20230305', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22335.8', self.close='22330.6'
2023-03-05 08:10:01,605:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677974999, self.tradeDate='20230305', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22335.8', self.close='22330.6'
127.0.0.1 - - [05/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-05 08:10:01,638:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230305   072000    072959  1677972599  22316.5  22304.2
17469  20230305   073000    073959  1677973199  22304.2  22320.1
17470  20230305   074000    074959  1677973799    22320  22315.7
17471  20230305   075000    075959  1677974399  22315.7  22335.7
17472  20230305   080000    080959  1677974999  22335.8  22330.6
2023-03-05 08:10:01,638:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14362 

self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22330.6', self.close='22331.7'
127.0.0.1 - - [05/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 08:20:01,747:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22330.6', self.close='22331.7'
2023-03-05 08:20:01,784:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230305   073000    073959  1677973199  22304.2  22320.1
17470  20230305   074000    074959  1677973799    22320  22315.7
17471  20230305   075000    075959  1677974399  22315.7  22335.7
17472  20230305   080000    080959  1677974999  22335.8  22330.6
17473  20230305   081000    081959  1677975599  22330.6  22331.7
2023-03-05 08:20:01,785:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230305   075000    075959  1677974399  22315.7  22335.7
2023-03-05 08:00:02,080:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14361 

self.closeSec=1677974999, self.tradeDate='20230305', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22335.8', self.close='22330.6'
2023-03-05 08:10:01,611:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677974999, self.tradeDate='20230305', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22335.8', self.close='22330.6'
127.0.0.1 - - [05/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-05 08:10:01,630:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230305   072000    072959  1677972599  22316.5  22304.2
12141  20230305   073000    073959  1677973199  22304.2  22320.1
12142  20230305   074000    074959  1677973799    22320  22315.7
12143  20230305   075000    075959  1677974399  22315.7  22335.7
12144  20230305   080000    080959  1677974999  22335.8  22330.6
2023-03-05 08:10:01,630:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14362 

self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22330.6', self.close='22331.7'
127.0.0.1 - - [05/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 08:20:01,728:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22330.6', self.close='22331.7'
2023-03-05 08:20:01,767:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230305   073000    073959  1677973199  22304.2  22320.1
12142  20230305   074000    074959  1677973799    22320  22315.7
12143  20230305   075000    075959  1677974399  22315.7  22335.7
12144  20230305   080000    080959  1677974999  22335.8  22330.6
12145  20230305   081000    081959  1677975599  22330.6  22331.7
2023-03-05 08:20:01,768:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24154
self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22330.0, self.close=22331.7, self.high=22332.6, self.low=22325.8, self.vol=319.517, self.amt=7134331.861 
127.0.0.1 - - [05/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-05 08:20:01,752:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230305   075500    075959  ...         0.0        0.0       0
5856  20230305   080000    080459  ...         0.0        0.0       0
5857  20230305   080500    080959  ...         0.0        0.0       0
5858  20230305   081000    081459  ...         0.0        0.0       0
5859  20230305   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 08:20:01,754:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677975599, self.tradeDate='20230305', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22330.0, self.close=22331.7, self.high=22332.6, self.low=22325.8, self.vol=319.517, self.amt=7134331.861, ukdf['pct'].iloc[-1]=8.1e-05 , ukdf['amount'].iloc[-1]=7134331.861, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [05/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24155
self.closeSec=1677975899, self.tradeDate='20230305', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22331.7, self.close=22305.1, self.high=22333.0, self.low=22305.0, self.vol=693.273, self.amt=15473219.5156 
2023-03-05 08:25:01,654:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230305   080000    080459  ...         0.0        0.0       0
5857  20230305   080500    080959  ...         0.0        0.0       0
5858  20230305   081000    081459  ...         0.0        0.0       0
5859  20230305   081500    081959  ...         0.0        0.0       0
5860  20230305   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-05 08:25:01,654:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677975899, self.tradeDate='20230305', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22331.7, self.close=22305.1, self.high=22333.0, self.low=22305.0, self.vol=693.273, self.amt=15473219.5156, ukdf['pct'].iloc[-1]=-0.001191 , ukdf['amount'].iloc[-1]=15473219.5156, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230304   200000    235959  1677945599  ...    719  0.685684  0.274947     NaN
720  20230305   000000    035959  1677959999  ...    720  0.719534  0.411752     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '46887.828', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22237.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [05/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=598
self.closeSec=1677974399, self.tradeDate='20230305', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22238.7, self.close=22335.7, self.high=22358.5, self.low=22147.5, self.vol=51628.209, self.amt=1148460661.7554 
2023-03-05 08:00:01,933:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677974399, self.tradeDate='20230305', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22238.7, self.close=22335.7, self.high=22358.5, self.low=22147.5, self.vol=51628.209, self.amt=1148460661.7554 
2023-03-05 08:00:02,010:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230304   120000    155959  ...  29929.532  6.686327e+08  0.000327
718  20230304   160000    195959  ...  17632.286  3.938497e+08 -0.000385
719  20230304   200000    235959  ...  22528.758  5.033403e+08 -0.001424
720  20230305   000000    035959  ...  29510.497  6.576456e+08 -0.003035
721  20230305   040000    075959  ...  51628.209  1.148461e+09  0.004366

[5 rows x 11 columns]
2023-03-05 08:00:04,376:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230304   120000    155959  1677916799  ...    717  0.598689 -0.049109     NaN
718  20230304   160000    195959  1677931199  ...    718  0.645301  0.120369     NaN
719  20230304   200000    235959  1677945599  ...    719  0.685684  0.274947     NaN
720  20230305   000000    035959  1677959999  ...    720  0.719534  0.411752     NaN
721  20230305   040000    075959  1677974399  ...    721  0.733079  0.486015     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '42745.9575', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22335.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


