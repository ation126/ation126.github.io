# 20230410 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38524
self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28350.1, self.close=28350.9, self.high=28374.6, self.low=28338.3, self.vol=1025.128, self.amt=29066423.2347 
127.0.0.1 - - [10/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-10 08:20:10,102:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230410   075500    075959  ...         0.0        0.0       0
5856  20230410   080000    080459  ...         0.0        0.0       0
5857  20230410   080500    080959  ...         0.0        0.0       0
5858  20230410   081000    081459  ...         0.0        0.0       0
5859  20230410   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 08:20:10,131:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28350.1, self.close=28350.9, self.high=28374.6, self.low=28338.3, self.vol=1025.128, self.amt=29066423.2347, ukdf['pct'].iloc[-1]=3.2e-05 , ukdf['amount'].iloc[-1]=29066423.2347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-711382.6192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28351', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38525
self.closeSec=1681086299, self.tradeDate='20230410', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28350.9, self.close=28335.5, self.high=28351.0, self.low=28334.2, self.vol=527.483, self.amt=14949622.7122 
2023-04-10 08:25:01,598:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230410   080000    080459  ...         0.0        0.0       0
5857  20230410   080500    080959  ...         0.0        0.0       0
5858  20230410   081000    081459  ...         0.0        0.0       0
5859  20230410   081500    081959  ...         0.0        0.0       0
5860  20230410   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 08:25:01,598:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681086299, self.tradeDate='20230410', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28350.9, self.close=28335.5, self.high=28351.0, self.low=28334.2, self.vol=527.483, self.amt=14949622.7122, ukdf['pct'].iloc[-1]=-0.000543 , ukdf['amount'].iloc[-1]=14949622.7122, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-710473.54602574752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28335.89309402', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28350.1, self.close=28350.9, self.high=28374.6, self.low=28338.3 
127.0.0.1 - - [10/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-10 08:20:07,492:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28350.1, self.close=28350.9, self.high=28374.6, self.low=28338.3   
2023-04-10 08:20:08,761:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230410   075500    075959  1681084799  ...  28306.2 -0.000046   1535    5
1536  20230410   080000    080459  1681085099  ...  28270.3 -0.000367   1536    0
1537  20230410   080500    080959  1681085399  ...  28298.9  0.001799   1537    1
1538  20230410   081000    081459  1681085699  ...  28336.0  0.000004   1538    2
1539  20230410   081500    081959  1681085999  ...  28338.3  0.000032   1539    3

[5 rows x 11 columns]
2023-04-10 08:20:08,762:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=11, self.factor=0.49845879779746477, self.count=39091 

self.closeSec=1681086299, self.tradeDate='20230410', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28350.9, self.close=28335.5, self.high=28351.0, self.low=28334.2 
127.0.0.1 - - [10/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-10 08:25:01,502:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1681086299, self.tradeDate='20230410', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28350.9, self.close=28335.5, self.high=28351.0, self.low=28334.2   
2023-04-10 08:25:01,548:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230410   080000    080459  1681085099  ...  28270.3 -0.000367   1536    0
1537  20230410   080500    080959  1681085399  ...  28298.9  0.001799   1537    1
1538  20230410   081000    081459  1681085699  ...  28336.0  0.000004   1538    2
1539  20230410   081500    081959  1681085999  ...  28338.3  0.000032   1539    3
1540  20230410   082000    082459  1681086299  ...  28334.2 -0.000543   1540    4

[5 rows x 11 columns]
2023-04-10 08:25:01,548:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-10 08:00:34,770:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230410    052959  28105.0  ...  47.916667  0.600917  0.475901
5771  20230410    055959  28304.8  ...  47.916667  0.627312  0.449454
5772  20230410    062959  28423.2  ...  47.500000  0.626277  0.429693
5773  20230410    065959  28420.3  ...  47.500000  0.606860  0.415981
5774  20230410    072959  28365.2  ...  47.500000  0.603774  0.403947

[5 rows x 33 columns]
0.5545286506469501
acc is : 0.5545286506469501
2023-04-10 08:00:34,956:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.571182  0.428818       1  ...  0.954477   1.0    0.0  1.004311
537     0  0.550937  0.449063       0  ...  0.954380   1.0    0.0  1.004208
538     0  0.529754  0.470246       0  ...  0.952529   1.0    0.0  1.002261
539     0  0.517666  0.482334       0  ...  0.952230   1.0    0.0  1.001947
540     0  0.526065  0.473935       0  ...  0.950655   1.0    0.0  1.000290

[5 rows x 10 columns]
2023-04-10 08:00:34,992:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.570566  0.429434       1  ...  0.930450   1.0    0.0  0.999891
46     0  0.550335  0.449665       0  ...  0.930355   1.0    0.0  1.003492
47     0  0.529834  0.470166       0  ...  0.928552   1.0    0.0  1.008085
48     0  0.517666  0.482334       0  ...  0.952230   1.0    0.0  1.001947
49     0  0.526065  0.473935       0  ...  0.950655   1.0    0.0  1.000290

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230410   075000    075959  1681084799  28315.2  28309.4 -0.000201
2023-04-10 08:00:02,209:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19544 

self.closeSec=1681085399, self.tradeDate='20230410', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28309.4', self.close='28350'
2023-04-10 08:10:01,610:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1681085399, self.tradeDate='20230410', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28309.4', self.close='28350'
127.0.0.1 - - [10/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-04-10 08:10:01,628:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230410   072000    072959  1681082999  28359.3  28356.3 -0.000106
621  20230410   073000    073959  1681083599  28356.4    28328 -0.000998
622  20230410   074000    074959  1681084199    28328  28315.1 -0.000455
623  20230410   075000    075959  1681084799  28315.2  28309.4 -0.000201
624  20230410   080000    080959  1681085399  28309.4    28350  0.001434
2023-04-10 08:10:01,629:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19545 

self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28349.9', self.close='28350.9'
127.0.0.1 - - [10/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-10 08:20:08,501:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28349.9', self.close='28350.9'
2023-04-10 08:20:09,431:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230410   073000    073959  1681083599  28356.4    28328 -0.000998
622  20230410   074000    074959  1681084199    28328  28315.1 -0.000455
623  20230410   075000    075959  1681084799  28315.2  28309.4 -0.000201
624  20230410   080000    080959  1681085399  28309.4    28350  0.001434
625  20230410   081000    081959  1681085999  28349.9  28350.9  0.000032
2023-04-10 08:20:09,432:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230410   075000    075959  1681084799  28315.2  28309.4
2023-04-10 08:00:02,229:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19545 

self.closeSec=1681085399, self.tradeDate='20230410', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28309.4', self.close='28350'
2023-04-10 08:10:01,600:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1681085399, self.tradeDate='20230410', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28309.4', self.close='28350'
2023-04-10 08:10:01,641:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230410   072000    072959  1681082999  28359.3  28356.3
17469  20230410   073000    073959  1681083599  28356.4    28328
17470  20230410   074000    074959  1681084199    28328  28315.1
17471  20230410   075000    075959  1681084799  28315.2  28309.4
17472  20230410   080000    080959  1681085399  28309.4    28350
2023-04-10 08:10:01,641:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19546 

self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28349.9', self.close='28350.9'
127.0.0.1 - - [10/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-10 08:20:12,215:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28349.9', self.close='28350.9'
2023-04-10 08:20:12,333:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230410   073000    073959  1681083599  28356.4    28328
17470  20230410   074000    074959  1681084199    28328  28315.1
17471  20230410   075000    075959  1681084799  28315.2  28309.4
17472  20230410   080000    080959  1681085399  28309.4    28350
17473  20230410   081000    081959  1681085999  28349.9  28350.9
2023-04-10 08:20:12,333:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230410   075000    075959  1681084799  28315.2  28309.4
2023-04-10 08:00:02,213:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19545 

self.closeSec=1681085399, self.tradeDate='20230410', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28309.4', self.close='28350'
2023-04-10 08:10:01,580:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1681085399, self.tradeDate='20230410', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28309.4', self.close='28350'
2023-04-10 08:10:01,636:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230410   072000    072959  1681082999  28359.3  28356.3
12141  20230410   073000    073959  1681083599  28356.4    28328
12142  20230410   074000    074959  1681084199    28328  28315.1
12143  20230410   075000    075959  1681084799  28315.2  28309.4
12144  20230410   080000    080959  1681085399  28309.4    28350
2023-04-10 08:10:01,637:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19546 

self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28349.9', self.close='28350.9'
127.0.0.1 - - [10/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-10 08:20:11,603:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28349.9', self.close='28350.9'
2023-04-10 08:20:11,933:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230410   073000    073959  1681083599  28356.4    28328
12142  20230410   074000    074959  1681084199    28328  28315.1
12143  20230410   075000    075959  1681084799  28315.2  28309.4
12144  20230410   080000    080959  1681085399  28309.4    28350
12145  20230410   081000    081959  1681085999  28349.9  28350.9
2023-04-10 08:20:11,934:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34522
self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28350.1, self.close=28350.9, self.high=28374.6, self.low=28338.3, self.vol=1025.128, self.amt=29066423.2347 
127.0.0.1 - - [10/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-10 08:20:09,832:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230410   075500    075959  ...         0.0        0.0       0
5856  20230410   080000    080459  ...         0.0        0.0       0
5857  20230410   080500    080959  ...         0.0        0.0       0
5858  20230410   081000    081459  ...         0.0        0.0       0
5859  20230410   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 08:20:09,862:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681085999, self.tradeDate='20230410', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28350.1, self.close=28350.9, self.high=28374.6, self.low=28338.3, self.vol=1025.128, self.amt=29066423.2347, ukdf['pct'].iloc[-1]=3.2e-05 , ukdf['amount'].iloc[-1]=29066423.2347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34523
self.closeSec=1681086299, self.tradeDate='20230410', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28350.9, self.close=28335.5, self.high=28351.0, self.low=28334.2, self.vol=527.483, self.amt=14949622.7122 
127.0.0.1 - - [10/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-10 08:25:01,600:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230410   080000    080459  ...         0.0        0.0       0
5857  20230410   080500    080959  ...         0.0        0.0       0
5858  20230410   081000    081459  ...         0.0        0.0       0
5859  20230410   081500    081959  ...         0.0        0.0       0
5860  20230410   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-10 08:25:01,600:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681086299, self.tradeDate='20230410', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28350.9, self.close=28335.5, self.high=28351.0, self.low=28334.2, self.vol=527.483, self.amt=14949622.7122, ukdf['pct'].iloc[-1]=-0.000543 , ukdf['amount'].iloc[-1]=14949622.7122, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230409   200000    235959  1681055999  ...    719  0.009779 -1.214057    -1.0
720  20230410   000000    035959  1681070399  ...    720  0.044729 -1.044944    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '13386.616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28141.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=814
self.closeSec=1681084799, self.tradeDate='20230410', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28132.4, self.close=28309.4, self.high=28539.1, self.low=28077.1, self.vol=91999.792, self.amt=2607345409.9571 
127.0.0.1 - - [10/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-10 08:00:01,940:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681084799, self.tradeDate='20230410', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28132.4, self.close=28309.4, self.high=28539.1, self.low=28077.1, self.vol=91999.792, self.amt=2607345409.9571 
2023-04-10 08:00:02,006:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230409   120000    155959  ...  47649.419  1.330187e+09 -0.004420
718  20230409   160000    195959  ...  31551.572  8.794584e+08  0.001115
719  20230409   200000    235959  ...  35449.263  9.880658e+08 -0.001637
720  20230410   000000    035959  ...  69130.038  1.941111e+09  0.009285
721  20230410   040000    075959  ...  91999.792  2.607345e+09  0.006292

[5 rows x 11 columns]
2023-04-10 08:00:04,732:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230409   120000    155959  1681027199  ...    717  0.209839 -0.237609     NaN
718  20230409   160000    195959  1681041599  ...    718  0.118720 -0.686927    -1.0
719  20230409   200000    235959  1681055999  ...    719  0.009779 -1.214057    -1.0
720  20230410   000000    035959  1681070399  ...    720  0.044729 -1.044944    -1.0
721  20230410   040000    075959  1681084799  ...    721  0.359606  0.471012     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '4643.41948550696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28309.65433333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


