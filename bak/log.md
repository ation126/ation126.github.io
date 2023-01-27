# 20230128 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17690
self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22984.4, self.close=22991.3, self.high=23006.6, self.low=22955.0, self.vol=1783.643, self.amt=41001153.3774 
127.0.0.1 - - [28/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-28 00:10:01,763:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230127   234500    234959  ...         0.0        0.0       0
5758  20230127   235000    235459  ...         0.0        0.0       0
5759  20230127   235500    235959  ...         0.0        0.0       0
5760  20230128   000000    000459  ...         0.0        0.0       0
5761  20230128   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 00:10:01,765:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22984.4, self.close=22991.3, self.high=23006.6, self.low=22955.0, self.vol=1783.643, self.amt=41001153.3774, ukdf['pct'].iloc[-1]=0.000274 , ukdf['amount'].iloc[-1]=41001153.3774, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-388833.2416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22990.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17691
self.closeSec=1674836099, self.tradeDate='20230128', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22990.9, self.close=22983.7, self.high=23000.8, self.low=22974.5, self.vol=996.336, self.amt=22904659.7135 
2023-01-28 00:15:00,914:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230127   235000    235459  ...         0.0        0.0       0
5759  20230127   235500    235959  ...         0.0        0.0       0
5760  20230128   000000    000459  ...         0.0        0.0       0
5761  20230128   000500    000959  ...         0.0        0.0       0
5762  20230128   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 00:15:00,916:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674836099, self.tradeDate='20230128', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22990.9, self.close=22983.7, self.high=23000.8, self.low=22974.5, self.vol=996.336, self.amt=22904659.7135, ukdf['pct'].iloc[-1]=-0.000331 , ukdf['amount'].iloc[-1]=22904659.7135, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-388464.1357902864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22984.7662289', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22984.4, self.close=22991.3, self.high=23006.6, self.low=22955.0 
2023-01-28 00:10:01,671:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22984.4, self.close=22991.3, self.high=23006.6, self.low=22955.0   
127.0.0.1 - - [28/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-28 00:10:01,721:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230127   234500    234959  1674834599  ...  22987.8 -0.004914   1725    3
1438  20230127   235000    235459  1674834899  ...  22932.0 -0.002478   1726    4
1439  20230127   235500    235959  1674835199  ...  22924.3 -0.000153   1727    5
1440  20230128   000000    000459  1674835499  ...  22919.0  0.001857   1440    0
1441  20230128   000500    000959  1674835799  ...  22955.0  0.000274   1441    1

[5 rows x 11 columns]
2023-01-28 00:10:01,721:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=333, self.factor=0.48570403195657985, self.count=18257 

self.closeSec=1674836099, self.tradeDate='20230128', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22990.9, self.close=22983.7, self.high=23000.8, self.low=22974.5 
2023-01-28 00:15:00,800:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674836099, self.tradeDate='20230128', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22990.9, self.close=22983.7, self.high=23000.8, self.low=22974.5   
2023-01-28 00:15:00,876:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230127   235000    235459  1674834899  ...  22932.0 -0.002478   1726    4
1439  20230127   235500    235959  1674835199  ...  22924.3 -0.000153   1727    5
1440  20230128   000000    000459  1674835499  ...  22919.0  0.001857   1440    0
1441  20230128   000500    000959  1674835799  ...  22955.0  0.000274   1441    1
1442  20230128   001000    001459  1674836099  ...  22974.5 -0.000331   1442    2

[5 rows x 11 columns]
2023-01-28 00:15:00,877:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-28 00:00:18,603:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230127    212959  22926.6  ...  51.666667  0.489473  0.447821
5803  20230127    215959  22925.6  ...  52.083333  0.492733  0.445351
5804  20230127    222959  22896.3  ...  51.666667  0.488677  0.445259
5805  20230127    225959  22874.5  ...  51.666667  0.504902  0.436535
5806  20230127    232959  22958.3  ...  52.083333  0.527142  0.415844

[5 rows x 33 columns]
0.5147058823529411
acc is : 0.5147058823529411
2023-01-28 00:00:18,700:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.505922  0.494078       1  ...  0.943469   1.0    0.0  1.084310
540     0  0.517853  0.482147       0  ...  0.942588   1.0    0.0  1.083297
541     0  0.508412  0.491588       1  ...  0.946028   1.0    0.0  1.087251
542     0  0.538510  0.461490       1  ...  0.951027   1.0    0.0  1.092996
543     0  0.558185  0.441815       0  ...  0.945369   1.0    0.0  1.086494

[5 rows x 10 columns]
2023-01-28 00:00:18,723:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506771  0.493229       1  ...  0.943469   1.0    0.0  1.082245
46     0  0.517796  0.482204       0  ...  0.942588   1.0    0.0  1.081142
47     0  0.508386  0.491614       1  ...  0.946028   1.0    0.0  1.085088
48     0  0.539227  0.460773       1  ...  0.951027   1.0    0.0  1.093250
49     0  0.558185  0.441815       0  ...  0.945369   1.0    0.0  1.086494

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.8', 'enterprice': '23035.8', 'countrevence': '0', 'unrealprofit': '-2516.283703472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22954.10247716', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-28 00:00:01,889:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230127   231000    231959  1674832799    23034    23050  0.000699
572  20230127   232000    232959  1674833399  23050.2  23079.7  0.001289
573  20230127   233000    233959  1674833999    23077  23075.9 -0.000165
574  20230127   234000    234959  1674834599    23076    23002 -0.003202
575  20230127   235000    235959  1674835199    23002  22942.4 -0.002591
2023-01-28 00:00:01,889:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.455', 'enterprice': '22790', 'countrevence': '0', 'unrealprofit': '6054.2050135572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22936.04281784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-28 00:00:02,447:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-28 00:00:02,447:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 41.455, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41620F1674835202446I0L59'}
2023-01-28 00:00:02,474:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1280000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230127, closeTime:235959, close:22942.4, total:943814.6905499999, mom:0.0035384182988211776, thd:0.0, side:sell 
127.0.0.1 - - [28/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-28 00:00:02,583:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41620F1674835202446I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674835202543126, 'quantity': '41.455', 'price': '22926.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674835202058, 'updatetime': 1674835202543, 'tradetype': 'usdt', 'selfid': 41620, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674835202543, 'clientorderid': '41620F1674835202446I0L59', 'price': '22926.3', 'quantity': '41.455', 'commission': '950.4097665', 'commissionasset': 'USDT', 'tradetime': 1674835202543, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674835202543}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-28 00:00:02,882:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41620F1674835202446I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674835202543126, 'quantity': '41.455', 'price': '22926.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674835202058, 'updatetime': 1674835202543, 'tradetype': 'usdt', 'selfid': 41620, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674835202543, 'clientorderid': '41620F1674835202446I0L59', 'price': '22926.3', 'quantity': '41.455', 'commission': '950.4097665', 'commissionasset': 'USDT', 'tradetime': 1674835202543, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674835202543}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9128 

self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22928.8', self.close='22991.3'
2023-01-28 00:10:01,792:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22928.8', self.close='22991.3'
2023-01-28 00:10:01,802:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230127   232000    232959  1674833399  23050.2  23079.7  0.001289
573  20230127   233000    233959  1674833999    23077  23075.9 -0.000165
574  20230127   234000    234959  1674834599    23076    23002 -0.003202
575  20230127   235000    235959  1674835199    23002  22942.4 -0.002591
576  20230128   000000    000959  1674835799  22928.8  22991.3  0.002131
2023-01-28 00:10:01,802:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-27 23:50:00,529:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9128 

self.closeSec=1674835199, self.tradeDate='20230127', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='23002', self.close='22942.4'
2023-01-28 00:00:01,859:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674835199, self.tradeDate='20230127', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='23002', self.close='22942.4'
2023-01-28 00:00:01,891:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230127   231000    231959  1674832799    23034    23050
17420  20230127   232000    232959  1674833399  23050.2  23079.7
17421  20230127   233000    233959  1674833999    23077  23075.9
17422  20230127   234000    234959  1674834599    23076    23002
17423  20230127   235000    235959  1674835199    23002  22942.4
2023-01-28 00:00:01,891:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-28 00:00:02,041:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1280000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230127, closeTime:235959, close:22942.4, total:950078.9425875, pct_pre:0.002407417116692123, thd:-0.0020630451050654974, side:sell 
127.0.0.1 - - [28/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9129 

self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22928.8', self.close='22991.3'
2023-01-28 00:10:01,793:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22928.8', self.close='22991.3'
2023-01-28 00:10:01,809:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230127   232000    232959  1674833399  23050.2  23079.7
17421  20230127   233000    233959  1674833999    23077  23075.9
17422  20230127   234000    234959  1674834599    23076    23002
17423  20230127   235000    235959  1674835199    23002  22942.4
17424  20230128   000000    000959  1674835799  22928.8  22991.3
2023-01-28 00:10:01,818:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-28 00:00:01,896:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230127   231000    231959  1674832799    23034    23050
12236  20230127   232000    232959  1674833399  23050.2  23079.7
12237  20230127   233000    233959  1674833999    23077  23075.9
12238  20230127   234000    234959  1674834599    23076    23002
12239  20230127   235000    235959  1674835199    23002  22942.4
2023-01-28 00:00:01,900:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '49.009', 'enterprice': '22995.8', 'countrevence': '0', 'unrealprofit': '2928.63974047944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22936.04281784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-28 00:00:02,835:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-28 00:00:02,836:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 49.009, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41621F1674835202627I0L2'}
2023-01-28 00:00:02,866:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1280000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230127, closeTime:235959, close:22942.4, total:1125874.1610378, corrDate:20230118, corrVal:0.7170884350966907, side:buy 
2023-01-28 00:00:03,145:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41621F1674835202627I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674835203090498, 'quantity': '49.009', 'price': '22926.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674835202098, 'updatetime': 1674835203090, 'tradetype': 'usdt', 'selfid': 41621, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674835203090, 'clientorderid': '41621F1674835202627I0L2', 'price': '22926.6', 'quantity': '49.009', 'commission': '1123.6097394', 'commissionasset': 'USDT', 'tradetime': 1674835203090, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674835203090}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-28 00:00:03,303:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41621F1674835202627I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674835203090498, 'quantity': '49.009', 'price': '22926.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674835202098, 'updatetime': 1674835203090, 'tradetype': 'usdt', 'selfid': 41621, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674835203090, 'clientorderid': '41621F1674835202627I0L2', 'price': '22926.6', 'quantity': '49.009', 'commission': '1123.6097394', 'commissionasset': 'USDT', 'tradetime': 1674835203090, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674835203090}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9129 

self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22928.8', self.close='22991.3'
2023-01-28 00:10:01,811:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22928.8', self.close='22991.3'
2023-01-28 00:10:01,817:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230127   232000    232959  1674833399  23050.2  23079.7
12237  20230127   233000    233959  1674833999    23077  23075.9
12238  20230127   234000    234959  1674834599    23076    23002
12239  20230127   235000    235959  1674835199    23002  22942.4
12240  20230128   000000    000959  1674835799  22928.8  22991.3
2023-01-28 00:10:01,817:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13688
self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22984.4, self.close=22991.3, self.high=23006.6, self.low=22955.0, self.vol=1783.643, self.amt=41001153.3774 
127.0.0.1 - - [28/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-28 00:10:01,764:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230127   234500    234959  ...         0.0        0.0       0
5758  20230127   235000    235459  ...         0.0        0.0       0
5759  20230127   235500    235959  ...         0.0        0.0       0
5760  20230128   000000    000459  ...         0.0        0.0       0
5761  20230128   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 00:10:01,764:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674835799, self.tradeDate='20230128', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22984.4, self.close=22991.3, self.high=23006.6, self.low=22955.0, self.vol=1783.643, self.amt=41001153.3774, ukdf['pct'].iloc[-1]=0.000274 , ukdf['amount'].iloc[-1]=41001153.3774, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [28/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13689
self.closeSec=1674836099, self.tradeDate='20230128', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22990.9, self.close=22983.7, self.high=23000.8, self.low=22974.5, self.vol=996.336, self.amt=22904659.7135 
2023-01-28 00:15:00,909:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230127   235000    235459  ...         0.0        0.0       0
5759  20230127   235500    235959  ...         0.0        0.0       0
5760  20230128   000000    000459  ...         0.0        0.0       0
5761  20230128   000500    000959  ...         0.0        0.0       0
5762  20230128   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 00:15:00,909:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674836099, self.tradeDate='20230128', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22990.9, self.close=22983.7, self.high=23000.8, self.low=22974.5, self.vol=996.336, self.amt=22904659.7135, ukdf['pct'].iloc[-1]=-0.000331 , ukdf['amount'].iloc[-1]=22904659.7135, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230127   120000    155959  1674806399  ...    723  0.157918 -1.190554    -1.0
724  20230127   160000    195959  1674820799  ...    724  0.130983 -1.222563    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-1473.3514', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=380
self.closeSec=1674835199, self.tradeDate='20230127', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22964.4, self.close=22942.4, self.high=23145.3, self.low=22830.0, self.vol=120970.159, self.amt=2779083822.53631 
127.0.0.1 - - [28/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-28 00:00:01,751:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674835199, self.tradeDate='20230127', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22964.4, self.close=22942.4, self.high=23145.3, self.low=22830.0, self.vol=120970.159, self.amt=2779083822.53631 
2023-01-28 00:00:01,764:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230127   040000    075959  ...   42267.061  9.743714e+08 -0.002667
722  20230127   080000    115959  ...   86055.897  1.959346e+09 -0.010421
723  20230127   120000    155959  ...   58836.674  1.350516e+09  0.013439
724  20230127   160000    195959  ...   38844.896  8.918868e+08 -0.004491
725  20230127   200000    235959  ...  120970.159  2.779084e+09 -0.000962

[5 rows x 11 columns]
2023-01-28 00:00:03,261:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230127   040000    075959  1674777599  ...    721  0.194076 -1.155881    -1.0
722  20230127   080000    115959  1674791999  ...    722  0.160359 -1.210508    -1.0
723  20230127   120000    155959  1674806399  ...    723  0.157918 -1.190554    -1.0
724  20230127   160000    195959  1674820799  ...    724  0.130983 -1.222563    -1.0
725  20230127   200000    235959  1674835199  ...    725  0.129665 -1.199676    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-185.62046954714', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22932.14727753', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


