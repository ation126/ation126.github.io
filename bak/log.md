# 20221210 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [10/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3674
self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17124.8, self.close=17116.2, self.high=17126.7, self.low=17113.7, self.vol=515.683, self.amt=8828392.132 
2022-12-10 08:10:01,444:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221210   074500    074959  ...    0.017685   0.132150       0
5854  20221210   075000    075459  ...    0.017463   0.131505       0
5855  20221210   075500    075959  ...    0.017241   0.130858       0
5856  20221210   080000    080459  ...    0.017019   0.130211       0
5857  20221210   080500    080959  ...    0.016796   0.129546       0

[5 rows x 18 columns]
2022-12-10 08:10:01,444:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17124.8, self.close=17116.2, self.high=17126.7, self.low=17113.7, self.vol=515.683, self.amt=8828392.132, ukdf['pct'].iloc[-1]=-0.000508 , ukdf['amount'].iloc[-1]=8828392.132, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.016795625133364914, signal=0, value_std=0.12954586658854467 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-35345.28923681248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17116.66521598', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3675
self.closeSec=1670631299, self.tradeDate='20221210', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17116.1, self.close=17120.0, self.high=17120.0, self.low=17112.3, self.vol=282.588, self.amt=4836499.873 
127.0.0.1 - - [10/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-10 08:15:00,559:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221210   075000    075459  ...    0.017463   0.131505       0
5855  20221210   075500    075959  ...    0.017241   0.130858       0
5856  20221210   080000    080459  ...    0.017019   0.130211       0
5857  20221210   080500    080959  ...    0.016796   0.129546       0
5858  20221210   081000    081459  ...    0.016573   0.128886       0

[5 rows x 18 columns]
2022-12-10 08:15:00,560:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670631299, self.tradeDate='20221210', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17116.1, self.close=17120.0, self.high=17120.0, self.low=17112.3, self.vol=282.588, self.amt=4836499.873, ukdf['pct'].iloc[-1]=0.000222 , ukdf['amount'].iloc[-1]=4836499.873, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.016573248353689844, signal=0, value_std=0.12888571238545135 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-35543.5961589872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17119.9606647', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=15, self.factor=0.46780995694827465, self.count=4240 

self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17124.8, self.close=17116.2, self.high=17126.7, self.low=17113.7 
2022-12-10 08:10:01,431:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17124.8, self.close=17116.2, self.high=17126.7, self.low=17113.7   
2022-12-10 08:10:01,443:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221210   074500    074959  1670629799  ...  17114.5 -0.000193   1533    3
1534  20221210   075000    075459  1670630099  ...  17111.7 -0.000823   1534    4
1535  20221210   075500    075959  1670630399  ...  17109.0  0.000503   1535    5
1536  20221210   080000    080459  1670630699  ...  17116.4  0.000263   1536    0
1537  20221210   080500    080959  1670630999  ...  17113.7 -0.000508   1537    1

[5 rows x 11 columns]
2022-12-10 08:10:01,443:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=15, self.factor=0.46780995694827465, self.count=4241 

self.closeSec=1670631299, self.tradeDate='20221210', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17116.1, self.close=17120.0, self.high=17120.0, self.low=17112.3 
2022-12-10 08:15:00,532:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670631299, self.tradeDate='20221210', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17116.1, self.close=17120.0, self.high=17120.0, self.low=17112.3   
2022-12-10 08:15:00,555:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221210   075000    075459  1670630099  ...  17111.7 -0.000823   1534    4
1535  20221210   075500    075959  1670630399  ...  17109.0  0.000503   1535    5
1536  20221210   080000    080459  1670630699  ...  17116.4  0.000263   1536    0
1537  20221210   080500    080959  1670630999  ...  17113.7 -0.000508   1537    1
1538  20221210   081000    081459  1670631299  ...  17112.3  0.000222   1538    2

[5 rows x 11 columns]
2022-12-10 08:15:00,555:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-10 08:00:17,822:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221210    052959  17092.4  ...  54.583333  0.499238  0.567677
5771  20221210    055959  17078.3  ...  54.583333  0.513307  0.585182
5772  20221210    062959  17105.2  ...  55.000000  0.515167  0.600754
5773  20221210    065959  17108.8  ...  55.000000  0.522614  0.612224
5774  20221210    072959  17123.3  ...  55.000000  0.527092  0.621080

[5 rows x 33 columns]
0.5804066543438078
acc is : 0.5804066543438078
2022-12-10 08:00:17,889:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.481616  0.518384       1  ...  0.975092   1.0    0.0  1.053114
537     1  0.492905  0.507095       1  ...  0.975297   1.0    0.0  1.053335
538     1  0.488999  0.511001       1  ...  0.976118   1.0    0.0  1.054222
539     1  0.494514  0.505486       1  ...  0.976614   1.0    0.0  1.054758
540     1  0.497384  0.502616       0  ...  0.976050   1.0    0.0  1.054148

[5 rows x 10 columns]
2022-12-10 08:00:17,900:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.481366  0.518634       1  ...  1.007103   1.0    0.0  1.060018
46     1  0.493073  0.506927       1  ...  1.007315   1.0    0.0  1.063319
47     1  0.488669  0.511331       1  ...  1.008162   1.0    0.0  1.050129
48     1  0.494500  0.505500       1  ...  0.976614   1.0    0.0  1.054758
49     1  0.497384  0.502616       0  ...  0.976050   1.0    0.0  1.054148

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-3540.8293', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17119.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221210   074000    074959  1670629799  17134.8  17125.9 -0.000514
2022-12-10 07:50:00,540:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2119 

self.closeSec=1670630399, self.tradeDate='20221210', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17125.8', self.close='17122'
2022-12-10 08:00:01,114:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670630399, self.tradeDate='20221210', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17125.8', self.close='17122'
2022-12-10 08:00:01,137:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221210   071000    071959  1670627999  17127.9  17126.3 -0.000088
620  20221210   072000    072959  1670628599  17126.3  17131.9  0.000327
621  20221210   073000    073959  1670629199    17132  17134.7  0.000163
622  20221210   074000    074959  1670629799  17134.8  17125.9 -0.000514
623  20221210   075000    075959  1670630399  17125.8    17122 -0.000228
2022-12-10 08:00:01,137:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2120 

self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17122', self.close='17116.1'
2022-12-10 08:10:01,513:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17122', self.close='17116.1'
127.0.0.1 - - [10/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-10 08:10:01,533:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221210   072000    072959  1670628599  17126.3  17131.9  0.000327
621  20221210   073000    073959  1670629199    17132  17134.7  0.000163
622  20221210   074000    074959  1670629799  17134.8  17125.9 -0.000514
623  20221210   075000    075959  1670630399  17125.8    17122 -0.000228
624  20221210   080000    080959  1670630999    17122  17116.1 -0.000345
2022-12-10 08:10:01,533:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221210   074000    074959  1670629799  17134.8  17125.9
2022-12-10 07:50:00,544:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2120 

self.closeSec=1670630399, self.tradeDate='20221210', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17125.8', self.close='17122'
2022-12-10 08:00:01,136:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670630399, self.tradeDate='20221210', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17125.8', self.close='17122'
2022-12-10 08:00:01,150:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221210   071000    071959  1670627999  17127.9  17126.3
17468  20221210   072000    072959  1670628599  17126.3  17131.9
17469  20221210   073000    073959  1670629199    17132  17134.7
17470  20221210   074000    074959  1670629799  17134.8  17125.9
17471  20221210   075000    075959  1670630399  17125.8    17122
2022-12-10 08:00:01,151:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2121 

self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17122', self.close='17116.1'
2022-12-10 08:10:01,516:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17122', self.close='17116.1'
2022-12-10 08:10:01,529:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221210   072000    072959  1670628599  17126.3  17131.9
17469  20221210   073000    073959  1670629199    17132  17134.7
17470  20221210   074000    074959  1670629799  17134.8  17125.9
17471  20221210   075000    075959  1670630399  17125.8    17122
17472  20221210   080000    080959  1670630999    17122  17116.1
2022-12-10 08:10:01,531:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221210   074000    074959  1670629799  17134.8  17125.9
2022-12-10 07:50:00,554:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2120 

self.closeSec=1670630399, self.tradeDate='20221210', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17125.8', self.close='17122'
127.0.0.1 - - [10/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-10 08:00:01,126:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670630399, self.tradeDate='20221210', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17125.8', self.close='17122'
2022-12-10 08:00:01,139:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221210   071000    071959  1670627999  17127.9  17126.3
12140  20221210   072000    072959  1670628599  17126.3  17131.9
12141  20221210   073000    073959  1670629199    17132  17134.7
12142  20221210   074000    074959  1670629799  17134.8  17125.9
12143  20221210   075000    075959  1670630399  17125.8    17122
2022-12-10 08:00:01,140:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2121 

self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17122', self.close='17116.1'
2022-12-10 08:10:01,522:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670630999, self.tradeDate='20221210', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17122', self.close='17116.1'
2022-12-10 08:10:01,528:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221210   072000    072959  1670628599  17126.3  17131.9
12141  20221210   073000    073959  1670629199    17132  17134.7
12142  20221210   074000    074959  1670629799  17134.8  17125.9
12143  20221210   075000    075959  1670630399  17125.8    17122
12144  20221210   080000    080959  1670630999    17122  17116.1
2022-12-10 08:10:01,528:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221209   200000    235959  1670601599  ...    719  0.637512  0.481243     NaN
720  20221210   000000    035959  1670615999  ...    720  0.584356  0.289338     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-9760.563', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17135', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=88
self.closeSec=1670630399, self.tradeDate='20221210', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17135.0, self.close=17122.0, self.high=17149.0, self.low=17052.0, self.vol=31474.007, self.amt=538458537.9635 
127.0.0.1 - - [10/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -
2022-12-10 08:00:00,989:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670630399, self.tradeDate='20221210', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17135.0, self.close=17122.0, self.high=17149.0, self.low=17052.0, self.vol=31474.007, self.amt=538458537.9635 
2022-12-10 08:00:01,012:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20221209   120000    155959  ...   23221.849  3.995087e+08  0.000564
718  20221209   160000    195959  ...   34061.603  5.864694e+08  0.001633
719  20221209   200000    235959  ...  130054.486  2.233482e+09 -0.003563
720  20221210   000000    035959  ...   28838.384  4.944049e+08 -0.002068
721  20221210   040000    075959  ...   31474.007  5.384585e+08 -0.000753

[5 rows x 11 columns]
2022-12-10 08:00:01,790:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221209   120000    155959  1670572799  ...    717  0.723998  0.798378     1.0
718  20221209   160000    195959  1670587199  ...    718  0.613072  0.399523     NaN
719  20221209   200000    235959  1670601599  ...    719  0.637512  0.481243     NaN
720  20221210   000000    035959  1670615999  ...    720  0.584356  0.289338     NaN
721  20221210   040000    075959  1670630399  ...    721  0.608464  0.371435     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-10528.5112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17121.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


