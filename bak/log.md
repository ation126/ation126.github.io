# 20230103 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [03/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10490
self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16721.4, self.close=16714.9, self.high=16721.4, self.low=16713.1, self.vol=667.661, self.amt=11160798.644 
2023-01-03 00:10:01,615:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230102   234500    234959  ...         0.0        0.0       0
5758  20230102   235000    235459  ...         0.0        0.0       0
5759  20230102   235500    235959  ...         0.0        0.0       0
5760  20230103   000000    000459  ...         0.0        0.0       0
5761  20230103   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 00:10:01,616:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16721.4, self.close=16714.9, self.high=16721.4, self.low=16713.1, self.vol=667.661, self.amt=11160798.644, ukdf['pct'].iloc[-1]=-0.000389 , ukdf['amount'].iloc[-1]=11160798.644, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-11171.17329820048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16714.94167273', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10491
self.closeSec=1672676099, self.tradeDate='20230103', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16714.9, self.close=16728.6, self.high=16730.0, self.low=16714.8, self.vol=973.16, self.amt=16273730.4385 
127.0.0.1 - - [03/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-03 00:15:00,630:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230102   235000    235459  ...         0.0        0.0       0
5759  20230102   235500    235959  ...         0.0        0.0       0
5760  20230103   000000    000459  ...         0.0        0.0       0
5761  20230103   000500    000959  ...         0.0        0.0       0
5762  20230103   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 00:15:00,631:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672676099, self.tradeDate='20230103', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16714.9, self.close=16728.6, self.high=16730.0, self.low=16714.8, self.vol=973.16, self.amt=16273730.4385, ukdf['pct'].iloc[-1]=0.00082 , ukdf['amount'].iloc[-1]=16273730.4385, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-11993.0768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16728.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16721.4, self.close=16714.9, self.high=16721.4, self.low=16713.1 
2023-01-03 00:10:01,426:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16721.4, self.close=16714.9, self.high=16721.4, self.low=16713.1   
127.0.0.1 - - [03/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-03 00:10:01,497:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230102   234500    234959  1672674599  ...  16728.5 -0.000143   1725    3
1438  20230102   235000    235459  1672674899  ...  16717.9 -0.000329   1726    4
1439  20230102   235500    235959  1672675199  ...  16723.5 -0.000018   1727    5
1440  20230103   000000    000459  1672675499  ...  16720.3 -0.000466   1440    0
1441  20230103   000500    000959  1672675799  ...  16713.1 -0.000389   1441    1

[5 rows x 11 columns]
2023-01-03 00:10:01,498:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=6, self.factor=0.30748224970708954, self.count=11057 

self.closeSec=1672676099, self.tradeDate='20230103', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16714.9, self.close=16728.6, self.high=16730.0, self.low=16714.8 
2023-01-03 00:15:00,547:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672676099, self.tradeDate='20230103', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16714.9, self.close=16728.6, self.high=16730.0, self.low=16714.8   
2023-01-03 00:15:00,622:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230102   235000    235459  1672674899  ...  16717.9 -0.000329   1726    4
1439  20230102   235500    235959  1672675199  ...  16723.5 -0.000018   1727    5
1440  20230103   000000    000459  1672675499  ...  16720.3 -0.000466   1440    0
1441  20230103   000500    000959  1672675799  ...  16713.1 -0.000389   1441    1
1442  20230103   001000    001459  1672676099  ...  16714.8  0.000820   1442    2

[5 rows x 11 columns]
2023-01-03 00:15:00,623:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-03 00:00:19,081:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230102    212959  16713.2  ...  49.166667  0.582216  0.249463
5803  20230102    215959  16710.8  ...  49.166667  0.561742  0.256369
5804  20230102    222959  16687.7  ...  48.750000  0.558085  0.264050
5805  20230102    225959  16683.6  ...  48.750000  0.565777  0.267923
5806  20230102    232959  16694.7  ...  49.166667  0.576390  0.266890

[5 rows x 33 columns]
0.5055147058823529
acc is : 0.5055147058823529
2023-01-03 00:00:19,188:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     1  0.496331  0.503669       0  ...  NaN   NaN -0.0016  0.992140
540     1  0.490620  0.509380       0  ...  NaN   NaN -0.0016  0.991891
541     1  0.491671  0.508329       1  ...  NaN   NaN -0.0016  0.992556
542     1  0.495685  0.504315       1  ...  NaN   NaN -0.0016  0.993496
543     0  0.500665  0.499335       1  ...  NaN   NaN -0.0016  0.994602

[5 rows x 10 columns]
2023-01-03 00:00:19,211:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
6      1  0.497053  0.502947       0  ...  NaN   NaN -0.0016  0.993564
7      1  0.490589  0.509411       0  ...  NaN   NaN -0.0016  0.993018
8      1  0.492156  0.507844       1  ...  NaN   NaN -0.0016  0.993685
9      1  0.495920  0.504080       1  ...  NaN   NaN -0.0016  0.994329
10     0  0.500665  0.499335       1  ...  NaN   NaN -0.0016  0.994602

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '1335.3792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16732.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-03 00:00:01,147:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230102   231000    231959  1672672799  16694.8  16707.4  0.000755
572  20230102   232000    232959  1672673399  16707.4  16710.7  0.000198
573  20230102   233000    233959  1672673999  16710.6  16722.9  0.000730
574  20230102   234000    234959  1672674599    16723  16735.1  0.000730
575  20230102   235000    235959  1672675199    16735  16729.2 -0.000353
2023-01-03 00:00:01,147:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.179', 'enterprice': '16610.5', 'countrevence': '0', 'unrealprofit': '6549.7473', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16729.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-03 00:00:01,791:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-03 00:00:01,791:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.179, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41461F1672675201789I0L59'}
2023-01-03 00:00:01,811:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1030000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230102, closeTime:235959, close:16729.2, total:915634.2287205, mom:0.0013205042007999879, thd:0.0, side:sell 
127.0.0.1 - - [03/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-03 00:00:02,176:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41461F1672675201789I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672675201903355, 'quantity': '55.179', 'price': '16729.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672675201346, 'updatetime': 1672675201903, 'tradetype': 'usdt', 'selfid': 41461, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672675201903, 'clientorderid': '41461F1672675201789I0L59', 'price': '16729.1', 'quantity': '55.179', 'commission': '923.0950089', 'commissionasset': 'USDT', 'tradetime': 1672675201903, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672675201903}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-03 00:00:02,431:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41461F1672675201789I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672675201903355, 'quantity': '55.179', 'price': '16729.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672675201346, 'updatetime': 1672675201903, 'tradetype': 'usdt', 'selfid': 41461, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672675201903, 'clientorderid': '41461F1672675201789I0L59', 'price': '16729.1', 'quantity': '55.179', 'commission': '923.0950089', 'commissionasset': 'USDT', 'tradetime': 1672675201903, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672675201903}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5528 

self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16729.2', self.close='16714.8'
2023-01-03 00:10:01,567:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16729.2', self.close='16714.8'
127.0.0.1 - - [03/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-03 00:10:01,608:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230102   232000    232959  1672673399  16707.4  16710.7  0.000198
573  20230102   233000    233959  1672673999  16710.6  16722.9  0.000730
574  20230102   234000    234959  1672674599    16723  16735.1  0.000730
575  20230102   235000    235959  1672675199    16735  16729.2 -0.000353
576  20230103   000000    000959  1672675799  16729.2  16714.8 -0.000861
2023-01-03 00:10:01,609:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-02 23:50:00,621:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5528 

self.closeSec=1672675199, self.tradeDate='20230102', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16735', self.close='16729.2'
2023-01-03 00:00:01,084:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672675199, self.tradeDate='20230102', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16735', self.close='16729.2'
127.0.0.1 - - [03/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-03 00:00:01,153:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230102   231000    231959  1672672799  16694.8  16707.4
17420  20230102   232000    232959  1672673399  16707.4  16710.7
17421  20230102   233000    233959  1672673999  16710.6  16722.9
17422  20230102   234000    234959  1672674599    16723  16735.1
17423  20230102   235000    235959  1672675199    16735  16729.2
2023-01-03 00:00:01,154:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-03 00:00:01,257:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1030000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230102, closeTime:235959, close:16729.2, total:943801.2083061, pct_pre:0.009039691309939979, thd:-0.08791464634634566, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5529 

self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16729.2', self.close='16714.8'
2023-01-03 00:10:01,563:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16729.2', self.close='16714.8'
127.0.0.1 - - [03/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-03 00:10:01,618:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230102   232000    232959  1672673399  16707.4  16710.7
17421  20230102   233000    233959  1672673999  16710.6  16722.9
17422  20230102   234000    234959  1672674599    16723  16735.1
17423  20230102   235000    235959  1672675199    16735  16729.2
17424  20230103   000000    000959  1672675799  16729.2  16714.8
2023-01-03 00:10:01,618:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-03 00:00:01,138:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230102   231000    231959  1672672799  16694.8  16707.4
12236  20230102   232000    232959  1672673399  16707.4  16710.7
12237  20230102   233000    233959  1672673999  16710.6  16722.9
12238  20230102   234000    234959  1672674599    16723  16735.1
12239  20230102   235000    235959  1672675199    16735  16729.2
2023-01-03 00:00:01,138:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '76.069', 'enterprice': '16594.4', 'countrevence': '0', 'unrealprofit': '-10254.1012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16729.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-03 00:00:01,768:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-03 00:00:01,769:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 76.069, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41460F1672675201768I0L2'}
2023-01-03 00:00:01,802:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1030000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230102, closeTime:235959, close:16729.2, total:1261057.0941864, corrDate:20221209, corrVal:0.820811404985827, side:buy 
127.0.0.1 - - [03/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-03 00:00:01,912:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41460F1672675201768I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672675201871100, 'quantity': '76.069', 'price': '16729.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672675201332, 'updatetime': 1672675201871, 'tradetype': 'usdt', 'selfid': 41460, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672675201871, 'clientorderid': '41460F1672675201768I0L2', 'price': '16729.2', 'quantity': '76.069', 'commission': '1272.5735148', 'commissionasset': 'USDT', 'tradetime': 1672675201871, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672675201871}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-03 00:00:02,159:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41460F1672675201768I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672675201871100, 'quantity': '76.069', 'price': '16729.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672675201332, 'updatetime': 1672675201871, 'tradetype': 'usdt', 'selfid': 41460, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672675201871, 'clientorderid': '41460F1672675201768I0L2', 'price': '16729.2', 'quantity': '76.069', 'commission': '1272.5735148', 'commissionasset': 'USDT', 'tradetime': 1672675201871, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672675201871}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5529 

self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16729.2', self.close='16714.8'
127.0.0.1 - - [03/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-03 00:10:01,524:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16729.2', self.close='16714.8'
2023-01-03 00:10:01,572:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230102   232000    232959  1672673399  16707.4  16710.7
12237  20230102   233000    233959  1672673999  16710.6  16722.9
12238  20230102   234000    234959  1672674599    16723  16735.1
12239  20230102   235000    235959  1672675199    16735  16729.2
12240  20230103   000000    000959  1672675799  16729.2  16714.8
2023-01-03 00:10:01,572:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [03/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6488
self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16721.4, self.close=16714.9, self.high=16721.4, self.low=16713.1, self.vol=667.661, self.amt=11160798.644 
2023-01-03 00:10:01,517:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230102   234500    234959  ...         0.0        0.0       0
5758  20230102   235000    235459  ...         0.0        0.0       0
5759  20230102   235500    235959  ...         0.0        0.0       0
5760  20230103   000000    000459  ...         0.0        0.0       0
5761  20230103   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 00:10:01,521:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672675799, self.tradeDate='20230103', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16721.4, self.close=16714.9, self.high=16721.4, self.low=16713.1, self.vol=667.661, self.amt=11160798.644, ukdf['pct'].iloc[-1]=-0.000389 , ukdf['amount'].iloc[-1]=11160798.644, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6489
self.closeSec=1672676099, self.tradeDate='20230103', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16714.9, self.close=16728.6, self.high=16730.0, self.low=16714.8, self.vol=973.16, self.amt=16273730.4385 
127.0.0.1 - - [03/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-03 00:15:00,607:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230102   235000    235459  ...         0.0        0.0       0
5759  20230102   235500    235959  ...         0.0        0.0       0
5760  20230103   000000    000459  ...         0.0        0.0       0
5761  20230103   000500    000959  ...         0.0        0.0       0
5762  20230103   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 00:15:00,607:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672676099, self.tradeDate='20230103', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16714.9, self.close=16728.6, self.high=16730.0, self.low=16714.8, self.vol=973.16, self.amt=16273730.4385, ukdf['pct'].iloc[-1]=0.00082 , ukdf['amount'].iloc[-1]=16273730.4385, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230102   120000    155959  1672646399  ...    723  0.081884 -0.510533     NaN
724  20230102   160000    195959  1672660799  ...    724  0.163524 -0.237419     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-8841.349', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16728.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [03/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891007.4496510001, self.flagDict['side']='sell', self.tradeCount=9, self.count=230
self.closeSec=1672675199, self.tradeDate='20230102', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16728.4, self.close=16729.1, self.high=16744.8, self.low=16665.0, self.vol=35861.233, self.amt=599065098.2071 
2023-01-03 00:00:00,990:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672675199, self.tradeDate='20230102', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16728.4, self.close=16729.1, self.high=16744.8, self.low=16665.0, self.vol=35861.233, self.amt=599065098.2071 
2023-01-03 00:00:01,022:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230102   040000    075959  ...  16635.812  2.761523e+08  0.000892
722  20230102   080000    115959  ...  36634.472  6.085019e+08  0.002637
723  20230102   120000    155959  ...  53334.962  8.901111e+08  0.003476
724  20230102   160000    195959  ...  37547.955  6.280194e+08  0.000951
725  20230102   200000    235959  ...  35861.233  5.990651e+08  0.000036

[5 rows x 11 columns]
2023-01-03 00:00:02,506:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230102   040000    075959  1672617599  ...    721  0.028206 -0.703374    -1.0
722  20230102   080000    115959  1672631999  ...    722  0.036558 -0.662826    -1.0
723  20230102   120000    155959  1672646399  ...    723  0.081884 -0.510533     NaN
724  20230102   160000    195959  1672660799  ...    724  0.163524 -0.237419     NaN
725  20230102   200000    235959  1672675199  ...    725  0.216347 -0.038365     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-8884.425', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16729.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


