# 20230102 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10202
self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16555.3, self.close=16560.9, self.high=16561.3, self.low=16555.2, self.vol=413.113, self.amt=6840640.1207 
127.0.0.1 - - [02/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-02 00:10:01,467:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230101   234500    234959  ...         0.0        0.0       0
5758  20230101   235000    235459  ...         0.0        0.0       0
5759  20230101   235500    235959  ...         0.0        0.0       0
5760  20230102   000000    000459  ...         0.0        0.0       0
5761  20230102   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 00:10:01,467:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16555.3, self.close=16560.9, self.high=16561.3, self.low=16555.2, self.vol=413.113, self.amt=6840640.1207, ukdf['pct'].iloc[-1]=0.000338 , ukdf['amount'].iloc[-1]=6840640.1207, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-1901.894869732', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16560.90553825', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10203
self.closeSec=1672589699, self.tradeDate='20230102', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16560.4, self.close=16554.8, self.high=16560.4, self.low=16552.6, self.vol=363.821, self.amt=6023182.8336 
127.0.0.1 - - [02/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-02 00:15:00,884:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230101   235000    235459  ...         0.0        0.0       0
5759  20230101   235500    235959  ...         0.0        0.0       0
5760  20230102   000000    000459  ...         0.0        0.0       0
5761  20230102   000500    000959  ...         0.0        0.0       0
5762  20230102   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 00:15:00,885:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672589699, self.tradeDate='20230102', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16560.4, self.close=16554.8, self.high=16560.4, self.low=16552.6, self.vol=363.821, self.amt=6023182.8336, ukdf['pct'].iloc[-1]=-0.000368 , ukdf['amount'].iloc[-1]=6023182.8336, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-1540.08582546272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16554.89302422', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5717304912910172, self.count=10768 

self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16555.3, self.close=16560.9, self.high=16561.3, self.low=16555.2 
2023-01-02 00:10:01,413:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16555.3, self.close=16560.9, self.high=16561.3, self.low=16555.2   
2023-01-02 00:10:01,455:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230101   234500    234959  1672588199  ...  16539.4 -0.000085   1725    3
1438  20230101   235000    235459  1672588499  ...  16539.4 -0.000006   1726    4
1439  20230101   235500    235959  1672588799  ...  16539.0  0.000828   1727    5
1440  20230102   000000    000459  1672589099  ...  16553.0  0.000133   1440    0
1441  20230102   000500    000959  1672589399  ...  16555.2  0.000338   1441    1

[5 rows x 11 columns]
2023-01-02 00:10:01,455:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [02/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5717304912910172, self.count=10769 

self.closeSec=1672589699, self.tradeDate='20230102', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16560.4, self.close=16554.8, self.high=16560.4, self.low=16552.6 
2023-01-02 00:15:00,767:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672589699, self.tradeDate='20230102', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16560.4, self.close=16554.8, self.high=16560.4, self.low=16552.6   
2023-01-02 00:15:00,800:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230101   235000    235459  1672588499  ...  16539.4 -0.000006   1726    4
1439  20230101   235500    235959  1672588799  ...  16539.0  0.000828   1727    5
1440  20230102   000000    000459  1672589099  ...  16553.0  0.000133   1440    0
1441  20230102   000500    000959  1672589399  ...  16555.2  0.000338   1441    1
1442  20230102   001000    001459  1672589699  ...  16552.6 -0.000368   1442    2

[5 rows x 11 columns]
2023-01-02 00:15:00,800:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

5806  20230101    232959  16533.2  ...  46.666667  0.484010  0.508520

[5 rows x 33 columns]
0.5073529411764706
acc is : 0.5073529411764706
2023-01-02 00:00:22,698:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     1  0.495195  0.504805       0  ...  NaN   NaN -0.0016  0.983979
540     1  0.498635  0.501365       1  ...  NaN   NaN -0.0016  0.984532
541     0  0.500491  0.499509       0  ...  NaN   NaN -0.0016  0.983580
542     1  0.492542  0.507458       1  ...  NaN   NaN -0.0016  0.983658
543     1  0.496338  0.503662       1  ...  NaN   NaN -0.0016  0.984764

[5 rows x 10 columns]
2023-01-02 00:00:22,714:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.494932  0.505068       0  ...  NaN   NaN -0.0016  0.982722
46     1  0.498671  0.501329       1  ...  NaN   NaN -0.0016  0.983374
47     0  0.500508  0.499492       0  ...  NaN   NaN -0.0016  0.982423
48     1  0.492291  0.507709       1  ...  NaN   NaN -0.0016  0.982518
49     1  0.496338  0.503662       1  ...  NaN   NaN -0.0016  0.984764

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-6311.1552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16553.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
Traceback (most recent call last):
  File "/root/FIL/strategy/logic/FIL_lib/client.py", line 95, in __start_handle
    handle_call(handle_data)
  File "main.py", line 431, in handleKline
    curSign = int(df_panel['sign'].iloc[-1])
ValueError: cannot convert float NaN to integer


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-02 00:00:01,320:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230101   231000    231959  1672586399  16540.3  16540.3  0.000006
572  20230101   232000    232959  1672586999  16540.2  16534.4 -0.000357
573  20230101   233000    233959  1672587599  16534.5  16536.6  0.000133
574  20230101   234000    234959  1672588199  16536.7  16539.5  0.000175
575  20230101   235000    235959  1672588799  16539.4  16553.1  0.000822
2023-01-02 00:00:01,320:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.426', 'enterprice': '16527.3', 'countrevence': '0', 'unrealprofit': '1429.9908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16553.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-02 00:00:01,849:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-02 00:00:01,850:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.426, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41456F1672588801848I0L59'}
2023-01-02 00:00:01,877:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1020000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230101, closeTime:235959, close:16553.1, total:915126.0876702, mom:0.0015291491728217643, thd:0.0, side:sell 
127.0.0.1 - - [02/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-02 00:00:02,206:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41456F1672588801848I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672588801964042, 'quantity': '55.426', 'price': '16553', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672588801467, 'updatetime': 1672588801964, 'tradetype': 'usdt', 'selfid': 41456, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672588801964, 'clientorderid': '41456F1672588801848I0L59', 'price': '16553', 'quantity': '55.426', 'commission': '917.466578', 'commissionasset': 'USDT', 'tradetime': 1672588801964, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672588801964}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-02 00:00:02,409:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41456F1672588801848I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672588801964042, 'quantity': '55.426', 'price': '16553', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672588801467, 'updatetime': 1672588801964, 'tradetype': 'usdt', 'selfid': 41456, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672588801964, 'clientorderid': '41456F1672588801848I0L59', 'price': '16553', 'quantity': '55.426', 'commission': '917.466578', 'commissionasset': 'USDT', 'tradetime': 1672588801964, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672588801964}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5384 

self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16553', self.close='16560.3'
2023-01-02 00:10:01,539:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16553', self.close='16560.3'
127.0.0.1 - - [02/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-02 00:10:01,551:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230101   232000    232959  1672586999  16540.2  16534.4 -0.000357
573  20230101   233000    233959  1672587599  16534.5  16536.6  0.000133
574  20230101   234000    234959  1672588199  16536.7  16539.5  0.000175
575  20230101   235000    235959  1672588799  16539.4  16553.1  0.000822
576  20230102   000000    000959  1672589399    16553  16560.3  0.000435
2023-01-02 00:10:01,552:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-01 23:50:00,633:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  127.0.0.1 - - [02/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5384 

self.closeSec=1672588799, self.tradeDate='20230101', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16539.4', self.close='16553.1'
2023-01-02 00:00:01,201:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672588799, self.tradeDate='20230101', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16539.4', self.close='16553.1'
2023-01-02 00:00:01,223:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230101   231000    231959  1672586399  16540.3  16540.3
17420  20230101   232000    232959  1672586999  16540.2  16534.4
17421  20230101   233000    233959  1672587599  16534.5  16536.6
17422  20230101   234000    234959  1672588199  16536.7  16539.5
17423  20230101   235000    235959  1672588799  16539.4  16553.1
2023-01-02 00:00:01,223:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-02 00:00:01,316:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1020000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230101, closeTime:235959, close:16553.1, total:943801.2083061, pct_pre:-0.0033036925395628636, thd:-0.14339293016495763, side:sell 
127.0.0.1 - - [02/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5385 

self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16553', self.close='16560.3'
2023-01-02 00:10:01,552:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16553', self.close='16560.3'
2023-01-02 00:10:01,572:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230101   232000    232959  1672586999  16540.2  16534.4
17421  20230101   233000    233959  1672587599  16534.5  16536.6
17422  20230101   234000    234959  1672588199  16536.7  16539.5
17423  20230101   235000    235959  1672588799  16539.4  16553.1
17424  20230102   000000    000959  1672589399    16553  16560.3
2023-01-02 00:10:01,573:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-02 00:00:01,213:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230101   231000    231959  1672586399  16540.3  16540.3
12236  20230101   232000    232959  1672586999  16540.2  16534.4
12237  20230101   233000    233959  1672587599  16534.5  16536.6
12238  20230101   234000    234959  1672588199  16536.7  16539.5
12239  20230101   235000    235959  1672588799  16539.4  16553.1
2023-01-02 00:00:01,217:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '76.323', 'enterprice': '16512.5', 'countrevence': '0', 'unrealprofit': '3098.7138', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16553.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-02 00:00:01,781:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-02 00:00:01,782:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 76.323, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41455F1672588801777I0L2'}
2023-01-02 00:00:01,814:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1020000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230101, closeTime:235959, close:16553.1, total:1259023.2539624998, corrDate:20221211, corrVal:0.85885664803449, side:sell 
2023-01-02 00:00:01,923:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41455F1672588801777I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672588801887098, 'quantity': '76.323', 'price': '16553', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672588801392, 'updatetime': 1672588801887, 'tradetype': 'usdt', 'selfid': 41455, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672588801887, 'clientorderid': '41455F1672588801777I0L2', 'price': '16553', 'quantity': '76.323', 'commission': '1263.374619', 'commissionasset': 'USDT', 'tradetime': 1672588801887, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672588801887}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-02 00:00:02,190:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41455F1672588801777I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672588801887098, 'quantity': '76.323', 'price': '16553', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672588801392, 'updatetime': 1672588801887, 'tradetype': 'usdt', 'selfid': 41455, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672588801887, 'clientorderid': '41455F1672588801777I0L2', 'price': '16553', 'quantity': '76.323', 'commission': '1263.374619', 'commissionasset': 'USDT', 'tradetime': 1672588801887, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672588801887}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5385 

self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16553', self.close='16560.3'
2023-01-02 00:10:01,528:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16553', self.close='16560.3'
2023-01-02 00:10:01,548:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230101   232000    232959  1672586999  16540.2  16534.4
12237  20230101   233000    233959  1672587599  16534.5  16536.6
12238  20230101   234000    234959  1672588199  16536.7  16539.5
12239  20230101   235000    235959  1672588799  16539.4  16553.1
12240  20230102   000000    000959  1672589399    16553  16560.3
2023-01-02 00:10:01,548:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6200
self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16555.3, self.close=16560.9, self.high=16561.3, self.low=16555.2, self.vol=413.113, self.amt=6840640.1207 
127.0.0.1 - - [02/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-02 00:10:01,479:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230101   234500    234959  ...         0.0        0.0       0
5758  20230101   235000    235459  ...         0.0        0.0       0
5759  20230101   235500    235959  ...         0.0        0.0       0
5760  20230102   000000    000459  ...         0.0        0.0       0
5761  20230102   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 00:10:01,480:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672589399, self.tradeDate='20230102', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16555.3, self.close=16560.9, self.high=16561.3, self.low=16555.2, self.vol=413.113, self.amt=6840640.1207, ukdf['pct'].iloc[-1]=0.000338 , ukdf['amount'].iloc[-1]=6840640.1207, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6201
self.closeSec=1672589699, self.tradeDate='20230102', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16560.4, self.close=16554.8, self.high=16560.4, self.low=16552.6, self.vol=363.821, self.amt=6023182.8336 
2023-01-02 00:15:00,884:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230101   235000    235459  ...         0.0        0.0       0
5759  20230101   235500    235959  ...         0.0        0.0       0
5760  20230102   000000    000459  ...         0.0        0.0       0
5761  20230102   000500    000959  ...         0.0        0.0       0
5762  20230102   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 00:15:00,885:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672589699, self.tradeDate='20230102', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16560.4, self.close=16554.8, self.high=16560.4, self.low=16552.6, self.vol=363.821, self.amt=6023182.8336, ukdf['pct'].iloc[-1]=-0.000368 , ukdf['amount'].iloc[-1]=6023182.8336, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230101   120000    155959  1672559999  ...    723  0.076628 -0.635073    -1.0
724  20230101   160000    195959  1672574399  ...    724  0.069651 -0.637465    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '780.7525', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16549.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [02/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891007.4496510001, self.flagDict['side']='sell', self.tradeCount=9, self.count=224
self.closeSec=1672588799, self.tradeDate='20230101', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16549.8, self.close=16553.1, self.high=16565.9, self.low=16524.6, self.vol=15542.884, self.amt=257160458.3334 
2023-01-02 00:00:00,857:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672588799, self.tradeDate='20230101', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16549.8, self.close=16553.1, self.high=16565.9, self.low=16524.6, self.vol=15542.884, self.amt=257160458.3334 
2023-01-02 00:00:00,913:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230101   040000    075959  ...  31497.566  5.205152e+08 -0.001612
722  20230101   080000    115959  ...  14204.791  2.348208e+08 -0.000502
723  20230101   120000    155959  ...  17998.501  2.972818e+08 -0.000587
724  20230101   160000    195959  ...  15117.276  2.498421e+08  0.001828
725  20230101   200000    235959  ...  15542.884  2.571605e+08  0.000199

[5 rows x 11 columns]
2023-01-02 00:00:02,373:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230101   040000    075959  1672531199  ...    721  0.088487 -0.635651    -1.0
722  20230101   080000    115959  1672545599  ...    722  0.069158 -0.672480    -1.0
723  20230101   120000    155959  1672559999  ...    723  0.076628 -0.635073    -1.0
724  20230101   160000    195959  1672574399  ...    724  0.069651 -0.637465    -1.0
725  20230101   200000    235959  1672588799  ...    725  0.047921 -0.681075    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '597.6795', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16553.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


