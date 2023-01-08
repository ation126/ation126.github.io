# 20230108 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [08/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12026
self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16944.7, self.close=16947.2, self.high=16948.3, self.low=16944.7, self.vol=320.911, self.amt=5438452.0093 
2023-01-08 08:10:01,721:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230108   074500    074959  ...         0.0        0.0       0
5854  20230108   075000    075459  ...         0.0        0.0       0
5855  20230108   075500    075959  ...         0.0        0.0       0
5856  20230108   080000    080459  ...         0.0        0.0       0
5857  20230108   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 08:10:01,721:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16944.7, self.close=16947.2, self.high=16948.3, self.low=16944.7, self.vol=320.911, self.amt=5438452.0093, ukdf['pct'].iloc[-1]=0.000106 , ukdf['amount'].iloc[-1]=5438452.0093, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-25141.5328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16947.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12027
self.closeSec=1673136899, self.tradeDate='20230108', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16947.1, self.close=16939.3, self.high=16947.2, self.low=16939.3, self.vol=267.455, self.amt=4531507.8613 
127.0.0.1 - - [08/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-08 08:15:00,640:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230108   075000    075459  ...         0.0        0.0       0
5855  20230108   075500    075959  ...         0.0        0.0       0
5856  20230108   080000    080459  ...         0.0        0.0       0
5857  20230108   080500    080959  ...         0.0        0.0       0
5858  20230108   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 08:15:00,641:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673136899, self.tradeDate='20230108', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16947.1, self.close=16939.3, self.high=16947.2, self.low=16939.3, self.vol=267.455, self.amt=4531507.8613, ukdf['pct'].iloc[-1]=-0.000466 , ukdf['amount'].iloc[-1]=4531507.8613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-24681.77943869232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16939.45985507', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16944.7, self.close=16947.2, self.high=16948.3, self.low=16944.7 
2023-01-08 08:10:01,653:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16944.7, self.close=16947.2, self.high=16948.3, self.low=16944.7   
127.0.0.1 - - [08/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-08 08:10:01,698:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230108   074500    074959  1673135399  ...  16934.3  0.000124   1533    3
1534  20230108   075000    075459  1673135699  ...  16936.3  0.000089   1534    4
1535  20230108   075500    075959  1673135999  ...  16936.4 -0.000089   1535    5
1536  20230108   080000    080459  1673136299  ...  16936.4  0.000531   1536    0
1537  20230108   080500    080959  1673136599  ...  16944.7  0.000106   1537    1

[5 rows x 11 columns]
2023-01-08 08:10:01,700:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=15, self.factor=0.37972491459397084, self.count=12593 

self.closeSec=1673136899, self.tradeDate='20230108', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16947.1, self.close=16939.3, self.high=16947.2, self.low=16939.3 
2023-01-08 08:15:00,546:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673136899, self.tradeDate='20230108', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16947.1, self.close=16939.3, self.high=16947.2, self.low=16939.3   
2023-01-08 08:15:00,592:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230108   075000    075459  1673135699  ...  16936.3  0.000089   1534    4
1535  20230108   075500    075959  1673135999  ...  16936.4 -0.000089   1535    5
1536  20230108   080000    080459  1673136299  ...  16936.4  0.000531   1536    0
1537  20230108   080500    080959  1673136599  ...  16944.7  0.000106   1537    1
1538  20230108   081000    081459  1673136899  ...  16939.3 -0.000466   1538    2

[5 rows x 11 columns]
2023-01-08 08:15:00,592:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-08 08:00:17,499:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230108    052959  16939.3  ...  51.666667  0.545590  0.495139
5771  20230108    055959  16929.4  ...  51.666667  0.547446  0.485186
5772  20230108    062959  16931.5  ...  51.666667  0.544743  0.479368
5773  20230108    065959  16929.0  ...  52.083333  0.546024  0.471993
5774  20230108    072959  16930.4  ...  52.083333  0.549076  0.459125

[5 rows x 33 columns]
0.5508317929759704
acc is : 0.5508317929759704
2023-01-08 08:00:17,581:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     1  0.497309  0.502691       1  ...  NaN   NaN -0.0016  1.011126
537     1  0.499820  0.500180       0  ...  NaN   NaN -0.0016  1.010976
538     1  0.498004  0.501996       1  ...  NaN   NaN -0.0016  1.011060
539     1  0.499181  0.500819       1  ...  NaN   NaN -0.0016  1.011257
540     1  0.499870  0.500130       1  ...  NaN   NaN -0.0016  1.011418

[5 rows x 10 columns]
2023-01-08 08:00:17,592:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.496671  0.503329       1  ...  NaN   NaN -0.0016  1.008386
46     1  0.499392  0.500608       0  ...  NaN   NaN -0.0016  1.008976
47     1  0.497790  0.502210       1  ...  NaN   NaN -0.0016  1.009583
48     1  0.499181  0.500819       1  ...  NaN   NaN -0.0016  1.011257
49     1  0.499870  0.500130       1  ...  NaN   NaN -0.0016  1.011418

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '10142.928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16940', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230108   074000    074959  1673135399  16938.2  16936.4 -0.000100
2023-01-08 07:50:00,740:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6295 

self.closeSec=1673135999, self.tradeDate='20230108', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16936.4', self.close='16936.5'
2023-01-08 08:00:01,138:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673135999, self.tradeDate='20230108', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16936.4', self.close='16936.5'
2023-01-08 08:00:01,168:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230108   071000    071959  1673133599  16933.9  16933.2 -0.000041
620  20230108   072000    072959  1673134199  16933.2  16933.7  0.000030
621  20230108   073000    073959  1673134799  16933.7  16938.1  0.000260
622  20230108   074000    074959  1673135399  16938.2  16936.4 -0.000100
623  20230108   075000    075959  1673135999  16936.4  16936.5  0.000006
2023-01-08 08:00:01,169:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6296 

self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16936.5', self.close='16947.2'
2023-01-08 08:10:01,776:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16936.5', self.close='16947.2'
127.0.0.1 - - [08/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-08 08:10:01,798:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230108   072000    072959  1673134199  16933.2  16933.7  0.000030
621  20230108   073000    073959  1673134799  16933.7  16938.1  0.000260
622  20230108   074000    074959  1673135399  16938.2  16936.4 -0.000100
623  20230108   075000    075959  1673135999  16936.4  16936.5  0.000006
624  20230108   080000    080959  1673136599  16936.5  16947.2  0.000632
2023-01-08 08:10:01,798:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230108   074000    074959  1673135399  16938.2  16936.4
2023-01-08 07:50:00,768:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6296 

self.closeSec=1673135999, self.tradeDate='20230108', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16936.4', self.close='16936.5'
127.0.0.1 - - [08/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-08 08:00:01,182:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673135999, self.tradeDate='20230108', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16936.4', self.close='16936.5'
2023-01-08 08:00:01,213:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230108   071000    071959  1673133599  16933.9  16933.2
17468  20230108   072000    072959  1673134199  16933.2  16933.7
17469  20230108   073000    073959  1673134799  16933.7  16938.1
17470  20230108   074000    074959  1673135399  16938.2  16936.4
17471  20230108   075000    075959  1673135999  16936.4  16936.5
2023-01-08 08:00:01,214:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6297 

self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16936.5', self.close='16947.2'
2023-01-08 08:10:01,785:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16936.5', self.close='16947.2'
2023-01-08 08:10:01,808:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230108   072000    072959  1673134199  16933.2  16933.7
17469  20230108   073000    073959  1673134799  16933.7  16938.1
17470  20230108   074000    074959  1673135399  16938.2  16936.4
17471  20230108   075000    075959  1673135999  16936.4  16936.5
17472  20230108   080000    080959  1673136599  16936.5  16947.2
2023-01-08 08:10:01,809:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230108   074000    074959  1673135399  16938.2  16936.4
2023-01-08 07:50:00,763:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6296 

self.closeSec=1673135999, self.tradeDate='20230108', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16936.4', self.close='16936.5'
2023-01-08 08:00:01,159:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673135999, self.tradeDate='20230108', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16936.4', self.close='16936.5'
127.0.0.1 - - [08/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-08 08:00:01,195:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230108   071000    071959  1673133599  16933.9  16933.2
12140  20230108   072000    072959  1673134199  16933.2  16933.7
12141  20230108   073000    073959  1673134799  16933.7  16938.1
12142  20230108   074000    074959  1673135399  16938.2  16936.4
12143  20230108   075000    075959  1673135999  16936.4  16936.5
2023-01-08 08:00:01,195:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [08/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6297 

self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16936.5', self.close='16947.2'
2023-01-08 08:10:01,785:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16936.5', self.close='16947.2'
2023-01-08 08:10:01,800:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230108   072000    072959  1673134199  16933.2  16933.7
12141  20230108   073000    073959  1673134799  16933.7  16938.1
12142  20230108   074000    074959  1673135399  16938.2  16936.4
12143  20230108   075000    075959  1673135999  16936.4  16936.5
12144  20230108   080000    080959  1673136599  16936.5  16947.2
2023-01-08 08:10:01,800:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8024
self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16944.7, self.close=16947.2, self.high=16948.3, self.low=16944.7, self.vol=320.911, self.amt=5438452.0093 
127.0.0.1 - - [08/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-08 08:10:01,719:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230108   074500    074959  ...         0.0        0.0       0
5854  20230108   075000    075459  ...         0.0        0.0       0
5855  20230108   075500    075959  ...         0.0        0.0       0
5856  20230108   080000    080459  ...         0.0        0.0       0
5857  20230108   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 08:10:01,720:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673136599, self.tradeDate='20230108', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16944.7, self.close=16947.2, self.high=16948.3, self.low=16944.7, self.vol=320.911, self.amt=5438452.0093, ukdf['pct'].iloc[-1]=0.000106 , ukdf['amount'].iloc[-1]=5438452.0093, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8025
self.closeSec=1673136899, self.tradeDate='20230108', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16947.1, self.close=16939.3, self.high=16947.2, self.low=16939.3, self.vol=267.455, self.amt=4531507.8613 
2023-01-08 08:15:00,611:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230108   075000    075459  ...         0.0        0.0       0
5855  20230108   075500    075959  ...         0.0        0.0       0
5856  20230108   080000    080459  ...         0.0        0.0       0
5857  20230108   080500    080959  ...         0.0        0.0       0
5858  20230108   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 08:15:00,611:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673136899, self.tradeDate='20230108', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16947.1, self.close=16939.3, self.high=16947.2, self.low=16939.3, self.vol=267.455, self.amt=4531507.8613, ukdf['pct'].iloc[-1]=-0.000466 , ukdf['amount'].iloc[-1]=4531507.8613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230107   200000    235959  1673107199  ...    719  0.354376  0.109310     NaN
720  20230108   000000    035959  1673121599  ...    720  0.336979  0.040098     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '11304.9416712951', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16937.33046563', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=262
self.closeSec=1673135999, self.tradeDate='20230108', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16937.3, self.close=16936.5, self.high=16945.8, self.low=16922.9, self.vol=9824.894, self.amt=166381363.3388 
127.0.0.1 - - [08/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-08 08:00:00,802:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673135999, self.tradeDate='20230108', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16937.3, self.close=16936.5, self.high=16945.8, self.low=16922.9, self.vol=9824.894, self.amt=166381363.3388 
2023-01-08 08:00:00,825:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230107   120000    155959  ...  10555.757  1.787108e+08 -0.000260
718  20230107   160000    195959  ...  13458.246  2.277289e+08 -0.001623
719  20230107   200000    235959  ...  16729.280  2.830697e+08  0.001301
720  20230108   000000    035959  ...   9360.224  1.584223e+08  0.000171
721  20230108   040000    075959  ...   9824.894  1.663814e+08 -0.000047

[5 rows x 11 columns]
2023-01-08 08:00:02,332:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230107   120000    155959  1673078399  ...    717  0.415503  0.335738     NaN
718  20230107   160000    195959  1673092799  ...    718  0.388516  0.234297     NaN
719  20230107   200000    235959  1673107199  ...    719  0.354376  0.109310     NaN
720  20230108   000000    035959  1673121599  ...    720  0.336979  0.040098     NaN
721  20230108   040000    075959  1673135999  ...    721  0.226620 -0.341427     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '11266.3501212258', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16936.59914954', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


