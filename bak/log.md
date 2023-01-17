# 20230117 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14618
self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=21122.1, self.close=21203.2, self.high=21208.8, self.low=21120.3, self.vol=2203.385, self.amt=46646802.8306 
2023-01-17 08:10:01,495:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230117   074500    074959  ...         0.0        0.0       0
5854  20230117   075000    075459  ...         0.0        0.0       0
5855  20230117   075500    075959  ...         0.0        0.0       0
5856  20230117   080000    080459  ...         0.0        0.0       0
5857  20230117   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 08:10:01,498:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=21122.1, self.close=21203.2, self.high=21208.8, self.low=21120.3, self.vol=2203.385, self.amt=46646802.8306, ukdf['pct'].iloc[-1]=0.003764 , ukdf['amount'].iloc[-1]=46646802.8306, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-281346.77435970576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21204.69840401', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14619
self.closeSec=1673914499, self.tradeDate='20230117', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=21203.2, self.close=21272.3, self.high=21308.9, self.low=21202.5, self.vol=6198.872, self.amt=131780952.2991 
2023-01-17 08:15:00,808:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230117   075000    075459  ...         0.0        0.0       0
5855  20230117   075500    075959  ...         0.0        0.0       0
5856  20230117   080000    080459  ...         0.0        0.0       0
5857  20230117   080500    080959  ...         0.0        0.0       0
5858  20230117   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 08:15:00,809:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673914499, self.tradeDate='20230117', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=21203.2, self.close=21272.3, self.high=21308.9, self.low=21202.5, self.vol=6198.872, self.amt=131780952.2991, ukdf['pct'].iloc[-1]=0.003259 , ukdf['amount'].iloc[-1]=131780952.2991, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-285435.27178713456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21272.64073031', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=447, self.factor=0.4598870936434703, self.count=15184 

self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=21122.1, self.close=21203.2, self.high=21208.8, self.low=21120.3 
2023-01-17 08:10:01,406:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=21122.1, self.close=21203.2, self.high=21208.8, self.low=21120.3   
2023-01-17 08:10:01,446:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230117   074500    074959  1673912999  ...  21163.7 -0.000477   1533    3
1534  20230117   075000    075459  1673913299  ...  21163.3 -0.000123   1534    4
1535  20230117   075500    075959  1673913599  ...  21152.8  0.001091   1535    5
1536  20230117   080000    080459  1673913899  ...  21073.8 -0.003049   1536    0
1537  20230117   080500    080959  1673914199  ...  21120.3  0.003764   1537    1

[5 rows x 11 columns]
2023-01-17 08:10:01,446:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=447, self.factor=0.4598870936434703, self.count=15185 

self.closeSec=1673914499, self.tradeDate='20230117', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=21203.2, self.close=21272.3, self.high=21308.9, self.low=21202.5 
2023-01-17 08:15:00,649:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673914499, self.tradeDate='20230117', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=21203.2, self.close=21272.3, self.high=21308.9, self.low=21202.5   
127.0.0.1 - - [17/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-17 08:15:00,740:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230117   075000    075459  1673913299  ...  21163.3 -0.000123   1534    4
1535  20230117   075500    075959  1673913599  ...  21152.8  0.001091   1535    5
1536  20230117   080000    080459  1673913899  ...  21073.8 -0.003049   1536    0
1537  20230117   080500    080959  1673914199  ...  21120.3  0.003764   1537    1
1538  20230117   081000    081459  1673914499  ...  21202.5  0.003259   1538    2

[5 rows x 11 columns]
2023-01-17 08:15:00,740:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-17 08:00:34,133:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230117    052959  21294.8  ...  56.250000  0.554906  0.448883
5771  20230117    055959  21123.0  ...  56.250000  0.557261  0.445911
5772  20230117    062959  21137.6  ...  56.666667  0.567434  0.438381
5773  20230117    065959  21201.2  ...  56.250000  0.565641  0.431996
5774  20230117    072959  21192.6  ...  56.250000  0.569323  0.424332

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2023-01-17 08:00:34,320:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.457831  0.542169       1  ...  1.049894   1.0    0.0  1.256844
537     1  0.491737  0.508263       1  ...  1.053053   1.0    0.0  1.260626
538     0  0.506494  0.493506       0  ...  1.052625   1.0    0.0  1.260114
539     1  0.489442  0.510558       1  ...  1.053758   1.0    0.0  1.261470
540     0  0.504735  0.495265       0  ...  1.052412   1.0    0.0  1.259858

[5 rows x 10 columns]
2023-01-17 08:00:34,353:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.458379  0.541621       1  ...  1.049894   1.0    0.0  1.255455
46     1  0.492003  0.507997       1  ...  1.053053   1.0    0.0  1.259876
47     0  0.506521  0.493479       0  ...  1.052625   1.0    0.0  1.258991
48     1  0.489662  0.510338       1  ...  1.053758   1.0    0.0  1.261470
49     0  0.504735  0.495265       0  ...  1.052412   1.0    0.0  1.259858

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230117   074000    074959  1673912999  21197.1  21167.8 -0.001387
2023-01-17 07:50:00,616:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7591 

self.closeSec=1673913599, self.tradeDate='20230117', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='21167.8', self.close='21188.3'
2023-01-17 08:00:01,409:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673913599, self.tradeDate='20230117', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='21167.8', self.close='21188.3'
127.0.0.1 - - [17/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-17 08:00:01,444:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230117   071000    071959  1673911199    21136  21195.6  0.002706
620  20230117   072000    072959  1673911799  21195.5  21215.4  0.000934
621  20230117   073000    073959  1673912399  21215.4  21197.2 -0.000858
622  20230117   074000    074959  1673912999  21197.1  21167.8 -0.001387
623  20230117   075000    075959  1673913599  21167.8  21188.3  0.000968
2023-01-17 08:00:01,447:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7592 

self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21188.2', self.close='21203.2'
2023-01-17 08:10:01,563:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21188.2', self.close='21203.2'
2023-01-17 08:10:01,583:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230117   072000    072959  1673911799  21195.5  21215.4  0.000934
621  20230117   073000    073959  1673912399  21215.4  21197.2 -0.000858
622  20230117   074000    074959  1673912999  21197.1  21167.8 -0.001387
623  20230117   075000    075959  1673913599  21167.8  21188.3  0.000968
624  20230117   080000    080959  1673914199  21188.2  21203.2  0.000703
2023-01-17 08:10:01,586:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230117   074000    074959  1673912999  21197.1  21167.8
2023-01-17 07:50:00,639:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7592 

self.closeSec=1673913599, self.tradeDate='20230117', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='21167.8', self.close='21188.3'
127.0.0.1 - - [17/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-17 08:00:01,422:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673913599, self.tradeDate='20230117', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='21167.8', self.close='21188.3'
2023-01-17 08:00:01,457:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230117   071000    071959  1673911199    21136  21195.6
17468  20230117   072000    072959  1673911799  21195.5  21215.4
17469  20230117   073000    073959  1673912399  21215.4  21197.2
17470  20230117   074000    074959  1673912999  21197.1  21167.8
17471  20230117   075000    075959  1673913599  21167.8  21188.3
2023-01-17 08:00:01,457:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7593 

self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21188.2', self.close='21203.2'
2023-01-17 08:10:01,554:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21188.2', self.close='21203.2'
2023-01-17 08:10:01,572:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230117   072000    072959  1673911799  21195.5  21215.4
17469  20230117   073000    073959  1673912399  21215.4  21197.2
17470  20230117   074000    074959  1673912999  21197.1  21167.8
17471  20230117   075000    075959  1673913599  21167.8  21188.3
17472  20230117   080000    080959  1673914199  21188.2  21203.2
2023-01-17 08:10:01,572:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230117   074000    074959  1673912999  21197.1  21167.8
2023-01-17 07:50:00,633:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7592 

self.closeSec=1673913599, self.tradeDate='20230117', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='21167.8', self.close='21188.3'
2023-01-17 08:00:01,415:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673913599, self.tradeDate='20230117', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='21167.8', self.close='21188.3'
127.0.0.1 - - [17/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-17 08:00:01,451:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230117   071000    071959  1673911199    21136  21195.6
12140  20230117   072000    072959  1673911799  21195.5  21215.4
12141  20230117   073000    073959  1673912399  21215.4  21197.2
12142  20230117   074000    074959  1673912999  21197.1  21167.8
12143  20230117   075000    075959  1673913599  21167.8  21188.3
2023-01-17 08:00:01,451:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7593 

self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21188.2', self.close='21203.2'
2023-01-17 08:10:01,536:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21188.2', self.close='21203.2'
127.0.0.1 - - [17/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-17 08:10:01,563:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230117   072000    072959  1673911799  21195.5  21215.4
12141  20230117   073000    073959  1673912399  21215.4  21197.2
12142  20230117   074000    074959  1673912999  21197.1  21167.8
12143  20230117   075000    075959  1673913599  21167.8  21188.3
12144  20230117   080000    080959  1673914199  21188.2  21203.2
2023-01-17 08:10:01,563:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10616
self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=21122.1, self.close=21203.2, self.high=21208.8, self.low=21120.3, self.vol=2203.385, self.amt=46646802.8306 
127.0.0.1 - - [17/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-17 08:10:01,493:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230117   074500    074959  ...         0.0        0.0       0
5854  20230117   075000    075459  ...         0.0        0.0       0
5855  20230117   075500    075959  ...         0.0        0.0       0
5856  20230117   080000    080459  ...         0.0        0.0       0
5857  20230117   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 08:10:01,493:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673914199, self.tradeDate='20230117', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=21122.1, self.close=21203.2, self.high=21208.8, self.low=21120.3, self.vol=2203.385, self.amt=46646802.8306, ukdf['pct'].iloc[-1]=0.003764 , ukdf['amount'].iloc[-1]=46646802.8306, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [17/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10617
self.closeSec=1673914499, self.tradeDate='20230117', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=21203.2, self.close=21272.3, self.high=21308.9, self.low=21202.5, self.vol=6198.872, self.amt=131780952.2991 
2023-01-17 08:15:00,793:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230117   075000    075459  ...         0.0        0.0       0
5855  20230117   075500    075959  ...         0.0        0.0       0
5856  20230117   080000    080459  ...         0.0        0.0       0
5857  20230117   080500    080959  ...         0.0        0.0       0
5858  20230117   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 08:15:00,799:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673914499, self.tradeDate='20230117', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=21203.2, self.close=21272.3, self.high=21308.9, self.low=21202.5, self.vol=6198.872, self.amt=131780952.2991, ukdf['pct'].iloc[-1]=0.003259 , ukdf['amount'].iloc[-1]=131780952.2991, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230116   200000    235959  1673884799  ...    719  0.815950  0.078361     NaN
720  20230117   000000    035959  1673899199  ...    720  0.793669  0.003926     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '210997.3632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21314.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [17/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=316
self.closeSec=1673913599, self.tradeDate='20230117', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=21314.5, self.close=21188.3, self.high=21498.0, self.low=21056.0, self.vol=85257.322, self.amt=1810115824.70967 
2023-01-17 08:00:01,253:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673913599, self.tradeDate='20230117', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=21314.5, self.close=21188.3, self.high=21498.0, self.low=21056.0, self.vol=85257.322, self.amt=1810115824.70967 
2023-01-17 08:00:01,274:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230116   120000    155959  ...   55958.606  1.183353e+09  0.001503
718  20230116   160000    195959  ...  101732.641  2.117565e+09 -0.013937
719  20230116   200000    235959  ...  114395.111  2.386427e+09  0.008592
720  20230117   000000    035959  ...  133530.799  2.828000e+09  0.014942
721  20230117   040000    075959  ...   85257.322  1.810116e+09 -0.005916

[5 rows x 11 columns]
2023-01-17 08:00:03,124:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230116   120000    155959  1673855999  ...    717  0.902588  0.320094     NaN
718  20230116   160000    195959  1673870399  ...    718  0.867218  0.219553     NaN
719  20230116   200000    235959  1673884799  ...    719  0.815950  0.078361     NaN
720  20230117   000000    035959  1673899199  ...    720  0.793669  0.003926     NaN
721  20230117   040000    075959  1673913599  ...    721  0.897750  0.242217     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '204513.82274004992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21187.60986272', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


