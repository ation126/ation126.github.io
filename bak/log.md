# 20221221 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [21/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6746
self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16909.2, self.close=16882.8, self.high=16910.6, self.low=16880.3, self.vol=4028.936, self.amt=68055408.1268 
2022-12-21 00:10:01,501:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221220   234500    234959  ...         0.0        0.0       0
5758  20221220   235000    235459  ...         0.0        0.0       0
5759  20221220   235500    235959  ...         0.0        0.0       0
5760  20221221   000000    000459  ...         0.0        0.0       0
5761  20221221   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 00:10:01,501:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16909.2, self.close=16882.8, self.high=16910.6, self.low=16880.3, self.vol=4028.936, self.amt=68055408.1268, ukdf['pct'].iloc[-1]=-0.001555 , ukdf['amount'].iloc[-1]=68055408.1268, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-21274.43577048272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16882.83688797', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6747
self.closeSec=1671552899, self.tradeDate='20221221', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16882.9, self.close=16874.3, self.high=16889.9, self.low=16870.4, self.vol=2916.862, self.amt=49233360.8497 
127.0.0.1 - - [21/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-21 00:15:00,648:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221220   235000    235459  ...         0.0        0.0       0
5759  20221220   235500    235959  ...         0.0        0.0       0
5760  20221221   000000    000459  ...         0.0        0.0       0
5761  20221221   000500    000959  ...         0.0        0.0       0
5762  20221221   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 00:15:00,649:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671552899, self.tradeDate='20221221', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16882.9, self.close=16874.3, self.high=16889.9, self.low=16870.4, self.vol=2916.862, self.amt=49233360.8497, ukdf['pct'].iloc[-1]=-0.000503 , ukdf['amount'].iloc[-1]=49233360.8497, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-20676.4736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16872.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.37127469089774645, self.count=7312 

self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16909.2, self.close=16882.8, self.high=16910.6, self.low=16880.3 
2022-12-21 00:10:01,432:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16909.2, self.close=16882.8, self.high=16910.6, self.low=16880.3   
2022-12-21 00:10:01,464:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221220   234500    234959  1671551399  ...  16916.7 -0.001711   1725    3
1438  20221220   235000    235459  1671551699  ...  16919.0  0.000821   1726    4
1439  20221220   235500    235959  1671551999  ...  16910.0 -0.001600   1727    5
1440  20221221   000000    000459  1671552299  ...  16901.0 -0.000142   1440    0
1441  20221221   000500    000959  1671552599  ...  16880.3 -0.001555   1441    1

[5 rows x 11 columns]
2022-12-21 00:10:01,465:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [21/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.37127469089774645, self.count=7313 

self.closeSec=1671552899, self.tradeDate='20221221', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16882.9, self.close=16874.3, self.high=16889.9, self.low=16870.4 
2022-12-21 00:15:00,527:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671552899, self.tradeDate='20221221', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16882.9, self.close=16874.3, self.high=16889.9, self.low=16870.4   
2022-12-21 00:15:00,567:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221220   235000    235459  1671551699  ...  16919.0  0.000821   1726    4
1439  20221220   235500    235959  1671551999  ...  16910.0 -0.001600   1727    5
1440  20221221   000000    000459  1671552299  ...  16901.0 -0.000142   1440    0
1441  20221221   000500    000959  1671552599  ...  16880.3 -0.001555   1441    1
1442  20221221   001000    001459  1671552899  ...  16870.4 -0.000503   1442    2

[5 rows x 11 columns]
2022-12-21 00:15:00,567:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-21 00:00:22,035:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221220    212959  16809.5  ...  47.916667  0.535762  0.242678
5803  20221220    215959  16802.6  ...  47.916667  0.528318  0.235860
5804  20221220    222959  16786.0  ...  47.916667  0.530697  0.228910
5805  20221220    225959  16792.0  ...  48.333333  0.568425  0.221933
5806  20221220    232959  16893.6  ...  48.750000  0.593767  0.212571

[5 rows x 33 columns]
0.5643382352941176
acc is : 0.5643382352941176
2022-12-21 00:00:22,165:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.503451  0.496549       0  ...  1.097013   1.0    0.0  0.975726
540     1  0.497503  0.502497       1  ...  1.097399   1.0    0.0  0.976069
541     0  0.503727  0.496273       1  ...  1.103947   1.0    0.0  0.981893
542     0  0.536960  0.463040       1  ...  1.108927   1.0    0.0  0.986323
543     0  0.538095  0.461905       0  ...  1.105208   1.0    0.0  0.983015

[5 rows x 10 columns]
2022-12-21 00:00:22,197:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503820  0.496180       0  ...  1.097013   1.0    0.0  0.976509
46     1  0.496435  0.503565       1  ...  1.097399   1.0    0.0  0.975825
47     0  0.503737  0.496263       1  ...  1.103947   1.0    0.0  0.981648
48     0  0.536668  0.463332       1  ...  1.108927   1.0    0.0  0.985160
49     0  0.538095  0.461905       0  ...  1.105208   1.0    0.0  0.983015

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '9133.53730219392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16916.26526764', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-21 00:00:01,194:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221220   231000    231959  1671549599  16927.8    16958  0.001778
572  20221220   232000    232959  1671550199    16958  16966.4  0.000495
573  20221220   233000    233959  1671550799  16968.4  16976.3  0.000584
574  20221220   234000    234959  1671551399  16976.2  16924.7 -0.003040
575  20221220   235000    235959  1671551999  16924.1  16911.5 -0.000780
2022-12-21 00:00:01,194:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.47', 'enterprice': '16690.4', 'countrevence': '0', 'unrealprofit': '-12691.2604234843', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16911.23278969', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-21 00:00:01,938:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-21 00:00:01,939:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 57.47, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41396F1671552001937I0L59'}
2022-12-21 00:00:01,976:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12210000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221220, closeTime:235959, close:16911.5, total:958238.090712, mom:-0.005819264211608499, thd:0.0, side:buy 
127.0.0.1 - - [21/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-21 00:00:02,285:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41396F1671552001937I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671552002043181, 'quantity': '57.47', 'price': '16910.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671552001459, 'updatetime': 1671552002043, 'tradetype': 'usdt', 'selfid': 41396, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671552002043, 'clientorderid': '41396F1671552001937I0L59', 'price': '16910.9', 'quantity': '57.47', 'commission': '971.869423', 'commissionasset': 'USDT', 'tradetime': 1671552002043, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671552002043}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-21 00:00:02,566:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41396F1671552001937I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671552002043181, 'quantity': '57.47', 'price': '16910.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671552001459, 'updatetime': 1671552002043, 'tradetype': 'usdt', 'selfid': 41396, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671552002043, 'clientorderid': '41396F1671552001937I0L59', 'price': '16910.9', 'quantity': '57.47', 'commission': '971.869423', 'commissionasset': 'USDT', 'tradetime': 1671552002043, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671552002043}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [21/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3656 

self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16910.8', self.close='16882.8'
2022-12-21 00:10:01,516:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16910.8', self.close='16882.8'
2022-12-21 00:10:01,538:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221220   232000    232959  1671550199    16958  16966.4  0.000495
573  20221220   233000    233959  1671550799  16968.4  16976.3  0.000584
574  20221220   234000    234959  1671551399  16976.2  16924.7 -0.003040
575  20221220   235000    235959  1671551999  16924.1  16911.5 -0.000780
576  20221221   000000    000959  1671552599  16910.8  16882.8 -0.001697
2022-12-21 00:10:01,544:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-21 00:00:01,196:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221220   231000    231959  1671549599  16927.8    16958
17420  20221220   232000    232959  1671550199    16958  16966.4
17421  20221220   233000    233959  1671550799  16968.4  16976.3
17422  20221220   234000    234959  1671551399  16976.2  16924.7
17423  20221220   235000    235959  1671551999  16924.1  16911.5
2022-12-21 00:00:01,197:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.973', 'enterprice': '16806.7', 'countrevence': '0', 'unrealprofit': '5851.01383731837', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16911.23278969', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-21 00:00:01,921:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-21 00:00:01,922:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.973, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41395F1671552001918I0L57'}
2022-12-21 00:00:01,955:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12210000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221220, closeTime:235959, close:16911.5, total:939780.6976809001, pct_pre:0.008350880981948139, thd:0.020026839268821983, side:sell 
127.0.0.1 - - [21/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-21 00:00:02,598:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41395F1671552001918I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671552002022742, 'quantity': '55.973', 'price': '16910.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671552001407, 'updatetime': 1671552002022, 'tradetype': 'usdt', 'selfid': 41395, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671552002022, 'clientorderid': '41395F1671552001918I0L57', 'price': '16910.8', 'quantity': '55.973', 'commission': '946.5482084', 'commissionasset': 'USDT', 'tradetime': 1671552002022, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671552002022}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-21 00:00:02,794:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41395F1671552001918I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671552002022742, 'quantity': '55.973', 'price': '16910.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671552001407, 'updatetime': 1671552002022, 'tradetype': 'usdt', 'selfid': 41395, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671552002022, 'clientorderid': '41395F1671552001918I0L57', 'price': '16910.8', 'quantity': '55.973', 'commission': '946.5482084', 'commissionasset': 'USDT', 'tradetime': 1671552002022, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671552002022}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3657 

self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16910.8', self.close='16882.8'
2022-12-21 00:10:01,531:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16910.8', self.close='16882.8'
127.0.0.1 - - [21/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-21 00:10:01,570:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221220   232000    232959  1671550199    16958  16966.4
17421  20221220   233000    233959  1671550799  16968.4  16976.3
17422  20221220   234000    234959  1671551399  16976.2  16924.7
17423  20221220   235000    235959  1671551999  16924.1  16911.5
17424  20221221   000000    000959  1671552599  16910.8  16882.8
2022-12-21 00:10:01,571:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-21 00:00:01,194:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221220   231000    231959  1671549599  16927.8    16958
12236  20221220   232000    232959  1671550199    16958  16966.4
12237  20221220   233000    233959  1671550799  16968.4  16976.3
12238  20221220   234000    234959  1671551399  16976.2  16924.7
12239  20221220   235000    235959  1671551999  16924.1  16911.5
2022-12-21 00:00:01,194:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.223', 'enterprice': '16405.4', 'countrevence': '0', 'unrealprofit': '38050.25993885087', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16911.23278969', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-21 00:00:01,892:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-21 00:00:01,892:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.223, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41394F1671552001891I0L2'}
2022-12-21 00:00:01,929:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12210000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221220, closeTime:235959, close:16911.5, total:1232829.3407958, corrDate:20221127, corrVal:0.8494551365384617, side:sell 
127.0.0.1 - - [21/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-21 00:00:02,082:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41394F1671552001891I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671552001999943, 'quantity': '75.223', 'price': '16910.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671552001368, 'updatetime': 1671552001999, 'tradetype': 'usdt', 'selfid': 41394, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671552001999, 'clientorderid': '41394F1671552001891I0L2', 'price': '16910.8', 'quantity': '75.223', 'commission': '1272.0811084', 'commissionasset': 'USDT', 'tradetime': 1671552001999, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671552001999}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-21 00:00:02,300:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41394F1671552001891I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671552001999943, 'quantity': '75.223', 'price': '16910.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671552001368, 'updatetime': 1671552001999, 'tradetype': 'usdt', 'selfid': 41394, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671552001999, 'clientorderid': '41394F1671552001891I0L2', 'price': '16910.8', 'quantity': '75.223', 'commission': '1272.0811084', 'commissionasset': 'USDT', 'tradetime': 1671552001999, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671552001999}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3657 

self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16910.8', self.close='16882.8'
2022-12-21 00:10:01,521:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16910.8', self.close='16882.8'
127.0.0.1 - - [21/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-21 00:10:01,557:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221220   232000    232959  1671550199    16958  16966.4
12237  20221220   233000    233959  1671550799  16968.4  16976.3
12238  20221220   234000    234959  1671551399  16976.2  16924.7
12239  20221220   235000    235959  1671551999  16924.1  16911.5
12240  20221221   000000    000959  1671552599  16910.8  16882.8
2022-12-21 00:10:01,557:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [21/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2744
self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16909.2, self.close=16882.8, self.high=16910.6, self.low=16880.3, self.vol=4028.936, self.amt=68055408.1268 
2022-12-21 00:10:01,479:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221220   234500    234959  ...         0.0        0.0       0
5758  20221220   235000    235459  ...         0.0        0.0       0
5759  20221220   235500    235959  ...         0.0        0.0       0
5760  20221221   000000    000459  ...         0.0        0.0       0
5761  20221221   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 00:10:01,479:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671552599, self.tradeDate='20221221', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16909.2, self.close=16882.8, self.high=16910.6, self.low=16880.3, self.vol=4028.936, self.amt=68055408.1268, ukdf['pct'].iloc[-1]=-0.001555 , ukdf['amount'].iloc[-1]=68055408.1268, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2745
self.closeSec=1671552899, self.tradeDate='20221221', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16882.9, self.close=16874.3, self.high=16889.9, self.low=16870.4, self.vol=2916.862, self.amt=49233360.8497 
127.0.0.1 - - [21/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-21 00:15:00,619:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221220   235000    235459  ...         0.0        0.0       0
5759  20221220   235500    235959  ...         0.0        0.0       0
5760  20221221   000000    000459  ...         0.0        0.0       0
5761  20221221   000500    000959  ...         0.0        0.0       0
5762  20221221   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 00:15:00,620:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671552899, self.tradeDate='20221221', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16882.9, self.close=16874.3, self.high=16889.9, self.low=16870.4, self.vol=2916.862, self.amt=49233360.8497, ukdf['pct'].iloc[-1]=-0.000503 , ukdf['amount'].iloc[-1]=49233360.8497, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221220   120000    155959  1671523199  ...    723  0.424051 -1.325928    -1.0
724  20221220   160000    195959  1671537599  ...    724  0.159883 -2.232762    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-4600.6664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16809.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [21/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=152
self.closeSec=1671551999, self.tradeDate='20221220', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16805.2, self.close=16910.9, self.high=17049.6, self.low=16684.0, self.vol=131483.196, self.amt=2220089706.97463 
2022-12-21 00:00:01,031:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671551999, self.tradeDate='20221220', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16805.2, self.close=16910.9, self.high=17049.6, self.low=16684.0, self.vol=131483.196, self.amt=2220089706.97463 
2022-12-21 00:00:01,071:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20221220   040000    075959  ...   87890.393  1.445146e+09 -0.007257
722  20221220   080000    115959  ...  109994.556  1.829875e+09  0.017578
723  20221220   120000    155959  ...   69915.337  1.173493e+09  0.004672
724  20221220   160000    195959  ...   47552.517  7.989043e+08  0.000536
725  20221220   200000    235959  ...  131483.196  2.220090e+09  0.006296

[5 rows x 11 columns]
2022-12-21 00:00:02,732:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221220   040000    075959  1671494399  ...    721  0.677568 -0.376910     NaN
722  20221220   080000    115959  1671508799  ...    722  0.483746 -1.110773    -1.0
723  20221220   120000    155959  1671523199  ...    723  0.424051 -1.325928    -1.0
724  20221220   160000    195959  1671537599  ...    724  0.159883 -2.232762    -1.0
725  20221220   200000    235959  1671551999  ...    725  0.026394 -2.594419    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-10041.02325133468', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16911.23278969', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


