# 20221211 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [11/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3866
self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17193.9, self.close=17196.8, self.high=17198.3, self.low=17184.5, self.vol=1003.182, self.amt=17245850.0833 
2022-12-11 00:10:01,464:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221210   234500    234959  ...         0.0        0.0       0
5758  20221210   235000    235459  ...         0.0        0.0       0
5759  20221210   235500    235959  ...         0.0        0.0       0
5760  20221211   000000    000459  ...         0.0        0.0       0
5761  20221211   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-11 00:10:01,465:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17193.9, self.close=17196.8, self.high=17198.3, self.low=17184.5, self.vol=1003.182, self.amt=17245850.0833, ukdf['pct'].iloc[-1]=0.000169 , ukdf['amount'].iloc[-1]=17245850.0833, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-40212.83285614992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17197.55367017', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3867
self.closeSec=1670688899, self.tradeDate='20221211', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17196.8, self.close=17196.3, self.high=17198.0, self.low=17195.7, self.vol=556.392, self.amt=9568207.8692 
2022-12-11 00:15:00,599:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221210   235000    235459  ...         0.0        0.0       0
5759  20221210   235500    235959  ...         0.0        0.0       0
5760  20221211   000000    000459  ...         0.0        0.0       0
5761  20221211   000500    000959  ...         0.0        0.0       0
5762  20221211   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-11 00:15:00,599:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670688899, self.tradeDate='20221211', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17196.8, self.close=17196.3, self.high=17198.0, self.low=17195.7, self.vol=556.392, self.amt=9568207.8692, ukdf['pct'].iloc[-1]=-2.9e-05 , ukdf['amount'].iloc[-1]=9568207.8692, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-40144.0185720936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17196.41011985', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=47, self.factor=0.4315022708144244, self.count=4432 

self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17193.9, self.close=17196.8, self.high=17198.3, self.low=17184.5 
2022-12-11 00:10:01,419:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17193.9, self.close=17196.8, self.high=17198.3, self.low=17184.5   
2022-12-11 00:10:01,452:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221210   234500    234959  1670687399  ...  17187.2 -0.000430   1725    3
1438  20221210   235000    235459  1670687699  ...  17188.8  0.000814   1726    4
1439  20221210   235500    235959  1670687999  ...  17200.3 -0.000151   1727    5
1440  20221211   000000    000459  1670688299  ...  17192.1 -0.000372   1440    0
1441  20221211   000500    000959  1670688599  ...  17184.5  0.000169   1441    1

[5 rows x 11 columns]
2022-12-11 00:10:01,453:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=47, self.factor=0.4315022708144244, self.count=4433 

self.closeSec=1670688899, self.tradeDate='20221211', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17196.8, self.close=17196.3, self.high=17198.0, self.low=17195.7 
2022-12-11 00:15:00,543:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670688899, self.tradeDate='20221211', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17196.8, self.close=17196.3, self.high=17198.0, self.low=17195.7   
127.0.0.1 - - [11/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-11 00:15:00,582:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221210   235000    235459  1670687699  ...  17188.8  0.000814   1726    4
1439  20221210   235500    235959  1670687999  ...  17200.3 -0.000151   1727    5
1440  20221211   000000    000459  1670688299  ...  17192.1 -0.000372   1440    0
1441  20221211   000500    000959  1670688599  ...  17184.5  0.000169   1441    1
1442  20221211   001000    001459  1670688899  ...  17195.7 -0.000029   1442    2

[5 rows x 11 columns]
2022-12-11 00:15:00,582:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-11 00:00:18,476:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221210    212959  17149.9  ...  55.833333  0.522786  0.495338
5803  20221210    215959  17140.4  ...  56.250000  0.528984  0.480266
5804  20221210    222959  17149.7  ...  56.666667  0.532051  0.463905
5805  20221210    225959  17154.3  ...  56.666667  0.534205  0.447040
5806  20221210    232959  17157.5  ...  57.083333  0.550432  0.434791

[5 rows x 33 columns]
0.5643382352941176
acc is : 0.5643382352941176
2022-12-11 00:00:18,588:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.489846  0.510154       1  ...  0.977629   1.0    0.0  1.042180
540     1  0.495142  0.504858       1  ...  0.977891   1.0    0.0  1.042460
541     1  0.493408  0.506592       1  ...  0.978074   1.0    0.0  1.042654
542     1  0.494966  0.505034       1  ...  0.979476   1.0    0.0  1.044149
543     0  0.501658  0.498342       1  ...  0.980513   1.0    0.0  1.045255

[5 rows x 10 columns]
2022-12-11 00:00:18,600:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490274  0.509726       1  ...  0.977629   1.0    0.0  1.042839
46     1  0.495203  0.504797       1  ...  0.977891   1.0    0.0  1.042460
47     1  0.493392  0.506608       1  ...  0.978074   1.0    0.0  1.042654
48     1  0.494583  0.505417       1  ...  0.979476   1.0    0.0  1.043369
49     0  0.501658  0.498342       1  ...  0.980513   1.0    0.0  1.045255

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-457.51004218994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17200.69303654', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-11 00:00:01,126:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221210   231000    231959  1670685599  17157.8  17171.1  0.000775
572  20221210   232000    232959  1670686199  17171.1    17182  0.000635
573  20221210   233000    233959  1670686799  17181.9  17185.9  0.000227
574  20221210   234000    234959  1670687399  17185.9  17188.9  0.000175
575  20221210   235000    235959  1670687999  17188.9  17200.3  0.000663
2022-12-11 00:00:01,126:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.451', 'enterprice': '17137.4', 'countrevence': '0', 'unrealprofit': '3383.1100781073', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17200.6936723', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-11 00:00:02,574:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-11 00:00:02,575:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.451, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41336F1670688002574I0L59'}
2022-12-11 00:00:02,603:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12110000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221210, closeTime:235959, close:17200.3, total:915095.1562326, mom:0.0021342975686260424, thd:0.0, side:sell 
127.0.0.1 - - [11/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-11 00:00:02,693:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41336F1670688002574I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670688002677361, 'quantity': '53.451', 'price': '17200.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670688001332, 'updatetime': 1670688002677, 'tradetype': 'usdt', 'selfid': 41336, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670688002677, 'clientorderid': '41336F1670688002574I0L59', 'price': '17200.3', 'quantity': '53.451', 'commission': '919.3732353', 'commissionasset': 'USDT', 'tradetime': 1670688002677, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670688002677}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-11 00:00:02,913:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41336F1670688002574I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670688002677361, 'quantity': '53.451', 'price': '17200.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670688001332, 'updatetime': 1670688002677, 'tradetype': 'usdt', 'selfid': 41336, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670688002677, 'clientorderid': '41336F1670688002574I0L59', 'price': '17200.3', 'quantity': '53.451', 'commission': '919.3732353', 'commissionasset': 'USDT', 'tradetime': 1670688002677, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670688002677}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2216 

self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17200.3', self.close='17196.8'
2022-12-11 00:10:01,529:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17200.3', self.close='17196.8'
2022-12-11 00:10:01,565:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221210   232000    232959  1670686199  17171.1    17182  0.000635
573  20221210   233000    233959  1670686799  17181.9  17185.9  0.000227
574  20221210   234000    234959  1670687399  17185.9  17188.9  0.000175
575  20221210   235000    235959  1670687999  17188.9  17200.3  0.000663
576  20221211   000000    000959  1670688599  17200.3  17196.8 -0.000203
2022-12-11 00:10:01,565:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-10 23:50:00,584:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2216 

self.closeSec=1670687999, self.tradeDate='20221210', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='17188.9', self.close='17200.3'
127.0.0.1 - - [11/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-11 00:00:01,057:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670687999, self.tradeDate='20221210', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='17188.9', self.close='17200.3'
2022-12-11 00:00:01,151:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221210   231000    231959  1670685599  17157.8  17171.1
17420  20221210   232000    232959  1670686199  17171.1    17182
17421  20221210   233000    233959  1670686799  17181.9  17185.9
17422  20221210   234000    234959  1670687399  17185.9  17188.9
17423  20221210   235000    235959  1670687999  17188.9  17200.3
2022-12-11 00:00:01,151:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-11 00:00:01,302:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12110000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221210, closeTime:235959, close:17200.3, total:935796.4056934, pct_pre:-0.0013985198997726878, thd:0.3453566271354668, side:sell 
127.0.0.1 - - [11/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2217 

self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17200.3', self.close='17196.8'
2022-12-11 00:10:01,541:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17200.3', self.close='17196.8'
2022-12-11 00:10:01,557:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221210   232000    232959  1670686199  17171.1    17182
17421  20221210   233000    233959  1670686799  17181.9  17185.9
17422  20221210   234000    234959  1670687399  17185.9  17188.9
17423  20221210   235000    235959  1670687999  17188.9  17200.3
17424  20221211   000000    000959  1670688599  17200.3  17196.8
2022-12-11 00:10:01,566:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-11 00:00:01,145:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221210   231000    231959  1670685599  17157.8  17171.1
12236  20221210   232000    232959  1670686199  17171.1    17182
12237  20221210   233000    233959  1670686799  17181.9  17185.9
12238  20221210   234000    234959  1670687399  17185.9  17188.9
12239  20221210   235000    235959  1670687999  17188.9  17200.3
2022-12-11 00:00:01,145:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '76.83', 'enterprice': '17123.8', 'countrevence': '0', 'unrealprofit': '-5907.740842809', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17200.6936723', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-11 00:00:02,967:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-11 00:00:02,967:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 76.83, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41337F1670688002966I0L2'}
2022-12-11 00:00:03,008:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12110000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221210, closeTime:235959, close:17200.3, total:1314305.932446, corrDate:20221113, corrVal:0.9255386123819082, side:buy 
2022-12-11 00:00:03,130:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41337F1670688002966I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670688003085300, 'quantity': '76.83', 'price': '17200.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670688002011, 'updatetime': 1670688003085, 'tradetype': 'usdt', 'selfid': 41337, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670688003085, 'clientorderid': '41337F1670688002966I0L2', 'price': '17200.4', 'quantity': '76.83', 'commission': '1321.506732', 'commissionasset': 'USDT', 'tradetime': 1670688003085, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670688003085}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-11 00:00:03,372:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41337F1670688002966I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670688003085300, 'quantity': '76.83', 'price': '17200.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670688002011, 'updatetime': 1670688003085, 'tradetype': 'usdt', 'selfid': 41337, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670688003085, 'clientorderid': '41337F1670688002966I0L2', 'price': '17200.4', 'quantity': '76.83', 'commission': '1321.506732', 'commissionasset': 'USDT', 'tradetime': 1670688003085, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670688003085}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2217 

self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17200.3', self.close='17196.8'
127.0.0.1 - - [11/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-11 00:10:01,541:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670688599, self.tradeDate='20221211', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17200.3', self.close='17196.8'
2022-12-11 00:10:01,568:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221210   232000    232959  1670686199  17171.1    17182
12237  20221210   233000    233959  1670686799  17181.9  17185.9
12238  20221210   234000    234959  1670687399  17185.9  17188.9
12239  20221210   235000    235959  1670687999  17188.9  17200.3
12240  20221211   000000    000959  1670688599  17200.3  17196.8
2022-12-11 00:10:01,569:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221210   120000    155959  1670659199  ...    723  0.558600  0.190165     NaN
724  20221210   160000    195959  1670673599  ...    724  0.549339  0.156319     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-8306.7374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17159.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--: 127.0.0.1 - - [11/Dec/2022 00:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=92
self.closeSec=1670687999, self.tradeDate='20221210', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=17159.9, self.close=17200.3, self.high=17228.6, self.low=17132.0, self.vol=36351.612, self.amt=624156408.4248 
2022-12-11 00:00:00,960:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670687999, self.tradeDate='20221210', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=17159.9, self.close=17200.3, self.high=17228.6, self.low=17132.0, self.vol=36351.612, self.amt=624156408.4248 
2022-12-11 00:00:00,980:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221210   040000    075959  ...  31474.007  5.384585e+08 -0.000753
722  20221210   080000    115959  ...  19761.717  3.386550e+08  0.001051
723  20221210   120000    155959  ...  17751.416  3.043245e+08  0.000268
724  20221210   160000    195959  ...  20902.227  3.582971e+08  0.000892
725  20221210   200000    235959  ...  36351.612  6.241564e+08  0.002354

[5 rows x 11 columns]
2022-12-11 00:00:02,249:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221210   040000    075959  1670630399  ...    721  0.608464  0.371435     NaN
722  20221210   080000    115959  1670644799  ...    722  0.581691  0.273686     NaN
723  20221210   120000    155959  1670659199  ...    723  0.558600  0.190165     NaN
724  20221210   160000    195959  1670673599  ...    724  0.549339  0.156319     NaN
725  20221210   200000    235959  1670687999  ...    725  0.552818  0.166990     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-5909.4685424294', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17200.6936723', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


