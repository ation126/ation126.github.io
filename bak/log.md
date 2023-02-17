# 20230217 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23548
self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23538.0, self.close=23633.0, self.high=23637.5, self.low=23517.6, self.vol=3898.388, self.amt=91976870.4673 
2023-02-17 08:20:01,689:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230217   075500    075959  ...         0.0        0.0       0
5856  20230217   080000    080459  ...         0.0        0.0       0
5857  20230217   080500    080959  ...         0.0        0.0       0
5858  20230217   081000    081459  ...         0.0        0.0       0
5859  20230217   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 08:20:01,689:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23538.0, self.close=23633.0, self.high=23637.5, self.low=23517.6, self.vol=3898.388, self.amt=91976870.4673, ukdf['pct'].iloc[-1]=0.004036 , ukdf['amount'].iloc[-1]=91976870.4673, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-427546.22268821008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23634.22925233', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23549
self.closeSec=1676593499, self.tradeDate='20230217', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23632.9, self.close=23606.9, self.high=23639.6, self.low=23575.0, self.vol=2551.055, self.amt=60212752.9563 
127.0.0.1 - - [17/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-17 08:25:01,579:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230217   080000    080459  ...         0.0        0.0       0
5857  20230217   080500    080959  ...         0.0        0.0       0
5858  20230217   081000    081459  ...         0.0        0.0       0
5859  20230217   081500    081959  ...         0.0        0.0       0
5860  20230217   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 08:25:01,580:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676593499, self.tradeDate='20230217', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23632.9, self.close=23606.9, self.high=23639.6, self.low=23575.0, self.vol=2551.055, self.amt=60212752.9563, ukdf['pct'].iloc[-1]=-0.001104 , ukdf['amount'].iloc[-1]=60212752.9563, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-425807.71373891136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23605.33884836', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23538.0, self.close=23633.0, self.high=23637.5, self.low=23517.6 
127.0.0.1 - - [17/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-17 08:20:01,531:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23538.0, self.close=23633.0, self.high=23637.5, self.low=23517.6   
2023-02-17 08:20:01,597:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230217   075500    075959  1676591999  ...  23518.0 -0.001320   1535    5
1536  20230217   080000    080459  1676592299  ...  23350.0  0.001131   1536    0
1537  20230217   080500    080959  1676592599  ...  23538.6  0.004759   1537    1
1538  20230217   081000    081459  1676592899  ...  23530.0 -0.005379   1538    2
1539  20230217   081500    081959  1676593199  ...  23517.6  0.004036   1539    3

[5 rows x 11 columns]
2023-02-17 08:20:01,597:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=103, self.factor=0.2886053854692773, self.count=24115 

self.closeSec=1676593499, self.tradeDate='20230217', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23632.9, self.close=23606.9, self.high=23639.6, self.low=23575.0 
2023-02-17 08:25:01,515:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676593499, self.tradeDate='20230217', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23632.9, self.close=23606.9, self.high=23639.6, self.low=23575.0   
127.0.0.1 - - [17/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-17 08:25:01,572:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230217   080000    080459  1676592299  ...  23350.0  0.001131   1536    0
1537  20230217   080500    080959  1676592599  ...  23538.6  0.004759   1537    1
1538  20230217   081000    081459  1676592899  ...  23530.0 -0.005379   1538    2
1539  20230217   081500    081959  1676593199  ...  23517.6  0.004036   1539    3
1540  20230217   082000    082459  1676593499  ...  23575.0 -0.001104   1540    4

[5 rows x 11 columns]
2023-02-17 08:25:01,581:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-17 08:00:36,964:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230217    052959  24581.5  ...  52.500000  0.593619  0.332940
5771  20230217    055959  24493.8  ...  52.500000  0.599874  0.360914
5772  20230217    062959  24554.0  ...  52.500000  0.573295  0.399157
5773  20230217    065959  24376.0  ...  52.083333  0.525057  0.438474
5774  20230217    072959  24012.8  ...  51.666667  0.507423  0.474010

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2023-02-17 08:00:37,121:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.414047  0.585953       1  ...  1.021593  -1.0    0.0  1.065675
537     1  0.453591  0.546409       0  ...  1.028999  -1.0    0.0  1.057949
538     1  0.399112  0.600888       0  ...  1.044267  -1.0    0.0  1.042251
539     1  0.364556  0.635444       0  ...  1.050633  -1.0    0.0  1.035897
540     1  0.379894  0.620106       0  ...  1.065657  -1.0    0.0  1.021084

[5 rows x 10 columns]
2023-02-17 08:00:37,150:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.414278  0.585722       1  ...  1.021593  -1.0    0.0  1.063211
46     1  0.453517  0.546483       0  ...  1.082822  -1.0    0.0  1.053528
47     1  0.399285  0.600715       0  ...  1.044267  -1.0    0.0  1.040801
48     1  0.365214  0.634786       0  ...  1.050633  -1.0    0.0  1.035897
49     1  0.379894  0.620106       0  ...  1.065657  -1.0    0.0  1.021084

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.282', 'enterprice': '24560.5', 'countrevence': '0', 'unrealprofit': '35509.2956', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23524.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230217   075000    075959  1676591999  23699.6  23526.6 -0.007300
2023-02-17 08:00:02,502:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12056 

self.closeSec=1676592599, self.tradeDate='20230217', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23526.6', self.close='23665.3'
2023-02-17 08:10:01,755:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676592599, self.tradeDate='20230217', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23526.6', self.close='23665.3'
2023-02-17 08:10:01,765:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230217   072000    072959  1676590199  23956.2  23867.9 -0.003690
621  20230217   073000    073959  1676590799  23867.9  23814.5 -0.002237
622  20230217   074000    074959  1676591399  23812.6  23699.6 -0.004825
623  20230217   075000    075959  1676591999  23699.6  23526.6 -0.007300
624  20230217   080000    080959  1676592599  23526.6  23665.3  0.005895
2023-02-17 08:10:01,765:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12057 

self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23665.4', self.close='23633'
2023-02-17 08:20:01,602:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23665.4', self.close='23633'
127.0.0.1 - - [17/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-17 08:20:01,667:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230217   073000    073959  1676590799  23867.9  23814.5 -0.002237
622  20230217   074000    074959  1676591399  23812.6  23699.6 -0.004825
623  20230217   075000    075959  1676591999  23699.6  23526.6 -0.007300
624  20230217   080000    080959  1676592599  23526.6  23665.3  0.005895
625  20230217   081000    081959  1676593199  23665.4    23633 -0.001365
2023-02-17 08:20:01,667:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [17/Feb/2023 07:00:02] "POST / HTTP/1.1" 200 -
2023-02-17 07:00:03,124:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/17 04:30:00  043000  24578.3  ...     NaN     NaN       0
145  2023/02/17 05:00:00  050000  24493.7  ...     NaN     NaN       0
146  2023/02/17 05:30:00  053000  24554.0  ...     NaN     NaN       0
147  2023/02/17 06:00:00  060000  24376.0  ...     NaN     NaN       0
148  2023/02/17 06:30:00  063000  24014.3  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [17/Feb/2023 07:30:01] "POST / HTTP/1.1" 200 -
2023-02-17 07:30:02,796:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/17 05:00:00  050000  24493.7  ...     NaN     NaN       0
145  2023/02/17 05:30:00  053000  24554.0  ...     NaN     NaN       0
146  2023/02/17 06:00:00  060000  24376.0  ...     NaN     NaN       0
147  2023/02/17 06:30:00  063000  24014.3  ...     NaN     NaN       0
148  2023/02/17 07:00:00  070000  23867.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [17/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-02-17 08:00:03,530:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/17 05:30:00  053000  24554.0  ...     NaN     NaN       0
145  2023/02/17 06:00:00  060000  24376.0  ...     NaN     NaN       0
146  2023/02/17 06:30:00  063000  24014.3  ...     NaN     NaN       0
147  2023/02/17 07:00:00  070000  23867.9  ...     NaN     NaN       0
148  2023/02/17 07:30:00  073000  23526.6  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17471  20230217   075000    075959  1676591999  23699.6  23526.6
2023-02-17 08:00:02,521:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12057 

self.closeSec=1676592599, self.tradeDate='20230217', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23526.6', self.close='23665.3'
2023-02-17 08:10:01,784:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676592599, self.tradeDate='20230217', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23526.6', self.close='23665.3'
2023-02-17 08:10:01,817:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230217   072000    072959  1676590199  23956.2  23867.9
17469  20230217   073000    073959  1676590799  23867.9  23814.5
17470  20230217   074000    074959  1676591399  23812.6  23699.6
17471  20230217   075000    075959  1676591999  23699.6  23526.6
17472  20230217   080000    080959  1676592599  23526.6  23665.3
2023-02-17 08:10:01,817:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12058 

self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23665.4', self.close='23633'
2023-02-17 08:20:01,613:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23665.4', self.close='23633'
2023-02-17 08:20:01,687:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230217   073000    073959  1676590799  23867.9  23814.5
17470  20230217   074000    074959  1676591399  23812.6  23699.6
17471  20230217   075000    075959  1676591999  23699.6  23526.6
17472  20230217   080000    080959  1676592599  23526.6  23665.3
17473  20230217   081000    081959  1676593199  23665.4    23633
2023-02-17 08:20:01,687:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230217   075000    075959  1676591999  23699.6  23526.6
2023-02-17 08:00:02,501:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12057 

self.closeSec=1676592599, self.tradeDate='20230217', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23526.6', self.close='23665.3'
2023-02-17 08:10:01,742:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676592599, self.tradeDate='20230217', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23526.6', self.close='23665.3'
2023-02-17 08:10:01,747:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230217   072000    072959  1676590199  23956.2  23867.9
12141  20230217   073000    073959  1676590799  23867.9  23814.5
12142  20230217   074000    074959  1676591399  23812.6  23699.6
12143  20230217   075000    075959  1676591999  23699.6  23526.6
12144  20230217   080000    080959  1676592599  23526.6  23665.3
2023-02-17 08:10:01,748:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12058 

self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23665.4', self.close='23633'
2023-02-17 08:20:01,657:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23665.4', self.close='23633'
127.0.0.1 - - [17/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-17 08:20:01,690:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230217   073000    073959  1676590799  23867.9  23814.5
12142  20230217   074000    074959  1676591399  23812.6  23699.6
12143  20230217   075000    075959  1676591999  23699.6  23526.6
12144  20230217   080000    080959  1676592599  23526.6  23665.3
12145  20230217   081000    081959  1676593199  23665.4    23633
2023-02-17 08:20:01,690:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [17/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19546
self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23538.0, self.close=23633.0, self.high=23637.5, self.low=23517.6, self.vol=3898.388, self.amt=91976870.4673 
2023-02-17 08:20:01,685:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230217   075500    075959  ...         0.0        0.0       0
5856  20230217   080000    080459  ...         0.0        0.0       0
5857  20230217   080500    080959  ...         0.0        0.0       0
5858  20230217   081000    081459  ...         0.0        0.0       0
5859  20230217   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 08:20:01,691:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676593199, self.tradeDate='20230217', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23538.0, self.close=23633.0, self.high=23637.5, self.low=23517.6, self.vol=3898.388, self.amt=91976870.4673, ukdf['pct'].iloc[-1]=0.004036 , ukdf['amount'].iloc[-1]=91976870.4673, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19547
self.closeSec=1676593499, self.tradeDate='20230217', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23632.9, self.close=23606.9, self.high=23639.6, self.low=23575.0, self.vol=2551.055, self.amt=60212752.9563 
127.0.0.1 - - [17/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-17 08:25:01,577:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230217   080000    080459  ...         0.0        0.0       0
5857  20230217   080500    080959  ...         0.0        0.0       0
5858  20230217   081000    081459  ...         0.0        0.0       0
5859  20230217   081500    081959  ...         0.0        0.0       0
5860  20230217   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-17 08:25:01,588:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676593499, self.tradeDate='20230217', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23632.9, self.close=23606.9, self.high=23639.6, self.low=23575.0, self.vol=2551.055, self.amt=60212752.9563, ukdf['pct'].iloc[-1]=-0.001104 , ukdf['amount'].iloc[-1]=60212752.9563, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230216   200000    235959  1676563199  ...    719  1.148644  1.765325     1.0
720  20230217   000000    035959  1676577599  ...    720  1.167381  1.771426     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '56857.1246929601', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24875.16162695', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [17/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=502
self.closeSec=1676591999, self.tradeDate='20230217', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=24879.1, self.close=23526.6, self.high=24884.1, self.low=23518.0, self.vol=237702.696, self.amt=5751313008.07482 
2023-02-17 08:00:02,357:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676591999, self.tradeDate='20230217', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=24879.1, self.close=23526.6, self.high=24884.1, self.low=23518.0, self.vol=237702.696, self.amt=5751313008.07482 
2023-02-17 08:00:02,394:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230216   120000    155959  ...   85116.457  2.096381e+09 -0.004454
718  20230216   160000    195959  ...   48543.148  1.194716e+09 -0.002062
719  20230216   200000    235959  ...  214136.439  5.270860e+09  0.021009
720  20230217   000000    035959  ...  224316.013  5.591111e+09 -0.008663
721  20230217   040000    075959  ...  237702.696  5.751313e+09 -0.054359

[5 rows x 11 columns]
2023-02-17 08:00:05,014:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230216   120000    155959  1676534399  ...    717  1.216220  2.090231     1.0
718  20230216   160000    195959  1676548799  ...    718  1.095735  1.639745     1.0
719  20230216   200000    235959  1676563199  ...    719  1.148644  1.765325     1.0
720  20230217   000000    035959  1676577599  ...    720  1.167381  1.771426     1.0
721  20230217   040000    075959  1676591999  ...    721  1.208527  1.844319     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '7489.8418', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23523.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


