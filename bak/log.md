# 20230123 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [23/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16250
self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22736.7, self.close=22727.4, self.high=22777.0, self.low=22723.5, self.vol=2446.241, self.amt=55645458.1839 
2023-01-23 00:10:01,465:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230122   234500    234959  ...         0.0        0.0       0
5758  20230122   235000    235459  ...         0.0        0.0       0
5759  20230122   235500    235959  ...         0.0        0.0       0
5760  20230123   000000    000459  ...         0.0        0.0       0
5761  20230123   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 00:10:01,466:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22736.7, self.close=22727.4, self.high=22777.0, self.low=22723.5, self.vol=2446.241, self.amt=55645458.1839, ukdf['pct'].iloc[-1]=-0.000774 , ukdf['amount'].iloc[-1]=55645458.1839, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-373063.2869080712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22728.83614245', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16251
self.closeSec=1674404099, self.tradeDate='20230123', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22727.4, self.close=22743.7, self.high=22750.3, self.low=22686.0, self.vol=2668.988, self.amt=60636581.5831 
127.0.0.1 - - [23/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-23 00:15:00,889:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230122   235000    235459  ...         0.0        0.0       0
5759  20230122   235500    235959  ...         0.0        0.0       0
5760  20230123   000000    000459  ...         0.0        0.0       0
5761  20230123   000500    000959  ...         0.0        0.0       0
5762  20230123   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 00:15:00,889:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674404099, self.tradeDate='20230123', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22727.4, self.close=22743.7, self.high=22750.3, self.low=22686.0, self.vol=2668.988, self.amt=60636581.5831, ukdf['pct'].iloc[-1]=0.000717 , ukdf['amount'].iloc[-1]=60636581.5831, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-373946.81625972496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22743.51856321', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=93, self.factor=0.4897837089009515, self.count=16816 

self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22736.7, self.close=22727.4, self.high=22777.0, self.low=22723.5 
2023-01-23 00:10:01,433:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22736.7, self.close=22727.4, self.high=22777.0, self.low=22723.5   
2023-01-23 00:10:01,460:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230122   234500    234959  1674402599  ...  22788.8  0.001188   1725    3
1438  20230122   235000    235459  1674402899  ...  22800.4 -0.001405   1726    4
1439  20230122   235500    235959  1674403199  ...  22772.3 -0.000658   1727    5
1440  20230123   000000    000459  1674403499  ...  22736.0 -0.002102   1440    0
1441  20230123   000500    000959  1674403799  ...  22723.5 -0.000774   1441    1

[5 rows x 11 columns]
2023-01-23 00:10:01,460:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=93, self.factor=0.4897837089009515, self.count=16817 

self.closeSec=1674404099, self.tradeDate='20230123', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22727.4, self.close=22743.7, self.high=22750.3, self.low=22686.0 
2023-01-23 00:15:00,811:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674404099, self.tradeDate='20230123', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22727.4, self.close=22743.7, self.high=22750.3, self.low=22686.0   
2023-01-23 00:15:00,869:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230122   235000    235459  1674402899  ...  22800.4 -0.001405   1726    4
1439  20230122   235500    235959  1674403199  ...  22772.3 -0.000658   1727    5
1440  20230123   000000    000459  1674403499  ...  22736.0 -0.002102   1440    0
1441  20230123   000500    000959  1674403799  ...  22723.5 -0.000774   1441    1
1442  20230123   001000    001459  1674404099  ...  22686.0  0.000717   1442    2

[5 rows x 11 columns]
2023-01-23 00:15:00,869:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-23 00:00:18,317:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230122    212959  22873.9  ...  54.583333  0.566976  0.615877
5803  20230122    215959  22900.1  ...  54.583333  0.566795  0.613381
5804  20230122    222959  22898.9  ...  54.583333  0.572099  0.607817
5805  20230122    225959  22933.8  ...  54.583333  0.581193  0.596998
5806  20230122    232959  22993.2  ...  54.583333  0.538628  0.607396

[5 rows x 33 columns]
0.5091911764705882
acc is : 0.5091911764705882
2023-01-23 00:00:18,405:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.520672  0.479328       0  ...  1.130089  -1.0  0.0000  1.313234
540     0  0.529005  0.470995       1  ...  1.128392  -1.0  0.0000  1.315207
541     0  0.537526  0.462474       1  ...  1.125449  -1.0  0.0000  1.318637
542     0  0.556028  0.443972       0  ...  1.112983   1.0 -0.0016  1.306140
543     1  0.465660  0.534340       1  ...  1.113843   1.0  0.0000  1.307150

[5 rows x 10 columns]
2023-01-23 00:00:18,416:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.520061  0.479939       0  ...  1.130089  -1.0  0.0000  1.314765
46     0  0.528206  0.471794       1  ...  1.057046  -1.0  0.0000  1.315962
47     0  0.537337  0.462663       1  ...  1.125449  -1.0  0.0000  1.319393
48     0  0.556111  0.443889       0  ...  1.112983   1.0 -0.0016  1.305773
49     1  0.465660  0.534340       1  ...  1.113843   1.0  0.0000  1.307150

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.748', 'enterprice': '22767.5', 'countrevence': '0', 'unrealprofit': '998.9408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22797.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-23 00:00:01,647:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230122   231000    231959  1674400799  23055.1  23017.1 -0.001709
572  20230122   232000    232959  1674401399  23017.2  22775.3 -0.010505
573  20230122   233000    233959  1674401999  22775.3  22761.1 -0.000623
574  20230122   234000    234959  1674402599  22761.2    22840  0.003466
575  20230122   235000    235959  1674403199  22840.1  22792.9 -0.002062
2023-01-23 00:00:01,649:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.865', 'enterprice': '22736.4', 'countrevence': '0', 'unrealprofit': '2369.559', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22793', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-23 00:00:02,316:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-23 00:00:02,317:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 41.865, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41581F1674403202315I0L59'}
2023-01-23 00:00:02,348:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1230000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230122, closeTime:235959, close:22792.9, total:950907.5266140001, mom:0.007995341032048575, thd:0.0, side:sell 
127.0.0.1 - - [23/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-23 00:00:02,708:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41581F1674403202315I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674403202422272, 'quantity': '41.865', 'price': '22792.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674403201846, 'updatetime': 1674403202422, 'tradetype': 'usdt', 'selfid': 41581, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674403202422, 'clientorderid': '41581F1674403202315I0L59', 'price': '22792.9', 'quantity': '41.865', 'commission': '954.2247585', 'commissionasset': 'USDT', 'tradetime': 1674403202422, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674403202422}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-23 00:00:02,865:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41581F1674403202315I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674403202422272, 'quantity': '41.865', 'price': '22792.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674403201846, 'updatetime': 1674403202422, 'tradetype': 'usdt', 'selfid': 41581, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674403202422, 'clientorderid': '41581F1674403202315I0L59', 'price': '22792.9', 'quantity': '41.865', 'commission': '954.2247585', 'commissionasset': 'USDT', 'tradetime': 1674403202422, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674403202422}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8408 

self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22793', self.close='22727.4'
2023-01-23 00:10:01,537:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22793', self.close='22727.4'
2023-01-23 00:10:01,557:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230122   232000    232959  1674401399  23017.2  22775.3 -0.010505
573  20230122   233000    233959  1674401999  22775.3  22761.1 -0.000623
574  20230122   234000    234959  1674402599  22761.2    22840  0.003466
575  20230122   235000    235959  1674403199  22840.1  22792.9 -0.002062
576  20230123   000000    000959  1674403799    22793  22727.4 -0.002874
2023-01-23 00:10:01,557:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-22 23:50:00,609:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8408 

self.closeSec=1674403199, self.tradeDate='20230122', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='22840.1', self.close='22792.9'
2023-01-23 00:00:01,632:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674403199, self.tradeDate='20230122', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='22840.1', self.close='22792.9'
127.0.0.1 - - [23/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-23 00:00:01,663:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230122   231000    231959  1674400799  23055.1  23017.1
17420  20230122   232000    232959  1674401399  23017.2  22775.3
17421  20230122   233000    233959  1674401999  22775.3  22761.1
17422  20230122   234000    234959  1674402599  22761.2    22840
17423  20230122   235000    235959  1674403199  22840.1  22792.9
2023-01-23 00:00:01,663:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-23 00:00:01,763:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1230000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230122, closeTime:235959, close:22792.9, total:948173.1491922, pct_pre:-0.009761190925948404, thd:0.04050432815107069, side:sell 

--handleKline--: 127.0.0.1 - - [23/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8409 

self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22793', self.close='22727.4'
2023-01-23 00:10:01,528:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22793', self.close='22727.4'
2023-01-23 00:10:01,550:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230122   232000    232959  1674401399  23017.2  22775.3
17421  20230122   233000    233959  1674401999  22775.3  22761.1
17422  20230122   234000    234959  1674402599  22761.2    22840
17423  20230122   235000    235959  1674403199  22840.1  22792.9
17424  20230123   000000    000959  1674403799    22793  22727.4
2023-01-23 00:10:01,550:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-23 00:00:01,624:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230122   231000    231959  1674400799  23055.1  23017.1
12236  20230122   232000    232959  1674401399  23017.2  22775.3
12237  20230122   233000    233959  1674401999  22775.3  22761.1
12238  20230122   234000    234959  1674402599  22761.2    22840
12239  20230122   235000    235959  1674403199  22840.1  22792.9
2023-01-23 00:00:01,650:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '48.879', 'enterprice': '22748.3', 'countrevence': '0', 'unrealprofit': '2184.8913', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22793', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-23 00:00:02,282:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-23 00:00:02,282:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 48.879, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41580F1674403202280I0L2'}
2023-01-23 00:00:02,329:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1230000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230122, closeTime:235959, close:22792.9, total:1110802.2415443, corrDate:20221224, corrVal:0.62715076245371, side:sell 
2023-01-23 00:00:02,445:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41580F1674403202280I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674403202392039, 'quantity': '48.879', 'price': '22792.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674403201871, 'updatetime': 1674403202392, 'tradetype': 'usdt', 'selfid': 41580, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674403202392, 'clientorderid': '41580F1674403202280I0L2', 'price': '22792.9', 'quantity': '48.879', 'commission': '1114.0941591', 'commissionasset': 'USDT', 'tradetime': 1674403202392, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674403202392}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-23 00:00:02,674:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41580F1674403202280I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674403202392039, 'quantity': '48.879', 'price': '22792.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674403201871, 'updatetime': 1674403202392, 'tradetype': 'usdt', 'selfid': 41580, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674403202392, 'clientorderid': '41580F1674403202280I0L2', 'price': '22792.9', 'quantity': '48.879', 'commission': '1114.0941591', 'commissionasset': 'USDT', 'tradetime': 1674403202392, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674403202392}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8409 

self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22793', self.close='22727.4'
2023-01-23 00:10:01,537:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22793', self.close='22727.4'
127.0.0.1 - - [23/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-23 00:10:01,548:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230122   232000    232959  1674401399  23017.2  22775.3
12237  20230122   233000    233959  1674401999  22775.3  22761.1
12238  20230122   234000    234959  1674402599  22761.2    22840
12239  20230122   235000    235959  1674403199  22840.1  22792.9
12240  20230123   000000    000959  1674403799    22793  22727.4
2023-01-23 00:10:01,548:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [23/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12248
self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22736.7, self.close=22727.4, self.high=22777.0, self.low=22723.5, self.vol=2446.241, self.amt=55645458.1839 
2023-01-23 00:10:01,462:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230122   234500    234959  ...         0.0        0.0       0
5758  20230122   235000    235459  ...         0.0        0.0       0
5759  20230122   235500    235959  ...         0.0        0.0       0
5760  20230123   000000    000459  ...         0.0        0.0       0
5761  20230123   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 00:10:01,462:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674403799, self.tradeDate='20230123', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22736.7, self.close=22727.4, self.high=22777.0, self.low=22723.5, self.vol=2446.241, self.amt=55645458.1839, ukdf['pct'].iloc[-1]=-0.000774 , ukdf['amount'].iloc[-1]=55645458.1839, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [23/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12249
self.closeSec=1674404099, self.tradeDate='20230123', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22727.4, self.close=22743.7, self.high=22750.3, self.low=22686.0, self.vol=2668.988, self.amt=60636581.5831 
2023-01-23 00:15:00,887:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230122   235000    235459  ...         0.0        0.0       0
5759  20230122   235500    235959  ...         0.0        0.0       0
5760  20230123   000000    000459  ...         0.0        0.0       0
5761  20230123   000500    000959  ...         0.0        0.0       0
5762  20230123   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 00:15:00,887:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674404099, self.tradeDate='20230123', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22727.4, self.close=22743.7, self.high=22750.3, self.low=22686.0, self.vol=2668.988, self.amt=60636581.5831, ukdf['pct'].iloc[-1]=0.000717 , ukdf['amount'].iloc[-1]=60636581.5831, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230122   120000    155959  1674374399  ...    723  1.019065  0.565618     NaN
724  20230122   160000    195959  1674388799  ...    724  0.986795  0.478925     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-20948.98727523957', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22783.01606557', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [23/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=972283.0195242, self.flagDict['side']='buy', self.tradeCount=14, self.count=350
self.closeSec=1674403199, self.tradeDate='20230122', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22785.6, self.close=22792.9, self.high=23080.2, self.low=22631.1, self.vol=106357.24, self.amt=2431628449.4837 
2023-01-23 00:00:01,421:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674403199, self.tradeDate='20230122', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22785.6, self.close=22792.9, self.high=23080.2, self.low=22631.1, self.vol=106357.24, self.amt=2431628449.4837 
2023-01-23 00:00:01,447:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230122   040000    075959  ...   98007.119  2.253013e+09 -0.021055
722  20230122   080000    115959  ...   77074.221  1.756555e+09 -0.000694
723  20230122   120000    155959  ...   41651.721  9.528983e+08  0.005583
724  20230122   160000    195959  ...   45035.486  1.028832e+09 -0.004704
725  20230122   200000    235959  ...  106357.240  2.431628e+09  0.000325

[5 rows x 11 columns]
2023-01-23 00:00:03,015:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230122   040000    075959  1674345599  ...    721  1.060041  0.686393     1.0
722  20230122   080000    115959  1674359999  ...    722  1.049703  0.649054     1.0
723  20230122   120000    155959  1674374399  ...    723  1.019065  0.565618     NaN
724  20230122   160000    195959  1674388799  ...    724  0.986795  0.478925     NaN
725  20230122   200000    235959  1674403199  ...    725  0.986552  0.464280     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-20531.6688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22793', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


