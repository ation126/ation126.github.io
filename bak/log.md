# 20221226 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8282
self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16819.2, self.close=16826.6, self.high=16829.9, self.low=16819.1, self.vol=536.862, self.amt=9033044.154 
127.0.0.1 - - [26/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-26 08:10:01,489:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221226   074500    074959  ...         0.0        0.0       0
5854  20221226   075000    075459  ...         0.0        0.0       0
5855  20221226   075500    075959  ...         0.0        0.0       0
5856  20221226   080000    080459  ...         0.0        0.0       0
5857  20221226   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 08:10:01,489:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16819.2, self.close=16826.6, self.high=16829.9, self.low=16819.1, self.vol=536.862, self.amt=9033044.154, ukdf['pct'].iloc[-1]=0.000446 , ukdf['amount'].iloc[-1]=9033044.154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17918.21165037872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16827.06342147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8283
self.closeSec=1672013699, self.tradeDate='20221226', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16826.7, self.close=16817.0, self.high=16826.7, self.low=16816.5, self.vol=304.795, self.amt=5127336.4466 
2022-12-26 08:15:00,613:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221226   075000    075459  ...         0.0        0.0       0
5855  20221226   075500    075959  ...         0.0        0.0       0
5856  20221226   080000    080459  ...         0.0        0.0       0
5857  20221226   080500    080959  ...         0.0        0.0       0
5858  20221226   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 08:15:00,613:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672013699, self.tradeDate='20221226', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16826.7, self.close=16817.0, self.high=16826.7, self.low=16816.5, self.vol=304.795, self.amt=5127336.4466, ukdf['pct'].iloc[-1]=-0.000571 , ukdf['amount'].iloc[-1]=5127336.4466, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17398.72190604256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16818.43058206', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=230, self.factor=0.5275144677869209, self.count=8848 

self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16819.2, self.close=16826.6, self.high=16829.9, self.low=16819.1 
2022-12-26 08:10:01,410:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16819.2, self.close=16826.6, self.high=16829.9, self.low=16819.1   
2022-12-26 08:10:01,454:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221226   074500    074959  1672012199  ...  16818.0 -0.000059   1533    3
1534  20221226   075000    075459  1672012499  ...  16818.3  0.000309   1534    4
1535  20221226   075500    075959  1672012799  ...  16824.3  0.000000   1535    5
1536  20221226   080000    080459  1672013099  ...  16817.2 -0.000315   1536    0
1537  20221226   080500    080959  1672013399  ...  16819.1  0.000446   1537    1

[5 rows x 11 columns]
2022-12-26 08:10:01,454:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [26/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=230, self.factor=0.5275144677869209, self.count=8849 

self.closeSec=1672013699, self.tradeDate='20221226', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16826.7, self.close=16817.0, self.high=16826.7, self.low=16816.5 
2022-12-26 08:15:00,518:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672013699, self.tradeDate='20221226', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16826.7, self.close=16817.0, self.high=16826.7, self.low=16816.5   
2022-12-26 08:15:00,578:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221226   075000    075459  1672012499  ...  16818.3  0.000309   1534    4
1535  20221226   075500    075959  1672012799  ...  16824.3  0.000000   1535    5
1536  20221226   080000    080459  1672013099  ...  16817.2 -0.000315   1536    0
1537  20221226   080500    080959  1672013399  ...  16819.1  0.000446   1537    1
1538  20221226   081000    081459  1672013699  ...  16816.5 -0.000571   1538    2

[5 rows x 11 columns]
2022-12-26 08:15:00,578:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-26 08:00:22,290:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221226    052959  16760.0  ...  47.916667  0.484410  0.506528
5771  20221226    055959  16793.9  ...  47.916667  0.512572  0.484937
5772  20221226    062959  16823.8  ...  47.500000  0.504538  0.468430
5773  20221226    065959  16814.4  ...  47.500000  0.504144  0.453201
5774  20221226    072959  16813.9  ...  47.083333  0.498689  0.441432

[5 rows x 33 columns]
0.5212569316081331
acc is : 0.5212569316081331
2022-12-26 08:00:22,395:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.505241  0.494759       1  ...  1.072662   1.0    0.0  0.930114
537     0  0.510442  0.489558       0  ...  1.072139   1.0    0.0  0.929661
538     1  0.497475  0.502525       0  ...  1.072114   1.0    0.0  0.929639
539     0  0.501306  0.498694       0  ...  1.071763   1.0    0.0  0.929334
540     1  0.499861  0.500139       1  ...  1.072777   1.0    0.0  0.930214

[5 rows x 10 columns]
2022-12-26 08:00:22,421:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505070  0.494930       1  ...  1.072662   1.0    0.0  0.931752
46     0  0.510259  0.489741       0  ...  1.072139   1.0    0.0  0.927266
47     1  0.497404  0.502596       0  ...  1.072114   1.0    0.0  0.929109
48     0  0.501522  0.498478       0  ...  1.071763   1.0    0.0  0.929334
49     1  0.499861  0.500139       1  ...  1.072777   1.0    0.0  0.930214

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5362.7808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16827.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221226   074000    074959  1672012199  16820.8  16819.2 -0.000101
2022-12-26 07:50:00,566:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4423 

self.closeSec=1672012799, self.tradeDate='20221226', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16819.3', self.close='16824.4'
127.0.0.1 - - [26/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-26 08:00:01,088:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672012799, self.tradeDate='20221226', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16819.3', self.close='16824.4'
2022-12-26 08:00:01,147:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221226   071000    071959  1672010399  16822.8  16817.5 -0.000315
620  20221226   072000    072959  1672010999  16817.4  16808.5 -0.000535
621  20221226   073000    073959  1672011599  16807.1  16820.9  0.000738
622  20221226   074000    074959  1672012199  16820.8  16819.2 -0.000101
623  20221226   075000    075959  1672012799  16819.3  16824.4  0.000309
2022-12-26 08:00:01,147:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4424 

self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16824.5', self.close='16826.6'
2022-12-26 08:10:01,518:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16824.5', self.close='16826.6'
2022-12-26 08:10:01,543:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221226   072000    072959  1672010999  16817.4  16808.5 -0.000535
621  20221226   073000    073959  1672011599  16807.1  16820.9  0.000738
622  20221226   074000    074959  1672012199  16820.8  16819.2 -0.000101
623  20221226   075000    075959  1672012799  16819.3  16824.4  0.000309
624  20221226   080000    080959  1672013399  16824.5  16826.6  0.000131
2022-12-26 08:10:01,544:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221226   074000    074959  1672012199  16820.8  16819.2
2022-12-26 07:50:00,570:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4424 

self.closeSec=1672012799, self.tradeDate='20221226', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16819.3', self.close='16824.4'
127.0.0.1 - - [26/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-26 08:00:01,104:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672012799, self.tradeDate='20221226', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16819.3', self.close='16824.4'
2022-12-26 08:00:01,157:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221226   071000    071959  1672010399  16822.8  16817.5
17468  20221226   072000    072959  1672010999  16817.4  16808.5
17469  20221226   073000    073959  1672011599  16807.1  16820.9
17470  20221226   074000    074959  1672012199  16820.8  16819.2
17471  20221226   075000    075959  1672012799  16819.3  16824.4
2022-12-26 08:00:01,157:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4425 

self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16824.5', self.close='16826.6'
127.0.0.1 - - [26/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-26 08:10:01,552:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16824.5', self.close='16826.6'
2022-12-26 08:10:01,568:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221226   072000    072959  1672010999  16817.4  16808.5
17469  20221226   073000    073959  1672011599  16807.1  16820.9
17470  20221226   074000    074959  1672012199  16820.8  16819.2
17471  20221226   075000    075959  1672012799  16819.3  16824.4
17472  20221226   080000    080959  1672013399  16824.5  16826.6
2022-12-26 08:10:01,568:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221226   074000    074959  1672012199  16820.8  16819.2
2022-12-26 07:50:00,528:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4424 

self.closeSec=1672012799, self.tradeDate='20221226', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16819.3', self.close='16824.4'
127.0.0.1 - - [26/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-26 08:00:01,060:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672012799, self.tradeDate='20221226', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16819.3', self.close='16824.4'
2022-12-26 08:00:01,101:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221226   071000    071959  1672010399  16822.8  16817.5
12140  20221226   072000    072959  1672010999  16817.4  16808.5
12141  20221226   073000    073959  1672011599  16807.1  16820.9
12142  20221226   074000    074959  1672012199  16820.8  16819.2
12143  20221226   075000    075959  1672012799  16819.3  16824.4
2022-12-26 08:00:01,101:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4425 

self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16824.5', self.close='16826.6'
2022-12-26 08:10:01,540:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16824.5', self.close='16826.6'
2022-12-26 08:10:01,566:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221226   072000    072959  1672010999  16817.4  16808.5
12141  20221226   073000    073959  1672011599  16807.1  16820.9
12142  20221226   074000    074959  1672012199  16820.8  16819.2
12143  20221226   075000    075959  1672012799  16819.3  16824.4
12144  20221226   080000    080959  1672013399  16824.5  16826.6
2022-12-26 08:10:01,566:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [26/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4280
self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16819.2, self.close=16826.6, self.high=16829.9, self.low=16819.1, self.vol=536.862, self.amt=9033044.154 
2022-12-26 08:10:01,481:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221226   074500    074959  ...         0.0        0.0       0
5854  20221226   075000    075459  ...         0.0        0.0       0
5855  20221226   075500    075959  ...         0.0        0.0       0
5856  20221226   080000    080459  ...         0.0        0.0       0
5857  20221226   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 08:10:01,481:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672013399, self.tradeDate='20221226', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16819.2, self.close=16826.6, self.high=16829.9, self.low=16819.1, self.vol=536.862, self.amt=9033044.154, ukdf['pct'].iloc[-1]=0.000446 , ukdf['amount'].iloc[-1]=9033044.154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4281
self.closeSec=1672013699, self.tradeDate='20221226', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16826.7, self.close=16817.0, self.high=16826.7, self.low=16816.5, self.vol=304.795, self.amt=5127336.4466 
2022-12-26 08:15:00,618:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221226   075000    075459  ...         0.0        0.0       0
5855  20221226   075500    075959  ...         0.0        0.0       0
5856  20221226   080000    080459  ...         0.0        0.0       0
5857  20221226   080500    080959  ...         0.0        0.0       0
5858  20221226   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 08:15:00,618:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672013699, self.tradeDate='20221226', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16826.7, self.close=16817.0, self.high=16826.7, self.low=16816.5, self.vol=304.795, self.amt=5127336.4466, ukdf['pct'].iloc[-1]=-0.000571 , ukdf['amount'].iloc[-1]=5127336.4466, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221225   200000    235959  1671983999  ...    719  0.004976 -1.162320    -1.0
720  20221226   000000    035959  1671998399  ...    720  0.012552 -1.123865    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-3407.55547405328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16786.94537724', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=184
self.closeSec=1672012799, self.tradeDate='20221226', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16786.6, self.close=16824.4, self.high=16840.2, self.low=16746.0, self.vol=24820.079, self.amt=417010622.8868 
2022-12-26 08:00:00,964:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672012799, self.tradeDate='20221226', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16786.6, self.close=16824.4, self.high=16840.2, self.low=16746.0, self.vol=24820.079, self.amt=417010622.8868 
2022-12-26 08:00:00,981:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221225   120000    155959  ...  13041.653  2.192675e+08 -0.000428
718  20221225   160000    195959  ...  10124.306  1.702797e+08 -0.000113
719  20221225   200000    235959  ...  58570.137  9.834614e+08 -0.001832
720  20221226   000000    035959  ...  29179.332  4.893140e+08  0.000149
721  20221226   040000    075959  ...  24820.079  4.170106e+08  0.002252

[5 rows x 11 columns]
2022-12-26 08:00:02,748:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221225   120000    155959  1671955199  ...    717  0.007733 -1.202113    -1.0
718  20221225   160000    195959  1671969599  ...    718  0.006121 -1.182515    -1.0
719  20221225   200000    235959  1671983999  ...    719  0.004976 -1.162320    -1.0
720  20221226   000000    035959  1671998399  ...    720  0.012552 -1.123865    -1.0
721  20221226   040000    075959  1672012799  ...    721  0.014034 -1.099894    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5500.0970788214', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16826.15210745', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


