# 20230202 08:35:46

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [02/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19230
self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23760.5, self.close=23736.2, self.high=23766.8, self.low=23723.1, self.vol=1141.365, self.amt=27095511.2631 
2023-02-02 08:30:01,079:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230202   080500    080959  ...         0.0        0.0       0
5858  20230202   081000    081459  ...         0.0        0.0       0
5859  20230202   081500    081959  ...         0.0        0.0       0
5860  20230202   082000    082459  ...         0.0        0.0       0
5861  20230202   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 08:30:01,079:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23760.5, self.close=23736.2, self.high=23766.8, self.low=23723.1, self.vol=1141.365, self.amt=27095511.2631, ukdf['pct'].iloc[-1]=-0.001023 , ukdf['amount'].iloc[-1]=27095511.2631, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-433518.38601110448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23733.47418923', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19231
self.closeSec=1675298099, self.tradeDate='20230202', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23732.6, self.close=23767.9, self.high=23820.3, self.low=23730.9, self.vol=3263.766, self.amt=77633876.9043 
2023-02-02 08:35:00,499:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230202   081000    081459  ...         0.0        0.0       0
5859  20230202   081500    081959  ...         0.0        0.0       0
5860  20230202   082000    082459  ...         0.0        0.0       0
5861  20230202   082500    082959  ...         0.0        0.0       0
5862  20230202   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 08:35:00,502:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675298099, self.tradeDate='20230202', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23732.6, self.close=23767.9, self.high=23820.3, self.low=23730.9, self.vol=3263.766, self.amt=77633876.9043, ukdf['pct'].iloc[-1]=0.001336 , ukdf['amount'].iloc[-1]=77633876.9043, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-435979.59425529632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23774.37435282', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230202   082000    082459  1675297499  ...  23716.5  0.001640   1540    4
1541  20230202   082500    082959  1675297799  ...  23723.1 -0.001023   1541    5

[5 rows x 11 columns]
2023-02-02 08:30:01,051:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-02 08:30:01,108:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230202   062500    062959  1675290599  ... -0.001284   1517    5  0.424469
214  20230202   065500    065959  1675292399  ...  0.000713   1523    5  0.415508
215  20230202   072500    072959  1675294199  ... -0.000505   1529    5  0.405534
216  20230202   075500    075959  1675295999  ...  0.000941   1535    5  0.396705
217  20230202   082500    082959  1675297799  ... -0.001023   1541    5  0.387912

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=19, self.factor=0.38791207971634356, self.count=19797 

self.closeSec=1675298099, self.tradeDate='20230202', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23732.6, self.close=23767.9, self.high=23820.3, self.low=23730.9 
2023-02-02 08:35:00,455:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675298099, self.tradeDate='20230202', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23732.6, self.close=23767.9, self.high=23820.3, self.low=23730.9   
127.0.0.1 - - [02/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-02 08:35:00,499:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230202   081000    081459  1675296899  ...  23694.5  0.000329   1538    2
1539  20230202   081500    081959  1675297199  ...  23713.6 -0.000030   1539    3
1540  20230202   082000    082459  1675297499  ...  23716.5  0.001640   1540    4
1541  20230202   082500    082959  1675297799  ...  23723.1 -0.001023   1541    5
1542  20230202   083000    083459  1675298099  ...  23730.9  0.001336   1542    0

[5 rows x 11 columns]
2023-02-02 08:35:00,500:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-02 08:30:32,044:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230202    055959  23718.9  ...  50.000000  0.611643  0.400667
5772  20230202    062959  23684.8  ...  50.416667  0.618571  0.381277
5773  20230202    065959  23730.3  ...  50.416667  0.615546  0.363934
5774  20230202    072959  23718.4  ...  50.416667  0.621827  0.345238
5775  20230202    075959  23764.8  ...  50.000000  0.614416  0.329605

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2023-02-02 08:30:32,180:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.540830  0.459170       1  ...  0.946466   1.0    0.0  1.021936
537     0  0.529267  0.470733       0  ...  0.945967   1.0    0.0  1.021398
538     0  0.506485  0.493515       1  ...  0.947626   1.0    0.0  1.023190
539     0  0.517777  0.482223       0  ...  0.946426   1.0    0.0  1.021893
540     1  0.493028  0.506972       1  ...  0.946673   1.0    0.0  1.022160

[5 rows x 10 columns]
2023-02-02 08:30:32,212:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.541246  0.458754       1  ...  0.946466   1.0    0.0  1.026783
46     0  0.528757  0.471243       0  ...  0.945967   1.0    0.0  1.022658
47     0  0.505496  0.494504       1  ...  0.947626   1.0    0.0  1.023106
48     0  0.516854  0.483146       0  ...  0.946426   1.0    0.0  1.021810
49     1  0.493028  0.506972       1  ...  0.946673   1.0    0.0  1.022160

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.955', 'enterprice': '23100.3', 'countrevence': '0', 'unrealprofit': '19848.25868987475', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23741.49717945', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230202   080000    080959  1675296599  23730.1  23714.5 -0.000653
2023-02-02 08:10:01,544:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9897 

self.closeSec=1675297199, self.tradeDate='20230202', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23714.5', self.close='23721.6'
2023-02-02 08:20:00,563:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675297199, self.tradeDate='20230202', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23714.5', self.close='23721.6'
2023-02-02 08:20:00,603:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230202   073000    073959  1675294799  23764.8  23695.8 -0.002706
622  20230202   074000    074959  1675295399  23695.9  23707.8  0.000506
623  20230202   075000    075959  1675295999  23707.9    23730  0.000936
624  20230202   080000    080959  1675296599  23730.1  23714.5 -0.000653
625  20230202   081000    081959  1675297199  23714.5  23721.6  0.000299
2023-02-02 08:20:00,603:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9898 

self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23721.7', self.close='23736.2'
2023-02-02 08:30:01,359:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23721.7', self.close='23736.2'
2023-02-02 08:30:01,366:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230202   074000    074959  1675295399  23695.9  23707.8  0.000506
623  20230202   075000    075959  1675295999  23707.9    23730  0.000936
624  20230202   080000    080959  1675296599  23730.1  23714.5 -0.000653
625  20230202   081000    081959  1675297199  23714.5  23721.6  0.000299
626  20230202   082000    082959  1675297799  23721.7  23736.2  0.000615
2023-02-02 08:30:01,366:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230202   080000    080959  1675296599  23730.1  23714.5
2023-02-02 08:10:01,561:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9898 

self.closeSec=1675297199, self.tradeDate='20230202', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23714.5', self.close='23721.6'
2023-02-02 08:20:00,535:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675297199, self.tradeDate='20230202', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23714.5', self.close='23721.6'
2023-02-02 08:20:00,624:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230202   073000    073959  1675294799  23764.8  23695.8
17470  20230202   074000    074959  1675295399  23695.9  23707.8
17471  20230202   075000    075959  1675295999  23707.9    23730
17472  20230202   080000    080959  1675296599  23730.1  23714.5
17473  20230202   081000    081959  1675297199  23714.5  23721.6
2023-02-02 08:20:00,624:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9899 

self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23721.7', self.close='23736.2'
2023-02-02 08:30:01,377:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23721.7', self.close='23736.2'
127.0.0.1 - - [02/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-02 08:30:01,385:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230202   074000    074959  1675295399  23695.9  23707.8
17471  20230202   075000    075959  1675295999  23707.9    23730
17472  20230202   080000    080959  1675296599  23730.1  23714.5
17473  20230202   081000    081959  1675297199  23714.5  23721.6
17474  20230202   082000    082959  1675297799  23721.7  23736.2
2023-02-02 08:30:01,388:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230202   080000    080959  1675296599  23730.1  23714.5
2023-02-02 08:10:01,554:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [02/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9898 

self.closeSec=1675297199, self.tradeDate='20230202', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23714.5', self.close='23721.6'
2023-02-02 08:20:00,568:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675297199, self.tradeDate='20230202', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23714.5', self.close='23721.6'
2023-02-02 08:20:00,611:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230202   073000    073959  1675294799  23764.8  23695.8
12142  20230202   074000    074959  1675295399  23695.9  23707.8
12143  20230202   075000    075959  1675295999  23707.9    23730
12144  20230202   080000    080959  1675296599  23730.1  23714.5
12145  20230202   081000    081959  1675297199  23714.5  23721.6
2023-02-02 08:20:00,611:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [02/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9899 

self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23721.7', self.close='23736.2'
2023-02-02 08:30:01,367:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23721.7', self.close='23736.2'
2023-02-02 08:30:01,403:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230202   074000    074959  1675295399  23695.9  23707.8
12143  20230202   075000    075959  1675295999  23707.9    23730
12144  20230202   080000    080959  1675296599  23730.1  23714.5
12145  20230202   081000    081959  1675297199  23714.5  23721.6
12146  20230202   082000    082959  1675297799  23721.7  23736.2
2023-02-02 08:30:01,403:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [02/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15228
self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23760.5, self.close=23736.2, self.high=23766.8, self.low=23723.1, self.vol=1141.365, self.amt=27095511.2631 
2023-02-02 08:30:00,995:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230202   080500    080959  ...         0.0        0.0       0
5858  20230202   081000    081459  ...         0.0        0.0       0
5859  20230202   081500    081959  ...         0.0        0.0       0
5860  20230202   082000    082459  ...         0.0        0.0       0
5861  20230202   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 08:30:00,995:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675297799, self.tradeDate='20230202', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23760.5, self.close=23736.2, self.high=23766.8, self.low=23723.1, self.vol=1141.365, self.amt=27095511.2631, ukdf['pct'].iloc[-1]=-0.001023 , ukdf['amount'].iloc[-1]=27095511.2631, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15229
self.closeSec=1675298099, self.tradeDate='20230202', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23732.6, self.close=23767.9, self.high=23820.3, self.low=23730.9, self.vol=3263.766, self.amt=77633876.9043 
2023-02-02 08:35:00,546:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230202   081000    081459  ...         0.0        0.0       0
5859  20230202   081500    081959  ...         0.0        0.0       0
5860  20230202   082000    082459  ...         0.0        0.0       0
5861  20230202   082500    082959  ...         0.0        0.0       0
5862  20230202   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 08:35:00,549:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675298099, self.tradeDate='20230202', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23732.6, self.close=23767.9, self.high=23820.3, self.low=23730.9, self.vol=3263.766, self.amt=77633876.9043, ukdf['pct'].iloc[-1]=0.001336 , ukdf['amount'].iloc[-1]=77633876.9043, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230201   200000    235959  1675267199  ...    719  0.637503  0.529206     NaN
720  20230202   000000    035959  1675281599  ...    720  0.509222  0.146437     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-12043.7724', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23391', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [02/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=412
self.closeSec=1675295999, self.tradeDate='20230202', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23379.8, self.close=23730.0, self.high=23852.4, self.low=23320.0, self.vol=160059.153, self.amt=3779793945.47008 
2023-02-02 08:00:02,351:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675295999, self.tradeDate='20230202', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23379.8, self.close=23730.0, self.high=23852.4, self.low=23320.0, self.vol=160059.153, self.amt=3779793945.47008 
2023-02-02 08:00:02,372:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230201   120000    155959  ...   33068.509  7.638194e+08 -0.002434
718  20230201   160000    195959  ...   50557.370  1.163133e+09  0.000221
719  20230201   200000    235959  ...   71259.336  1.643445e+09 -0.004351
720  20230202   000000    035959  ...  215468.368  4.979553e+09  0.017592
721  20230202   040000    075959  ...  160059.153  3.779794e+09  0.014974

[5 rows x 11 columns]
2023-02-02 08:00:04,391:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230201   120000    155959  1675238399  ...    717  0.643037  0.550769     NaN
718  20230201   160000    195959  1675252799  ...    718  0.646420  0.560265     NaN
719  20230201   200000    235959  1675267199  ...    719  0.637503  0.529206     NaN
720  20230202   000000    035959  1675281599  ...    720  0.509222  0.146437     NaN
721  20230202   040000    075959  1675295999  ...    721  0.558106  0.277750     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '1214.95668215832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23731.28151838', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


