# 20221218 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5978
self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16752.9, self.close=16747.7, self.high=16756.5, self.low=16742.8, self.vol=721.212, self.amt=12080207.194 
127.0.0.1 - - [18/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-18 08:10:01,497:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221218   074500    074959  ...         0.0        0.0       0
5854  20221218   075000    075459  ...         0.0        0.0       0
5855  20221218   075500    075959  ...         0.0        0.0       0
5856  20221218   080000    080459  ...         0.0        0.0       0
5857  20221218   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-18 08:10:01,497:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16752.9, self.close=16747.7, self.high=16756.5, self.low=16742.8, self.vol=721.212, self.amt=12080207.194, ukdf['pct'].iloc[-1]=-0.000316 , ukdf['amount'].iloc[-1]=12080207.194, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-13161.24677406832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16748.01255607', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5979
self.closeSec=1671322499, self.tradeDate='20221218', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16747.8, self.close=16739.8, self.high=16748.3, self.low=16731.3, self.vol=969.158, self.amt=16223039.749 
127.0.0.1 - - [18/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-18 08:15:00,603:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221218   075000    075459  ...         0.0        0.0       0
5855  20221218   075500    075959  ...         0.0        0.0       0
5856  20221218   080000    080459  ...         0.0        0.0       0
5857  20221218   080500    080959  ...         0.0        0.0       0
5858  20221218   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-18 08:15:00,603:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671322499, self.tradeDate='20221218', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16747.8, self.close=16739.8, self.high=16748.3, self.low=16731.3, self.vol=969.158, self.amt=16223039.749, ukdf['pct'].iloc[-1]=-0.000472 , ukdf['amount'].iloc[-1]=16223039.749, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-12667.048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16739.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6378355658310518, self.count=6544 

self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16752.9, self.close=16747.7, self.high=16756.5, self.low=16742.8 
2022-12-18 08:10:01,441:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16752.9, self.close=16747.7, self.high=16756.5, self.low=16742.8   
2022-12-18 08:10:01,495:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221218   074500    074959  1671320999  ...  16753.4  0.000758   1533    3
1534  20221218   075000    075459  1671321299  ...  16773.7  0.000215   1534    4
1535  20221218   075500    075959  1671321599  ...  16766.8 -0.000691   1535    5
1536  20221218   080000    080459  1671321899  ...  16753.0 -0.000895   1536    0
1537  20221218   080500    080959  1671322199  ...  16742.8 -0.000316   1537    1

[5 rows x 11 columns]
2022-12-18 08:10:01,495:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6378355658310518, self.count=6545 

self.closeSec=1671322499, self.tradeDate='20221218', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16747.8, self.close=16739.8, self.high=16748.3, self.low=16731.3 
2022-12-18 08:15:00,525:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671322499, self.tradeDate='20221218', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16747.8, self.close=16739.8, self.high=16748.3, self.low=16731.3   
2022-12-18 08:15:00,556:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221218   075000    075459  1671321299  ...  16773.7  0.000215   1534    4
1535  20221218   075500    075959  1671321599  ...  16766.8 -0.000691   1535    5
1536  20221218   080000    080459  1671321899  ...  16753.0 -0.000895   1536    0
1537  20221218   080500    080959  1671322199  ...  16742.8 -0.000316   1537    1
1538  20221218   081000    081459  1671322499  ...  16731.3 -0.000472   1538    2

[5 rows x 11 columns]
2022-12-18 08:15:00,556:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-18 08:00:19,165:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221218    052959  16692.6  ...  46.666667  0.418083  0.554451
5771  20221218    055959  16700.1  ...  47.083333  0.419989  0.538195
5772  20221218    062959  16704.4  ...  47.500000  0.420304  0.524791
5773  20221218    065959  16704.9  ...  47.916667  0.432580  0.505950
5774  20221218    072959  16732.4  ...  47.916667  0.443072  0.486624

[5 rows x 33 columns]
0.5526802218114603
acc is : 0.5526802218114603
2022-12-18 08:00:19,251:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.506298  0.493702       1  ...  1.077232  -1.0    0.0  0.984749
537     0  0.506355  0.493645       1  ...  1.077187  -1.0    0.0  0.984790
538     0  0.505338  0.494662       1  ...  1.075427  -1.0    0.0  0.986400
539     0  0.513971  0.486029       1  ...  1.073897  -1.0    0.0  0.987803
540     0  0.514510  0.485490       1  ...  1.073134  -1.0    0.0  0.988504

[5 rows x 10 columns]
2022-12-18 08:00:19,262:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505992  0.494008       1  ...  1.077232  -1.0    0.0  0.984059
46     0  0.505938  0.494062       1  ...  1.077187  -1.0    0.0  0.982763
47     0  0.505261  0.494739       1  ...  1.075427  -1.0    0.0  0.985581
48     0  0.514110  0.485890       1  ...  1.073897  -1.0    0.0  0.987803
49     0  0.514510  0.485490       1  ...  1.073134  -1.0    0.0  0.988504

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '37714.86965863608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16769.71171073', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221218   074000    074959  1671320999  16749.7  16776.1  0.001582
2022-12-18 07:50:00,583:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3271 

self.closeSec=1671321599, self.tradeDate='20221218', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16776.1', self.close='16768'
2022-12-18 08:00:01,198:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671321599, self.tradeDate='20221218', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16776.1', self.close='16768'
2022-12-18 08:00:01,240:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221218   071000    071959  1671319199  16756.3    16749 -0.000436
620  20221218   072000    072959  1671319799    16749  16756.2  0.000430
621  20221218   073000    073959  1671320399  16756.2  16749.6 -0.000394
622  20221218   074000    074959  1671320999  16749.7  16776.1  0.001582
623  20221218   075000    075959  1671321599  16776.1    16768 -0.000483
2022-12-18 08:00:01,241:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3272 

self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16768.1', self.close='16747.7'
2022-12-18 08:10:01,508:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16768.1', self.close='16747.7'
2022-12-18 08:10:01,554:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221218   072000    072959  1671319799    16749  16756.2  0.000430
621  20221218   073000    073959  1671320399  16756.2  16749.6 -0.000394
622  20221218   074000    074959  1671320999  16749.7  16776.1  0.001582
623  20221218   075000    075959  1671321599  16776.1    16768 -0.000483
624  20221218   080000    080959  1671322199  16768.1  16747.7 -0.001211
2022-12-18 08:10:01,555:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221218   074000    074959  1671320999  16749.7  16776.1
2022-12-18 07:50:00,567:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3272 

self.closeSec=1671321599, self.tradeDate='20221218', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16776.1', self.close='16768'
127.0.0.1 - - [18/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-18 08:00:01,220:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671321599, self.tradeDate='20221218', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16776.1', self.close='16768'
2022-12-18 08:00:01,266:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221218   071000    071959  1671319199  16756.3    16749
17468  20221218   072000    072959  1671319799    16749  16756.2
17469  20221218   073000    073959  1671320399  16756.2  16749.6
17470  20221218   074000    074959  1671320999  16749.7  16776.1
17471  20221218   075000    075959  1671321599  16776.1    16768
2022-12-18 08:00:01,266:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3273 

self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16768.1', self.close='16747.7'
2022-12-18 08:10:01,525:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16768.1', self.close='16747.7'
2022-12-18 08:10:01,534:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221218   072000    072959  1671319799    16749  16756.2
17469  20221218   073000    073959  1671320399  16756.2  16749.6
17470  20221218   074000    074959  1671320999  16749.7  16776.1
17471  20221218   075000    075959  1671321599  16776.1    16768
17472  20221218   080000    080959  1671322199  16768.1  16747.7
2022-12-18 08:10:01,534:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221218   074000    074959  1671320999  16749.7  16776.1
2022-12-18 07:50:00,553:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3272 

self.closeSec=1671321599, self.tradeDate='20221218', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16776.1', self.close='16768'
2022-12-18 08:00:01,211:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671321599, self.tradeDate='20221218', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16776.1', self.close='16768'
2022-12-18 08:00:01,247:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221218   071000    071959  1671319199  16756.3    16749
12140  20221218   072000    072959  1671319799    16749  16756.2
12141  20221218   073000    073959  1671320399  16756.2  16749.6
12142  20221218   074000    074959  1671320999  16749.7  16776.1
12143  20221218   075000    075959  1671321599  16776.1    16768
2022-12-18 08:00:01,247:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3273 

self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16768.1', self.close='16747.7'
127.0.0.1 - - [18/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-18 08:10:01,558:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16768.1', self.close='16747.7'
2022-12-18 08:10:01,564:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221218   072000    072959  1671319799    16749  16756.2
12141  20221218   073000    073959  1671320399  16756.2  16749.6
12142  20221218   074000    074959  1671320999  16749.7  16776.1
12143  20221218   075000    075959  1671321599  16776.1    16768
12144  20221218   080000    080959  1671322199  16768.1  16747.7
2022-12-18 08:10:01,565:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1976
self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16752.9, self.close=16747.7, self.high=16756.5, self.low=16742.8, self.vol=721.212, self.amt=12080207.194 
2022-12-18 08:10:01,485:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221218   074500    074959  ...    0.054300   0.202596       0
5854  20221218   075000    075459  ...    0.053975   0.202180       0
5855  20221218   075500    075959  ...    0.053646   0.201756       0
5856  20221218   080000    080459  ...    0.053311   0.201309       0
5857  20221218   080500    080959  ...    0.052974   0.200855       0

[5 rows x 18 columns]
2022-12-18 08:10:01,488:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671322199, self.tradeDate='20221218', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16752.9, self.close=16747.7, self.high=16756.5, self.low=16742.8, self.vol=721.212, self.amt=12080207.194, ukdf['pct'].iloc[-1]=-0.000316 , ukdf['amount'].iloc[-1]=12080207.194, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.05297352957540572, signal=0, value_std=0.20085462093162318 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1977
self.closeSec=1671322499, self.tradeDate='20221218', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16747.8, self.close=16739.8, self.high=16748.3, self.low=16731.3, self.vol=969.158, self.amt=16223039.749 
127.0.0.1 - - [18/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-18 08:15:00,590:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221218   075000    075459  ...    0.053975   0.202180       0
5855  20221218   075500    075959  ...    0.053646   0.201756       0
5856  20221218   080000    080459  ...    0.053311   0.201309       0
5857  20221218   080500    080959  ...    0.052974   0.200855       0
5858  20221218   081000    081459  ...    0.052636   0.200397       0

[5 rows x 18 columns]
2022-12-18 08:15:00,593:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671322499, self.tradeDate='20221218', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16747.8, self.close=16739.8, self.high=16748.3, self.low=16731.3, self.vol=969.158, self.amt=16223039.749, ukdf['pct'].iloc[-1]=-0.000472 , ukdf['amount'].iloc[-1]=16223039.749, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.05263557596239386, signal=0, value_std=0.20039705948650488 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221217   200000    235959  1671292799  ...    719  0.839180  0.506705     NaN
720  20221218   000000    035959  1671307199  ...    720  0.894041  0.665375     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-57294.0792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16684.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=136
self.closeSec=1671321599, self.tradeDate='20221218', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16684.1, self.close=16768.0, self.high=16790.0, self.low=16677.4, self.vol=33778.374, self.amt=565073099.1908 
127.0.0.1 - - [18/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-18 08:00:01,072:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671321599, self.tradeDate='20221218', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16684.1, self.close=16768.0, self.high=16790.0, self.low=16677.4, self.vol=33778.374, self.amt=565073099.1908 
2022-12-18 08:00:01,103:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221217   120000    155959  ...  45721.150  7.635974e+08  0.004230
718  20221217   160000    195959  ...  37850.072  6.323066e+08 -0.002234
719  20221217   200000    235959  ...  40968.291  6.830872e+08 -0.000491
720  20221218   000000    035959  ...  23775.354  3.965878e+08 -0.000491
721  20221218   040000    075959  ...  33778.374  5.650731e+08  0.005023

[5 rows x 11 columns]
2022-12-18 08:00:02,647:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221217   120000    155959  1671263999  ...    717  0.729073  0.174966     NaN
718  20221217   160000    195959  1671278399  ...    718  0.776478  0.319181     NaN
719  20221217   200000    235959  1671292799  ...    719  0.839180  0.506705     NaN
720  20221218   000000    035959  1671307199  ...    720  0.894041  0.665375     1.0
721  20221218   040000    075959  1671321599  ...    721  0.914646  0.718202     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-52738.08088536192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16769.36084128', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


