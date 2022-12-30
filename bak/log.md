# 20221230 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9434
self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16630.0, self.close=16634.0, self.high=16635.9, self.low=16629.9, self.vol=375.752, self.amt=6249744.9938 
127.0.0.1 - - [30/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-30 08:10:01,488:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221230   074500    074959  ...         0.0        0.0       0
5854  20221230   075000    075459  ...         0.0        0.0       0
5855  20221230   075500    075959  ...         0.0        0.0       0
5856  20221230   080000    080459  ...         0.0        0.0       0
5857  20221230   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 08:10:01,490:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16630.0, self.close=16634.0, self.high=16635.9, self.low=16629.9, self.vol=375.752, self.amt=6249744.9938, ukdf['pct'].iloc[-1]=0.000247 , ukdf['amount'].iloc[-1]=6249744.9938, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-6294.4096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16633.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9435
self.closeSec=1672359299, self.tradeDate='20221230', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16634.0, self.close=16621.3, self.high=16635.0, self.low=16620.0, self.vol=433.948, self.amt=7215378.2122 
127.0.0.1 - - [30/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-30 08:15:00,571:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221230   075000    075459  ...         0.0        0.0       0
5855  20221230   075500    075959  ...         0.0        0.0       0
5856  20221230   080000    080459  ...         0.0        0.0       0
5857  20221230   080500    080959  ...         0.0        0.0       0
5858  20221230   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 08:15:00,572:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672359299, self.tradeDate='20221230', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16634.0, self.close=16621.3, self.high=16635.0, self.low=16620.0, self.vol=433.948, self.amt=7215378.2122, ukdf['pct'].iloc[-1]=-0.000763 , ukdf['amount'].iloc[-1]=7215378.2122, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-5561.82435473344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16621.72595644', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.436515925219517, self.count=10000 

self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16630.0, self.close=16634.0, self.high=16635.9, self.low=16629.9 
2022-12-30 08:10:01,417:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16630.0, self.close=16634.0, self.high=16635.9, self.low=16629.9   
2022-12-30 08:10:01,467:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221230   074500    074959  1672357799  ...  16632.0 -0.000361   1533    3
1534  20221230   075000    075459  1672358099  ...  16632.2  0.000180   1534    4
1535  20221230   075500    075959  1672358399  ...  16630.3 -0.000403   1535    5
1536  20221230   080000    080459  1672358699  ...  16624.9 -0.000024   1536    0
1537  20221230   080500    080959  1672358999  ...  16629.9  0.000247   1537    1

[5 rows x 11 columns]
2022-12-30 08:10:01,467:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [30/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.436515925219517, self.count=10001 

self.closeSec=1672359299, self.tradeDate='20221230', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16634.0, self.close=16621.3, self.high=16635.0, self.low=16620.0 
2022-12-30 08:15:00,516:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672359299, self.tradeDate='20221230', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16634.0, self.close=16621.3, self.high=16635.0, self.low=16620.0   
2022-12-30 08:15:00,556:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221230   075000    075459  1672358099  ...  16632.2  0.000180   1534    4
1535  20221230   075500    075959  1672358399  ...  16630.3 -0.000403   1535    5
1536  20221230   080000    080459  1672358699  ...  16624.9 -0.000024   1536    0
1537  20221230   080500    080959  1672358999  ...  16629.9  0.000247   1537    1
1538  20221230   081000    081459  1672359299  ...  16620.0 -0.000763   1538    2

[5 rows x 11 columns]
2022-12-30 08:15:00,557:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-30 08:00:18,844:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221230    052959  16592.8  ...  42.916667  0.477185  0.366546
5771  20221230    055959  16594.9  ...  42.916667  0.474410  0.368370
5772  20221230    062959  16590.9  ...  43.333333  0.488800  0.362252
5773  20221230    065959  16610.8  ...  43.333333  0.490961  0.358877
5774  20221230    072959  16614.1  ...  43.333333  0.501776  0.348526

[5 rows x 33 columns]
0.5157116451016636
acc is : 0.5157116451016636
2022-12-30 08:00:18,958:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.494499  0.505501       0  ...  0.991087   1.0    0.0  0.994396
537     1  0.495610  0.504390       1  ...  0.992306   1.0    0.0  0.995619
538     0  0.502813  0.497187       1  ...  0.992491   1.0    0.0  0.995804
539     0  0.501238  0.498762       1  ...  0.993423   1.0    0.0  0.996739
540     0  0.505126  0.494874       1  ...  0.993465   1.0    0.0  0.996781

[5 rows x 10 columns]
2022-12-30 08:00:18,986:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494762  0.505238       0  ...  0.991087   1.0    0.0  0.994849
46     1  0.495608  0.504392       1  ...  0.992306   1.0    0.0  0.995499
47     0  0.502553  0.497447       1  ...  0.992491   1.0    0.0  0.995655
48     0  0.501361  0.498639       1  ...  0.993423   1.0    0.0  0.996739
49     0  0.505126  0.494874       1  ...  0.993465   1.0    0.0  0.996781

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-2965.03854763776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16631.78032008', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221230   074000    074959  1672357799  16639.3    16634 -0.000313
2022-12-30 07:50:01,018:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4999 

self.closeSec=1672358399, self.tradeDate='20221230', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16634.1', self.close='16630.3'
127.0.0.1 - - [30/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-30 08:00:01,440:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672358399, self.tradeDate='20221230', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16634.1', self.close='16630.3'
2022-12-30 08:00:01,454:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221230   071000    071959  1672355999  16621.2  16627.1  0.000361
620  20221230   072000    072959  1672356599  16627.2  16629.6  0.000150
621  20221230   073000    073959  1672357199  16629.7  16639.2  0.000577
622  20221230   074000    074959  1672357799  16639.3    16634 -0.000313
623  20221230   075000    075959  1672358399  16634.1  16630.3 -0.000222
2022-12-30 08:00:01,455:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5000 

self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16630.3', self.close='16634'
2022-12-30 08:10:01,542:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16630.3', self.close='16634'
2022-12-30 08:10:01,549:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221230   072000    072959  1672356599  16627.2  16629.6  0.000150
621  20221230   073000    073959  1672357199  16629.7  16639.2  0.000577
622  20221230   074000    074959  1672357799  16639.3    16634 -0.000313
623  20221230   075000    075959  1672358399  16634.1  16630.3 -0.000222
624  20221230   080000    080959  1672358999  16630.3    16634  0.000222
2022-12-30 08:10:01,549:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221230   074000    074959  1672357799  16639.3    16634
2022-12-30 07:50:01,032:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5000 

self.closeSec=1672358399, self.tradeDate='20221230', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16634.1', self.close='16630.3'
127.0.0.1 - - [30/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-30 08:00:01,457:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672358399, self.tradeDate='20221230', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16634.1', self.close='16630.3'
2022-12-30 08:00:01,476:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221230   071000    071959  1672355999  16621.2  16627.1
17468  20221230   072000    072959  1672356599  16627.2  16629.6
17469  20221230   073000    073959  1672357199  16629.7  16639.2
17470  20221230   074000    074959  1672357799  16639.3    16634
17471  20221230   075000    075959  1672358399  16634.1  16630.3
2022-12-30 08:00:01,477:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5001 

self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16630.3', self.close='16634'
2022-12-30 08:10:01,509:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16630.3', self.close='16634'
2022-12-30 08:10:01,518:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221230   072000    072959  1672356599  16627.2  16629.6
17469  20221230   073000    073959  1672357199  16629.7  16639.2
17470  20221230   074000    074959  1672357799  16639.3    16634
17471  20221230   075000    075959  1672358399  16634.1  16630.3
17472  20221230   080000    080959  1672358999  16630.3    16634
2022-12-30 08:10:01,518:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221230   074000    074959  1672357799  16639.3    16634
2022-12-30 07:50:01,032:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5000 

self.closeSec=1672358399, self.tradeDate='20221230', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16634.1', self.close='16630.3'
2022-12-30 08:00:01,454:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672358399, self.tradeDate='20221230', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16634.1', self.close='16630.3'
2022-12-30 08:00:01,484:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221230   071000    071959  1672355999  16621.2  16627.1
12140  20221230   072000    072959  1672356599  16627.2  16629.6
12141  20221230   073000    073959  1672357199  16629.7  16639.2
12142  20221230   074000    074959  1672357799  16639.3    16634
12143  20221230   075000    075959  1672358399  16634.1  16630.3
2022-12-30 08:00:01,484:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5001 

self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16630.3', self.close='16634'
2022-12-30 08:10:01,519:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16630.3', self.close='16634'
127.0.0.1 - - [30/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-30 08:10:01,539:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221230   072000    072959  1672356599  16627.2  16629.6
12141  20221230   073000    073959  1672357199  16629.7  16639.2
12142  20221230   074000    074959  1672357799  16639.3    16634
12143  20221230   075000    075959  1672358399  16634.1  16630.3
12144  20221230   080000    080959  1672358999  16630.3    16634
2022-12-30 08:10:01,539:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5432
self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16630.0, self.close=16634.0, self.high=16635.9, self.low=16629.9, self.vol=375.752, self.amt=6249744.9938 
127.0.0.1 - - [30/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-30 08:10:01,489:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221230   074500    074959  ...         0.0        0.0       0
5854  20221230   075000    075459  ...         0.0        0.0       0
5855  20221230   075500    075959  ...         0.0        0.0       0
5856  20221230   080000    080459  ...         0.0        0.0       0
5857  20221230   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 08:10:01,490:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672358999, self.tradeDate='20221230', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16630.0, self.close=16634.0, self.high=16635.9, self.low=16629.9, self.vol=375.752, self.amt=6249744.9938, ukdf['pct'].iloc[-1]=0.000247 , ukdf['amount'].iloc[-1]=6249744.9938, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [30/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5433
self.closeSec=1672359299, self.tradeDate='20221230', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16634.0, self.close=16621.3, self.high=16635.0, self.low=16620.0, self.vol=433.948, self.amt=7215378.2122 
2022-12-30 08:15:00,600:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221230   075000    075459  ...         0.0        0.0       0
5855  20221230   075500    075959  ...         0.0        0.0       0
5856  20221230   080000    080459  ...         0.0        0.0       0
5857  20221230   080500    080959  ...         0.0        0.0       0
5858  20221230   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 08:15:00,602:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672359299, self.tradeDate='20221230', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16634.0, self.close=16621.3, self.high=16635.0, self.low=16620.0, self.vol=433.948, self.amt=7215378.2122, ukdf['pct'].iloc[-1]=-0.000763 , ukdf['amount'].iloc[-1]=7215378.2122, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

718  20221229   160000    195959  ...  40553.131  6.720861e+08  0.002465
719  20221229   200000    235959  ...  52351.625  8.702267e+08  0.000982
720  20221230   000000    035959  ...  26803.582  4.453796e+08 -0.000120
721  20221230   040000    075959  ...  32491.913  5.394451e+08  0.001337

[5 rows x 11 columns]
2022-12-30 08:00:02,706:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221229   120000    155959  1672300799  ...    717  0.516441  0.253051     NaN
718  20221229   160000    195959  1672315199  ...    718  0.557166  0.357870     NaN
719  20221229   200000    235959  1672329599  ...    719  0.610035  0.494206     NaN
720  20221230   000000    035959  1672343999  ...    720  0.624418  0.549845     NaN
721  20221230   040000    075959  1672358399  ...    721  0.637508  0.605011     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '4945.8054872226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16630.43333045', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '4945.8054872226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16630.43333045', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-30 08:00:08,768:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '899040.7321033', 'total': '899040.7321033', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2022-12-30 08:00:09,041:DEBUG:s_rsrs:main.py:253:openBuy:185271: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2022-12-30 08:00:09,041:INFO:s_rsrs:main.py:254:openBuy:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 53.898, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41441F1672358409040I0L65'}
2022-12-30 08:00:09,064:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:12300800, name:s_rsrs, symbol:BTCUSDT, tradeDate:20221230, closeTime:075959, close:16630.3, sign:1, total:899040.7321033, side:buy  
127.0.0.1 - - [30/Dec/2022 08:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Dec/2022 08:00:09] "POST / HTTP/1.1" 200 -
2022-12-30 08:00:09,065:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41440F1672358403619I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672358403719452, 'quantity': '53.372', 'price': '16630.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672358403139, 'updatetime': 1672358403719, 'tradetype': 'usdt', 'selfid': 41440, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672358403719, 'clientorderid': '41440F1672358403619I0L65', 'price': '16630.1', 'quantity': '53.372', 'commission': '887.5816972', 'commissionasset': 'USDT', 'tradetime': 1672358403719, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672358403719}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-30 08:00:09,065:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41440F1672358403619I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672358403719452, 'quantity': '53.372', 'price': '16630.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672358403139, 'updatetime': 1672358403719, 'tradetype': 'usdt', 'selfid': 41440, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672358403719, 'clientorderid': '41440F1672358403619I0L65', 'price': '16630.1', 'quantity': '53.372', 'commission': '887.5816972', 'commissionasset': 'USDT', 'tradetime': 1672358403719, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672358403719}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Dec/2022 08:00:09] "POST / HTTP/1.1" 200 -
2022-12-30 08:00:09,189:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41441F1672358409040I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672358409145135, 'quantity': '53.898', 'price': '16630.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672358408786, 'updatetime': 1672358409145, 'tradetype': 'usdt', 'selfid': 41441, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672358409145, 'clientorderid': '41441F1672358409040I0L65', 'price': '16630.1', 'quantity': '53.898', 'commission': '896.3291298', 'commissionasset': 'USDT', 'tradetime': 1672358409145, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672358409145}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-30 08:00:09,399:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41441F1672358409040I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672358409145135, 'quantity': '53.898', 'price': '16630.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672358408786, 'updatetime': 1672358409145, 'tradetype': 'usdt', 'selfid': 41441, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672358409145, 'clientorderid': '41441F1672358409040I0L65', 'price': '16630.1', 'quantity': '53.898', 'commission': '896.3291298', 'commissionasset': 'USDT', 'tradetime': 1672358409145, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672358409145}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Dec/2022 08:00:09] "POST / HTTP/1.1" 200 -


