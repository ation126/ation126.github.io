# 20221211 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3962
self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17117.5, self.close=17116.0, self.high=17117.6, self.low=17114.0, self.vol=327.044, self.amt=5597763.4355 
127.0.0.1 - - [11/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-11 08:10:01,445:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221211   074500    074959  ...         0.0        0.0       0
5854  20221211   075000    075459  ...         0.0        0.0       0
5855  20221211   075500    075959  ...         0.0        0.0       0
5856  20221211   080000    080459  ...         0.0        0.0       0
5857  20221211   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-11 08:10:01,446:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17117.5, self.close=17116.0, self.high=17117.6, self.low=17114.0, self.vol=327.044, self.amt=5597763.4355, ukdf['pct'].iloc[-1]=-8.8e-05 , ukdf['amount'].iloc[-1]=5597763.4355, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-35321.81143561824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17116.27506374', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3963
self.closeSec=1670717699, self.tradeDate='20221211', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17115.9, self.close=17121.1, self.high=17121.2, self.low=17115.9, self.vol=260.451, self.amt=4458231.5805 
2022-12-11 08:15:00,596:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221211   075000    075459  ...         0.0        0.0       0
5855  20221211   075500    075959  ...         0.0        0.0       0
5856  20221211   080000    080459  ...         0.0        0.0       0
5857  20221211   080500    080959  ...         0.0        0.0       0
5858  20221211   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-11 08:15:00,597:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670717699, self.tradeDate='20221211', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17115.9, self.close=17121.1, self.high=17121.2, self.low=17115.9, self.vol=260.451, self.amt=4458231.5805, ukdf['pct'].iloc[-1]=0.000298 , ukdf['amount'].iloc[-1]=4458231.5805, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-35612.1568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17121.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=63, self.factor=0.49504406096478487, self.count=4528 

self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17117.5, self.close=17116.0, self.high=17117.6, self.low=17114.0 
2022-12-11 08:10:01,417:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17117.5, self.close=17116.0, self.high=17117.6, self.low=17114.0   
2022-12-11 08:10:01,446:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221211   074500    074959  1670716199  ...  17081.0 -0.000736   1533    3
1534  20221211   075000    075459  1670716499  ...  17099.9  0.000485   1534    4
1535  20221211   075500    075959  1670716799  ...  17107.8  0.000713   1535    5
1536  20221211   080000    080459  1670717099  ...  17114.8 -0.000152   1536    0
1537  20221211   080500    080959  1670717399  ...  17114.0 -0.000088   1537    1

[5 rows x 11 columns]
2022-12-11 08:10:01,446:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=63, self.factor=0.49504406096478487, self.count=4529 

self.closeSec=1670717699, self.tradeDate='20221211', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17115.9, self.close=17121.1, self.high=17121.2, self.low=17115.9 
2022-12-11 08:15:00,522:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670717699, self.tradeDate='20221211', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17115.9, self.close=17121.1, self.high=17121.2, self.low=17115.9   
2022-12-11 08:15:00,552:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221211   075000    075459  1670716499  ...  17099.9  0.000485   1534    4
1535  20221211   075500    075959  1670716799  ...  17107.8  0.000713   1535    5
1536  20221211   080000    080459  1670717099  ...  17114.8 -0.000152   1536    0
1537  20221211   080500    080959  1670717399  ...  17114.0 -0.000088   1537    1
1538  20221211   081000    081459  1670717699  ...  17115.9  0.000298   1538    2

[5 rows x 11 columns]
2022-12-11 08:15:00,552:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-11 08:00:16,886:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221211    052959  17163.3  ...  56.250000  0.525074  0.441127
5771  20221211    055959  17157.6  ...  55.833333  0.493493  0.472398
5772  20221211    062959  17116.0  ...  56.250000  0.510364  0.489017
5773  20221211    065959  17136.5  ...  55.833333  0.500579  0.511756
5774  20221211    072959  17126.1  ...  55.833333  0.493163  0.538534

[5 rows x 33 columns]
0.5822550831792976
acc is : 0.5822550831792976
2022-12-11 08:00:16,945:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.492624  0.507376       0  ...  0.975714   1.0    0.0  1.046229
537     1  0.482636  0.517364       1  ...  0.977042   1.0    0.0  1.047653
538     1  0.497533  0.502467       0  ...  0.976278   1.0    0.0  1.046834
539     1  0.488950  0.511050       0  ...  0.975691   1.0    0.0  1.046205
540     1  0.488578  0.511422       1  ...  0.975936   1.0    0.0  1.046468

[5 rows x 10 columns]
2022-12-11 08:00:16,956:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492162  0.507838       0  ...  0.975714   1.0    0.0  1.044626
46     1  0.482643  0.517357       1  ...  0.977042   1.0    0.0  1.046202
47     1  0.497171  0.502829       0  ...  0.976278   1.0    0.0  1.044020
48     1  0.488927  0.511073       0  ...  0.975691   1.0    0.0  1.046205
49     1  0.488578  0.511422       1  ...  0.975936   1.0    0.0  1.046468

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-3466.90118209982', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17121.05633962', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221211   074000    074959  1670716199  17127.7  17100.9 -0.001565
2022-12-11 07:50:00,534:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2263 

self.closeSec=1670716799, self.tradeDate='20221211', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17102.1', self.close='17120'
127.0.0.1 - - [11/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-11 08:00:01,185:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670716799, self.tradeDate='20221211', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17102.1', self.close='17120'
2022-12-11 08:00:01,193:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221211   071000    071959  1670714399  17133.8    17124 -0.000572
620  20221211   072000    072959  1670714999  17124.1  17115.7 -0.000485
621  20221211   073000    073959  1670715599  17115.7  17127.7  0.000701
622  20221211   074000    074959  1670716199  17127.7  17100.9 -0.001565
623  20221211   075000    075959  1670716799  17102.1    17120  0.001117
2022-12-11 08:00:01,193:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2264 

self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17120.1', self.close='17116'
2022-12-11 08:10:01,505:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17120.1', self.close='17116'
127.0.0.1 - - [11/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-11 08:10:01,518:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221211   072000    072959  1670714999  17124.1  17115.7 -0.000485
621  20221211   073000    073959  1670715599  17115.7  17127.7  0.000701
622  20221211   074000    074959  1670716199  17127.7  17100.9 -0.001565
623  20221211   075000    075959  1670716799  17102.1    17120  0.001117
624  20221211   080000    080959  1670717399  17120.1    17116 -0.000234
2022-12-11 08:10:01,519:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221211   074000    074959  1670716199  17127.7  17100.9
2022-12-11 07:50:00,540:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2264 

self.closeSec=1670716799, self.tradeDate='20221211', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17102.1', self.close='17120'
2022-12-11 08:00:01,204:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670716799, self.tradeDate='20221211', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17102.1', self.close='17120'
2022-12-11 08:00:01,217:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221211   071000    071959  1670714399  17133.8    17124
17468  20221211   072000    072959  1670714999  17124.1  17115.7
17469  20221211   073000    073959  1670715599  17115.7  17127.7
17470  20221211   074000    074959  1670716199  17127.7  17100.9
17471  20221211   075000    075959  1670716799  17102.1    17120
2022-12-11 08:00:01,218:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2265 

self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17120.1', self.close='17116'
2022-12-11 08:10:01,509:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17120.1', self.close='17116'
2022-12-11 08:10:01,524:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221211   072000    072959  1670714999  17124.1  17115.7
17469  20221211   073000    073959  1670715599  17115.7  17127.7
17470  20221211   074000    074959  1670716199  17127.7  17100.9
17471  20221211   075000    075959  1670716799  17102.1    17120
17472  20221211   080000    080959  1670717399  17120.1    17116
2022-12-11 08:10:01,525:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221211   074000    074959  1670716199  17127.7  17100.9
2022-12-11 07:50:00,534:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2264 

self.closeSec=1670716799, self.tradeDate='20221211', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17102.1', self.close='17120'
2022-12-11 08:00:01,195:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670716799, self.tradeDate='20221211', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17102.1', self.close='17120'
2022-12-11 08:00:01,213:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221211   071000    071959  1670714399  17133.8    17124
12140  20221211   072000    072959  1670714999  17124.1  17115.7
12141  20221211   073000    073959  1670715599  17115.7  17127.7
12142  20221211   074000    074959  1670716199  17127.7  17100.9
12143  20221211   075000    075959  1670716799  17102.1    17120
2022-12-11 08:00:01,213:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2265 

self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17120.1', self.close='17116'
2022-12-11 08:10:01,516:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670717399, self.tradeDate='20221211', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17120.1', self.close='17116'
2022-12-11 08:10:01,523:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221211   072000    072959  1670714999  17124.1  17115.7
12141  20221211   073000    073959  1670715599  17115.7  17127.7
12142  20221211   074000    074959  1670716199  17127.7  17100.9
12143  20221211   075000    075959  1670716799  17102.1    17120
12144  20221211   080000    080959  1670717399  17120.1    17116
2022-12-11 08:10:01,524:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221210   200000    235959  1670687999  ...    719  0.552818  0.166990     NaN
720  20221211   000000    035959  1670702399  ...    720  0.545006  0.137279     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-7919.8322', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17166.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=94
self.closeSec=1670716799, self.tradeDate='20221211', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17166.3, self.close=17120.0, self.high=17175.6, self.low=17081.0, self.vol=26181.427, self.amt=448495456.0625 
127.0.0.1 - - [11/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-11 08:00:01,060:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670716799, self.tradeDate='20221211', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17166.3, self.close=17120.0, self.high=17175.6, self.low=17081.0, self.vol=26181.427, self.amt=448495456.0625 
2022-12-11 08:00:01,082:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221210   120000    155959  ...  17751.416  3.043245e+08  0.000268
718  20221210   160000    195959  ...  20902.227  3.582971e+08  0.000892
719  20221210   200000    235959  ...  36351.612  6.241564e+08  0.002354
720  20221211   000000    035959  ...  20946.808  3.598371e+08 -0.001977
721  20221211   040000    075959  ...  26181.427  4.484955e+08 -0.002697

[5 rows x 11 columns]
2022-12-11 08:00:01,904:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221210   120000    155959  1670659199  ...    717  0.558600  0.190165     NaN
718  20221210   160000    195959  1670673599  ...    718  0.549339  0.156319     NaN
719  20221210   200000    235959  1670687999  ...    719  0.552818  0.166990     NaN
720  20221211   000000    035959  1670702399  ...    720  0.545006  0.137279     NaN
721  20221211   040000    075959  1670716799  ...    721  0.540221  0.120987     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-10634.0308', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17120.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


