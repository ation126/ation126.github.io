# 20230207 08:35:51

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20670
self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=22786.3, self.close=22814.3, self.high=22816.6, self.low=22767.2, self.vol=732.299, self.amt=16692460.5064 
127.0.0.1 - - [07/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-07 08:30:00,636:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230207   080500    080959  ...         0.0        0.0       0
5858  20230207   081000    081459  ...         0.0        0.0       0
5859  20230207   081500    081959  ...         0.0        0.0       0
5860  20230207   082000    082459  ...         0.0        0.0       0
5861  20230207   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 08:30:00,636:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=22786.3, self.close=22814.3, self.high=22816.6, self.low=22767.2, self.vol=732.299, self.amt=16692460.5064, ukdf['pct'].iloc[-1]=0.001229 , ukdf['amount'].iloc[-1]=16692460.5064, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-378215.53559350512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22814.45580287', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20671
self.closeSec=1675730099, self.tradeDate='20230207', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=22814.3, self.close=22804.7, self.high=22814.3, self.low=22800.6, self.vol=401.287, self.amt=9151056.9955 
127.0.0.1 - - [07/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-07 08:35:00,514:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230207   081000    081459  ...         0.0        0.0       0
5859  20230207   081500    081959  ...         0.0        0.0       0
5860  20230207   082000    082459  ...         0.0        0.0       0
5861  20230207   082500    082959  ...         0.0        0.0       0
5862  20230207   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 08:35:00,514:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675730099, self.tradeDate='20230207', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=22814.3, self.close=22804.7, self.high=22814.3, self.low=22800.6, self.vol=401.287, self.amt=9151056.9955, ukdf['pct'].iloc[-1]=-0.000421 , ukdf['amount'].iloc[-1]=9151056.9955, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-377681.27787407392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22805.57755042', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230207   082000    082459  1675729499  ...  22773.5 -0.001100   1540    4
1541  20230207   082500    082959  1675729799  ...  22767.2  0.001229   1541    5

[5 rows x 11 columns]
2023-02-07 08:30:00,571:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-07 08:30:00,626:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230207   062500    062959  1675722599  ...  0.000512   1517    5  0.513664
214  20230207   065500    065959  1675724399  ... -0.000127   1523    5  0.512581
215  20230207   072500    072959  1675726199  ...  0.000308   1529    5  0.519221
216  20230207   075500    075959  1675727999  ...  0.000585   1535    5  0.523767
217  20230207   082500    082959  1675729799  ...  0.001229   1541    5  0.525516

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=16, self.factor=0.5255163796161946, self.count=21237 

self.closeSec=1675730099, self.tradeDate='20230207', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=22814.3, self.close=22804.7, self.high=22814.3, self.low=22800.6 
2023-02-07 08:35:00,418:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675730099, self.tradeDate='20230207', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=22814.3, self.close=22804.7, self.high=22814.3, self.low=22800.6   
127.0.0.1 - - [07/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-07 08:35:00,456:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230207   081000    081459  1675728899  ...  22787.4  0.000232   1538    2
1539  20230207   081500    081959  1675729199  ...  22793.4  0.000167   1539    3
1540  20230207   082000    082459  1675729499  ...  22773.5 -0.001100   1540    4
1541  20230207   082500    082959  1675729799  ...  22767.2  0.001229   1541    5
1542  20230207   083000    083459  1675730099  ...  22800.6 -0.000421   1542    0

[5 rows x 11 columns]
2023-02-07 08:35:00,456:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-07 08:30:33,325:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230207    055959  22973.7  ...  44.583333  0.465286  0.418733
5772  20230207    062959  22915.1  ...  44.166667  0.457151  0.424103
5773  20230207    065959  22880.2  ...  44.166667  0.456988  0.429199
5774  20230207    072959  22879.2  ...  43.750000  0.421407  0.453309
5775  20230207    075959  22716.9  ...  44.166667  0.432702  0.470961

[5 rows x 33 columns]
0.5009242144177449
acc is : 0.5009242144177449
2023-02-07 08:30:33,500:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     1  0.468855  0.531145       0  ...  1.019233   1.0  0.0000  0.995874
537     1  0.472387  0.527613       0  ...  1.019202   1.0  0.0000  0.995843
538     1  0.480628  0.519372       0  ...  1.011967   1.0  0.0000  0.988775
539     1  0.436188  0.563812       1  ...  1.008535  -1.0 -0.0016  0.990546
540     1  0.474504  0.525496       1  ...  1.006027  -1.0  0.0000  0.993010

[5 rows x 10 columns]
2023-02-07 08:30:33,530:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.469690  0.530310       0  ...  1.019233   1.0  0.0000  0.995553
46     1  0.472477  0.527523       0  ...  1.019202   1.0  0.0000  0.994735
47     1  0.479863  0.520137       0  ...  1.011967   1.0  0.0000  0.986906
48     1  0.435376  0.564624       1  ...  1.008535  -1.0 -0.0016  0.988674
49     1  0.474504  0.525496       1  ...  1.006027  -1.0  0.0000  0.993010

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.436', 'enterprice': '22744.1', 'countrevence': '0', 'unrealprofit': '-1900.4695248708', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22802.6913653', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230207   080000    080959  1675728599  22757.8  22802.3  0.001960
2023-02-07 08:10:01,786:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10617 

self.closeSec=1675729199, self.tradeDate='20230207', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22802.4', self.close='22811.4'
2023-02-07 08:20:00,735:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675729199, self.tradeDate='20230207', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22802.4', self.close='22811.4'
127.0.0.1 - - [07/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-07 08:20:00,759:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230207   073000    073959  1675726799  22716.9  22735.4  0.000810
622  20230207   074000    074959  1675727399  22735.3  22775.8  0.001777
623  20230207   075000    075959  1675727999  22775.8  22757.7 -0.000795
624  20230207   080000    080959  1675728599  22757.8  22802.3  0.001960
625  20230207   081000    081959  1675729199  22802.4  22811.4  0.000399
2023-02-07 08:20:00,759:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10618 

self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='22811.6', self.close='22814.3'
2023-02-07 08:30:00,943:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='22811.6', self.close='22814.3'
127.0.0.1 - - [07/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-07 08:30:00,981:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230207   074000    074959  1675727399  22735.3  22775.8  0.001777
623  20230207   075000    075959  1675727999  22775.8  22757.7 -0.000795
624  20230207   080000    080959  1675728599  22757.8  22802.3  0.001960
625  20230207   081000    081959  1675729199  22802.4  22811.4  0.000399
626  20230207   082000    082959  1675729799  22811.6  22814.3  0.000127
2023-02-07 08:30:00,981:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230207   080000    080959  1675728599  22757.8  22802.3
2023-02-07 08:10:01,796:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10618 

self.closeSec=1675729199, self.tradeDate='20230207', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22802.4', self.close='22811.4'
2023-02-07 08:20:00,772:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675729199, self.tradeDate='20230207', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22802.4', self.close='22811.4'
127.0.0.1 - - [07/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-02-07 08:20:00,785:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230207   073000    073959  1675726799  22716.9  22735.4
17470  20230207   074000    074959  1675727399  22735.3  22775.8
17471  20230207   075000    075959  1675727999  22775.8  22757.7
17472  20230207   080000    080959  1675728599  22757.8  22802.3
17473  20230207   081000    081959  1675729199  22802.4  22811.4
2023-02-07 08:20:00,785:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10619 

self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='22811.6', self.close='22814.3'
2023-02-07 08:30:00,966:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='22811.6', self.close='22814.3'
127.0.0.1 - - [07/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-07 08:30:00,991:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230207   074000    074959  1675727399  22735.3  22775.8
17471  20230207   075000    075959  1675727999  22775.8  22757.7
17472  20230207   080000    080959  1675728599  22757.8  22802.3
17473  20230207   081000    081959  1675729199  22802.4  22811.4
17474  20230207   082000    082959  1675729799  22811.6  22814.3
2023-02-07 08:30:00,991:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230207   080000    080959  1675728599  22757.8  22802.3
2023-02-07 08:10:01,802:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Feb/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10618 

self.closeSec=1675729199, self.tradeDate='20230207', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22802.4', self.close='22811.4'
2023-02-07 08:20:00,742:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675729199, self.tradeDate='20230207', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22802.4', self.close='22811.4'
2023-02-07 08:20:00,784:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230207   073000    073959  1675726799  22716.9  22735.4
12142  20230207   074000    074959  1675727399  22735.3  22775.8
12143  20230207   075000    075959  1675727999  22775.8  22757.7
12144  20230207   080000    080959  1675728599  22757.8  22802.3
12145  20230207   081000    081959  1675729199  22802.4  22811.4
2023-02-07 08:20:00,784:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10619 

self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='22811.6', self.close='22814.3'
2023-02-07 08:30:00,956:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='22811.6', self.close='22814.3'
2023-02-07 08:30:00,995:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230207   074000    074959  1675727399  22735.3  22775.8
12143  20230207   075000    075959  1675727999  22775.8  22757.7
12144  20230207   080000    080959  1675728599  22757.8  22802.3
12145  20230207   081000    081959  1675729199  22802.4  22811.4
12146  20230207   082000    082959  1675729799  22811.6  22814.3
2023-02-07 08:30:00,995:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16668
self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=22786.3, self.close=22814.3, self.high=22816.6, self.low=22767.2, self.vol=732.299, self.amt=16692460.5064 
127.0.0.1 - - [07/Feb/2023 08:30:00] "POST / HTTP/1.1" 200 -
2023-02-07 08:30:00,592:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230207   080500    080959  ...         0.0        0.0       0
5858  20230207   081000    081459  ...         0.0        0.0       0
5859  20230207   081500    081959  ...         0.0        0.0       0
5860  20230207   082000    082459  ...         0.0        0.0       0
5861  20230207   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 08:30:00,598:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675729799, self.tradeDate='20230207', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=22786.3, self.close=22814.3, self.high=22816.6, self.low=22767.2, self.vol=732.299, self.amt=16692460.5064, ukdf['pct'].iloc[-1]=0.001229 , ukdf['amount'].iloc[-1]=16692460.5064, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16669
self.closeSec=1675730099, self.tradeDate='20230207', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=22814.3, self.close=22804.7, self.high=22814.3, self.low=22800.6, self.vol=401.287, self.amt=9151056.9955 
127.0.0.1 - - [07/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-07 08:35:00,512:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230207   081000    081459  ...         0.0        0.0       0
5859  20230207   081500    081959  ...         0.0        0.0       0
5860  20230207   082000    082459  ...         0.0        0.0       0
5861  20230207   082500    082959  ...         0.0        0.0       0
5862  20230207   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 08:35:00,516:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675730099, self.tradeDate='20230207', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=22814.3, self.close=22804.7, self.high=22814.3, self.low=22800.6, self.vol=401.287, self.amt=9151056.9955, ukdf['pct'].iloc[-1]=-0.000421 , ukdf['amount'].iloc[-1]=9151056.9955, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230206   200000    235959  1675699199  ...    719  0.728452  0.727701     1.0
720  20230207   000000    035959  1675713599  ...    720  0.682212  0.585344     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-26257.8396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23026.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [07/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=442
self.closeSec=1675727999, self.tradeDate='20230207', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23026.3, self.close=22757.7, self.high=23026.3, self.low=22622.1, self.vol=67427.476, self.amt=1538921006.62405 
2023-02-07 08:00:01,153:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675727999, self.tradeDate='20230207', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23026.3, self.close=22757.7, self.high=23026.3, self.low=22622.1, self.vol=67427.476, self.amt=1538921006.62405 
2023-02-07 08:00:01,188:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230206   120000    155959  ...   59449.276  1.353709e+09 -0.000839
718  20230206   160000    195959  ...   48624.377  1.110397e+09  0.000162
719  20230206   200000    235959  ...   94648.260  2.164577e+09  0.007331
720  20230207   000000    035959  ...  105678.626  2.434439e+09 -0.000777
721  20230207   040000    075959  ...   67427.476  1.538921e+09 -0.011661

[5 rows x 11 columns]
2023-02-07 08:00:03,483:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230206   120000    155959  1675670399  ...    717  0.662380  0.457873     NaN
718  20230206   160000    195959  1675684799  ...    718  0.690053  0.573136     NaN
719  20230206   200000    235959  1675699199  ...    719  0.728452  0.727701     1.0
720  20230207   000000    035959  1675713599  ...    720  0.682212  0.585344     NaN
721  20230207   040000    075959  1675727999  ...    721  0.528222  0.049603     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-36719.6736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22757.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


