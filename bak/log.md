# 20221217 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5690
self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16629.9, self.close=16664.8, self.high=16665.6, self.low=16618.5, self.vol=2997.944, self.amt=49894731.9755 
127.0.0.1 - - [17/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-17 08:10:01,424:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221217   074500    074959  ...         0.0        0.0       0
5854  20221217   075000    075459  ...         0.0        0.0       0
5855  20221217   075500    075959  ...         0.0        0.0       0
5856  20221217   080000    080459  ...         0.0        0.0       0
5857  20221217   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-17 08:10:01,425:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16629.9, self.close=16664.8, self.high=16665.6, self.low=16618.5, self.vol=2997.944, self.amt=49894731.9755, ukdf['pct'].iloc[-1]=0.002183 , ukdf['amount'].iloc[-1]=49894731.9755, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-8159.8656', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16664.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5691
self.closeSec=1671236099, self.tradeDate='20221217', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16664.7, self.close=16684.4, self.high=16699.0, self.low=16664.1, self.vol=4080.511, self.amt=68070342.2761 
2022-12-17 08:15:00,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221217   075000    075459  ...         0.0        0.0       0
5855  20221217   075500    075959  ...         0.0        0.0       0
5856  20221217   080000    080459  ...         0.0        0.0       0
5857  20221217   080500    080959  ...         0.0        0.0       0
5858  20221217   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-17 08:15:00,578:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671236099, self.tradeDate='20221217', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16664.7, self.close=16684.4, self.high=16699.0, self.low=16664.1, self.vol=4080.511, self.amt=68070342.2761, ukdf['pct'].iloc[-1]=0.001176 , ukdf['amount'].iloc[-1]=68070342.2761, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-9327.28', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16684.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8402996871674936, self.count=6256 

self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16629.9, self.close=16664.8, self.high=16665.6, self.low=16618.5 
2022-12-17 08:10:01,416:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16629.9, self.close=16664.8, self.high=16665.6, self.low=16618.5   
2022-12-17 08:10:01,473:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221217   074500    074959  1671234599  ...  16592.5 -0.001113   1533    3
1534  20221217   075000    075459  1671234899  ...  16589.7  0.000211   1534    4
1535  20221217   075500    075959  1671235199  ...  16599.1  0.001398   1535    5
1536  20221217   080000    080459  1671235499  ...  16593.4  0.000265   1536    0
1537  20221217   080500    080959  1671235799  ...  16618.5  0.002183   1537    1

[5 rows x 11 columns]
2022-12-17 08:10:01,473:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8402996871674936, self.count=6257 

self.closeSec=1671236099, self.tradeDate='20221217', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16664.7, self.close=16684.4, self.high=16699.0, self.low=16664.1 
2022-12-17 08:15:00,514:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671236099, self.tradeDate='20221217', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16664.7, self.close=16684.4, self.high=16699.0, self.low=16664.1   
127.0.0.1 - - [17/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-17 08:15:00,568:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221217   075000    075459  1671234899  ...  16589.7  0.000211   1534    4
1535  20221217   075500    075959  1671235199  ...  16599.1  0.001398   1535    5
1536  20221217   080000    080459  1671235499  ...  16593.4  0.000265   1536    0
1537  20221217   080500    080959  1671235799  ...  16618.5  0.002183   1537    1
1538  20221217   081000    081459  1671236099  ...  16664.1  0.001176   1538    2

[5 rows x 11 columns]
2022-12-17 08:15:00,568:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-17 08:00:20,506:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221217    052959  16864.0  ...  48.750000  0.373851  0.822782
5771  20221217    055959  16838.1  ...  48.750000  0.371238  0.824484
5772  20221217    062959  16825.5  ...  48.750000  0.378157  0.824502
5773  20221217    065959  16845.1  ...  48.750000  0.351822  0.833083
5774  20221217    072959  16715.0  ...  48.333333  0.329455  0.840847

[5 rows x 33 columns]
0.5582255083179297
acc is : 0.5582255083179297
2022-12-17 08:00:20,612:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.497497  0.502503       0  ...  1.069717  -1.0    0.0  0.985804
537     1  0.499277  0.500723       1  ...  1.068478  -1.0    0.0  0.986946
538     0  0.502059  0.497941       0  ...  1.076723  -1.0    0.0  0.979330
539     1  0.449115  0.550885       0  ...  1.084724  -1.0    0.0  0.972053
540     1  0.444231  0.555769       1  ...  1.082553  -1.0    0.0  0.973998

[5 rows x 10 columns]
2022-12-17 08:00:20,641:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497282  0.502718       0  ...  1.069717  -1.0    0.0  0.985463
46     1  0.499884  0.500116       1  ...  1.068478  -1.0    0.0  0.988156
47     0  0.502335  0.497665       0  ...  1.076723  -1.0    0.0  0.981175
48     1  0.449115  0.550885       0  ...  1.084724  -1.0    0.0  0.972053
49     1  0.444231  0.555769       1  ...  1.082553  -1.0    0.0  0.973998

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '43412.81365124976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16618.58864706', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221217   074000    074959  1671234599  16584.4  16597.3  0.000778
2022-12-17 07:50:00,561:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [17/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3127 

self.closeSec=1671235199, self.tradeDate='20221217', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16597.4', self.close='16624.1'
2022-12-17 08:00:01,557:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671235199, self.tradeDate='20221217', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16597.4', self.close='16624.1'
2022-12-17 08:00:01,579:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221217   071000    071959  1671232799    16636  16583.6 -0.003150
620  20221217   072000    072959  1671233399  16582.1  16590.9  0.000440
621  20221217   073000    073959  1671233999    16591  16584.4 -0.000392
622  20221217   074000    074959  1671234599  16584.4  16597.3  0.000778
623  20221217   075000    075959  1671235199  16597.4  16624.1  0.001615
2022-12-17 08:00:01,583:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3128 

self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16624.1', self.close='16663.2'
2022-12-17 08:10:01,503:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16624.1', self.close='16663.2'
2022-12-17 08:10:01,510:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221217   072000    072959  1671233399  16582.1  16590.9  0.000440
621  20221217   073000    073959  1671233999    16591  16584.4 -0.000392
622  20221217   074000    074959  1671234599  16584.4  16597.3  0.000778
623  20221217   075000    075959  1671235199  16597.4  16624.1  0.001615
624  20221217   080000    080959  1671235799  16624.1  16663.2  0.002352
2022-12-17 08:10:01,511:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221217   074000    074959  1671234599  16584.4  16597.3
2022-12-17 07:50:00,559:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3128 

self.closeSec=1671235199, self.tradeDate='20221217', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16597.4', self.close='16624.1'
127.0.0.1 - - [17/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-17 08:00:01,541:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671235199, self.tradeDate='20221217', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16597.4', self.close='16624.1'
2022-12-17 08:00:01,581:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221217   071000    071959  1671232799    16636  16583.6
17468  20221217   072000    072959  1671233399  16582.1  16590.9
17469  20221217   073000    073959  1671233999    16591  16584.4
17470  20221217   074000    074959  1671234599  16584.4  16597.3
17471  20221217   075000    075959  1671235199  16597.4  16624.1
2022-12-17 08:00:01,586:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3129 

self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16624.1', self.close='16663.2'
2022-12-17 08:10:01,541:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16624.1', self.close='16663.2'
2022-12-17 08:10:01,549:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221217   072000    072959  1671233399  16582.1  16590.9
17469  20221217   073000    073959  1671233999    16591  16584.4
17470  20221217   074000    074959  1671234599  16584.4  16597.3
17471  20221217   075000    075959  1671235199  16597.4  16624.1
17472  20221217   080000    080959  1671235799  16624.1  16663.2
2022-12-17 08:10:01,549:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221217   074000    074959  1671234599  16584.4  16597.3
2022-12-17 07:50:00,564:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3128 

self.closeSec=1671235199, self.tradeDate='20221217', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16597.4', self.close='16624.1'
2022-12-17 08:00:01,538:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671235199, self.tradeDate='20221217', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16597.4', self.close='16624.1'
127.0.0.1 - - [17/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-17 08:00:01,578:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221217   071000    071959  1671232799    16636  16583.6
12140  20221217   072000    072959  1671233399  16582.1  16590.9
12141  20221217   073000    073959  1671233999    16591  16584.4
12142  20221217   074000    074959  1671234599  16584.4  16597.3
12143  20221217   075000    075959  1671235199  16597.4  16624.1
2022-12-17 08:00:01,578:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3129 

self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16624.1', self.close='16663.2'
2022-12-17 08:10:01,521:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16624.1', self.close='16663.2'
127.0.0.1 - - [17/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-17 08:10:01,530:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221217   072000    072959  1671233399  16582.1  16590.9
12141  20221217   073000    073959  1671233999    16591  16584.4
12142  20221217   074000    074959  1671234599  16584.4  16597.3
12143  20221217   075000    075959  1671235199  16597.4  16624.1
12144  20221217   080000    080959  1671235799  16624.1  16663.2
2022-12-17 08:10:01,530:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [17/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1688
self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16629.9, self.close=16664.8, self.high=16665.6, self.low=16618.5, self.vol=2997.944, self.amt=49894731.9755 
2022-12-17 08:10:01,483:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221217   074500    074959  ...    0.150242   0.291452       0
5854  20221217   075000    075459  ...    0.149825   0.291092       0
5855  20221217   075500    075959  ...    0.149406   0.290729       0
5856  20221217   080000    080459  ...    0.148984   0.290357       0
5857  20221217   080500    080959  ...    0.148567   0.289995       0

[5 rows x 18 columns]
2022-12-17 08:10:01,483:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671235799, self.tradeDate='20221217', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16629.9, self.close=16664.8, self.high=16665.6, self.low=16618.5, self.vol=2997.944, self.amt=49894731.9755, ukdf['pct'].iloc[-1]=0.002183 , ukdf['amount'].iloc[-1]=49894731.9755, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.14856681905850355, signal=0, value_std=0.2899950635766661 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [17/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1689
self.closeSec=1671236099, self.tradeDate='20221217', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16664.7, self.close=16684.4, self.high=16699.0, self.low=16664.1, self.vol=4080.511, self.amt=68070342.2761 
2022-12-17 08:15:00,575:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221217   075000    075459  ...    0.149825   0.291092       0
5855  20221217   075500    075959  ...    0.149406   0.290729       0
5856  20221217   080000    080459  ...    0.148984   0.290357       0
5857  20221217   080500    080959  ...    0.148567   0.289995       0
5858  20221217   081000    081459  ...    0.148148   0.289629       0

[5 rows x 18 columns]
2022-12-17 08:15:00,576:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671236099, self.tradeDate='20221217', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16664.7, self.close=16684.4, self.high=16699.0, self.low=16664.1, self.vol=4080.511, self.amt=68070342.2761, ukdf['pct'].iloc[-1]=0.001176 , ukdf['amount'].iloc[-1]=68070342.2761, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.14814805329126607, signal=0, value_std=0.2896285389525862 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221216   200000    235959  1671206399  ...    719  0.692185  0.053751     NaN
720  20221217   000000    035959  1671220799  ...    720  0.669449 -0.015307     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-48167.2104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16854.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=130
self.closeSec=1671235199, self.tradeDate='20221217', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16856.6, self.close=16624.1, self.high=16945.6, self.low=16521.1, self.vol=134056.77, self.amt=2240063148.3023 
127.0.0.1 - - [17/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-17 08:00:01,403:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671235199, self.tradeDate='20221217', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16856.6, self.close=16624.1, self.high=16945.6, self.low=16521.1, self.vol=134056.77, self.amt=2240063148.3023 
2022-12-17 08:00:01,431:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20221216   120000    155959  ...   41640.940  7.263423e+08  0.004455
718  20221216   160000    195959  ...  188849.287  3.229967e+09 -0.027314
719  20221216   200000    235959  ...  107276.345  1.821694e+09 -0.003338
720  20221217   000000    035959  ...  114774.620  1.931465e+09 -0.006208
721  20221217   040000    075959  ...  134056.770  2.240063e+09 -0.013787

[5 rows x 11 columns]
2022-12-17 08:00:03,104:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221216   120000    155959  1671177599  ...    717  0.991257  0.981591     1.0
718  20221216   160000    195959  1671191999  ...    718  0.725008  0.154497     NaN
719  20221216   200000    235959  1671206399  ...    719  0.692185  0.053751     NaN
720  20221217   000000    035959  1671220799  ...    720  0.669449 -0.015307     NaN
721  20221217   040000    075959  1671235199  ...    721  0.600340 -0.225650     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-60372.04255586268', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16626.49906887', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


