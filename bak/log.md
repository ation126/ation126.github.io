# 20230119 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15194
self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=20693.0, self.close=20730.9, self.high=20734.3, self.low=20693.0, self.vol=1529.552, self.amt=31682215.8851 
127.0.0.1 - - [19/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 08:10:01,513:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230119   074500    074959  ...         0.0        0.0       0
5854  20230119   075000    075459  ...         0.0        0.0       0
5855  20230119   075500    075959  ...         0.0        0.0       0
5856  20230119   080000    080459  ...         0.0        0.0       0
5857  20230119   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 08:10:01,513:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=20693.0, self.close=20730.9, self.high=20734.3, self.low=20693.0, self.vol=1529.552, self.amt=31682215.8851, ukdf['pct'].iloc[-1]=0.001798 , ukdf['amount'].iloc[-1]=31682215.8851, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-252835.4816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20730.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15195
self.closeSec=1674087299, self.tradeDate='20230119', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20730.9, self.close=20734.4, self.high=20746.9, self.low=20722.0, self.vol=1263.298, self.amt=26193252.2882 
2023-01-19 08:15:00,982:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230119   075000    075459  ...         0.0        0.0       0
5855  20230119   075500    075959  ...         0.0        0.0       0
5856  20230119   080000    080459  ...         0.0        0.0       0
5857  20230119   080500    080959  ...         0.0        0.0       0
5858  20230119   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 08:15:00,982:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674087299, self.tradeDate='20230119', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20730.9, self.close=20734.4, self.high=20746.9, self.low=20722.0, self.vol=1263.298, self.amt=26193252.2882, ukdf['pct'].iloc[-1]=0.000169 , ukdf['amount'].iloc[-1]=26193252.2882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-253082.2032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20735', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=20693.0, self.close=20730.9, self.high=20734.3, self.low=20693.0 
2023-01-19 08:10:01,436:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=20693.0, self.close=20730.9, self.high=20734.3, self.low=20693.0   
127.0.0.1 - - [19/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 08:10:01,469:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230119   074500    074959  1674085799  ...  20683.4 -0.000237   1533    3
1534  20230119   075000    075459  1674086099  ...  20656.3 -0.000686   1534    4
1535  20230119   075500    075959  1674086399  ...  20648.0 -0.000421   1535    5
1536  20230119   080000    080459  1674086699  ...  20666.2  0.000662   1536    0
1537  20230119   080500    080959  1674086999  ...  20693.0  0.001798   1537    1

[5 rows x 11 columns]
2023-01-19 08:10:01,469:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=543, self.factor=0.5838651833257286, self.count=15761 

self.closeSec=1674087299, self.tradeDate='20230119', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20730.9, self.close=20734.4, self.high=20746.9, self.low=20722.0 
2023-01-19 08:15:00,840:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674087299, self.tradeDate='20230119', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20730.9, self.close=20734.4, self.high=20746.9, self.low=20722.0   
2023-01-19 08:15:00,939:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230119   075000    075459  1674086099  ...  20656.3 -0.000686   1534    4
1535  20230119   075500    075959  1674086399  ...  20648.0 -0.000421   1535    5
1536  20230119   080000    080459  1674086699  ...  20666.2  0.000662   1536    0
1537  20230119   080500    080959  1674086999  ...  20693.0  0.001798   1537    1
1538  20230119   081000    081459  1674087299  ...  20722.0  0.000169   1538    2

[5 rows x 11 columns]
2023-01-19 08:15:00,940:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-19 08:00:34,961:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230119    052959  20732.7  ...  51.250000  0.437086  0.593665
5771  20230119    055959  20757.5  ...  51.250000  0.441873  0.600261
5772  20230119    062959  20780.7  ...  50.833333  0.435443  0.608517
5773  20230119    065959  20740.8  ...  51.250000  0.449767  0.612543
5774  20230119    072959  20811.8  ...  51.250000  0.439243  0.619705

[5 rows x 33 columns]
0.5397412199630314
acc is : 0.5397412199630314
2023-01-19 08:00:35,120:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.476024  0.523976       1  ...  1.100488  -1.0    0.0  1.228238
537     1  0.476519  0.523481       0  ...  1.102633  -1.0    0.0  1.225845
538     1  0.465156  0.534844       1  ...  1.098859  -1.0    0.0  1.230041
539     1  0.499381  0.500619       0  ...  1.102327  -1.0    0.0  1.226158
540     1  0.478398  0.521602       0  ...  1.105840  -1.0    0.0  1.222251

[5 rows x 10 columns]
2023-01-19 08:00:35,163:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
31     1  0.476036  0.523964       1  ...  1.100488  -1.0    0.0  1.227158
32     1  0.476425  0.523575       0  ...  1.102633  -1.0    0.0  1.225903
33     1  0.465171  0.534829       1  ...  1.098859  -1.0    0.0  1.230274
34     1  0.499381  0.500619       0  ...  1.102327  -1.0    0.0  1.226158
35     1  0.478398  0.521602       0  ...  1.105840  -1.0    0.0  1.222251

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.395', 'enterprice': '20707.9', 'countrevence': '0', 'unrealprofit': '342.3105155478', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20697.94766636', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230119   074000    074959  1674085799    20713  20702.9 -0.000492
2023-01-19 07:50:00,580:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7879 

self.closeSec=1674086399, self.tradeDate='20230119', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='20700.2', self.close='20680'
127.0.0.1 - - [19/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-19 08:00:01,561:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674086399, self.tradeDate='20230119', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='20700.2', self.close='20680'
2023-01-19 08:00:01,631:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230119   071000    071959  1674083999  20776.8  20764.4 -0.000597
620  20230119   072000    072959  1674084599  20764.4  20746.1 -0.000881
621  20230119   073000    073959  1674085199    20746  20713.1 -0.001591
622  20230119   074000    074959  1674085799    20713  20702.9 -0.000492
623  20230119   075000    075959  1674086399  20700.2    20680 -0.001106
2023-01-19 08:00:01,631:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7880 

self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20680.1', self.close='20730.9'
2023-01-19 08:10:01,529:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20680.1', self.close='20730.9'
127.0.0.1 - - [19/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 08:10:01,537:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230119   072000    072959  1674084599  20764.4  20746.1 -0.000881
621  20230119   073000    073959  1674085199    20746  20713.1 -0.001591
622  20230119   074000    074959  1674085799    20713  20702.9 -0.000492
623  20230119   075000    075959  1674086399  20700.2    20680 -0.001106
624  20230119   080000    080959  1674086999  20680.1  20730.9  0.002461
2023-01-19 08:10:01,538:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230119   074000    074959  1674085799    20713  20702.9
2023-01-19 07:50:00,620:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7880 

self.closeSec=1674086399, self.tradeDate='20230119', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='20700.2', self.close='20680'
127.0.0.1 - - [19/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-19 08:00:01,540:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674086399, self.tradeDate='20230119', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='20700.2', self.close='20680'
2023-01-19 08:00:01,614:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230119   071000    071959  1674083999  20776.8  20764.4
17468  20230119   072000    072959  1674084599  20764.4  20746.1
17469  20230119   073000    073959  1674085199    20746  20713.1
17470  20230119   074000    074959  1674085799    20713  20702.9
17471  20230119   075000    075959  1674086399  20700.2    20680
2023-01-19 08:00:01,614:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7881 

self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20680.1', self.close='20730.9'
2023-01-19 08:10:01,553:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20680.1', self.close='20730.9'
127.0.0.1 - - [19/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 08:10:01,577:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230119   072000    072959  1674084599  20764.4  20746.1
17469  20230119   073000    073959  1674085199    20746  20713.1
17470  20230119   074000    074959  1674085799    20713  20702.9
17471  20230119   075000    075959  1674086399  20700.2    20680
17472  20230119   080000    080959  1674086999  20680.1  20730.9
2023-01-19 08:10:01,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230119   074000    074959  1674085799    20713  20702.9
2023-01-19 07:50:00,599:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7880 

self.closeSec=1674086399, self.tradeDate='20230119', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='20700.2', self.close='20680'
2023-01-19 08:00:01,538:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674086399, self.tradeDate='20230119', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='20700.2', self.close='20680'
127.0.0.1 - - [19/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-19 08:00:01,603:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230119   071000    071959  1674083999  20776.8  20764.4
12140  20230119   072000    072959  1674084599  20764.4  20746.1
12141  20230119   073000    073959  1674085199    20746  20713.1
12142  20230119   074000    074959  1674085799    20713  20702.9
12143  20230119   075000    075959  1674086399  20700.2    20680
2023-01-19 08:00:01,603:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7881 

self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20680.1', self.close='20730.9'
2023-01-19 08:10:01,546:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20680.1', self.close='20730.9'
2023-01-19 08:10:01,587:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230119   072000    072959  1674084599  20764.4  20746.1
12141  20230119   073000    073959  1674085199    20746  20713.1
12142  20230119   074000    074959  1674085799    20713  20702.9
12143  20230119   075000    075959  1674086399  20700.2    20680
12144  20230119   080000    080959  1674086999  20680.1  20730.9
2023-01-19 08:10:01,587:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11192
self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=20693.0, self.close=20730.9, self.high=20734.3, self.low=20693.0, self.vol=1529.552, self.amt=31682215.8851 
127.0.0.1 - - [19/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-19 08:10:01,486:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230119   074500    074959  ...         0.0        0.0       0
5854  20230119   075000    075459  ...         0.0        0.0       0
5855  20230119   075500    075959  ...         0.0        0.0       0
5856  20230119   080000    080459  ...         0.0        0.0       0
5857  20230119   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 08:10:01,486:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674086999, self.tradeDate='20230119', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=20693.0, self.close=20730.9, self.high=20734.3, self.low=20693.0, self.vol=1529.552, self.amt=31682215.8851, ukdf['pct'].iloc[-1]=0.001798 , ukdf['amount'].iloc[-1]=31682215.8851, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11193
self.closeSec=1674087299, self.tradeDate='20230119', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20730.9, self.close=20734.4, self.high=20746.9, self.low=20722.0, self.vol=1263.298, self.amt=26193252.2882 
2023-01-19 08:15:00,984:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230119   075000    075459  ...         0.0        0.0       0
5855  20230119   075500    075959  ...         0.0        0.0       0
5856  20230119   080000    080459  ...         0.0        0.0       0
5857  20230119   080500    080959  ...         0.0        0.0       0
5858  20230119   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-19 08:15:00,985:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674087299, self.tradeDate='20230119', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20730.9, self.close=20734.4, self.high=20746.9, self.low=20722.0, self.vol=1263.298, self.amt=26193252.2882, ukdf['pct'].iloc[-1]=0.000169 , ukdf['amount'].iloc[-1]=26193252.2882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230118   200000    235959  1674057599  ...    719  0.189080 -1.617061    -1.0
720  20230119   000000    035959  1674071999  ...    720  0.173649 -1.613879    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '13423.05115680676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20903.97615308', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [19/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=328
self.closeSec=1674086399, self.tradeDate='20230119', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=20905.0, self.close=20680.0, self.high=20937.8, self.low=20621.1, self.vol=93528.513, self.amt=1941499472.64343 
2023-01-19 08:00:01,444:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674086399, self.tradeDate='20230119', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=20905.0, self.close=20680.0, self.high=20937.8, self.low=20621.1, self.vol=93528.513, self.amt=1941499472.64343 
2023-01-19 08:00:01,505:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230118   120000    155959  ...   26297.724  5.595176e+08  0.002522
718  20230118   160000    195959  ...   45098.726  9.571280e+08 -0.004979
719  20230118   200000    235959  ...  269413.610  5.745100e+09 -0.007830
720  20230119   000000    035959  ...  320910.719  6.682469e+09 -0.006204
721  20230119   040000    075959  ...   93528.513  1.941499e+09 -0.010768

[5 rows x 11 columns]
2023-01-19 08:00:03,756:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230118   120000    155959  1674028799  ...    717  0.179287 -1.690226    -1.0
718  20230118   160000    195959  1674043199  ...    718  0.172129 -1.682806    -1.0
719  20230118   200000    235959  1674057599  ...    719  0.189080 -1.617061    -1.0
720  20230119   000000    035959  1674071999  ...    720  0.173649 -1.613879    -1.0
721  20230119   040000    075959  1674086399  ...    721  0.176794 -1.566888    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '24792.74487492445', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20681.27241935', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


