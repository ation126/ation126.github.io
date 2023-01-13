# 20230113 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [13/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13466
self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=18869.2, self.close=18821.9, self.high=18870.1, self.low=18811.2, self.vol=2085.395, self.amt=39274190.3378 
2023-01-13 08:10:01,723:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230113   074500    074959  ...         0.0        0.0       0
5854  20230113   075000    075459  ...         0.0        0.0       0
5855  20230113   075500    075959  ...         0.0        0.0       0
5856  20230113   080000    080459  ...         0.0        0.0       0
5857  20230113   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 08:10:01,726:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=18869.2, self.close=18821.9, self.high=18870.1, self.low=18811.2, self.vol=2085.395, self.amt=39274190.3378, ukdf['pct'].iloc[-1]=-0.002554 , ukdf['amount'].iloc[-1]=39274190.3378, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-138097.9024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18824.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13467
self.closeSec=1673568899, self.tradeDate='20230113', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=18822.5, self.close=18827.2, self.high=18835.0, self.low=18811.2, self.vol=1705.593, self.amt=32105468.2183 
2023-01-13 08:15:00,700:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230113   075000    075459  ...         0.0        0.0       0
5855  20230113   075500    075959  ...         0.0        0.0       0
5856  20230113   080000    080459  ...         0.0        0.0       0
5857  20230113   080500    080959  ...         0.0        0.0       0
5858  20230113   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 08:15:00,704:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673568899, self.tradeDate='20230113', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=18822.5, self.close=18827.2, self.high=18835.0, self.low=18811.2, self.vol=1705.593, self.amt=32105468.2183, ukdf['pct'].iloc[-1]=0.000282 , ukdf['amount'].iloc[-1]=32105468.2183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-138284.448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18827.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=255, self.factor=0.20134878453574612, self.count=14032 

self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=18869.2, self.close=18821.9, self.high=18870.1, self.low=18811.2 
2023-01-13 08:10:01,632:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=18869.2, self.close=18821.9, self.high=18870.1, self.low=18811.2   
2023-01-13 08:10:01,694:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230113   074500    074959  1673567399  ...  18863.3 -0.000583   1533    3
1534  20230113   075000    075459  1673567699  ...  18838.1 -0.000403   1534    4
1535  20230113   075500    075959  1673567999  ...  18837.3 -0.001092   1535    5
1536  20230113   080000    080459  1673568299  ...  18838.0  0.001704   1536    0
1537  20230113   080500    080959  1673568599  ...  18811.2 -0.002554   1537    1

[5 rows x 11 columns]
2023-01-13 08:10:01,695:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=255, self.factor=0.20134878453574612, self.count=14033 

self.closeSec=1673568899, self.tradeDate='20230113', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=18822.5, self.close=18827.2, self.high=18835.0, self.low=18811.2 
2023-01-13 08:15:00,571:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673568899, self.tradeDate='20230113', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=18822.5, self.close=18827.2, self.high=18835.0, self.low=18811.2   
2023-01-13 08:15:00,633:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230113   075000    075459  1673567699  ...  18838.1 -0.000403   1534    4
1535  20230113   075500    075959  1673567999  ...  18837.3 -0.001092   1535    5
1536  20230113   080000    080459  1673568299  ...  18838.0  0.001704   1536    0
1537  20230113   080500    080959  1673568599  ...  18811.2 -0.002554   1537    1
1538  20230113   081000    081459  1673568899  ...  18811.2  0.000282   1538    2

[5 rows x 11 columns]
2023-01-13 08:15:00,633:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-13 08:00:34,349:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230113    052959  19042.2  ...  57.500000  0.660592  0.200051
5771  20230113    055959  18799.9  ...  57.500000  0.663751  0.203036
5772  20230113    062959  18823.4  ...  57.500000  0.659452  0.206773
5773  20230113    065959  18805.8  ...  57.500000  0.672188  0.204670
5774  20230113    072959  18907.4  ...  57.083333  0.656640  0.206176

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-01-13 08:00:34,521:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.469151  0.530849       1  ...  1.015159   1.0    0.0  1.135625
537     0  0.516280  0.483720       0  ...  1.014226   1.0    0.0  1.134581
538     0  0.504152  0.495848       1  ...  1.019710   1.0    0.0  1.140717
539     0  0.534624  0.465376       0  ...  1.016307   1.0    0.0  1.136910
540     1  0.483961  0.516039       0  ...  1.015962   1.0    0.0  1.136524

[5 rows x 10 columns]
2023-01-13 08:00:34,564:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.468268  0.531732       1  ...  1.015159   1.0    0.0  1.137134
46     0  0.516269  0.483731       0  ...  1.014226   1.0    0.0  1.134780
47     0  0.504293  0.495707       1  ...  1.019710   1.0    0.0  1.142033
48     0  0.534624  0.465376       0  ...  1.016307   1.0    0.0  1.136910
49     1  0.483961  0.516039       0  ...  1.015962   1.0    0.0  1.136524

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230113   074000    074959  1673567399  18864.1  18866.2  0.000106
2023-01-13 07:50:00,598:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7015 

self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='18866.2', self.close='18838'
2023-01-13 08:00:01,627:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='18866.2', self.close='18838'
2023-01-13 08:00:01,678:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230113   071000    071959  1673565599  18888.3  18881.4 -0.000360
620  20230113   072000    072959  1673566199  18881.9  18844.3 -0.001965
621  20230113   073000    073959  1673566799  18844.4  18864.2  0.001056
622  20230113   074000    074959  1673567399  18864.1  18866.2  0.000106
623  20230113   075000    075959  1673567999  18866.2    18838 -0.001495
2023-01-13 08:00:01,678:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7016 

self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='18838.1', self.close='18821.9'
2023-01-13 08:10:01,753:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='18838.1', self.close='18821.9'
2023-01-13 08:10:01,775:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230113   072000    072959  1673566199  18881.9  18844.3 -0.001965
621  20230113   073000    073959  1673566799  18844.4  18864.2  0.001056
622  20230113   074000    074959  1673567399  18864.1  18866.2  0.000106
623  20230113   075000    075959  1673567999  18866.2    18838 -0.001495
624  20230113   080000    080959  1673568599  18838.1  18821.9 -0.000855
2023-01-13 08:10:01,777:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230113   074000    074959  1673567399  18864.1  18866.2
2023-01-13 07:50:00,600:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7016 

self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='18866.2', self.close='18838'
127.0.0.1 - - [13/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-13 08:00:01,589:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='18866.2', self.close='18838'
2023-01-13 08:00:01,656:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230113   071000    071959  1673565599  18888.3  18881.4
17468  20230113   072000    072959  1673566199  18881.9  18844.3
17469  20230113   073000    073959  1673566799  18844.4  18864.2
17470  20230113   074000    074959  1673567399  18864.1  18866.2
17471  20230113   075000    075959  1673567999  18866.2    18838
2023-01-13 08:00:01,656:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7017 

self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='18838.1', self.close='18821.9'
2023-01-13 08:10:01,784:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='18838.1', self.close='18821.9'
2023-01-13 08:10:01,797:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230113   072000    072959  1673566199  18881.9  18844.3
17469  20230113   073000    073959  1673566799  18844.4  18864.2
17470  20230113   074000    074959  1673567399  18864.1  18866.2
17471  20230113   075000    075959  1673567999  18866.2    18838
17472  20230113   080000    080959  1673568599  18838.1  18821.9
2023-01-13 08:10:01,797:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230113   074000    074959  1673567399  18864.1  18866.2
2023-01-13 07:50:00,553:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7016 

self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='18866.2', self.close='18838'
127.0.0.1 - - [13/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-13 08:00:01,610:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='18866.2', self.close='18838'
2023-01-13 08:00:01,667:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230113   071000    071959  1673565599  18888.3  18881.4
12140  20230113   072000    072959  1673566199  18881.9  18844.3
12141  20230113   073000    073959  1673566799  18844.4  18864.2
12142  20230113   074000    074959  1673567399  18864.1  18866.2
12143  20230113   075000    075959  1673567999  18866.2    18838
2023-01-13 08:00:01,667:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [13/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7017 

self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='18838.1', self.close='18821.9'
2023-01-13 08:10:01,784:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='18838.1', self.close='18821.9'
2023-01-13 08:10:01,825:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230113   072000    072959  1673566199  18881.9  18844.3
12141  20230113   073000    073959  1673566799  18844.4  18864.2
12142  20230113   074000    074959  1673567399  18864.1  18866.2
12143  20230113   075000    075959  1673567999  18866.2    18838
12144  20230113   080000    080959  1673568599  18838.1  18821.9
2023-01-13 08:10:01,825:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9464
self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=18869.2, self.close=18821.9, self.high=18870.1, self.low=18811.2, self.vol=2085.395, self.amt=39274190.3378 
2023-01-13 08:10:01,724:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230113   074500    074959  ...         0.0        0.0       0
5854  20230113   075000    075459  ...         0.0        0.0       0
5855  20230113   075500    075959  ...         0.0        0.0       0
5856  20230113   080000    080459  ...         0.0        0.0       0
5857  20230113   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 08:10:01,725:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673568599, self.tradeDate='20230113', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=18869.2, self.close=18821.9, self.high=18870.1, self.low=18811.2, self.vol=2085.395, self.amt=39274190.3378, ukdf['pct'].iloc[-1]=-0.002554 , ukdf['amount'].iloc[-1]=39274190.3378, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [13/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9465
self.closeSec=1673568899, self.tradeDate='20230113', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=18822.5, self.close=18827.2, self.high=18835.0, self.low=18811.2, self.vol=1705.593, self.amt=32105468.2183 
2023-01-13 08:15:00,696:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230113   075000    075459  ...         0.0        0.0       0
5855  20230113   075500    075959  ...         0.0        0.0       0
5856  20230113   080000    080459  ...         0.0        0.0       0
5857  20230113   080500    080959  ...         0.0        0.0       0
5858  20230113   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 08:15:00,699:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673568899, self.tradeDate='20230113', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=18822.5, self.close=18827.2, self.high=18835.0, self.low=18811.2, self.vol=1705.593, self.amt=32105468.2183, ukdf['pct'].iloc[-1]=0.000282 , ukdf['amount'].iloc[-1]=32105468.2183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230112   200000    235959  1673539199  ...    719  1.297220  1.946828     1.0
720  20230113   000000    035959  1673553599  ...    720  1.612741  2.660284     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '86399.3856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18877.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=292
self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=18877.3, self.close=18838.0, self.high=19120.0, self.low=18758.5, self.vol=124572.563, self.amt=2353820342.8442 
127.0.0.1 - - [13/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-13 08:00:01,244:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=18877.3, self.close=18838.0, self.high=19120.0, self.low=18758.5, self.vol=124572.563, self.amt=2353820342.8442 
2023-01-13 08:00:01,318:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230112   120000    155959  ...   51547.124  9.355653e+08 -0.004825
718  20230112   160000    195959  ...   45869.521  8.326695e+08  0.003596
719  20230112   200000    235959  ...  322077.456  5.844744e+09 -0.006425
720  20230113   000000    035959  ...  328471.599  6.135608e+09  0.044232
721  20230113   040000    075959  ...  124572.563  2.353820e+09 -0.002077

[5 rows x 11 columns]
2023-01-13 08:00:03,706:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230112   120000    155959  1673510399  ...    717  1.335643  2.179508     1.0
718  20230112   160000    195959  1673524799  ...    718  1.209428  1.770281     1.0
719  20230112   200000    235959  1673539199  ...    719  1.297220  1.946828     1.0
720  20230113   000000    035959  1673553599  ...    720  1.612741  2.660284     1.0
721  20230113   040000    075959  1673567999  ...    721  1.431327  2.104170     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '84410.98879594752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18838.91551932', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


