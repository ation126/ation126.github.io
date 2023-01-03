# 20230104 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [04/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10778
self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16654.9, self.close=16663.1, self.high=16680.1, self.low=16653.8, self.vol=1580.637, self.amt=26349035.7905 
2023-01-04 00:10:01,580:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230103   234500    234959  ...         0.0        0.0       0
5758  20230103   235000    235459  ...         0.0        0.0       0
5759  20230103   235500    235959  ...         0.0        0.0       0
5760  20230104   000000    000459  ...         0.0        0.0       0
5761  20230104   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 00:10:01,585:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16654.9, self.close=16663.1, self.high=16680.1, self.low=16653.8, self.vol=1580.637, self.amt=26349035.7905, ukdf['pct'].iloc[-1]=0.000486 , ukdf['amount'].iloc[-1]=26349035.7905, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-8142.19178182864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16664.60629789', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10779
self.closeSec=1672762499, self.tradeDate='20230104', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16663.0, self.close=16642.8, self.high=16665.1, self.low=16640.0, self.vol=1147.938, self.amt=19117982.3326 
127.0.0.1 - - [04/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-04 00:15:00,692:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230103   235000    235459  ...         0.0        0.0       0
5759  20230103   235500    235959  ...         0.0        0.0       0
5760  20230104   000000    000459  ...         0.0        0.0       0
5761  20230104   000500    000959  ...         0.0        0.0       0
5762  20230104   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 00:15:00,692:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672762499, self.tradeDate='20230104', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16663.0, self.close=16642.8, self.high=16665.1, self.low=16640.0, self.vol=1147.938, self.amt=19117982.3326, ukdf['pct'].iloc[-1]=-0.001218 , ukdf['amount'].iloc[-1]=19117982.3326, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-6868.87988148512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16643.44650162', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=54, self.factor=0.47947187897948834, self.count=11344 

self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16654.9, self.close=16663.1, self.high=16680.1, self.low=16653.8 
2023-01-04 00:10:01,431:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16654.9, self.close=16663.1, self.high=16680.1, self.low=16653.8   
2023-01-04 00:10:01,462:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230103   234500    234959  1672760999  ...  16642.7  0.000451   1725    3
1438  20230103   235000    235459  1672761299  ...  16643.7 -0.000078   1726    4
1439  20230103   235500    235959  1672761599  ...  16647.1  0.001123   1727    5
1440  20230104   000000    000459  1672761899  ...  16650.9 -0.000948   1440    0
1441  20230104   000500    000959  1672762199  ...  16653.8  0.000486   1441    1

[5 rows x 11 columns]
2023-01-04 00:10:01,462:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=54, self.factor=0.47947187897948834, self.count=11345 

self.closeSec=1672762499, self.tradeDate='20230104', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16663.0, self.close=16642.8, self.high=16665.1, self.low=16640.0 
2023-01-04 00:15:00,526:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672762499, self.tradeDate='20230104', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16663.0, self.close=16642.8, self.high=16665.1, self.low=16640.0   
2023-01-04 00:15:00,635:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230103   235000    235459  1672761299  ...  16643.7 -0.000078   1726    4
1439  20230103   235500    235959  1672761599  ...  16647.1  0.001123   1727    5
1440  20230104   000000    000459  1672761899  ...  16650.9 -0.000948   1440    0
1441  20230104   000500    000959  1672762199  ...  16653.8  0.000486   1441    1
1442  20230104   001000    001459  1672762499  ...  16640.0 -0.001218   1442    2

[5 rows x 11 columns]
2023-01-04 00:15:00,635:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-04 00:00:17,949:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230103    212959  16703.8  ...  48.333333  0.534816  0.514699
5803  20230103    215959  16711.6  ...  48.750000  0.539606  0.514200
5804  20230103    222959  16718.2  ...  48.750000  0.552748  0.506252
5805  20230103    225959  16736.0  ...  48.333333  0.487046  0.531097
5806  20230103    232959  16653.1  ...  47.916667  0.477133  0.552163

[5 rows x 33 columns]
0.5165441176470589
acc is : 0.5165441176470589
2023-01-04 00:00:18,045:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     1  0.497977  0.502023       1  ...  NaN   NaN -0.0016  0.992643
540     1  0.498661  0.501339       1  ...  NaN   NaN -0.0016  0.993706
541     0  0.503622  0.496378       0  ...  NaN   NaN -0.0016  0.988784
542     1  0.474027  0.525973       0  ...  NaN   NaN -0.0016  0.987941
543     1  0.486659  0.513341       1  ...  NaN   NaN -0.0016  0.989847

[5 rows x 10 columns]
2023-01-04 00:00:18,073:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.498226  0.501774       1  ...  NaN   NaN -0.0016  0.994598
46     1  0.498790  0.501210       1  ...  NaN   NaN -0.0016  0.994113
47     0  0.503649  0.496351       0  ...  NaN   NaN -0.0016  0.989189
48     1  0.473807  0.526193       0  ...  NaN   NaN -0.0016  0.987695
49     1  0.486659  0.513341       1  ...  NaN   NaN -0.0016  0.989847

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-1427.28517092576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16667.93893033', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-04 00:00:00,976:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230103   231000    231959  1672759199  16670.2  16619.9 -0.003023
572  20230103   232000    232959  1672759799    16620  16638.9  0.001143
573  20230103   233000    233959  1672760399    16639  16633.2 -0.000343
574  20230103   234000    234959  1672760999  16633.2  16653.4  0.001214
575  20230103   235000    235959  1672761599  16653.4  16670.8  0.001045
2023-01-04 00:00:00,976:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.263', 'enterprice': '16686.7', 'countrevence': '0', 'unrealprofit': '-873.1554', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16670.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-04 00:00:01,609:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-04 00:00:01,609:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.263, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41467F1672761601605I0L59'}
2023-01-04 00:00:01,652:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1040000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230103, closeTime:235959, close:16670.8, total:921234.9449979, mom:0.0036950182580441915, thd:0.0, side:sell 
2023-01-04 00:00:01,770:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41467F1672761601605I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672761601728124, 'quantity': '55.263', 'price': '16670.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672761601123, 'updatetime': 1672761601728, 'tradetype': 'usdt', 'selfid': 41467, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672761601728, 'clientorderid': '41467F1672761601605I0L59', 'price': '16670.8', 'quantity': '55.263', 'commission': '921.2784204', 'commissionasset': 'USDT', 'tradetime': 1672761601728, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672761601728}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-04 00:00:02,062:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41467F1672761601605I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672761601728124, 'quantity': '55.263', 'price': '16670.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672761601123, 'updatetime': 1672761601728, 'tradetype': 'usdt', 'selfid': 41467, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672761601728, 'clientorderid': '41467F1672761601605I0L59', 'price': '16670.8', 'quantity': '55.263', 'commission': '921.2784204', 'commissionasset': 'USDT', 'tradetime': 1672761601728, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672761601728}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5672 

self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16670.9', self.close='16663.1'
2023-01-04 00:10:01,553:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16670.9', self.close='16663.1'
2023-01-04 00:10:01,623:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230103   232000    232959  1672759799    16620  16638.9  0.001143
573  20230103   233000    233959  1672760399    16639  16633.2 -0.000343
574  20230103   234000    234959  1672760999  16633.2  16653.4  0.001214
575  20230103   235000    235959  1672761599  16653.4  16670.8  0.001045
576  20230104   000000    000959  1672762199  16670.9  16663.1 -0.000462
2023-01-04 00:10:01,624:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-04 00:00:00,982:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230103   231000    231959  1672759199  16670.2  16619.9
17420  20230103   232000    232959  1672759799    16620  16638.9
17421  20230103   233000    233959  1672760399    16639  16633.2
17422  20230103   234000    234959  1672760999  16633.2  16653.4
17423  20230103   235000    235959  1672761599  16653.4  16670.8
2023-01-04 00:00:00,984:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '56.347', 'enterprice': '16733', 'countrevence': '0', 'unrealprofit': '-3499.1487', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16670.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-04 00:00:01,661:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-04 00:00:01,661:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 56.347, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41468F1672761601655I0L57'}
2023-01-04 00:00:01,697:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1040000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230103, closeTime:235959, close:16670.8, total:941911.496649, pct_pre:0.0010828726637472919, thd:0.3760991650863408, side:sell 
2023-01-04 00:00:02,066:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41468F1672761601655I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672761601794495, 'quantity': '56.347', 'price': '16670.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672761601191, 'updatetime': 1672761601794, 'tradetype': 'usdt', 'selfid': 41468, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672761601794, 'clientorderid': '41468F1672761601655I0L57', 'price': '16670.8', 'quantity': '56.347', 'commission': '939.3495676', 'commissionasset': 'USDT', 'tradetime': 1672761601794, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672761601794}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-04 00:00:02,294:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41468F1672761601655I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672761601794495, 'quantity': '56.347', 'price': '16670.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672761601191, 'updatetime': 1672761601794, 'tradetype': 'usdt', 'selfid': 41468, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672761601794, 'clientorderid': '41468F1672761601655I0L57', 'price': '16670.8', 'quantity': '56.347', 'commission': '939.3495676', 'commissionasset': 'USDT', 'tradetime': 1672761601794, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672761601794}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5673 

self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16670.9', self.close='16663.1'
2023-01-04 00:10:01,580:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16670.9', self.close='16663.1'
2023-01-04 00:10:01,627:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230103   232000    232959  1672759799    16620  16638.9
17421  20230103   233000    233959  1672760399    16639  16633.2
17422  20230103   234000    234959  1672760999  16633.2  16653.4
17423  20230103   235000    235959  1672761599  16653.4  16670.8
17424  20230104   000000    000959  1672762199  16670.9  16663.1
2023-01-04 00:10:01,628:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-04 00:00:00,985:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230103   231000    231959  1672759199  16670.2  16619.9
12236  20230103   232000    232959  1672759799    16620  16638.9
12237  20230103   233000    233959  1672760399    16639  16633.2
12238  20230103   234000    234959  1672760999  16633.2  16653.4
12239  20230103   235000    235959  1672761599  16653.4  16670.8
2023-01-04 00:00:00,985:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '74.922', 'enterprice': '16695', 'countrevence': '0', 'unrealprofit': '1805.6202', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16670.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-04 00:00:01,680:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-04 00:00:01,687:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 74.922, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41469F1672761601679I0L2'}
2023-01-04 00:00:01,718:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1040000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230103, closeTime:235959, close:16670.8, total:1249571.9672100001, corrDate:20221217, corrVal:0.6003086233269456, side:buy 
2023-01-04 00:00:02,318:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41469F1672761601679I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672761601802395, 'quantity': '74.922', 'price': '16670.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672761601220, 'updatetime': 1672761601802, 'tradetype': 'usdt', 'selfid': 41469, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672761601802, 'clientorderid': '41469F1672761601679I0L2', 'price': '16670.9', 'quantity': '74.922', 'commission': '1249.0171698', 'commissionasset': 'USDT', 'tradetime': 1672761601802, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672761601802}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-04 00:00:02,502:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41469F1672761601679I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672761601802395, 'quantity': '74.922', 'price': '16670.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672761601220, 'updatetime': 1672761601802, 'tradetype': 'usdt', 'selfid': 41469, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672761601802, 'clientorderid': '41469F1672761601679I0L2', 'price': '16670.9', 'quantity': '74.922', 'commission': '1249.0171698', 'commissionasset': 'USDT', 'tradetime': 1672761601802, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672761601802}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5673 

self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16670.9', self.close='16663.1'
2023-01-04 00:10:01,575:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16670.9', self.close='16663.1'
2023-01-04 00:10:01,636:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230103   232000    232959  1672759799    16620  16638.9
12237  20230103   233000    233959  1672760399    16639  16633.2
12238  20230103   234000    234959  1672760999  16633.2  16653.4
12239  20230103   235000    235959  1672761599  16653.4  16670.8
12240  20230104   000000    000959  1672762199  16670.9  16663.1
2023-01-04 00:10:01,636:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [04/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6776
self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16654.9, self.close=16663.1, self.high=16680.1, self.low=16653.8, self.vol=1580.637, self.amt=26349035.7905 
2023-01-04 00:10:01,626:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230103   234500    234959  ...         0.0        0.0       0
5758  20230103   235000    235459  ...         0.0        0.0       0
5759  20230103   235500    235959  ...         0.0        0.0       0
5760  20230104   000000    000459  ...         0.0        0.0       0
5761  20230104   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 00:10:01,631:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672762199, self.tradeDate='20230104', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16654.9, self.close=16663.1, self.high=16680.1, self.low=16653.8, self.vol=1580.637, self.amt=26349035.7905, ukdf['pct'].iloc[-1]=0.000486 , ukdf['amount'].iloc[-1]=26349035.7905, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [04/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6777
self.closeSec=1672762499, self.tradeDate='20230104', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16663.0, self.close=16642.8, self.high=16665.1, self.low=16640.0, self.vol=1147.938, self.amt=19117982.3326 
2023-01-04 00:15:00,683:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230103   235000    235459  ...         0.0        0.0       0
5759  20230103   235500    235959  ...         0.0        0.0       0
5760  20230104   000000    000459  ...         0.0        0.0       0
5761  20230104   000500    000959  ...         0.0        0.0       0
5762  20230104   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 00:15:00,688:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672762499, self.tradeDate='20230104', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16663.0, self.close=16642.8, self.high=16665.1, self.low=16640.0, self.vol=1147.938, self.amt=19117982.3326, ukdf['pct'].iloc[-1]=-0.001218 , ukdf['amount'].iloc[-1]=19117982.3326, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230103   120000    155959  1672732799  ...    723  0.350542  0.614121     1.0
724  20230103   160000    195959  1672747199  ...    724  0.446284  1.070450     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-465.6255344976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16714.27632112', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [04/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=236
self.closeSec=1672761599, self.tradeDate='20230103', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16714.2, self.close=16670.8, self.high=16764.9, self.low=16610.0, self.vol=73811.27, self.amt=1231383821.0799 
2023-01-04 00:00:00,804:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672761599, self.tradeDate='20230103', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16714.2, self.close=16670.8, self.high=16764.9, self.low=16610.0, self.vol=73811.27, self.amt=1231383821.0799 
2023-01-04 00:00:00,843:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230103   040000    075959  ...  35222.075  5.888274e+08 -0.003849
722  20230103   080000    115959  ...  22052.463  3.676388e+08  0.001110
723  20230103   120000    155959  ...  29396.023  4.915810e+08  0.002314
724  20230103   160000    195959  ...  22008.402  3.680183e+08 -0.000532
725  20230103   200000    235959  ...  73811.270  1.231384e+09 -0.002597

[5 rows x 11 columns]
2023-01-04 00:00:02,833:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230103   040000    075959  1672703999  ...    721  0.297501  0.321886     NaN
722  20230103   080000    115959  1672718399  ...    722  0.303175  0.384621     NaN
723  20230103   120000    155959  1672732799  ...    723  0.350542  0.614121     1.0
724  20230103   160000    195959  1672747199  ...    724  0.446284  1.070450     1.0
725  20230103   200000    235959  1672761599  ...    725  0.425551  1.079751     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-2754.594', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16670.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


