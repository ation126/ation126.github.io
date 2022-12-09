# 20221209 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3386
self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17222.2, self.close=17233.3, self.high=17233.3, self.low=17221.3, self.vol=909.061, self.amt=15659564.8381 
127.0.0.1 - - [09/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-09 08:10:01,464:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221209   074500    074959  ...    0.067342   0.211552       0
5854  20221209   075000    075459  ...    0.067153   0.211307       0
5855  20221209   075500    075959  ...    0.066965   0.211065       0
5856  20221209   080000    080459  ...    0.066777   0.210822       0
5857  20221209   080500    080959  ...    0.066588   0.210579       0

[5 rows x 18 columns]
2022-12-09 08:10:01,464:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17222.2, self.close=17233.3, self.high=17233.3, self.low=17221.3, self.vol=909.061, self.amt=15659564.8381, ukdf['pct'].iloc[-1]=0.000645 , ukdf['amount'].iloc[-1]=15659564.8381, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.06658816076017417, signal=0, value_std=0.21057888508402298 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-42357.8864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17233.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3387
self.closeSec=1670544899, self.tradeDate='20221209', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17233.2, self.close=17240.9, self.high=17248.9, self.low=17230.8, self.vol=937.49, self.amt=16160047.516 
127.0.0.1 - - [09/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-09 08:15:00,847:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221209   075000    075459  ...    0.067153   0.211307       0
5855  20221209   075500    075959  ...    0.066965   0.211065       0
5856  20221209   080000    080459  ...    0.066777   0.210822       0
5857  20221209   080500    080959  ...    0.066588   0.210579       0
5858  20221209   081000    081459  ...    0.066400   0.210336       0

[5 rows x 18 columns]
2022-12-09 08:15:00,847:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670544899, self.tradeDate='20221209', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17233.2, self.close=17240.9, self.high=17248.9, self.low=17230.8, self.vol=937.49, self.amt=16160047.516, ukdf['pct'].iloc[-1]=0.000441 , ukdf['amount'].iloc[-1]=16160047.516, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0664000134348719, signal=0, value_std=0.21033556597693012 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-42833.15345243872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17241.09795022', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=16, self.factor=0.43926526577982716, self.count=3952 

self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17222.2, self.close=17233.3, self.high=17233.3, self.low=17221.3 
2022-12-09 08:10:01,429:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17222.2, self.close=17233.3, self.high=17233.3, self.low=17221.3   
2022-12-09 08:10:01,446:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221209   074500    074959  1670543399  ...  17218.1 -0.000609   1533    3
1534  20221209   075000    075459  1670543699  ...  17218.1  0.001475   1534    4
1535  20221209   075500    075959  1670543999  ...  17210.3 -0.001595   1535    5
1536  20221209   080000    080459  1670544299  ...  17211.1  0.000360   1536    0
1537  20221209   080500    080959  1670544599  ...  17221.3  0.000645   1537    1

[5 rows x 11 columns]
2022-12-09 08:10:01,446:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=16, self.factor=0.43926526577982716, self.count=3953 

self.closeSec=1670544899, self.tradeDate='20221209', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17233.2, self.close=17240.9, self.high=17248.9, self.low=17230.8 
2022-12-09 08:15:00,819:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670544899, self.tradeDate='20221209', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17233.2, self.close=17240.9, self.high=17248.9, self.low=17230.8   
2022-12-09 08:15:00,830:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221209   075000    075459  1670543699  ...  17218.1  0.001475   1534    4
1535  20221209   075500    075959  1670543999  ...  17210.3 -0.001595   1535    5
1536  20221209   080000    080459  1670544299  ...  17211.1  0.000360   1536    0
1537  20221209   080500    080959  1670544599  ...  17221.3  0.000645   1537    1
1538  20221209   081000    081459  1670544899  ...  17230.8  0.000441   1538    2

[5 rows x 11 columns]
2022-12-09 08:15:00,830:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-09 08:00:19,380:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221209    052959  17186.3  ...  53.750000  0.625199  0.261068
5771  20221209    055959  17186.5  ...  53.333333  0.618291  0.257385
5772  20221209    062959  17174.6  ...  53.750000  0.622370  0.252647
5773  20221209    065959  17185.9  ...  54.166667  0.625558  0.247209
5774  20221209    072959  17195.0  ...  54.583333  0.630951  0.240412

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2022-12-09 08:00:19,453:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.485937  0.514063       0  ...  1.004210   1.0    0.0  1.039555
537     1  0.485022  0.514978       1  ...  1.004876   1.0    0.0  1.040246
538     1  0.487365  0.512635       1  ...  1.005397   1.0    0.0  1.040784
539     1  0.491878  0.508122       1  ...  1.006280   1.0    0.0  1.041698
540     1  0.496439  0.503561       1  ...  1.006631   1.0    0.0  1.042061

[5 rows x 10 columns]
2022-12-09 08:00:19,467:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484552  0.515448       0  ...  1.004210   1.0    0.0  1.036725
46     1  0.483848  0.516152       1  ...  1.004876   1.0    0.0  1.037620
47     1  0.486924  0.513076       1  ...  1.005397   1.0    0.0  1.040173
48     1  0.491706  0.508294       1  ...  1.006280   1.0    0.0  1.041698
49     1  0.496439  0.503561       1  ...  1.006631   1.0    0.0  1.042061

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '7.5578', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17213', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221209   074000    074959  1670543399  17220.4  17218.1 -0.000139
2022-12-09 07:50:00,549:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1975 

self.closeSec=1670543999, self.tradeDate='20221209', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17218.2', self.close='17214.1'
2022-12-09 08:00:01,334:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670543999, self.tradeDate='20221209', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17218.2', self.close='17214.1'
127.0.0.1 - - [09/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-09 08:00:01,376:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221209   071000    071959  1670541599  17198.9  17234.8  0.002087
620  20221209   072000    072959  1670542199  17234.7    17210 -0.001439
621  20221209   073000    073959  1670542799    17210  17220.5  0.000610
622  20221209   074000    074959  1670543399  17220.4  17218.1 -0.000139
623  20221209   075000    075959  1670543999  17218.2  17214.1 -0.000232
2022-12-09 08:00:01,376:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1976 

self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17216', self.close='17233.3'
2022-12-09 08:10:01,526:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17216', self.close='17233.3'
127.0.0.1 - - [09/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-09 08:10:01,533:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221209   072000    072959  1670542199  17234.7    17210 -0.001439
621  20221209   073000    073959  1670542799    17210  17220.5  0.000610
622  20221209   074000    074959  1670543399  17220.4  17218.1 -0.000139
623  20221209   075000    075959  1670543999  17218.2  17214.1 -0.000232
624  20221209   080000    080959  1670544599    17216  17233.3  0.001115
2022-12-09 08:10:01,533:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221209   074000    074959  1670543399  17220.4  17218.1
2022-12-09 07:50:00,528:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1976 

self.closeSec=1670543999, self.tradeDate='20221209', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17218.2', self.close='17214.1'
127.0.0.1 - - [09/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-09 08:00:01,314:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670543999, self.tradeDate='20221209', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17218.2', self.close='17214.1'
2022-12-09 08:00:01,361:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221209   071000    071959  1670541599  17198.9  17234.8
17468  20221209   072000    072959  1670542199  17234.7    17210
17469  20221209   073000    073959  1670542799    17210  17220.5
17470  20221209   074000    074959  1670543399  17220.4  17218.1
17471  20221209   075000    075959  1670543999  17218.2  17214.1
2022-12-09 08:00:01,361:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1977 

self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17216', self.close='17233.3'
2022-12-09 08:10:01,543:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17216', self.close='17233.3'
2022-12-09 08:10:01,548:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221209   072000    072959  1670542199  17234.7    17210
17469  20221209   073000    073959  1670542799    17210  17220.5
17470  20221209   074000    074959  1670543399  17220.4  17218.1
17471  20221209   075000    075959  1670543999  17218.2  17214.1
17472  20221209   080000    080959  1670544599    17216  17233.3
2022-12-09 08:10:01,549:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221209   074000    074959  1670543399  17220.4  17218.1
2022-12-09 07:50:00,543:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1976 

self.closeSec=1670543999, self.tradeDate='20221209', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17218.2', self.close='17214.1'
127.0.0.1 - - [09/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-09 08:00:01,354:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670543999, self.tradeDate='20221209', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17218.2', self.close='17214.1'
2022-12-09 08:00:01,390:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221209   071000    071959  1670541599  17198.9  17234.8
12140  20221209   072000    072959  1670542199  17234.7    17210
12141  20221209   073000    073959  1670542799    17210  17220.5
12142  20221209   074000    074959  1670543399  17220.4  17218.1
12143  20221209   075000    075959  1670543999  17218.2  17214.1
2022-12-09 08:00:01,390:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1977 

self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17216', self.close='17233.3'
2022-12-09 08:10:01,521:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670544599, self.tradeDate='20221209', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17216', self.close='17233.3'
2022-12-09 08:10:01,531:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221209   072000    072959  1670542199  17234.7    17210
12141  20221209   073000    073959  1670542799    17210  17220.5
12142  20221209   074000    074959  1670543399  17220.4  17218.1
12143  20221209   075000    075959  1670543999  17218.2  17214.1
12144  20221209   080000    080959  1670544599    17216  17233.3
2022-12-09 08:10:01,531:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221208   200000    235959  1670515199  ...    719  0.958119  1.745379     1.0
720  20221209   000000    035959  1670529599  ...    720  0.890290  1.460099     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-3318.0052', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17244.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [09/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=82
self.closeSec=1670543999, self.tradeDate='20221209', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17241.9, self.close=17216.0, self.high=17289.0, self.low=17144.6, self.vol=58532.02, self.amt=1007111691.3332 
2022-12-09 08:00:00,947:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670543999, self.tradeDate='20221209', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17241.9, self.close=17216.0, self.high=17289.0, self.low=17144.6, self.vol=58532.02, self.amt=1007111691.3332 
2022-12-09 08:00:00,983:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20221208   120000    155959  ...   28765.766  4.835081e+08 -0.000529
718  20221208   160000    195959  ...   44048.307  7.401749e+08  0.001499
719  20221208   200000    235959  ...   88430.186  1.491772e+09  0.003907
720  20221209   000000    035959  ...  143901.415  2.463060e+09  0.019766
721  20221209   040000    075959  ...   58532.020  1.007112e+09 -0.001502

[5 rows x 11 columns]
2022-12-09 08:00:01,843:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221208   120000    155959  1670486399  ...    717  0.947182  1.810544     1.0
718  20221208   160000    195959  1670500799  ...    718  0.959713  1.802969     1.0
719  20221208   200000    235959  1670515199  ...    719  0.958119  1.745379     1.0
720  20221209   000000    035959  1670529599  ...    720  0.890290  1.460099     1.0
721  20221209   040000    075959  1670543999  ...    721  0.876128  1.378563     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-5012.181', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17216', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


