# 20221227 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [27/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8570
self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16941.0, self.close=16950.2, self.high=16958.5, self.low=16940.1, self.vol=1745.503, self.amt=29587497.5206 
2022-12-27 08:10:01,473:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221227   074500    074959  ...         0.0        0.0       0
5854  20221227   075000    075459  ...         0.0        0.0       0
5855  20221227   075500    075959  ...         0.0        0.0       0
5856  20221227   080000    080459  ...         0.0        0.0       0
5857  20221227   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-27 08:10:01,473:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16941.0, self.close=16950.2, self.high=16958.5, self.low=16940.1, self.vol=1745.503, self.amt=29587497.5206, ukdf['pct'].iloc[-1]=0.000543 , ukdf['amount'].iloc[-1]=29587497.5206, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-25322.0608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16950.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8571
self.closeSec=1672100099, self.tradeDate='20221227', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16950.1, self.close=16951.0, self.high=16959.7, self.low=16948.1, self.vol=1396.656, self.amt=23677767.2277 
127.0.0.1 - - [27/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-27 08:15:00,556:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221227   075000    075459  ...         0.0        0.0       0
5855  20221227   075500    075959  ...         0.0        0.0       0
5856  20221227   080000    080459  ...         0.0        0.0       0
5857  20221227   080500    080959  ...         0.0        0.0       0
5858  20221227   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-27 08:15:00,557:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672100099, self.tradeDate='20221227', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16950.1, self.close=16951.0, self.high=16959.7, self.low=16948.1, self.vol=1396.656, self.amt=23677767.2277, ukdf['pct'].iloc[-1]=4.7e-05 , ukdf['amount'].iloc[-1]=23677767.2277, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-25545.04542498608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16953.80554083', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=278, self.factor=0.45565935814536196, self.count=9136 

self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16941.0, self.close=16950.2, self.high=16958.5, self.low=16940.1 
2022-12-27 08:10:01,432:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16941.0, self.close=16950.2, self.high=16958.5, self.low=16940.1   
2022-12-27 08:10:01,462:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221227   074500    074959  1672098599  ...  16869.2  0.000865   1533    3
1534  20221227   075000    075459  1672098899  ...  16883.8  0.002334   1534    4
1535  20221227   075500    075959  1672099199  ...  16911.0 -0.000609   1535    5
1536  20221227   080000    080459  1672099499  ...  16912.8  0.001661   1536    0
1537  20221227   080500    080959  1672099799  ...  16940.1  0.000543   1537    1

[5 rows x 11 columns]
2022-12-27 08:10:01,463:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=278, self.factor=0.45565935814536196, self.count=9137 

self.closeSec=1672100099, self.tradeDate='20221227', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16950.1, self.close=16951.0, self.high=16959.7, self.low=16948.1 
2022-12-27 08:15:00,539:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672100099, self.tradeDate='20221227', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16950.1, self.close=16951.0, self.high=16959.7, self.low=16948.1   
127.0.0.1 - - [27/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-27 08:15:00,577:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221227   075000    075459  1672098899  ...  16883.8  0.002334   1534    4
1535  20221227   075500    075959  1672099199  ...  16911.0 -0.000609   1535    5
1536  20221227   080000    080459  1672099499  ...  16912.8  0.001661   1536    0
1537  20221227   080500    080959  1672099799  ...  16940.1  0.000543   1537    1
1538  20221227   081000    081459  1672100099  ...  16948.1  0.000047   1538    2

[5 rows x 11 columns]
2022-12-27 08:15:00,577:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-27 08:00:18,720:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221227    052959  16834.3  ...  48.333333  0.513988  0.523138
5771  20221227    055959  16839.0  ...  47.916667  0.500042  0.533251
5772  20221227    062959  16826.2  ...  48.333333  0.505770  0.540095
5773  20221227    065959  16831.6  ...  48.333333  0.505661  0.546530
5774  20221227    072959  16831.5  ...  48.333333  0.528667  0.541914

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2022-12-27 08:00:18,832:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.501021  0.498979       0  ...  1.033115   1.0    0.0  0.966368
537     1  0.493406  0.506594       1  ...  1.033447   1.0    0.0  0.966678
538     1  0.497914  0.502086       0  ...  1.033440   1.0    0.0  0.966672
539     1  0.496855  0.503145       1  ...  1.034797   1.0    0.0  0.967941
540     0  0.503835  0.496165       1  ...  1.038328   1.0    0.0  0.971244

[5 rows x 10 columns]
2022-12-27 08:00:18,859:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500757  0.499243       0  ...  1.033115   1.0    0.0  0.965913
46     1  0.493332  0.506668       1  ...  1.033447   1.0    0.0  0.967067
47     1  0.498143  0.501857       0  ...  1.033440   1.0    0.0  0.967789
48     1  0.496855  0.503145       1  ...  1.034797   1.0    0.0  0.967941
49     0  0.503835  0.496165       1  ...  1.038328   1.0    0.0  0.971244

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '9794.1984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16931.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221227   074000    074959  1672098599  16864.8  16883.8  0.001127
2022-12-27 07:50:00,822:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4567 

self.closeSec=1672099199, self.tradeDate='20221227', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16883.9', self.close='16912.9'
127.0.0.1 - - [27/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-27 08:00:01,160:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672099199, self.tradeDate='20221227', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16883.9', self.close='16912.9'
2022-12-27 08:00:01,201:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221227   071000    071959  1672096799  16831.6    16848  0.000968
620  20221227   072000    072959  1672097399  16848.1  16853.6  0.000332
621  20221227   073000    073959  1672097999  16853.7  16864.8  0.000665
622  20221227   074000    074959  1672098599  16864.8  16883.8  0.001127
623  20221227   075000    075959  1672099199  16883.9  16912.9  0.001724
2022-12-27 08:00:01,201:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4568 

self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16912.8', self.close='16950.2'
2022-12-27 08:10:01,534:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16912.8', self.close='16950.2'
2022-12-27 08:10:01,560:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221227   072000    072959  1672097399  16848.1  16853.6  0.000332
621  20221227   073000    073959  1672097999  16853.7  16864.8  0.000665
622  20221227   074000    074959  1672098599  16864.8  16883.8  0.001127
623  20221227   075000    075959  1672099199  16883.9  16912.9  0.001724
624  20221227   080000    080959  1672099799  16912.8  16950.2  0.002205
2022-12-27 08:10:01,560:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221227   074000    074959  1672098599  16864.8  16883.8
2022-12-27 07:50:00,825:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4568 

self.closeSec=1672099199, self.tradeDate='20221227', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16883.9', self.close='16912.9'
127.0.0.1 - - [27/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-27 08:00:01,187:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672099199, self.tradeDate='20221227', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16883.9', self.close='16912.9'
2022-12-27 08:00:01,236:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221227   071000    071959  1672096799  16831.6    16848
17468  20221227   072000    072959  1672097399  16848.1  16853.6
17469  20221227   073000    073959  1672097999  16853.7  16864.8
17470  20221227   074000    074959  1672098599  16864.8  16883.8
17471  20221227   075000    075959  1672099199  16883.9  16912.9
2022-12-27 08:00:01,237:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4569 

self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16912.8', self.close='16950.2'
2022-12-27 08:10:01,545:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16912.8', self.close='16950.2'
2022-12-27 08:10:01,564:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221227   072000    072959  1672097399  16848.1  16853.6
17469  20221227   073000    073959  1672097999  16853.7  16864.8
17470  20221227   074000    074959  1672098599  16864.8  16883.8
17471  20221227   075000    075959  1672099199  16883.9  16912.9
17472  20221227   080000    080959  1672099799  16912.8  16950.2
2022-12-27 08:10:01,564:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221227   074000    074959  1672098599  16864.8  16883.8
2022-12-27 07:50:00,835:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4568 

self.closeSec=1672099199, self.tradeDate='20221227', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16883.9', self.close='16912.9'
127.0.0.1 - - [27/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-27 08:00:01,172:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672099199, self.tradeDate='20221227', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16883.9', self.close='16912.9'
2022-12-27 08:00:01,215:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221227   071000    071959  1672096799  16831.6    16848
12140  20221227   072000    072959  1672097399  16848.1  16853.6
12141  20221227   073000    073959  1672097999  16853.7  16864.8
12142  20221227   074000    074959  1672098599  16864.8  16883.8
12143  20221227   075000    075959  1672099199  16883.9  16912.9
2022-12-27 08:00:01,216:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4569 

self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16912.8', self.close='16950.2'
2022-12-27 08:10:01,549:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16912.8', self.close='16950.2'
2022-12-27 08:10:01,569:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221227   072000    072959  1672097399  16848.1  16853.6
12141  20221227   073000    073959  1672097999  16853.7  16864.8
12142  20221227   074000    074959  1672098599  16864.8  16883.8
12143  20221227   075000    075959  1672099199  16883.9  16912.9
12144  20221227   080000    080959  1672099799  16912.8  16950.2
2022-12-27 08:10:01,569:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [27/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4568
self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16941.0, self.close=16950.2, self.high=16958.5, self.low=16940.1, self.vol=1745.503, self.amt=29587497.5206 
2022-12-27 08:10:01,519:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221227   074500    074959  ...         0.0        0.0       0
5854  20221227   075000    075459  ...         0.0        0.0       0
5855  20221227   075500    075959  ...         0.0        0.0       0
5856  20221227   080000    080459  ...         0.0        0.0       0
5857  20221227   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-27 08:10:01,519:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672099799, self.tradeDate='20221227', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16941.0, self.close=16950.2, self.high=16958.5, self.low=16940.1, self.vol=1745.503, self.amt=29587497.5206, ukdf['pct'].iloc[-1]=0.000543 , ukdf['amount'].iloc[-1]=29587497.5206, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4569
self.closeSec=1672100099, self.tradeDate='20221227', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16950.1, self.close=16951.0, self.high=16959.7, self.low=16948.1, self.vol=1396.656, self.amt=23677767.2277 
127.0.0.1 - - [27/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-27 08:15:00,581:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221227   075000    075459  ...         0.0        0.0       0
5855  20221227   075500    075959  ...         0.0        0.0       0
5856  20221227   080000    080459  ...         0.0        0.0       0
5857  20221227   080500    080959  ...         0.0        0.0       0
5858  20221227   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-27 08:15:00,582:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672100099, self.tradeDate='20221227', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16950.1, self.close=16951.0, self.high=16959.7, self.low=16948.1, self.vol=1396.656, self.amt=23677767.2277, ukdf['pct'].iloc[-1]=4.7e-05 , ukdf['amount'].iloc[-1]=23677767.2277, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221226   200000    235959  1672070399  ...    719  0.023196 -1.002639    -1.0
720  20221227   000000    035959  1672084799  ...    720  0.039913 -0.948991    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5972.3268', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16835', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=190
self.closeSec=1672099199, self.tradeDate='20221227', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16834.9, self.close=16911.1, self.high=16936.8, self.low=16810.2, self.vol=26899.477, self.amt=453743054.4928 
2022-12-27 08:00:01,064:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672099199, self.tradeDate='20221227', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16834.9, self.close=16911.1, self.high=16936.8, self.low=16810.2, self.vol=26899.477, self.amt=453743054.4928 
127.0.0.1 - - [27/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-27 08:00:01,090:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221226   120000    155959  ...  24738.987  4.172029e+08 -0.002990
718  20221226   160000    195959  ...  20279.232  3.414780e+08  0.001033
719  20221226   200000    235959  ...  26504.163  4.458605e+08 -0.003133
720  20221227   000000    035959  ...  21061.266  3.543693e+08  0.002006
721  20221227   040000    075959  ...  26899.477  4.537431e+08  0.004526

[5 rows x 11 columns]
2022-12-27 08:00:02,597:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime  ...          beta    zscore  signal
717  20221226   120000    155959  ...  2.306278e-02 -1.041725    -1.0
718  20221226   160000    195959  ...  2.330184e-02 -1.021403    -1.0
719  20221226   200000    235959  ...  2.319617e-02 -1.002639    -1.0
720  20221227   000000    035959  ...  3.991269e-02 -0.948991    -1.0
721  20221227   040000    075959  ...  5.692034e-09 -1.016754    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-10192.84993820324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16914.07747767', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


