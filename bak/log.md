# 20221208 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3002
self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16836.7, self.close=16821.8, self.high=16839.7, self.low=16818.4, self.vol=1301.498, self.amt=21902725.2721 
127.0.0.1 - - [08/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-08 00:10:01,488:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221207   234500    234959  ...    0.139799   0.281733       0
5758  20221207   235000    235459  ...    0.139646   0.281659       0
5759  20221207   235500    235959  ...    0.139495   0.281589       0
5760  20221208   000000    000459  ...    0.139344   0.281518       0
5761  20221208   000500    000959  ...    0.139192   0.281444       0

[5 rows x 18 columns]
2022-12-08 00:10:01,489:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16836.7, self.close=16821.8, self.high=16839.7, self.low=16818.4, self.vol=1301.498, self.amt=21902725.2721, ukdf['pct'].iloc[-1]=-0.000891 , ukdf['amount'].iloc[-1]=21902725.2721, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.13919174084236155, signal=0, value_std=0.28144441934200387 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17611.42050412976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16821.96519051', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3003
self.closeSec=1670429699, self.tradeDate='20221208', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16821.8, self.close=16811.3, self.high=16823.2, self.low=16808.0, self.vol=864.813, self.amt=14540422.4864 
2022-12-08 00:15:00,570:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221207   235000    235459  ...    0.139646   0.281659       0
5759  20221207   235500    235959  ...    0.139495   0.281589       0
5760  20221208   000000    000459  ...    0.139344   0.281518       0
5761  20221208   000500    000959  ...    0.139192   0.281444       0
5762  20221208   001000    001459  ...    0.139030   0.281357       0

[5 rows x 18 columns]
2022-12-08 00:15:00,571:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670429699, self.tradeDate='20221208', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16821.8, self.close=16811.3, self.high=16823.2, self.low=16808.0, self.vol=864.813, self.amt=14540422.4864, ukdf['pct'].iloc[-1]=-0.000624 , ukdf['amount'].iloc[-1]=14540422.4864, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.13903023325914013, signal=0, value_std=0.2813574083251 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16975.6496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16811.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6535717581767528, self.count=3568 

self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16836.7, self.close=16821.8, self.high=16839.7, self.low=16818.4 
2022-12-08 00:10:01,422:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16836.7, self.close=16821.8, self.high=16839.7, self.low=16818.4   
2022-12-08 00:10:01,434:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221207   234500    234959  1670428199  ...  16804.0  0.000440   1725    3
1438  20221207   235000    235459  1670428499  ...  16820.0  0.000820   1726    4
1439  20221207   235500    235959  1670428799  ...  16827.4 -0.000356   1727    5
1440  20221208   000000    000459  1670429099  ...  16829.1  0.000458   1440    0
1441  20221208   000500    000959  1670429399  ...  16818.4 -0.000891   1441    1

[5 rows x 11 columns]
2022-12-08 00:10:01,434:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6535717581767528, self.count=3569 

self.closeSec=1670429699, self.tradeDate='20221208', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16821.8, self.close=16811.3, self.high=16823.2, self.low=16808.0 
2022-12-08 00:15:00,504:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670429699, self.tradeDate='20221208', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16821.8, self.close=16811.3, self.high=16823.2, self.low=16808.0   
127.0.0.1 - - [08/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-08 00:15:00,562:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221207   235000    235459  1670428499  ...  16820.0  0.000820   1726    4
1439  20221207   235500    235959  1670428799  ...  16827.4 -0.000356   1727    5
1440  20221208   000000    000459  1670429099  ...  16829.1  0.000458   1440    0
1441  20221208   000500    000959  1670429399  ...  16818.4 -0.000891   1441    1
1442  20221208   001000    001459  1670429699  ...  16808.0 -0.000624   1442    2

[5 rows x 11 columns]
2022-12-08 00:15:00,562:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-08 00:00:18,391:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221207    212959  16785.6  ...  50.833333  0.442976  0.630333
5803  20221207    215959  16843.8  ...  51.250000  0.444534  0.628128
5804  20221207    222959  16846.3  ...  51.250000  0.450954  0.624288
5805  20221207    225959  16859.0  ...  50.833333  0.438138  0.625125
5806  20221207    232959  16827.6  ...  50.416667  0.437172  0.626243

[5 rows x 33 columns]
0.53125
acc is : 0.53125
2022-12-08 00:00:18,484:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.500412  0.499588       1  ...  0.968055  -1.0    0.0  1.016252
540     1  0.489081  0.510919       1  ...  0.967326  -1.0    0.0  1.017018
541     1  0.495094  0.504906       0  ...  0.969133  -1.0    0.0  1.015117
542     1  0.482958  0.517042       0  ...  0.969271  -1.0    0.0  1.014973
543     1  0.488307  0.511693       1  ...  0.969041  -1.0    0.0  1.015214

[5 rows x 10 columns]
2022-12-08 00:00:18,504:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500532  0.499468       1  ...  0.946596  -1.0    0.0  1.016994
46     1  0.489299  0.510701       1  ...  0.967326  -1.0    0.0  1.018634
47     1  0.495252  0.504748       0  ...  0.969133  -1.0    0.0  1.016731
48     1  0.483302  0.516698       0  ...  0.969271  -1.0    0.0  1.016610
49     1  0.488307  0.511693       1  ...  0.969041  -1.0    0.0  1.015214

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '5200.80966076', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16830.571797', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-08 00:00:01,071:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221207   231000    231959  1670426399  16832.2    16821 -0.000659
572  20221207   232000    232959  1670426999  16820.9  16825.1  0.000244
573  20221207   233000    233959  1670427599    16825  16803.1 -0.001308
574  20221207   234000    234959  1670428199  16803.1  16821.3  0.001083
575  20221207   235000    235959  1670428799  16821.3  16829.1  0.000464
2022-12-08 00:00:01,071:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.547', 'enterprice': '17024.3', 'countrevence': '0', 'unrealprofit': '10427.78402832504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16829.55922968', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-08 00:00:01,723:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-08 00:00:01,723:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.547, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41320F1670428801722I0L59'}
2022-12-08 00:00:01,753:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12080000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221207, closeTime:235959, close:16829.1, total:910688.5919078998, mom:-0.0009749350217842512, thd:0.0, side:buy 
127.0.0.1 - - [08/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-08 00:00:02,103:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41320F1670428801722I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670428801830164, 'quantity': '53.547', 'price': '16829.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670428801223, 'updatetime': 1670428801830, 'tradetype': 'usdt', 'selfid': 41320, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670428801830, 'clientorderid': '41320F1670428801722I0L59', 'price': '16829.2', 'quantity': '53.547', 'commission': '901.1531724', 'commissionasset': 'USDT', 'tradetime': 1670428801830, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670428801830}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-08 00:00:02,375:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41320F1670428801722I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670428801830164, 'quantity': '53.547', 'price': '16829.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670428801223, 'updatetime': 1670428801830, 'tradetype': 'usdt', 'selfid': 41320, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670428801830, 'clientorderid': '41320F1670428801722I0L59', 'price': '16829.2', 'quantity': '53.547', 'commission': '901.1531724', 'commissionasset': 'USDT', 'tradetime': 1670428801830, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670428801830}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1784 

self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16829.1', self.close='16821.8'
2022-12-08 00:10:01,788:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16829.1', self.close='16821.8'
2022-12-08 00:10:01,807:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221207   232000    232959  1670426999  16820.9  16825.1  0.000244
573  20221207   233000    233959  1670427599    16825  16803.1 -0.001308
574  20221207   234000    234959  1670428199  16803.1  16821.3  0.001083
575  20221207   235000    235959  1670428799  16821.3  16829.1  0.000464
576  20221208   000000    000959  1670429399  16829.1  16821.8 -0.000434
2022-12-08 00:10:01,807:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-07 23:50:00,994:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1784 

self.closeSec=1670428799, self.tradeDate='20221207', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16821.3', self.close='16829.1'
127.0.0.1 - - [08/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-08 00:00:01,065:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670428799, self.tradeDate='20221207', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16821.3', self.close='16829.1'
2022-12-08 00:00:01,110:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221207   231000    231959  1670426399  16832.2    16821
17420  20221207   232000    232959  1670426999  16820.9  16825.1
17421  20221207   233000    233959  1670427599    16825  16803.1
17422  20221207   234000    234959  1670428199  16803.1  16821.3
17423  20221207   235000    235959  1670428799  16821.3  16829.1
2022-12-08 00:00:01,110:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-08 00:00:01,225:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12080000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221207, closeTime:235959, close:16829.1, total:940056.5307028, pct_pre:-0.009407858328721597, thd:0.3105026070936279, side:sell 
127.0.0.1 - - [08/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1785 

self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16829.1', self.close='16821.8'
2022-12-08 00:10:01,785:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16829.1', self.close='16821.8'
2022-12-08 00:10:01,817:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221207   232000    232959  1670426999  16820.9  16825.1
17421  20221207   233000    233959  1670427599    16825  16803.1
17422  20221207   234000    234959  1670428199  16803.1  16821.3
17423  20221207   235000    235959  1670428799  16821.3  16829.1
17424  20221208   000000    000959  1670429399  16829.1  16821.8
2022-12-08 00:10:01,818:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-08 00:00:01,083:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221207   231000    231959  1670426399  16832.2    16821
12236  20221207   232000    232959  1670426999  16820.9  16825.1
12237  20221207   233000    233959  1670427599    16825  16803.1
12238  20221207   234000    234959  1670428199  16803.1  16821.3
12239  20221207   235000    235959  1670428799  16821.3  16829.1
2022-12-08 00:00:01,083:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '77.374', 'enterprice': '16967.2', 'countrevence': '0', 'unrealprofit': '10649.81696273968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16829.55922968', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-08 00:00:01,699:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-08 00:00:01,699:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 77.374, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41319F1670428801695I0L2'}
2022-12-08 00:00:01,732:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12080000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221207, closeTime:235959, close:16829.1, total:1311507.3126672, corrDate:20221111, corrVal:0.7119114800439768, side:buy 
2022-12-08 00:00:01,869:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41319F1670428801695I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670428801813185, 'quantity': '77.374', 'price': '16829.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670428801280, 'updatetime': 1670428801813, 'tradetype': 'usdt', 'selfid': 41319, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670428801813, 'clientorderid': '41319F1670428801695I0L2', 'price': '16829.2', 'quantity': '77.374', 'commission': '1302.1425208', 'commissionasset': 'USDT', 'tradetime': 1670428801813, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670428801813}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-08 00:00:02,101:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41319F1670428801695I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670428801813185, 'quantity': '77.374', 'price': '16829.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670428801280, 'updatetime': 1670428801813, 'tradetype': 'usdt', 'selfid': 41319, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670428801813, 'clientorderid': '41319F1670428801695I0L2', 'price': '16829.2', 'quantity': '77.374', 'commission': '1302.1425208', 'commissionasset': 'USDT', 'tradetime': 1670428801813, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670428801813}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1785 

self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16829.1', self.close='16821.8'
2022-12-08 00:10:01,798:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670429399, self.tradeDate='20221208', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16829.1', self.close='16821.8'
2022-12-08 00:10:01,811:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221207   232000    232959  1670426999  16820.9  16825.1
12237  20221207   233000    233959  1670427599    16825  16803.1
12238  20221207   234000    234959  1670428199  16803.1  16821.3
12239  20221207   235000    235959  1670428799  16821.3  16829.1
12240  20221208   000000    000959  1670429399  16829.1  16821.8
2022-12-08 00:10:01,811:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221207   120000    155959  1670399999  ...    723  0.702535  1.042009     1.0
724  20221207   160000    195959  1670414399  ...    724  0.718504  1.093072     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-30207.9166', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16786.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=74
self.closeSec=1670428799, self.tradeDate='20221207', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16787.2, self.close=16829.1, self.high=16886.5, self.low=16754.6, self.vol=70616.715, self.amt=1188355042.9883 127.0.0.1 - - [08/Dec/2022 00:00:00] "POST / HTTP/1.1" 200 -

2022-12-08 00:00:00,883:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670428799, self.tradeDate='20221207', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16787.2, self.close=16829.1, self.high=16886.5, self.low=16754.6, self.vol=70616.715, self.amt=1188355042.9883 
2022-12-08 00:00:00,914:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221207   040000    075959  ...  51125.606  8.698549e+08  0.006714
722  20221207   080000    115959  ...  42347.692  7.222808e+08 -0.003548
723  20221207   120000    155959  ...  97327.468  1.641001e+09 -0.015378
724  20221207   160000    195959  ...  68360.933  1.147011e+09  0.001874
725  20221207   200000    235959  ...  70616.715  1.188355e+09  0.002502

[5 rows x 11 columns]
2022-12-08 00:00:02,486:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0
722  20221207   080000    115959  1670385599  ...    722  1.084938  2.647182     1.0
723  20221207   120000    155959  1670399999  ...    723  0.702535  1.042009     1.0
724  20221207   160000    195959  1670414399  ...    724  0.718504  1.093072     1.0
725  20221207   200000    235959  1670428799  ...    725  0.741914  1.167551     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-27675.22915145878', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16829.40370251', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


