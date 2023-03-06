# 20230306 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [06/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28444
self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22402.6, self.close=22412.6, self.high=22422.9, self.low=22356.0, self.vol=2355.151, self.amt=52715308.1211 
2023-03-06 08:20:01,623:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230306   075500    075959  ...         0.0        0.0       0
5856  20230306   080000    080459  ...         0.0        0.0       0
5857  20230306   080500    080959  ...         0.0        0.0       0
5858  20230306   081000    081459  ...         0.0        0.0       0
5859  20230306   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 08:20:01,624:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22402.6, self.close=22412.6, self.high=22422.9, self.low=22356.0, self.vol=2355.151, self.amt=52715308.1211, ukdf['pct'].iloc[-1]=0.000446 , ukdf['amount'].iloc[-1]=52715308.1211, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-354141.7776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22414.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28445
self.closeSec=1678062299, self.tradeDate='20230306', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22414.5, self.close=22424.9, self.high=22426.9, self.low=22407.0, self.vol=1025.103, self.amt=22979442.2326 
127.0.0.1 - - [06/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-06 08:25:01,571:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230306   080000    080459  ...         0.0        0.0       0
5857  20230306   080500    080959  ...         0.0        0.0       0
5858  20230306   081000    081459  ...         0.0        0.0       0
5859  20230306   081500    081959  ...         0.0        0.0       0
5860  20230306   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 08:25:01,572:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678062299, self.tradeDate='20230306', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22414.5, self.close=22424.9, self.high=22426.9, self.low=22407.0, self.vol=1025.103, self.amt=22979442.2326, ukdf['pct'].iloc[-1]=0.000549 , ukdf['amount'].iloc[-1]=22979442.2326, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-354847.43597960704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22426.12657504', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.5049845552419627, self.count=29010 

self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22402.6, self.close=22412.6, self.high=22422.9, self.low=22356.0 
2023-03-06 08:20:01,543:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22402.6, self.close=22412.6, self.high=22422.9, self.low=22356.0   
2023-03-06 08:20:01,619:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230306   075500    075959  1678060799  ...  22414.5 -0.000281   1535    5
1536  20230306   080000    080459  1678061099  ...  22404.0  0.000285   1536    0
1537  20230306   080500    080959  1678061399  ...  22411.4 -0.000299   1537    1
1538  20230306   081000    081459  1678061699  ...  22402.5 -0.000736   1538    2
1539  20230306   081500    081959  1678061999  ...  22356.0  0.000446   1539    3

[5 rows x 11 columns]
2023-03-06 08:20:01,622:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.5049845552419627, self.count=29011 

self.closeSec=1678062299, self.tradeDate='20230306', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22414.5, self.close=22424.9, self.high=22426.9, self.low=22407.0 
2023-03-06 08:25:01,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678062299, self.tradeDate='20230306', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22414.5, self.close=22424.9, self.high=22426.9, self.low=22407.0   
127.0.0.1 - - [06/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-06 08:25:01,549:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230306   080000    080459  1678061099  ...  22404.0  0.000285   1536    0
1537  20230306   080500    080959  1678061399  ...  22411.4 -0.000299   1537    1
1538  20230306   081000    081459  1678061699  ...  22402.5 -0.000736   1538    2
1539  20230306   081500    081959  1678061999  ...  22356.0  0.000446   1539    3
1540  20230306   082000    082459  1678062299  ...  22407.0  0.000549   1540    4

[5 rows x 11 columns]
2023-03-06 08:25:01,550:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-06 08:00:34,268:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230306    052959  22397.5  ...  47.500000  0.502574  0.481132
5771  20230306    055959  22450.1  ...  47.916667  0.511895  0.468864
5772  20230306    062959  22473.6  ...  47.500000  0.481726  0.465423
5773  20230306    065959  22396.3  ...  47.916667  0.491963  0.469362
5774  20230306    072959  22422.3  ...  47.916667  0.479974  0.481497

[5 rows x 33 columns]
0.5545286506469501
acc is : 0.5545286506469501
2023-03-06 08:00:34,413:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.527808  0.472192       1  ...  0.915019  -1.0    0.0  0.948546
537     0  0.527283  0.472717       0  ...  0.918166  -1.0    0.0  0.945283
538     1  0.478100  0.521900       1  ...  0.917104  -1.0    0.0  0.946376
539     0  0.518524  0.481476       0  ...  0.918417  -1.0    0.0  0.945021
540     1  0.492423  0.507577       1  ...  0.917220  -1.0    0.0  0.946254

[5 rows x 10 columns]
2023-03-06 08:00:34,450:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.527505  0.472495       1  ...  0.915019  -1.0    0.0  0.947853
46     0  0.527421  0.472579       0  ...  0.918166  -1.0    0.0  0.945798
47     1  0.478407  0.521593       1  ...  0.885987  -1.0    0.0  0.948976
48     0  0.518524  0.481476       0  ...  0.918417  -1.0    0.0  0.945021
49     1  0.492423  0.507577       1  ...  0.917220  -1.0    0.0  0.946254

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.887', 'enterprice': '22396.9', 'countrevence': '0', 'unrealprofit': '-495.31030298091', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22412.43329893', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230306   075000    075959  1678060799  22399.8  22419.4  0.000875
2023-03-06 08:00:02,408:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14504 

self.closeSec=1678061399, self.tradeDate='20230306', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22419.3', self.close='22419.1'
2023-03-06 08:10:01,630:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678061399, self.tradeDate='20230306', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22419.3', self.close='22419.1'
2023-03-06 08:10:01,656:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230306   072000    072959  1678058999    22366  22390.2  0.001086
621  20230306   073000    073959  1678059599  22390.1  22424.7  0.001541
622  20230306   074000    074959  1678060199  22424.7  22399.8 -0.001110
623  20230306   075000    075959  1678060799  22399.8  22419.4  0.000875
624  20230306   080000    080959  1678061399  22419.3  22419.1 -0.000013
2023-03-06 08:10:01,656:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14505 

self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22419.1', self.close='22412.6'
2023-03-06 08:20:01,584:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22419.1', self.close='22412.6'
127.0.0.1 - - [06/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-06 08:20:01,595:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230306   073000    073959  1678059599  22390.1  22424.7  0.001541
622  20230306   074000    074959  1678060199  22424.7  22399.8 -0.001110
623  20230306   075000    075959  1678060799  22399.8  22419.4  0.000875
624  20230306   080000    080959  1678061399  22419.3  22419.1 -0.000013
625  20230306   081000    081959  1678061999  22419.1  22412.6 -0.000290
2023-03-06 08:20:01,597:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230306   075000    075959  1678060799  22399.8  22419.4
2023-03-06 08:00:02,347:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14505 

self.closeSec=1678061399, self.tradeDate='20230306', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22419.3', self.close='22419.1'
2023-03-06 08:10:01,657:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678061399, self.tradeDate='20230306', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22419.3', self.close='22419.1'
2023-03-06 08:10:01,687:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230306   072000    072959  1678058999    22366  22390.2
17469  20230306   073000    073959  1678059599  22390.1  22424.7
17470  20230306   074000    074959  1678060199  22424.7  22399.8
17471  20230306   075000    075959  1678060799  22399.8  22419.4
17472  20230306   080000    080959  1678061399  22419.3  22419.1
2023-03-06 08:10:01,687:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14506 

self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22419.1', self.close='22412.6'
2023-03-06 08:20:01,666:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22419.1', self.close='22412.6'
2023-03-06 08:20:01,696:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230306   073000    073959  1678059599  22390.1  22424.7
17470  20230306   074000    074959  1678060199  22424.7  22399.8
17471  20230306   075000    075959  1678060799  22399.8  22419.4
17472  20230306   080000    080959  1678061399  22419.3  22419.1
17473  20230306   081000    081959  1678061999  22419.1  22412.6
2023-03-06 08:20:01,697:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230306   075000    075959  1678060799  22399.8  22419.4
2023-03-06 08:00:02,344:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [06/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14505 

self.closeSec=1678061399, self.tradeDate='20230306', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22419.3', self.close='22419.1'
2023-03-06 08:10:01,608:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678061399, self.tradeDate='20230306', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22419.3', self.close='22419.1'
2023-03-06 08:10:01,633:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230306   072000    072959  1678058999    22366  22390.2
12141  20230306   073000    073959  1678059599  22390.1  22424.7
12142  20230306   074000    074959  1678060199  22424.7  22399.8
12143  20230306   075000    075959  1678060799  22399.8  22419.4
12144  20230306   080000    080959  1678061399  22419.3  22419.1
2023-03-06 08:10:01,633:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [06/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14506 

self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22419.1', self.close='22412.6'
2023-03-06 08:20:01,658:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22419.1', self.close='22412.6'
2023-03-06 08:20:01,684:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230306   073000    073959  1678059599  22390.1  22424.7
12142  20230306   074000    074959  1678060199  22424.7  22399.8
12143  20230306   075000    075959  1678060799  22399.8  22419.4
12144  20230306   080000    080959  1678061399  22419.3  22419.1
12145  20230306   081000    081959  1678061999  22419.1  22412.6
2023-03-06 08:20:01,684:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24442
self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22402.6, self.close=22412.6, self.high=22422.9, self.low=22356.0, self.vol=2355.151, self.amt=52715308.1211 
127.0.0.1 - - [06/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-06 08:20:01,591:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230306   075500    075959  ...         0.0        0.0       0
5856  20230306   080000    080459  ...         0.0        0.0       0
5857  20230306   080500    080959  ...         0.0        0.0       0
5858  20230306   081000    081459  ...         0.0        0.0       0
5859  20230306   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 08:20:01,596:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678061999, self.tradeDate='20230306', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22402.6, self.close=22412.6, self.high=22422.9, self.low=22356.0, self.vol=2355.151, self.amt=52715308.1211, ukdf['pct'].iloc[-1]=0.000446 , ukdf['amount'].iloc[-1]=52715308.1211, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24443
self.closeSec=1678062299, self.tradeDate='20230306', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22414.5, self.close=22424.9, self.high=22426.9, self.low=22407.0, self.vol=1025.103, self.amt=22979442.2326 
127.0.0.1 - - [06/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-06 08:25:01,569:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230306   080000    080459  ...         0.0        0.0       0
5857  20230306   080500    080959  ...         0.0        0.0       0
5858  20230306   081000    081459  ...         0.0        0.0       0
5859  20230306   081500    081959  ...         0.0        0.0       0
5860  20230306   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 08:25:01,573:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678062299, self.tradeDate='20230306', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22414.5, self.close=22424.9, self.high=22426.9, self.low=22407.0, self.vol=1025.103, self.amt=22979442.2326, ukdf['pct'].iloc[-1]=0.000549 , ukdf['amount'].iloc[-1]=22979442.2326, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230305   200000    235959  1678031999  ...    719  0.664683  0.319818     NaN
720  20230306   000000    035959  1678046399  ...    720  0.625788  0.194302     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '40352.6895', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22392.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=604
self.closeSec=1678060799, self.tradeDate='20230306', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22394.0, self.close=22419.4, self.high=22555.0, self.low=22310.0, self.vol=53766.64, self.amt=1205734279.6082 
127.0.0.1 - - [06/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-06 08:00:02,194:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678060799, self.tradeDate='20230306', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22394.0, self.close=22419.4, self.high=22555.0, self.low=22310.0, self.vol=53766.64, self.amt=1205734279.6082 
2023-03-06 08:00:02,233:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230305   120000    155959  ...  30138.059  6.752701e+08 -0.000407
718  20230305   160000    195959  ...  31592.000  7.067840e+08  0.000671
719  20230305   200000    235959  ...  32096.465  7.199611e+08  0.001979
720  20230306   000000    035959  ...  21185.383  4.748226e+08 -0.001356
721  20230306   040000    075959  ...  53766.640  1.205734e+09  0.001134

[5 rows x 11 columns]
2023-03-06 08:00:04,396:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230305   120000    155959  1678003199  ...    717  0.723793  0.502248     NaN
718  20230305   160000    195959  1678017599  ...    718  0.704319  0.449658     NaN
719  20230305   200000    235959  1678031999  ...    719  0.664683  0.319818     NaN
720  20230306   000000    035959  1678046399  ...    720  0.625788  0.194302     NaN
721  20230306   040000    075959  1678060799  ...    721  0.571982  0.009081     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '39223.4715', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22419.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


