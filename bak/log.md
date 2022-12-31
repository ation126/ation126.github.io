# 20221231 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9722
self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16597.0, self.close=16587.7, self.high=16597.1, self.low=16587.7, self.vol=600.154, self.amt=9957712.4822 
127.0.0.1 - - [31/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-31 08:10:01,486:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221231   074500    074959  ...         0.0        0.0       0
5854  20221231   075000    075459  ...         0.0        0.0       0
5855  20221231   075500    075959  ...         0.0        0.0       0
5856  20221231   080000    080459  ...         0.0        0.0       0
5857  20221231   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 08:10:01,486:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16597.0, self.close=16587.7, self.high=16597.1, self.low=16587.7, self.vol=600.154, self.amt=9957712.4822, ukdf['pct'].iloc[-1]=-0.00056 , ukdf['amount'].iloc[-1]=9957712.4822, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-3612.86891581088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16589.33836938', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9723
self.closeSec=1672445699, self.tradeDate='20221231', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16587.7, self.close=16585.9, self.high=16587.8, self.low=16585.4, self.vol=319.507, self.amt=5299346.3749 
127.0.0.1 - - [31/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-31 08:15:00,604:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221231   075000    075459  ...         0.0        0.0       0
5855  20221231   075500    075959  ...         0.0        0.0       0
5856  20221231   080000    080459  ...         0.0        0.0       0
5857  20221231   080500    080959  ...         0.0        0.0       0
5858  20221231   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 08:15:00,604:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672445699, self.tradeDate='20221231', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16587.7, self.close=16585.9, self.high=16587.8, self.low=16585.4, self.vol=319.507, self.amt=5299346.3749, ukdf['pct'].iloc[-1]=-0.000109 , ukdf['amount'].iloc[-1]=5299346.3749, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-3405.9616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16585.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=19, self.factor=0.438237984133514, self.count=10288 

self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16597.0, self.close=16587.7, self.high=16597.1, self.low=16587.7 
2022-12-31 08:10:01,424:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16597.0, self.close=16587.7, self.high=16597.1, self.low=16587.7   
2022-12-31 08:10:01,480:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221231   074500    074959  1672444199  ...  16597.8 -0.000765   1533    3
1534  20221231   075000    075459  1672444499  ...  16595.9 -0.000054   1534    4
1535  20221231   075500    075959  1672444799  ...  16591.4  0.000253   1535    5
1536  20221231   080000    080459  1672445099  ...  16597.0 -0.000253   1536    0
1537  20221231   080500    080959  1672445399  ...  16587.7 -0.000560   1537    1

[5 rows x 11 columns]
2022-12-31 08:10:01,480:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=19, self.factor=0.438237984133514, self.count=10289 

self.closeSec=1672445699, self.tradeDate='20221231', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16587.7, self.close=16585.9, self.high=16587.8, self.low=16585.4 
2022-12-31 08:15:00,547:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672445699, self.tradeDate='20221231', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16587.7, self.close=16585.9, self.high=16587.8, self.low=16585.4   
2022-12-31 08:15:00,565:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221231   075000    075459  1672444499  ...  16595.9 -0.000054   1534    4
1535  20221231   075500    075959  1672444799  ...  16591.4  0.000253   1535    5
1536  20221231   080000    080459  1672445099  ...  16597.0 -0.000253   1536    0
1537  20221231   080500    080959  1672445399  ...  16587.7 -0.000560   1537    1
1538  20221231   081000    081459  1672445699  ...  16585.4 -0.000109   1538    2

[5 rows x 11 columns]
2022-12-31 08:15:00,565:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-31 08:00:19,398:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221231    052959  16564.6  ...  44.583333  0.516707  0.437709
5771  20221231    055959  16601.5  ...  44.166667  0.504260  0.425397
5772  20221231    062959  16579.0  ...  44.583333  0.504744  0.413733
5773  20221231    065959  16579.8  ...  45.000000  0.504854  0.402808
5774  20221231    072959  16580.1  ...  45.416667  0.510885  0.390515

[5 rows x 33 columns]
0.5637707948243993
acc is : 0.5637707948243993
2022-12-31 08:00:19,500:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.513556  0.486444       0  ...  0.990394   1.0    0.0  1.000018
537     1  0.498821  0.501179       1  ...  0.990448   1.0    0.0  1.000072
538     0  0.508527  0.491473       0  ...  0.990460   1.0    0.0  1.000084
539     0  0.506818  0.493182       1  ...  0.991111   1.0    0.0  1.000742
540     0  0.506839  0.493161       1  ...  0.991720   1.0    0.0  1.001357

[5 rows x 10 columns]
2022-12-31 08:00:19,524:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512572  0.487428       0  ...  0.970628   1.0    0.0  0.995120
46     1  0.498084  0.501916       1  ...  0.970681   1.0    0.0  0.996694
47     0  0.508186  0.491814       0  ...  0.990460   1.0    0.0  0.997167
48     0  0.506706  0.493294       1  ...  0.991111   1.0    0.0  1.000742
49     0  0.506839  0.493161       1  ...  0.991720   1.0    0.0  1.001357

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-4265.5584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16601.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221231   074000    074959  1672444199  16607.3  16597.8 -0.000572
2022-12-31 07:50:00,624:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5143 

self.closeSec=1672444799, self.tradeDate='20221231', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16597.8', self.close='16601.2'
127.0.0.1 - - [31/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -
2022-12-31 08:00:00,895:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672444799, self.tradeDate='20221231', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16597.8', self.close='16601.2'
2022-12-31 08:00:00,929:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221231   071000    071959  1672442399  16593.8  16590.4 -0.000133
620  20221231   072000    072959  1672442999  16590.5  16591.4  0.000060
621  20221231   073000    073959  1672443599  16591.5  16607.3  0.000958
622  20221231   074000    074959  1672444199  16607.3  16597.8 -0.000572
623  20221231   075000    075959  1672444799  16597.8  16601.2  0.000205
2022-12-31 08:00:00,930:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5144 

self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16601.2', self.close='16587.7'
2022-12-31 08:10:01,513:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16601.2', self.close='16587.7'
2022-12-31 08:10:01,565:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221231   072000    072959  1672442999  16590.5  16591.4  0.000060
621  20221231   073000    073959  1672443599  16591.5  16607.3  0.000958
622  20221231   074000    074959  1672444199  16607.3  16597.8 -0.000572
623  20221231   075000    075959  1672444799  16597.8  16601.2  0.000205
624  20221231   080000    080959  1672445399  16601.2  16587.7 -0.000813
2022-12-31 08:10:01,565:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221231   074000    074959  1672444199  16607.3  16597.8
2022-12-31 07:50:00,612:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5144 

self.closeSec=1672444799, self.tradeDate='20221231', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16597.8', self.close='16601.2'
127.0.0.1 - - [31/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -
2022-12-31 08:00:00,876:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672444799, self.tradeDate='20221231', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16597.8', self.close='16601.2'
2022-12-31 08:00:00,918:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221231   071000    071959  1672442399  16593.8  16590.4
17468  20221231   072000    072959  1672442999  16590.5  16591.4
17469  20221231   073000    073959  1672443599  16591.5  16607.3
17470  20221231   074000    074959  1672444199  16607.3  16597.8
17471  20221231   075000    075959  1672444799  16597.8  16601.2
2022-12-31 08:00:00,918:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5145 

self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16601.2', self.close='16587.7'
2022-12-31 08:10:01,571:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16601.2', self.close='16587.7'
2022-12-31 08:10:01,590:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221231   072000    072959  1672442999  16590.5  16591.4
17469  20221231   073000    073959  1672443599  16591.5  16607.3
17470  20221231   074000    074959  1672444199  16607.3  16597.8
17471  20221231   075000    075959  1672444799  16597.8  16601.2
17472  20221231   080000    080959  1672445399  16601.2  16587.7
2022-12-31 08:10:01,590:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221231   074000    074959  1672444199  16607.3  16597.8
2022-12-31 07:50:00,661:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [31/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5144 

self.closeSec=1672444799, self.tradeDate='20221231', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16597.8', self.close='16601.2'
2022-12-31 08:00:00,881:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672444799, self.tradeDate='20221231', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16597.8', self.close='16601.2'
2022-12-31 08:00:00,937:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221231   071000    071959  1672442399  16593.8  16590.4
12140  20221231   072000    072959  1672442999  16590.5  16591.4
12141  20221231   073000    073959  1672443599  16591.5  16607.3
12142  20221231   074000    074959  1672444199  16607.3  16597.8
12143  20221231   075000    075959  1672444799  16597.8  16601.2
2022-12-31 08:00:00,941:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5145 

self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16601.2', self.close='16587.7'
2022-12-31 08:10:01,531:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16601.2', self.close='16587.7'
127.0.0.1 - - [31/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-31 08:10:01,576:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221231   072000    072959  1672442999  16590.5  16591.4
12141  20221231   073000    073959  1672443599  16591.5  16607.3
12142  20221231   074000    074959  1672444199  16607.3  16597.8
12143  20221231   075000    075959  1672444799  16597.8  16601.2
12144  20221231   080000    080959  1672445399  16601.2  16587.7
2022-12-31 08:10:01,577:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5720
self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16597.0, self.close=16587.7, self.high=16597.1, self.low=16587.7, self.vol=600.154, self.amt=9957712.4822 
127.0.0.1 - - [31/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-31 08:10:01,456:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221231   074500    074959  ...         0.0        0.0       0
5854  20221231   075000    075459  ...         0.0        0.0       0
5855  20221231   075500    075959  ...         0.0        0.0       0
5856  20221231   080000    080459  ...         0.0        0.0       0
5857  20221231   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 08:10:01,456:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672445399, self.tradeDate='20221231', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16597.0, self.close=16587.7, self.high=16597.1, self.low=16587.7, self.vol=600.154, self.amt=9957712.4822, ukdf['pct'].iloc[-1]=-0.00056 , ukdf['amount'].iloc[-1]=9957712.4822, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5721
self.closeSec=1672445699, self.tradeDate='20221231', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16587.7, self.close=16585.9, self.high=16587.8, self.low=16585.4, self.vol=319.507, self.amt=5299346.3749 
127.0.0.1 - - [31/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-31 08:15:00,650:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221231   075000    075459  ...         0.0        0.0       0
5855  20221231   075500    075959  ...         0.0        0.0       0
5856  20221231   080000    080459  ...         0.0        0.0       0
5857  20221231   080500    080959  ...         0.0        0.0       0
5858  20221231   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 08:15:00,650:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672445699, self.tradeDate='20221231', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16587.7, self.close=16585.9, self.high=16587.8, self.low=16585.4, self.vol=319.507, self.amt=5299346.3749, ukdf['pct'].iloc[-1]=-0.000109 , ukdf['amount'].iloc[-1]=5299346.3749, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221230   200000    235959  1672415999  ...    719  0.537523  0.446099     NaN
720  20221231   000000    035959  1672430399  ...    720  0.547593  0.492465     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-5838.39521746572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16521.77695986', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=895432.8006702, self.flagDict['side']='buy', self.tradeCount=8, self.count=214
self.closeSec=1672444799, self.tradeDate='20221231', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16520.8, self.close=16601.1, self.high=16666.6, self.low=16520.5, self.vol=34781.545, self.amt=577093248.2741 
2022-12-31 08:00:00,744:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672444799, self.tradeDate='20221231', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16520.8, self.close=16601.1, self.high=16666.6, self.low=16520.5, self.vol=34781.545, self.amt=577093248.2741 
127.0.0.1 - - [31/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -
2022-12-31 08:00:00,773:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20221230   120000    155959  ...   62732.710  1.035995e+09 -0.007617
718  20221230   160000    195959  ...   38916.057  6.420308e+08  0.001336
719  20221230   200000    235959  ...  104487.149  1.719910e+09  0.003530
720  20221231   000000    035959  ...   34830.474  5.759541e+08 -0.001626
721  20221231   040000    075959  ...   34781.545  5.770932e+08  0.004861

[5 rows x 11 columns]
2022-12-31 08:00:02,539:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221230   120000    155959  1672387199  ...    717  0.592312  0.542793     NaN
718  20221230   160000    195959  1672401599  ...    718  0.616368  0.623980     1.0
719  20221230   200000    235959  1672415999  ...    719  0.537523  0.446099     NaN
720  20221231   000000    035959  1672430399  ...    720  0.547593  0.492465     NaN
721  20221231   040000    075959  1672444799  ...    721  0.543605  0.502980     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-1557.6522', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16601.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


