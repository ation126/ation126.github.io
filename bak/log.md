# 20230324 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33532
self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28442.1, self.close=28368.0, self.high=28534.7, self.low=28353.2, self.vol=7063.976, self.amt=200881727.1133 
127.0.0.1 - - [24/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-24 00:20:09,075:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230323   235500    235959  ...         0.0        0.0       0
5760  20230324   000000    000459  ...         0.0        0.0       0
5761  20230324   000500    000959  ...         0.0        0.0       0
5762  20230324   001000    001459  ...         0.0        0.0       0
5763  20230324   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 00:20:09,096:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28442.1, self.close=28368.0, self.high=28534.7, self.low=28353.2, self.vol=7063.976, self.amt=200881727.1133, ukdf['pct'].iloc[-1]=-0.002602 , ukdf['amount'].iloc[-1]=200881727.1133, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-713356.392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28383.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33533
self.closeSec=1679588699, self.tradeDate='20230324', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28367.9, self.close=28414.3, self.high=28456.7, self.low=28364.5, self.vol=4175.558, self.amt=118635737.447 
127.0.0.1 - - [24/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-24 00:25:01,687:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230324   000000    000459  ...         0.0        0.0       0
5761  20230324   000500    000959  ...         0.0        0.0       0
5762  20230324   001000    001459  ...         0.0        0.0       0
5763  20230324   001500    001959  ...         0.0        0.0       0
5764  20230324   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 00:25:01,690:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679588699, self.tradeDate='20230324', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28367.9, self.close=28414.3, self.high=28456.7, self.low=28364.5, self.vol=4175.558, self.amt=118635737.447, ukdf['pct'].iloc[-1]=0.001632 , ukdf['amount'].iloc[-1]=118635737.447, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-714917.38203573648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28409.74040873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28442.1, self.close=28368.0, self.high=28534.7, self.low=28353.2 
127.0.0.1 - - [24/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-24 00:20:06,276:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28442.1, self.close=28368.0, self.high=28534.7, self.low=28353.2   
2023-03-24 00:20:07,727:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230323   235500    235959  1679587199  ...  28521.0 -0.000829   1727    5
1440  20230324   000000    000459  1679587499  ...  28470.2 -0.002607   1440    0
1441  20230324   000500    000959  1679587799  ...  28500.0  0.001225   1441    1
1442  20230324   001000    001459  1679588099  ...  28430.0 -0.003256   1442    2
1443  20230324   001500    001959  1679588399  ...  28353.2 -0.002602   1443    3

[5 rows x 11 columns]
2023-03-24 00:20:07,736:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=300, self.factor=0.4862708651696635, self.count=34099 

self.closeSec=1679588699, self.tradeDate='20230324', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28367.9, self.close=28414.3, self.high=28456.7, self.low=28364.5 
2023-03-24 00:25:01,519:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679588699, self.tradeDate='20230324', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28367.9, self.close=28414.3, self.high=28456.7, self.low=28364.5   
2023-03-24 00:25:01,615:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230324   000000    000459  1679587499  ...  28470.2 -0.002607   1440    0
1441  20230324   000500    000959  1679587799  ...  28500.0  0.001225   1441    1
1442  20230324   001000    001459  1679588099  ...  28430.0 -0.003256   1442    2
1443  20230324   001500    001959  1679588399  ...  28353.2 -0.002602   1443    3
1444  20230324   002000    002459  1679588699  ...  28364.5  0.001632   1444    4

[5 rows x 11 columns]
2023-03-24 00:25:01,615:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-24 00:00:34,354:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230323    212959  27462.4  ...  52.500000  0.457440  0.594613
5803  20230323    215959  27345.9  ...  52.916667  0.458550  0.599384
5804  20230323    222959  27354.7  ...  52.500000  0.457415  0.600879
5805  20230323    225959  27344.1  ...  52.916667  0.534326  0.565700
5806  20230323    232959  28043.6  ...  53.333333  0.572488  0.537184

[5 rows x 33 columns]
0.5238970588235294
acc is : 0.5238970588235294
2023-03-24 00:00:34,508:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.480994  0.519006       1  ...  1.246525   1.0    0.0  1.345168
540     0  0.532933  0.467067       0  ...  1.246038   1.0    0.0  1.344642
541     0  0.516617  0.483383       1  ...  1.277913   1.0    0.0  1.379040
542     0  0.778217  0.221783       1  ...  1.297585   1.0    0.0  1.400268
543     0  0.753390  0.246610       1  ...  1.302106   1.0    0.0  1.405147

[5 rows x 10 columns]
2023-03-24 00:00:34,529:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.480773  0.519227       1  ...  1.246525   1.0    0.0  1.343114
46     0  0.532809  0.467191       0  ...  1.246038   1.0    0.0  1.345621
47     0  0.516502  0.483498       1  ...  1.277913   1.0    0.0  1.380044
48     0  0.777797  0.222203       1  ...  1.297585   1.0    0.0  1.399340
49     0  0.753390  0.246610       1  ...  1.302106   1.0    0.0  1.405147

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-03-24 00:00:03,220:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42046F1679587202848I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679587202967722, 'quantity': '28.885', 'price': '28575.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679587202509, 'updatetime': 1679587202967, 'tradetype': 'usdt', 'selfid': 42046, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679587202967, 'clientorderid': '42046F1679587202848I0L59', 'price': '28575.6', 'quantity': '28.885', 'commission': '825.406206', 'commissionasset': 'USDT', 'tradetime': 1679587202967, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679587202967}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17048 

self.closeSec=1679587799, self.tradeDate='20230324', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28574.6', self.close='28534.9'
2023-03-24 00:10:01,601:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679587799, self.tradeDate='20230324', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28574.6', self.close='28534.9'
2023-03-24 00:10:01,668:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230323   232000    232959  1679585399  28529.7  28475.3 -0.002180
573  20230323   233000    233959  1679585999  28475.2  28594.4  0.004183
574  20230323   234000    234959  1679586599  28594.3  28602.1  0.000269
575  20230323   235000    235959  1679587199    28608  28574.5 -0.000965
576  20230324   000000    000959  1679587799  28574.6  28534.9 -0.001386
2023-03-24 00:10:01,669:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17049 

self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28532', self.close='28368'
127.0.0.1 - - [24/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-24 00:20:08,117:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28532', self.close='28368'
2023-03-24 00:20:09,057:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230323   233000    233959  1679585999  28475.2  28594.4  0.004183
574  20230323   234000    234959  1679586599  28594.3  28602.1  0.000269
575  20230323   235000    235959  1679587199    28608  28574.5 -0.000965
576  20230324   000000    000959  1679587799  28574.6  28534.9 -0.001386
577  20230324   001000    001959  1679588399    28532    28368 -0.005849
2023-03-24 00:20:09,057:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-24 00:00:02,296:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-24 00:00:02,472:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3240000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230323, closeTime:235959, close:28574.5, total:1055364.7473673, pct_pre:-0.03287634766404901, thd:0.4249576638346216, side:sell 
127.0.0.1 - - [24/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17049 

self.closeSec=1679587799, self.tradeDate='20230324', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28574.6', self.close='28534.9'
2023-03-24 00:10:01,654:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679587799, self.tradeDate='20230324', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28574.6', self.close='28534.9'
2023-03-24 00:10:01,685:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230323   232000    232959  1679585399  28529.7  28475.3
17421  20230323   233000    233959  1679585999  28475.2  28594.4
17422  20230323   234000    234959  1679586599  28594.3  28602.1
17423  20230323   235000    235959  1679587199    28608  28574.5
17424  20230324   000000    000959  1679587799  28574.6  28534.9
2023-03-24 00:10:01,687:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17050 

self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28532', self.close='28368'
127.0.0.1 - - [24/Mar/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-03-24 00:20:10,581:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28532', self.close='28368'
2023-03-24 00:20:10,713:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230323   233000    233959  1679585999  28475.2  28594.4
17422  20230323   234000    234959  1679586599  28594.3  28602.1
17423  20230323   235000    235959  1679587199    28608  28574.5
17424  20230324   000000    000959  1679587799  28574.6  28534.9
17425  20230324   001000    001959  1679588399    28532    28368
2023-03-24 00:20:10,714:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-24 00:00:03,545:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42047F1679587203007I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679587203290698, 'quantity': '41.163', 'price': '28574.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679587202560, 'updatetime': 1679587203290, 'tradetype': 'usdt', 'selfid': 42047, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679587203290, 'clientorderid': '42047F1679587203007I0L2', 'price': '28574.5', 'quantity': '41.163', 'commission': '1176.2121435', 'commissionasset': 'USDT', 'tradetime': 1679587203290, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679587203290}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17049 

self.closeSec=1679587799, self.tradeDate='20230324', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28574.6', self.close='28534.9'
2023-03-24 00:10:01,654:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679587799, self.tradeDate='20230324', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28574.6', self.close='28534.9'
2023-03-24 00:10:01,672:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230323   232000    232959  1679585399  28529.7  28475.3
12237  20230323   233000    233959  1679585999  28475.2  28594.4
12238  20230323   234000    234959  1679586599  28594.3  28602.1
12239  20230323   235000    235959  1679587199    28608  28574.5
12240  20230324   000000    000959  1679587799  28574.6  28534.9
2023-03-24 00:10:01,672:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17050 

self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28532', self.close='28368'
127.0.0.1 - - [24/Mar/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-03-24 00:20:10,025:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28532', self.close='28368'
2023-03-24 00:20:10,391:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230323   233000    233959  1679585999  28475.2  28594.4
12238  20230323   234000    234959  1679586599  28594.3  28602.1
12239  20230323   235000    235959  1679587199    28608  28574.5
12240  20230324   000000    000959  1679587799  28574.6  28534.9
12241  20230324   001000    001959  1679588399    28532    28368
2023-03-24 00:20:10,392:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29530
self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28442.1, self.close=28368.0, self.high=28534.7, self.low=28353.2, self.vol=7063.976, self.amt=200881727.1133 
127.0.0.1 - - [24/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-24 00:20:07,196:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230323   235500    235959  ...         0.0        0.0       0
5760  20230324   000000    000459  ...         0.0        0.0       0
5761  20230324   000500    000959  ...         0.0        0.0       0
5762  20230324   001000    001459  ...         0.0        0.0       0
5763  20230324   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 00:20:07,236:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679588399, self.tradeDate='20230324', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28442.1, self.close=28368.0, self.high=28534.7, self.low=28353.2, self.vol=7063.976, self.amt=200881727.1133, ukdf['pct'].iloc[-1]=-0.002602 , ukdf['amount'].iloc[-1]=200881727.1133, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29531
self.closeSec=1679588699, self.tradeDate='20230324', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28367.9, self.close=28414.3, self.high=28456.7, self.low=28364.5, self.vol=4175.558, self.amt=118635737.447 
2023-03-24 00:25:01,645:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230324   000000    000459  ...         0.0        0.0       0
5761  20230324   000500    000959  ...         0.0        0.0       0
5762  20230324   001000    001459  ...         0.0        0.0       0
5763  20230324   001500    001959  ...         0.0        0.0       0
5764  20230324   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 00:25:01,650:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679588699, self.tradeDate='20230324', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28367.9, self.close=28414.3, self.high=28456.7, self.low=28364.5, self.vol=4175.558, self.amt=118635737.447, ukdf['pct'].iloc[-1]=0.001632 , ukdf['amount'].iloc[-1]=118635737.447, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230323   120000    155959  1679558399  ...    723  0.092907 -2.108669    -1.0
724  20230323   160000    195959  1679572799  ...    724  0.057176 -2.214658    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '27756.0482749662', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27574.2853373', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [24/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=710
self.closeSec=1679587199, self.tradeDate='20230323', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27573.5, self.close=28574.5, self.high=28777.0, self.low=27267.0, self.vol=280955.401, self.amt=7873060381.73335 
2023-03-24 00:00:01,972:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679587199, self.tradeDate='20230323', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27573.5, self.close=28574.5, self.high=28777.0, self.low=27267.0, self.vol=280955.401, self.amt=7873060381.73335 
2023-03-24 00:00:02,073:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230323   040000    075959  ...  168601.777  4.570693e+09  0.021339
722  20230323   080000    115959  ...   63845.694  1.742141e+09  0.004035
723  20230323   120000    155959  ...   84538.137  2.326729e+09  0.009973
724  20230323   160000    195959  ...   67047.240  1.848970e+09 -0.001557
725  20230323   200000    235959  ...  280955.401  7.873060e+09  0.036307

[5 rows x 11 columns]
2023-03-24 00:00:05,036:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230323   040000    075959  1679529599  ...    721  0.129752 -1.963301    -1.0
722  20230323   080000    115959  1679543999  ...    722  0.120047 -2.014558    -1.0
723  20230323   120000    155959  1679558399  ...    723  0.092907 -2.108669    -1.0
724  20230323   160000    195959  1679572799  ...    724  0.057176 -2.214658    -1.0
725  20230323   200000    235959  1679587199  ...    725  0.015358 -2.323733    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-25966.851', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28574.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


