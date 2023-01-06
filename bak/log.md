# 20230106 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [06/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11450
self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16821.6, self.close=16825.6, self.high=16828.0, self.low=16819.3, self.vol=422.815, self.amt=7113228.2202 
2023-01-06 08:10:01,513:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230106   074500    074959  ...         0.0        0.0       0
5854  20230106   075000    075459  ...         0.0        0.0       0
5855  20230106   075500    075959  ...         0.0        0.0       0
5856  20230106   080000    080459  ...         0.0        0.0       0
5857  20230106   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 08:10:01,513:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16821.6, self.close=16825.6, self.high=16828.0, self.low=16819.3, self.vol=422.815, self.amt=7113228.2202, ukdf['pct'].iloc[-1]=0.000238 , ukdf['amount'].iloc[-1]=7113228.2202, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17853.2486303224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16825.98387115', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11451
self.closeSec=1672964099, self.tradeDate='20230106', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16825.5, self.close=16822.0, self.high=16827.1, self.low=16821.8, self.vol=404.811, self.amt=6810088.1721 
127.0.0.1 - - [06/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-06 08:15:00,615:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230106   075000    075459  ...         0.0        0.0       0
5855  20230106   075500    075959  ...         0.0        0.0       0
5856  20230106   080000    080459  ...         0.0        0.0       0
5857  20230106   080500    080959  ...         0.0        0.0       0
5858  20230106   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 08:15:00,615:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672964099, self.tradeDate='20230106', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16825.5, self.close=16822.0, self.high=16827.1, self.low=16821.8, self.vol=404.811, self.amt=6810088.1721, ukdf['pct'].iloc[-1]=-0.000214 , ukdf['amount'].iloc[-1]=6810088.1721, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17614.82235390368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16822.02172218', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16821.6, self.close=16825.6, self.high=16828.0, self.low=16819.3 
2023-01-06 08:10:01,442:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16821.6, self.close=16825.6, self.high=16828.0, self.low=16819.3   
127.0.0.1 - - [06/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-06 08:10:01,486:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230106   074500    074959  1672962599  ...  16820.4  0.000392   1533    3
1534  20230106   075000    075459  1672962899  ...  16818.2 -0.000392   1534    4
1535  20230106   075500    075959  1672963199  ...  16818.4  0.000196   1535    5
1536  20230106   080000    080459  1672963499  ...  16821.6 -0.000131   1536    0
1537  20230106   080500    080959  1672963799  ...  16819.3  0.000238   1537    1

[5 rows x 11 columns]
2023-01-06 08:10:01,488:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=166, self.factor=0.48862446109729796, self.count=12017 

self.closeSec=1672964099, self.tradeDate='20230106', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16825.5, self.close=16822.0, self.high=16827.1, self.low=16821.8 
2023-01-06 08:15:00,555:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672964099, self.tradeDate='20230106', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16825.5, self.close=16822.0, self.high=16827.1, self.low=16821.8   
2023-01-06 08:15:00,621:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230106   075000    075459  1672962899  ...  16818.2 -0.000392   1534    4
1535  20230106   075500    075959  1672963199  ...  16818.4  0.000196   1535    5
1536  20230106   080000    080459  1672963499  ...  16821.6 -0.000131   1536    0
1537  20230106   080500    080959  1672963799  ...  16819.3  0.000238   1537    1
1538  20230106   081000    081459  1672964099  ...  16821.8 -0.000214   1538    2

[5 rows x 11 columns]
2023-01-06 08:15:00,621:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-06 08:00:20,775:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230106    052959  16852.8  ...  49.583333  0.527116  0.458644
5771  20230106    055959  16836.8  ...  50.000000  0.529139  0.444634
5772  20230106    062959  16840.0  ...  50.416667  0.534021  0.427932
5773  20230106    065959  16847.0  ...  50.416667  0.520857  0.421005
5774  20230106    072959  16829.9  ...  50.000000  0.514165  0.419020

[5 rows x 33 columns]
0.5489833641404805
acc is : 0.5489833641404805
2023-01-06 08:00:20,918:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     1  0.496513  0.503487       1  ...  NaN   NaN -0.0016  1.002357
537     0  0.501803  0.498197       1  ...  NaN   NaN -0.0016  1.002786
538     0  0.500938  0.499062       0  ...  NaN   NaN -0.0016  1.001762
539     1  0.494188  0.505812       0  ...  NaN   NaN -0.0016  1.001232
540     1  0.493904  0.506096       1  ...  NaN   NaN -0.0016  1.001399

[5 rows x 10 columns]
2023-01-06 08:00:20,950:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.496645  0.503355       1  ...  NaN   NaN -0.0016  1.003325
46     0  0.501806  0.498194       1  ...  NaN   NaN -0.0016  1.002678
47     0  0.500708  0.499292       0  ...  NaN   NaN -0.0016  1.001434
48     1  0.494680  0.505320       0  ...  NaN   NaN -0.0016  1.001232
49     1  0.493904  0.506096       1  ...  NaN   NaN -0.0016  1.001399

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5201.1744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16823.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230106   074000    074959  1672962599  16822.3  16827.1  0.000285
2023-01-06 07:50:00,557:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6007 

self.closeSec=1672963199, self.tradeDate='20230106', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16827', self.close='16823.8'
2023-01-06 08:00:00,893:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672963199, self.tradeDate='20230106', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16827', self.close='16823.8'
127.0.0.1 - - [06/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-06 08:00:00,923:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230106   071000    071959  1672960799  16827.2  16826.4 -0.000042
620  20230106   072000    072959  1672961399  16826.3    16821 -0.000321
621  20230106   073000    073959  1672961999    16821  16822.3  0.000077
622  20230106   074000    074959  1672962599  16822.3  16827.1  0.000285
623  20230106   075000    075959  1672963199    16827  16823.8 -0.000196
2023-01-06 08:00:00,923:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6008 

self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16823.8', self.close='16825.6'
2023-01-06 08:10:01,538:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16823.8', self.close='16825.6'
2023-01-06 08:10:01,571:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230106   072000    072959  1672961399  16826.3    16821 -0.000321
621  20230106   073000    073959  1672961999    16821  16822.3  0.000077
622  20230106   074000    074959  1672962599  16822.3  16827.1  0.000285
623  20230106   075000    075959  1672963199    16827  16823.8 -0.000196
624  20230106   080000    080959  1672963799  16823.8  16825.6  0.000107
2023-01-06 08:10:01,571:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230106   074000    074959  1672962599  16822.3  16827.1
2023-01-06 07:50:00,552:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6008 

self.closeSec=1672963199, self.tradeDate='20230106', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16827', self.close='16823.8'
127.0.0.1 - - [06/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-06 08:00:00,902:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672963199, self.tradeDate='20230106', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16827', self.close='16823.8'
2023-01-06 08:00:00,962:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230106   071000    071959  1672960799  16827.2  16826.4
17468  20230106   072000    072959  1672961399  16826.3    16821
17469  20230106   073000    073959  1672961999    16821  16822.3
17470  20230106   074000    074959  1672962599  16822.3  16827.1
17471  20230106   075000    075959  1672963199    16827  16823.8
2023-01-06 08:00:00,966:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6009 

self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16823.8', self.close='16825.6'
127.0.0.1 - - [06/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-06 08:10:01,535:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16823.8', self.close='16825.6'
2023-01-06 08:10:01,561:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230106   072000    072959  1672961399  16826.3    16821
17469  20230106   073000    073959  1672961999    16821  16822.3
17470  20230106   074000    074959  1672962599  16822.3  16827.1
17471  20230106   075000    075959  1672963199    16827  16823.8
17472  20230106   080000    080959  1672963799  16823.8  16825.6
2023-01-06 08:10:01,562:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230106   074000    074959  1672962599  16822.3  16827.1
2023-01-06 07:50:00,558:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6008 

self.closeSec=1672963199, self.tradeDate='20230106', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16827', self.close='16823.8'
127.0.0.1 - - [06/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-06 08:00:00,910:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672963199, self.tradeDate='20230106', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16827', self.close='16823.8'
2023-01-06 08:00:00,926:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230106   071000    071959  1672960799  16827.2  16826.4
12140  20230106   072000    072959  1672961399  16826.3    16821
12141  20230106   073000    073959  1672961999    16821  16822.3
12142  20230106   074000    074959  1672962599  16822.3  16827.1
12143  20230106   075000    075959  1672963199    16827  16823.8
2023-01-06 08:00:00,926:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [06/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6009 

self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16823.8', self.close='16825.6'
2023-01-06 08:10:01,546:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16823.8', self.close='16825.6'
2023-01-06 08:10:01,574:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230106   072000    072959  1672961399  16826.3    16821
12141  20230106   073000    073959  1672961999    16821  16822.3
12142  20230106   074000    074959  1672962599  16822.3  16827.1
12143  20230106   075000    075959  1672963199    16827  16823.8
12144  20230106   080000    080959  1672963799  16823.8  16825.6
2023-01-06 08:10:01,574:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7448
self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16821.6, self.close=16825.6, self.high=16828.0, self.low=16819.3, self.vol=422.815, self.amt=7113228.2202 
127.0.0.1 - - [06/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-06 08:10:01,508:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230106   074500    074959  ...         0.0        0.0       0
5854  20230106   075000    075459  ...         0.0        0.0       0
5855  20230106   075500    075959  ...         0.0        0.0       0
5856  20230106   080000    080459  ...         0.0        0.0       0
5857  20230106   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 08:10:01,508:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672963799, self.tradeDate='20230106', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16821.6, self.close=16825.6, self.high=16828.0, self.low=16819.3, self.vol=422.815, self.amt=7113228.2202, ukdf['pct'].iloc[-1]=0.000238 , ukdf['amount'].iloc[-1]=7113228.2202, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7449
self.closeSec=1672964099, self.tradeDate='20230106', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16825.5, self.close=16822.0, self.high=16827.1, self.low=16821.8, self.vol=404.811, self.amt=6810088.1721 
127.0.0.1 - - [06/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-06 08:15:00,587:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230106   075000    075459  ...         0.0        0.0       0
5855  20230106   075500    075959  ...         0.0        0.0       0
5856  20230106   080000    080459  ...         0.0        0.0       0
5857  20230106   080500    080959  ...         0.0        0.0       0
5858  20230106   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 08:15:00,588:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672964099, self.tradeDate='20230106', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16825.5, self.close=16822.0, self.high=16827.1, self.low=16821.8, self.vol=404.811, self.amt=6810088.1721, ukdf['pct'].iloc[-1]=-0.000214 , ukdf['amount'].iloc[-1]=6810088.1721, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230105   200000    235959  1672934399  ...    719  0.703932  1.416203     1.0
720  20230106   000000    035959  1672948799  ...    720  0.587124  1.013075     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '7061.7091380228', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16856.92052564', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [06/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=250
self.closeSec=1672963199, self.tradeDate='20230106', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16856.3, self.close=16823.8, self.high=16863.4, self.low=16810.0, self.vol=19079.522, self.amt=321268082.4729 
2023-01-06 08:00:00,801:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672963199, self.tradeDate='20230106', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16856.3, self.close=16823.8, self.high=16863.4, self.low=16810.0, self.vol=19079.522, self.amt=321268082.4729 
2023-01-06 08:00:00,857:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230105   120000    155959  ...  16536.782  2.780496e+08 -0.000178
718  20230105   160000    195959  ...  23157.753  3.891926e+08  0.000654
719  20230105   200000    235959  ...  68886.393  1.157975e+09  0.000571
720  20230106   000000    035959  ...  29187.231  4.912216e+08  0.001170
721  20230106   040000    075959  ...  19079.522  3.212681e+08 -0.001928

[5 rows x 11 columns]
2023-01-06 08:00:02,304:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230105   120000    155959  1672905599  ...    717  0.872667  2.061405     1.0
718  20230105   160000    195959  1672919999  ...    718  0.774980  1.685966     1.0
719  20230105   200000    235959  1672934399  ...    719  0.703932  1.416203     1.0
720  20230106   000000    035959  1672948799  ...    720  0.587124  1.013075     1.0
721  20230106   040000    075959  1672963199  ...    721  0.486126  0.669225     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '5313.939', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16823.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


