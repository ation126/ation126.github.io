# 20230121 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15770
self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22633.5, self.close=22656.7, self.high=22812.4, self.low=22633.5, self.vol=13322.497, self.amt=302696276.74695 
127.0.0.1 - - [21/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 08:10:01,509:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230121   074500    074959  ...         0.0        0.0       0
5854  20230121   075000    075459  ...         0.0        0.0       0
5855  20230121   075500    075959  ...         0.0        0.0       0
5856  20230121   080000    080459  ...         0.0        0.0       0
5857  20230121   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 08:10:01,509:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22633.5, self.close=22656.7, self.high=22812.4, self.low=22633.5, self.vol=13322.497, self.amt=302696276.74695, ukdf['pct'].iloc[-1]=0.001043 , ukdf['amount'].iloc[-1]=302696276.74695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-368457.4765405232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22652.2971507', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15771
self.closeSec=1674260099, self.tradeDate='20230121', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22645.8, self.close=22528.5, self.high=22660.8, self.low=22422.0, self.vol=19262.978, self.amt=433857299.3636 
127.0.0.1 - - [21/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-21 08:15:00,662:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230121   075000    075459  ...         0.0        0.0       0
5855  20230121   075500    075959  ...         0.0        0.0       0
5856  20230121   080000    080459  ...         0.0        0.0       0
5857  20230121   080500    080959  ...         0.0        0.0       0
5858  20230121   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 08:15:00,662:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674260099, self.tradeDate='20230121', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22645.8, self.close=22528.5, self.high=22660.8, self.low=22422.0, self.vol=19262.978, self.amt=433857299.3636, ukdf['pct'].iloc[-1]=-0.005658 , ukdf['amount'].iloc[-1]=433857299.3636, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-360779.1904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22524.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22633.5, self.close=22656.7, self.high=22812.4, self.low=22633.5 
2023-01-21 08:10:01,436:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22633.5, self.close=22656.7, self.high=22812.4, self.low=22633.5   
127.0.0.1 - - [21/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 08:10:01,458:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230121   074500    074959  1674258599  ...  22634.5 -0.001063   1533    3
1534  20230121   075000    075459  1674258899  ...  22649.0  0.000728   1534    4
1535  20230121   075500    075959  1674259199  ...  22660.0 -0.000106   1535    5
1536  20230121   080000    080459  1674259499  ...  22609.4 -0.001381   1536    0
1537  20230121   080500    080959  1674259799  ...  22633.5  0.001043   1537    1

[5 rows x 11 columns]
2023-01-21 08:10:01,458:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=13, self.factor=0.29928383160875094, self.count=16337 

self.closeSec=1674260099, self.tradeDate='20230121', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22645.8, self.close=22528.5, self.high=22660.8, self.low=22422.0 
2023-01-21 08:15:00,623:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674260099, self.tradeDate='20230121', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22645.8, self.close=22528.5, self.high=22660.8, self.low=22422.0   
2023-01-21 08:15:00,663:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230121   075000    075459  1674258899  ...  22649.0  0.000728   1534    4
1535  20230121   075500    075959  1674259199  ...  22660.0 -0.000106   1535    5
1536  20230121   080000    080459  1674259499  ...  22609.4 -0.001381   1536    0
1537  20230121   080500    080959  1674259799  ...  22633.5  0.001043   1537    1
1538  20230121   081000    081459  1674260099  ...  22422.0 -0.005658   1538    2

[5 rows x 11 columns]
2023-01-21 08:15:00,664:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-21 08:00:20,193:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230121    052959  22287.2  ...  52.916667  0.721220  0.248662
5771  20230121    055959  22283.1  ...  52.916667  0.724020  0.237650
5772  20230121    062959  22309.9  ...  53.333333  0.748220  0.228415
5773  20230121    065959  22562.7  ...  53.333333  0.750406  0.218926
5774  20230121    072959  22590.5  ...  53.750000  0.755442  0.208048

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-01-21 08:00:20,294:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.633746  0.366254       1  ...  1.012723   1.0    0.0  1.286190
537     0  0.640398  0.359602       1  ...  1.024176   1.0    0.0  1.300736
538     0  0.693732  0.306268       1  ...  1.025297   1.0    0.0  1.302160
539     0  0.624718  0.375282       1  ...  1.027902   1.0    0.0  1.305469
540     0  0.596941  0.403059       1  ...  1.028810   1.0    0.0  1.306622

[5 rows x 10 columns]
2023-01-21 08:00:20,308:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.633966  0.366034       1  ...  1.012723   1.0    0.0  1.292554
46     0  0.640517  0.359483       1  ...  1.024176   1.0    0.0  1.304707
47     0  0.693647  0.306353       1  ...  1.025297   1.0    0.0  1.304220
48     0  0.624718  0.375282       1  ...  1.027902   1.0    0.0  1.305469
49     0  0.596941  0.403059       1  ...  1.028810   1.0    0.0  1.306622

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.709', 'enterprice': '20883.4', 'countrevence': '0', 'unrealprofit': '60262.68658705269', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22671.13284841', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230121   074000    074959  1674258599  22636.7  22650.3  0.000610
2023-01-21 07:50:00,557:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8167 

self.closeSec=1674259199, self.tradeDate='20230121', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22650.3', self.close='22661.1'
2023-01-21 08:00:01,798:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674259199, self.tradeDate='20230121', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22650.3', self.close='22661.1'
2023-01-21 08:00:01,824:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230121   071000    071959  1674256799  22599.8    22680  0.003549
620  20230121   072000    072959  1674257399    22680  22644.4 -0.001570
621  20230121   073000    073959  1674257999  22642.5  22636.5 -0.000349
622  20230121   074000    074959  1674258599  22636.7  22650.3  0.000610
623  20230121   075000    075959  1674259199  22650.3  22661.1  0.000477
2023-01-21 08:00:01,824:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8168 

self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22661', self.close='22656.7'
2023-01-21 08:10:01,520:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22661', self.close='22656.7'
2023-01-21 08:10:01,546:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230121   072000    072959  1674257399    22680  22644.4 -0.001570
621  20230121   073000    073959  1674257999  22642.5  22636.5 -0.000349
622  20230121   074000    074959  1674258599  22636.7  22650.3  0.000610
623  20230121   075000    075959  1674259199  22650.3  22661.1  0.000477
624  20230121   080000    080959  1674259799    22661  22656.7 -0.000194
2023-01-21 08:10:01,546:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230121   074000    074959  1674258599  22636.7  22650.3
2023-01-21 07:50:00,564:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8168 

self.closeSec=1674259199, self.tradeDate='20230121', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22650.3', self.close='22661.1'
2023-01-21 08:00:01,817:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674259199, self.tradeDate='20230121', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22650.3', self.close='22661.1'
2023-01-21 08:00:01,837:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230121   071000    071959  1674256799  22599.8    22680
17468  20230121   072000    072959  1674257399    22680  22644.4
17469  20230121   073000    073959  1674257999  22642.5  22636.5
17470  20230121   074000    074959  1674258599  22636.7  22650.3
17471  20230121   075000    075959  1674259199  22650.3  22661.1
2023-01-21 08:00:01,850:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8169 

self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22661', self.close='22656.7'
2023-01-21 08:10:01,549:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22661', self.close='22656.7'
2023-01-21 08:10:01,576:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230121   072000    072959  1674257399    22680  22644.4
17469  20230121   073000    073959  1674257999  22642.5  22636.5
17470  20230121   074000    074959  1674258599  22636.7  22650.3
17471  20230121   075000    075959  1674259199  22650.3  22661.1
17472  20230121   080000    080959  1674259799    22661  22656.7
2023-01-21 08:10:01,576:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230121   074000    074959  1674258599  22636.7  22650.3
2023-01-21 07:50:00,561:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8168 

self.closeSec=1674259199, self.tradeDate='20230121', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22650.3', self.close='22661.1'
2023-01-21 08:00:01,807:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674259199, self.tradeDate='20230121', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22650.3', self.close='22661.1'
2023-01-21 08:00:01,832:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230121   071000    071959  1674256799  22599.8    22680
12140  20230121   072000    072959  1674257399    22680  22644.4
12141  20230121   073000    073959  1674257999  22642.5  22636.5
12142  20230121   074000    074959  1674258599  22636.7  22650.3
12143  20230121   075000    075959  1674259199  22650.3  22661.1
2023-01-21 08:00:01,832:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8169 

self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22661', self.close='22656.7'
2023-01-21 08:10:01,539:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22661', self.close='22656.7'
127.0.0.1 - - [21/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 08:10:01,551:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230121   072000    072959  1674257399    22680  22644.4
12141  20230121   073000    073959  1674257999  22642.5  22636.5
12142  20230121   074000    074959  1674258599  22636.7  22650.3
12143  20230121   075000    075959  1674259199  22650.3  22661.1
12144  20230121   080000    080959  1674259799    22661  22656.7
2023-01-21 08:10:01,551:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11768
self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22633.5, self.close=22656.7, self.high=22812.4, self.low=22633.5, self.vol=13322.497, self.amt=302696276.74695 
127.0.0.1 - - [21/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 08:10:01,465:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230121   074500    074959  ...         0.0        0.0       0
5854  20230121   075000    075459  ...         0.0        0.0       0
5855  20230121   075500    075959  ...         0.0        0.0       0
5856  20230121   080000    080459  ...         0.0        0.0       0
5857  20230121   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 08:10:01,466:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674259799, self.tradeDate='20230121', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22633.5, self.close=22656.7, self.high=22812.4, self.low=22633.5, self.vol=13322.497, self.amt=302696276.74695, ukdf['pct'].iloc[-1]=0.001043 , ukdf['amount'].iloc[-1]=302696276.74695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11769
self.closeSec=1674260099, self.tradeDate='20230121', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22645.8, self.close=22528.5, self.high=22660.8, self.low=22422.0, self.vol=19262.978, self.amt=433857299.3636 
127.0.0.1 - - [21/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-21 08:15:00,661:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230121   075000    075459  ...         0.0        0.0       0
5855  20230121   075500    075959  ...         0.0        0.0       0
5856  20230121   080000    080459  ...         0.0        0.0       0
5857  20230121   080500    080959  ...         0.0        0.0       0
5858  20230121   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 08:15:00,661:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674260099, self.tradeDate='20230121', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22645.8, self.close=22528.5, self.high=22660.8, self.low=22422.0, self.vol=19262.978, self.amt=433857299.3636, ukdf['pct'].iloc[-1]=-0.005658 , ukdf['amount'].iloc[-1]=433857299.3636, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230120   200000    235959  1674230399  ...    719  0.158853 -1.270892    -1.0
720  20230121   000000    035959  1674244799  ...    720  0.194292 -1.172561    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-17084.89558950806', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21501.55017902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--: 127.0.0.1 - - [21/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=340
self.closeSec=1674259199, self.tradeDate='20230121', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=21494.1, self.close=22664.4, self.high=22750.0, self.low=21493.8, self.vol=326184.044, self.amt=7247154972.96158 
2023-01-21 08:00:01,429:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674259199, self.tradeDate='20230121', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=21494.1, self.close=22664.4, self.high=22750.0, self.low=21493.8, self.vol=326184.044, self.amt=7247154972.96158 
2023-01-21 08:00:01,450:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230120   120000    155959  ...   54029.169  1.133558e+09 -0.006260
718  20230120   160000    195959  ...   33135.271  6.940604e+08  0.000162
719  20230120   200000    235959  ...  103649.390  2.187745e+09  0.008689
720  20230121   000000    035959  ...  157134.305  3.354302e+09  0.016713
721  20230121   040000    075959  ...  326184.044  7.247155e+09  0.054501

[5 rows x 11 columns]
2023-01-21 08:00:02,805:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230120   120000    155959  1674201599  ...    717  0.154954 -1.334303    -1.0
718  20230120   160000    195959  1674215999  ...    718  0.149571 -1.317577    -1.0
719  20230120   200000    235959  1674230399  ...    719  0.158853 -1.270892    -1.0
720  20230121   000000    035959  1674244799  ...    720  0.194292 -1.172561    -1.0
721  20230121   040000    075959  1674259199  ...    721  0.730974  0.021872     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-76492.40193196704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22665.19396768', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


