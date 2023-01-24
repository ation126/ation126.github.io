# 20230124 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [24/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16634
self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22920.2, self.close=22902.5, self.high=22920.2, self.low=22863.3, self.vol=1811.702, self.amt=41475703.7449 
2023-01-24 08:10:01,512:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230124   074500    074959  ...         0.0        0.0       0
5854  20230124   075000    075459  ...         0.0        0.0       0
5855  20230124   075500    075959  ...         0.0        0.0       0
5856  20230124   080000    080459  ...         0.0        0.0       0
5857  20230124   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 08:10:01,512:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22920.2, self.close=22902.5, self.high=22920.2, self.low=22863.3, self.vol=1811.702, self.amt=41475703.7449, ukdf['pct'].iloc[-1]=-0.000772 , ukdf['amount'].iloc[-1]=41475703.7449, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-383585.8944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22903.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16635
self.closeSec=1674519299, self.tradeDate='20230124', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22902.5, self.close=22943.9, self.high=22946.8, self.low=22897.3, self.vol=1061.593, self.amt=24345400.2244 
127.0.0.1 - - [24/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-24 08:15:00,893:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230124   075000    075459  ...         0.0        0.0       0
5855  20230124   075500    075959  ...         0.0        0.0       0
5856  20230124   080000    080459  ...         0.0        0.0       0
5857  20230124   080500    080959  ...         0.0        0.0       0
5858  20230124   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 08:15:00,894:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674519299, self.tradeDate='20230124', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22902.5, self.close=22943.9, self.high=22946.8, self.low=22897.3, self.vol=1061.593, self.amt=24345400.2244, ukdf['pct'].iloc[-1]=0.001808 , ukdf['amount'].iloc[-1]=24345400.2244, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-386032.23165982', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22944.35303875', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=157, self.factor=0.4022168500309187, self.count=17200 

self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22920.2, self.close=22902.5, self.high=22920.2, self.low=22863.3 
2023-01-24 08:10:01,442:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22920.2, self.close=22902.5, self.high=22920.2, self.low=22863.3   
2023-01-24 08:10:01,498:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230124   074500    074959  1674517799  ...  22925.3  0.000593   1533    3
1534  20230124   075000    075459  1674518099  ...  22939.7 -0.000179   1534    4
1535  20230124   075500    075959  1674518399  ...  22902.6 -0.001264   1535    5
1536  20230124   080000    080459  1674518699  ...  22893.1  0.000310   1536    0
1537  20230124   080500    080959  1674518999  ...  22863.3 -0.000772   1537    1

[5 rows x 11 columns]
2023-01-24 08:10:01,498:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [24/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=157, self.factor=0.4022168500309187, self.count=17201 

self.closeSec=1674519299, self.tradeDate='20230124', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22902.5, self.close=22943.9, self.high=22946.8, self.low=22897.3 
2023-01-24 08:15:00,863:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674519299, self.tradeDate='20230124', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22902.5, self.close=22943.9, self.high=22946.8, self.low=22897.3   
2023-01-24 08:15:00,892:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230124   075000    075459  1674518099  ...  22939.7 -0.000179   1534    4
1535  20230124   075500    075959  1674518399  ...  22902.6 -0.001264   1535    5
1536  20230124   080000    080459  1674518699  ...  22893.1  0.000310   1536    0
1537  20230124   080500    080959  1674518999  ...  22863.3 -0.000772   1537    1
1538  20230124   081000    081459  1674519299  ...  22897.3  0.001808   1538    2

[5 rows x 11 columns]
2023-01-24 08:15:00,892:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-24 08:00:22,979:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230124    052959  23021.4  ...  54.583333  0.540453  0.357602
5771  20230124    055959  22980.6  ...  54.583333  0.541978  0.353220
5772  20230124    062959  22992.7  ...  54.583333  0.539507  0.350458
5773  20230124    065959  22979.6  ...  54.166667  0.530052  0.352969
5774  20230124    072959  22924.1  ...  54.166667  0.529801  0.355446

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2023-01-24 08:00:23,160:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.514150  0.485850       1  ...  1.068676   1.0    0.0  1.260115
537     0  0.532059  0.467941       0  ...  1.068035   1.0    0.0  1.259359
538     0  0.532110  0.467890       0  ...  1.065576   1.0    0.0  1.256459
539     0  0.513557  0.486443       0  ...  1.065511   1.0    0.0  1.256383
540     0  0.507438  0.492562       0  ...  1.065065   1.0    0.0  1.255856

[5 rows x 10 columns]
2023-01-24 08:00:23,198:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514103  0.485897       1  ...  1.103697   1.0    0.0  1.271777
46     0  0.532089  0.467911       0  ...  1.103035   1.0    0.0  1.267690
47     0  0.532026  0.467974       0  ...  1.100495   1.0    0.0  1.264548
48     0  0.513557  0.486443       0  ...  1.065511   1.0    0.0  1.256383
49     0  0.507438  0.492562       0  ...  1.065065   1.0    0.0  1.255856

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.288', 'enterprice': '22918.2', 'countrevence': '0', 'unrealprofit': '-306.736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22908.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230124   074000    074959  1674517799    22939  22946.2  0.000314
2023-01-24 07:50:00,585:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8599 

self.closeSec=1674518399, self.tradeDate='20230124', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22946.3', self.close='22913.1'
2023-01-24 08:00:01,581:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674518399, self.tradeDate='20230124', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22946.3', self.close='22913.1'
2023-01-24 08:00:01,645:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230124   071000    071959  1674515999  22920.8    22890 -0.001348
620  20230124   072000    072959  1674516599  22891.7  22922.7  0.001429
621  20230124   073000    073959  1674517199  22922.7    22939  0.000711
622  20230124   074000    074959  1674517799    22939  22946.2  0.000314
623  20230124   075000    075959  1674518399  22946.3  22913.1 -0.001443
2023-01-24 08:00:01,647:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8600 

self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22913.3', self.close='22902.5'
2023-01-24 08:10:01,535:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22913.3', self.close='22902.5'
2023-01-24 08:10:01,564:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230124   072000    072959  1674516599  22891.7  22922.7  0.001429
621  20230124   073000    073959  1674517199  22922.7    22939  0.000711
622  20230124   074000    074959  1674517799    22939  22946.2  0.000314
623  20230124   075000    075959  1674518399  22946.3  22913.1 -0.001443
624  20230124   080000    080959  1674518999  22913.3  22902.5 -0.000463
2023-01-24 08:10:01,564:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230124   074000    074959  1674517799    22939  22946.2
2023-01-24 07:50:00,596:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8600 

self.closeSec=1674518399, self.tradeDate='20230124', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22946.3', self.close='22913.1'
127.0.0.1 - - [24/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-24 08:00:01,579:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674518399, self.tradeDate='20230124', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22946.3', self.close='22913.1'
2023-01-24 08:00:01,598:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230124   071000    071959  1674515999  22920.8    22890
17468  20230124   072000    072959  1674516599  22891.7  22922.7
17469  20230124   073000    073959  1674517199  22922.7    22939
17470  20230124   074000    074959  1674517799    22939  22946.2
17471  20230124   075000    075959  1674518399  22946.3  22913.1
2023-01-24 08:00:01,598:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8601 

self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22913.3', self.close='22902.5'
2023-01-24 08:10:01,572:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22913.3', self.close='22902.5'
2023-01-24 08:10:01,577:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230124   072000    072959  1674516599  22891.7  22922.7
17469  20230124   073000    073959  1674517199  22922.7    22939
17470  20230124   074000    074959  1674517799    22939  22946.2
17471  20230124   075000    075959  1674518399  22946.3  22913.1
17472  20230124   080000    080959  1674518999  22913.3  22902.5
2023-01-24 08:10:01,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230124   074000    074959  1674517799    22939  22946.2
2023-01-24 07:50:00,591:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [24/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8600 

self.closeSec=1674518399, self.tradeDate='20230124', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22946.3', self.close='22913.1'
2023-01-24 08:00:01,595:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674518399, self.tradeDate='20230124', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22946.3', self.close='22913.1'
2023-01-24 08:00:01,652:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230124   071000    071959  1674515999  22920.8    22890
12140  20230124   072000    072959  1674516599  22891.7  22922.7
12141  20230124   073000    073959  1674517199  22922.7    22939
12142  20230124   074000    074959  1674517799    22939  22946.2
12143  20230124   075000    075959  1674518399  22946.3  22913.1
2023-01-24 08:00:01,652:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [24/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8601 

self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22913.3', self.close='22902.5'
2023-01-24 08:10:01,548:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22913.3', self.close='22902.5'
2023-01-24 08:10:01,566:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230124   072000    072959  1674516599  22891.7  22922.7
12141  20230124   073000    073959  1674517199  22922.7    22939
12142  20230124   074000    074959  1674517799    22939  22946.2
12143  20230124   075000    075959  1674518399  22946.3  22913.1
12144  20230124   080000    080959  1674518999  22913.3  22902.5
2023-01-24 08:10:01,567:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [24/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12632
self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22920.2, self.close=22902.5, self.high=22920.2, self.low=22863.3, self.vol=1811.702, self.amt=41475703.7449 
2023-01-24 08:10:01,515:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230124   074500    074959  ...         0.0        0.0       0
5854  20230124   075000    075459  ...         0.0        0.0       0
5855  20230124   075500    075959  ...         0.0        0.0       0
5856  20230124   080000    080459  ...         0.0        0.0       0
5857  20230124   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 08:10:01,515:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674518999, self.tradeDate='20230124', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22920.2, self.close=22902.5, self.high=22920.2, self.low=22863.3, self.vol=1811.702, self.amt=41475703.7449, ukdf['pct'].iloc[-1]=-0.000772 , ukdf['amount'].iloc[-1]=41475703.7449, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12633
self.closeSec=1674519299, self.tradeDate='20230124', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22902.5, self.close=22943.9, self.high=22946.8, self.low=22897.3, self.vol=1061.593, self.amt=24345400.2244 
2023-01-24 08:15:00,891:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230124   075000    075459  ...         0.0        0.0       0
5855  20230124   075500    075959  ...         0.0        0.0       0
5856  20230124   080000    080459  ...         0.0        0.0       0
5857  20230124   080500    080959  ...         0.0        0.0       0
5858  20230124   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 08:15:00,891:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674519299, self.tradeDate='20230124', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22902.5, self.close=22943.9, self.high=22946.8, self.low=22897.3, self.vol=1061.593, self.amt=24345400.2244, ukdf['pct'].iloc[-1]=0.001808 , ukdf['amount'].iloc[-1]=24345400.2244, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230123   200000    235959  1674489599  ...    719  0.979369  0.342718     NaN
720  20230124   000000    035959  1674503999  ...    720  0.971922  0.308584     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-20711.34868328736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22788.70133536', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [24/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=972283.0195242, self.flagDict['side']='buy', self.tradeCount=14, self.count=358
self.closeSec=1674518399, self.tradeDate='20230124', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22789.6, self.close=22913.1, self.high=23043.9, self.low=22756.1, self.vol=53110.17, self.amt=1217506713.0419 
2023-01-24 08:00:01,449:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674518399, self.tradeDate='20230124', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22789.6, self.close=22913.1, self.high=23043.9, self.low=22756.1, self.vol=53110.17, self.amt=1217506713.0419 
2023-01-24 08:00:01,496:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230123   120000    155959  ...   36713.329  8.339291e+08  0.001536
718  20230123   160000    195959  ...   68823.859  1.571893e+09  0.009430
719  20230123   200000    235959  ...  183939.268  4.198658e+09 -0.002375
720  20230124   000000    035959  ...  135623.970  3.109008e+09 -0.002682
721  20230124   040000    075959  ...   53110.170  1.217507e+09  0.005371

[5 rows x 11 columns]
2023-01-24 08:00:03,090:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230123   120000    155959  1674460799  ...    717  1.032809  0.501858     NaN
718  20230123   160000    195959  1674475199  ...    718  1.000022  0.408161     NaN
719  20230123   200000    235959  1674489599  ...    719  0.979369  0.342718     NaN
720  20230124   000000    035959  1674503999  ...    720  0.971922  0.308584     NaN
721  20230124   040000    075959  1674518399  ...    721  0.950928  0.242794     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-15503.2491', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22913.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


