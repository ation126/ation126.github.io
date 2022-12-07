
## /root/FIL/strategy/amihud/log.txt ----- -----
127.0.0.1 - - [07/Dec/2022 12:05:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2857
self.closeSec=1670385899, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120459', self.symbol='BTCUSDT', self.open=17017.4, self.close=17015.4, self.high=17017.5, self.low=17013.7, self.vol=523.476, self.amt=8907302.8369 
2022-12-07 12:05:00,470:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5900  20221207   114000    114459  ...    0.165219   0.296770       0
5901  20221207   114500    114959  ...    0.165027   0.296654       0
5902  20221207   115000    115459  ...    0.164822   0.296513       0
5903  20221207   115500    115959  ...    0.164617   0.296371       0
5904  20221207   120000    120459  ...    0.164412   0.296230       0

[5 rows x 18 columns]
2022-12-07 12:05:00,470:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670385899, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120459',self.symbol='BTCUSDT',self.open=17017.4, self.close=17015.4, self.high=17017.5, self.low=17013.7, self.vol=523.476, self.amt=8907302.8369, ukdf['pct'].iloc[-1]=-0.000118 , ukdf['amount'].iloc[-1]=8907302.8369, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5904, value=0.0, value_mean=0.16441216005244583, signal=0, value_std=0.2962300966078235 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-29251.5536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17015.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--: 127.0.0.1 - - [07/Dec/2022 12:10:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2858
self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120500', self.closeTime='120959', self.symbol='BTCUSDT', self.open=17015.4, self.close=17012.7, self.high=17015.5, self.low=17011.5, self.vol=674.874, self.amt=11481445.8386 
2022-12-07 12:10:01,449:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5901  20221207   114500    114959  ...    0.165027   0.296654       0
5902  20221207   115000    115459  ...    0.164822   0.296513       0
5903  20221207   115500    115959  ...    0.164617   0.296371       0
5904  20221207   120000    120459  ...    0.164412   0.296230       0
5905  20221207   120500    120959  ...    0.164199   0.296071       0

[5 rows x 18 columns]
2022-12-07 12:10:01,449:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120500', self.closeTime='120959',self.symbol='BTCUSDT',self.open=17015.4, self.close=17012.7, self.high=17015.5, self.low=17011.5, self.vol=674.874, self.amt=11481445.8386, ukdf['pct'].iloc[-1]=-0.000159 , ukdf['amount'].iloc[-1]=11481445.8386, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5905, value=0.0, value_mean=0.1641985619761871, signal=0, value_std=0.29607129860371567 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-29197.3952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17014.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----
--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.5526281110804184, self.count=3423 

self.closeSec=1670385899, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120459', self.symbol='BTCUSDT', self.open=17017.4, self.close=17015.4, self.high=17017.5, self.low=17013.7 
2022-12-07 12:05:00,430:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670385899, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120459',self.symbol='BTCUSDT',self.open=17017.4, self.close=17015.4, self.high=17017.5, self.low=17013.7   
2022-12-07 12:05:00,464:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1580  20221207   114000    114459  1670384699  ...  17021.0  0.000047   1580    2
1581  20221207   114500    114959  1670384999  ...  17020.0  0.000059   1581    3
1582  20221207   115000    115459  1670385299  ...  17020.5 -0.000229   1582    4
1583  20221207   115500    115959  1670385599  ...  17017.4 -0.000182   1583    5
1584  20221207   120000    120459  1670385899  ...  17013.7 -0.000118   1584    0

[5 rows x 11 columns]
2022-12-07 12:05:00,464:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Dec/2022 12:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.5526281110804184, self.count=3424 

self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120500', self.closeTime='120959', self.symbol='BTCUSDT', self.open=17015.4, self.close=17012.7, self.high=17015.5, self.low=17011.5 
2022-12-07 12:10:01,418:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120500', self.closeTime='120959',self.symbol='BTCUSDT',self.open=17015.4, self.close=17012.7, self.high=17015.5, self.low=17011.5   
2022-12-07 12:10:01,429:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1581  20221207   114500    114959  1670384999  ...  17020.0  0.000059   1581    3
1582  20221207   115000    115459  1670385299  ...  17020.5 -0.000229   1582    4
1583  20221207   115500    115959  1670385599  ...  17017.4 -0.000182   1583    5
1584  20221207   120000    120459  1670385899  ...  17013.7 -0.000118   1584    0
1585  20221207   120500    120959  1670386199  ...  17011.5 -0.000159   1585    1

[5 rows x 11 columns]
2022-12-07 12:10:01,429:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----
2022-12-07 12:00:17,078:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5778  20221207    092959  17056.5  ...  50.833333  0.502610  0.511078
5779  20221207    095959  17027.9  ...  51.250000  0.506089  0.504502
5780  20221207    102959  17035.1  ...  51.666667  0.508730  0.496770
5781  20221207    105959  17040.7  ...  51.666667  0.511686  0.487787
5782  20221207    112959  17046.7  ...  51.666667  0.496738  0.488065

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2022-12-07 12:00:17,138:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.486352  0.513648       1  ...  0.936216  -1.0    0.0  1.033257
537     1  0.485405  0.514595       1  ...  0.935914  -1.0    0.0  1.033591
538     1  0.483464  0.516536       1  ...  0.935579  -1.0    0.0  1.033961
539     1  0.486157  0.513843       0  ...  0.937220  -1.0    0.0  1.032147
540     1  0.476141  0.523859       1  ...  0.937187  -1.0    0.0  1.032183

[5 rows x 10 columns]
2022-12-07 12:00:17,149:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486012  0.513988       1  ...  0.936216  -1.0    0.0  1.031974
46     1  0.484674  0.515326       1  ...  0.935914  -1.0    0.0  1.031763
47     1  0.482579  0.517421       1  ...  0.935579  -1.0    0.0  1.029763
48     1  0.485705  0.514295       0  ...  0.937220  -1.0    0.0  1.030141
49     1  0.476141  0.523859       1  ...  0.937187  -1.0    0.0  1.032183

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '-2103.003206052', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17018.2339981', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----
127.0.0.1 - - [07/Dec/2022 11:50:01] "POST / HTTP/1.1" 200 -
2022-12-07 11:50:01,145:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41318F1670385000862I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670385000962247, 'quantity': '53.547', 'price': '17024.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1670385000692, 'updatetime': 1670385000962, 'tradetype': 'usdt', 'selfid': 41318, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670385000962, 'clientorderid': '41318F1670385000862I0L59', 'price': '17024.3', 'quantity': '53.547', 'commission': '911.6001921', 'commissionasset': 'USDT', 'tradetime': 1670385000962, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670385000962}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Dec/2022 12:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1711 

self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='115000', self.closeTime='115959', self.symbol='BTCUSDT', self.open='17024.4', self.close='17017.9'
2022-12-07 12:00:01,065:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='115000', self.closeTime='115959',self.symbol='BTCUSDT',self.open='17024.4', self.close='17017.9'
2022-12-07 12:00:01,101:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
499  20221207   111000    111959  1670383199  17031.7  17027.1 -0.000276
500  20221207   112000    112959  1670383799  17027.1  17016.8 -0.000605
501  20221207   113000    113959  1670384399  17016.8  17022.6  0.000341
502  20221207   114000    114959  1670384999  17022.5  17024.4  0.000106
503  20221207   115000    115959  1670385599  17024.4  17017.9 -0.000382
2022-12-07 12:00:01,101:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Dec/2022 12:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1712 

self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120959', self.symbol='BTCUSDT', self.open='17017.4', self.close='17012.7'
2022-12-07 12:10:01,541:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120959',self.symbol='BTCUSDT',self.open='17017.4', self.close='17012.7'
2022-12-07 12:10:01,581:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
500  20221207   112000    112959  1670383799  17027.1  17016.8 -0.000605
501  20221207   113000    113959  1670384399  17016.8  17022.6  0.000341
502  20221207   114000    114959  1670384999  17022.5  17024.4  0.000106
503  20221207   115000    115959  1670385599  17024.4  17017.9 -0.000382
504  20221207   120000    120959  1670386199  17017.4  17012.7 -0.000306
2022-12-07 12:10:01,581:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----
17494  20221207   114000    114959  1670384999  17022.5  17024.4
2022-12-07 11:50:00,538:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1712 

self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='115000', self.closeTime='115959', self.symbol='BTCUSDT', self.open='17024.4', self.close='17017.9'
2022-12-07 12:00:01,096:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='115000', self.closeTime='115959',self.symbol='BTCUSDT',self.open='17024.4', self.close='17017.9'
127.0.0.1 - - [07/Dec/2022 12:00:01] "POST / HTTP/1.1" 200 -
2022-12-07 12:00:01,109:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17491  20221207   111000    111959  1670383199  17031.7  17027.1
17492  20221207   112000    112959  1670383799  17027.1  17016.8
17493  20221207   113000    113959  1670384399  17016.8  17022.6
17494  20221207   114000    114959  1670384999  17022.5  17024.4
17495  20221207   115000    115959  1670385599  17024.4  17017.9
2022-12-07 12:00:01,110:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Dec/2022 12:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1713 

self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120959', self.symbol='BTCUSDT', self.open='17017.4', self.close='17012.7'
2022-12-07 12:10:01,554:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120959',self.symbol='BTCUSDT',self.open='17017.4', self.close='17012.7'
2022-12-07 12:10:01,566:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17492  20221207   112000    112959  1670383799  17027.1  17016.8
17493  20221207   113000    113959  1670384399  17016.8  17022.6
17494  20221207   114000    114959  1670384999  17022.5  17024.4
17495  20221207   115000    115959  1670385599  17024.4  17017.9
17496  20221207   120000    120959  1670386199  17017.4  17012.7
2022-12-07 12:10:01,567:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----
12166  20221207   114000    114959  1670384999  17022.5  17024.4
2022-12-07 11:50:00,556:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1712 

self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='115000', self.closeTime='115959', self.symbol='BTCUSDT', self.open='17024.4', self.close='17017.9'
2022-12-07 12:00:01,053:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='115000', self.closeTime='115959',self.symbol='BTCUSDT',self.open='17024.4', self.close='17017.9'
127.0.0.1 - - [07/Dec/2022 12:00:01] "POST / HTTP/1.1" 200 -
2022-12-07 12:00:01,066:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12163  20221207   111000    111959  1670383199  17031.7  17027.1
12164  20221207   112000    112959  1670383799  17027.1  17016.8
12165  20221207   113000    113959  1670384399  17016.8  17022.6
12166  20221207   114000    114959  1670384999  17022.5  17024.4
12167  20221207   115000    115959  1670385599  17024.4  17017.9
2022-12-07 12:00:01,068:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Dec/2022 12:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1713 

self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120959', self.symbol='BTCUSDT', self.open='17017.4', self.close='17012.7'
2022-12-07 12:10:01,564:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670386199, self.tradeDate='20221207', self.openTime='120000', self.closeTime='120959',self.symbol='BTCUSDT',self.open='17017.4', self.close='17012.7'
2022-12-07 12:10:01,584:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12164  20221207   112000    112959  1670383799  17027.1  17016.8
12165  20221207   113000    113959  1670384399  17016.8  17022.6
12166  20221207   114000    114959  1670384999  17022.5  17024.4
12167  20221207   115000    115959  1670385599  17024.4  17017.9
12168  20221207   120000    120959  1670386199  17017.4  17012.7
2022-12-07 12:10:01,584:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----
720  20221207   000000    035959  1670356799  ...    720  1.120770  3.120988     1.0
721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-13012.51157857668', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17079.52682306', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [07/Dec/2022 12:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=71
self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='080000', self.closeTime='115959', self.symbol='BTCUSDT', self.open=17078.7, self.close=17017.4, self.high=17130.0, self.low=17011.0, self.vol=42347.692, self.amt=722280772.2839 
2022-12-07 12:00:00,936:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='080000', self.closeTime='115959',self.symbol='BTCUSDT',self.open=17078.7, self.close=17017.4, self.high=17130.0, self.low=17011.0, self.vol=42347.692, self.amt=722280772.2839 
2022-12-07 12:00:00,950:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
718  20221206   160000    195959  ...  57639.285  9.783913e+08 -0.001118
719  20221206   200000    235959  ...  69024.422  1.172189e+09  0.000018
720  20221207   000000    035959  ...  56413.953  9.566549e+08 -0.000636
721  20221207   040000    075959  ...  51125.606  8.698549e+08  0.006714
722  20221207   080000    115959  ...  42347.692  7.222808e+08 -0.003548

[5 rows x 11 columns]
2022-12-07 12:00:01,641:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
718  20221206   160000    195959  1670327999  ...    718  0.713850  1.417234     1.0
719  20221206   200000    235959  1670342399  ...    719  0.716348  1.398787     1.0
720  20221207   000000    035959  1670356799  ...    720  1.120770  3.120988     1.0
721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0
722  20221207   080000    115959  1670385599  ...    722  1.084938  2.647182     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-16610.74134876276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17018.14662842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


