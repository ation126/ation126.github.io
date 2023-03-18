# 20230318 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31996
self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27114.2, self.close=27183.5, self.high=27193.0, self.low=27050.0, self.vol=7398.635, self.amt=200664400.9921 
127.0.0.1 - - [18/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-18 16:20:02,603:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230318   155500    155959  ...         0.0        0.0       0
5952  20230318   160000    160459  ...         0.0        0.0       0
5953  20230318   160500    160959  ...         0.0        0.0       0
5954  20230318   161000    161459  ...         0.0        0.0       0
5955  20230318   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 16:20:02,607:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27114.2, self.close=27183.5, self.high=27193.0, self.low=27050.0, self.vol=7398.635, self.amt=200664400.9921, ukdf['pct'].iloc[-1]=0.002475 , ukdf['amount'].iloc[-1]=200664400.9921, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-641012.96546630944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27181.60266994', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31997
self.closeSec=1679127899, self.tradeDate='20230318', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27183.5, self.close=27196.6, self.high=27225.0, self.low=27170.4, self.vol=2262.088, self.amt=61528708.2405 
2023-03-18 16:25:01,645:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230318   160000    160459  ...         0.0        0.0       0
5953  20230318   160500    160959  ...         0.0        0.0       0
5954  20230318   161000    161459  ...         0.0        0.0       0
5955  20230318   161500    161959  ...         0.0        0.0       0
5956  20230318   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 16:25:01,645:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679127899, self.tradeDate='20230318', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27183.5, self.close=27196.6, self.high=27225.0, self.low=27170.4, self.vol=2262.088, self.amt=61528708.2405, ukdf['pct'].iloc[-1]=0.000482 , ukdf['amount'].iloc[-1]=61528708.2405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-641915.4448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27196.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27114.2, self.close=27183.5, self.high=27193.0, self.low=27050.0 
127.0.0.1 - - [18/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-18 16:20:01,727:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27114.2, self.close=27183.5, self.high=27193.0, self.low=27050.0   
2023-03-18 16:20:01,798:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230318   155500    155959  1679126399  ...  27313.2  0.001413   1631    5
1632  20230318   160000    160459  1679126699  ...  27297.2 -0.000271   1632    0
1633  20230318   160500    160959  1679126999  ...  27250.9 -0.002037   1633    1
1634  20230318   161000    161459  1679127299  ...  27104.0 -0.006318   1634    2
1635  20230318   161500    161959  1679127599  ...  27050.0  0.002475   1635    3

[5 rows x 11 columns]
2023-03-18 16:20:01,798:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=44, self.factor=0.2105065398723206, self.count=32563 

self.closeSec=1679127899, self.tradeDate='20230318', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27183.5, self.close=27196.6, self.high=27225.0, self.low=27170.4 
2023-03-18 16:25:01,522:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679127899, self.tradeDate='20230318', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27183.5, self.close=27196.6, self.high=27225.0, self.low=27170.4   
2023-03-18 16:25:01,609:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230318   160000    160459  1679126699  ...  27297.2 -0.000271   1632    0
1633  20230318   160500    160959  1679126999  ...  27250.9 -0.002037   1633    1
1634  20230318   161000    161459  1679127299  ...  27104.0 -0.006318   1634    2
1635  20230318   161500    161959  1679127599  ...  27050.0  0.002475   1635    3
1636  20230318   162000    162459  1679127899  ...  27170.4  0.000482   1636    4

[5 rows x 11 columns]
2023-03-18 16:25:01,615:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-18 16:00:33,318:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5786  20230318    132959  27316.3  ...    51.25  0.623567  0.190834
5787  20230318    135959  27390.4  ...    51.25  0.635406  0.186132
5788  20230318    142959  27565.7  ...    51.25  0.623306  0.186047
5789  20230318    145959  27459.6  ...    51.25  0.625705  0.184548
5790  20230318    152959  27494.7  ...    51.25  0.615431  0.186796

[5 rows x 33 columns]
0.566420664206642
acc is : 0.566420664206642
2023-03-18 16:00:33,478:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.511301  0.488699       1  ...  1.159302  -1.0  0.0000  1.230480
538     0  0.565386  0.434614       0  ...  1.152985   1.0 -0.0016  1.225744
539     1  0.461925  0.538075       1  ...  1.154455   1.0  0.0000  1.227306
540     0  0.505946  0.494054       0  ...  1.150680   1.0  0.0000  1.223293
541     1  0.461946  0.538054       0  ...  1.148463   1.0  0.0000  1.220936

[5 rows x 10 columns]
2023-03-18 16:00:33,513:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.510038  0.489962       1  ...  1.169433  -1.0  0.0000  1.229190
46     0  0.563937  0.436063       0  ...  1.152985   1.0 -0.0016  1.225169
47     1  0.460985  0.539015       1  ...  1.154455   1.0  0.0000  1.227596
48     0  0.505169  0.494831       0  ...  1.150680   1.0  0.0000  1.224348
49     1  0.461946  0.538054       0  ...  1.148463   1.0  0.0000  1.220936

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230318   155000    155959  1679126399    27395  27351.9 -0.001577
2023-03-18 16:00:02,606:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16280 

self.closeSec=1679126999, self.tradeDate='20230318', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27351.9', self.close='27288.8'
2023-03-18 16:10:01,588:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679126999, self.tradeDate='20230318', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27351.9', self.close='27288.8'
2023-03-18 16:10:01,615:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230318   152000    152959  1679124599    27434  27404.7 -0.001068
525  20230318   153000    153959  1679125199  27404.8  27402.2 -0.000091
526  20230318   154000    154959  1679125799  27402.1  27395.1 -0.000259
527  20230318   155000    155959  1679126399    27395  27351.9 -0.001577
528  20230318   160000    160959  1679126999  27351.9  27288.8 -0.002307
2023-03-18 16:10:01,620:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16281 

self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27288.5', self.close='27183.5'
127.0.0.1 - - [18/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-18 16:20:02,357:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27288.5', self.close='27183.5'
2023-03-18 16:20:02,440:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230318   153000    153959  1679125199  27404.8  27402.2 -0.000091
526  20230318   154000    154959  1679125799  27402.1  27395.1 -0.000259
527  20230318   155000    155959  1679126399    27395  27351.9 -0.001577
528  20230318   160000    160959  1679126999  27351.9  27288.8 -0.002307
529  20230318   161000    161959  1679127599  27288.5  27183.5 -0.003859
2023-03-18 16:20:02,440:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230318   155000    155959  1679126399    27395  27351.9
2023-03-18 16:00:02,546:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16281 

self.closeSec=1679126999, self.tradeDate='20230318', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27351.9', self.close='27288.8'
2023-03-18 16:10:01,600:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679126999, self.tradeDate='20230318', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27351.9', self.close='27288.8'
127.0.0.1 - - [18/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-18 16:10:01,634:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230318   152000    152959  1679124599    27434  27404.7
17517  20230318   153000    153959  1679125199  27404.8  27402.2
17518  20230318   154000    154959  1679125799  27402.1  27395.1
17519  20230318   155000    155959  1679126399    27395  27351.9
17520  20230318   160000    160959  1679126999  27351.9  27288.8
2023-03-18 16:10:01,634:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16282 

self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27288.5', self.close='27183.5'
127.0.0.1 - - [18/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-18 16:20:03,021:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27288.5', self.close='27183.5'
2023-03-18 16:20:03,052:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230318   153000    153959  1679125199  27404.8  27402.2
17518  20230318   154000    154959  1679125799  27402.1  27395.1
17519  20230318   155000    155959  1679126399    27395  27351.9
17520  20230318   160000    160959  1679126999  27351.9  27288.8
17521  20230318   161000    161959  1679127599  27288.5  27183.5
2023-03-18 16:20:03,054:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230318   155000    155959  1679126399    27395  27351.9
2023-03-18 16:00:02,621:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16281 

self.closeSec=1679126999, self.tradeDate='20230318', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27351.9', self.close='27288.8'
2023-03-18 16:10:01,602:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679126999, self.tradeDate='20230318', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27351.9', self.close='27288.8'
2023-03-18 16:10:01,628:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230318   152000    152959  1679124599    27434  27404.7
12189  20230318   153000    153959  1679125199  27404.8  27402.2
12190  20230318   154000    154959  1679125799  27402.1  27395.1
12191  20230318   155000    155959  1679126399    27395  27351.9
12192  20230318   160000    160959  1679126999  27351.9  27288.8
2023-03-18 16:10:01,629:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16282 

self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27288.5', self.close='27183.5'
127.0.0.1 - - [18/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-18 16:20:02,830:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27288.5', self.close='27183.5'
2023-03-18 16:20:02,920:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230318   153000    153959  1679125199  27404.8  27402.2
12190  20230318   154000    154959  1679125799  27402.1  27395.1
12191  20230318   155000    155959  1679126399    27395  27351.9
12192  20230318   160000    160959  1679126999  27351.9  27288.8
12193  20230318   161000    161959  1679127599  27288.5  27183.5
2023-03-18 16:20:02,920:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27994
self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27114.2, self.close=27183.5, self.high=27193.0, self.low=27050.0, self.vol=7398.635, self.amt=200664400.9921 
2023-03-18 16:20:01,569:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230318   155500    155959  ...         0.0        0.0       0
5952  20230318   160000    160459  ...         0.0        0.0       0
5953  20230318   160500    160959  ...         0.0        0.0       0
5954  20230318   161000    161459  ...         0.0        0.0       0
5955  20230318   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 16:20:01,573:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679127599, self.tradeDate='20230318', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27114.2, self.close=27183.5, self.high=27193.0, self.low=27050.0, self.vol=7398.635, self.amt=200664400.9921, ukdf['pct'].iloc[-1]=0.002475 , ukdf['amount'].iloc[-1]=200664400.9921, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [18/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27995
self.closeSec=1679127899, self.tradeDate='20230318', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27183.5, self.close=27196.6, self.high=27225.0, self.low=27170.4, self.vol=2262.088, self.amt=61528708.2405 
2023-03-18 16:25:01,598:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230318   160000    160459  ...         0.0        0.0       0
5953  20230318   160500    160959  ...         0.0        0.0       0
5954  20230318   161000    161459  ...         0.0        0.0       0
5955  20230318   161500    161959  ...         0.0        0.0       0
5956  20230318   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-18 16:25:01,598:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679127899, self.tradeDate='20230318', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27183.5, self.close=27196.6, self.high=27225.0, self.low=27170.4, self.vol=2262.088, self.amt=61528708.2405, ukdf['pct'].iloc[-1]=0.000482 , ukdf['amount'].iloc[-1]=61528708.2405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230318   040000    075959  1679097599  ...    721  0.897811  0.812698     1.0
722  20230318   080000    115959  1679111999  ...    722  0.861374  0.690349     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '-5408.8207936819', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27299.45495318', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=678
self.closeSec=1679126399, self.tradeDate='20230318', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27293.4, self.close=27351.9, self.high=27600.0, self.low=27205.0, self.vol=67348.417, self.amt=1847160678.4641 
127.0.0.1 - - [18/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-03-18 16:00:02,275:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679126399, self.tradeDate='20230318', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27293.4, self.close=27351.9, self.high=27600.0, self.low=27205.0, self.vol=67348.417, self.amt=1847160678.4641 
2023-03-18 16:00:02,350:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230317   200000    235959  ...  264742.761  7.010303e+09 -0.018546
720  20230318   000000    035959  ...  166484.320  4.421618e+09  0.015141
721  20230318   040000    075959  ...  271230.892  7.389118e+09  0.021315
722  20230318   080000    115959  ...  145608.554  3.984148e+09 -0.003312
723  20230318   120000    155959  ...   67348.417  1.847161e+09  0.002147

[5 rows x 11 columns]
2023-03-18 16:00:04,448:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230317   200000    235959  1679068799  ...    719  0.301906 -0.883417    -1.0
720  20230318   000000    035959  1679083199  ...    720  0.764404  0.443770     NaN
721  20230318   040000    075959  1679097599  ...    721  0.897811  0.812698     1.0
722  20230318   080000    115959  1679111999  ...    722  0.861374  0.690349     1.0
723  20230318   120000    155959  1679126399  ...    723  0.790757  0.466857     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '-2488.4323862104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27353.74231088', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


