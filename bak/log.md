# 20221220 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6554
self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16429.8, self.close=16410.8, self.high=16433.6, self.low=16410.0, self.vol=931.203, self.amt=15292894.5529 
127.0.0.1 - - [20/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-20 08:10:01,561:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221220   074500    074959  ...         0.0        0.0       0
5854  20221220   075000    075459  ...         0.0        0.0       0
5855  20221220   075500    075959  ...         0.0        0.0       0
5856  20221220   080000    080459  ...         0.0        0.0       0
5857  20221220   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 08:10:01,569:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16429.8, self.close=16410.8, self.high=16433.6, self.low=16410.0, self.vol=931.203, self.amt=15292894.5529, ukdf['pct'].iloc[-1]=-0.00115 , ukdf['amount'].iloc[-1]=15292894.5529, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '7060.89002252368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16411.96268907', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6555
self.closeSec=1671495299, self.tradeDate='20221220', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16410.8, self.close=16401.0, self.high=16417.3, self.low=16390.3, self.vol=1451.374, self.amt=23804772.4793 
127.0.0.1 - - [20/Dec/2022 08:15:01] "POST / HTTP/1.1" 200 -
2022-12-20 08:15:01,106:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221220   075000    075459  ...         0.0        0.0       0
5855  20221220   075500    075959  ...         0.0        0.0       0
5856  20221220   080000    080459  ...         0.0        0.0       0
5857  20221220   080500    080959  ...         0.0        0.0       0
5858  20221220   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 08:15:01,107:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671495299, self.tradeDate='20221220', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16410.8, self.close=16401.0, self.high=16417.3, self.low=16390.3, self.vol=1451.374, self.amt=23804772.4793, ukdf['pct'].iloc[-1]=-0.000597 , ukdf['amount'].iloc[-1]=23804772.4793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '7624.2992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16402.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16429.8, self.close=16410.8, self.high=16433.6, self.low=16410.0 
2022-12-20 08:10:01,436:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16429.8, self.close=16410.8, self.high=16433.6, self.low=16410.0   
127.0.0.1 - - [20/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-20 08:10:01,477:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221220   074500    074959  1671493799  ...  16417.0 -0.000901   1533    3
1534  20221220   075000    075459  1671494099  ...  16405.6  0.000073   1534    4
1535  20221220   075500    075959  1671494399  ...  16411.0  0.000670   1535    5
1536  20221220   080000    080459  1671494699  ...  16421.3  0.000030   1536    0
1537  20221220   080500    080959  1671494999  ...  16410.0 -0.001150   1537    1

[5 rows x 11 columns]
2022-12-20 08:10:01,478:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6577951171687637, self.count=7121 

self.closeSec=1671495299, self.tradeDate='20221220', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16410.8, self.close=16401.0, self.high=16417.3, self.low=16390.3 
2022-12-20 08:15:00,987:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671495299, self.tradeDate='20221220', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16410.8, self.close=16401.0, self.high=16417.3, self.low=16390.3   
2022-12-20 08:15:01,016:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221220   075000    075459  1671494099  ...  16405.6  0.000073   1534    4
1535  20221220   075500    075959  1671494399  ...  16411.0  0.000670   1535    5
1536  20221220   080000    080459  1671494699  ...  16421.3  0.000030   1536    0
1537  20221220   080500    080959  1671494999  ...  16410.0 -0.001150   1537    1
1538  20221220   081000    081459  1671495299  ...  16390.3 -0.000597   1538    2

[5 rows x 11 columns]
2022-12-20 08:15:01,016:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-20 08:00:28,323:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221220    052959  16593.8  ...  47.500000  0.450408  0.700937
5771  20221220    055959  16629.4  ...  47.500000  0.429347  0.703413
5772  20221220    062959  16582.3  ...  47.083333  0.416587  0.713111
5773  20221220    065959  16551.9  ...  47.083333  0.363951  0.709011
5774  20221220    072959  16407.5  ...  47.500000  0.366607  0.704631

[5 rows x 33 columns]
0.5637707948243993
acc is : 0.5637707948243993
2022-12-20 08:00:28,457:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.514443  0.485557       0  ...  1.115001  -1.0    0.0  0.979086
537     1  0.490287  0.509713       0  ...  1.117039  -1.0    0.0  0.977297
538     1  0.489722  0.510278       0  ...  1.126791  -1.0    0.0  0.968765
539     1  0.447052  0.552948       1  ...  1.126468  -1.0    0.0  0.969043
540     1  0.479006  0.520994       1  ...  1.125205  -1.0    0.0  0.970129

[5 rows x 10 columns]
2022-12-20 08:00:28,477:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514790  0.485210       0  ...  1.115001  -1.0    0.0  0.980754
46     1  0.490302  0.509698       0  ...  1.117039  -1.0    0.0  0.977996
47     1  0.489452  0.510548       0  ...  1.126791  -1.0    0.0  0.968760
48     1  0.446834  0.553166       1  ...  1.126468  -1.0    0.0  0.969043
49     1  0.479006  0.520994       1  ...  1.125205  -1.0    0.0  0.970129

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '50620.05295353192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16427.43547227', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221220   074000    074959  1671493799  16423.2    16417 -0.000359
2022-12-20 07:50:00,533:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3559 

self.closeSec=1671494399, self.tradeDate='20221220', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16414.6', self.close='16429.2'
127.0.0.1 - - [20/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-20 08:00:01,386:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671494399, self.tradeDate='20221220', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16414.6', self.close='16429.2'
2022-12-20 08:00:01,405:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221220   071000    071959  1671491999  16377.1  16366.7 -0.000641
620  20221220   072000    072959  1671492599  16366.7  16412.2  0.002780
621  20221220   073000    073959  1671493199  16412.2  16422.9  0.000652
622  20221220   074000    074959  1671493799  16423.2    16417 -0.000359
623  20221220   075000    075959  1671494399  16414.6  16429.2  0.000743
2022-12-20 08:00:01,408:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3560 

self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16429.2', self.close='16410.8'
2022-12-20 08:10:01,569:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16429.2', self.close='16410.8'
2022-12-20 08:10:01,639:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221220   072000    072959  1671492599  16366.7  16412.2  0.002780
621  20221220   073000    073959  1671493199  16412.2  16422.9  0.000652
622  20221220   074000    074959  1671493799  16423.2    16417 -0.000359
623  20221220   075000    075959  1671494399  16414.6  16429.2  0.000743
624  20221220   080000    080959  1671494999  16429.2  16410.8 -0.001120
2022-12-20 08:10:01,639:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221220   074000    074959  1671493799  16423.2    16417
2022-12-20 07:50:00,634:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3560 

self.closeSec=1671494399, self.tradeDate='20221220', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16414.6', self.close='16429.2'
2022-12-20 08:00:01,420:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671494399, self.tradeDate='20221220', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16414.6', self.close='16429.2'
2022-12-20 08:00:01,492:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221220   071000    071959  1671491999  16377.1  16366.7
17468  20221220   072000    072959  1671492599  16366.7  16412.2
17469  20221220   073000    073959  1671493199  16412.2  16422.9
17470  20221220   074000    074959  1671493799  16423.2    16417
17471  20221220   075000    075959  1671494399  16414.6  16429.2
2022-12-20 08:00:01,493:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [20/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3561 

self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16429.2', self.close='16410.8'
2022-12-20 08:10:01,612:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16429.2', self.close='16410.8'
2022-12-20 08:10:01,662:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221220   072000    072959  1671492599  16366.7  16412.2
17469  20221220   073000    073959  1671493199  16412.2  16422.9
17470  20221220   074000    074959  1671493799  16423.2    16417
17471  20221220   075000    075959  1671494399  16414.6  16429.2
17472  20221220   080000    080959  1671494999  16429.2  16410.8
2022-12-20 08:10:01,663:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221220   074000    074959  1671493799  16423.2    16417
2022-12-20 07:50:00,585:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3560 

self.closeSec=1671494399, self.tradeDate='20221220', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16414.6', self.close='16429.2'
2022-12-20 08:00:01,422:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671494399, self.tradeDate='20221220', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16414.6', self.close='16429.2'
127.0.0.1 - - [20/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-20 08:00:01,467:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221220   071000    071959  1671491999  16377.1  16366.7
12140  20221220   072000    072959  1671492599  16366.7  16412.2
12141  20221220   073000    073959  1671493199  16412.2  16422.9
12142  20221220   074000    074959  1671493799  16423.2    16417
12143  20221220   075000    075959  1671494399  16414.6  16429.2
2022-12-20 08:00:01,467:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3561 

self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16429.2', self.close='16410.8'
2022-12-20 08:10:01,604:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16429.2', self.close='16410.8'
127.0.0.1 - - [20/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-20 08:10:01,650:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221220   072000    072959  1671492599  16366.7  16412.2
12141  20221220   073000    073959  1671493199  16412.2  16422.9
12142  20221220   074000    074959  1671493799  16423.2    16417
12143  20221220   075000    075959  1671494399  16414.6  16429.2
12144  20221220   080000    080959  1671494999  16429.2  16410.8
2022-12-20 08:10:01,650:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [20/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2552
self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16429.8, self.close=16410.8, self.high=16433.6, self.low=16410.0, self.vol=931.203, self.amt=15292894.5529 
2022-12-20 08:10:01,502:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221220   074500    074959  ...         0.0        0.0       0
5854  20221220   075000    075459  ...         0.0        0.0       0
5855  20221220   075500    075959  ...         0.0        0.0       0
5856  20221220   080000    080459  ...         0.0        0.0       0
5857  20221220   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 08:10:01,502:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671494999, self.tradeDate='20221220', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16429.8, self.close=16410.8, self.high=16433.6, self.low=16410.0, self.vol=931.203, self.amt=15292894.5529, ukdf['pct'].iloc[-1]=-0.00115 , ukdf['amount'].iloc[-1]=15292894.5529, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [20/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2553
self.closeSec=1671495299, self.tradeDate='20221220', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16410.8, self.close=16401.0, self.high=16417.3, self.low=16390.3, self.vol=1451.374, self.amt=23804772.4793 
2022-12-20 08:15:01,088:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221220   075000    075459  ...         0.0        0.0       0
5855  20221220   075500    075959  ...         0.0        0.0       0
5856  20221220   080000    080459  ...         0.0        0.0       0
5857  20221220   080500    080959  ...         0.0        0.0       0
5858  20221220   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 08:15:01,089:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671495299, self.tradeDate='20221220', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16410.8, self.close=16401.0, self.high=16417.3, self.low=16390.3, self.vol=1451.374, self.amt=23804772.4793, ukdf['pct'].iloc[-1]=-0.000597 , ukdf['amount'].iloc[-1]=23804772.4793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221219   200000    235959  1671465599  ...    719  1.012876  0.847578     1.0
720  20221220   000000    035959  1671479999  ...    720  0.877226  0.363186     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-64497.252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16549.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [20/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=148
self.closeSec=1671494399, self.tradeDate='20221220', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16549.3, self.close=16429.2, self.high=16642.1, self.low=16210.0, self.vol=87890.393, self.amt=1445146479.54664 
2022-12-20 08:00:01,267:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671494399, self.tradeDate='20221220', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16549.3, self.close=16429.2, self.high=16642.1, self.low=16210.0, self.vol=87890.393, self.amt=1445146479.54664 
2022-12-20 08:00:01,301:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221219   120000    155959  ...  28214.603  4.714000e+08  0.002447
718  20221219   160000    195959  ...  27329.823  4.575512e+08  0.000652
719  20221219   200000    235959  ...  54277.784  9.068502e+08 -0.003892
720  20221220   000000    035959  ...  97414.221  1.616079e+09 -0.006657
721  20221220   040000    075959  ...  87890.393  1.445146e+09 -0.007257

[5 rows x 11 columns]
2022-12-20 08:00:03,033:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221219   120000    155959  1671436799  ...    717  0.895413  0.487981     NaN
718  20221219   160000    195959  1671451199  ...    718  0.952799  0.659302     1.0
719  20221219   200000    235959  1671465599  ...    719  1.012876  0.847578     1.0
720  20221220   000000    035959  1671479999  ...    720  0.877226  0.363186     NaN
721  20221220   040000    075959  1671494399  ...    721  0.677568 -0.376910     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-70852.90785215472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16430.36041148', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


