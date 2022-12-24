# 20221224 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [24/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7706
self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16780.4, self.close=16782.1, self.high=16782.1, self.low=16780.3, self.vol=174.595, self.amt=2929975.6565 
2022-12-24 08:10:01,499:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221224   074500    074959  ...         0.0        0.0       0
5854  20221224   075000    075459  ...         0.0        0.0       0
5855  20221224   075500    075959  ...         0.0        0.0       0
5856  20221224   080000    080459  ...         0.0        0.0       0
5857  20221224   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 08:10:01,500:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16780.4, self.close=16782.1, self.high=16782.1, self.low=16780.3, self.vol=174.595, self.amt=2929975.6565, ukdf['pct'].iloc[-1]=0.000101 , ukdf['amount'].iloc[-1]=2929975.6565, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15231.1741112408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16782.41044455', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7707
self.closeSec=1671840899, self.tradeDate='20221224', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16782.0, self.close=16795.4, self.high=16795.4, self.low=16782.0, self.vol=399.302, self.amt=6703564.4973 
2022-12-24 08:15:00,585:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221224   075000    075459  ...         0.0        0.0       0
5855  20221224   075500    075959  ...         0.0        0.0       0
5856  20221224   080000    080459  ...         0.0        0.0       0
5857  20221224   080500    080959  ...         0.0        0.0       0
5858  20221224   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 08:15:00,585:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671840899, self.tradeDate='20221224', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16782.0, self.close=16795.4, self.high=16795.4, self.low=16782.0, self.vol=399.302, self.amt=6703564.4973, ukdf['pct'].iloc[-1]=0.000793 , ukdf['amount'].iloc[-1]=6703564.4973, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16024.8688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16795.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16780.4, self.close=16782.1, self.high=16782.1, self.low=16780.3 
2022-12-24 08:10:01,428:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16780.4, self.close=16782.1, self.high=16782.1, self.low=16780.3   
127.0.0.1 - - [24/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-24 08:10:01,450:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221224   074500    074959  1671839399  ...  16768.7 -0.000358   1533    3
1534  20221224   075000    075459  1671839699  ...  16770.6  0.000471   1534    4
1535  20221224   075500    075959  1671839999  ...  16774.8 -0.000161   1535    5
1536  20221224   080000    080459  1671840299  ...  16774.4  0.000238   1536    0
1537  20221224   080500    080959  1671840599  ...  16780.3  0.000101   1537    1

[5 rows x 11 columns]
2022-12-24 08:10:01,450:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=134, self.factor=0.42452581962838826, self.count=8273 

self.closeSec=1671840899, self.tradeDate='20221224', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16782.0, self.close=16795.4, self.high=16795.4, self.low=16782.0 
2022-12-24 08:15:00,541:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671840899, self.tradeDate='20221224', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16782.0, self.close=16795.4, self.high=16795.4, self.low=16782.0   
2022-12-24 08:15:00,576:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221224   075000    075459  1671839699  ...  16770.6  0.000471   1534    4
1535  20221224   075500    075959  1671839999  ...  16774.8 -0.000161   1535    5
1536  20221224   080000    080459  1671840299  ...  16774.4  0.000238   1536    0
1537  20221224   080500    080959  1671840599  ...  16780.3  0.000101   1537    1
1538  20221224   081000    081459  1671840899  ...  16782.0  0.000793   1538    2

[5 rows x 11 columns]
2022-12-24 08:15:00,576:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-24 08:00:19,025:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221224    052959  16802.6  ...  47.916667  0.493718  0.397895
5771  20221224    055959  16794.2  ...  47.916667  0.502324  0.408899
5772  20221224    062959  16808.1  ...  47.500000  0.485542  0.425911
5773  20221224    065959  16780.7  ...  47.916667  0.487908  0.440875
5774  20221224    072959  16784.3  ...  47.916667  0.490171  0.453977

[5 rows x 33 columns]
0.5360443622920518
acc is : 0.5360443622920518
2022-12-24 08:00:19,122:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.490924  0.509076       1  ...  1.098444   1.0    0.0  0.989783
537     1  0.495094  0.504906       0  ...  1.096660   1.0    0.0  0.988175
538     1  0.484063  0.515937       1  ...  1.096902   1.0    0.0  0.988393
539     1  0.493277  0.506723       1  ...  1.097131   1.0    0.0  0.988599
540     1  0.495168  0.504832       0  ...  1.096379   1.0    0.0  0.987922

[5 rows x 10 columns]
2022-12-24 08:00:19,134:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490674  0.509326       1  ...  1.098444   1.0    0.0  0.988712
46     1  0.495104  0.504896       0  ...  1.096660   1.0    0.0  0.987472
47     1  0.484371  0.515629       1  ...  1.096902   1.0    0.0  0.987782
48     1  0.493831  0.506169       1  ...  1.097131   1.0    0.0  0.988599
49     1  0.495168  0.504832       0  ...  1.096379   1.0    0.0  0.987922

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '3124.1536267776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16774.9610992', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221224   074000    074959  1671839399    16779  16771.2 -0.000465
2022-12-24 07:50:00,795:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4135 

self.closeSec=1671839999, self.tradeDate='20221224', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16771.2', self.close='16776.4'
127.0.0.1 - - [24/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-24 08:00:01,503:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671839999, self.tradeDate='20221224', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16771.2', self.close='16776.4'
2022-12-24 08:00:01,517:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221224   071000    071959  1671837599  16783.9  16781.5 -0.000143
620  20221224   072000    072959  1671838199  16781.5    16788  0.000387
621  20221224   073000    073959  1671838799    16788    16779 -0.000536
622  20221224   074000    074959  1671839399    16779  16771.2 -0.000465
623  20221224   075000    075959  1671839999  16771.2  16776.4  0.000310
2022-12-24 08:00:01,518:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4136 

self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16776.3', self.close='16782.1'
2022-12-24 08:10:01,766:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16776.3', self.close='16782.1'
127.0.0.1 - - [24/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-24 08:10:01,804:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221224   072000    072959  1671838199  16781.5    16788  0.000387
621  20221224   073000    073959  1671838799    16788    16779 -0.000536
622  20221224   074000    074959  1671839399    16779  16771.2 -0.000465
623  20221224   075000    075959  1671839999  16771.2  16776.4  0.000310
624  20221224   080000    080959  1671840599  16776.3  16782.1  0.000340
2022-12-24 08:10:01,805:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221224   074000    074959  1671839399    16779  16771.2
2022-12-24 07:50:00,789:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4136 

self.closeSec=1671839999, self.tradeDate='20221224', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16771.2', self.close='16776.4'
2022-12-24 08:00:01,547:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671839999, self.tradeDate='20221224', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16771.2', self.close='16776.4'
2022-12-24 08:00:01,574:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221224   071000    071959  1671837599  16783.9  16781.5
17468  20221224   072000    072959  1671838199  16781.5    16788
17469  20221224   073000    073959  1671838799    16788    16779
17470  20221224   074000    074959  1671839399    16779  16771.2
17471  20221224   075000    075959  1671839999  16771.2  16776.4
2022-12-24 08:00:01,574:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4137 

self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16776.3', self.close='16782.1'
2022-12-24 08:10:01,763:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16776.3', self.close='16782.1'
2022-12-24 08:10:01,810:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221224   072000    072959  1671838199  16781.5    16788
17469  20221224   073000    073959  1671838799    16788    16779
17470  20221224   074000    074959  1671839399    16779  16771.2
17471  20221224   075000    075959  1671839999  16771.2  16776.4
17472  20221224   080000    080959  1671840599  16776.3  16782.1
2022-12-24 08:10:01,810:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221224   074000    074959  1671839399    16779  16771.2
2022-12-24 07:50:00,774:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [24/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4136 

self.closeSec=1671839999, self.tradeDate='20221224', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16771.2', self.close='16776.4'
2022-12-24 08:00:01,538:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671839999, self.tradeDate='20221224', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16771.2', self.close='16776.4'
2022-12-24 08:00:01,573:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221224   071000    071959  1671837599  16783.9  16781.5
12140  20221224   072000    072959  1671838199  16781.5    16788
12141  20221224   073000    073959  1671838799    16788    16779
12142  20221224   074000    074959  1671839399    16779  16771.2
12143  20221224   075000    075959  1671839999  16771.2  16776.4
2022-12-24 08:00:01,573:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4137 

self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16776.3', self.close='16782.1'
2022-12-24 08:10:01,787:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16776.3', self.close='16782.1'
127.0.0.1 - - [24/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-24 08:10:01,808:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221224   072000    072959  1671838199  16781.5    16788
12141  20221224   073000    073959  1671838799    16788    16779
12142  20221224   074000    074959  1671839399    16779  16771.2
12143  20221224   075000    075959  1671839999  16771.2  16776.4
12144  20221224   080000    080959  1671840599  16776.3  16782.1
2022-12-24 08:10:01,808:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [24/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3704
self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16780.4, self.close=16782.1, self.high=16782.1, self.low=16780.3, self.vol=174.595, self.amt=2929975.6565 
2022-12-24 08:10:01,502:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221224   074500    074959  ...         0.0        0.0       0
5854  20221224   075000    075459  ...         0.0        0.0       0
5855  20221224   075500    075959  ...         0.0        0.0       0
5856  20221224   080000    080459  ...         0.0        0.0       0
5857  20221224   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 08:10:01,503:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671840599, self.tradeDate='20221224', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16780.4, self.close=16782.1, self.high=16782.1, self.low=16780.3, self.vol=174.595, self.amt=2929975.6565, ukdf['pct'].iloc[-1]=0.000101 , ukdf['amount'].iloc[-1]=2929975.6565, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--: 127.0.0.1 - - [24/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3705
self.closeSec=1671840899, self.tradeDate='20221224', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16782.0, self.close=16795.4, self.high=16795.4, self.low=16782.0, self.vol=399.302, self.amt=6703564.4973 
2022-12-24 08:15:00,609:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221224   075000    075459  ...         0.0        0.0       0
5855  20221224   075500    075959  ...         0.0        0.0       0
5856  20221224   080000    080459  ...         0.0        0.0       0
5857  20221224   080500    080959  ...         0.0        0.0       0
5858  20221224   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-24 08:15:00,609:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671840899, self.tradeDate='20221224', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16782.0, self.close=16795.4, self.high=16795.4, self.low=16782.0, self.vol=399.302, self.amt=6703564.4973, ukdf['pct'].iloc[-1]=0.000793 , ukdf['amount'].iloc[-1]=6703564.4973, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221223   200000    235959  1671811199  ...    719  0.046037 -1.408536    -1.0
720  20221224   000000    035959  1671825599  ...    720  0.041362 -1.385213    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-6159.1288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16838.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [24/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=172
self.closeSec=1671839999, self.tradeDate='20221224', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16838.5, self.close=16776.4, self.high=16843.0, self.low=16762.5, self.vol=26104.665, self.amt=438450871.6278 
2022-12-24 08:00:01,393:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671839999, self.tradeDate='20221224', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16838.5, self.close=16776.4, self.high=16843.0, self.low=16762.5, self.vol=26104.665, self.amt=438450871.6278 
2022-12-24 08:00:01,423:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20221223   120000    155959  ...   24891.267  4.188321e+08  0.001100
718  20221223   160000    195959  ...   30513.335  5.139140e+08 -0.000273
719  20221223   200000    235959  ...  123957.356  2.086381e+09 -0.000677
720  20221224   000000    035959  ...   18873.526  3.176618e+08  0.000743
721  20221224   040000    075959  ...   26104.665  4.384509e+08 -0.003688

[5 rows x 11 columns]
2022-12-24 08:00:02,755:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221223   120000    155959  1671782399  ...    717  0.044734 -1.484985    -1.0
718  20221223   160000    195959  1671796799  ...    718  0.046008 -1.444387    -1.0
719  20221223   200000    235959  1671811199  ...    719  0.046037 -1.408536    -1.0
720  20221224   000000    035959  1671825599  ...    720  0.041362 -1.385213    -1.0
721  20221224   040000    075959  1671839999  ...    721  0.026274 -1.387503    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-2844.7276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16776.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


