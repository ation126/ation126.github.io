# 20230104 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [04/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10874
self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16661.9, self.close=16657.1, self.high=16662.4, self.low=16657.1, self.vol=387.769, self.amt=6460466.3966 
2023-01-04 08:10:01,636:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230104   074500    074959  ...         0.0        0.0       0
5854  20230104   075000    075459  ...         0.0        0.0       0
5855  20230104   075500    075959  ...         0.0        0.0       0
5856  20230104   080000    080459  ...         0.0        0.0       0
5857  20230104   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 08:10:01,638:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16661.9, self.close=16657.1, self.high=16662.4, self.low=16657.1, self.vol=387.769, self.amt=6460466.3966, ukdf['pct'].iloc[-1]=-0.000288 , ukdf['amount'].iloc[-1]=6460466.3966, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-7706.89662655824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16657.37259749', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10875
self.closeSec=1672791299, self.tradeDate='20230104', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16657.1, self.close=16660.0, self.high=16661.3, self.low=16657.1, self.vol=229.669, self.amt=3826214.4396 
127.0.0.1 - - [04/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-04 08:15:00,592:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230104   075000    075459  ...         0.0        0.0       0
5855  20230104   075500    075959  ...         0.0        0.0       0
5856  20230104   080000    080459  ...         0.0        0.0       0
5857  20230104   080500    080959  ...         0.0        0.0       0
5858  20230104   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 08:15:00,593:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672791299, self.tradeDate='20230104', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16657.1, self.close=16660.0, self.high=16661.3, self.low=16657.1, self.vol=229.669, self.amt=3826214.4396, ukdf['pct'].iloc[-1]=0.000174 , ukdf['amount'].iloc[-1]=3826214.4396, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-7974.9535286696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16661.82714585', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=70, self.factor=0.5619442999971371, self.count=11440 

self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16661.9, self.close=16657.1, self.high=16662.4, self.low=16657.1 
2023-01-04 08:10:01,429:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16661.9, self.close=16657.1, self.high=16662.4, self.low=16657.1   
2023-01-04 08:10:01,463:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230104   074500    074959  1672789799  ...  16667.4  0.000270   1533    3
1534  20230104   075000    075459  1672790099  ...  16667.5 -0.000264   1534    4
1535  20230104   075500    075959  1672790399  ...  16667.2 -0.000024   1535    5
1536  20230104   080000    080459  1672790699  ...  16661.9 -0.000318   1536    0
1537  20230104   080500    080959  1672790999  ...  16657.1 -0.000288   1537    1

[5 rows x 11 columns]
2023-01-04 08:10:01,463:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=70, self.factor=0.5619442999971371, self.count=11441 

self.closeSec=1672791299, self.tradeDate='20230104', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16657.1, self.close=16660.0, self.high=16661.3, self.low=16657.1 
2023-01-04 08:15:00,507:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672791299, self.tradeDate='20230104', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16657.1, self.close=16660.0, self.high=16661.3, self.low=16657.1   
2023-01-04 08:15:00,549:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230104   075000    075459  1672790099  ...  16667.5 -0.000264   1534    4
1535  20230104   075500    075959  1672790399  ...  16667.2 -0.000024   1535    5
1536  20230104   080000    080459  1672790699  ...  16661.9 -0.000318   1536    0
1537  20230104   080500    080959  1672790999  ...  16657.1 -0.000288   1537    1
1538  20230104   081000    081459  1672791299  ...  16657.1  0.000174   1538    2

[5 rows x 11 columns]
2023-01-04 08:15:00,549:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-04 08:00:17,851:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230104    052959  16656.0  ...  48.750000  0.498517  0.675589
5771  20230104    055959  16661.9  ...  48.750000  0.496161  0.674764
5772  20230104    062959  16658.8  ...  48.333333  0.494076  0.675069
5773  20230104    065959  16656.1  ...  48.333333  0.504843  0.669903
5774  20230104    072959  16670.2  ...  48.333333  0.504995  0.665005

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2023-01-04 08:00:17,957:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     1  0.496226  0.503774       0  ...  NaN   NaN -0.0016  0.989681
537     1  0.495570  0.504430       0  ...  NaN   NaN -0.0016  0.989514
538     1  0.494591  0.505409       1  ...  NaN   NaN -0.0016  0.990358
539     1  0.497882  0.502118       1  ...  NaN   NaN -0.0016  0.990370
540     1  0.495006  0.504994       0  ...  NaN   NaN -0.0016  0.990180

[5 rows x 10 columns]
2023-01-04 08:00:17,974:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.496598  0.503402       0  ...  NaN   NaN -0.0016  0.990069
46     1  0.496177  0.503823       0  ...  NaN   NaN -0.0016  0.990256
47     1  0.494837  0.505163       1  ...  NaN   NaN -0.0016  0.991118
48     1  0.497882  0.502118       1  ...  NaN   NaN -0.0016  0.990370
49     1  0.495006  0.504994       0  ...  NaN   NaN -0.0016  0.990180

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-1458.7104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16667.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230104   074000    074959  1672789799  16665.6    16672  0.000384
2023-01-04 07:50:00,604:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5719 

self.closeSec=1672790399, self.tradeDate='20230104', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16672', self.close='16667.2'
2023-01-04 08:00:01,096:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672790399, self.tradeDate='20230104', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16672', self.close='16667.2'
2023-01-04 08:00:01,153:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230104   071000    071959  1672787999  16683.1  16676.7 -0.000384
620  20230104   072000    072959  1672788599  16676.7  16670.4 -0.000378
621  20230104   073000    073959  1672789199  16670.4  16665.6 -0.000288
622  20230104   074000    074959  1672789799  16665.6    16672  0.000384
623  20230104   075000    075959  1672790399    16672  16667.2 -0.000288
2023-01-04 08:00:01,153:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5720 

self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16667.3', self.close='16657.1'
2023-01-04 08:10:01,558:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16667.3', self.close='16657.1'
2023-01-04 08:10:01,622:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230104   072000    072959  1672788599  16676.7  16670.4 -0.000378
621  20230104   073000    073959  1672789199  16670.4  16665.6 -0.000288
622  20230104   074000    074959  1672789799  16665.6    16672  0.000384
623  20230104   075000    075959  1672790399    16672  16667.2 -0.000288
624  20230104   080000    080959  1672790999  16667.3  16657.1 -0.000606
2023-01-04 08:10:01,622:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230104   074000    074959  1672789799  16665.6    16672
2023-01-04 07:50:00,627:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5720 

self.closeSec=1672790399, self.tradeDate='20230104', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16672', self.close='16667.2'
2023-01-04 08:00:01,099:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672790399, self.tradeDate='20230104', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16672', self.close='16667.2'
2023-01-04 08:00:01,151:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230104   071000    071959  1672787999  16683.1  16676.7
17468  20230104   072000    072959  1672788599  16676.7  16670.4
17469  20230104   073000    073959  1672789199  16670.4  16665.6
17470  20230104   074000    074959  1672789799  16665.6    16672
17471  20230104   075000    075959  1672790399    16672  16667.2
2023-01-04 08:00:01,152:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5721 

self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16667.3', self.close='16657.1'
127.0.0.1 - - [04/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-04 08:10:01,543:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16667.3', self.close='16657.1'
2023-01-04 08:10:01,598:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230104   072000    072959  1672788599  16676.7  16670.4
17469  20230104   073000    073959  1672789199  16670.4  16665.6
17470  20230104   074000    074959  1672789799  16665.6    16672
17471  20230104   075000    075959  1672790399    16672  16667.2
17472  20230104   080000    080959  1672790999  16667.3  16657.1
2023-01-04 08:10:01,598:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230104   074000    074959  1672789799  16665.6    16672
2023-01-04 07:50:00,607:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5720 

self.closeSec=1672790399, self.tradeDate='20230104', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16672', self.close='16667.2'
2023-01-04 08:00:01,128:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672790399, self.tradeDate='20230104', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16672', self.close='16667.2'
2023-01-04 08:00:01,167:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230104   071000    071959  1672787999  16683.1  16676.7
12140  20230104   072000    072959  1672788599  16676.7  16670.4
12141  20230104   073000    073959  1672789199  16670.4  16665.6
12142  20230104   074000    074959  1672789799  16665.6    16672
12143  20230104   075000    075959  1672790399    16672  16667.2
2023-01-04 08:00:01,168:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5721 

self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16667.3', self.close='16657.1'
2023-01-04 08:10:01,518:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16667.3', self.close='16657.1'
2023-01-04 08:10:01,608:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230104   072000    072959  1672788599  16676.7  16670.4
12141  20230104   073000    073959  1672789199  16670.4  16665.6
12142  20230104   074000    074959  1672789799  16665.6    16672
12143  20230104   075000    075959  1672790399    16672  16667.2
12144  20230104   080000    080959  1672790999  16667.3  16657.1
2023-01-04 08:10:01,609:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [04/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6872
self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16661.9, self.close=16657.1, self.high=16662.4, self.low=16657.1, self.vol=387.769, self.amt=6460466.3966 
2023-01-04 08:10:01,637:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230104   074500    074959  ...         0.0        0.0       0
5854  20230104   075000    075459  ...         0.0        0.0       0
5855  20230104   075500    075959  ...         0.0        0.0       0
5856  20230104   080000    080459  ...         0.0        0.0       0
5857  20230104   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 08:10:01,638:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672790999, self.tradeDate='20230104', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16661.9, self.close=16657.1, self.high=16662.4, self.low=16657.1, self.vol=387.769, self.amt=6460466.3966, ukdf['pct'].iloc[-1]=-0.000288 , ukdf['amount'].iloc[-1]=6460466.3966, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6873
self.closeSec=1672791299, self.tradeDate='20230104', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16657.1, self.close=16660.0, self.high=16661.3, self.low=16657.1, self.vol=229.669, self.amt=3826214.4396 
127.0.0.1 - - [04/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-04 08:15:00,592:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230104   075000    075459  ...         0.0        0.0       0
5855  20230104   075500    075959  ...         0.0        0.0       0
5856  20230104   080000    080459  ...         0.0        0.0       0
5857  20230104   080500    080959  ...         0.0        0.0       0
5858  20230104   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 08:15:00,592:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672791299, self.tradeDate='20230104', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16657.1, self.close=16660.0, self.high=16661.3, self.low=16657.1, self.vol=229.669, self.amt=3826214.4396, ukdf['pct'].iloc[-1]=0.000174 , ukdf['amount'].iloc[-1]=3826214.4396, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230103   200000    235959  1672761599  ...    719  0.425551  1.079751     1.0
720  20230104   000000    035959  1672775999  ...    720  0.821427  2.883686     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-4503.5055647322', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16637.75784414', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=238
self.closeSec=1672790399, self.tradeDate='20230104', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16637.6, self.close=16667.2, self.high=16688.2, self.low=16636.0, self.vol=20681.239, self.amt=344569849.8403 
127.0.0.1 - - [04/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-04 08:00:00,965:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672790399, self.tradeDate='20230104', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16637.6, self.close=16667.2, self.high=16688.2, self.low=16636.0, self.vol=20681.239, self.amt=344569849.8403 
2023-01-04 08:00:01,006:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230103   120000    155959  ...  29396.023  4.915810e+08  0.002314
718  20230103   160000    195959  ...  22008.402  3.680183e+08 -0.000532
719  20230103   200000    235959  ...  73811.270  1.231384e+09 -0.002597
720  20230104   000000    035959  ...  35119.476  5.841547e+08 -0.001986
721  20230104   040000    075959  ...  20681.239  3.445698e+08  0.001773

[5 rows x 11 columns]
2023-01-04 08:00:02,252:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230103   120000    155959  1672732799  ...    717  0.350542  0.614121     1.0
718  20230103   160000    195959  1672747199  ...    718  0.446284  1.070450     1.0
719  20230103   200000    235959  1672761599  ...    719  0.425551  1.079751     1.0
720  20230104   000000    035959  1672775999  ...    720  0.821427  2.883686     1.0
721  20230104   040000    075959  1672790399  ...    721  0.770401  2.618052     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-2939.9952351579', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16667.38661673', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


