# 20230123 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16346
self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22714.4, self.close=22727.5, self.high=22744.2, self.low=22708.8, self.vol=1323.731, self.amt=30083555.4469 
127.0.0.1 - - [23/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-23 08:10:01,488:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230123   074500    074959  ...         0.0        0.0       0
5854  20230123   075000    075459  ...         0.0        0.0       0
5855  20230123   075500    075959  ...         0.0        0.0       0
5856  20230123   080000    080459  ...         0.0        0.0       0
5857  20230123   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 08:10:01,488:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22714.4, self.close=22727.5, self.high=22744.2, self.low=22708.8, self.vol=1323.731, self.amt=30083555.4469, ukdf['pct'].iloc[-1]=0.000577 , ukdf['amount'].iloc[-1]=30083555.4469, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-373103.76009960224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22729.50872274', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16347
self.closeSec=1674432899, self.tradeDate='20230123', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22727.4, self.close=22682.3, self.high=22731.5, self.low=22664.0, self.vol=1966.615, self.amt=44620782.0217 
2023-01-23 08:15:00,879:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230123   075000    075459  ...         0.0        0.0       0
5855  20230123   075500    075959  ...         0.0        0.0       0
5856  20230123   080000    080459  ...         0.0        0.0       0
5857  20230123   080500    080959  ...         0.0        0.0       0
5858  20230123   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 08:15:00,881:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674432899, self.tradeDate='20230123', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22727.4, self.close=22682.3, self.high=22731.5, self.low=22664.0, self.vol=1966.615, self.amt=44620782.0217, ukdf['pct'].iloc[-1]=-0.001989 , ukdf['amount'].iloc[-1]=44620782.0217, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-370256.9104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22682.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22714.4, self.close=22727.5, self.high=22744.2, self.low=22708.8 
2023-01-23 08:10:01,413:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22714.4, self.close=22727.5, self.high=22744.2, self.low=22708.8   
127.0.0.1 - - [23/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-23 08:10:01,468:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230123   074500    074959  1674431399  ...  22695.6 -0.001127   1533    3
1534  20230123   075000    075459  1674431699  ...  22685.2  0.001062   1534    4
1535  20230123   075500    075959  1674431999  ...  22696.0 -0.000744   1535    5
1536  20230123   080000    080459  1674432299  ...  22678.7  0.000396   1536    0
1537  20230123   080500    080959  1674432599  ...  22708.8  0.000577   1537    1

[5 rows x 11 columns]
2023-01-23 08:10:01,469:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=109, self.factor=0.55431665818945, self.count=16913 

self.closeSec=1674432899, self.tradeDate='20230123', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22727.4, self.close=22682.3, self.high=22731.5, self.low=22664.0 
2023-01-23 08:15:00,808:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674432899, self.tradeDate='20230123', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22727.4, self.close=22682.3, self.high=22731.5, self.low=22664.0   
2023-01-23 08:15:00,837:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230123   075000    075459  1674431699  ...  22685.2  0.001062   1534    4
1535  20230123   075500    075959  1674431999  ...  22696.0 -0.000744   1535    5
1536  20230123   080000    080459  1674432299  ...  22678.7  0.000396   1536    0
1537  20230123   080500    080959  1674432599  ...  22708.8  0.000577   1537    1
1538  20230123   081000    081459  1674432899  ...  22664.0 -0.001989   1538    2

[5 rows x 11 columns]
2023-01-23 08:15:00,837:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-23 08:00:18,121:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230123    052959  22464.3  ...  53.750000  0.474573  0.632310
5771  20230123    055959  22444.2  ...  54.166667  0.498966  0.631835
5772  20230123    062959  22584.3  ...  54.166667  0.495831  0.632964
5773  20230123    065959  22565.7  ...  54.583333  0.513946  0.624881
5774  20230123    072959  22674.1  ...  55.000000  0.515270  0.616656

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2023-01-23 08:00:18,205:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.460515  0.539485       1  ...  1.100701  -1.0    0.0  1.299554
537     0  0.506735  0.493265       0  ...  1.101612  -1.0    0.0  1.298478
538     1  0.487808  0.512192       1  ...  1.096305  -1.0    0.0  1.304733
539     0  0.538740  0.461260       1  ...  1.095914  -1.0    0.0  1.305199
540     0  0.534395  0.465605       1  ...  1.094803  -1.0    0.0  1.306522

[5 rows x 10 columns]
2023-01-23 08:00:18,231:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.460846  0.539154       1  ...  1.100701  -1.0    0.0  1.303545
46     0  0.506685  0.493315       0  ...  1.101612  -1.0    0.0  1.300289
47     1  0.487865  0.512135       1  ...  1.096305  -1.0    0.0  1.307637
48     0  0.538740  0.461260       1  ...  1.095914  -1.0    0.0  1.305199
49     0  0.534395  0.465605       1  ...  1.094803  -1.0    0.0  1.306522

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.678', 'enterprice': '22437.6', 'countrevence': '0', 'unrealprofit': '-8820.16303269906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22699.49687727', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230123   074000    074959  1674431399  22727.1  22698.2 -0.001272
2023-01-23 07:50:00,812:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8455 

self.closeSec=1674431999, self.tradeDate='20230123', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22698.3', self.close='22705.4'
127.0.0.1 - - [23/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-23 08:00:01,699:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674431999, self.tradeDate='20230123', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22698.3', self.close='22705.4'
2023-01-23 08:00:01,728:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230123   071000    071959  1674429599  22739.7  22687.3 -0.002309
620  20230123   072000    072959  1674430199  22687.3  22682.4 -0.000216
621  20230123   073000    073959  1674430799  22682.4  22727.1  0.001971
622  20230123   074000    074959  1674431399  22727.1  22698.2 -0.001272
623  20230123   075000    075959  1674431999  22698.3  22705.4  0.000317
2023-01-23 08:00:01,728:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8456 

self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22704.7', self.close='22727.5'
2023-01-23 08:10:01,549:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22704.7', self.close='22727.5'
127.0.0.1 - - [23/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-23 08:10:01,555:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230123   072000    072959  1674430199  22687.3  22682.4 -0.000216
621  20230123   073000    073959  1674430799  22682.4  22727.1  0.001971
622  20230123   074000    074959  1674431399  22727.1  22698.2 -0.001272
623  20230123   075000    075959  1674431999  22698.3  22705.4  0.000317
624  20230123   080000    080959  1674432599  22704.7  22727.5  0.000973
2023-01-23 08:10:01,562:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230123   074000    074959  1674431399  22727.1  22698.2
2023-01-23 07:50:00,777:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8456 

self.closeSec=1674431999, self.tradeDate='20230123', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22698.3', self.close='22705.4'
2023-01-23 08:00:01,727:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674431999, self.tradeDate='20230123', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22698.3', self.close='22705.4'
127.0.0.1 - - [23/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-23 08:00:01,770:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230123   071000    071959  1674429599  22739.7  22687.3
17468  20230123   072000    072959  1674430199  22687.3  22682.4
17469  20230123   073000    073959  1674430799  22682.4  22727.1
17470  20230123   074000    074959  1674431399  22727.1  22698.2
17471  20230123   075000    075959  1674431999  22698.3  22705.4
2023-01-23 08:00:01,771:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8457 

self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22704.7', self.close='22727.5'
2023-01-23 08:10:01,531:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22704.7', self.close='22727.5'
2023-01-23 08:10:01,536:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230123   072000    072959  1674430199  22687.3  22682.4
17469  20230123   073000    073959  1674430799  22682.4  22727.1
17470  20230123   074000    074959  1674431399  22727.1  22698.2
17471  20230123   075000    075959  1674431999  22698.3  22705.4
17472  20230123   080000    080959  1674432599  22704.7  22727.5
2023-01-23 08:10:01,536:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230123   074000    074959  1674431399  22727.1  22698.2
2023-01-23 07:50:00,815:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8456 

self.closeSec=1674431999, self.tradeDate='20230123', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22698.3', self.close='22705.4'
2023-01-23 08:00:01,709:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674431999, self.tradeDate='20230123', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22698.3', self.close='22705.4'
127.0.0.1 - - [23/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-23 08:00:01,735:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230123   071000    071959  1674429599  22739.7  22687.3
12140  20230123   072000    072959  1674430199  22687.3  22682.4
12141  20230123   073000    073959  1674430799  22682.4  22727.1
12142  20230123   074000    074959  1674431399  22727.1  22698.2
12143  20230123   075000    075959  1674431999  22698.3  22705.4
2023-01-23 08:00:01,735:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [23/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8457 

self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22704.7', self.close='22727.5'
2023-01-23 08:10:01,525:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22704.7', self.close='22727.5'
2023-01-23 08:10:01,543:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230123   072000    072959  1674430199  22687.3  22682.4
12141  20230123   073000    073959  1674430799  22682.4  22727.1
12142  20230123   074000    074959  1674431399  22727.1  22698.2
12143  20230123   075000    075959  1674431999  22698.3  22705.4
12144  20230123   080000    080959  1674432599  22704.7  22727.5
2023-01-23 08:10:01,543:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [23/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12344
self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22714.4, self.close=22727.5, self.high=22744.2, self.low=22708.8, self.vol=1323.731, self.amt=30083555.4469 
2023-01-23 08:10:01,487:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230123   074500    074959  ...         0.0        0.0       0
5854  20230123   075000    075459  ...         0.0        0.0       0
5855  20230123   075500    075959  ...         0.0        0.0       0
5856  20230123   080000    080459  ...         0.0        0.0       0
5857  20230123   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 08:10:01,489:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674432599, self.tradeDate='20230123', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22714.4, self.close=22727.5, self.high=22744.2, self.low=22708.8, self.vol=1323.731, self.amt=30083555.4469, ukdf['pct'].iloc[-1]=0.000577 , ukdf['amount'].iloc[-1]=30083555.4469, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [23/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12345
self.closeSec=1674432899, self.tradeDate='20230123', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22727.4, self.close=22682.3, self.high=22731.5, self.low=22664.0, self.vol=1966.615, self.amt=44620782.0217 
2023-01-23 08:15:00,848:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230123   075000    075459  ...         0.0        0.0       0
5855  20230123   075500    075959  ...         0.0        0.0       0
5856  20230123   080000    080459  ...         0.0        0.0       0
5857  20230123   080500    080959  ...         0.0        0.0       0
5858  20230123   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 08:15:00,849:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674432899, self.tradeDate='20230123', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22727.4, self.close=22682.3, self.high=22731.5, self.low=22664.0, self.vol=1966.615, self.amt=44620782.0217, ukdf['pct'].iloc[-1]=-0.001989 , ukdf['amount'].iloc[-1]=44620782.0217, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230122   200000    235959  1674403199  ...    719  0.986552  0.464280     NaN
720  20230123   000000    035959  1674417599  ...    720  1.022171  0.530393     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-23445.0591', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22723.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [23/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=972283.0195242, self.flagDict['side']='buy', self.tradeCount=14, self.count=352
self.closeSec=1674431999, self.tradeDate='20230123', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22720.0, self.close=22705.4, self.high=22770.0, self.low=22287.0, self.vol=139693.559, self.amt=3148396928.64876 
2023-01-23 08:00:01,520:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674431999, self.tradeDate='20230123', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22720.0, self.close=22705.4, self.high=22770.0, self.low=22287.0, self.vol=139693.559, self.amt=3148396928.64876 
2023-01-23 08:00:01,553:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230122   120000    155959  ...   41651.721  9.528983e+08  0.005583
718  20230122   160000    195959  ...   45035.486  1.028832e+09 -0.004704
719  20230122   200000    235959  ...  106357.240  2.431628e+09  0.000325
720  20230123   000000    035959  ...   72710.666  1.660094e+09 -0.003198
721  20230123   040000    075959  ...  139693.559  3.148397e+09 -0.000643

[5 rows x 11 columns]
2023-01-23 08:00:02,764:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230122   120000    155959  1674374399  ...    717  1.019065  0.565618     NaN
718  20230122   160000    195959  1674388799  ...    718  0.986795  0.478925     NaN
719  20230122   200000    235959  1674403199  ...    719  0.986552  0.464280     NaN
720  20230123   000000    035959  1674417599  ...    720  1.022171  0.530393     NaN
721  20230123   040000    075959  1674431999  ...    721  1.092073  0.673076     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-24218.2901820462', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22704.8012062', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


