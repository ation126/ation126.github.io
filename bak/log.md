# 20221213 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4442
self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16997.8, self.close=17010.0, self.high=17011.4, self.low=16997.4, self.vol=1078.213, self.amt=18335825.7111 
127.0.0.1 - - [13/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-13 00:10:01,503:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221212   234500    234959  ...         0.0        0.0       0
5758  20221212   235000    235459  ...         0.0        0.0       0
5759  20221212   235500    235959  ...         0.0        0.0       0
5760  20221213   000000    000459  ...         0.0        0.0       0
5761  20221213   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-13 00:10:01,504:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16997.8, self.close=17010.0, self.high=17011.4, self.low=16997.4, self.vol=1078.213, self.amt=18335825.7111, ukdf['pct'].iloc[-1]=0.000712 , ukdf['amount'].iloc[-1]=18335825.7111, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-28926.6032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17010', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4443
self.closeSec=1670861699, self.tradeDate='20221213', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17010.0, self.close=16990.0, self.high=17010.0, self.low=16990.0, self.vol=664.137, self.amt=11290443.9034 
127.0.0.1 - - [13/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-13 00:15:00,527:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221212   235000    235459  ...         0.0        0.0       0
5759  20221212   235500    235959  ...         0.0        0.0       0
5760  20221213   000000    000459  ...         0.0        0.0       0
5761  20221213   000500    000959  ...         0.0        0.0       0
5762  20221213   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-13 00:15:00,528:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670861699, self.tradeDate='20221213', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17010.0, self.close=16990.0, self.high=17010.0, self.low=16990.0, self.vol=664.137, self.amt=11290443.9034, ukdf['pct'].iloc[-1]=-0.001176 , ukdf['amount'].iloc[-1]=11290443.9034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-27864.6311639816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16992.35223285', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16997.8, self.close=17010.0, self.high=17011.4, self.low=16997.4 
2022-12-13 00:10:01,448:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16997.8, self.close=17010.0, self.high=17011.4, self.low=16997.4   
127.0.0.1 - - [13/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-13 00:10:01,481:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221212   234500    234959  1670860199  ...  16995.5 -0.000800   1725    3
1438  20221212   235000    235459  1670860499  ...  16996.0  0.000065   1726    4
1439  20221212   235500    235959  1670860799  ...  16996.0  0.000171   1727    5
1440  20221213   000000    000459  1670861099  ...  16984.4 -0.000118   1440    0
1441  20221213   000500    000959  1670861399  ...  16997.4  0.000712   1441    1

[5 rows x 11 columns]
2022-12-13 00:10:01,481:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6745095087727743, self.count=5009 

self.closeSec=1670861699, self.tradeDate='20221213', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17010.0, self.close=16990.0, self.high=17010.0, self.low=16990.0 
2022-12-13 00:15:00,521:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670861699, self.tradeDate='20221213', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17010.0, self.close=16990.0, self.high=17010.0, self.low=16990.0   
2022-12-13 00:15:00,574:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221212   235000    235459  1670860499  ...  16996.0  0.000065   1726    4
1439  20221212   235500    235959  1670860799  ...  16996.0  0.000171   1727    5
1440  20221213   000000    000459  1670861099  ...  16984.4 -0.000118   1440    0
1441  20221213   000500    000959  1670861399  ...  16997.4  0.000712   1441    1
1442  20221213   001000    001459  1670861699  ...  16990.0 -0.001176   1442    2

[5 rows x 11 columns]
2022-12-13 00:15:00,574:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-13 00:00:18,973:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221212    212959  16952.9  ...  54.166667  0.432784  0.775437
5803  20221212    215959  16964.2  ...  53.750000  0.431175  0.774275
5804  20221212    222959  16961.2  ...  53.750000  0.456335  0.768106
5805  20221212    225959  16990.8  ...  54.166667  0.468294  0.759816
5806  20221212    232959  17007.6  ...  54.583333  0.476261  0.747461

[5 rows x 33 columns]
0.5772058823529411
acc is : 0.5772058823529411
2022-12-13 00:00:19,065:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494415  0.505585       0  ...  0.962671   1.0    0.0  0.994092
540     1  0.492400  0.507600       1  ...  0.964402   1.0    0.0  0.995880
541     0  0.501769  0.498231       1  ...  0.965264   1.0    0.0  0.996771
542     0  0.503750  0.496250       1  ...  0.965849   1.0    0.0  0.997374
543     0  0.504639  0.495361       0  ...  0.964833   1.0    0.0  0.996325

[5 rows x 10 columns]
2022-12-13 00:00:19,093:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494064  0.505936       0  ...  0.962671   1.0    0.0  0.992435
46     1  0.491756  0.508244       1  ...  0.964402   1.0    0.0  0.992889
47     0  0.501131  0.498869       1  ...  0.965264   1.0    0.0  0.993777
48     0  0.503466  0.496534       1  ...  0.965849   1.0    0.0  0.994966
49     0  0.504639  0.495361       0  ...  0.964833   1.0    0.0  0.996325

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-8177.5396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16996.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-13 00:00:01,396:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221212   231000    231959  1670858399  17023.9    17016 -0.000464
572  20221212   232000    232959  1670858999  17017.7  17017.8  0.000106
573  20221212   233000    233959  1670859599  17017.8  17011.1 -0.000394
574  20221212   234000    234959  1670860199    17011  16996.9 -0.000835
575  20221212   235000    235959  1670860799  16996.9  16999.9  0.000177
2022-12-13 00:00:01,396:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.235', 'enterprice': '16905.7', 'countrevence': '0', 'unrealprofit': '-5121.91774753805', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17000.13934263', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-13 00:00:02,461:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-13 00:00:02,461:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.235, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41348F1670860802460I0L59'}
2022-12-13 00:00:02,483:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12130000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221212, closeTime:235959, close:16999.9, total:915963.7588605001, mom:-4.307945648418521e-05, thd:0.0, side:buy 
2022-12-13 00:00:02,783:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41348F1670860802460I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670860802556462, 'quantity': '54.235', 'price': '17000', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670860801815, 'updatetime': 1670860802556, 'tradetype': 'usdt', 'selfid': 41348, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670860802556, 'clientorderid': '41348F1670860802460I0L59', 'price': '17000', 'quantity': '54.235', 'commission': '921.995', 'commissionasset': 'USDT', 'tradetime': 1670860802556, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670860802556}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-13 00:00:02,939:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41348F1670860802460I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670860802556462, 'quantity': '54.235', 'price': '17000', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670860801815, 'updatetime': 1670860802556, 'tradetype': 'usdt', 'selfid': 41348, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670860802556, 'clientorderid': '41348F1670860802460I0L59', 'price': '17000', 'quantity': '54.235', 'commission': '921.995', 'commissionasset': 'USDT', 'tradetime': 1670860802556, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670860802556}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2504 

self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17000', self.close='17010'
2022-12-13 00:10:01,540:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17000', self.close='17010'
2022-12-13 00:10:01,580:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221212   232000    232959  1670858999  17017.7  17017.8  0.000106
573  20221212   233000    233959  1670859599  17017.8  17011.1 -0.000394
574  20221212   234000    234959  1670860199    17011  16996.9 -0.000835
575  20221212   235000    235959  1670860799  16996.9  16999.9  0.000177
576  20221213   000000    000959  1670861399    17000    17010  0.000594
2022-12-13 00:10:01,580:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-12 23:50:00,601:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2504 

self.closeSec=1670860799, self.tradeDate='20221212', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16996.9', self.close='16999.9'
2022-12-13 00:00:01,329:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670860799, self.tradeDate='20221212', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16996.9', self.close='16999.9'
2022-12-13 00:00:01,384:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221212   231000    231959  1670858399  17023.9    17016
17420  20221212   232000    232959  1670858999  17017.7  17017.8
17421  20221212   233000    233959  1670859599  17017.8  17011.1
17422  20221212   234000    234959  1670860199    17011  16996.9
17423  20221212   235000    235959  1670860799  16996.9  16999.9
2022-12-13 00:00:01,384:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-13 00:00:01,534:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12130000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221212, closeTime:235959, close:16999.9, total:935796.4056934, pct_pre:-0.011284970285827645, thd:-1.0413597139732191, side:sell 
127.0.0.1 - - [13/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2505 

self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17000', self.close='17010'
2022-12-13 00:10:01,532:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17000', self.close='17010'
2022-12-13 00:10:01,549:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221212   232000    232959  1670858999  17017.7  17017.8
17421  20221212   233000    233959  1670859599  17017.8  17011.1
17422  20221212   234000    234959  1670860199    17011  16996.9
17423  20221212   235000    235959  1670860799  16996.9  16999.9
17424  20221213   000000    000959  1670861399    17000    17010
2022-12-13 00:10:01,549:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-13 00:00:01,374:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221212   231000    231959  1670858399  17023.9    17016
12236  20221212   232000    232959  1670858999  17017.7  17017.8
12237  20221212   233000    233959  1670859599  17017.8  17011.1
12238  20221212   234000    234959  1670860199    17011  16996.9
12239  20221212   235000    235959  1670860799  16996.9  16999.9
2022-12-13 00:00:01,374:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '76.386', 'enterprice': '17090.4', 'countrevence': '0', 'unrealprofit': '-6894.65057386482', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17000.13934263', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-13 00:00:02,356:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-13 00:00:02,356:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 76.386, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41347F1670860802355I0L2'}
2022-12-13 00:00:02,370:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12130000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221212, closeTime:235959, close:16999.9, total:1304161.8271056, corrDate:20221028, corrVal:0.8455277634059493, side:sell 
2022-12-13 00:00:02,508:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41347F1670860802355I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670860802469022, 'quantity': '76.386', 'price': '16999.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670860801787, 'updatetime': 1670860802469, 'tradetype': 'usdt', 'selfid': 41347, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670860802469, 'clientorderid': '41347F1670860802355I0L2', 'price': '16999.9', 'quantity': '76.386', 'commission': '1298.5543614', 'commissionasset': 'USDT', 'tradetime': 1670860802469, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670860802469}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-13 00:00:02,763:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41347F1670860802355I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670860802469022, 'quantity': '76.386', 'price': '16999.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670860801787, 'updatetime': 1670860802469, 'tradetype': 'usdt', 'selfid': 41347, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670860802469, 'clientorderid': '41347F1670860802355I0L2', 'price': '16999.9', 'quantity': '76.386', 'commission': '1298.5543614', 'commissionasset': 'USDT', 'tradetime': 1670860802469, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670860802469}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2505 

self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17000', self.close='17010'
2022-12-13 00:10:01,562:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17000', self.close='17010'
2022-12-13 00:10:01,581:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221212   232000    232959  1670858999  17017.7  17017.8
12237  20221212   233000    233959  1670859599  17017.8  17011.1
12238  20221212   234000    234959  1670860199    17011  16996.9
12239  20221212   235000    235959  1670860799  16996.9  16999.9
12240  20221213   000000    000959  1670861399    17000    17010
2022-12-13 00:10:01,581:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=440
self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16997.8, self.close=17010.0, self.high=17011.4, self.low=16997.4, self.vol=1078.213, self.amt=18335825.7111 
2022-12-13 00:10:01,503:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221212   234500    234959  ...    0.506102   0.237223       0
5758  20221212   235000    235459  ...    0.505811   0.237501       0
5759  20221212   235500    235959  ...    0.505527   0.237779       0
5760  20221213   000000    000459  ...    0.505241   0.238057       0
5761  20221213   000500    000959  ...    0.504956   0.238334       0

[5 rows x 18 columns]
2022-12-13 00:10:01,504:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670861399, self.tradeDate='20221213', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16997.8, self.close=17010.0, self.high=17011.4, self.low=16997.4, self.vol=1078.213, self.amt=18335825.7111, ukdf['pct'].iloc[-1]=0.000712 , ukdf['amount'].iloc[-1]=18335825.7111, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.504956481228398, signal=0, value_std=0.23833357148854126 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [13/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=441
self.closeSec=1670861699, self.tradeDate='20221213', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17010.0, self.close=16990.0, self.high=17010.0, self.low=16990.0, self.vol=664.137, self.amt=11290443.9034 
2022-12-13 00:15:00,590:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221212   235000    235459  ...    0.505811   0.237501       0
5759  20221212   235500    235959  ...    0.505527   0.237779       0
5760  20221213   000000    000459  ...    0.505241   0.238057       0
5761  20221213   000500    000959  ...    0.504956   0.238334       0
5762  20221213   001000    001459  ...    0.504672   0.238610       0

[5 rows x 18 columns]
2022-12-13 00:15:00,591:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670861699, self.tradeDate='20221213', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17010.0, self.close=16990.0, self.high=17010.0, self.low=16990.0, self.vol=664.137, self.amt=11290443.9034, ukdf['pct'].iloc[-1]=-0.001176 , ukdf['amount'].iloc[-1]=11290443.9034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.5046721982207525, signal=0, value_std=0.23861002339693418 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2022-12-12 20:00:09,621:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41345F1670846404315I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670846404411040, 'quantity': '58.622', 'price': '16978.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670846404008, 'updatetime': 1670846404411, 'tradetype': 'usdt', 'selfid': 41345, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670846404411, 'clientorderid': '41345F1670846404315I0L65', 'price': '16978.7', 'quantity': '58.622', 'commission': '995.3253514', 'commissionasset': 'USDT', 'tradetime': 1670846404411, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670846404411}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-12 20:00:09,623:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41345F1670846404315I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670846404411040, 'quantity': '58.622', 'price': '16978.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670846404008, 'updatetime': 1670846404411, 'tradetype': 'usdt', 'selfid': 41345, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670846404411, 'clientorderid': '41345F1670846404315I0L65', 'price': '16978.7', 'quantity': '58.622', 'commission': '995.3253514', 'commissionasset': 'USDT', 'tradetime': 1670846404411, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670846404411}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-12 20:00:09,713:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41346F1670846409596I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670846409695616, 'quantity': '58.578', 'price': '16978.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670846409405, 'updatetime': 1670846409695, 'tradetype': 'usdt', 'selfid': 41346, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670846409695, 'clientorderid': '41346F1670846409596I0L65', 'price': '16978.7', 'quantity': '58.578', 'commission': '994.5782886', 'commissionasset': 'USDT', 'tradetime': 1670846409695, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670846409695}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Dec/2022 20:00:09] "POST / HTTP/1.1" 200 -
2022-12-12 20:00:09,930:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41346F1670846409596I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670846409695616, 'quantity': '58.578', 'price': '16978.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670846409405, 'updatetime': 1670846409695, 'tradetype': 'usdt', 'selfid': 41346, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670846409695, 'clientorderid': '41346F1670846409596I0L65', 'price': '16978.7', 'quantity': '58.578', 'commission': '994.5782886', 'commissionasset': 'USDT', 'tradetime': 1670846409695, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670846409695}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Dec/2022 20:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=993583.7103114001, self.flagDict['side']='sell', self.tradeCount=5, self.count=104
self.closeSec=1670860799, self.tradeDate='20221212', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16977.8, self.close=16999.9, self.high=17050.0, self.low=16912.8, self.vol=71821.147, self.amt=1219595887.6584 
2022-12-13 00:00:01,218:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670860799, self.tradeDate='20221212', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16977.8, self.close=16999.9, self.high=17050.0, self.low=16912.8, self.vol=71821.147, self.amt=1219595887.6584 
2022-12-13 00:00:01,295:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221212   040000    075959  ...  52598.599  8.996990e+08 -0.005353
722  20221212   080000    115959  ...  93215.464  1.579861e+09 -0.009873
723  20221212   120000    155959  ...  27433.054  4.641777e+08  0.000420
724  20221212   160000    195959  ...  36001.638  6.103408e+08  0.003647
725  20221212   200000    235959  ...  71821.147  1.219596e+09  0.001302

[5 rows x 11 columns]
2022-12-13 00:00:02,784:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221212   040000    075959  1670803199  ...    721  0.507540 -0.038979     NaN
722  20221212   080000    115959  1670817599  ...    722  0.404512 -0.433041     NaN
723  20221212   120000    155959  1670831999  ...    723  0.378032 -0.551198     NaN
724  20221212   160000    195959  1670846399  ...    724  0.299141 -0.866888    -1.0
725  20221212   200000    235959  1670860799  ...    725  0.200578 -1.259185    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.578', 'enterprice': '16978.7', 'countrevence': '0', 'unrealprofit': '-1272.68545255254', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17000.42633843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


