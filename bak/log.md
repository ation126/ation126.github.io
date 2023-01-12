# 20230112 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [12/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13178
self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17922.0, self.close=17969.6, self.high=17978.8, self.low=17902.8, self.vol=5164.223, self.amt=92694282.0902 
2023-01-12 08:10:01,502:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230112   074500    074959  ...         0.0        0.0       0
5854  20230112   075000    075459  ...         0.0        0.0       0
5855  20230112   075500    075959  ...         0.0        0.0       0
5856  20230112   080000    080459  ...         0.0        0.0       0
5857  20230112   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 08:10:01,502:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17922.0, self.close=17969.6, self.high=17978.8, self.low=17902.8, self.vol=5164.223, self.amt=92694282.0902, ukdf['pct'].iloc[-1]=0.002813 , ukdf['amount'].iloc[-1]=92694282.0902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-86732.52081152416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17970.61415866', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13179
self.closeSec=1673482499, self.tradeDate='20230112', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17968.7, self.close=17942.3, self.high=17977.3, self.low=17921.4, self.vol=3037.032, self.amt=54516758.9914 
127.0.0.1 - - [12/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-12 08:15:00,638:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230112   075000    075459  ...         0.0        0.0       0
5855  20230112   075500    075959  ...         0.0        0.0       0
5856  20230112   080000    080459  ...         0.0        0.0       0
5857  20230112   080500    080959  ...         0.0        0.0       0
5858  20230112   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 08:15:00,638:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673482499, self.tradeDate='20230112', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17968.7, self.close=17942.3, self.high=17977.3, self.low=17921.4, self.vol=3037.032, self.amt=54516758.9914, ukdf['pct'].iloc[-1]=-0.001519 , ukdf['amount'].iloc[-1]=54516758.9914, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-85034.7056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17942.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17922.0, self.close=17969.6, self.high=17978.8, self.low=17902.8 
2023-01-12 08:10:01,425:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17922.0, self.close=17969.6, self.high=17978.8, self.low=17902.8   
127.0.0.1 - - [12/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-12 08:10:01,438:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230112   074500    074959  1673480999  ...  17867.7  0.000643   1533    3
1534  20230112   075000    075459  1673481299  ...  17903.8  0.001357   1534    4
1535  20230112   075500    075959  1673481599  ...  17922.5  0.000145   1535    5
1536  20230112   080000    080459  1673481899  ...  17902.4 -0.000914   1536    0
1537  20230112   080500    080959  1673482199  ...  17902.8  0.002813   1537    1

[5 rows x 11 columns]
2023-01-12 08:10:01,438:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=207, self.factor=0.31703635535918473, self.count=13745 

self.closeSec=1673482499, self.tradeDate='20230112', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17968.7, self.close=17942.3, self.high=17977.3, self.low=17921.4 
2023-01-12 08:15:00,540:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673482499, self.tradeDate='20230112', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17968.7, self.close=17942.3, self.high=17977.3, self.low=17921.4   
2023-01-12 08:15:00,582:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230112   075000    075459  1673481299  ...  17903.8  0.001357   1534    4
1535  20230112   075500    075959  1673481599  ...  17922.5  0.000145   1535    5
1536  20230112   080000    080459  1673481899  ...  17902.4 -0.000914   1536    0
1537  20230112   080500    080959  1673482199  ...  17902.8  0.002813   1537    1
1538  20230112   081000    081459  1673482499  ...  17921.4 -0.001519   1538    2

[5 rows x 11 columns]
2023-01-12 08:15:00,582:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-12 08:00:17,737:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230112    052959  17542.4  ...  54.166667  0.607555  0.369670
5771  20230112    055959  17540.1  ...  54.166667  0.610496  0.351802
5772  20230112    062959  17547.5  ...  53.750000  0.606482  0.339672
5773  20230112    065959  17540.9  ...  53.750000  0.609643  0.326699
5774  20230112    072959  17548.0  ...  53.750000  0.650594  0.314436

[5 rows x 33 columns]
0.5452865064695009
acc is : 0.5452865064695009
2023-01-12 08:00:17,841:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     0  0.509776  0.490224       1  ...  NaN   NaN -0.0016  1.058516
537     0  0.509502  0.490498       0  ...  NaN   NaN -0.0016  1.058166
538     0  0.502270  0.497730       1  ...  NaN   NaN -0.0016  1.058588
539     0  0.507193  0.492807       1  ...  NaN   NaN -0.0016  1.064626
540     0  0.538670  0.461330       1  ...  NaN   NaN -0.0016  1.081976

[5 rows x 10 columns]
2023-01-12 08:00:17,859:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.509117  0.490883       1  ...  NaN   NaN -0.0016  1.057928
46     0  0.508796  0.491204       0  ...  NaN   NaN -0.0016  1.056744
47     0  0.501815  0.498185       1  ...  NaN   NaN -0.0016  1.057363
48     0  0.506936  0.493064       1  ...  NaN   NaN -0.0016  1.064626
49     0  0.538670  0.461330       1  ...  NaN   NaN -0.0016  1.081976

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '53049.4272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17948.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230112   074000    074959  1673480999    17892  17908.7  0.000950
2023-01-12 07:50:00,569:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6871 

self.closeSec=1673481599, self.tradeDate='20230112', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17913', self.close='17935.7'
2023-01-12 08:00:01,140:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673481599, self.tradeDate='20230112', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17913', self.close='17935.7'
2023-01-12 08:00:01,153:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230112   071000    071959  1673479199  17562.2    17558 -0.000233
620  20230112   072000    072959  1673479799  17557.9  17642.5  0.004813
621  20230112   073000    073959  1673480399  17642.5  17891.7  0.014125
622  20230112   074000    074959  1673480999    17892  17908.7  0.000950
623  20230112   075000    075959  1673481599    17913  17935.7  0.001508
2023-01-12 08:00:01,153:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6872 

self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17935.6', self.close='17969.6'
2023-01-12 08:10:01,554:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17935.6', self.close='17969.6'
2023-01-12 08:10:01,563:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230112   072000    072959  1673479799  17557.9  17642.5  0.004813
621  20230112   073000    073959  1673480399  17642.5  17891.7  0.014125
622  20230112   074000    074959  1673480999    17892  17908.7  0.000950
623  20230112   075000    075959  1673481599    17913  17935.7  0.001508
624  20230112   080000    080959  1673482199  17935.6  17969.6  0.001890
2023-01-12 08:10:01,564:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230112   074000    074959  1673480999    17892  17908.7
2023-01-12 07:50:00,618:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6872 

self.closeSec=1673481599, self.tradeDate='20230112', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17913', self.close='17935.7'
2023-01-12 08:00:01,166:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673481599, self.tradeDate='20230112', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17913', self.close='17935.7'
2023-01-12 08:00:01,187:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230112   071000    071959  1673479199  17562.2    17558
17468  20230112   072000    072959  1673479799  17557.9  17642.5
17469  20230112   073000    073959  1673480399  17642.5  17891.7
17470  20230112   074000    074959  1673480999    17892  17908.7
17471  20230112   075000    075959  1673481599    17913  17935.7
2023-01-12 08:00:01,188:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6873 

self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17935.6', self.close='17969.6'
2023-01-12 08:10:01,549:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17935.6', self.close='17969.6'
2023-01-12 08:10:01,562:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230112   072000    072959  1673479799  17557.9  17642.5
17469  20230112   073000    073959  1673480399  17642.5  17891.7
17470  20230112   074000    074959  1673480999    17892  17908.7
17471  20230112   075000    075959  1673481599    17913  17935.7
17472  20230112   080000    080959  1673482199  17935.6  17969.6
2023-01-12 08:10:01,562:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230112   074000    074959  1673480999    17892  17908.7
2023-01-12 07:50:00,590:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6872 

self.closeSec=1673481599, self.tradeDate='20230112', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17913', self.close='17935.7'
127.0.0.1 - - [12/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-12 08:00:01,141:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673481599, self.tradeDate='20230112', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17913', self.close='17935.7'
2023-01-12 08:00:01,155:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230112   071000    071959  1673479199  17562.2    17558
12140  20230112   072000    072959  1673479799  17557.9  17642.5
12141  20230112   073000    073959  1673480399  17642.5  17891.7
12142  20230112   074000    074959  1673480999    17892  17908.7
12143  20230112   075000    075959  1673481599    17913  17935.7
2023-01-12 08:00:01,155:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6873 

self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17935.6', self.close='17969.6'
2023-01-12 08:10:01,521:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17935.6', self.close='17969.6'
127.0.0.1 - - [12/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-12 08:10:01,534:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230112   072000    072959  1673479799  17557.9  17642.5
12141  20230112   073000    073959  1673480399  17642.5  17891.7
12142  20230112   074000    074959  1673480999    17892  17908.7
12143  20230112   075000    075959  1673481599    17913  17935.7
12144  20230112   080000    080959  1673482199  17935.6  17969.6
2023-01-12 08:10:01,534:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9176
self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17922.0, self.close=17969.6, self.high=17978.8, self.low=17902.8, self.vol=5164.223, self.amt=92694282.0902 
127.0.0.1 - - [12/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-12 08:10:01,500:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230112   074500    074959  ...         0.0        0.0       0
5854  20230112   075000    075459  ...         0.0        0.0       0
5855  20230112   075500    075959  ...         0.0        0.0       0
5856  20230112   080000    080459  ...         0.0        0.0       0
5857  20230112   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 08:10:01,503:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673482199, self.tradeDate='20230112', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17922.0, self.close=17969.6, self.high=17978.8, self.low=17902.8, self.vol=5164.223, self.amt=92694282.0902, ukdf['pct'].iloc[-1]=0.002813 , ukdf['amount'].iloc[-1]=92694282.0902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [12/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9177
self.closeSec=1673482499, self.tradeDate='20230112', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17968.7, self.close=17942.3, self.high=17977.3, self.low=17921.4, self.vol=3037.032, self.amt=54516758.9914 
2023-01-12 08:15:00,653:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230112   075000    075459  ...         0.0        0.0       0
5855  20230112   075500    075959  ...         0.0        0.0       0
5856  20230112   080000    080459  ...         0.0        0.0       0
5857  20230112   080500    080959  ...         0.0        0.0       0
5858  20230112   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-12 08:15:00,654:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673482499, self.tradeDate='20230112', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17968.7, self.close=17942.3, self.high=17977.3, self.low=17921.4, self.vol=3037.032, self.amt=54516758.9914, ukdf['pct'].iloc[-1]=-0.001519 , ukdf['amount'].iloc[-1]=54516758.9914, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230111   200000    235959  1673452799  ...    719  1.065789  1.736196     1.0
720  20230112   000000    035959  1673467199  ...    720  1.084789  1.748467     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '18081.6896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17541.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=286
self.closeSec=1673481599, self.tradeDate='20230112', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17540.7, self.close=17935.6, self.high=18013.2, self.low=17501.4, self.vol=144426.875, self.amt=2562553206.41881 
127.0.0.1 - - [12/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-12 08:00:01,046:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673481599, self.tradeDate='20230112', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17540.7, self.close=17935.6, self.high=18013.2, self.low=17501.4, self.vol=144426.875, self.amt=2562553206.41881 
2023-01-12 08:00:01,081:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230111   120000    155959  ...   25910.727  4.512019e+08  0.001683
718  20230111   160000    195959  ...   24797.868  4.323252e+08 -0.000476
719  20230111   200000    235959  ...   62512.096  1.086442e+09 -0.005933
720  20230112   000000    035959  ...   86210.349  1.504725e+09  0.012427
721  20230112   040000    075959  ...  144426.875  2.562553e+09  0.022519

[5 rows x 11 columns]
2023-01-12 08:00:02,537:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230111   120000    155959  1673423999  ...    717  1.161141  2.127499     1.0
718  20230111   160000    195959  1673438399  ...    718  1.083178  1.833845     1.0
719  20230111   200000    235959  1673452799  ...    719  1.065789  1.736196     1.0
720  20230112   000000    035959  1673467199  ...    720  1.084789  1.748467     1.0
721  20230112   040000    075959  1673481599  ...    721  1.297732  2.310525     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '38392.28167014144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17938.98773604', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


