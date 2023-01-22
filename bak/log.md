# 20230122 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [22/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16058
self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22808.3, self.close=22834.5, self.high=22838.0, self.low=22800.9, self.vol=1941.219, self.amt=44298916.9114 
2023-01-22 08:10:01,482:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230122   074500    074959  ...         0.0        0.0       0
5854  20230122   075000    075459  ...         0.0        0.0       0
5855  20230122   075500    075959  ...         0.0        0.0       0
5856  20230122   080000    080459  ...         0.0        0.0       0
5857  20230122   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 08:10:01,482:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22808.3, self.close=22834.5, self.high=22838.0, self.low=22800.9, self.vol=1941.219, self.amt=44298916.9114, ukdf['pct'].iloc[-1]=0.00132 , ukdf['amount'].iloc[-1]=44298916.9114, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-379533.56066226928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22836.35863903', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16059
self.closeSec=1674346499, self.tradeDate='20230122', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22834.5, self.close=22841.6, self.high=22867.8, self.low=22830.7, self.vol=1738.862, self.amt=39730136.0977 
2023-01-22 08:15:00,931:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230122   075000    075459  ...         0.0        0.0       0
5855  20230122   075500    075959  ...         0.0        0.0       0
5856  20230122   080000    080459  ...         0.0        0.0       0
5857  20230122   080500    080959  ...         0.0        0.0       0
5858  20230122   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 08:15:00,933:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674346499, self.tradeDate='20230122', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22834.5, self.close=22841.6, self.high=22867.8, self.low=22830.7, self.vol=1738.862, self.amt=39730136.0977, ukdf['pct'].iloc[-1]=0.000311 , ukdf['amount'].iloc[-1]=39730136.0977, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-380104.57157836144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22845.84765319', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22808.3, self.close=22834.5, self.high=22838.0, self.low=22800.9 
2023-01-22 08:10:01,428:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22808.3, self.close=22834.5, self.high=22838.0, self.low=22800.9   
127.0.0.1 - - [22/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-22 08:10:01,470:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230122   074500    074959  1674344999  ...  22714.8  0.000541   1533    3
1534  20230122   075000    075459  1674345299  ...  22741.7  0.000849   1534    4
1535  20230122   075500    075959  1674345599  ...  22730.4  0.000857   1535    5
1536  20230122   080000    080459  1674345899  ...  22708.4  0.000988   1536    0
1537  20230122   080500    080959  1674346199  ...  22800.9  0.001320   1537    1

[5 rows x 11 columns]
2023-01-22 08:10:01,470:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=61, self.factor=0.20976817094680417, self.count=16625 

self.closeSec=1674346499, self.tradeDate='20230122', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22834.5, self.close=22841.6, self.high=22867.8, self.low=22830.7 
2023-01-22 08:15:00,845:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674346499, self.tradeDate='20230122', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22834.5, self.close=22841.6, self.high=22867.8, self.low=22830.7   
2023-01-22 08:15:00,907:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230122   075000    075459  1674345299  ...  22741.7  0.000849   1534    4
1535  20230122   075500    075959  1674345599  ...  22730.4  0.000857   1535    5
1536  20230122   080000    080459  1674345899  ...  22708.4  0.000988   1536    0
1537  20230122   080500    080959  1674346199  ...  22800.9  0.001320   1537    1
1538  20230122   081000    081459  1674346499  ...  22830.7  0.000311   1538    2

[5 rows x 11 columns]
2023-01-22 08:15:00,907:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-22 08:00:18,057:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230122    052959  23086.4  ...  54.583333  0.649757  0.176609
5771  20230122    055959  23155.1  ...  54.583333  0.654144  0.179253
5772  20230122    062959  23198.7  ...  54.166667  0.626355  0.191895
5773  20230122    065959  23056.9  ...  54.166667  0.572868  0.225606
5774  20230122    072959  22739.6  ...  54.166667  0.578450  0.254930

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-01-22 08:00:18,157:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     0  0.509204  0.490796       1  ...  1.087386   1.0  0.0000  1.340734
537     0  0.510980  0.489020       0  ...  1.080926   1.0  0.0000  1.332769
538     1  0.460674  0.539326       0  ...  1.067011   1.0  0.0000  1.315613
539     1  0.406358  0.593642       1  ...  1.063190  -1.0 -0.0016  1.318220
540     1  0.475090  0.524910       0  ...  1.064276  -1.0  0.0000  1.316873

[5 rows x 10 columns]
2023-01-22 08:00:18,173:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.510552  0.489448       1  ...  1.160779   1.0  0.0000  1.339379
46     0  0.512356  0.487644       0  ...  1.153883   1.0  0.0000  1.332114
47     1  0.460690  0.539310       0  ...  1.067011   1.0  0.0000  1.316062
48     1  0.406358  0.593642       1  ...  1.063190  -1.0 -0.0016  1.318220
49     1  0.475090  0.524910       0  ...  1.064276  -1.0  0.0000  1.316873

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.659', 'enterprice': '22798.2', 'countrevence': '0', 'unrealprofit': '1053.5267', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22766.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230122   074000    074959  1674344999  22833.4  22743.1 -0.004059
2023-01-22 07:50:00,806:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8311 

self.closeSec=1674345599, self.tradeDate='20230122', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22745.6', self.close='22781.9'
2023-01-22 08:00:01,632:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674345599, self.tradeDate='20230122', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22745.6', self.close='22781.9'
127.0.0.1 - - [22/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-22 08:00:01,661:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230122   071000    071959  1674343199  22908.9    22838 -0.003099
620  20230122   072000    072959  1674343799    22838  22805.3 -0.001432
621  20230122   073000    073959  1674344399  22805.3  22835.8  0.001337
622  20230122   074000    074959  1674344999  22833.4  22743.1 -0.004059
623  20230122   075000    075959  1674345599  22745.6  22781.9  0.001706
2023-01-22 08:00:01,661:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8312 

self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22781.8', self.close='22834.5'
2023-01-22 08:10:01,514:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22781.8', self.close='22834.5'
2023-01-22 08:10:01,531:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230122   072000    072959  1674343799    22838  22805.3 -0.001432
621  20230122   073000    073959  1674344399  22805.3  22835.8  0.001337
622  20230122   074000    074959  1674344999  22833.4  22743.1 -0.004059
623  20230122   075000    075959  1674345599  22745.6  22781.9  0.001706
624  20230122   080000    080959  1674346199  22781.8  22834.5  0.002309
2023-01-22 08:10:01,531:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230122   074000    074959  1674344999  22833.4  22743.1
2023-01-22 07:50:00,815:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8312 

self.closeSec=1674345599, self.tradeDate='20230122', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22745.6', self.close='22781.9'
2023-01-22 08:00:01,637:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674345599, self.tradeDate='20230122', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22745.6', self.close='22781.9'
2023-01-22 08:00:01,665:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230122   071000    071959  1674343199  22908.9    22838
17468  20230122   072000    072959  1674343799    22838  22805.3
17469  20230122   073000    073959  1674344399  22805.3  22835.8
17470  20230122   074000    074959  1674344999  22833.4  22743.1
17471  20230122   075000    075959  1674345599  22745.6  22781.9
2023-01-22 08:00:01,665:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8313 

self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22781.8', self.close='22834.5'
2023-01-22 08:10:01,520:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22781.8', self.close='22834.5'
2023-01-22 08:10:01,535:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230122   072000    072959  1674343799    22838  22805.3
17469  20230122   073000    073959  1674344399  22805.3  22835.8
17470  20230122   074000    074959  1674344999  22833.4  22743.1
17471  20230122   075000    075959  1674345599  22745.6  22781.9
17472  20230122   080000    080959  1674346199  22781.8  22834.5
2023-01-22 08:10:01,535:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230122   074000    074959  1674344999  22833.4  22743.1
2023-01-22 07:50:00,810:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [22/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8312 

self.closeSec=1674345599, self.tradeDate='20230122', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22745.6', self.close='22781.9'
2023-01-22 08:00:01,617:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674345599, self.tradeDate='20230122', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22745.6', self.close='22781.9'
2023-01-22 08:00:01,659:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230122   071000    071959  1674343199  22908.9    22838
12140  20230122   072000    072959  1674343799    22838  22805.3
12141  20230122   073000    073959  1674344399  22805.3  22835.8
12142  20230122   074000    074959  1674344999  22833.4  22743.1
12143  20230122   075000    075959  1674345599  22745.6  22781.9
2023-01-22 08:00:01,659:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [22/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8313 

self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22781.8', self.close='22834.5'
2023-01-22 08:10:01,516:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22781.8', self.close='22834.5'
2023-01-22 08:10:01,528:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230122   072000    072959  1674343799    22838  22805.3
12141  20230122   073000    073959  1674344399  22805.3  22835.8
12142  20230122   074000    074959  1674344999  22833.4  22743.1
12143  20230122   075000    075959  1674345599  22745.6  22781.9
12144  20230122   080000    080959  1674346199  22781.8  22834.5
2023-01-22 08:10:01,528:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12056
self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22808.3, self.close=22834.5, self.high=22838.0, self.low=22800.9, self.vol=1941.219, self.amt=44298916.9114 
127.0.0.1 - - [22/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-22 08:10:01,442:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230122   074500    074959  ...         0.0        0.0       0
5854  20230122   075000    075459  ...         0.0        0.0       0
5855  20230122   075500    075959  ...         0.0        0.0       0
5856  20230122   080000    080459  ...         0.0        0.0       0
5857  20230122   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 08:10:01,442:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674346199, self.tradeDate='20230122', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22808.3, self.close=22834.5, self.high=22838.0, self.low=22800.9, self.vol=1941.219, self.amt=44298916.9114, ukdf['pct'].iloc[-1]=0.00132 , ukdf['amount'].iloc[-1]=44298916.9114, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12057
self.closeSec=1674346499, self.tradeDate='20230122', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22834.5, self.close=22841.6, self.high=22867.8, self.low=22830.7, self.vol=1738.862, self.amt=39730136.0977 
2023-01-22 08:15:00,932:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230122   075000    075459  ...         0.0        0.0       0
5855  20230122   075500    075959  ...         0.0        0.0       0
5856  20230122   080000    080459  ...         0.0        0.0       0
5857  20230122   080500    080959  ...         0.0        0.0       0
5858  20230122   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 08:15:00,932:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674346499, self.tradeDate='20230122', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22834.5, self.close=22841.6, self.high=22867.8, self.low=22830.7, self.vol=1738.862, self.amt=39730136.0977, ukdf['pct'].iloc[-1]=0.000311 , ukdf['amount'].iloc[-1]=39730136.0977, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-01-22 04:00:08,921:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41572F1674331203452I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674331203559788, 'quantity': '51.053', 'price': '23272.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674331203099, 'updatetime': 1674331203559, 'tradetype': 'usdt', 'selfid': 41572, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674331203559, 'clientorderid': '41572F1674331203452I0L65', 'price': '23272.3', 'quantity': '51.053', 'commission': '1188.1207319', 'commissionasset': 'USDT', 'tradetime': 1674331203559, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674331203559}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-22 04:00:08,921:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41572F1674331203452I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674331203559788, 'quantity': '51.053', 'price': '23272.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674331203099, 'updatetime': 1674331203559, 'tradetype': 'usdt', 'selfid': 41572, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674331203559, 'clientorderid': '41572F1674331203452I0L65', 'price': '23272.3', 'quantity': '51.053', 'commission': '1188.1207319', 'commissionasset': 'USDT', 'tradetime': 1674331203559, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674331203559}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-22 04:00:09,015:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41573F1674331208881I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674331208974168, 'quantity': '41.799', 'price': '23284.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674331208666, 'updatetime': 1674331208974, 'tradetype': 'usdt', 'selfid': 41573, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674331208974, 'clientorderid': '41573F1674331208881I0L65', 'price': '23284.2', 'quantity': '41.799', 'commission': '973.2562758', 'commissionasset': 'USDT', 'tradetime': 1674331208974, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674331208974}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Jan/2023 04:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Jan/2023 04:00:09] "POST / HTTP/1.1" 200 -
2023-01-22 04:00:09,197:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41573F1674331208881I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674331208974168, 'quantity': '41.799', 'price': '23284.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674331208666, 'updatetime': 1674331208974, 'tradetype': 'usdt', 'selfid': 41573, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674331208974, 'clientorderid': '41573F1674331208881I0L65', 'price': '23284.2', 'quantity': '41.799', 'commission': '973.2562758', 'commissionasset': 'USDT', 'tradetime': 1674331208974, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674331208974}], 'gatetype': 'simulator', 'handletime': 0}
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=972283.0195242, self.flagDict['side']='buy', self.tradeCount=14, self.count=346
self.closeSec=1674345599, self.tradeDate='20230122', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23271.9, self.close=22781.9, self.high=23298.2, self.low=22670.0, self.vol=98007.119, self.amt=2253013198.21012 
127.0.0.1 - - [22/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-22 08:00:01,528:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674345599, self.tradeDate='20230122', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23271.9, self.close=22781.9, self.high=23298.2, self.low=22670.0, self.vol=98007.119, self.amt=2253013198.21012 
2023-01-22 08:00:01,564:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230121   120000    155959  ...   32823.977  7.419001e+08  0.003984
718  20230121   160000    195959  ...  266330.182  6.102600e+09  0.012019
719  20230121   200000    235959  ...  145710.162  3.357102e+09  0.004047
720  20230122   000000    035959  ...  130707.129  3.031658e+09  0.011989
721  20230122   040000    075959  ...   98007.119  2.253013e+09 -0.021055

[5 rows x 11 columns]
2023-01-22 08:00:02,985:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230121   120000    155959  1674287999  ...    717  0.778042  0.107792     NaN
718  20230121   160000    195959  1674302399  ...    718  0.980106  0.549824     NaN
719  20230121   200000    235959  1674316799  ...    719  1.000848  0.581866     NaN
720  20230122   000000    035959  1674331199  ...    720  1.018084  0.606025     1.0
721  20230122   040000    075959  1674345599  ...    721  1.060041  0.686393     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-20995.6377', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22781.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


