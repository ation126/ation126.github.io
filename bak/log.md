# 20221219 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [19/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6266
self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16735.7, self.close=16720.2, self.high=16735.7, self.low=16708.5, self.vol=1573.008, self.amt=26302114.4316 
2022-12-19 08:10:01,531:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221219   074500    074959  ...         0.0        0.0       0
5854  20221219   075000    075459  ...         0.0        0.0       0
5855  20221219   075500    075959  ...         0.0        0.0       0
5856  20221219   080000    080459  ...         0.0        0.0       0
5857  20221219   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 08:10:01,531:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16735.7, self.close=16720.2, self.high=16735.7, self.low=16708.5, self.vol=1573.008, self.amt=26302114.4316, ukdf['pct'].iloc[-1]=-0.000926 , ukdf['amount'].iloc[-1]=26302114.4316, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-11487.5984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16720.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6267
self.closeSec=1671408899, self.tradeDate='20221219', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16720.1, self.close=16742.0, self.high=16746.9, self.low=16720.1, self.vol=829.074, self.amt=13875675.6353 
127.0.0.1 - - [19/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-19 08:15:00,701:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221219   075000    075459  ...         0.0        0.0       0
5855  20221219   075500    075959  ...         0.0        0.0       0
5856  20221219   080000    080459  ...         0.0        0.0       0
5857  20221219   080500    080959  ...         0.0        0.0       0
5858  20221219   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 08:15:00,701:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671408899, self.tradeDate='20221219', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16720.1, self.close=16742.0, self.high=16746.9, self.low=16720.1, self.vol=829.074, self.amt=13875675.6353, ukdf['pct'].iloc[-1]=0.001304 , ukdf['amount'].iloc[-1]=13875675.6353, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-12799.4352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16742', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16735.7, self.close=16720.2, self.high=16735.7, self.low=16708.5 
2022-12-19 08:10:01,429:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16735.7, self.close=16720.2, self.high=16735.7, self.low=16708.5   
127.0.0.1 - - [19/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 08:10:01,475:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221219   074500    074959  1671407399  ...  16755.7 -0.000501   1533    3
1534  20221219   075000    075459  1671407699  ...  16738.7 -0.001342   1534    4
1535  20221219   075500    075959  1671407999  ...  16722.6 -0.000532   1535    5
1536  20221219   080000    080459  1671408299  ...  16730.3  0.000323   1536    0
1537  20221219   080500    080959  1671408599  ...  16708.5 -0.000926   1537    1

[5 rows x 11 columns]
2022-12-19 08:10:01,478:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=10, self.factor=0.5417946499160612, self.count=6833 

self.closeSec=1671408899, self.tradeDate='20221219', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16720.1, self.close=16742.0, self.high=16746.9, self.low=16720.1 
2022-12-19 08:15:00,544:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671408899, self.tradeDate='20221219', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16720.1, self.close=16742.0, self.high=16746.9, self.low=16720.1   
2022-12-19 08:15:00,598:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221219   075000    075459  1671407699  ...  16738.7 -0.001342   1534    4
1535  20221219   075500    075959  1671407999  ...  16722.6 -0.000532   1535    5
1536  20221219   080000    080459  1671408299  ...  16730.3  0.000323   1536    0
1537  20221219   080500    080959  1671408599  ...  16708.5 -0.000926   1537    1
1538  20221219   081000    081459  1671408899  ...  16720.1  0.001304   1538    2

[5 rows x 11 columns]
2022-12-19 08:15:00,598:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-19 08:00:22,614:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221219    052959  16750.6  ...  47.083333  0.468239  0.511158
5771  20221219    055959  16737.9  ...  47.083333  0.468846  0.503940
5772  20221219    062959  16738.9  ...  47.500000  0.482699  0.486171
5773  20221219    065959  16761.9  ...  47.083333  0.478217  0.490210
5774  20221219    072959  16753.9  ...  47.083333  0.496647  0.484320

[5 rows x 33 columns]
0.55637707948244
acc is : 0.55637707948244
2022-12-19 08:00:22,741:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.497216  0.502784       1  ...  1.104706  -1.0    0.0  0.995735
537     1  0.499811  0.500189       1  ...  1.103188  -1.0    0.0  0.997103
538     0  0.507132  0.492868       0  ...  1.103721  -1.0    0.0  0.996621
539     1  0.498614  0.501386       1  ...  1.101659  -1.0    0.0  0.998483
540     0  0.511054  0.488946       0  ...  1.105262  -1.0    0.0  0.995217

[5 rows x 10 columns]
2022-12-19 08:00:22,776:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497378  0.502622       1  ...  1.104706  -1.0    0.0  0.994646
46     0  0.500413  0.499587       1  ...  1.103188  -1.0    0.0  0.998374
47     0  0.507359  0.492641       0  ...  1.103721  -1.0    0.0  0.997232
48     1  0.498614  0.501386       1  ...  1.101659  -1.0    0.0  0.998483
49     0  0.511054  0.488946       0  ...  1.105262  -1.0    0.0  0.995217

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '38895.4464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16738.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221219   074000    074959  1671407399    16780  16761.7 -0.001091
2022-12-19 07:50:00,639:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3415 

self.closeSec=1671407999, self.tradeDate='20221219', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16761.8', self.close='16730.3'
2022-12-19 08:00:01,427:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671407999, self.tradeDate='20221219', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16761.8', self.close='16730.3'
2022-12-19 08:00:01,510:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221219   071000    071959  1671405599  16788.7  16788.4 -0.000024
620  20221219   072000    072959  1671406199  16788.5  16785.2 -0.000191
621  20221219   073000    073959  1671406799  16785.2    16780 -0.000310
622  20221219   074000    074959  1671407399    16780  16761.7 -0.001091
623  20221219   075000    075959  1671407999  16761.8  16730.3 -0.001873
2022-12-19 08:00:01,510:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3416 

self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16730.4', self.close='16720.2'
2022-12-19 08:10:01,534:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16730.4', self.close='16720.2'
2022-12-19 08:10:01,582:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221219   072000    072959  1671406199  16788.5  16785.2 -0.000191
621  20221219   073000    073959  1671406799  16785.2    16780 -0.000310
622  20221219   074000    074959  1671407399    16780  16761.7 -0.001091
623  20221219   075000    075959  1671407999  16761.8  16730.3 -0.001873
624  20221219   080000    080959  1671408599  16730.4  16720.2 -0.000604
2022-12-19 08:10:01,583:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221219   074000    074959  1671407399    16780  16761.7
2022-12-19 07:50:00,634:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3416 

self.closeSec=1671407999, self.tradeDate='20221219', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16761.8', self.close='16730.3'
127.0.0.1 - - [19/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-19 08:00:01,395:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671407999, self.tradeDate='20221219', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16761.8', self.close='16730.3'
2022-12-19 08:00:01,502:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221219   071000    071959  1671405599  16788.7  16788.4
17468  20221219   072000    072959  1671406199  16788.5  16785.2
17469  20221219   073000    073959  1671406799  16785.2    16780
17470  20221219   074000    074959  1671407399    16780  16761.7
17471  20221219   075000    075959  1671407999  16761.8  16730.3
2022-12-19 08:00:01,502:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3417 

self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16730.4', self.close='16720.2'
2022-12-19 08:10:01,562:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16730.4', self.close='16720.2'
127.0.0.1 - - [19/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 08:10:01,593:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221219   072000    072959  1671406199  16788.5  16785.2
17469  20221219   073000    073959  1671406799  16785.2    16780
17470  20221219   074000    074959  1671407399    16780  16761.7
17471  20221219   075000    075959  1671407999  16761.8  16730.3
17472  20221219   080000    080959  1671408599  16730.4  16720.2
2022-12-19 08:10:01,593:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221219   074000    074959  1671407399    16780  16761.7
2022-12-19 07:50:00,625:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3416 

self.closeSec=1671407999, self.tradeDate='20221219', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16761.8', self.close='16730.3'
2022-12-19 08:00:01,451:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671407999, self.tradeDate='20221219', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16761.8', self.close='16730.3'
2022-12-19 08:00:01,521:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221219   071000    071959  1671405599  16788.7  16788.4
12140  20221219   072000    072959  1671406199  16788.5  16785.2
12141  20221219   073000    073959  1671406799  16785.2    16780
12142  20221219   074000    074959  1671407399    16780  16761.7
12143  20221219   075000    075959  1671407999  16761.8  16730.3
2022-12-19 08:00:01,521:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3417 

self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16730.4', self.close='16720.2'
127.0.0.1 - - [19/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 08:10:01,565:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16730.4', self.close='16720.2'
2022-12-19 08:10:01,594:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221219   072000    072959  1671406199  16788.5  16785.2
12141  20221219   073000    073959  1671406799  16785.2    16780
12142  20221219   074000    074959  1671407399    16780  16761.7
12143  20221219   075000    075959  1671407999  16761.8  16730.3
12144  20221219   080000    080959  1671408599  16730.4  16720.2
2022-12-19 08:10:01,594:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2264
self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16735.7, self.close=16720.2, self.high=16735.7, self.low=16708.5, self.vol=1573.008, self.amt=26302114.4316 
127.0.0.1 - - [19/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 08:10:01,522:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221219   074500    074959  ...         0.0        0.0       0
5854  20221219   075000    075459  ...         0.0        0.0       0
5855  20221219   075500    075959  ...         0.0        0.0       0
5856  20221219   080000    080459  ...         0.0        0.0       0
5857  20221219   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 08:10:01,522:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671408599, self.tradeDate='20221219', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16735.7, self.close=16720.2, self.high=16735.7, self.low=16708.5, self.vol=1573.008, self.amt=26302114.4316, ukdf['pct'].iloc[-1]=-0.000926 , ukdf['amount'].iloc[-1]=26302114.4316, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2265
self.closeSec=1671408899, self.tradeDate='20221219', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16720.1, self.close=16742.0, self.high=16746.9, self.low=16720.1, self.vol=829.074, self.amt=13875675.6353 
2022-12-19 08:15:00,700:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221219   075000    075459  ...         0.0        0.0       0
5855  20221219   075500    075959  ...         0.0        0.0       0
5856  20221219   080000    080459  ...         0.0        0.0       0
5857  20221219   080500    080959  ...         0.0        0.0       0
5858  20221219   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 08:15:00,702:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671408899, self.tradeDate='20221219', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16720.1, self.close=16742.0, self.high=16746.9, self.low=16720.1, self.vol=829.074, self.amt=13875675.6353, ukdf['pct'].iloc[-1]=0.001304 , ukdf['amount'].iloc[-1]=13875675.6353, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221218   200000    235959  1671379199  ...    719  1.132630  1.292668     1.0
720  20221219   000000    035959  1671393599  ...    720  1.127079  1.248861     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-54007.7652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16745.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [19/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=142
self.closeSec=1671407999, self.tradeDate='20221219', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16745.7, self.close=16730.3, self.high=16872.0, self.low=16715.1, self.vol=37334.568, self.amt=626197515.6605 
2022-12-19 08:00:01,248:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671407999, self.tradeDate='20221219', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16745.7, self.close=16730.3, self.high=16872.0, self.low=16715.1, self.vol=37334.568, self.amt=626197515.6605 
2022-12-19 08:00:01,302:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221218   120000    155959  ...  26928.603  4.510137e+08  0.000203
718  20221218   160000    195959  ...  35341.001  5.903013e+08 -0.002252
719  20221218   200000    235959  ...  25280.386  4.220179e+08 -0.001545
720  20221219   000000    035959  ...  41996.189  7.028551e+08  0.004150
721  20221219   040000    075959  ...  37334.568  6.261975e+08 -0.000914

[5 rows x 11 columns]
2022-12-19 08:00:02,670:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221218   120000    155959  1671350399  ...    717  1.003667  0.955392     1.0
718  20221218   160000    195959  1671364799  ...    718  1.060150  1.102955     1.0
719  20221218   200000    235959  1671379199  ...    719  1.132630  1.292668     1.0
720  20221219   000000    035959  1671393599  ...    720  1.127079  1.248861     1.0
721  20221219   040000    075959  1671407999  ...    721  0.986301  0.804651     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-54825.336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16730.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


