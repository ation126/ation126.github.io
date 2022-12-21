# 20221221 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6842
self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16899.3, self.close=16907.6, self.high=16918.2, self.low=16899.3, self.vol=937.533, self.amt=15853030.0216 
127.0.0.1 - - [21/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-21 08:10:01,504:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221221   074500    074959  ...         0.0        0.0       0
5854  20221221   075000    075459  ...         0.0        0.0       0
5855  20221221   075500    075959  ...         0.0        0.0       0
5856  20221221   080000    080459  ...         0.0        0.0       0
5857  20221221   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 08:10:01,504:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16899.3, self.close=16907.6, self.high=16918.2, self.low=16899.3, self.vol=937.533, self.amt=15853030.0216, ukdf['pct'].iloc[-1]=0.000485 , ukdf['amount'].iloc[-1]=15853030.0216, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-22924.24040648144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16910.25321069', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6843
self.closeSec=1671581699, self.tradeDate='20221221', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16908.5, self.close=16863.5, self.high=16909.1, self.low=16850.4, self.vol=1969.715, self.amt=33238345.507 
2022-12-21 08:15:00,813:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221221   075000    075459  ...         0.0        0.0       0
5855  20221221   075500    075959  ...         0.0        0.0       0
5856  20221221   080000    080459  ...         0.0        0.0       0
5857  20221221   080500    080959  ...         0.0        0.0       0
5858  20221221   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 08:15:00,818:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671581699, self.tradeDate='20221221', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16908.5, self.close=16863.5, self.high=16909.1, self.low=16850.4, self.vol=1969.715, self.amt=33238345.507, ukdf['pct'].iloc[-1]=-0.002608 , ukdf['amount'].iloc[-1]=33238345.507, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-20189.8617119072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16864.8135222', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16899.3, self.close=16907.6, self.high=16918.2, self.low=16899.3 
2022-12-21 08:10:01,443:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16899.3, self.close=16907.6, self.high=16918.2, self.low=16899.3   
127.0.0.1 - - [21/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-21 08:10:01,482:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221221   074500    074959  1671580199  ...  16885.0 -0.000130   1533    3
1534  20221221   075000    075459  1671580499  ...  16882.4  0.000663   1534    4
1535  20221221   075500    075959  1671580799  ...  16887.2 -0.000681   1535    5
1536  20221221   080000    080459  1671581099  ...  16881.1  0.000722   1536    0
1537  20221221   080500    080959  1671581399  ...  16899.3  0.000485   1537    1

[5 rows x 11 columns]
2022-12-21 08:10:01,485:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [21/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.3435315893412101, self.count=7409 

self.closeSec=1671581699, self.tradeDate='20221221', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16908.5, self.close=16863.5, self.high=16909.1, self.low=16850.4 
2022-12-21 08:15:00,780:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671581699, self.tradeDate='20221221', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16908.5, self.close=16863.5, self.high=16909.1, self.low=16850.4   
2022-12-21 08:15:00,804:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221221   075000    075459  1671580499  ...  16882.4  0.000663   1534    4
1535  20221221   075500    075959  1671580799  ...  16887.2 -0.000681   1535    5
1536  20221221   080000    080459  1671581099  ...  16881.1  0.000722   1536    0
1537  20221221   080500    080959  1671581399  ...  16899.3  0.000485   1537    1
1538  20221221   081000    081459  1671581699  ...  16850.4 -0.002608   1538    2

[5 rows x 11 columns]
2022-12-21 08:15:00,805:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-21 08:00:19,953:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221221    052959  16851.3  ...  49.166667  0.534085  0.251359
5771  20221221    055959  16847.7  ...  49.583333  0.541618  0.258204
5772  20221221    062959  16870.1  ...  50.000000  0.542532  0.265575
5773  20221221    065959  16872.6  ...  50.000000  0.538273  0.280362
5774  20221221    072959  16862.2  ...  50.000000  0.553333  0.286500

[5 rows x 33 columns]
0.5508317929759704
acc is : 0.5508317929759704
2022-12-21 08:00:20,075:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.497252  0.502748       1  ...  1.102496   1.0    0.0  0.983914
537     0  0.500068  0.499932       1  ...  1.102673   1.0    0.0  0.984072
538     1  0.494071  0.505929       0  ...  1.101986   1.0    0.0  0.983460
539     1  0.487874  0.512126       1  ...  1.104875   1.0    0.0  0.986037
540     0  0.510923  0.489077       0  ...  1.103620   1.0    0.0  0.984918

[5 rows x 10 columns]
2022-12-21 08:00:20,101:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496930  0.503070       1  ...  1.102496   1.0    0.0  0.982505
46     1  0.499295  0.500705       1  ...  1.102673   1.0    0.0  0.982399
47     1  0.493657  0.506343       0  ...  1.101986   1.0    0.0  0.983305
48     1  0.487814  0.512186       1  ...  1.104875   1.0    0.0  0.986037
49     0  0.510923  0.489077       0  ...  1.103620   1.0    0.0  0.984918

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '8108.80849716', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16892.16987625', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221221   074000    074959  1671580199  16892.5  16887.5 -0.000302
2022-12-21 07:50:00,583:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3703 

self.closeSec=1671580799, self.tradeDate='20221221', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16887.4', self.close='16887.2'
2022-12-21 08:00:01,290:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671580799, self.tradeDate='20221221', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16887.4', self.close='16887.2'
2022-12-21 08:00:01,365:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221221   071000    071959  1671578399  16885.5    16891  0.000320
620  20221221   072000    072959  1671578999    16891  16906.4  0.000912
621  20221221   073000    073959  1671579599  16906.3  16892.6 -0.000816
622  20221221   074000    074959  1671580199  16892.5  16887.5 -0.000302
623  20221221   075000    075959  1671580799  16887.4  16887.2 -0.000018
2022-12-21 08:00:01,365:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3704 

self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16887.3', self.close='16907.6'
2022-12-21 08:10:01,564:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16887.3', self.close='16907.6'
2022-12-21 08:10:01,582:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221221   072000    072959  1671578999    16891  16906.4  0.000912
621  20221221   073000    073959  1671579599  16906.3  16892.6 -0.000816
622  20221221   074000    074959  1671580199  16892.5  16887.5 -0.000302
623  20221221   075000    075959  1671580799  16887.4  16887.2 -0.000018
624  20221221   080000    080959  1671581399  16887.3  16907.6  0.001208
2022-12-21 08:10:01,583:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221221   074000    074959  1671580199  16892.5  16887.5
2022-12-21 07:50:00,593:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3704 

self.closeSec=1671580799, self.tradeDate='20221221', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16887.4', self.close='16887.2'
2022-12-21 08:00:01,334:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671580799, self.tradeDate='20221221', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16887.4', self.close='16887.2'
2022-12-21 08:00:01,402:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221221   071000    071959  1671578399  16885.5    16891
17468  20221221   072000    072959  1671578999    16891  16906.4
17469  20221221   073000    073959  1671579599  16906.3  16892.6
17470  20221221   074000    074959  1671580199  16892.5  16887.5
17471  20221221   075000    075959  1671580799  16887.4  16887.2
2022-12-21 08:00:01,402:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3705 

self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16887.3', self.close='16907.6'
2022-12-21 08:10:01,570:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16887.3', self.close='16907.6'
2022-12-21 08:10:01,585:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221221   072000    072959  1671578999    16891  16906.4
17469  20221221   073000    073959  1671579599  16906.3  16892.6
17470  20221221   074000    074959  1671580199  16892.5  16887.5
17471  20221221   075000    075959  1671580799  16887.4  16887.2
17472  20221221   080000    080959  1671581399  16887.3  16907.6
2022-12-21 08:10:01,585:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221221   074000    074959  1671580199  16892.5  16887.5
2022-12-21 07:50:00,587:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3704 

self.closeSec=1671580799, self.tradeDate='20221221', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16887.4', self.close='16887.2'
2022-12-21 08:00:01,320:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671580799, self.tradeDate='20221221', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16887.4', self.close='16887.2'
2022-12-21 08:00:01,364:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221221   071000    071959  1671578399  16885.5    16891
12140  20221221   072000    072959  1671578999    16891  16906.4
12141  20221221   073000    073959  1671579599  16906.3  16892.6
12142  20221221   074000    074959  1671580199  16892.5  16887.5
12143  20221221   075000    075959  1671580799  16887.4  16887.2
2022-12-21 08:00:01,370:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3705 

self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16887.3', self.close='16907.6'
2022-12-21 08:10:01,557:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16887.3', self.close='16907.6'
2022-12-21 08:10:01,583:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221221   072000    072959  1671578999    16891  16906.4
12141  20221221   073000    073959  1671579599  16906.3  16892.6
12142  20221221   074000    074959  1671580199  16892.5  16887.5
12143  20221221   075000    075959  1671580799  16887.4  16887.2
12144  20221221   080000    080959  1671581399  16887.3  16907.6
2022-12-21 08:10:01,584:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [21/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2840
self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16899.3, self.close=16907.6, self.high=16918.2, self.low=16899.3, self.vol=937.533, self.amt=15853030.0216 
2022-12-21 08:10:01,514:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221221   074500    074959  ...         0.0        0.0       0
5854  20221221   075000    075459  ...         0.0        0.0       0
5855  20221221   075500    075959  ...         0.0        0.0       0
5856  20221221   080000    080459  ...         0.0        0.0       0
5857  20221221   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 08:10:01,514:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671581399, self.tradeDate='20221221', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16899.3, self.close=16907.6, self.high=16918.2, self.low=16899.3, self.vol=937.533, self.amt=15853030.0216, ukdf['pct'].iloc[-1]=0.000485 , ukdf['amount'].iloc[-1]=15853030.0216, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2841
self.closeSec=1671581699, self.tradeDate='20221221', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16908.5, self.close=16863.5, self.high=16909.1, self.low=16850.4, self.vol=1969.715, self.amt=33238345.507 
127.0.0.1 - - [21/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-21 08:15:00,823:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221221   075000    075459  ...         0.0        0.0       0
5855  20221221   075500    075959  ...         0.0        0.0       0
5856  20221221   080000    080459  ...         0.0        0.0       0
5857  20221221   080500    080959  ...         0.0        0.0       0
5858  20221221   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-21 08:15:00,825:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671581699, self.tradeDate='20221221', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16908.5, self.close=16863.5, self.high=16909.1, self.low=16850.4, self.vol=1969.715, self.amt=33238345.507, ukdf['pct'].iloc[-1]=-0.002608 , ukdf['amount'].iloc[-1]=33238345.507, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221220   200000    235959  1671551999  ...    719  0.026394 -2.594419    -1.0
720  20221221   000000    035959  1671566399  ...    720  0.008696 -2.530130    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-9158.6352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16894.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [21/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=154
self.closeSec=1671580799, self.tradeDate='20221221', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16894.6, self.close=16887.2, self.high=16918.7, self.low=16825.2, self.vol=35569.835, self.amt=600276000.1091 
2022-12-21 08:00:01,115:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671580799, self.tradeDate='20221221', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16894.6, self.close=16887.2, self.high=16918.7, self.low=16825.2, self.vol=35569.835, self.amt=600276000.1091 
2022-12-21 08:00:01,165:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20221220   120000    155959  ...   69915.337  1.173493e+09  0.004672
718  20221220   160000    195959  ...   47552.517  7.989043e+08  0.000536
719  20221220   200000    235959  ...  131483.196  2.220090e+09  0.006296
720  20221221   000000    035959  ...   81655.657  1.374707e+09 -0.000958
721  20221221   040000    075959  ...   35569.835  6.002760e+08 -0.000444

[5 rows x 11 columns]
2022-12-21 08:00:02,736:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221220   120000    155959  1671523199  ...    717  0.424051 -1.325928    -1.0
718  20221220   160000    195959  1671537599  ...    718  0.159883 -2.232762    -1.0
719  20221220   200000    235959  1671551999  ...    719  0.026394 -2.594419    -1.0
720  20221221   000000    035959  1671566399  ...    720  0.008696 -2.530130    -1.0
721  20221221   040000    075959  1671580799  ...    721  0.011155 -2.410683    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-8918.63644215852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16890.20328341', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


