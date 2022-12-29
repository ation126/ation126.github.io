# 20221229 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [29/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9146
self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16547.5, self.close=16554.8, self.high=16559.0, self.low=16545.0, self.vol=1025.303, self.amt=16972329.5065 
2022-12-29 08:10:01,472:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221229   074500    074959  ...         0.0        0.0       0
5854  20221229   075000    075459  ...         0.0        0.0       0
5855  20221229   075500    075959  ...         0.0        0.0       0
5856  20221229   080000    080459  ...         0.0        0.0       0
5857  20221229   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 08:10:01,473:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16547.5, self.close=16554.8, self.high=16559.0, self.low=16545.0, self.vol=1025.303, self.amt=16972329.5065, ukdf['pct'].iloc[-1]=0.000447 , ukdf['amount'].iloc[-1]=16972329.5065, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-1550.75689391344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16555.07035519', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9147
self.closeSec=1672272899, self.tradeDate='20221229', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16555.0, self.close=16544.9, self.high=16555.0, self.low=16544.8, self.vol=518.059, self.amt=8574170.1114 
127.0.0.1 - - [29/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-29 08:15:00,573:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221229   075000    075459  ...         0.0        0.0       0
5855  20221229   075500    075959  ...         0.0        0.0       0
5856  20221229   080000    080459  ...         0.0        0.0       0
5857  20221229   080500    080959  ...         0.0        0.0       0
5858  20221229   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 08:15:00,573:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672272899, self.tradeDate='20221229', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16555.0, self.close=16544.9, self.high=16555.0, self.low=16544.8, self.vol=518.059, self.amt=8574170.1114, ukdf['pct'].iloc[-1]=-0.000598 , ukdf['amount'].iloc[-1]=8574170.1114, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-1077.43392102928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16547.20471153', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6942589302666563, self.count=9712 

self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16547.5, self.close=16554.8, self.high=16559.0, self.low=16545.0 
2022-12-29 08:10:01,417:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16547.5, self.close=16554.8, self.high=16559.0, self.low=16545.0   
2022-12-29 08:10:01,457:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221229   074500    074959  1672271399  ...  16533.5  0.000048   1533    3
1534  20221229   075000    075459  1672271699  ...  16533.2  0.000242   1534    4
1535  20221229   075500    075959  1672271999  ...  16538.5 -0.000109   1535    5
1536  20221229   080000    080459  1672272299  ...  16534.9  0.000508   1536    0
1537  20221229   080500    080959  1672272599  ...  16545.0  0.000447   1537    1

[5 rows x 11 columns]
2022-12-29 08:10:01,458:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6942589302666563, self.count=9713 

self.closeSec=1672272899, self.tradeDate='20221229', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16555.0, self.close=16544.9, self.high=16555.0, self.low=16544.8 
2022-12-29 08:15:00,526:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672272899, self.tradeDate='20221229', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16555.0, self.close=16544.9, self.high=16555.0, self.low=16544.8   
127.0.0.1 - - [29/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-29 08:15:00,545:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221229   075000    075459  1672271699  ...  16533.2  0.000242   1534    4
1535  20221229   075500    075959  1672271999  ...  16538.5 -0.000109   1535    5
1536  20221229   080000    080459  1672272299  ...  16534.9  0.000508   1536    0
1537  20221229   080500    080959  1672272599  ...  16545.0  0.000447   1537    1
1538  20221229   081000    081459  1672272899  ...  16544.8 -0.000598   1538    2

[5 rows x 11 columns]
2022-12-29 08:15:00,545:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-29 08:00:17,575:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221229    052959  16591.3  ...  43.750000  0.404965  0.662255
5771  20221229    055959  16532.7  ...  43.333333  0.399611  0.671281
5772  20221229    062959  16521.0  ...  43.333333  0.384441  0.686895
5773  20221229    065959  16486.0  ...  43.333333  0.401301  0.696241
5774  20221229    072959  16511.4  ...  43.333333  0.420878  0.698642

[5 rows x 33 columns]
0.5194085027726433
acc is : 0.5194085027726433
2022-12-29 08:00:17,656:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.477645  0.522355       0  ...  0.986929   1.0    0.0  0.990937
537     1  0.487260  0.512740       0  ...  0.984850   1.0    0.0  0.988850
538     1  0.480331  0.519669       1  ...  0.986362   1.0    0.0  0.990367
539     1  0.493858  0.506142       1  ...  0.988190   1.0    0.0  0.992202
540     1  0.499378  0.500622       0  ...  0.988010   1.0    0.0  0.992023

[5 rows x 10 columns]
2022-12-29 08:00:17,667:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.477425  0.522575       0  ...  0.986929   1.0    0.0  0.989726
46     1  0.487333  0.512667       0  ...  0.984850   1.0    0.0  0.988500
47     1  0.480090  0.519910       1  ...  0.986362   1.0    0.0  0.989489
48     1  0.493922  0.506078       1  ...  0.988190   1.0    0.0  0.992202
49     1  0.499378  0.500622       0  ...  0.988010   1.0    0.0  0.992023

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-6773.39779539456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16542.23086448', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221229   074000    074959  1672271399    16537  16536.7 -0.000018
2022-12-29 07:50:00,659:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4855 

self.closeSec=1672271999, self.tradeDate='20221229', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16536.8', self.close='16539'
2022-12-29 08:00:01,192:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672271999, self.tradeDate='20221229', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16536.8', self.close='16539'
127.0.0.1 - - [29/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-29 08:00:01,247:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221229   071000    071959  1672269599  16530.9  16537.5  0.000405
620  20221229   072000    072959  1672270199  16537.5    16542  0.000272
621  20221229   073000    073959  1672270799  16541.9    16537 -0.000302
622  20221229   074000    074959  1672271399    16537  16536.7 -0.000018
623  20221229   075000    075959  1672271999  16536.8    16539  0.000139
2022-12-29 08:00:01,247:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4856 

self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16538.9', self.close='16555'
2022-12-29 08:10:01,515:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16538.9', self.close='16555'
2022-12-29 08:10:01,539:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221229   072000    072959  1672270199  16537.5    16542  0.000272
621  20221229   073000    073959  1672270799  16541.9    16537 -0.000302
622  20221229   074000    074959  1672271399    16537  16536.7 -0.000018
623  20221229   075000    075959  1672271999  16536.8    16539  0.000139
624  20221229   080000    080959  1672272599  16538.9    16555  0.000967
2022-12-29 08:10:01,539:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221229   074000    074959  1672271399    16537  16536.7
2022-12-29 07:50:00,645:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4856 

self.closeSec=1672271999, self.tradeDate='20221229', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16536.8', self.close='16539'
2022-12-29 08:00:01,217:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672271999, self.tradeDate='20221229', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16536.8', self.close='16539'
2022-12-29 08:00:01,258:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221229   071000    071959  1672269599  16530.9  16537.5
17468  20221229   072000    072959  1672270199  16537.5    16542
17469  20221229   073000    073959  1672270799  16541.9    16537
17470  20221229   074000    074959  1672271399    16537  16536.7
17471  20221229   075000    075959  1672271999  16536.8    16539
2022-12-29 08:00:01,258:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4857 

self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16538.9', self.close='16555'
2022-12-29 08:10:01,527:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16538.9', self.close='16555'
2022-12-29 08:10:01,544:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221229   072000    072959  1672270199  16537.5    16542
17469  20221229   073000    073959  1672270799  16541.9    16537
17470  20221229   074000    074959  1672271399    16537  16536.7
17471  20221229   075000    075959  1672271999  16536.8    16539
17472  20221229   080000    080959  1672272599  16538.9    16555
2022-12-29 08:10:01,545:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221229   074000    074959  1672271399    16537  16536.7
2022-12-29 07:50:00,657:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4856 

self.closeSec=1672271999, self.tradeDate='20221229', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16536.8', self.close='16539'
127.0.0.1 - - [29/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-29 08:00:01,233:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672271999, self.tradeDate='20221229', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16536.8', self.close='16539'
2022-12-29 08:00:01,289:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221229   071000    071959  1672269599  16530.9  16537.5
12140  20221229   072000    072959  1672270199  16537.5    16542
12141  20221229   073000    073959  1672270799  16541.9    16537
12142  20221229   074000    074959  1672271399    16537  16536.7
12143  20221229   075000    075959  1672271999  16536.8    16539
2022-12-29 08:00:01,289:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [29/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4857 

self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16538.9', self.close='16555'
2022-12-29 08:10:01,524:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16538.9', self.close='16555'
2022-12-29 08:10:01,541:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221229   072000    072959  1672270199  16537.5    16542
12141  20221229   073000    073959  1672270799  16541.9    16537
12142  20221229   074000    074959  1672271399    16537  16536.7
12143  20221229   075000    075959  1672271999  16536.8    16539
12144  20221229   080000    080959  1672272599  16538.9    16555
2022-12-29 08:10:01,541:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5144
self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16547.5, self.close=16554.8, self.high=16559.0, self.low=16545.0, self.vol=1025.303, self.amt=16972329.5065 
127.0.0.1 - - [29/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-29 08:10:01,484:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221229   074500    074959  ...         0.0        0.0       0
5854  20221229   075000    075459  ...         0.0        0.0       0
5855  20221229   075500    075959  ...         0.0        0.0       0
5856  20221229   080000    080459  ...         0.0        0.0       0
5857  20221229   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 08:10:01,485:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672272599, self.tradeDate='20221229', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16547.5, self.close=16554.8, self.high=16559.0, self.low=16545.0, self.vol=1025.303, self.amt=16972329.5065, ukdf['pct'].iloc[-1]=0.000447 , ukdf['amount'].iloc[-1]=16972329.5065, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5145
self.closeSec=1672272899, self.tradeDate='20221229', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16555.0, self.close=16544.9, self.high=16555.0, self.low=16544.8, self.vol=518.059, self.amt=8574170.1114 
127.0.0.1 - - [29/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-29 08:15:00,554:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221229   075000    075459  ...         0.0        0.0       0
5855  20221229   075500    075959  ...         0.0        0.0       0
5856  20221229   080000    080459  ...         0.0        0.0       0
5857  20221229   080500    080959  ...         0.0        0.0       0
5858  20221229   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 08:15:00,554:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672272899, self.tradeDate='20221229', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16555.0, self.close=16544.9, self.high=16555.0, self.low=16544.8, self.vol=518.059, self.amt=8574170.1114, ukdf['pct'].iloc[-1]=-0.000598 , ukdf['amount'].iloc[-1]=8574170.1114, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221228   200000    235959  1672243199  ...    719  0.235238 -0.435767     NaN
720  20221229   000000    035959  1672257599  ...    720  0.303751 -0.268507     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '7125.162', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16589.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [29/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=202
self.closeSec=1672271999, self.tradeDate='20221229', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16589.7, self.close=16539.0, self.high=16607.3, self.low=16455.6, self.vol=73829.964, self.amt=1219721527.24064 
2022-12-29 08:00:01,066:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672271999, self.tradeDate='20221229', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16589.7, self.close=16539.0, self.high=16607.3, self.low=16455.6, self.vol=73829.964, self.amt=1219721527.24064 
2022-12-29 08:00:01,081:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221228   120000    155959  ...  40102.069  6.665582e+08 -0.000258
718  20221228   160000    195959  ...  27228.635  4.534001e+08  0.001983
719  20221228   200000    235959  ...  96230.923  1.604563e+09 -0.006040
720  20221229   000000    035959  ...  48646.340  8.078613e+08  0.001110
721  20221229   040000    075959  ...  73829.964  1.219722e+09 -0.003056

[5 rows x 11 columns]
2022-12-29 08:00:02,386:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221228   120000    155959  1672214399  ...    717  0.220248 -0.486980     NaN
718  20221228   160000    195959  1672228799  ...    718  0.275760 -0.369005     NaN
719  20221228   200000    235959  1672243199  ...    719  0.235238 -0.435767     NaN
720  20221229   000000    035959  1672257599  ...    720  0.303751 -0.268507     NaN
721  20221229   040000    075959  1672271999  ...    721  0.368737 -0.107683     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '9711.45679008648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16541.14210466', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


