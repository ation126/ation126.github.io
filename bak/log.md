# 20230329 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35068
self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27253.5, self.close=27279.9, self.high=27281.9, self.low=27245.4, self.vol=617.965, self.amt=16846541.1786 
127.0.0.1 - - [29/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-29 08:20:07,887:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230329   075500    075959  ...         0.0        0.0       0
5856  20230329   080000    080459  ...         0.0        0.0       0
5857  20230329   080500    080959  ...         0.0        0.0       0
5858  20230329   081000    081459  ...         0.0        0.0       0
5859  20230329   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 08:20:07,917:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27253.5, self.close=27279.9, self.high=27281.9, self.low=27245.4, self.vol=617.965, self.amt=16846541.1786, ukdf['pct'].iloc[-1]=0.000965 , ukdf['amount'].iloc[-1]=16846541.1786, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-646928.1056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27279.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35069
self.closeSec=1680049499, self.tradeDate='20230329', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27280.0, self.close=27306.1, self.high=27329.9, self.low=27270.4, self.vol=1647.322, self.amt=44968671.9539 
127.0.0.1 - - [29/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-29 08:25:01,607:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230329   080000    080459  ...         0.0        0.0       0
5857  20230329   080500    080959  ...         0.0        0.0       0
5858  20230329   081000    081459  ...         0.0        0.0       0
5859  20230329   081500    081959  ...         0.0        0.0       0
5860  20230329   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 08:25:01,614:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680049499, self.tradeDate='20230329', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27280.0, self.close=27306.1, self.high=27329.9, self.low=27270.4, self.vol=1647.322, self.amt=44968671.9539, ukdf['pct'].iloc[-1]=0.00096 , ukdf['amount'].iloc[-1]=44968671.9539, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-648529.26637908096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27306.50796296', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27253.5, self.close=27279.9, self.high=27281.9, self.low=27245.4 
127.0.0.1 - - [29/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-29 08:20:05,687:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27253.5, self.close=27279.9, self.high=27281.9, self.low=27245.4   
2023-03-29 08:20:06,887:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230329   075500    075959  1680047999  ...  27240.0 -0.000253   1535    5
1536  20230329   080000    080459  1680048299  ...  27233.5  0.000936   1536    0
1537  20230329   080500    080959  1680048599  ...  27242.2 -0.000286   1537    1
1538  20230329   081000    081459  1680048899  ...  27252.6 -0.000506   1538    2
1539  20230329   081500    081959  1680049199  ...  27245.4  0.000965   1539    3

[5 rows x 11 columns]
2023-03-29 08:20:06,897:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=9, self.factor=0.5370460360690262, self.count=35635 

self.closeSec=1680049499, self.tradeDate='20230329', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27280.0, self.close=27306.1, self.high=27329.9, self.low=27270.4 
2023-03-29 08:25:01,501:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680049499, self.tradeDate='20230329', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27280.0, self.close=27306.1, self.high=27329.9, self.low=27270.4   
2023-03-29 08:25:01,554:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230329   080000    080459  1680048299  ...  27233.5  0.000936   1536    0
1537  20230329   080500    080959  1680048599  ...  27242.2 -0.000286   1537    1
1538  20230329   081000    081459  1680048899  ...  27252.6 -0.000506   1538    2
1539  20230329   081500    081959  1680049199  ...  27245.4  0.000965   1539    3
1540  20230329   082000    082459  1680049499  ...  27270.4  0.000960   1540    4

[5 rows x 11 columns]
2023-03-29 08:25:01,556:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-29 08:00:35,208:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230329    052959  27293.9  ...  47.500000  0.503109  0.436497
5771  20230329    055959  27249.9  ...  47.083333  0.492867  0.431615
5772  20230329    062959  27176.7  ...  47.500000  0.496137  0.425342
5773  20230329    065959  27199.6  ...  47.500000  0.497494  0.418784
5774  20230329    072959  27209.0  ...  47.500000  0.505191  0.408678

[5 rows x 33 columns]
0.512014787430684
acc is : 0.512014787430684
2023-03-29 08:00:35,380:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.514935  0.485065       0  ...  0.935452   1.0    0.0  1.024507
537     0  0.508376  0.491624       1  ...  0.936240   1.0    0.0  1.025371
538     0  0.522416  0.477584       1  ...  0.936563   1.0    0.0  1.025725
539     0  0.525113  0.474887       1  ...  0.938395   1.0    0.0  1.027731
540     0  0.540260  0.459740       0  ...  0.937964   1.0    0.0  1.027259

[5 rows x 10 columns]
2023-03-29 08:00:35,418:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515611  0.484389       0  ...  0.935452   1.0    0.0  1.028929
46     0  0.508465  0.491535       1  ...  0.928945   1.0    0.0  1.027625
47     0  0.522804  0.477196       1  ...  0.936563   1.0    0.0  1.031234
48     0  0.525130  0.474870       1  ...  0.938395   1.0    0.0  1.027731
49     0  0.540260  0.459740       0  ...  0.937964   1.0    0.0  1.027259

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230329   075000    075959  1680047999  27265.8  27249.7 -0.000590
2023-03-29 08:00:02,039:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17816 

self.closeSec=1680048599, self.tradeDate='20230329', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27249.7', self.close='27267.4'
2023-03-29 08:10:01,758:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680048599, self.tradeDate='20230329', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27249.7', self.close='27267.4'
127.0.0.1 - - [29/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-29 08:10:01,786:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230329   072000    072959  1680046199  27239.9  27262.2  0.000819
621  20230329   073000    073959  1680046799  27262.2  27244.5 -0.000649
622  20230329   074000    074959  1680047399  27244.6  27265.8  0.000782
623  20230329   075000    075959  1680047999  27265.8  27249.7 -0.000590
624  20230329   080000    080959  1680048599  27249.7  27267.4  0.000650
2023-03-29 08:10:01,786:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17817 

self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27262.7', self.close='27279.9'
127.0.0.1 - - [29/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 08:20:07,197:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27262.7', self.close='27279.9'
2023-03-29 08:20:07,869:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230329   073000    073959  1680046799  27262.2  27244.5 -0.000649
622  20230329   074000    074959  1680047399  27244.6  27265.8  0.000782
623  20230329   075000    075959  1680047999  27265.8  27249.7 -0.000590
624  20230329   080000    080959  1680048599  27249.7  27267.4  0.000650
625  20230329   081000    081959  1680049199  27262.7  27279.9  0.000458
2023-03-29 08:20:07,870:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230329   075000    075959  1680047999  27265.8  27249.7
2023-03-29 08:00:02,077:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17817 

self.closeSec=1680048599, self.tradeDate='20230329', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27249.7', self.close='27267.4'
2023-03-29 08:10:01,734:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680048599, self.tradeDate='20230329', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27249.7', self.close='27267.4'
127.0.0.1 - - [29/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-29 08:10:01,797:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230329   072000    072959  1680046199  27239.9  27262.2
17469  20230329   073000    073959  1680046799  27262.2  27244.5
17470  20230329   074000    074959  1680047399  27244.6  27265.8
17471  20230329   075000    075959  1680047999  27265.8  27249.7
17472  20230329   080000    080959  1680048599  27249.7  27267.4
2023-03-29 08:10:01,797:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17818 

self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27262.7', self.close='27279.9'
127.0.0.1 - - [29/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 08:20:10,038:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27262.7', self.close='27279.9'
2023-03-29 08:20:10,158:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230329   073000    073959  1680046799  27262.2  27244.5
17470  20230329   074000    074959  1680047399  27244.6  27265.8
17471  20230329   075000    075959  1680047999  27265.8  27249.7
17472  20230329   080000    080959  1680048599  27249.7  27267.4
17473  20230329   081000    081959  1680049199  27262.7  27279.9
2023-03-29 08:20:10,158:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230329   075000    075959  1680047999  27265.8  27249.7
2023-03-29 08:00:02,019:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [29/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17817 

self.closeSec=1680048599, self.tradeDate='20230329', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27249.7', self.close='27267.4'
2023-03-29 08:10:01,752:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680048599, self.tradeDate='20230329', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27249.7', self.close='27267.4'
2023-03-29 08:10:01,793:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230329   072000    072959  1680046199  27239.9  27262.2
12141  20230329   073000    073959  1680046799  27262.2  27244.5
12142  20230329   074000    074959  1680047399  27244.6  27265.8
12143  20230329   075000    075959  1680047999  27265.8  27249.7
12144  20230329   080000    080959  1680048599  27249.7  27267.4
2023-03-29 08:10:01,793:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17818 

self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27262.7', self.close='27279.9'
127.0.0.1 - - [29/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-29 08:20:09,541:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27262.7', self.close='27279.9'
2023-03-29 08:20:09,826:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230329   073000    073959  1680046799  27262.2  27244.5
12142  20230329   074000    074959  1680047399  27244.6  27265.8
12143  20230329   075000    075959  1680047999  27265.8  27249.7
12144  20230329   080000    080959  1680048599  27249.7  27267.4
12145  20230329   081000    081959  1680049199  27262.7  27279.9
2023-03-29 08:20:09,827:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31066
self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27253.5, self.close=27279.9, self.high=27281.9, self.low=27245.4, self.vol=617.965, self.amt=16846541.1786 
127.0.0.1 - - [29/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-29 08:20:06,877:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230329   075500    075959  ...         0.0        0.0       0
5856  20230329   080000    080459  ...         0.0        0.0       0
5857  20230329   080500    080959  ...         0.0        0.0       0
5858  20230329   081000    081459  ...         0.0        0.0       0
5859  20230329   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 08:20:06,907:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680049199, self.tradeDate='20230329', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27253.5, self.close=27279.9, self.high=27281.9, self.low=27245.4, self.vol=617.965, self.amt=16846541.1786, ukdf['pct'].iloc[-1]=0.000965 , ukdf['amount'].iloc[-1]=16846541.1786, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [29/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31067
self.closeSec=1680049499, self.tradeDate='20230329', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27280.0, self.close=27306.1, self.high=27329.9, self.low=27270.4, self.vol=1647.322, self.amt=44968671.9539 
2023-03-29 08:25:01,576:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230329   080000    080459  ...         0.0        0.0       0
5857  20230329   080500    080959  ...         0.0        0.0       0
5858  20230329   081000    081459  ...         0.0        0.0       0
5859  20230329   081500    081959  ...         0.0        0.0       0
5860  20230329   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-29 08:25:01,577:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680049499, self.tradeDate='20230329', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27280.0, self.close=27306.1, self.high=27329.9, self.low=27270.4, self.vol=1647.322, self.amt=44968671.9539, ukdf['pct'].iloc[-1]=0.00096 , ukdf['amount'].iloc[-1]=44968671.9539, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230328   200000    235959  1680019199  ...    719  0.235390 -0.710596    -1.0
720  20230329   000000    035959  1680033599  ...    720  0.197143 -0.780871    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '35048.5356', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27438.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=742
self.closeSec=1680047999, self.tradeDate='20230329', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27412.1, self.close=27249.7, self.high=27482.5, self.low=27080.0, self.vol=58236.084, self.amt=1587363663.21798 
127.0.0.1 - - [29/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-03-29 08:00:01,879:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680047999, self.tradeDate='20230329', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27412.1, self.close=27249.7, self.high=27482.5, self.low=27080.0, self.vol=58236.084, self.amt=1587363663.21798 
2023-03-29 08:00:01,943:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230328   120000    155959  ...   58393.922  1.575997e+09 -0.000078
718  20230328   160000    195959  ...  128635.011  3.456745e+09  0.003421
719  20230328   200000    235959  ...  123639.089  3.334585e+09 -0.002244
720  20230329   000000    035959  ...  151133.821  4.096441e+09  0.015831
721  20230329   040000    075959  ...   58236.084  1.587364e+09 -0.005924

[5 rows x 11 columns]
2023-03-29 08:00:05,143:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230328   120000    155959  1679990399  ...    717  0.178320 -0.876850    -1.0
718  20230328   160000    195959  1680004799  ...    718  0.190310 -0.830932    -1.0
719  20230328   200000    235959  1680019199  ...    719  0.235390 -0.710596    -1.0
720  20230329   000000    035959  1680033599  ...    720  0.197143 -0.780871    -1.0
721  20230329   040000    075959  1680047999  ...    721  0.185511 -0.789420    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '45005.628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27253.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


