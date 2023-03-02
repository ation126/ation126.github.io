# 20230302 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27292
self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23621.4, self.close=23709.6, self.high=23731.9, self.low=23611.4, self.vol=5231.851, self.amt=123962761.6742 
127.0.0.1 - - [02/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 08:20:01,909:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230302   075500    075959  ...         0.0        0.0       0
5856  20230302   080000    080459  ...         0.0        0.0       0
5857  20230302   080500    080959  ...         0.0        0.0       0
5858  20230302   081000    081459  ...         0.0        0.0       0
5859  20230302   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 08:20:01,911:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23621.4, self.close=23709.6, self.high=23731.9, self.low=23611.4, self.vol=5231.851, self.amt=123962761.6742, ukdf['pct'].iloc[-1]=0.00373 , ukdf['amount'].iloc[-1]=123962761.6742, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-432515', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23716.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27293
self.closeSec=1677716699, self.tradeDate='20230302', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23709.5, self.close=23707.6, self.high=23790.5, self.low=23707.0, self.vol=5839.265, self.amt=138694504.5512 
2023-03-02 08:25:01,716:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230302   080000    080459  ...         0.0        0.0       0
5857  20230302   080500    080959  ...         0.0        0.0       0
5858  20230302   081000    081459  ...         0.0        0.0       0
5859  20230302   081500    081959  ...         0.0        0.0       0
5860  20230302   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 08:25:01,721:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677716699, self.tradeDate='20230302', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23709.5, self.close=23707.6, self.high=23790.5, self.low=23707.0, self.vol=5839.265, self.amt=138694504.5512, ukdf['pct'].iloc[-1]=-8.4e-05 , ukdf['amount'].iloc[-1]=138694504.5512, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-432268.26040857952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23712.69970102', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=132, self.factor=0.45463672833937985, self.count=27858 

self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23621.4, self.close=23709.6, self.high=23731.9, self.low=23611.4 
2023-03-02 08:20:01,508:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23621.4, self.close=23709.6, self.high=23731.9, self.low=23611.4   
2023-03-02 08:20:01,563:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230302   075500    075959  1677715199  ...  23614.6 -0.000698   1535    5
1536  20230302   080000    080459  1677715499  ...  23603.6 -0.000686   1536    0
1537  20230302   080500    080959  1677715799  ...  23603.5  0.001445   1537    1
1538  20230302   081000    081459  1677716099  ...  23621.4 -0.000685   1538    2
1539  20230302   081500    081959  1677716399  ...  23611.4  0.003730   1539    3

[5 rows x 11 columns]
2023-03-02 08:20:01,563:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=132, self.factor=0.45463672833937985, self.count=27859 

self.closeSec=1677716699, self.tradeDate='20230302', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23709.5, self.close=23707.6, self.high=23790.5, self.low=23707.0 
2023-03-02 08:25:01,637:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677716699, self.tradeDate='20230302', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23709.5, self.close=23707.6, self.high=23790.5, self.low=23707.0   
127.0.0.1 - - [02/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-02 08:25:01,695:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230302   080000    080459  1677715499  ...  23603.6 -0.000686   1536    0
1537  20230302   080500    080959  1677715799  ...  23603.5  0.001445   1537    1
1538  20230302   081000    081459  1677716099  ...  23621.4 -0.000685   1538    2
1539  20230302   081500    081959  1677716399  ...  23611.4  0.003730   1539    3
1540  20230302   082000    082459  1677716699  ...  23707.0 -0.000084   1540    4

[5 rows x 11 columns]
2023-03-02 08:25:01,695:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-02 08:00:34,755:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230302    052959  23406.6  ...  50.416667  0.496377  0.409941
5771  20230302    055959  23482.5  ...  50.833333  0.508637  0.422379
5772  20230302    062959  23544.8  ...  50.833333  0.492843  0.440687
5773  20230302    065959  23464.4  ...  50.833333  0.504582  0.456115
5774  20230302    072959  23524.6  ...  50.833333  0.509890  0.468032

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2023-03-02 08:00:34,920:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.499016  0.500984       1  ...  0.841999  -1.0    0.0  0.953100
537     0  0.508274  0.491726       0  ...  0.844878  -1.0    0.0  0.949841
538     0  0.503901  0.496099       1  ...  0.842711  -1.0    0.0  0.952278
539     0  0.531697  0.468303       1  ...  0.841722  -1.0    0.0  0.953395
540     0  0.527963  0.472037       1  ...  0.839306  -1.0    0.0  0.956132

[5 rows x 10 columns]
2023-03-02 08:00:34,953:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498547  0.501453       1  ...  0.826171  -1.0    0.0  0.954394
46     0  0.508247  0.491753       0  ...  0.844878  -1.0    0.0  0.951621
47     0  0.504414  0.495586       1  ...  0.826231  -1.0    0.0  0.954325
48     0  0.531697  0.468303       1  ...  0.841722  -1.0    0.0  0.953395
49     0  0.527963  0.472037       1  ...  0.839306  -1.0    0.0  0.956132

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.484', 'enterprice': '23376.7', 'countrevence': '0', 'unrealprofit': '-8032.84489221408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23623.98619912', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230302   075000    075959  1677715199  23656.9  23619.8 -0.001568
2023-03-02 08:00:02,053:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13928 

self.closeSec=1677715799, self.tradeDate='20230302', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23619.8', self.close='23637.7'
2023-03-02 08:10:01,611:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677715799, self.tradeDate='20230302', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23619.8', self.close='23637.7'
2023-03-02 08:10:01,627:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230302   072000    072959  1677713399  23514.8  23552.2  0.001595
621  20230302   073000    073959  1677713999  23552.2  23591.1  0.001652
622  20230302   074000    074959  1677714599  23591.1  23656.9  0.002789
623  20230302   075000    075959  1677715199  23656.9  23619.8 -0.001568
624  20230302   080000    080959  1677715799  23619.8  23637.7  0.000758
2023-03-02 08:10:01,627:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13929 

self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23637.7', self.close='23709.6'
127.0.0.1 - - [02/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 08:20:01,633:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23637.7', self.close='23709.6'
2023-03-02 08:20:01,672:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230302   073000    073959  1677713999  23552.2  23591.1  0.001652
622  20230302   074000    074959  1677714599  23591.1  23656.9  0.002789
623  20230302   075000    075959  1677715199  23656.9  23619.8 -0.001568
624  20230302   080000    080959  1677715799  23619.8  23637.7  0.000758
625  20230302   081000    081959  1677716399  23637.7  23709.6  0.003042
2023-03-02 08:20:01,673:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230302   075000    075959  1677715199  23656.9  23619.8
2023-03-02 08:00:02,080:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13929 

self.closeSec=1677715799, self.tradeDate='20230302', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23619.8', self.close='23637.7'
2023-03-02 08:10:01,640:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677715799, self.tradeDate='20230302', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23619.8', self.close='23637.7'
2023-03-02 08:10:01,675:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230302   072000    072959  1677713399  23514.8  23552.2
17469  20230302   073000    073959  1677713999  23552.2  23591.1
17470  20230302   074000    074959  1677714599  23591.1  23656.9
17471  20230302   075000    075959  1677715199  23656.9  23619.8
17472  20230302   080000    080959  1677715799  23619.8  23637.7
2023-03-02 08:10:01,675:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13930 

self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23637.7', self.close='23709.6'
2023-03-02 08:20:01,677:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23637.7', self.close='23709.6'
2023-03-02 08:20:01,691:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230302   073000    073959  1677713999  23552.2  23591.1
17470  20230302   074000    074959  1677714599  23591.1  23656.9
17471  20230302   075000    075959  1677715199  23656.9  23619.8
17472  20230302   080000    080959  1677715799  23619.8  23637.7
17473  20230302   081000    081959  1677716399  23637.7  23709.6
2023-03-02 08:20:01,692:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230302   075000    075959  1677715199  23656.9  23619.8
2023-03-02 08:00:02,064:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [02/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13929 

self.closeSec=1677715799, self.tradeDate='20230302', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23619.8', self.close='23637.7'
2023-03-02 08:10:01,597:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677715799, self.tradeDate='20230302', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23619.8', self.close='23637.7'
2023-03-02 08:10:01,623:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230302   072000    072959  1677713399  23514.8  23552.2
12141  20230302   073000    073959  1677713999  23552.2  23591.1
12142  20230302   074000    074959  1677714599  23591.1  23656.9
12143  20230302   075000    075959  1677715199  23656.9  23619.8
12144  20230302   080000    080959  1677715799  23619.8  23637.7
2023-03-02 08:10:01,624:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13930 

self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23637.7', self.close='23709.6'
127.0.0.1 - - [02/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 08:20:01,657:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23637.7', self.close='23709.6'
2023-03-02 08:20:01,682:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230302   073000    073959  1677713999  23552.2  23591.1
12142  20230302   074000    074959  1677714599  23591.1  23656.9
12143  20230302   075000    075959  1677715199  23656.9  23619.8
12144  20230302   080000    080959  1677715799  23619.8  23637.7
12145  20230302   081000    081959  1677716399  23637.7  23709.6
2023-03-02 08:20:01,682:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [02/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23290
self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23621.4, self.close=23709.6, self.high=23731.9, self.low=23611.4, self.vol=5231.851, self.amt=123962761.6742 
2023-03-02 08:20:01,542:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230302   075500    075959  ...         0.0        0.0       0
5856  20230302   080000    080459  ...         0.0        0.0       0
5857  20230302   080500    080959  ...         0.0        0.0       0
5858  20230302   081000    081459  ...         0.0        0.0       0
5859  20230302   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 08:20:01,545:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677716399, self.tradeDate='20230302', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23621.4, self.close=23709.6, self.high=23731.9, self.low=23611.4, self.vol=5231.851, self.amt=123962761.6742, ukdf['pct'].iloc[-1]=0.00373 , ukdf['amount'].iloc[-1]=123962761.6742, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23291
self.closeSec=1677716699, self.tradeDate='20230302', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23709.5, self.close=23707.6, self.high=23790.5, self.low=23707.0, self.vol=5839.265, self.amt=138694504.5512 
2023-03-02 08:25:01,717:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230302   080000    080459  ...         0.0        0.0       0
5857  20230302   080500    080959  ...         0.0        0.0       0
5858  20230302   081000    081459  ...         0.0        0.0       0
5859  20230302   081500    081959  ...         0.0        0.0       0
5860  20230302   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 08:25:01,719:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677716699, self.tradeDate='20230302', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23709.5, self.close=23707.6, self.high=23790.5, self.low=23707.0, self.vol=5839.265, self.amt=138694504.5512, ukdf['pct'].iloc[-1]=-8.4e-05 , ukdf['amount'].iloc[-1]=138694504.5512, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230301   200000    235959  1677686399  ...    719  0.744879  0.171695     NaN
720  20230302   000000    035959  1677700799  ...    720  0.693070  0.012446     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '9513.70850766194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23334.35557286', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=580
self.closeSec=1677715199, self.tradeDate='20230302', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23342.8, self.close=23619.8, self.high=23667.5, self.low=23281.6, self.vol=79548.85, self.amt=1867408857.5566 
2023-03-02 08:00:01,916:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677715199, self.tradeDate='20230302', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23342.8, self.close=23619.8, self.high=23667.5, self.low=23281.6, self.vol=79548.85, self.amt=1867408857.5566 
127.0.0.1 - - [02/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-03-02 08:00:01,961:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230301   120000    155959  ...  119744.837  2.837105e+09  0.011864
718  20230301   160000    195959  ...   87997.318  2.094237e+09  0.001147
719  20230301   200000    235959  ...  137452.515  3.257164e+09 -0.001432
720  20230302   000000    035959  ...   97637.359  2.302435e+09 -0.015184
721  20230302   040000    075959  ...   79548.850  1.867409e+09  0.011862

[5 rows x 11 columns]
2023-03-02 08:00:04,373:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230301   120000    155959  1677657599  ...    717  0.676162  0.028418     NaN
718  20230301   160000    195959  1677671999  ...    718  0.747762  0.198074     NaN
719  20230301   200000    235959  1677686399  ...    719  0.744879  0.171695     NaN
720  20230302   000000    035959  1677700799  ...    720  0.693070  0.012446     NaN
721  20230302   040000    075959  1677715199  ...    721  0.605781 -0.246234     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '21590.41016074341', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23620.67581879', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


