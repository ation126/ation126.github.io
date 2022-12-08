# 20221208 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3098
self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16825.6, self.close=16826.5, self.high=16828.6, self.low=16821.9, self.vol=360.056, self.amt=6057796.1861 
127.0.0.1 - - [08/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-08 08:10:01,436:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221208   074500    074959  ...    0.123610   0.271563       0
5854  20221208   075000    075459  ...    0.123415   0.271400       0
5855  20221208   075500    075959  ...    0.123220   0.271236       0
5856  20221208   080000    080459  ...    0.123024   0.271071       0
5857  20221208   080500    080959  ...    0.122833   0.270914       0

[5 rows x 18 columns]
2022-12-08 08:10:01,436:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16825.6, self.close=16826.5, self.high=16828.6, self.low=16821.9, self.vol=360.056, self.amt=6057796.1861, ukdf['pct'].iloc[-1]=3.6e-05 , ukdf['amount'].iloc[-1]=6057796.1861, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.12283270046114356, signal=0, value_std=0.27091417698293424 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17905.81487686512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16826.85741287', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3099
self.closeSec=1670458499, self.tradeDate='20221208', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16826.6, self.close=16835.3, self.high=16839.4, self.low=16826.5, self.vol=502.687, self.amt=8462509.088 
2022-12-08 08:15:00,549:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221208   075000    075459  ...    0.123415   0.271400       0
5855  20221208   075500    075959  ...    0.123220   0.271236       0
5856  20221208   080000    080459  ...    0.123024   0.271071       0
5857  20221208   080500    080959  ...    0.122833   0.270914       0
5858  20221208   081000    081459  ...    0.122640   0.270755       0

[5 rows x 18 columns]
2022-12-08 08:15:00,550:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670458499, self.tradeDate='20221208', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16826.6, self.close=16835.3, self.high=16839.4, self.low=16826.5, self.vol=502.687, self.amt=8462509.088, ukdf['pct'].iloc[-1]=0.000523 , ukdf['amount'].iloc[-1]=8462509.088, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.12263992538756613, signal=0, value_std=0.27075455355261485 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-18448.15807894448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16835.87002923', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16825.6, self.close=16826.5, self.high=16828.6, self.low=16821.9 
2022-12-08 08:10:01,406:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16825.6, self.close=16826.5, self.high=16828.6, self.low=16821.9   
127.0.0.1 - - [08/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-08 08:10:01,417:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221208   074500    074959  1670456999  ...  16836.5 -0.000534   1533    3
1534  20221208   075000    075459  1670457299  ...  16815.8 -0.000315   1534    4
1535  20221208   075500    075959  1670457599  ...  16818.9 -0.000196   1535    5
1536  20221208   080000    080459  1670457899  ...  16823.8 -0.000125   1536    0
1537  20221208   080500    080959  1670458199  ...  16821.9  0.000036   1537    1

[5 rows x 11 columns]
2022-12-08 08:10:01,417:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7022310335417011, self.count=3665 

self.closeSec=1670458499, self.tradeDate='20221208', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16826.6, self.close=16835.3, self.high=16839.4, self.low=16826.5 
2022-12-08 08:15:00,533:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670458499, self.tradeDate='20221208', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16826.6, self.close=16835.3, self.high=16839.4, self.low=16826.5   
127.0.0.1 - - [08/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-08 08:15:00,548:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221208   075000    075459  1670457299  ...  16815.8 -0.000315   1534    4
1535  20221208   075500    075959  1670457599  ...  16818.9 -0.000196   1535    5
1536  20221208   080000    080459  1670457899  ...  16823.8 -0.000125   1536    0
1537  20221208   080500    080959  1670458199  ...  16821.9  0.000036   1537    1
1538  20221208   081000    081459  1670458499  ...  16826.5  0.000523   1538    2

[5 rows x 11 columns]
2022-12-08 08:15:00,549:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-08 08:00:17,258:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221208    052959  16811.7  ...  50.416667  0.441677  0.652662
5771  20221208    055959  16810.7  ...  50.833333  0.448772  0.647808
5772  20221208    062959  16821.2  ...  50.416667  0.444281  0.644678
5773  20221208    065959  16813.5  ...  50.416667  0.455788  0.637908
5774  20221208    072959  16834.0  ...  50.416667  0.459464  0.629623

[5 rows x 33 columns]
0.5397412199630314
acc is : 0.5397412199630314
2022-12-08 08:00:17,318:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.487497  0.512503       1  ...  0.961684  -1.0    0.0  1.018717
537     1  0.491018  0.508982       0  ...  0.962250  -1.0    0.0  1.018118
538     1  0.484846  0.515154       1  ...  0.961077  -1.0    0.0  1.019359
539     1  0.493076  0.506924       1  ...  0.960700  -1.0    0.0  1.019759
540     1  0.490811  0.509189       0  ...  0.961419  -1.0    0.0  1.018996

[5 rows x 10 columns]
2022-12-08 08:00:17,329:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487818  0.512182       1  ...  0.947866  -1.0    0.0  1.019198
46     1  0.490938  0.509062       0  ...  0.962250  -1.0    0.0  1.017397
47     1  0.485260  0.514740       1  ...  0.947268  -1.0    0.0  1.020181
48     1  0.493076  0.506924       1  ...  0.960700  -1.0    0.0  1.019759
49     1  0.490811  0.509189       0  ...  0.961419  -1.0    0.0  1.018996

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '5215.28', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16830.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221208   074000    074959  1670456999  16844.2  16836.5 -0.000457
2022-12-08 07:50:00,534:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1831 

self.closeSec=1670457599, self.tradeDate='20221208', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16836.6', self.close='16828'
2022-12-08 08:00:00,962:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670457599, self.tradeDate='20221208', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16836.6', self.close='16828'
2022-12-08 08:00:00,987:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221208   071000    071959  1670455199  16841.2  16835.8 -0.000327
620  20221208   072000    072959  1670455799  16835.7  16840.6  0.000285
621  20221208   073000    073959  1670456399  16840.5  16844.2  0.000214
622  20221208   074000    074959  1670456999  16844.2  16836.5 -0.000457
623  20221208   075000    075959  1670457599  16836.6    16828 -0.000505
2022-12-08 08:00:00,989:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1832 

self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16828', self.close='16826.6'
2022-12-08 08:10:01,496:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16828', self.close='16826.6'
2022-12-08 08:10:01,517:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221208   072000    072959  1670455799  16835.7  16840.6  0.000285
621  20221208   073000    073959  1670456399  16840.5  16844.2  0.000214
622  20221208   074000    074959  1670456999  16844.2  16836.5 -0.000457
623  20221208   075000    075959  1670457599  16836.6    16828 -0.000505
624  20221208   080000    080959  1670458199    16828  16826.6 -0.000083
2022-12-08 08:10:01,517:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221208   074000    074959  1670456999  16844.2  16836.5
2022-12-08 07:50:00,540:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1832 

self.closeSec=1670457599, self.tradeDate='20221208', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16836.6', self.close='16828'
127.0.0.1 - - [08/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -
2022-12-08 08:00:00,966:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670457599, self.tradeDate='20221208', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16836.6', self.close='16828'
2022-12-08 08:00:01,001:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221208   071000    071959  1670455199  16841.2  16835.8
17468  20221208   072000    072959  1670455799  16835.7  16840.6
17469  20221208   073000    073959  1670456399  16840.5  16844.2
17470  20221208   074000    074959  1670456999  16844.2  16836.5
17471  20221208   075000    075959  1670457599  16836.6    16828
2022-12-08 08:00:01,013:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1833 

self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16828', self.close='16826.6'
2022-12-08 08:10:01,505:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16828', self.close='16826.6'
2022-12-08 08:10:01,525:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221208   072000    072959  1670455799  16835.7  16840.6
17469  20221208   073000    073959  1670456399  16840.5  16844.2
17470  20221208   074000    074959  1670456999  16844.2  16836.5
17471  20221208   075000    075959  1670457599  16836.6    16828
17472  20221208   080000    080959  1670458199    16828  16826.6
2022-12-08 08:10:01,525:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221208   074000    074959  1670456999  16844.2  16836.5
2022-12-08 07:50:00,524:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1832 

self.closeSec=1670457599, self.tradeDate='20221208', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16836.6', self.close='16828'
127.0.0.1 - - [08/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -
2022-12-08 08:00:00,972:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670457599, self.tradeDate='20221208', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16836.6', self.close='16828'
2022-12-08 08:00:00,993:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221208   071000    071959  1670455199  16841.2  16835.8
12140  20221208   072000    072959  1670455799  16835.7  16840.6
12141  20221208   073000    073959  1670456399  16840.5  16844.2
12142  20221208   074000    074959  1670456999  16844.2  16836.5
12143  20221208   075000    075959  1670457599  16836.6    16828
2022-12-08 08:00:00,993:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [08/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1833 

self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16828', self.close='16826.6'
2022-12-08 08:10:01,493:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670458199, self.tradeDate='20221208', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16828', self.close='16826.6'
2022-12-08 08:10:01,511:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221208   072000    072959  1670455799  16835.7  16840.6
12141  20221208   073000    073959  1670456399  16840.5  16844.2
12142  20221208   074000    074959  1670456999  16844.2  16836.5
12143  20221208   075000    075959  1670457599  16836.6    16828
12144  20221208   080000    080959  1670458199    16828  16826.6
2022-12-08 08:10:01,511:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221207   200000    235959  1670428799  ...    719  0.741914  1.167551     1.0
720  20221208   000000    035959  1670443199  ...    720  0.808755  1.407951     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-28972.36914822196', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16807.27651482', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [08/Dec/2022 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=76
self.closeSec=1670457599, self.tradeDate='20221208', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16807.4, self.close=16828.0, self.high=16856.8, self.low=16783.8, self.vol=24456.653, self.amt=411448321.56 
2022-12-08 08:00:00,843:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670457599, self.tradeDate='20221208', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16807.4, self.close=16828.0, self.high=16856.8, self.low=16783.8, self.vol=24456.653, self.amt=411448321.56 
2022-12-08 08:00:00,883:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221207   120000    155959  ...  97327.468  1.641001e+09 -0.015378
718  20221207   160000    195959  ...  68360.933  1.147011e+09  0.001874
719  20221207   200000    235959  ...  70616.715  1.188355e+09  0.002502
720  20221208   000000    035959  ...  34665.520  5.824289e+08 -0.001283
721  20221208   040000    075959  ...  24456.653  4.114483e+08  0.001220

[5 rows x 11 columns]
2022-12-08 08:00:01,663:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221207   120000    155959  1670399999  ...    717  0.702535  1.042009     1.0
718  20221207   160000    195959  1670414399  ...    718  0.718504  1.093072     1.0
719  20221207   200000    235959  1670428799  ...    719  0.741914  1.167551     1.0
720  20221208   000000    035959  1670443199  ...    720  0.808755  1.407951     1.0
721  20221208   040000    075959  1670457599  ...    721  0.877063  1.638632     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-27751.6548', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16828.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


