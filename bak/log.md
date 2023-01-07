# 20230107 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11738
self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16936.7, self.close=16931.0, self.high=16938.2, self.low=16924.8, self.vol=1001.335, self.amt=16954702.8187 
127.0.0.1 - - [07/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 08:10:01,454:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230107   074500    074959  ...         0.0        0.0       0
5854  20230107   075000    075459  ...         0.0        0.0       0
5855  20230107   075500    075959  ...         0.0        0.0       0
5856  20230107   080000    080459  ...         0.0        0.0       0
5857  20230107   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 08:10:01,454:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16936.7, self.close=16931.0, self.high=16938.2, self.low=16924.8, self.vol=1001.335, self.amt=16954702.8187, ukdf['pct'].iloc[-1]=-0.000331 , ukdf['amount'].iloc[-1]=16954702.8187, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-24228.24843765808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16931.92311283', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11739
self.closeSec=1673050499, self.tradeDate='20230107', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16930.9, self.close=16936.6, self.high=16941.2, self.low=16930.9, self.vol=494.039, self.amt=8366882.3782 
127.0.0.1 - - [07/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-07 08:15:00,594:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230107   075000    075459  ...         0.0        0.0       0
5855  20230107   075500    075959  ...         0.0        0.0       0
5856  20230107   080000    080459  ...         0.0        0.0       0
5857  20230107   080500    080959  ...         0.0        0.0       0
5858  20230107   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 08:15:00,594:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673050499, self.tradeDate='20230107', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16930.9, self.close=16936.6, self.high=16941.2, self.low=16930.9, self.vol=494.039, self.amt=8366882.3782, ukdf['pct'].iloc[-1]=0.000331 , ukdf['amount'].iloc[-1]=8366882.3782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-24503.6672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16936.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16936.7, self.close=16931.0, self.high=16938.2, self.low=16924.8 
2023-01-07 08:10:01,424:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16936.7, self.close=16931.0, self.high=16938.2, self.low=16924.8   
127.0.0.1 - - [07/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 08:10:01,474:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230107   074500    074959  1673048999  ...  16935.0  0.001081   1533    3
1534  20230107   075000    075459  1673049299  ...  16943.6 -0.000572   1534    4
1535  20230107   075500    075959  1673049599  ...  16943.6  0.000012   1535    5
1536  20230107   080000    080459  1673049899  ...  16933.6 -0.000425   1536    0
1537  20230107   080500    080959  1673050199  ...  16924.8 -0.000331   1537    1

[5 rows x 11 columns]
2023-01-07 08:10:01,474:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=16, self.factor=0.44301570832842985, self.count=12305 

self.closeSec=1673050499, self.tradeDate='20230107', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16930.9, self.close=16936.6, self.high=16941.2, self.low=16930.9 
2023-01-07 08:15:00,542:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673050499, self.tradeDate='20230107', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16930.9, self.close=16936.6, self.high=16941.2, self.low=16930.9   
127.0.0.1 - - [07/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-07 08:15:00,584:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230107   075000    075459  1673049299  ...  16943.6 -0.000572   1534    4
1535  20230107   075500    075959  1673049599  ...  16943.6  0.000012   1535    5
1536  20230107   080000    080459  1673049899  ...  16933.6 -0.000425   1536    0
1537  20230107   080500    080959  1673050199  ...  16924.8 -0.000331   1537    1
1538  20230107   081000    081459  1673050499  ...  16930.9  0.000331   1538    2

[5 rows x 11 columns]
2023-01-07 08:15:00,584:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-07 08:00:17,971:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230107    052959  16888.6  ...  48.750000  0.565726  0.388216
5771  20230107    055959  16917.0  ...  48.750000  0.568751  0.381886
5772  20230107    062959  16923.0  ...  49.166667  0.580377  0.371779
5773  20230107    065959  16946.0  ...  49.166667  0.581777  0.361835
5774  20230107    072959  16948.8  ...  49.166667  0.587101  0.350619

[5 rows x 33 columns]
0.5415896487985212
acc is : 0.5415896487985212
2023-01-07 08:00:18,071:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     0  0.515873  0.484127       1  ...  NaN   NaN -0.0016  1.005861
537     0  0.511064  0.488936       1  ...  NaN   NaN -0.0016  1.007228
538     0  0.509364  0.490636       1  ...  NaN   NaN -0.0016  1.007394
539     0  0.505068  0.494932       1  ...  NaN   NaN -0.0016  1.008024
540     0  0.512722  0.487278       0  ...  NaN   NaN -0.0016  1.007103

[5 rows x 10 columns]
2023-01-07 08:00:18,091:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.516018  0.483982       1  ...  NaN   NaN -0.0016  1.007244
46     0  0.511065  0.488935       1  ...  NaN   NaN -0.0016  1.007335
47     0  0.509151  0.490849       1  ...  NaN   NaN -0.0016  1.006969
48     0  0.505487  0.494513       1  ...  NaN   NaN -0.0016  1.008024
49     0  0.512722  0.487278       0  ...  NaN   NaN -0.0016  1.007103

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '10364.0736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16945.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230107   074000    074959  1673048999  16944.8  16953.3  0.000508
2023-01-07 07:50:00,613:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6151 

self.closeSec=1673049599, self.tradeDate='20230107', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16953.3', self.close='16943.8'
2023-01-07 08:00:01,132:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673049599, self.tradeDate='20230107', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16953.3', self.close='16943.8'
2023-01-07 08:00:01,164:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230107   071000    071959  1673047199  16952.9  16968.1  0.000897
620  20230107   072000    072959  1673047799  16968.1  16959.3 -0.000519
621  20230107   073000    073959  1673048399  16959.3  16944.7 -0.000861
622  20230107   074000    074959  1673048999  16944.8  16953.3  0.000508
623  20230107   075000    075959  1673049599  16953.3  16943.8 -0.000560
2023-01-07 08:00:01,164:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6152 

self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16943.9', self.close='16931'
2023-01-07 08:10:01,527:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16943.9', self.close='16931'
2023-01-07 08:10:01,562:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230107   072000    072959  1673047799  16968.1  16959.3 -0.000519
621  20230107   073000    073959  1673048399  16959.3  16944.7 -0.000861
622  20230107   074000    074959  1673048999  16944.8  16953.3  0.000508
623  20230107   075000    075959  1673049599  16953.3  16943.8 -0.000560
624  20230107   080000    080959  1673050199  16943.9    16931 -0.000755
2023-01-07 08:10:01,562:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230107   074000    074959  1673048999  16944.8  16953.3
2023-01-07 07:50:00,585:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6152 

self.closeSec=1673049599, self.tradeDate='20230107', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16953.3', self.close='16943.8'
2023-01-07 08:00:01,147:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673049599, self.tradeDate='20230107', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16953.3', self.close='16943.8'
2023-01-07 08:00:01,179:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230107   071000    071959  1673047199  16952.9  16968.1
17468  20230107   072000    072959  1673047799  16968.1  16959.3
17469  20230107   073000    073959  1673048399  16959.3  16944.7
17470  20230107   074000    074959  1673048999  16944.8  16953.3
17471  20230107   075000    075959  1673049599  16953.3  16943.8
2023-01-07 08:00:01,179:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6153 

self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16943.9', self.close='16931'
2023-01-07 08:10:01,516:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16943.9', self.close='16931'
127.0.0.1 - - [07/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 08:10:01,533:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230107   072000    072959  1673047799  16968.1  16959.3
17469  20230107   073000    073959  1673048399  16959.3  16944.7
17470  20230107   074000    074959  1673048999  16944.8  16953.3
17471  20230107   075000    075959  1673049599  16953.3  16943.8
17472  20230107   080000    080959  1673050199  16943.9    16931
2023-01-07 08:10:01,534:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230107   074000    074959  1673048999  16944.8  16953.3
2023-01-07 07:50:00,609:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6152 

self.closeSec=1673049599, self.tradeDate='20230107', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16953.3', self.close='16943.8'
2023-01-07 08:00:01,142:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673049599, self.tradeDate='20230107', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16953.3', self.close='16943.8'
2023-01-07 08:00:01,227:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230107   071000    071959  1673047199  16952.9  16968.1
12140  20230107   072000    072959  1673047799  16968.1  16959.3
12141  20230107   073000    073959  1673048399  16959.3  16944.7
12142  20230107   074000    074959  1673048999  16944.8  16953.3
12143  20230107   075000    075959  1673049599  16953.3  16943.8
2023-01-07 08:00:01,228:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6153 

self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16943.9', self.close='16931'
2023-01-07 08:10:01,546:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16943.9', self.close='16931'
127.0.0.1 - - [07/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 08:10:01,586:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230107   072000    072959  1673047799  16968.1  16959.3
12141  20230107   073000    073959  1673048399  16959.3  16944.7
12142  20230107   074000    074959  1673048999  16944.8  16953.3
12143  20230107   075000    075959  1673049599  16953.3  16943.8
12144  20230107   080000    080959  1673050199  16943.9    16931
2023-01-07 08:10:01,587:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [07/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7736
self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16936.7, self.close=16931.0, self.high=16938.2, self.low=16924.8, self.vol=1001.335, self.amt=16954702.8187 
2023-01-07 08:10:01,489:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230107   074500    074959  ...         0.0        0.0       0
5854  20230107   075000    075459  ...         0.0        0.0       0
5855  20230107   075500    075959  ...         0.0        0.0       0
5856  20230107   080000    080459  ...         0.0        0.0       0
5857  20230107   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 08:10:01,489:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673050199, self.tradeDate='20230107', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16936.7, self.close=16931.0, self.high=16938.2, self.low=16924.8, self.vol=1001.335, self.amt=16954702.8187, ukdf['pct'].iloc[-1]=-0.000331 , ukdf['amount'].iloc[-1]=16954702.8187, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7737
self.closeSec=1673050499, self.tradeDate='20230107', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16930.9, self.close=16936.6, self.high=16941.2, self.low=16930.9, self.vol=494.039, self.amt=8366882.3782 
127.0.0.1 - - [07/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-07 08:15:00,561:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230107   075000    075459  ...         0.0        0.0       0
5855  20230107   075500    075959  ...         0.0        0.0       0
5856  20230107   080000    080459  ...         0.0        0.0       0
5857  20230107   080500    080959  ...         0.0        0.0       0
5858  20230107   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 08:15:00,561:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673050499, self.tradeDate='20230107', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16930.9, self.close=16936.6, self.high=16941.2, self.low=16930.9, self.vol=494.039, self.amt=8366882.3782, ukdf['pct'].iloc[-1]=0.000331 , ukdf['amount'].iloc[-1]=8366882.3782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230106   200000    235959  1673020799  ...    719  0.364248  0.223422     NaN
720  20230107   000000    035959  1673035199  ...    720  0.393304  0.307458     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '11393.043', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16939', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [07/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=256
self.closeSec=1673049599, self.tradeDate='20230107', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16932.7, self.close=16943.8, self.high=17030.0, self.low=16881.0, self.vol=68235.521, self.amt=1156655763.45893 
2023-01-07 08:00:00,976:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673049599, self.tradeDate='20230107', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16932.7, self.close=16943.8, self.high=17030.0, self.low=16881.0, self.vol=68235.521, self.amt=1156655763.45893 
2023-01-07 08:00:01,006:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230106   120000    155959  ...   23858.140  4.007046e+08 -0.002336
718  20230106   160000    195959  ...   43526.534  7.292327e+08 -0.003229
719  20230106   200000    235959  ...  102292.442  1.714161e+09  0.006132
720  20230107   000000    035959  ...   57986.610  9.782164e+08  0.005851
721  20230107   040000    075959  ...   68235.521  1.156656e+09  0.000661

[5 rows x 11 columns]
2023-01-07 08:00:02,409:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230106   120000    155959  1672991999  ...    717  0.397553  0.357165     NaN
718  20230106   160000    195959  1673006399  ...    718  0.430357  0.451420     NaN
719  20230106   200000    235959  1673020799  ...    719  0.364248  0.223422     NaN
720  20230107   000000    035959  1673035199  ...    720  0.393304  0.307458     NaN
721  20230107   040000    075959  1673049599  ...    721  0.505149  0.661141     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '11646.339', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16943.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


