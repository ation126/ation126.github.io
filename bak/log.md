# 20221229 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9050
self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16593.9, self.close=16576.4, self.high=16595.1, self.low=16562.7, self.vol=2614.256, self.amt=43340559.474 
127.0.0.1 - - [29/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-29 00:10:01,495:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221228   234500    234959  ...         0.0        0.0       0
5758  20221228   235000    235459  ...         0.0        0.0       0
5759  20221228   235500    235959  ...         0.0        0.0       0
5760  20221229   000000    000459  ...         0.0        0.0       0
5761  20221229   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 00:10:01,496:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16593.9, self.close=16576.4, self.high=16595.1, self.low=16562.7, self.vol=2614.256, self.amt=43340559.474, ukdf['pct'].iloc[-1]=-0.001031 , ukdf['amount'].iloc[-1]=43340559.474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-2840.3072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16576.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9051
self.closeSec=1672244099, self.tradeDate='20221229', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16576.5, self.close=16579.6, self.high=16589.1, self.low=16569.1, self.vol=2105.114, self.amt=34899028.2587 
2022-12-29 00:15:00,633:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221228   235000    235459  ...         0.0        0.0       0
5759  20221228   235500    235959  ...         0.0        0.0       0
5760  20221229   000000    000459  ...         0.0        0.0       0
5761  20221229   000500    000959  ...         0.0        0.0       0
5762  20221229   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 00:15:00,633:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672244099, self.tradeDate='20221229', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16576.5, self.close=16579.6, self.high=16589.1, self.low=16569.1, self.vol=2105.114, self.amt=34899028.2587, ukdf['pct'].iloc[-1]=0.000193 , ukdf['amount'].iloc[-1]=34899028.2587, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-3026.8528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16579.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6753104178986438, self.count=9616 

self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16593.9, self.close=16576.4, self.high=16595.1, self.low=16562.7 
2022-12-29 00:10:01,430:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16593.9, self.close=16576.4, self.high=16595.1, self.low=16562.7   
2022-12-29 00:10:01,475:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221228   234500    234959  1672242599  ...  16601.0 -0.000211   1725    3
1438  20221228   235000    235459  1672242899  ...  16588.6 -0.001186   1726    4
1439  20221228   235500    235959  1672243199  ...  16560.7 -0.001458   1727    5
1440  20221229   000000    000459  1672243499  ...  16555.8  0.001340   1440    0
1441  20221229   000500    000959  1672243799  ...  16562.7 -0.001031   1441    1

[5 rows x 11 columns]
2022-12-29 00:10:01,475:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6753104178986438, self.count=9617 

self.closeSec=1672244099, self.tradeDate='20221229', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16576.5, self.close=16579.6, self.high=16589.1, self.low=16569.1 
127.0.0.1 - - [29/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-29 00:15:00,538:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672244099, self.tradeDate='20221229', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16576.5, self.close=16579.6, self.high=16589.1, self.low=16569.1   
2022-12-29 00:15:00,555:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221228   235000    235459  1672242899  ...  16588.6 -0.001186   1726    4
1439  20221228   235500    235959  1672243199  ...  16560.7 -0.001458   1727    5
1440  20221229   000000    000459  1672243499  ...  16555.8  0.001340   1440    0
1441  20221229   000500    000959  1672243799  ...  16562.7 -0.001031   1441    1
1442  20221229   001000    001459  1672244099  ...  16569.1  0.000193   1442    2

[5 rows x 11 columns]
2022-12-29 00:15:00,555:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-29 00:00:18,772:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221228    212959  16646.5  ...  43.333333  0.434437  0.636830
5803  20221228    215959  16643.6  ...  43.333333  0.433559  0.627937
5804  20221228    222959  16642.4  ...  43.750000  0.437619  0.618035
5805  20221228    225959  16651.9  ...  44.166667  0.499154  0.586039
5806  20221228    232959  16729.5  ...  43.750000  0.449514  0.583548

[5 rows x 33 columns]
0.5036764705882353
acc is : 0.5036764705882353
2022-12-29 00:00:18,875:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.496443  0.503557       0  ...  0.994181   1.0    0.0  0.994282
540     1  0.496327  0.503673       1  ...  0.994474   1.0    0.0  0.994575
541     1  0.496978  0.503022       1  ...  0.999391   1.0    0.0  0.999492
542     0  0.522149  0.477851       0  ...  0.994528   1.0    0.0  0.994629
543     1  0.482304  0.517696       0  ...  0.989940   1.0    0.0  0.990041

[5 rows x 10 columns]
2022-12-29 00:00:18,897:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496719  0.503281       0  ...  0.994181   1.0    0.0  0.997411
46     1  0.496327  0.503673       1  ...  0.994474   1.0    0.0  0.996695
47     1  0.497109  0.502891       1  ...  0.999391   1.0    0.0  1.001623
48     0  0.522405  0.477595       0  ...  0.994528   1.0    0.0  0.997615
49     1  0.482304  0.517696       0  ...  0.989940   1.0    0.0  0.990041

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-5745.5156442048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16566.4004034', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-29 00:00:01,272:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221228   231000    231959  1672240799  16746.7    16731 -0.000937
572  20221228   232000    232959  1672241399  16733.1  16648.1 -0.004955
573  20221228   233000    233959  1672241999    16648  16606.4 -0.002505
574  20221228   234000    234959  1672242599  16606.3  16615.1  0.000524
575  20221228   235000    235959  1672243199  16615.5  16571.3 -0.002636
2022-12-29 00:00:01,272:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.145', 'enterprice': '16651.8', 'countrevence': '0', 'unrealprofit': '4444.687', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16571.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-29 00:00:01,912:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-29 00:00:01,912:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.145, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41431F1672243201909I0L59'}
2022-12-29 00:00:01,968:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12290000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221228, closeTime:235959, close:16571.3, total:917345.2474890001, mom:-0.004342636539535927, thd:0.0, side:buy 
127.0.0.1 - - [29/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-29 00:00:02,067:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41431F1672243201909I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672243202021567, 'quantity': '55.145', 'price': '16569.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672243201450, 'updatetime': 1672243202021, 'tradetype': 'usdt', 'selfid': 41431, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672243202021, 'clientorderid': '41431F1672243201909I0L59', 'price': '16569.9', 'quantity': '55.145', 'commission': '913.7471355', 'commissionasset': 'USDT', 'tradetime': 1672243202021, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672243202021}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-29 00:00:02,379:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41431F1672243201909I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672243202021567, 'quantity': '55.145', 'price': '16569.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672243201450, 'updatetime': 1672243202021, 'tradetype': 'usdt', 'selfid': 41431, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672243202021, 'clientorderid': '41431F1672243201909I0L59', 'price': '16569.9', 'quantity': '55.145', 'commission': '913.7471355', 'commissionasset': 'USDT', 'tradetime': 1672243202021, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672243202021}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4808 

self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16571.3', self.close='16576.4'
2022-12-29 00:10:01,532:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16571.3', self.close='16576.4'
2022-12-29 00:10:01,552:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221228   232000    232959  1672241399  16733.1  16648.1 -0.004955
573  20221228   233000    233959  1672241999    16648  16606.4 -0.002505
574  20221228   234000    234959  1672242599  16606.3  16615.1  0.000524
575  20221228   235000    235959  1672243199  16615.5  16571.3 -0.002636
576  20221229   000000    000959  1672243799  16571.3  16576.4  0.000308
2022-12-29 00:10:01,562:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-28 23:50:00,624:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4808 

self.closeSec=1672243199, self.tradeDate='20221228', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16615.5', self.close='16571.3'
127.0.0.1 - - [29/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-29 00:00:01,211:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672243199, self.tradeDate='20221228', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16615.5', self.close='16571.3'
2022-12-29 00:00:01,293:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221228   231000    231959  1672240799  16746.7    16731
17420  20221228   232000    232959  1672241399  16733.1  16648.1
17421  20221228   233000    233959  1672241999    16648  16606.4
17422  20221228   234000    234959  1672242599  16606.3  16615.1
17423  20221228   235000    235959  1672243199  16615.5  16571.3
2022-12-29 00:00:01,300:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-29 00:00:01,418:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12290000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221228, closeTime:235959, close:16571.3, total:943443.8042161, pct_pre:-0.007894893642376166, thd:0.3352727105927513, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4809 

self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16571.3', self.close='16576.4'
2022-12-29 00:10:01,547:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16571.3', self.close='16576.4'
127.0.0.1 - - [29/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-29 00:10:01,564:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221228   232000    232959  1672241399  16733.1  16648.1
17421  20221228   233000    233959  1672241999    16648  16606.4
17422  20221228   234000    234959  1672242599  16606.3  16615.1
17423  20221228   235000    235959  1672243199  16615.5  16571.3
17424  20221229   000000    000959  1672243799  16571.3  16576.4
2022-12-29 00:10:01,565:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-29 00:00:01,264:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221228   231000    231959  1672240799  16746.7    16731
12236  20221228   232000    232959  1672241399  16733.1  16648.1
12237  20221228   233000    233959  1672241999    16648  16606.4
12238  20221228   234000    234959  1672242599  16606.3  16615.1
12239  20221228   235000    235959  1672243199  16615.5  16571.3
2022-12-29 00:00:01,265:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.48', 'enterprice': '16682.1', 'countrevence': '0', 'unrealprofit': '8370.732', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16571.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-29 00:00:02,005:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-29 00:00:02,005:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.48, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41432F1672243202004I0L2'}
2022-12-29 00:00:02,063:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12290000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221228, closeTime:235959, close:16571.3, total:1257905.743092, corrDate:20221109, corrVal:0.8469152145019281, side:buy 
2022-12-29 00:00:02,370:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41432F1672243202004I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672243202130288, 'quantity': '75.48', 'price': '16569.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672243201570, 'updatetime': 1672243202130, 'tradetype': 'usdt', 'selfid': 41432, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672243202130, 'clientorderid': '41432F1672243202004I0L2', 'price': '16569.9', 'quantity': '75.48', 'commission': '1250.696052', 'commissionasset': 'USDT', 'tradetime': 1672243202130, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672243202130}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-29 00:00:02,629:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41432F1672243202004I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672243202130288, 'quantity': '75.48', 'price': '16569.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672243201570, 'updatetime': 1672243202130, 'tradetype': 'usdt', 'selfid': 41432, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672243202130, 'clientorderid': '41432F1672243202004I0L2', 'price': '16569.9', 'quantity': '75.48', 'commission': '1250.696052', 'commissionasset': 'USDT', 'tradetime': 1672243202130, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672243202130}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4809 

self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16571.3', self.close='16576.4'
2022-12-29 00:10:01,527:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16571.3', self.close='16576.4'
127.0.0.1 - - [29/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-29 00:10:01,535:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221228   232000    232959  1672241399  16733.1  16648.1
12237  20221228   233000    233959  1672241999    16648  16606.4
12238  20221228   234000    234959  1672242599  16606.3  16615.1
12239  20221228   235000    235959  1672243199  16615.5  16571.3
12240  20221229   000000    000959  1672243799  16571.3  16576.4
2022-12-29 00:10:01,535:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [29/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5048
self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16593.9, self.close=16576.4, self.high=16595.1, self.low=16562.7, self.vol=2614.256, self.amt=43340559.474 
2022-12-29 00:10:01,495:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221228   234500    234959  ...         0.0        0.0       0
5758  20221228   235000    235459  ...         0.0        0.0       0
5759  20221228   235500    235959  ...         0.0        0.0       0
5760  20221229   000000    000459  ...         0.0        0.0       0
5761  20221229   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 00:10:01,496:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672243799, self.tradeDate='20221229', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16593.9, self.close=16576.4, self.high=16595.1, self.low=16562.7, self.vol=2614.256, self.amt=43340559.474, ukdf['pct'].iloc[-1]=-0.001031 , ukdf['amount'].iloc[-1]=43340559.474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [29/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5049
self.closeSec=1672244099, self.tradeDate='20221229', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16576.5, self.close=16579.6, self.high=16589.1, self.low=16569.1, self.vol=2105.114, self.amt=34899028.2587 
2022-12-29 00:15:00,631:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221228   235000    235459  ...         0.0        0.0       0
5759  20221228   235500    235959  ...         0.0        0.0       0
5760  20221229   000000    000459  ...         0.0        0.0       0
5761  20221229   000500    000959  ...         0.0        0.0       0
5762  20221229   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 00:15:00,632:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672244099, self.tradeDate='20221229', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16576.5, self.close=16579.6, self.high=16589.1, self.low=16569.1, self.vol=2105.114, self.amt=34899028.2587, ukdf['pct'].iloc[-1]=0.000193 , ukdf['amount'].iloc[-1]=34899028.2587, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221228   120000    155959  1672214399  ...    723  0.220248 -0.486980     NaN
724  20221228   160000    195959  1672228799  ...    724  0.275760 -0.369005     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '2721.972', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16672.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=200
self.closeSec=1672243199, self.tradeDate='20221228', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16672.0, self.close=16571.3, self.high=16778.3, self.low=16560.7, self.vol=96230.923, self.amt=1604562828.129 
127.0.0.1 - - [29/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-29 00:00:01,100:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672243199, self.tradeDate='20221228', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16672.0, self.close=16571.3, self.high=16778.3, self.low=16560.7, self.vol=96230.923, self.amt=1604562828.129 
2022-12-29 00:00:01,136:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221228   040000    075959  ...  29295.519  4.886661e+08  0.001013
722  20221228   080000    115959  ...  58603.619  9.755579e+08 -0.003288
723  20221228   120000    155959  ...  40102.069  6.665582e+08 -0.000258
724  20221228   160000    195959  ...  27228.635  4.534001e+08  0.001983
725  20221228   200000    235959  ...  96230.923  1.604563e+09 -0.006040

[5 rows x 11 columns]
2022-12-29 00:00:03,117:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221228   040000    075959  1672185599  ...    721  0.131348 -0.681255    -1.0
722  20221228   080000    115959  1672199999  ...    722  0.139470 -0.658077    -1.0
723  20221228   120000    155959  1672214399  ...    723  0.220248 -0.486980     NaN
724  20221228   160000    195959  1672228799  ...    724  0.275760 -0.369005     NaN
725  20221228   200000    235959  1672243199  ...    725  0.235238 -0.435767     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '8181.9276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16569.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


