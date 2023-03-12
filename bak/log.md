# 20230312 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30172
self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=20344.2, self.close=20368.0, self.high=20402.6, self.low=20344.1, self.vol=2334.978, self.amt=47590444.7405 
127.0.0.1 - - [12/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 08:20:03,141:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230312   075500    075959  ...         0.0        0.0       0
5856  20230312   080000    080459  ...         0.0        0.0       0
5857  20230312   080500    080959  ...         0.0        0.0       0
5858  20230312   081000    081459  ...         0.0        0.0       0
5859  20230312   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 08:20:03,162:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=20344.2, self.close=20368.0, self.high=20402.6, self.low=20344.1, self.vol=2334.978, self.amt=47590444.7405, ukdf['pct'].iloc[-1]=0.00117 , ukdf['amount'].iloc[-1]=47590444.7405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-231023.47348662768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20368.42977743', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30173
self.closeSec=1678580699, self.tradeDate='20230312', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=20368.1, self.close=20380.7, self.high=20397.2, self.low=20363.8, self.vol=1777.709, self.amt=36227293.422 
127.0.0.1 - - [12/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-12 08:25:01,606:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230312   080000    080459  ...         0.0        0.0       0
5857  20230312   080500    080959  ...         0.0        0.0       0
5858  20230312   081000    081459  ...         0.0        0.0       0
5859  20230312   081500    081959  ...         0.0        0.0       0
5860  20230312   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 08:25:01,607:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678580699, self.tradeDate='20230312', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=20368.1, self.close=20380.7, self.high=20397.2, self.low=20363.8, self.vol=1777.709, self.amt=36227293.422, ukdf['pct'].iloc[-1]=0.000624 , ukdf['amount'].iloc[-1]=36227293.422, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-231820.63635174976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20381.67696676', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [12/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -

self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=20344.2, self.close=20368.0, self.high=20402.6, self.low=20344.1 
2023-03-12 08:20:01,826:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=20344.2, self.close=20368.0, self.high=20402.6, self.low=20344.1   
2023-03-12 08:20:01,923:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230312   075500    075959  1678579199  ...  20435.8 -0.001499   1535    5
1536  20230312   080000    080459  1678579499  ...  20421.4 -0.000240   1536    0
1537  20230312   080500    080959  1678579799  ...  20440.1  0.000127   1537    1
1538  20230312   081000    081459  1678580099  ...  20328.0 -0.004930   1538    2
1539  20230312   081500    081959  1678580399  ...  20344.1  0.001170   1539    3

[5 rows x 11 columns]
2023-03-12 08:20:01,923:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.53480838248595, self.count=30739 

self.closeSec=1678580699, self.tradeDate='20230312', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=20368.1, self.close=20380.7, self.high=20397.2, self.low=20363.8 
127.0.0.1 - - [12/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-12 08:25:01,502:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678580699, self.tradeDate='20230312', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=20368.1, self.close=20380.7, self.high=20397.2, self.low=20363.8   
2023-03-12 08:25:01,591:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230312   080000    080459  1678579499  ...  20421.4 -0.000240   1536    0
1537  20230312   080500    080959  1678579799  ...  20440.1  0.000127   1537    1
1538  20230312   081000    081459  1678580099  ...  20328.0 -0.004930   1538    2
1539  20230312   081500    081959  1678580399  ...  20344.1  0.001170   1539    3
1540  20230312   082000    082459  1678580699  ...  20363.8  0.000624   1540    4

[5 rows x 11 columns]
2023-03-12 08:25:01,591:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-12 08:00:37,097:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230312    052959  20338.5  ...  43.333333  0.491450  0.522041
5771  20230312    055959  20296.4  ...  43.333333  0.499511  0.508672
5772  20230312    062959  20347.3  ...  43.333333  0.505168  0.485870
5773  20230312    065959  20383.1  ...  42.916667  0.495647  0.468358
5774  20230312    072959  20323.3  ...  43.333333  0.507046  0.442783

[5 rows x 33 columns]
0.5545286506469501
acc is : 0.5545286506469501
2023-03-12 08:00:37,258:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.489435  0.510565       1  ...  0.929399   1.0    0.0  0.866196
537     0  0.542131  0.457869       1  ...  0.931039   1.0    0.0  0.867724
538     0  0.543037  0.456963       0  ...  0.928308   1.0    0.0  0.865178
539     1  0.482961  0.517039       1  ...  0.931592   1.0    0.0  0.868239
540     0  0.536993  0.463007       1  ...  0.933972   1.0    0.0  0.870457

[5 rows x 10 columns]
2023-03-12 08:00:37,296:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489320  0.510680       1  ...  0.929399   1.0    0.0  0.865426
46     0  0.542380  0.457620       1  ...  0.939931   1.0    0.0  0.868194
47     0  0.543220  0.456780       0  ...  0.937174   1.0    0.0  0.866784
48     1  0.482961  0.517039       1  ...  0.931592   1.0    0.0  0.868239
49     0  0.536993  0.463007       1  ...  0.933972   1.0    0.0  0.870457

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.476', 'enterprice': '20021.1', 'countrevence': '0', 'unrealprofit': '13669.42869775792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20442.00863092', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230312   075000    075959  1678579199  20399.4  20447.3  0.002343
2023-03-12 08:00:02,504:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15368 

self.closeSec=1678579799, self.tradeDate='20230312', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20447.3', self.close='20445'
2023-03-12 08:10:01,725:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678579799, self.tradeDate='20230312', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20447.3', self.close='20445'
127.0.0.1 - - [12/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-12 08:10:01,732:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230312   072000    072959  1678577399  20355.7  20395.2  0.001936
621  20230312   073000    073959  1678577999  20395.3    20428  0.001608
622  20230312   074000    074959  1678578599    20428  20399.5 -0.001395
623  20230312   075000    075959  1678579199  20399.4  20447.3  0.002343
624  20230312   080000    080959  1678579799  20447.3    20445 -0.000112
2023-03-12 08:10:01,744:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15369 

self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='20445', self.close='20368'
127.0.0.1 - - [12/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 08:20:02,923:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='20445', self.close='20368'
2023-03-12 08:20:03,382:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230312   073000    073959  1678577999  20395.3    20428  0.001608
622  20230312   074000    074959  1678578599    20428  20399.5 -0.001395
623  20230312   075000    075959  1678579199  20399.4  20447.3  0.002343
624  20230312   080000    080959  1678579799  20447.3    20445 -0.000112
625  20230312   081000    081959  1678580399    20445    20368 -0.003766
2023-03-12 08:20:03,390:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230312   075000    075959  1678579199  20399.4  20447.3
2023-03-12 08:00:02,512:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15369 

self.closeSec=1678579799, self.tradeDate='20230312', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20447.3', self.close='20445'
2023-03-12 08:10:01,713:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678579799, self.tradeDate='20230312', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20447.3', self.close='20445'
2023-03-12 08:10:01,747:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230312   072000    072959  1678577399  20355.7  20395.2
17469  20230312   073000    073959  1678577999  20395.3    20428
17470  20230312   074000    074959  1678578599    20428  20399.5
17471  20230312   075000    075959  1678579199  20399.4  20447.3
17472  20230312   080000    080959  1678579799  20447.3    20445
2023-03-12 08:10:01,747:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15370 

self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='20445', self.close='20368'
127.0.0.1 - - [12/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 08:20:04,193:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='20445', self.close='20368'
2023-03-12 08:20:04,377:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230312   073000    073959  1678577999  20395.3    20428
17470  20230312   074000    074959  1678578599    20428  20399.5
17471  20230312   075000    075959  1678579199  20399.4  20447.3
17472  20230312   080000    080959  1678579799  20447.3    20445
17473  20230312   081000    081959  1678580399    20445    20368
2023-03-12 08:20:04,377:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230312   075000    075959  1678579199  20399.4  20447.3
2023-03-12 08:00:02,508:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [12/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15369 

self.closeSec=1678579799, self.tradeDate='20230312', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20447.3', self.close='20445'
2023-03-12 08:10:01,736:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678579799, self.tradeDate='20230312', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20447.3', self.close='20445'
2023-03-12 08:10:01,753:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230312   072000    072959  1678577399  20355.7  20395.2
12141  20230312   073000    073959  1678577999  20395.3    20428
12142  20230312   074000    074959  1678578599    20428  20399.5
12143  20230312   075000    075959  1678579199  20399.4  20447.3
12144  20230312   080000    080959  1678579799  20447.3    20445
2023-03-12 08:10:01,753:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15370 

self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='20445', self.close='20368'
127.0.0.1 - - [12/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-12 08:20:04,134:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='20445', self.close='20368'
2023-03-12 08:20:04,254:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230312   073000    073959  1678577999  20395.3    20428
12142  20230312   074000    074959  1678578599    20428  20399.5
12143  20230312   075000    075959  1678579199  20399.4  20447.3
12144  20230312   080000    080959  1678579799  20447.3    20445
12145  20230312   081000    081959  1678580399    20445    20368
2023-03-12 08:20:04,254:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26170
self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=20344.2, self.close=20368.0, self.high=20402.6, self.low=20344.1, self.vol=2334.978, self.amt=47590444.7405 
127.0.0.1 - - [12/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-12 08:20:01,694:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230312   075500    075959  ...         0.0        0.0       0
5856  20230312   080000    080459  ...         0.0        0.0       0
5857  20230312   080500    080959  ...         0.0        0.0       0
5858  20230312   081000    081459  ...         0.0        0.0       0
5859  20230312   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 08:20:01,697:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678580399, self.tradeDate='20230312', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=20344.2, self.close=20368.0, self.high=20402.6, self.low=20344.1, self.vol=2334.978, self.amt=47590444.7405, ukdf['pct'].iloc[-1]=0.00117 , ukdf['amount'].iloc[-1]=47590444.7405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [12/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26171
self.closeSec=1678580699, self.tradeDate='20230312', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=20368.1, self.close=20380.7, self.high=20397.2, self.low=20363.8, self.vol=1777.709, self.amt=36227293.422 
2023-03-12 08:25:01,608:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230312   080000    080459  ...         0.0        0.0       0
5857  20230312   080500    080959  ...         0.0        0.0       0
5858  20230312   081000    081459  ...         0.0        0.0       0
5859  20230312   081500    081959  ...         0.0        0.0       0
5860  20230312   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-12 08:25:01,609:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678580699, self.tradeDate='20230312', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=20368.1, self.close=20380.7, self.high=20397.2, self.low=20363.8, self.vol=1777.709, self.amt=36227293.422, ukdf['pct'].iloc[-1]=0.000624 , ukdf['amount'].iloc[-1]=36227293.422, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230311   200000    235959  1678550399  ...    719  0.778201  0.737284     1.0
720  20230312   000000    035959  1678564799  ...    720  0.766253  0.689669     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '8125.21421440575', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20215.54794831', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=640
self.closeSec=1678579199, self.tradeDate='20230312', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=20209.9, self.close=20447.3, self.high=20531.0, self.low=20206.7, self.vol=88653.535, self.amt=1804985508.7695 
127.0.0.1 - - [12/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-12 08:00:02,193:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678579199, self.tradeDate='20230312', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=20209.9, self.close=20447.3, self.high=20531.0, self.low=20206.7, self.vol=88653.535, self.amt=1804985508.7695 
2023-03-12 08:00:02,213:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230311   120000    155959  ...  139731.915  2.816961e+09 -0.026338
718  20230311   160000    195959  ...  150197.076  3.006404e+09  0.011746
719  20230311   200000    235959  ...   70208.550  1.410859e+09 -0.001255
720  20230312   000000    035959  ...   96711.737  1.950538e+09  0.007864
721  20230312   040000    075959  ...   88653.535  1.804986e+09  0.011742

[5 rows x 11 columns]
2023-03-12 08:00:05,632:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230311   120000    155959  1678521599  ...    717  0.719905  0.545570     NaN
718  20230311   160000    195959  1678535999  ...    718  0.746170  0.634227     1.0
719  20230311   200000    235959  1678550399  ...    719  0.778201  0.737284     1.0
720  20230312   000000    035959  1678564799  ...    720  0.766253  0.689669     1.0
721  20230312   040000    075959  1678579199  ...    721  0.762446  0.673127     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '21062.7725', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20447.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


