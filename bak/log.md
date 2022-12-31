# 20230101 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [01/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9914
self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16587.7, self.close=16587.5, self.high=16590.5, self.low=16586.9, self.vol=252.476, self.amt=4188041.3742 
2023-01-01 00:10:01,668:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221231   234500    234959  ...         0.0        0.0       0
5758  20221231   235000    235459  ...         0.0        0.0       0
5759  20221231   235500    235959  ...         0.0        0.0       0
5760  20230101   000000    000459  ...         0.0        0.0       0
5761  20230101   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 00:10:01,669:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16587.7, self.close=16587.5, self.high=16590.5, self.low=16586.9, self.vol=252.476, self.amt=4188041.3742, ukdf['pct'].iloc[-1]=-1.2e-05 , ukdf['amount'].iloc[-1]=4188041.3742, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-3502.2432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16587.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9915
self.closeSec=1672503299, self.tradeDate='20230101', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16587.5, self.close=16588.4, self.high=16588.5, self.low=16587.5, self.vol=131.47, self.amt=2180863.002 
2023-01-01 00:15:00,636:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221231   235000    235459  ...         0.0        0.0       0
5759  20221231   235500    235959  ...         0.0        0.0       0
5760  20230101   000000    000459  ...         0.0        0.0       0
5761  20230101   000500    000959  ...         0.0        0.0       0
5762  20230101   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 00:15:00,636:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672503299, self.tradeDate='20230101', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16587.5, self.close=16588.4, self.high=16588.5, self.low=16587.5, self.vol=131.47, self.amt=2180863.002, ukdf['pct'].iloc[-1]=5.4e-05 , ukdf['amount'].iloc[-1]=2180863.002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-3556.4016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16588.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16587.7, self.close=16587.5, self.high=16590.5, self.low=16586.9 
2023-01-01 00:10:01,649:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16587.7, self.close=16587.5, self.high=16590.5, self.low=16586.9   
127.0.0.1 - - [01/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 00:10:01,692:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221231   234500    234959  1672501799  ...  16591.6  0.000066   1725    3
1438  20221231   235000    235459  1672502099  ...  16594.2 -0.000024   1726    4
1439  20221231   235500    235959  1672502399  ...  16581.4 -0.000524   1727    5
1440  20230101   000000    000459  1672502699  ...  16586.0  0.000102   1440    0
1441  20230101   000500    000959  1672502999  ...  16586.9 -0.000012   1441    1

[5 rows x 11 columns]
2023-01-01 00:10:01,692:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=51, self.factor=0.350872180803688, self.count=10481 

self.closeSec=1672503299, self.tradeDate='20230101', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16587.5, self.close=16588.4, self.high=16588.5, self.low=16587.5 
2023-01-01 00:15:00,549:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672503299, self.tradeDate='20230101', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16587.5, self.close=16588.4, self.high=16588.5, self.low=16587.5   
2023-01-01 00:15:00,573:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221231   235000    235459  1672502099  ...  16594.2 -0.000024   1726    4
1439  20221231   235500    235959  1672502399  ...  16581.4 -0.000524   1727    5
1440  20230101   000000    000459  1672502699  ...  16586.0  0.000102   1440    0
1441  20230101   000500    000959  1672502999  ...  16586.9 -0.000012   1441    1
1442  20230101   001000    001459  1672503299  ...  16587.5  0.000054   1442    2

[5 rows x 11 columns]
2023-01-01 00:15:00,573:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

5806  20221231    232959  16584.8  ...  45.416667  0.522288  0.420850

[5 rows x 33 columns]
0.5165441176470589
acc is : 0.5165441176470589
2023-01-01 00:00:18,849:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     0  0.500753  0.499247       1  ...  NaN   NaN -0.0016  0.988188
540     0  0.504020  0.495980       1  ...  NaN   NaN -0.0016  0.989938
541     0  0.510380  0.489620       0  ...  NaN   NaN -0.0016  0.987426
542     1  0.490860  0.509140       1  ...  NaN   NaN -0.0016  0.988378
543     0  0.503686  0.496314       0  ...  NaN   NaN -0.0016  0.987491

[5 rows x 10 columns]
2023-01-01 00:00:18,860:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.500589  0.499411       1  ...  NaN   NaN -0.0016  0.989980
46     0  0.503526  0.496474       1  ...  NaN   NaN -0.0016  0.987909
47     0  0.510000  0.490000       0  ...  NaN   NaN -0.0016  0.985402
48     1  0.490570  0.509430       1  ...  NaN   NaN -0.0016  0.988396
49     0  0.503686  0.496314       0  ...  NaN   NaN -0.0016  0.987491

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-4716.3552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16590.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
Traceback (most recent call last):
  File "/root/FIL/strategy/logic/FIL_lib/client.py", line 95, in __start_handle
    handle_call(handle_data)
  File "main.py", line 431, in handleKline
    curSign = int(df_panel['sign'].iloc[-1])
ValueError: cannot convert float NaN to integer


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-01 00:00:01,081:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221231   231000    231959  1672499999  16603.9  16618.6  0.000879
572  20221231   232000    232959  1672500599  16619.4  16600.9 -0.001065
573  20221231   233000    233959  1672501199  16600.9  16594.5 -0.000386
574  20221231   234000    234959  1672501799  16594.6  16595.1  0.000036
575  20221231   235000    235959  1672502399  16595.1    16586 -0.000548
2023-01-01 00:00:01,081:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.51', 'enterprice': '16552.4', 'countrevence': '0', 'unrealprofit': '-1931.7701884572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16587.20039972', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-01 00:00:01,802:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-01 00:00:01,802:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.51, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41449F1672502401799I0L59'}
2023-01-01 00:00:01,824:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1010000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221231, closeTime:235959, close:16586, total:917904.900276, mom:-0.0011435881705644801, thd:0.0, side:buy 
2023-01-01 00:00:02,182:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41449F1672502401799I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672502401914787, 'quantity': '55.51', 'price': '16586.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672502401356, 'updatetime': 1672502401914, 'tradetype': 'usdt', 'selfid': 41449, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672502401914, 'clientorderid': '41449F1672502401799I0L59', 'price': '16586.1', 'quantity': '55.51', 'commission': '920.694411', 'commissionasset': 'USDT', 'tradetime': 1672502401914, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672502401914}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-01 00:00:02,430:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41449F1672502401799I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672502401914787, 'quantity': '55.51', 'price': '16586.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672502401356, 'updatetime': 1672502401914, 'tradetype': 'usdt', 'selfid': 41449, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672502401914, 'clientorderid': '41449F1672502401799I0L59', 'price': '16586.1', 'quantity': '55.51', 'commission': '920.694411', 'commissionasset': 'USDT', 'tradetime': 1672502401914, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672502401914}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5240 

self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16586.1', self.close='16587.5'
2023-01-01 00:10:02,004:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16586.1', self.close='16587.5'
2023-01-01 00:10:02,014:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221231   232000    232959  1672500599  16619.4  16600.9 -0.001065
573  20221231   233000    233959  1672501199  16600.9  16594.5 -0.000386
574  20221231   234000    234959  1672501799  16594.6  16595.1  0.000036
575  20221231   235000    235959  1672502399  16595.1    16586 -0.000548
576  20230101   000000    000959  1672502999  16586.1  16587.5  0.000090
2023-01-01 00:10:02,014:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-31 23:50:00,599:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5240 

self.closeSec=1672502399, self.tradeDate='20221231', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16595.1', self.close='16586'
127.0.0.1 - - [01/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-01 00:00:01,065:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672502399, self.tradeDate='20221231', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16595.1', self.close='16586'
2023-01-01 00:00:01,136:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221231   231000    231959  1672499999  16603.9  16618.6
17420  20221231   232000    232959  1672500599  16619.4  16600.9
17421  20221231   233000    233959  1672501199  16600.9  16594.5
17422  20221231   234000    234959  1672501799  16594.6  16595.1
17423  20221231   235000    235959  1672502399  16595.1    16586
2023-01-01 00:00:01,136:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-01 00:00:01,400:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1010000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221231, closeTime:235959, close:16586, total:943801.2083061, pct_pre:-0.000489363887361649, thd:0.3436547151082719, side:sell 
127.0.0.1 - - [01/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5241 

self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16586.1', self.close='16587.5'
2023-01-01 00:10:01,992:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16586.1', self.close='16587.5'
2023-01-01 00:10:02,020:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221231   232000    232959  1672500599  16619.4  16600.9
17421  20221231   233000    233959  1672501199  16600.9  16594.5
17422  20221231   234000    234959  1672501799  16594.6  16595.1
17423  20221231   235000    235959  1672502399  16595.1    16586
17424  20230101   000000    000959  1672502999  16586.1  16587.5
2023-01-01 00:10:02,020:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-01 00:00:01,111:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221231   231000    231959  1672499999  16603.9  16618.6
12236  20221231   232000    232959  1672500599  16619.4  16600.9
12237  20221231   233000    233959  1672501199  16600.9  16594.5
12238  20221231   234000    234959  1672501799  16594.6  16595.1
12239  20221231   235000    235959  1672502399  16595.1    16586
2023-01-01 00:00:01,111:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '76.073', 'enterprice': '16580.1', 'countrevence': '0', 'unrealprofit': '540.14870789956', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16587.20039972', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-01 00:00:01,774:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-01 00:00:01,775:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 76.073, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41448F1672502401771I0L2'}
2023-01-01 00:00:01,818:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1010000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221231, closeTime:235959, close:16586, total:1260036.6493527, corrDate:20221213, corrVal:0.902261666470195, side:sell 
127.0.0.1 - - [01/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-01 00:00:01,939:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41448F1672502401771I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672502401902174, 'quantity': '76.073', 'price': '16586', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672502401357, 'updatetime': 1672502401902, 'tradetype': 'usdt', 'selfid': 41448, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672502401902, 'clientorderid': '41448F1672502401771I0L2', 'price': '16586', 'quantity': '76.073', 'commission': '1261.746778', 'commissionasset': 'USDT', 'tradetime': 1672502401902, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672502401902}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-01 00:00:02,161:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41448F1672502401771I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672502401902174, 'quantity': '76.073', 'price': '16586', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672502401357, 'updatetime': 1672502401902, 'tradetype': 'usdt', 'selfid': 41448, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672502401902, 'clientorderid': '41448F1672502401771I0L2', 'price': '16586', 'quantity': '76.073', 'commission': '1261.746778', 'commissionasset': 'USDT', 'tradetime': 1672502401902, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672502401902}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5241 

self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16586.1', self.close='16587.5'
2023-01-01 00:10:01,991:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16586.1', self.close='16587.5'
127.0.0.1 - - [01/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 00:10:01,998:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221231   232000    232959  1672500599  16619.4  16600.9
12237  20221231   233000    233959  1672501199  16600.9  16594.5
12238  20221231   234000    234959  1672501799  16594.6  16595.1
12239  20221231   235000    235959  1672502399  16595.1    16586
12240  20230101   000000    000959  1672502999  16586.1  16587.5
2023-01-01 00:10:01,999:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5912
self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16587.7, self.close=16587.5, self.high=16590.5, self.low=16586.9, self.vol=252.476, self.amt=4188041.3742 
127.0.0.1 - - [01/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 00:10:01,650:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221231   234500    234959  ...         0.0        0.0       0
5758  20221231   235000    235459  ...         0.0        0.0       0
5759  20221231   235500    235959  ...         0.0        0.0       0
5760  20230101   000000    000459  ...         0.0        0.0       0
5761  20230101   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 00:10:01,650:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672502999, self.tradeDate='20230101', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16587.7, self.close=16587.5, self.high=16590.5, self.low=16586.9, self.vol=252.476, self.amt=4188041.3742, ukdf['pct'].iloc[-1]=-1.2e-05 , ukdf['amount'].iloc[-1]=4188041.3742, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5913
self.closeSec=1672503299, self.tradeDate='20230101', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16587.5, self.close=16588.4, self.high=16588.5, self.low=16587.5, self.vol=131.47, self.amt=2180863.002 
127.0.0.1 - - [01/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-01 00:15:00,584:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221231   235000    235459  ...         0.0        0.0       0
5759  20221231   235500    235959  ...         0.0        0.0       0
5760  20230101   000000    000459  ...         0.0        0.0       0
5761  20230101   000500    000959  ...         0.0        0.0       0
5762  20230101   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 00:15:00,585:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672503299, self.tradeDate='20230101', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16587.5, self.close=16588.4, self.high=16588.5, self.low=16587.5, self.vol=131.47, self.amt=2180863.002, ukdf['pct'].iloc[-1]=5.4e-05 , ukdf['amount'].iloc[-1]=2180863.002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221231   120000    155959  1672473599  ...    723  0.374744  0.093364     NaN
724  20221231   160000    195959  1672487999  ...    724  0.314214 -0.059448     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-3433.88694918048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16566.38915824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [01/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=895432.8006702, self.flagDict['side']='buy', self.tradeCount=8, self.count=218
self.closeSec=1672502399, self.tradeDate='20221231', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16565.5, self.close=16586.0, self.high=16640.0, self.low=16546.2, self.vol=37418.928, self.amt=621005828.3915 
2023-01-01 00:00:00,956:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672502399, self.tradeDate='20221231', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16565.5, self.close=16586.0, self.high=16640.0, self.low=16546.2, self.vol=37418.928, self.amt=621005828.3915 
2023-01-01 00:00:00,977:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221231   040000    075959  ...  34781.545  5.770932e+08  0.004861
722  20221231   080000    115959  ...  15952.362  2.643333e+08 -0.003132
723  20221231   120000    155959  ...  15302.151  2.532091e+08  0.000925
724  20221231   160000    195959  ...  18890.316  3.128260e+08  0.000072
725  20221231   200000    235959  ...  37418.928  6.210058e+08  0.001231

[5 rows x 11 columns]
2023-01-01 00:00:02,775:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221231   040000    075959  1672444799  ...    721  0.543605  0.502980     NaN
722  20221231   080000    115959  1672459199  ...    722  0.484071  0.366170     NaN
723  20221231   120000    155959  1672473599  ...    723  0.374744  0.093364     NaN
724  20221231   160000    195959  1672487999  ...    724  0.314214 -0.059448     NaN
725  20221231   200000    235959  1672502399  ...    725  0.206195 -0.342355     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-2308.89875107086', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16587.26169893', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


