# 20221214 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [14/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4826
self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17786.4, self.close=17788.0, self.high=17795.4, self.low=17777.6, self.vol=483.072, self.amt=8592180.2153 
2022-12-14 08:10:01,478:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221214   074500    074959  ...         0.0        0.0       0
5854  20221214   075000    075459  ...         0.0        0.0       0
5855  20221214   075500    075959  ...         0.0        0.0       0
5856  20221214   080000    080459  ...         0.0        0.0       0
5857  20221214   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-14 08:10:01,478:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17786.4, self.close=17788.0, self.high=17795.4, self.low=17777.6, self.vol=483.072, self.amt=8592180.2153, ukdf['pct'].iloc[-1]=9e-05 , ukdf['amount'].iloc[-1]=8592180.2153, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-75767.21294367584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17788.39354134', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4827
self.closeSec=1670976899, self.tradeDate='20221214', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17788.1, self.close=17779.8, self.high=17789.1, self.low=17769.4, self.vol=871.81, self.amt=15498321.6154 
127.0.0.1 - - [14/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-14 08:15:00,624:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221214   075000    075459  ...         0.0        0.0       0
5855  20221214   075500    075959  ...         0.0        0.0       0
5856  20221214   080000    080459  ...         0.0        0.0       0
5857  20221214   080500    080959  ...         0.0        0.0       0
5858  20221214   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-14 08:15:00,625:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670976899, self.tradeDate='20221214', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17788.1, self.close=17779.8, self.high=17789.1, self.low=17769.4, self.vol=871.81, self.amt=15498321.6154, ukdf['pct'].iloc[-1]=-0.000461 , ukdf['amount'].iloc[-1]=15498321.6154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-75261.50007511296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17779.98964496', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17786.4, self.close=17788.0, self.high=17795.4, self.low=17777.6 
2022-12-14 08:10:01,428:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17786.4, self.close=17788.0, self.high=17795.4, self.low=17777.6   
127.0.0.1 - - [14/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-14 08:10:01,440:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221214   074500    074959  1670975399  ...  17773.4 -0.000652   1533    3
1534  20221214   075000    075459  1670975699  ...  17765.1 -0.000315   1534    4
1535  20221214   075500    075959  1670975999  ...  17764.4  0.000523   1535    5
1536  20221214   080000    080459  1670976299  ...  17760.2  0.000523   1536    0
1537  20221214   080500    080959  1670976599  ...  17777.6  0.000090   1537    1

[5 rows x 11 columns]
2022-12-14 08:10:01,440:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=6, self.factor=0.28146698663091035, self.count=5393 

self.closeSec=1670976899, self.tradeDate='20221214', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17788.1, self.close=17779.8, self.high=17789.1, self.low=17769.4 
2022-12-14 08:15:00,547:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670976899, self.tradeDate='20221214', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17788.1, self.close=17779.8, self.high=17789.1, self.low=17769.4   
127.0.0.1 - - [14/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-14 08:15:00,584:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221214   075000    075459  1670975699  ...  17765.1 -0.000315   1534    4
1535  20221214   075500    075959  1670975999  ...  17764.4  0.000523   1535    5
1536  20221214   080000    080459  1670976299  ...  17760.2  0.000523   1536    0
1537  20221214   080500    080959  1670976599  ...  17777.6  0.000090   1537    1
1538  20221214   081000    081459  1670976899  ...  17769.4 -0.000461   1538    2

[5 rows x 11 columns]
2022-12-14 08:15:00,585:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-14 08:00:17,647:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221214    052959  17747.6  ...  53.333333  0.650523  0.306414
5771  20221214    055959  17741.0  ...  53.750000  0.656851  0.307646
5772  20221214    062959  17767.4  ...  53.333333  0.644534  0.310567
5773  20221214    065959  17739.9  ...  53.333333  0.653029  0.311028
5774  20221214    072959  17775.0  ...  53.333333  0.656637  0.310482

[5 rows x 33 columns]
0.5841035120147874
acc is : 0.5841035120147874
2022-12-14 08:00:17,731:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.498945  0.501055       1  ...  1.014997   1.0    0.0  1.048589
537     0  0.507994  0.492006       0  ...  1.013443   1.0    0.0  1.046984
538     1  0.492547  0.507453       1  ...  1.015431   1.0    0.0  1.049038
539     0  0.506945  0.493055       1  ...  1.016288   1.0    0.0  1.049923
540     0  0.504490  0.495510       0  ...  1.015556   1.0    0.0  1.049168

[5 rows x 10 columns]
2022-12-14 08:00:17,743:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498546  0.501454       1  ...  1.014997   1.0    0.0  1.049525
46     0  0.508497  0.491503       0  ...  1.013443   1.0    0.0  1.049555
47     1  0.492164  0.507836       1  ...  1.015431   1.0    0.0  1.050154
48     0  0.506945  0.493055       1  ...  1.016288   1.0    0.0  1.049923
49     0  0.504490  0.495510       0  ...  1.015556   1.0    0.0  1.049168

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '21130.18333165558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17771.96227822', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221214   074000    074959  1670975399  17785.8  17773.4 -0.000697
2022-12-14 07:50:00,547:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  127.0.0.1 - - [14/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2695 

self.closeSec=1670975999, self.tradeDate='20221214', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17773.4', self.close='17777.1'
2022-12-14 08:00:01,141:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670975999, self.tradeDate='20221214', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17773.4', self.close='17777.1'
2022-12-14 08:00:01,204:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221214   071000    071959  1670973599  17747.2  17770.7  0.001319
620  20221214   072000    072959  1670974199    17770  17789.9  0.001080
621  20221214   073000    073959  1670974799  17789.9  17785.8 -0.000230
622  20221214   074000    074959  1670975399  17785.8  17773.4 -0.000697
623  20221214   075000    075959  1670975999  17773.4  17777.1  0.000208
2022-12-14 08:00:01,204:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2696 

self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17777.1', self.close='17788'
2022-12-14 08:10:01,548:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17777.1', self.close='17788'
2022-12-14 08:10:01,556:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221214   072000    072959  1670974199    17770  17789.9  0.001080
621  20221214   073000    073959  1670974799  17789.9  17785.8 -0.000230
622  20221214   074000    074959  1670975399  17785.8  17773.4 -0.000697
623  20221214   075000    075959  1670975999  17773.4  17777.1  0.000208
624  20221214   080000    080959  1670976599  17777.1    17788  0.000613
2022-12-14 08:10:01,557:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221214   074000    074959  1670975399  17785.8  17773.4
2022-12-14 07:50:00,584:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2696 

self.closeSec=1670975999, self.tradeDate='20221214', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17773.4', self.close='17777.1'
2022-12-14 08:00:01,129:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670975999, self.tradeDate='20221214', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17773.4', self.close='17777.1'
2022-12-14 08:00:01,209:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221214   071000    071959  1670973599  17747.2  17770.7
17468  20221214   072000    072959  1670974199    17770  17789.9
17469  20221214   073000    073959  1670974799  17789.9  17785.8
17470  20221214   074000    074959  1670975399  17785.8  17773.4
17471  20221214   075000    075959  1670975999  17773.4  17777.1
2022-12-14 08:00:01,209:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2697 

self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17777.1', self.close='17788'
2022-12-14 08:10:01,526:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17777.1', self.close='17788'
2022-12-14 08:10:01,553:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221214   072000    072959  1670974199    17770  17789.9
17469  20221214   073000    073959  1670974799  17789.9  17785.8
17470  20221214   074000    074959  1670975399  17785.8  17773.4
17471  20221214   075000    075959  1670975999  17773.4  17777.1
17472  20221214   080000    080959  1670976599  17777.1    17788
2022-12-14 08:10:01,553:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221214   074000    074959  1670975399  17785.8  17773.4
2022-12-14 07:50:00,548:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2696 

self.closeSec=1670975999, self.tradeDate='20221214', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17773.4', self.close='17777.1'
2022-12-14 08:00:01,117:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670975999, self.tradeDate='20221214', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17773.4', self.close='17777.1'
2022-12-14 08:00:01,197:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221214   071000    071959  1670973599  17747.2  17770.7
12140  20221214   072000    072959  1670974199    17770  17789.9
12141  20221214   073000    073959  1670974799  17789.9  17785.8
12142  20221214   074000    074959  1670975399  17785.8  17773.4
12143  20221214   075000    075959  1670975999  17773.4  17777.1
2022-12-14 08:00:01,202:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2697 

self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17777.1', self.close='17788'
2022-12-14 08:10:01,532:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17777.1', self.close='17788'
2022-12-14 08:10:01,555:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221214   072000    072959  1670974199    17770  17789.9
12141  20221214   073000    073959  1670974799  17789.9  17785.8
12142  20221214   074000    074959  1670975399  17785.8  17773.4
12143  20221214   075000    075959  1670975999  17773.4  17777.1
12144  20221214   080000    080959  1670976599  17777.1    17788
2022-12-14 08:10:01,555:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [14/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=824
self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17786.4, self.close=17788.0, self.high=17795.4, self.low=17777.6, self.vol=483.072, self.amt=8592180.2153 
2022-12-14 08:10:01,496:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221214   074500    074959  ...    0.376156   0.291374       0
5854  20221214   075000    075459  ...    0.375886   0.291483       0
5855  20221214   075500    075959  ...    0.375617   0.291591       0
5856  20221214   080000    080459  ...    0.375351   0.291700       0
5857  20221214   080500    080959  ...    0.375095   0.291814       0

[5 rows x 18 columns]
2022-12-14 08:10:01,496:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670976599, self.tradeDate='20221214', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17786.4, self.close=17788.0, self.high=17795.4, self.low=17777.6, self.vol=483.072, self.amt=8592180.2153, ukdf['pct'].iloc[-1]=9e-05 , ukdf['amount'].iloc[-1]=8592180.2153, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.3750946789558414, signal=0, value_std=0.29181392715732574 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [14/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=825
self.closeSec=1670976899, self.tradeDate='20221214', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17788.1, self.close=17779.8, self.high=17789.1, self.low=17769.4, self.vol=871.81, self.amt=15498321.6154 
2022-12-14 08:15:00,617:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221214   075000    075459  ...    0.375886   0.291483       0
5855  20221214   075500    075959  ...    0.375617   0.291591       0
5856  20221214   080000    080459  ...    0.375351   0.291700       0
5857  20221214   080500    080959  ...    0.375095   0.291814       0
5858  20221214   081000    081459  ...    0.374840   0.291928       0

[5 rows x 18 columns]
2022-12-14 08:15:00,622:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670976899, self.tradeDate='20221214', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17788.1, self.close=17779.8, self.high=17789.1, self.low=17769.4, self.vol=871.81, self.amt=15498321.6154, ukdf['pct'].iloc[-1]=-0.000461 , ukdf['amount'].iloc[-1]=15498321.6154, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.37484004888612127, signal=0, value_std=0.29192779584684647 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221213   200000    235959  1670947199  ...    719  1.615970  3.841313     1.0
720  20221214   000000    035959  1670961599  ...    720  1.401853  2.892232     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-844.2888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17740.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=112
self.closeSec=1670975999, self.tradeDate='20221214', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17740.5, self.close=17777.1, self.high=17818.0, self.low=17704.5, self.vol=33535.147, self.amt=595550340.0306 
127.0.0.1 - - [14/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-14 08:00:01,015:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670975999, self.tradeDate='20221214', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17740.5, self.close=17777.1, self.high=17818.0, self.low=17704.5, self.vol=33535.147, self.amt=595550340.0306 
2022-12-14 08:00:01,083:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20221213   120000    155959  ...   55625.343  9.536149e+08  0.000805
718  20221213   160000    195959  ...  122406.120  2.125053e+09  0.016308
719  20221213   200000    235959  ...  263218.863  4.674095e+09  0.017933
720  20221214   000000    035959  ...   85131.142  1.509010e+09 -0.000501
721  20221214   040000    075959  ...   33535.147  5.955503e+08  0.002057

[5 rows x 11 columns]
2022-12-14 08:00:02,673:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221213   120000    155959  1670918399  ...    717  0.315132 -0.874432    -1.0
718  20221213   160000    195959  1670932799  ...    718  0.365657 -0.678358    -1.0
719  20221213   200000    235959  1670947199  ...    719  1.615970  3.841313     1.0
720  20221214   000000    035959  1670961599  ...    720  1.401853  2.892232     1.0
721  20221214   040000    075959  1670975999  ...    721  1.139591  1.922200     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '1111.4688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17777.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


