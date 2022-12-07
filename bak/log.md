# 20221207 12:38:30

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2862
self.closeSec=1670387399, self.tradeDate='20221207', self.openTime='122500', self.closeTime='122959', self.symbol='BTCUSDT', self.open=17019.6, self.close=17023.3, self.high=17023.7, self.low=17017.8, self.vol=404.638, self.amt=6887352.626 
127.0.0.1 - - [07/Dec/2022 12:30:00] "POST / HTTP/1.1" 200 -
2022-12-07 12:30:00,569:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5905  20221207   120500    120959  ...    0.164199   0.296071       0
5906  20221207   121000    121459  ...    0.163994   0.295930       0
5907  20221207   121500    121959  ...    0.163792   0.295795       0
5908  20221207   122000    122459  ...    0.163590   0.295657       0
5909  20221207   122500    122959  ...    0.163388   0.295520       0

[5 rows x 18 columns]
2022-12-07 12:30:00,569:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670387399, self.tradeDate='20221207', self.openTime='122500', self.closeTime='122959',self.symbol='BTCUSDT',self.open=17019.6, self.close=17023.3, self.high=17023.7, self.low=17017.8, self.vol=404.638, self.amt=6887352.626, ukdf['pct'].iloc[-1]=0.000223 , ukdf['amount'].iloc[-1]=6887352.626, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5909, value=0.0, value_mean=0.1633878927522674, signal=0, value_std=0.29552037308824175 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-29720.9264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17023.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2863
self.closeSec=1670387699, self.tradeDate='20221207', self.openTime='123000', self.closeTime='123459', self.symbol='BTCUSDT', self.open=17023.2, self.close=17022.3, self.high=17024.8, self.low=17018.5, self.vol=489.715, self.amt=8335851.6804 
127.0.0.1 - - [07/Dec/2022 12:35:00] "POST / HTTP/1.1" 200 -
2022-12-07 12:35:00,451:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5906  20221207   121000    121459  ...    0.163994   0.295930       0
5907  20221207   121500    121959  ...    0.163792   0.295795       0
5908  20221207   122000    122459  ...    0.163590   0.295657       0
5909  20221207   122500    122959  ...    0.163388   0.295520       0
5910  20221207   123000    123459  ...    0.163187   0.295386       0

[5 rows x 18 columns]
2022-12-07 12:35:00,451:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670387699, self.tradeDate='20221207', self.openTime='123000', self.closeTime='123459',self.symbol='BTCUSDT',self.open=17023.2, self.close=17022.3, self.high=17024.8, self.low=17018.5, self.vol=489.715, self.amt=8335851.6804, ukdf['pct'].iloc[-1]=-5.9e-05 , ukdf['amount'].iloc[-1]=8335851.6804, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5910, value=0.0, value_mean=0.16318710237497272, signal=0, value_std=0.2953857200923723 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-29672.7856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17022.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1588  20221207   122000    122459  1670387099  ...  17013.2  0.000235   1588    4
1589  20221207   122500    122959  1670387399  ...  17017.8  0.000223   1589    5

[5 rows x 11 columns]
2022-12-07 12:30:00,566:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2022-12-07 12:30:00,599:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
221  20221207   102500    102959  1670380199  ... -0.000586   1565    5  0.564435
222  20221207   105500    105959  1670381999  ...  0.000194   1571    5  0.557436
223  20221207   112500    112959  1670383799  ... -0.000347   1577    5  0.554917
224  20221207   115500    115959  1670385599  ... -0.000182   1583    5  0.552628
225  20221207   122500    122959  1670387399  ...  0.000223   1589    5  0.549496

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=9, self.factor=0.5494961689871687, self.count=3429 

self.closeSec=1670387699, self.tradeDate='20221207', self.openTime='123000', self.closeTime='123459', self.symbol='BTCUSDT', self.open=17023.2, self.close=17022.3, self.high=17024.8, self.low=17018.5 
2022-12-07 12:35:00,431:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670387699, self.tradeDate='20221207', self.openTime='123000', self.closeTime='123459',self.symbol='BTCUSDT',self.open=17023.2, self.close=17022.3, self.high=17024.8, self.low=17018.5   
127.0.0.1 - - [07/Dec/2022 12:35:00] "POST / HTTP/1.1" 200 -
2022-12-07 12:35:00,446:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1586  20221207   121000    121459  1670386499  ...  17012.6  0.000182   1586    2
1587  20221207   121500    121959  1670386799  ...  17014.4 -0.000018   1587    3
1588  20221207   122000    122459  1670387099  ...  17013.2  0.000235   1588    4
1589  20221207   122500    122959  1670387399  ...  17017.8  0.000223   1589    5
1590  20221207   123000    123459  1670387699  ...  17018.5 -0.000059   1590    0

[5 rows x 11 columns]
2022-12-07 12:35:00,446:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-07 12:30:15,426:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5779  20221207    095959  17027.9  ...  51.250000  0.506089  0.504502
5780  20221207    102959  17035.1  ...  51.666667  0.508730  0.496770
5781  20221207    105959  17040.7  ...  51.666667  0.511686  0.487787
5782  20221207    112959  17046.7  ...  51.666667  0.496738  0.488065
5783  20221207    115959  17016.8  ...  51.666667  0.497039  0.488151

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2022-12-07 12:30:15,481:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.484740  0.515260       1  ...  0.935914  -1.0    0.0  1.033164
537     1  0.482802  0.517198       1  ...  0.935579  -1.0    0.0  1.033534
538     1  0.485494  0.514506       0  ...  0.937220  -1.0    0.0  1.031721
539     1  0.475452  0.524548       1  ...  0.937187  -1.0    0.0  1.031758
540     1  0.484638  0.515362       1  ...  0.936867  -1.0    0.0  1.032109

[5 rows x 10 columns]
2022-12-07 12:30:15,492:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484674  0.515326       1  ...  0.935914  -1.0    0.0  1.031763
46     1  0.482579  0.517421       1  ...  0.935579  -1.0    0.0  1.029763
47     1  0.485705  0.514295       0  ...  0.937220  -1.0    0.0  1.030141
48     1  0.476141  0.523859       1  ...  0.937187  -1.0    0.0  1.032183
49     1  0.484638  0.515362       1  ...  0.936867  -1.0    0.0  1.032109

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '-2300.172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17023.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

504  20221207   120000    120959  1670386199  17017.4  17012.7 -0.000306
2022-12-07 12:10:01,581:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1713 

self.closeSec=1670386799, self.tradeDate='20221207', self.openTime='121000', self.closeTime='121959', self.symbol='BTCUSDT', self.open='17012.7', self.close='17015.5'
2022-12-07 12:20:00,523:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670386799, self.tradeDate='20221207', self.openTime='121000', self.closeTime='121959',self.symbol='BTCUSDT',self.open='17012.7', self.close='17015.5'
127.0.0.1 - - [07/Dec/2022 12:20:00] "POST / HTTP/1.1" 200 -
2022-12-07 12:20:00,537:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
501  20221207   113000    113959  1670384399  17016.8  17022.6  0.000341
502  20221207   114000    114959  1670384999  17022.5  17024.4  0.000106
503  20221207   115000    115959  1670385599  17024.4  17017.9 -0.000382
504  20221207   120000    120959  1670386199  17017.4  17012.7 -0.000306
505  20221207   121000    121959  1670386799  17012.7  17015.5  0.000165
2022-12-07 12:20:00,537:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Dec/2022 12:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1714 

self.closeSec=1670387399, self.tradeDate='20221207', self.openTime='122000', self.closeTime='122959', self.symbol='BTCUSDT', self.open='17015.5', self.close='17023.2'
2022-12-07 12:30:00,768:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670387399, self.tradeDate='20221207', self.openTime='122000', self.closeTime='122959',self.symbol='BTCUSDT',self.open='17015.5', self.close='17023.2'
2022-12-07 12:30:00,780:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
502  20221207   114000    114959  1670384999  17022.5  17024.4  0.000106
503  20221207   115000    115959  1670385599  17024.4  17017.9 -0.000382
504  20221207   120000    120959  1670386199  17017.4  17012.7 -0.000306
505  20221207   121000    121959  1670386799  17012.7  17015.5  0.000165
506  20221207   122000    122959  1670387399  17015.5  17023.2  0.000453
2022-12-07 12:30:00,780:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17496  20221207   120000    120959  1670386199  17017.4  17012.7
2022-12-07 12:10:01,567:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Dec/2022 12:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1714 

self.closeSec=1670386799, self.tradeDate='20221207', self.openTime='121000', self.closeTime='121959', self.symbol='BTCUSDT', self.open='17012.7', self.close='17015.5'
2022-12-07 12:20:00,541:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670386799, self.tradeDate='20221207', self.openTime='121000', self.closeTime='121959',self.symbol='BTCUSDT',self.open='17012.7', self.close='17015.5'
2022-12-07 12:20:00,555:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17493  20221207   113000    113959  1670384399  17016.8  17022.6
17494  20221207   114000    114959  1670384999  17022.5  17024.4
17495  20221207   115000    115959  1670385599  17024.4  17017.9
17496  20221207   120000    120959  1670386199  17017.4  17012.7
17497  20221207   121000    121959  1670386799  17012.7  17015.5
2022-12-07 12:20:00,556:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Dec/2022 12:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1715 

self.closeSec=1670387399, self.tradeDate='20221207', self.openTime='122000', self.closeTime='122959', self.symbol='BTCUSDT', self.open='17015.5', self.close='17023.2'
2022-12-07 12:30:00,762:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670387399, self.tradeDate='20221207', self.openTime='122000', self.closeTime='122959',self.symbol='BTCUSDT',self.open='17015.5', self.close='17023.2'
2022-12-07 12:30:00,769:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17494  20221207   114000    114959  1670384999  17022.5  17024.4
17495  20221207   115000    115959  1670385599  17024.4  17017.9
17496  20221207   120000    120959  1670386199  17017.4  17012.7
17497  20221207   121000    121959  1670386799  17012.7  17015.5
17498  20221207   122000    122959  1670387399  17015.5  17023.2
2022-12-07 12:30:00,769:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12168  20221207   120000    120959  1670386199  17017.4  17012.7
2022-12-07 12:10:01,584:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Dec/2022 12:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1714 

self.closeSec=1670386799, self.tradeDate='20221207', self.openTime='121000', self.closeTime='121959', self.symbol='BTCUSDT', self.open='17012.7', self.close='17015.5'
2022-12-07 12:20:00,539:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670386799, self.tradeDate='20221207', self.openTime='121000', self.closeTime='121959',self.symbol='BTCUSDT',self.open='17012.7', self.close='17015.5'
2022-12-07 12:20:00,551:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12165  20221207   113000    113959  1670384399  17016.8  17022.6
12166  20221207   114000    114959  1670384999  17022.5  17024.4
12167  20221207   115000    115959  1670385599  17024.4  17017.9
12168  20221207   120000    120959  1670386199  17017.4  17012.7
12169  20221207   121000    121959  1670386799  17012.7  17015.5
2022-12-07 12:20:00,551:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Dec/2022 12:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1715 

self.closeSec=1670387399, self.tradeDate='20221207', self.openTime='122000', self.closeTime='122959', self.symbol='BTCUSDT', self.open='17015.5', self.close='17023.2'
2022-12-07 12:30:00,744:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670387399, self.tradeDate='20221207', self.openTime='122000', self.closeTime='122959',self.symbol='BTCUSDT',self.open='17015.5', self.close='17023.2'
2022-12-07 12:30:00,749:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12166  20221207   114000    114959  1670384999  17022.5  17024.4
12167  20221207   115000    115959  1670385599  17024.4  17017.9
12168  20221207   120000    120959  1670386199  17017.4  17012.7
12169  20221207   121000    121959  1670386799  17012.7  17015.5
12170  20221207   122000    122959  1670387399  17015.5  17023.2
2022-12-07 12:30:00,750:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

720  20221207   000000    035959  1670356799  ...    720  1.120770  3.120988     1.0
721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-13012.51157857668', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17079.52682306', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [07/Dec/2022 12:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=71
self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='080000', self.closeTime='115959', self.symbol='BTCUSDT', self.open=17078.7, self.close=17017.4, self.high=17130.0, self.low=17011.0, self.vol=42347.692, self.amt=722280772.2839 
2022-12-07 12:00:00,936:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670385599, self.tradeDate='20221207', self.openTime='080000', self.closeTime='115959',self.symbol='BTCUSDT',self.open=17078.7, self.close=17017.4, self.high=17130.0, self.low=17011.0, self.vol=42347.692, self.amt=722280772.2839 
2022-12-07 12:00:00,950:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
718  20221206   160000    195959  ...  57639.285  9.783913e+08 -0.001118
719  20221206   200000    235959  ...  69024.422  1.172189e+09  0.000018
720  20221207   000000    035959  ...  56413.953  9.566549e+08 -0.000636
721  20221207   040000    075959  ...  51125.606  8.698549e+08  0.006714
722  20221207   080000    115959  ...  42347.692  7.222808e+08 -0.003548

[5 rows x 11 columns]
2022-12-07 12:00:01,641:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
718  20221206   160000    195959  1670327999  ...    718  0.713850  1.417234     1.0
719  20221206   200000    235959  1670342399  ...    719  0.716348  1.398787     1.0
720  20221207   000000    035959  1670356799  ...    720  1.120770  3.120988     1.0
721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0
722  20221207   080000    115959  1670385599  ...    722  1.084938  2.647182     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-16610.74134876276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17018.14662842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


