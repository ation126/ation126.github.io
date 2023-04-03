# 20230403 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36604
self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28112.7, self.close=28356.3, self.high=28424.0, self.low=28112.6, self.vol=23929.56, self.amt=676943139.74076 
127.0.0.1 - - [03/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-03 16:20:09,091:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230403   155500    155959  ...         0.0        0.0       0
5952  20230403   160000    160459  ...         0.0        0.0       0
5953  20230403   160500    160959  ...         0.0        0.0       0
5954  20230403   161000    161459  ...         0.0        0.0       0
5955  20230403   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 16:20:09,111:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28112.7, self.close=28356.3, self.high=28424.0, self.low=28112.6, self.vol=23929.56, self.amt=676943139.74076, ukdf['pct'].iloc[-1]=0.008665 , ukdf['amount'].iloc[-1]=676943139.74076, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-711171.0024159528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28347.48336905', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36605
self.closeSec=1680510299, self.tradeDate='20230403', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28346.3, self.close=28330.6, self.high=28388.0, self.low=28258.0, self.vol=8324.597, self.amt=235781493.4585 
2023-04-03 16:25:01,620:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230403   160000    160459  ...         0.0        0.0       0
5953  20230403   160500    160959  ...         0.0        0.0       0
5954  20230403   161000    161459  ...         0.0        0.0       0
5955  20230403   161500    161959  ...         0.0        0.0       0
5956  20230403   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 16:25:01,621:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680510299, self.tradeDate='20230403', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28346.3, self.close=28330.6, self.high=28388.0, self.low=28258.0, self.vol=8324.597, self.amt=235781493.4585, ukdf['pct'].iloc[-1]=-0.000906 , ukdf['amount'].iloc[-1]=235781493.4585, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-710239.2752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28332', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28112.7, self.close=28356.3, self.high=28424.0, self.low=28112.6 
127.0.0.1 - - [03/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-03 16:20:06,611:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28112.7, self.close=28356.3, self.high=28424.0, self.low=28112.6   
2023-04-03 16:20:07,761:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230403   155500    155959  1680508799  ...  27895.1  0.001645   1631    5
1632  20230403   160000    160459  1680509099  ...  27944.0  0.002891   1632    0
1633  20230403   160500    160959  1680509399  ...  28022.0  0.003514   1633    1
1634  20230403   161000    161459  1680509699  ...  28087.0 -0.000462   1634    2
1635  20230403   161500    161959  1680509999  ...  28112.6  0.008665   1635    3

[5 rows x 11 columns]
2023-04-03 16:20:07,771:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6918845310501087, self.count=37171 

self.closeSec=1680510299, self.tradeDate='20230403', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28346.3, self.close=28330.6, self.high=28388.0, self.low=28258.0 
2023-04-03 16:25:01,556:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680510299, self.tradeDate='20230403', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28346.3, self.close=28330.6, self.high=28388.0, self.low=28258.0   
2023-04-03 16:25:01,624:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230403   160000    160459  1680509099  ...  27944.0  0.002891   1632    0
1633  20230403   160500    160959  1680509399  ...  28022.0  0.003514   1633    1
1634  20230403   161000    161459  1680509699  ...  28087.0 -0.000462   1634    2
1635  20230403   161500    161959  1680509999  ...  28112.6  0.008665   1635    3
1636  20230403   162000    162459  1680510299  ...  28258.0 -0.000906   1636    4

[5 rows x 11 columns]
2023-04-03 16:25:01,625:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

5787  20230403    135959  27700.5  ...  52.083333  0.401555  0.729107
5788  20230403    142959  27666.0  ...  52.083333  0.409030  0.735714
5789  20230403    145959  27698.0  ...  52.083333  0.424119  0.736288
5790  20230403    152959  27764.0  ...  52.083333  0.454505  0.725458

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-04-03 16:00:35,071:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.527071  0.472929       0  ...  0.885399  -1.0  0.0000  1.013195
538     0  0.516308  0.483692       1  ...  0.884372  -1.0  0.0000  1.014371
539     0  0.529763  0.470237       1  ...  0.882265  -1.0  0.0000  1.016788
540     0  0.542999  0.457001       1  ...  0.877781  -1.0  0.0000  1.021955
541     0  0.565514  0.434486       1  ...  0.877676   1.0 -0.0016  1.023468

[5 rows x 10 columns]
2023-04-03 16:00:35,110:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.527699  0.472301       0  ...  0.883328  -1.0  0.0000  1.017533
46     0  0.515737  0.484263       1  ...  0.880445  -1.0  0.0000  1.014575
47     0  0.529889  0.470111       1  ...  0.880201  -1.0  0.0000  1.019468
48     0  0.542255  0.457745       1  ...  0.873884  -1.0  0.0000  1.020759
49     0  0.565514  0.434486       1  ...  0.877676   1.0 -0.0016  1.023468

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-04-03 16:00:35,415:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '27.369', 'buy' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:765439.7706', 'result': 'success', 'clientorderid': ''}
2023-04-03 16:00:35,429:INFO:logic:main.py:494:insertFactor:885513: curDateTime:4031600, name:logic, symbol:BTCUSDT, tradeDate:20230403, closeTime:155959, close:27946.4, sign:1, total:767183.2585902, side:buy  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230403   155000    155959  1680508799  27859.7  27946.4  0.003112
2023-04-03 16:00:01,995:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18584 

self.closeSec=1680509399, self.tradeDate='20230403', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27946.5', self.close='28125.7'
2023-04-03 16:10:01,721:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680509399, self.tradeDate='20230403', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27946.5', self.close='28125.7'
127.0.0.1 - - [03/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-03 16:10:01,753:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230403   152000    152959  1680506999  27832.2  27905.1  0.002616
525  20230403   153000    153959  1680507599  27905.2  27866.7 -0.001376
526  20230403   154000    154959  1680508199  27866.7  27859.7 -0.000251
527  20230403   155000    155959  1680508799  27859.7  27946.4  0.003112
528  20230403   160000    160959  1680509399  27946.5  28125.7  0.006416
2023-04-03 16:10:01,759:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18585 

self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28125.7', self.close='28356.3'
127.0.0.1 - - [03/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-03 16:20:07,321:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28125.7', self.close='28356.3'
2023-04-03 16:20:08,422:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230403   153000    153959  1680507599  27905.2  27866.7 -0.001376
526  20230403   154000    154959  1680508199  27866.7  27859.7 -0.000251
527  20230403   155000    155959  1680508799  27859.7  27946.4  0.003112
528  20230403   160000    160959  1680509399  27946.5  28125.7  0.006416
529  20230403   161000    161959  1680509999  28125.7  28356.3  0.008199
2023-04-03 16:20:08,422:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230403   155000    155959  1680508799  27859.7  27946.4
2023-04-03 16:00:01,993:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18585 

self.closeSec=1680509399, self.tradeDate='20230403', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27946.5', self.close='28125.7'
127.0.0.1 - - [03/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-03 16:10:01,746:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680509399, self.tradeDate='20230403', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27946.5', self.close='28125.7'
2023-04-03 16:10:01,771:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230403   152000    152959  1680506999  27832.2  27905.1
17517  20230403   153000    153959  1680507599  27905.2  27866.7
17518  20230403   154000    154959  1680508199  27866.7  27859.7
17519  20230403   155000    155959  1680508799  27859.7  27946.4
17520  20230403   160000    160959  1680509399  27946.5  28125.7
2023-04-03 16:10:01,771:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18586 

self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28125.7', self.close='28356.3'
127.0.0.1 - - [03/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-03 16:20:10,703:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28125.7', self.close='28356.3'
2023-04-03 16:20:10,837:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230403   153000    153959  1680507599  27905.2  27866.7
17518  20230403   154000    154959  1680508199  27866.7  27859.7
17519  20230403   155000    155959  1680508799  27859.7  27946.4
17520  20230403   160000    160959  1680509399  27946.5  28125.7
17521  20230403   161000    161959  1680509999  28125.7  28356.3
2023-04-03 16:20:10,838:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230403   155000    155959  1680508799  27859.7  27946.4
2023-04-03 16:00:02,000:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18585 

self.closeSec=1680509399, self.tradeDate='20230403', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27946.5', self.close='28125.7'
2023-04-03 16:10:01,778:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680509399, self.tradeDate='20230403', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27946.5', self.close='28125.7'
2023-04-03 16:10:01,790:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230403   152000    152959  1680506999  27832.2  27905.1
12189  20230403   153000    153959  1680507599  27905.2  27866.7
12190  20230403   154000    154959  1680508199  27866.7  27859.7
12191  20230403   155000    155959  1680508799  27859.7  27946.4
12192  20230403   160000    160959  1680509399  27946.5  28125.7
2023-04-03 16:10:01,790:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18586 

self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28125.7', self.close='28356.3'
127.0.0.1 - - [03/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-03 16:20:10,232:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28125.7', self.close='28356.3'
2023-04-03 16:20:10,533:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230403   153000    153959  1680507599  27905.2  27866.7
12190  20230403   154000    154959  1680508199  27866.7  27859.7
12191  20230403   155000    155959  1680508799  27859.7  27946.4
12192  20230403   160000    160959  1680509399  27946.5  28125.7
12193  20230403   161000    161959  1680509999  28125.7  28356.3
2023-04-03 16:20:10,533:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32602
self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28112.7, self.close=28356.3, self.high=28424.0, self.low=28112.6, self.vol=23929.56, self.amt=676943139.74076 
127.0.0.1 - - [03/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-04-03 16:20:07,622:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230403   155500    155959  ...         0.0        0.0       0
5952  20230403   160000    160459  ...         0.0        0.0       0
5953  20230403   160500    160959  ...         0.0        0.0       0
5954  20230403   161000    161459  ...         0.0        0.0       0
5955  20230403   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 16:20:07,661:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680509999, self.tradeDate='20230403', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28112.7, self.close=28356.3, self.high=28424.0, self.low=28112.6, self.vol=23929.56, self.amt=676943139.74076, ukdf['pct'].iloc[-1]=0.008665 , ukdf['amount'].iloc[-1]=676943139.74076, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32603
self.closeSec=1680510299, self.tradeDate='20230403', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28346.3, self.close=28330.6, self.high=28388.0, self.low=28258.0, self.vol=8324.597, self.amt=235781493.4585 
2023-04-03 16:25:01,625:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230403   160000    160459  ...         0.0        0.0       0
5953  20230403   160500    160959  ...         0.0        0.0       0
5954  20230403   161000    161459  ...         0.0        0.0       0
5955  20230403   161500    161959  ...         0.0        0.0       0
5956  20230403   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 16:25:01,626:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680510299, self.tradeDate='20230403', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28346.3, self.close=28330.6, self.high=28388.0, self.low=28258.0, self.vol=8324.597, self.amt=235781493.4585, ukdf['pct'].iloc[-1]=-0.000906 , ukdf['amount'].iloc[-1]=235781493.4585, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230403   040000    075959  1680479999  ...    721  0.119203 -0.783243    -1.0
722  20230403   080000    115959  1680494399  ...    722  0.133327 -0.724516    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '34555.1792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27735.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [03/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=774
self.closeSec=1680508799, self.tradeDate='20230403', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27738.1, self.close=27946.4, self.high=27951.9, self.low=27559.2, self.vol=59552.703, self.amt=1652843366.43728 
2023-04-03 16:00:01,808:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680508799, self.tradeDate='20230403', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27738.1, self.close=27946.4, self.high=27951.9, self.low=27559.2, self.vol=59552.703, self.amt=1652843366.43728 
2023-04-03 16:00:01,896:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230402   200000    235959  ...  92591.724  2.610223e+09 -0.008280
720  20230403   000000    035959  ...  83183.919  2.334075e+09 -0.006279
721  20230403   040000    075959  ...  59221.178  1.659291e+09  0.008144
722  20230403   080000    115959  ...  92246.758  2.562180e+09 -0.015024
723  20230403   120000    155959  ...  59552.703  1.652843e+09  0.007510

[5 rows x 11 columns]
2023-04-03 16:00:04,329:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230402   200000    235959  1680451199  ...    719  0.088071 -0.911072    -1.0
720  20230403   000000    035959  1680465599  ...    720  0.102683 -0.849219    -1.0
721  20230403   040000    075959  1680479999  ...    721  0.119203 -0.783243    -1.0
722  20230403   080000    115959  1680494399  ...    722  0.133327 -0.724516    -1.0
723  20230403   120000    155959  1680508799  ...    723  0.249354 -0.352679     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '23564.6112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27946.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


