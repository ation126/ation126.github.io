# 20230129 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [29/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18074
self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23021.3, self.close=23023.2, self.high=23023.9, self.low=23015.3, self.vol=300.233, self.amt=6911630.1154 
2023-01-29 08:10:01,472:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230129   074500    074959  ...         0.0        0.0       0
5854  20230129   075000    075459  ...         0.0        0.0       0
5855  20230129   075500    075959  ...         0.0        0.0       0
5856  20230129   080000    080459  ...         0.0        0.0       0
5857  20230129   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-29 08:10:01,472:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23021.3, self.close=23023.2, self.high=23023.9, self.low=23015.3, self.vol=300.233, self.amt=6911630.1154, ukdf['pct'].iloc[-1]=7.8e-05 , ukdf['amount'].iloc[-1]=6911630.1154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-390776.9264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23023.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18075
self.closeSec=1674951299, self.tradeDate='20230129', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23023.3, self.close=22985.4, self.high=23023.3, self.low=22985.4, self.vol=692.515, self.amt=15931627.5695 
127.0.0.1 - - [29/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-29 08:15:00,744:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230129   075000    075459  ...         0.0        0.0       0
5855  20230129   075500    075959  ...         0.0        0.0       0
5856  20230129   080000    080459  ...         0.0        0.0       0
5857  20230129   080500    080959  ...         0.0        0.0       0
5858  20230129   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-29 08:15:00,744:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674951299, self.tradeDate='20230129', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23023.3, self.close=22985.4, self.high=23023.3, self.low=22985.4, self.vol=692.515, self.amt=15931627.5695, ukdf['pct'].iloc[-1]=-0.001642 , ukdf['amount'].iloc[-1]=15931627.5695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-388584.88956076624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22986.77290549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23021.3, self.close=23023.2, self.high=23023.9, self.low=23015.3 
2023-01-29 08:10:01,415:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23021.3, self.close=23023.2, self.high=23023.9, self.low=23015.3   
127.0.0.1 - - [29/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-29 08:10:01,451:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230129   074500    074959  1674949799  ...  22975.7  0.000431   1533    3
1534  20230129   075000    075459  1674950099  ...  22990.3  0.000191   1534    4
1535  20230129   075500    075959  1674950399  ...  22999.2  0.000722   1535    5
1536  20230129   080000    080459  1674950699  ...  23012.3  0.000239   1536    0
1537  20230129   080500    080959  1674950999  ...  23015.3  0.000078   1537    1

[5 rows x 11 columns]
2023-01-29 08:10:01,451:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=397, self.factor=0.5706830408989789, self.count=18641 

self.closeSec=1674951299, self.tradeDate='20230129', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23023.3, self.close=22985.4, self.high=23023.3, self.low=22985.4 
2023-01-29 08:15:00,718:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674951299, self.tradeDate='20230129', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23023.3, self.close=22985.4, self.high=23023.3, self.low=22985.4   
127.0.0.1 - - [29/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-29 08:15:00,737:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230129   075000    075459  1674950099  ...  22990.3  0.000191   1534    4
1535  20230129   075500    075959  1674950399  ...  22999.2  0.000722   1535    5
1536  20230129   080000    080459  1674950699  ...  23012.3  0.000239   1536    0
1537  20230129   080500    080959  1674950999  ...  23015.3  0.000078   1537    1
1538  20230129   081000    081459  1674951299  ...  22985.4 -0.001642   1538    2

[5 rows x 11 columns]
2023-01-29 08:15:00,737:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-29 08:00:19,091:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230129    052959  22959.1  ...  52.083333  0.495977  0.659826
5771  20230129    055959  22985.0  ...  52.083333  0.498481  0.651276
5772  20230129    062959  22993.9  ...  52.083333  0.495377  0.646087
5773  20230129    065959  22982.9  ...  52.083333  0.491686  0.644542
5774  20230129    072959  22969.9  ...  52.500000  0.499040  0.636732

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-01-29 08:00:19,181:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.519905  0.480095       1  ...  1.005295   1.0    0.0  1.088458
537     0  0.513346  0.486654       0  ...  1.004814   1.0    0.0  1.087938
538     0  0.511031  0.488969       0  ...  1.004246   1.0    0.0  1.087322
539     0  0.512331  0.487669       1  ...  1.005343   1.0    0.0  1.088510
540     0  0.524246  0.475754       1  ...  1.006257   1.0    0.0  1.089500

[5 rows x 10 columns]
2023-01-29 08:00:19,200:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518863  0.481137       1  ...  0.988078   1.0    0.0  1.085868
46     0  0.512959  0.487041       0  ...  1.004814   1.0    0.0  1.086231
47     0  0.510249  0.489751       0  ...  1.004246   1.0    0.0  1.085529
48     0  0.512021  0.487979       1  ...  1.005343   1.0    0.0  1.088510
49     0  0.524246  0.475754       1  ...  1.006257   1.0    0.0  1.089500

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.8', 'enterprice': '23035.8', 'countrevence': '0', 'unrealprofit': '-557.00746178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23017.71534215', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230129   074000    074959  1674949799  22990.6  22994.9  0.000187
2023-01-29 07:50:00,747:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9319 

self.closeSec=1674950399, self.tradeDate='20230129', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22994.9', self.close='23015.9'
2023-01-29 08:00:01,943:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674950399, self.tradeDate='20230129', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22994.9', self.close='23015.9'
2023-01-29 08:00:02,000:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230129   071000    071959  1674947999  22965.3  22991.8  0.001158
620  20230129   072000    072959  1674948599  22991.9    22995  0.000139
621  20230129   073000    073959  1674949199  22995.1  22990.6 -0.000191
622  20230129   074000    074959  1674949799  22990.6  22994.9  0.000187
623  20230129   075000    075959  1674950399  22994.9  23015.9  0.000913
2023-01-29 08:00:02,002:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9320 

self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23016', self.close='23023.2'
2023-01-29 08:10:01,499:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23016', self.close='23023.2'
2023-01-29 08:10:01,533:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230129   072000    072959  1674948599  22991.9    22995  0.000139
621  20230129   073000    073959  1674949199  22995.1  22990.6 -0.000191
622  20230129   074000    074959  1674949799  22990.6  22994.9  0.000187
623  20230129   075000    075959  1674950399  22994.9  23015.9  0.000913
624  20230129   080000    080959  1674950999    23016  23023.2  0.000317
2023-01-29 08:10:01,534:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230129   074000    074959  1674949799  22990.6  22994.9
2023-01-29 07:50:00,757:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9320 

self.closeSec=1674950399, self.tradeDate='20230129', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22994.9', self.close='23015.9'
2023-01-29 08:00:01,990:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674950399, self.tradeDate='20230129', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22994.9', self.close='23015.9'
2023-01-29 08:00:02,009:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230129   071000    071959  1674947999  22965.3  22991.8
17468  20230129   072000    072959  1674948599  22991.9    22995
17469  20230129   073000    073959  1674949199  22995.1  22990.6
17470  20230129   074000    074959  1674949799  22990.6  22994.9
17471  20230129   075000    075959  1674950399  22994.9  23015.9
2023-01-29 08:00:02,009:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9321 

self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23016', self.close='23023.2'
2023-01-29 08:10:01,536:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23016', self.close='23023.2'
2023-01-29 08:10:01,543:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230129   072000    072959  1674948599  22991.9    22995
17469  20230129   073000    073959  1674949199  22995.1  22990.6
17470  20230129   074000    074959  1674949799  22990.6  22994.9
17471  20230129   075000    075959  1674950399  22994.9  23015.9
17472  20230129   080000    080959  1674950999    23016  23023.2
2023-01-29 08:10:01,544:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230129   074000    074959  1674949799  22990.6  22994.9
2023-01-29 07:50:00,794:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9320 

self.closeSec=1674950399, self.tradeDate='20230129', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22994.9', self.close='23015.9'
2023-01-29 08:00:01,960:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674950399, self.tradeDate='20230129', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22994.9', self.close='23015.9'
127.0.0.1 - - [29/Jan/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-01-29 08:00:02,020:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230129   071000    071959  1674947999  22965.3  22991.8
12140  20230129   072000    072959  1674948599  22991.9    22995
12141  20230129   073000    073959  1674949199  22995.1  22990.6
12142  20230129   074000    074959  1674949799  22990.6  22994.9
12143  20230129   075000    075959  1674950399  22994.9  23015.9
2023-01-29 08:00:02,033:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9321 

self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23016', self.close='23023.2'
2023-01-29 08:10:01,518:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23016', self.close='23023.2'
127.0.0.1 - - [29/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-29 08:10:01,542:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230129   072000    072959  1674948599  22991.9    22995
12141  20230129   073000    073959  1674949199  22995.1  22990.6
12142  20230129   074000    074959  1674949799  22990.6  22994.9
12143  20230129   075000    075959  1674950399  22994.9  23015.9
12144  20230129   080000    080959  1674950999    23016  23023.2
2023-01-29 08:10:01,542:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14072
self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23021.3, self.close=23023.2, self.high=23023.9, self.low=23015.3, self.vol=300.233, self.amt=6911630.1154 
127.0.0.1 - - [29/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-29 08:10:01,473:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230129   074500    074959  ...         0.0        0.0       0
5854  20230129   075000    075459  ...         0.0        0.0       0
5855  20230129   075500    075959  ...         0.0        0.0       0
5856  20230129   080000    080459  ...         0.0        0.0       0
5857  20230129   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-29 08:10:01,473:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674950999, self.tradeDate='20230129', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23021.3, self.close=23023.2, self.high=23023.9, self.low=23015.3, self.vol=300.233, self.amt=6911630.1154, ukdf['pct'].iloc[-1]=7.8e-05 , ukdf['amount'].iloc[-1]=6911630.1154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14073
self.closeSec=1674951299, self.tradeDate='20230129', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23023.3, self.close=22985.4, self.high=23023.3, self.low=22985.4, self.vol=692.515, self.amt=15931627.5695 
127.0.0.1 - - [29/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-29 08:15:00,769:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230129   075000    075459  ...         0.0        0.0       0
5855  20230129   075500    075959  ...         0.0        0.0       0
5856  20230129   080000    080459  ...         0.0        0.0       0
5857  20230129   080500    080959  ...         0.0        0.0       0
5858  20230129   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-29 08:15:00,769:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674951299, self.tradeDate='20230129', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23023.3, self.close=22985.4, self.high=23023.3, self.low=22985.4, self.vol=692.515, self.amt=15931627.5695, ukdf['pct'].iloc[-1]=-0.001642 , ukdf['amount'].iloc[-1]=15931627.5695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230128   200000    235959  1674921599  ...    719  0.189366 -0.953117    -1.0
720  20230129   000000    035959  1674935999  ...    720  0.160954 -0.998196    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-4403.359', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23033.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [29/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=388
self.closeSec=1674950399, self.tradeDate='20230129', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23033.2, self.close=23015.9, self.high=23036.2, self.low=22935.1, self.vol=20401.518, self.amt=468923738.2442 
2023-01-29 08:00:01,809:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674950399, self.tradeDate='20230129', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23033.2, self.close=23015.9, self.high=23036.2, self.low=22935.1, self.vol=20401.518, self.amt=468923738.2442 
2023-01-29 08:00:01,852:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230128   120000    155959  ...  29492.397  6.790772e+08 -0.005396
718  20230128   160000    195959  ...  36651.176  8.419766e+08 -0.000474
719  20230128   200000    235959  ...  49477.228  1.135744e+09  0.001362
720  20230129   000000    035959  ...  19771.548  4.549539e+08  0.001235
721  20230129   040000    075959  ...  20401.518  4.689237e+08 -0.000747

[5 rows x 11 columns]
2023-01-29 08:00:03,365:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230128   120000    155959  1674892799  ...    717  0.205949 -0.956298    -1.0
718  20230128   160000    195959  1674907199  ...    718  0.203517 -0.940949    -1.0
719  20230128   200000    235959  1674921599  ...    719  0.189366 -0.953117    -1.0
720  20230129   000000    035959  1674935999  ...    720  0.160954 -0.998196    -1.0
721  20230129   040000    075959  1674950399  ...    721  0.142844 -1.020068    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-3744.7582901074', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23017.4205973', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


