# 20230105 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11162
self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16849.2, self.close=16847.7, self.high=16850.9, self.low=16846.6, self.vol=364.742, self.amt=6145691.2129 
127.0.0.1 - - [05/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 08:10:01,515:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230105   074500    074959  ...         0.0        0.0       0
5854  20230105   075000    075459  ...         0.0        0.0       0
5855  20230105   075500    075959  ...         0.0        0.0       0
5856  20230105   080000    080459  ...         0.0        0.0       0
5857  20230105   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 08:10:01,516:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16849.2, self.close=16847.7, self.high=16850.9, self.low=16846.6, self.vol=364.742, self.amt=6145691.2129, ukdf['pct'].iloc[-1]=-6.5e-05 , ukdf['amount'].iloc[-1]=6145691.2129, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-19160.0384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16847.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11163
self.closeSec=1672877699, self.tradeDate='20230105', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16847.6, self.close=16856.0, self.high=16857.0, self.low=16844.6, self.vol=570.261, self.amt=9609583.9699 
2023-01-05 08:15:00,572:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230105   075000    075459  ...         0.0        0.0       0
5855  20230105   075500    075959  ...         0.0        0.0       0
5856  20230105   080000    080459  ...         0.0        0.0       0
5857  20230105   080500    080959  ...         0.0        0.0       0
5858  20230105   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 08:15:00,573:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672877699, self.tradeDate='20230105', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16847.6, self.close=16856.0, self.high=16857.0, self.low=16844.6, self.vol=570.261, self.amt=9609583.9699, ukdf['pct'].iloc[-1]=0.000493 , ukdf['amount'].iloc[-1]=9609583.9699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-19659.4992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16856', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=118, self.factor=0.3639570283147505, self.count=11728 

self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16849.2, self.close=16847.7, self.high=16850.9, self.low=16846.6 
2023-01-05 08:10:01,453:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16849.2, self.close=16847.7, self.high=16850.9, self.low=16846.6   
2023-01-05 08:10:01,590:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230105   074500    074959  1672876199  ...  16841.9 -0.000593   1533    3
1534  20230105   075000    075459  1672876499  ...  16842.4  0.000439   1534    4
1535  20230105   075500    075959  1672876799  ...  16842.1 -0.000451   1535    5
1536  20230105   080000    080459  1672877099  ...  16841.0  0.000392   1536    0
1537  20230105   080500    080959  1672877399  ...  16846.6 -0.000065   1537    1

[5 rows x 11 columns]
2023-01-05 08:10:01,590:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [05/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=118, self.factor=0.3639570283147505, self.count=11729 

self.closeSec=1672877699, self.tradeDate='20230105', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16847.6, self.close=16856.0, self.high=16857.0, self.low=16844.6 
2023-01-05 08:15:00,565:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672877699, self.tradeDate='20230105', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16847.6, self.close=16856.0, self.high=16857.0, self.low=16844.6   
2023-01-05 08:15:00,615:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230105   075000    075459  1672876499  ...  16842.4  0.000439   1534    4
1535  20230105   075500    075959  1672876799  ...  16842.1 -0.000451   1535    5
1536  20230105   080000    080459  1672877099  ...  16841.0  0.000392   1536    0
1537  20230105   080500    080959  1672877399  ...  16846.6 -0.000065   1537    1
1538  20230105   081000    081459  1672877699  ...  16844.6  0.000493   1538    2

[5 rows x 11 columns]
2023-01-05 08:15:00,616:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-05 08:00:18,371:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230105    052959  16801.1  ...  49.166667  0.534158  0.333447
5771  20230105    055959  16819.4  ...  49.166667  0.534097  0.349312
5772  20230105    062959  16819.3  ...  49.166667  0.534642  0.366034
5773  20230105    065959  16820.3  ...  48.750000  0.533559  0.384903
5774  20230105    072959  16818.7  ...  48.750000  0.547744  0.400698

[5 rows x 33 columns]
0.5157116451016636
acc is : 0.5157116451016636
2023-01-05 08:00:18,475:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     1  0.486589  0.513411       0  ...  NaN   NaN -0.0016  0.999679
537     1  0.497708  0.502292       1  ...  NaN   NaN -0.0016  0.999738
538     1  0.495132  0.504868       0  ...  NaN   NaN -0.0016  0.999637
539     1  0.494596  0.505404       1  ...  NaN   NaN -0.0016  1.001171
540     0  0.507627  0.492373       0  ...  NaN   NaN -0.0016  1.001028

[5 rows x 10 columns]
2023-01-05 08:00:18,497:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.486377  0.513623       0  ...  NaN   NaN -0.0016  0.999358
46     1  0.497722  0.502278       1  ...  NaN   NaN -0.0016  0.999697
47     1  0.494908  0.505092       0  ...  NaN   NaN -0.0016  0.999352
48     1  0.494676  0.505324       1  ...  NaN   NaN -0.0016  1.001171
49     0  0.507627  0.492373       0  ...  NaN   NaN -0.0016  1.001028

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '6098.5152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16844.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230105   074000    074959  1672876199  16854.1  16842.4 -0.000688
2023-01-05 07:50:00,603:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5863 

self.closeSec=1672876799, self.tradeDate='20230105', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16842.5', self.close='16842.1'
127.0.0.1 - - [05/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-05 08:00:00,859:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672876799, self.tradeDate='20230105', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16842.5', self.close='16842.1'
2023-01-05 08:00:00,888:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230105   071000    071959  1672874399  16826.6  16835.6  0.000535
620  20230105   072000    072959  1672874999  16836.3  16844.6  0.000535
621  20230105   073000    073959  1672875599  16844.6    16854  0.000558
622  20230105   074000    074959  1672876199  16854.1  16842.4 -0.000688
623  20230105   075000    075959  1672876799  16842.5  16842.1 -0.000018
2023-01-05 08:00:00,890:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5864 

self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16842.2', self.close='16847.7'
2023-01-05 08:10:01,544:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16842.2', self.close='16847.7'
2023-01-05 08:10:01,646:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230105   072000    072959  1672874999  16836.3  16844.6  0.000535
621  20230105   073000    073959  1672875599  16844.6    16854  0.000558
622  20230105   074000    074959  1672876199  16854.1  16842.4 -0.000688
623  20230105   075000    075959  1672876799  16842.5  16842.1 -0.000018
624  20230105   080000    080959  1672877399  16842.2  16847.7  0.000333
2023-01-05 08:10:01,647:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230105   074000    074959  1672876199  16854.1  16842.4
2023-01-05 07:50:00,619:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5864 

self.closeSec=1672876799, self.tradeDate='20230105', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16842.5', self.close='16842.1'
2023-01-05 08:00:00,829:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672876799, self.tradeDate='20230105', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16842.5', self.close='16842.1'
2023-01-05 08:00:00,889:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230105   071000    071959  1672874399  16826.6  16835.6
17468  20230105   072000    072959  1672874999  16836.3  16844.6
17469  20230105   073000    073959  1672875599  16844.6    16854
17470  20230105   074000    074959  1672876199  16854.1  16842.4
17471  20230105   075000    075959  1672876799  16842.5  16842.1
2023-01-05 08:00:00,892:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5865 

self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16842.2', self.close='16847.7'
127.0.0.1 - - [05/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 08:10:01,596:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16842.2', self.close='16847.7'
2023-01-05 08:10:01,659:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230105   072000    072959  1672874999  16836.3  16844.6
17469  20230105   073000    073959  1672875599  16844.6    16854
17470  20230105   074000    074959  1672876199  16854.1  16842.4
17471  20230105   075000    075959  1672876799  16842.5  16842.1
17472  20230105   080000    080959  1672877399  16842.2  16847.7
2023-01-05 08:10:01,659:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230105   074000    074959  1672876199  16854.1  16842.4
2023-01-05 07:50:00,606:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [05/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5864 

self.closeSec=1672876799, self.tradeDate='20230105', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16842.5', self.close='16842.1'
2023-01-05 08:00:00,835:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672876799, self.tradeDate='20230105', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16842.5', self.close='16842.1'
2023-01-05 08:00:00,887:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230105   071000    071959  1672874399  16826.6  16835.6
12140  20230105   072000    072959  1672874999  16836.3  16844.6
12141  20230105   073000    073959  1672875599  16844.6    16854
12142  20230105   074000    074959  1672876199  16854.1  16842.4
12143  20230105   075000    075959  1672876799  16842.5  16842.1
2023-01-05 08:00:00,890:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5865 

self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16842.2', self.close='16847.7'
127.0.0.1 - - [05/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 08:10:01,574:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16842.2', self.close='16847.7'
2023-01-05 08:10:01,633:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230105   072000    072959  1672874999  16836.3  16844.6
12141  20230105   073000    073959  1672875599  16844.6    16854
12142  20230105   074000    074959  1672876199  16854.1  16842.4
12143  20230105   075000    075959  1672876799  16842.5  16842.1
12144  20230105   080000    080959  1672877399  16842.2  16847.7
2023-01-05 08:10:01,636:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [05/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7160
self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16849.2, self.close=16847.7, self.high=16850.9, self.low=16846.6, self.vol=364.742, self.amt=6145691.2129 
2023-01-05 08:10:01,675:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230105   074500    074959  ...         0.0        0.0       0
5854  20230105   075000    075459  ...         0.0        0.0       0
5855  20230105   075500    075959  ...         0.0        0.0       0
5856  20230105   080000    080459  ...         0.0        0.0       0
5857  20230105   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 08:10:01,680:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672877399, self.tradeDate='20230105', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16849.2, self.close=16847.7, self.high=16850.9, self.low=16846.6, self.vol=364.742, self.amt=6145691.2129, ukdf['pct'].iloc[-1]=-6.5e-05 , ukdf['amount'].iloc[-1]=6145691.2129, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [05/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7161
self.closeSec=1672877699, self.tradeDate='20230105', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16847.6, self.close=16856.0, self.high=16857.0, self.low=16844.6, self.vol=570.261, self.amt=9609583.9699 
2023-01-05 08:15:00,633:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230105   075000    075459  ...         0.0        0.0       0
5855  20230105   075500    075959  ...         0.0        0.0       0
5856  20230105   080000    080459  ...         0.0        0.0       0
5857  20230105   080500    080959  ...         0.0        0.0       0
5858  20230105   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 08:15:00,634:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672877699, self.tradeDate='20230105', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16847.6, self.close=16856.0, self.high=16857.0, self.low=16844.6, self.vol=570.261, self.amt=9609583.9699, ukdf['pct'].iloc[-1]=0.000493 , ukdf['amount'].iloc[-1]=9609583.9699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230104   200000    235959  1672847999  ...    719  0.864275  2.479193     1.0
720  20230105   000000    035959  1672862399  ...    720  0.990559  2.795060     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '5910.24', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16835.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [05/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=244
self.closeSec=1672876799, self.tradeDate='20230105', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16835.9, self.close=16842.2, self.high=16860.9, self.low=16766.0, self.vol=30171.855, self.amt=507370806.3352 
2023-01-05 08:00:00,747:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672876799, self.tradeDate='20230105', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16835.9, self.close=16842.2, self.high=16860.9, self.low=16766.0, self.vol=30171.855, self.amt=507370806.3352 
2023-01-05 08:00:00,807:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230104   120000    155959  ...   44883.639  7.567214e+08  0.000392
718  20230104   160000    195959  ...   34681.883  5.844936e+08 -0.002117
719  20230104   200000    235959  ...   60470.868  1.016581e+09  0.001177
720  20230105   000000    035959  ...  109449.124  1.847913e+09 -0.000635
721  20230105   040000    075959  ...   30171.855  5.073708e+08  0.000374

[5 rows x 11 columns]
2023-01-05 08:00:02,247:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230104   120000    155959  1672819199  ...    717  0.877228  2.794820     1.0
718  20230104   160000    195959  1672833599  ...    718  0.874170  2.639039     1.0
719  20230104   200000    235959  1672847999  ...    719  0.864275  2.479193     1.0
720  20230105   000000    035959  1672862399  ...    720  0.990559  2.795060     1.0
721  20230105   040000    075959  1672876799  ...    721  0.969185  2.583625     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '6279.63', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16842.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


