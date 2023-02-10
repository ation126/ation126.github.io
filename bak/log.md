# 20230210 08:36:00

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [10/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21534
self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21830.4, self.close=21834.0, self.high=21853.0, self.low=21822.5, self.vol=1006.638, self.amt=21985719.1172 
2023-02-10 08:30:00,575:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230210   080500    080959  ...         0.0        0.0       0
5858  20230210   081000    081459  ...         0.0        0.0       0
5859  20230210   081500    081959  ...         0.0        0.0       0
5860  20230210   082000    082459  ...         0.0        0.0       0
5861  20230210   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 08:30:00,575:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21830.4, self.close=21834.0, self.high=21853.0, self.low=21822.5, self.vol=1006.638, self.amt=21985719.1172, ukdf['pct'].iloc[-1]=0.000165 , ukdf['amount'].iloc[-1]=21985719.1172, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-319355.44740390832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21836.32352107', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21535
self.closeSec=1675989299, self.tradeDate='20230210', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21834.0, self.close=21826.5, self.high=21839.6, self.low=21800.0, self.vol=1305.49, self.amt=28481299.8136 
127.0.0.1 - - [10/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-10 08:35:00,496:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230210   081000    081459  ...         0.0        0.0       0
5859  20230210   081500    081959  ...         0.0        0.0       0
5860  20230210   082000    082459  ...         0.0        0.0       0
5861  20230210   082500    082959  ...         0.0        0.0       0
5862  20230210   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 08:35:00,496:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675989299, self.tradeDate='20230210', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21834.0, self.close=21826.5, self.high=21839.6, self.low=21800.0, self.vol=1305.49, self.amt=28481299.8136, ukdf['pct'].iloc[-1]=-0.000344 , ukdf['amount'].iloc[-1]=28481299.8136, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-318842.73514585264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21827.80330939', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1541  20230210   082500    082959  1675988999  ...  21822.5  0.000165   1541    5

[5 rows x 11 columns]
2023-02-10 08:30:00,661:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-10 08:30:00,715:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230210   062500    062959  1675981799  ... -0.000817   1517    5  0.659510
214  20230210   065500    065959  1675983599  ...  0.001957   1523    5  0.666789
215  20230210   072500    072959  1675985399  ...  0.000073   1529    5  0.672218
216  20230210   075500    075959  1675987199  ...  0.000353   1535    5  0.678389
217  20230210   082500    082959  1675988999  ...  0.000165   1541    5  0.683395

[5 rows x 12 columns]
2023-02-10 08:30:00,754:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2100830, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230210, closeTime:082959, close:21834.0, total:909224.3076578999, factor:0.6833954375727981, factorCnt:0, side:buy 
127.0.0.1 - - [10/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6833954375727981, self.count=22101 

self.closeSec=1675989299, self.tradeDate='20230210', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21834.0, self.close=21826.5, self.high=21839.6, self.low=21800.0 
2023-02-10 08:35:00,419:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675989299, self.tradeDate='20230210', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21834.0, self.close=21826.5, self.high=21839.6, self.low=21800.0   
2023-02-10 08:35:00,460:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230210   081000    081459  1675988099  ...  21829.1  0.000385   1538    2
1539  20230210   081500    081959  1675988399  ...  21825.8 -0.000403   1539    3
1540  20230210   082000    082459  1675988699  ...  21813.9 -0.000554   1540    4
1541  20230210   082500    082959  1675988999  ...  21822.5  0.000165   1541    5
1542  20230210   083000    083459  1675989299  ...  21800.0 -0.000344   1542    0

[5 rows x 11 columns]
2023-02-10 08:35:00,460:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-10 08:30:33,798:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230210    055959  21860.8  ...  45.416667  0.323409  0.704900
5772  20230210    062959  21849.3  ...  45.833333  0.331364  0.714409
5773  20230210    065959  21879.1  ...  45.833333  0.315936  0.729248
5774  20230210    072959  21762.8  ...  45.833333  0.334360  0.739006
5775  20230210    075959  21828.4  ...  45.833333  0.329594  0.750265

[5 rows x 33 columns]
0.47689463955637706
acc is : 0.47689463955637706
2023-02-10 08:30:33,973:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.451592  0.548408       1  ...  1.031944  -1.0    0.0  0.927454
537     1  0.476290  0.523710       0  ...  1.037684  -1.0    0.0  0.922295
538     1  0.448253  0.551747       1  ...  1.034302  -1.0    0.0  0.925301
539     1  0.485434  0.514566       0  ...  1.036070  -1.0    0.0  0.923720
540     1  0.472123  0.527877       1  ...  1.034030  -1.0    0.0  0.925538

[5 rows x 10 columns]
2023-02-10 08:30:33,997:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.452248  0.547752       1  ...  1.031944  -1.0    0.0  0.929645
46     1  0.476427  0.523573       0  ...  1.037684  -1.0    0.0  0.922483
47     1  0.447872  0.552128       1  ...  1.034302  -1.0    0.0  0.924642
48     1  0.484986  0.515014       0  ...  1.036070  -1.0    0.0  0.923062
49     1  0.472123  0.527877       1  ...  1.034030  -1.0    0.0  0.925538

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '35122.428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21835.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230210   080000    080959  1675987799  21793.3  21842.9  0.002377
2023-02-10 08:10:01,528:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11049 

self.closeSec=1675988399, self.tradeDate='20230210', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21846.6', self.close='21842.5'
2023-02-10 08:20:00,513:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675988399, self.tradeDate='20230210', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21846.6', self.close='21842.5'
2023-02-10 08:20:00,596:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230210   073000    073959  1675985999  21828.4  21790.9 -0.001718
622  20230210   074000    074959  1675986599  21791.4  21824.4  0.001537
623  20230210   075000    075959  1675987199  21824.3  21791.1 -0.001526
624  20230210   080000    080959  1675987799  21793.3  21842.9  0.002377
625  20230210   081000    081959  1675988399  21846.6  21842.5 -0.000018
2023-02-10 08:20:00,596:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11050 

self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21842.5', self.close='21834'
2023-02-10 08:30:00,731:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21842.5', self.close='21834'
127.0.0.1 - - [10/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-10 08:30:00,764:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230210   074000    074959  1675986599  21791.4  21824.4  0.001537
623  20230210   075000    075959  1675987199  21824.3  21791.1 -0.001526
624  20230210   080000    080959  1675987799  21793.3  21842.9  0.002377
625  20230210   081000    081959  1675988399  21846.6  21842.5 -0.000018
626  20230210   082000    082959  1675988999  21842.5    21834 -0.000389
2023-02-10 08:30:00,764:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230210   080000    080959  1675987799  21793.3  21842.9
2023-02-10 08:10:01,535:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11050 

self.closeSec=1675988399, self.tradeDate='20230210', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21846.6', self.close='21842.5'
2023-02-10 08:20:00,558:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675988399, self.tradeDate='20230210', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21846.6', self.close='21842.5'
2023-02-10 08:20:00,603:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230210   073000    073959  1675985999  21828.4  21790.9
17470  20230210   074000    074959  1675986599  21791.4  21824.4
17471  20230210   075000    075959  1675987199  21824.3  21791.1
17472  20230210   080000    080959  1675987799  21793.3  21842.9
17473  20230210   081000    081959  1675988399  21846.6  21842.5
2023-02-10 08:20:00,603:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11051 

self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21842.5', self.close='21834'
2023-02-10 08:30:00,775:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21842.5', self.close='21834'
2023-02-10 08:30:00,788:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230210   074000    074959  1675986599  21791.4  21824.4
17471  20230210   075000    075959  1675987199  21824.3  21791.1
17472  20230210   080000    080959  1675987799  21793.3  21842.9
17473  20230210   081000    081959  1675988399  21846.6  21842.5
17474  20230210   082000    082959  1675988999  21842.5    21834
2023-02-10 08:30:00,788:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230210   080000    080959  1675987799  21793.3  21842.9
2023-02-10 08:10:01,525:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11050 

self.closeSec=1675988399, self.tradeDate='20230210', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21846.6', self.close='21842.5'
2023-02-10 08:20:00,554:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675988399, self.tradeDate='20230210', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21846.6', self.close='21842.5'
2023-02-10 08:20:00,607:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230210   073000    073959  1675985999  21828.4  21790.9
12142  20230210   074000    074959  1675986599  21791.4  21824.4
12143  20230210   075000    075959  1675987199  21824.3  21791.1
12144  20230210   080000    080959  1675987799  21793.3  21842.9
12145  20230210   081000    081959  1675988399  21846.6  21842.5
2023-02-10 08:20:00,607:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11051 

self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21842.5', self.close='21834'
2023-02-10 08:30:00,742:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21842.5', self.close='21834'
127.0.0.1 - - [10/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-10 08:30:00,768:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230210   074000    074959  1675986599  21791.4  21824.4
12143  20230210   075000    075959  1675987199  21824.3  21791.1
12144  20230210   080000    080959  1675987799  21793.3  21842.9
12145  20230210   081000    081959  1675988399  21846.6  21842.5
12146  20230210   082000    082959  1675988999  21842.5    21834
2023-02-10 08:30:00,768:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [10/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17532
self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21830.4, self.close=21834.0, self.high=21853.0, self.low=21822.5, self.vol=1006.638, self.amt=21985719.1172 
2023-02-10 08:30:00,695:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230210   080500    080959  ...         0.0        0.0       0
5858  20230210   081000    081459  ...         0.0        0.0       0
5859  20230210   081500    081959  ...         0.0        0.0       0
5860  20230210   082000    082459  ...         0.0        0.0       0
5861  20230210   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 08:30:00,695:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675988999, self.tradeDate='20230210', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21830.4, self.close=21834.0, self.high=21853.0, self.low=21822.5, self.vol=1006.638, self.amt=21985719.1172, ukdf['pct'].iloc[-1]=0.000165 , ukdf['amount'].iloc[-1]=21985719.1172, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [10/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17533
self.closeSec=1675989299, self.tradeDate='20230210', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21834.0, self.close=21826.5, self.high=21839.6, self.low=21800.0, self.vol=1305.49, self.amt=28481299.8136 
2023-02-10 08:35:00,505:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230210   081000    081459  ...         0.0        0.0       0
5859  20230210   081500    081959  ...         0.0        0.0       0
5860  20230210   082000    082459  ...         0.0        0.0       0
5861  20230210   082500    082959  ...         0.0        0.0       0
5862  20230210   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 08:35:00,505:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675989299, self.tradeDate='20230210', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21834.0, self.close=21826.5, self.high=21839.6, self.low=21800.0, self.vol=1305.49, self.amt=28481299.8136, ukdf['pct'].iloc[-1]=-0.000344 , ukdf['amount'].iloc[-1]=28481299.8136, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230209   200000    235959  1675958399  ...    719  0.282399 -0.875070    -1.0
720  20230210   000000    035959  1675972799  ...    720  0.222654 -1.148003    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.925', 'enterprice': '22855.7', 'countrevence': '0', 'unrealprofit': '32408.955', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22023.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=888768.4643774999, self.flagDict['side']='sell', self.tradeCount=17, self.count=460
self.closeSec=1675987199, self.tradeDate='20230210', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22027.3, self.close=21791.1, self.high=22074.5, self.low=21684.7, self.vol=165794.93, self.amt=3626204373.90706 
127.0.0.1 - - [10/Feb/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-02-10 08:00:00,972:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675987199, self.tradeDate='20230210', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22027.3, self.close=21791.1, self.high=22074.5, self.low=21684.7, self.vol=165794.93, self.amt=3626204373.90706 
2023-02-10 08:00:01,018:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230209   120000    155959  ...   83990.686  1.895751e+09  0.006979
718  20230209   160000    195959  ...   42168.627  9.572935e+08  0.000384
719  20230209   200000    235959  ...  112744.024  2.557579e+09 -0.003246
720  20230210   000000    035959  ...  212764.619  4.742705e+09 -0.025323
721  20230210   040000    075959  ...  165794.930  3.626204e+09 -0.010907

[5 rows x 11 columns]
2023-02-10 08:00:03,109:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230209   120000    155959  1675929599  ...    717  0.269893 -0.917045    -1.0
718  20230209   160000    195959  1675943999  ...    718  0.271249 -0.923900    -1.0
719  20230209   200000    235959  1675958399  ...    719  0.282399 -0.875070    -1.0
720  20230210   000000    035959  1675972799  ...    720  0.222654 -1.148003    -1.0
721  20230210   040000    075959  1675987199  ...    721  0.389329 -0.397613     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.925', 'enterprice': '22855.7', 'countrevence': '0', 'unrealprofit': '41318.8875', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21794.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


