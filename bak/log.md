# 20221228 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [28/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8762
self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16793.9, self.close=16783.0, self.high=16794.3, self.low=16783.0, self.vol=658.708, self.amt=11059114.1665 
2022-12-28 00:10:01,493:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221227   234500    234959  ...         0.0        0.0       0
5758  20221227   235000    235459  ...         0.0        0.0       0
5759  20221227   235500    235959  ...         0.0        0.0       0
5760  20221228   000000    000459  ...         0.0        0.0       0
5761  20221228   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 00:10:01,493:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16793.9, self.close=16783.0, self.high=16794.3, self.low=16783.0, self.vol=658.708, self.amt=11059114.1665, ukdf['pct'].iloc[-1]=-0.000655 , ukdf['amount'].iloc[-1]=11059114.1665, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15398.13535561728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16785.18499328', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8763
self.closeSec=1672157699, self.tradeDate='20221228', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16783.1, self.close=16772.7, self.high=16783.1, self.low=16772.0, self.vol=1069.607, self.amt=17944826.605 
127.0.0.1 - - [28/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-28 00:15:00,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221227   235000    235459  ...         0.0        0.0       0
5759  20221227   235500    235959  ...         0.0        0.0       0
5760  20221228   000000    000459  ...         0.0        0.0       0
5761  20221228   000500    000959  ...         0.0        0.0       0
5762  20221228   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 00:15:00,577:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672157699, self.tradeDate='20221228', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16783.1, self.close=16772.7, self.high=16783.1, self.low=16772.0, self.vol=1069.607, self.amt=17944826.605, ukdf['pct'].iloc[-1]=-0.000614 , ukdf['amount'].iloc[-1]=17944826.605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-14652.856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16772.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=310, self.factor=0.5701652687925507, self.count=9328 

self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16793.9, self.close=16783.0, self.high=16794.3, self.low=16783.0 
2022-12-28 00:10:01,423:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16793.9, self.close=16783.0, self.high=16794.3, self.low=16783.0   
2022-12-28 00:10:01,464:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221227   234500    234959  1672156199  ...  16803.4  0.000113   1725    3
1438  20221227   235000    235459  1672156499  ...  16791.3 -0.000768   1726    4
1439  20221227   235500    235959  1672156799  ...  16781.3 -0.000167   1727    5
1440  20221228   000000    000459  1672157099  ...  16782.9  0.000197   1440    0
1441  20221228   000500    000959  1672157399  ...  16783.0 -0.000655   1441    1

[5 rows x 11 columns]
2022-12-28 00:10:01,466:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=310, self.factor=0.5701652687925507, self.count=9329 

self.closeSec=1672157699, self.tradeDate='20221228', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16783.1, self.close=16772.7, self.high=16783.1, self.low=16772.0 
2022-12-28 00:15:00,521:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672157699, self.tradeDate='20221228', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16783.1, self.close=16772.7, self.high=16783.1, self.low=16772.0   
2022-12-28 00:15:00,635:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221227   235000    235459  1672156499  ...  16791.3 -0.000768   1726    4
1439  20221227   235500    235959  1672156799  ...  16781.3 -0.000167   1727    5
1440  20221228   000000    000459  1672157099  ...  16782.9  0.000197   1440    0
1441  20221228   000500    000959  1672157399  ...  16783.0 -0.000655   1441    1
1442  20221228   001000    001459  1672157699  ...  16772.0 -0.000614   1442    2

[5 rows x 11 columns]
2022-12-28 00:15:00,635:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-28 00:00:18,577:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221227    212959  16803.1  ...  46.666667  0.486409  0.638244
5803  20221227    215959  16824.5  ...  46.666667  0.475007  0.654492
5804  20221227    222959  16811.1  ...  46.666667  0.472373  0.670818
5805  20221227    225959  16808.1  ...  46.666667  0.437482  0.681570
5806  20221227    232959  16764.2  ...  46.666667  0.486058  0.676682

[5 rows x 33 columns]
0.5165441176470589
acc is : 0.5165441176470589
2022-12-28 00:00:18,663:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.498482  0.501518       0  ...  1.032188   1.0    0.0  0.960821
540     1  0.493340  0.506660       0  ...  1.031997   1.0    0.0  0.960644
541     1  0.494641  0.505359       0  ...  1.029314   1.0    0.0  0.958146
542     1  0.482262  0.517738       1  ...  1.032679   1.0    0.0  0.961278
543     0  0.509356  0.490644       0  ...  1.030935   1.0    0.0  0.959655

[5 rows x 10 columns]
2022-12-28 00:00:18,673:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499078  0.500922       0  ...  1.032188   1.0    0.0  0.967156
46     1  0.493236  0.506764       0  ...  1.031997   1.0    0.0  0.965139
47     1  0.495013  0.504987       0  ...  1.029314   1.0    0.0  0.962630
48     1  0.482392  0.517608       1  ...  1.032679   1.0    0.0  0.962736
49     0  0.509356  0.490644       0  ...  1.030935   1.0    0.0  0.959655

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '3804.41127740352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16790.95662334', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-28 00:00:01,397:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221227   231000    231959  1672154399  16769.9  16807.1  0.002218
572  20221227   232000    232959  1672154999    16807  16819.1  0.000714
573  20221227   233000    233959  1672155599  16819.2  16802.8 -0.000969
574  20221227   234000    234959  1672156199  16802.7  16806.4  0.000214
575  20221227   235000    235959  1672156799  16806.4  16790.7 -0.000934
2022-12-28 00:00:01,400:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.744', 'enterprice': '16870.1', 'countrevence': '0', 'unrealprofit': '-4324.19347402296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16791.11064091', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-28 00:00:02,296:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-28 00:00:02,297:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.744, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41427F1672156802295I0L59'}
2022-12-28 00:00:02,356:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12280000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221227, closeTime:235959, close:16790.7, total:922613.2176455999, mom:0.0006229299248352582, thd:0.0, side:sell 
127.0.0.1 - - [28/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-28 00:00:02,700:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41427F1672156802295I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672156802659900, 'quantity': '54.744', 'price': '16790.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672156801725, 'updatetime': 1672156802659, 'tradetype': 'usdt', 'selfid': 41427, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672156802659, 'clientorderid': '41427F1672156802295I0L59', 'price': '16790.7', 'quantity': '54.744', 'commission': '919.1900808', 'commissionasset': 'USDT', 'tradetime': 1672156802659, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672156802659}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-28 00:00:02,893:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41427F1672156802295I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672156802659900, 'quantity': '54.744', 'price': '16790.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672156801725, 'updatetime': 1672156802659, 'tradetype': 'usdt', 'selfid': 41427, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672156802659, 'clientorderid': '41427F1672156802295I0L59', 'price': '16790.7', 'quantity': '54.744', 'commission': '919.1900808', 'commissionasset': 'USDT', 'tradetime': 1672156802659, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672156802659}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4664 

self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16790.7', self.close='16783'
2022-12-28 00:10:01,513:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16790.7', self.close='16783'
127.0.0.1 - - [28/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-28 00:10:01,523:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221227   232000    232959  1672154999    16807  16819.1  0.000714
573  20221227   233000    233959  1672155599  16819.2  16802.8 -0.000969
574  20221227   234000    234959  1672156199  16802.7  16806.4  0.000214
575  20221227   235000    235959  1672156799  16806.4  16790.7 -0.000934
576  20221228   000000    000959  1672157399  16790.7    16783 -0.000459
2022-12-28 00:10:01,524:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-27 23:50:00,629:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4664 

self.closeSec=1672156799, self.tradeDate='20221227', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16806.4', self.close='16790.7'
2022-12-28 00:00:01,345:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672156799, self.tradeDate='20221227', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16806.4', self.close='16790.7'
2022-12-28 00:00:01,415:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221227   231000    231959  1672154399  16769.9  16807.1
17420  20221227   232000    232959  1672154999    16807  16819.1
17421  20221227   233000    233959  1672155599  16819.2  16802.8
17422  20221227   234000    234959  1672156199  16802.7  16806.4
17423  20221227   235000    235959  1672156799  16806.4  16790.7
2022-12-28 00:00:01,419:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-28 00:00:01,547:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12280000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221227, closeTime:235959, close:16790.7, total:943443.8042161, pct_pre:0.0036768424371871333, thd:-0.0017346436012878885, side:sell 
127.0.0.1 - - [28/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4665 

self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16790.7', self.close='16783'
2022-12-28 00:10:01,531:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16790.7', self.close='16783'
2022-12-28 00:10:01,538:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221227   232000    232959  1672154999    16807  16819.1
17421  20221227   233000    233959  1672155599  16819.2  16802.8
17422  20221227   234000    234959  1672156199  16802.7  16806.4
17423  20221227   235000    235959  1672156799  16806.4  16790.7
17424  20221228   000000    000959  1672157399  16790.7    16783
2022-12-28 00:10:01,538:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-28 00:00:01,348:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221227   231000    231959  1672154399  16769.9  16807.1
12236  20221227   232000    232959  1672154999    16807  16819.1
12237  20221227   233000    233959  1672155599  16819.2  16802.8
12238  20221227   234000    234959  1672156199  16802.7  16806.4
12239  20221227   235000    235959  1672156799  16806.4  16790.7
2022-12-28 00:00:01,348:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.074', 'enterprice': '16833.1', 'countrevence': '0', 'unrealprofit': '-3152.30914432266', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16791.11064091', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-28 00:00:02,005:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-28 00:00:02,005:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.074, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41426F1672156802004I0L2'}
2022-12-28 00:00:02,039:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12280000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221227, closeTime:235959, close:16790.7, total:1262464.4212505997, corrDate:20221017, corrVal:0.6110313948378822, side:sell 
127.0.0.1 - - [28/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-28 00:00:02,394:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41426F1672156802004I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672156802331056, 'quantity': '75.074', 'price': '16790.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672156801606, 'updatetime': 1672156802331, 'tradetype': 'usdt', 'selfid': 41426, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672156802331, 'clientorderid': '41426F1672156802004I0L2', 'price': '16790.7', 'quantity': '75.074', 'commission': '1260.5450118', 'commissionasset': 'USDT', 'tradetime': 1672156802331, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672156802331}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-28 00:00:02,586:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41426F1672156802004I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672156802331056, 'quantity': '75.074', 'price': '16790.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672156801606, 'updatetime': 1672156802331, 'tradetype': 'usdt', 'selfid': 41426, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672156802331, 'clientorderid': '41426F1672156802004I0L2', 'price': '16790.7', 'quantity': '75.074', 'commission': '1260.5450118', 'commissionasset': 'USDT', 'tradetime': 1672156802331, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672156802331}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4665 

self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16790.7', self.close='16783'
2022-12-28 00:10:01,535:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16790.7', self.close='16783'
2022-12-28 00:10:01,549:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221227   232000    232959  1672154999    16807  16819.1
12237  20221227   233000    233959  1672155599  16819.2  16802.8
12238  20221227   234000    234959  1672156199  16802.7  16806.4
12239  20221227   235000    235959  1672156799  16806.4  16790.7
12240  20221228   000000    000959  1672157399  16790.7    16783
2022-12-28 00:10:01,556:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4760
self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16793.9, self.close=16783.0, self.high=16794.3, self.low=16783.0, self.vol=658.708, self.amt=11059114.1665 
127.0.0.1 - - [28/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-28 00:10:01,480:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221227   234500    234959  ...         0.0        0.0       0
5758  20221227   235000    235459  ...         0.0        0.0       0
5759  20221227   235500    235959  ...         0.0        0.0       0
5760  20221228   000000    000459  ...         0.0        0.0       0
5761  20221228   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 00:10:01,480:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672157399, self.tradeDate='20221228', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16793.9, self.close=16783.0, self.high=16794.3, self.low=16783.0, self.vol=658.708, self.amt=11059114.1665, ukdf['pct'].iloc[-1]=-0.000655 , ukdf['amount'].iloc[-1]=11059114.1665, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4761
self.closeSec=1672157699, self.tradeDate='20221228', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16783.1, self.close=16772.7, self.high=16783.1, self.low=16772.0, self.vol=1069.607, self.amt=17944826.605 
127.0.0.1 - - [28/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-28 00:15:00,647:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221227   235000    235459  ...         0.0        0.0       0
5759  20221227   235500    235959  ...         0.0        0.0       0
5760  20221228   000000    000459  ...         0.0        0.0       0
5761  20221228   000500    000959  ...         0.0        0.0       0
5762  20221228   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 00:15:00,647:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672157699, self.tradeDate='20221228', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16783.1, self.close=16772.7, self.high=16783.1, self.low=16772.0, self.vol=1069.607, self.amt=17944826.605, ukdf['pct'].iloc[-1]=-0.000614 , ukdf['amount'].iloc[-1]=17944826.605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221227   120000    155959  ...  1.904855e-04 -0.986887    -1.0
724  20221227   160000    195959  ...  2.415497e-04 -0.975139    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5366.00057835864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16823.63961962', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=194
self.closeSec=1672156799, self.tradeDate='20221227', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16823.6, self.close=16790.7, self.high=16833.4, self.low=16723.2, self.vol=66673.069, self.amt=1119302009.5306 
2022-12-28 00:00:01,200:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672156799, self.tradeDate='20221227', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16823.6, self.close=16790.7, self.high=16833.4, self.low=16723.2, self.vol=66673.069, self.amt=1119302009.5306 
127.0.0.1 - - [28/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-28 00:00:01,267:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221227   040000    075959  ...  26899.477  4.537431e+08  0.004526
722  20221227   080000    115959  ...  42682.907  7.210720e+08 -0.002543
723  20221227   120000    155959  ...  15232.900  2.569441e+08 -0.000504
724  20221227   160000    195959  ...  30792.583  5.184878e+08 -0.002135
725  20221227   200000    235959  ...  66673.069  1.119302e+09 -0.001956

[5 rows x 11 columns]
2022-12-28 00:00:03,127:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime  ...          beta    zscore  signal
721  20221227   040000    075959  ...  5.692034e-09 -1.016754    -1.0
722  20221227   080000    115959  ...  2.235041e-05 -1.001465    -1.0
723  20221227   120000    155959  ...  1.904855e-04 -0.986887    -1.0
724  20221227   160000    195959  ...  2.415497e-04 -0.975139    -1.0
725  20221227   200000    235959  ...  6.249903e-04 -0.966176    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-3620.95843217592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16790.94378386', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


