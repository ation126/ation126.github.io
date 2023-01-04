# 20230104 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10970
self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16867.7, self.close=16866.7, self.high=16867.7, self.low=16864.3, self.vol=525.631, self.amt=8865116.1791 
127.0.0.1 - - [04/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-04 16:10:01,484:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230104   154500    154959  ...         0.0        0.0       0
5950  20230104   155000    155459  ...         0.0        0.0       0
5951  20230104   155500    155959  ...         0.0        0.0       0
5952  20230104   160000    160459  ...         0.0        0.0       0
5953  20230104   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 16:10:01,485:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16867.7, self.close=16866.7, self.high=16867.7, self.low=16864.3, self.vol=525.631, self.amt=8865116.1791, ukdf['pct'].iloc[-1]=-9.5e-05 , ukdf['amount'].iloc[-1]=8865116.1791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-20303.3824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16866.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10971
self.closeSec=1672820099, self.tradeDate='20230104', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16866.7, self.close=16870.9, self.high=16884.0, self.low=16866.7, self.vol=1555.368, self.amt=26251608.1034 
2023-01-04 16:15:00,804:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230104   155000    155459  ...         0.0        0.0       0
5951  20230104   155500    155959  ...         0.0        0.0       0
5952  20230104   160000    160459  ...         0.0        0.0       0
5953  20230104   160500    160959  ...         0.0        0.0       0
5954  20230104   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 16:15:00,805:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672820099, self.tradeDate='20230104', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16866.7, self.close=16870.9, self.high=16884.0, self.low=16866.7, self.vol=1555.368, self.amt=26251608.1034, ukdf['pct'].iloc[-1]=0.000249 , ukdf['amount'].iloc[-1]=26251608.1034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-20814.05726718848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16875.18635448', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=86, self.factor=0.4323325465133124, self.count=11536 

self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16867.7, self.close=16866.7, self.high=16867.7, self.low=16864.3 
2023-01-04 16:10:01,446:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16867.7, self.close=16866.7, self.high=16867.7, self.low=16864.3   
2023-01-04 16:10:01,471:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230104   154500    154959  1672818599  ...  16862.7 -0.000332   1629    3
1630  20230104   155000    155459  1672818899  ...  16850.1 -0.000688   1630    4
1631  20230104   155500    155959  1672819199  ...  16851.1  0.000677   1631    5
1632  20230104   160000    160459  1672819499  ...  16861.1  0.000344   1632    0
1633  20230104   160500    160959  1672819799  ...  16864.3 -0.000095   1633    1

[5 rows x 11 columns]
2023-01-04 16:10:01,471:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=86, self.factor=0.4323325465133124, self.count=11537 

self.closeSec=1672820099, self.tradeDate='20230104', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16866.7, self.close=16870.9, self.high=16884.0, self.low=16866.7 
2023-01-04 16:15:00,746:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672820099, self.tradeDate='20230104', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16866.7, self.close=16870.9, self.high=16884.0, self.low=16866.7   
2023-01-04 16:15:00,766:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230104   155000    155459  1672818899  ...  16850.1 -0.000688   1630    4
1631  20230104   155500    155959  1672819199  ...  16851.1  0.000677   1631    5
1632  20230104   160000    160459  1672819499  ...  16861.1  0.000344   1632    0
1633  20230104   160500    160959  1672819799  ...  16864.3 -0.000095   1633    1
1634  20230104   161000    161459  1672820099  ...  16866.7  0.000249   1634    2

[5 rows x 11 columns]
2023-01-04 16:15:00,766:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-04 16:00:19,464:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230104    132959  16852.5  ...  48.333333  0.607080  0.464089
5787  20230104    135959  16843.9  ...  48.750000  0.609382  0.445448
5788  20230104    142959  16848.3  ...  48.750000  0.612592  0.426713
5789  20230104    145959  16854.4  ...  49.166667  0.622200  0.405171
5790  20230104    152959  16872.8  ...  49.166667  0.601625  0.390546

[5 rows x 33 columns]
0.5202952029520295
acc is : 0.5202952029520295
2023-01-04 16:00:19,544:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     0  0.507122  0.492878       1  ...  NaN   NaN -0.0016  1.002875
538     0  0.504843  0.495157       1  ...  NaN   NaN -0.0016  1.003238
539     1  0.499974  0.500026       1  ...  NaN   NaN -0.0016  1.004339
540     0  0.505683  0.494317       0  ...  NaN   NaN -0.0016  1.002851
541     1  0.493446  0.506554       1  ...  NaN   NaN -0.0016  1.003720

[5 rows x 10 columns]
2023-01-04 16:00:19,556:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.506611  0.493389       1  ...  NaN   NaN -0.0016  1.003813
46     0  0.504590  0.495410       1  ...  NaN   NaN -0.0016  1.003961
47     1  0.499965  0.500035       1  ...  NaN   NaN -0.0016  1.005752
48     0  0.505444  0.494556       0  ...  NaN   NaN -0.0016  1.002392
49     1  0.493446  0.506554       1  ...  NaN   NaN -0.0016  1.003720

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '6820.61776759104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16861.87946218', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230104   154000    154959  1672818599  16862.9  16862.7 -0.000012
2023-01-04 15:50:00,544:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5767 

self.closeSec=1672819199, self.tradeDate='20230104', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16862.7', self.close='16862.5'
2023-01-04 16:00:00,850:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672819199, self.tradeDate='20230104', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16862.7', self.close='16862.5'
127.0.0.1 - - [04/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-04 16:00:00,889:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230104   151000    151959  1672816799    16855  16848.9 -0.000362
524  20230104   152000    152959  1672817399  16848.8  16847.9 -0.000059
525  20230104   153000    153959  1672817999    16848  16862.9  0.000890
526  20230104   154000    154959  1672818599  16862.9  16862.7 -0.000012
527  20230104   155000    155959  1672819199  16862.7  16862.5 -0.000012
2023-01-04 16:00:00,889:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5768 

self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16862.5', self.close='16866.7'
2023-01-04 16:10:01,557:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16862.5', self.close='16866.7'
2023-01-04 16:10:01,573:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230104   152000    152959  1672817399  16848.8  16847.9 -0.000059
525  20230104   153000    153959  1672817999    16848  16862.9  0.000890
526  20230104   154000    154959  1672818599  16862.9  16862.7 -0.000012
527  20230104   155000    155959  1672819199  16862.7  16862.5 -0.000012
528  20230104   160000    160959  1672819799  16862.5  16866.7  0.000249
2023-01-04 16:10:01,573:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230104   154000    154959  1672818599  16862.9  16862.7
2023-01-04 15:50:00,564:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5768 

self.closeSec=1672819199, self.tradeDate='20230104', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16862.7', self.close='16862.5'
2023-01-04 16:00:00,832:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672819199, self.tradeDate='20230104', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16862.7', self.close='16862.5'
2023-01-04 16:00:00,900:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230104   151000    151959  1672816799    16855  16848.9
17516  20230104   152000    152959  1672817399  16848.8  16847.9
17517  20230104   153000    153959  1672817999    16848  16862.9
17518  20230104   154000    154959  1672818599  16862.9  16862.7
17519  20230104   155000    155959  1672819199  16862.7  16862.5
2023-01-04 16:00:00,900:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5769 

self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16862.5', self.close='16866.7'
2023-01-04 16:10:01,552:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16862.5', self.close='16866.7'
127.0.0.1 - - [04/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-04 16:10:01,572:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230104   152000    152959  1672817399  16848.8  16847.9
17517  20230104   153000    153959  1672817999    16848  16862.9
17518  20230104   154000    154959  1672818599  16862.9  16862.7
17519  20230104   155000    155959  1672819199  16862.7  16862.5
17520  20230104   160000    160959  1672819799  16862.5  16866.7
2023-01-04 16:10:01,572:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230104   154000    154959  1672818599  16862.9  16862.7
2023-01-04 15:50:00,558:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5768 

self.closeSec=1672819199, self.tradeDate='20230104', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16862.7', self.close='16862.5'
2023-01-04 16:00:00,832:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672819199, self.tradeDate='20230104', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16862.7', self.close='16862.5'
2023-01-04 16:00:00,889:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230104   151000    151959  1672816799    16855  16848.9
12188  20230104   152000    152959  1672817399  16848.8  16847.9
12189  20230104   153000    153959  1672817999    16848  16862.9
12190  20230104   154000    154959  1672818599  16862.9  16862.7
12191  20230104   155000    155959  1672819199  16862.7  16862.5
2023-01-04 16:00:00,890:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5769 

self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16862.5', self.close='16866.7'
2023-01-04 16:10:01,557:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16862.5', self.close='16866.7'
127.0.0.1 - - [04/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-04 16:10:01,570:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230104   152000    152959  1672817399  16848.8  16847.9
12189  20230104   153000    153959  1672817999    16848  16862.9
12190  20230104   154000    154959  1672818599  16862.9  16862.7
12191  20230104   155000    155959  1672819199  16862.7  16862.5
12192  20230104   160000    160959  1672819799  16862.5  16866.7
2023-01-04 16:10:01,571:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [04/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6968
self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16867.7, self.close=16866.7, self.high=16867.7, self.low=16864.3, self.vol=525.631, self.amt=8865116.1791 
2023-01-04 16:10:01,480:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230104   154500    154959  ...         0.0        0.0       0
5950  20230104   155000    155459  ...         0.0        0.0       0
5951  20230104   155500    155959  ...         0.0        0.0       0
5952  20230104   160000    160459  ...         0.0        0.0       0
5953  20230104   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 16:10:01,487:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672819799, self.tradeDate='20230104', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16867.7, self.close=16866.7, self.high=16867.7, self.low=16864.3, self.vol=525.631, self.amt=8865116.1791, ukdf['pct'].iloc[-1]=-9.5e-05 , ukdf['amount'].iloc[-1]=8865116.1791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [04/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6969
self.closeSec=1672820099, self.tradeDate='20230104', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16866.7, self.close=16870.9, self.high=16884.0, self.low=16866.7, self.vol=1555.368, self.amt=26251608.1034 
2023-01-04 16:15:00,800:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230104   155000    155459  ...         0.0        0.0       0
5951  20230104   155500    155959  ...         0.0        0.0       0
5952  20230104   160000    160459  ...         0.0        0.0       0
5953  20230104   160500    160959  ...         0.0        0.0       0
5954  20230104   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-04 16:15:00,800:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672820099, self.tradeDate='20230104', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16866.7, self.close=16870.9, self.high=16884.0, self.low=16866.7, self.vol=1555.368, self.amt=26251608.1034, ukdf['pct'].iloc[-1]=0.000249 , ukdf['amount'].iloc[-1]=26251608.1034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230104   040000    075959  1672790399  ...    721  0.770401  2.618052     1.0
722  20230104   080000    115959  1672804799  ...    722  0.914817  3.093077     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '7087.011', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16857.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [04/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=240
self.closeSec=1672819199, self.tradeDate='20230104', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16855.9, self.close=16862.5, self.high=16904.4, self.low=16832.3, self.vol=44883.639, self.amt=756721389.5514 
2023-01-04 16:00:00,710:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672819199, self.tradeDate='20230104', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16855.9, self.close=16862.5, self.high=16904.4, self.low=16832.3, self.vol=44883.639, self.amt=756721389.5514 
2023-01-04 16:00:00,733:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230103   200000    235959  ...  73811.270  1.231384e+09 -0.002597
720  20230104   000000    035959  ...  35119.476  5.841547e+08 -0.001986
721  20230104   040000    075959  ...  20681.239  3.445698e+08  0.001773
722  20230104   080000    115959  ...  70080.094  1.175072e+09  0.011322
723  20230104   120000    155959  ...  44883.639  7.567214e+08  0.000392

[5 rows x 11 columns]
2023-01-04 16:00:02,288:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230103   200000    235959  1672761599  ...    719  0.425551  1.079751     1.0
720  20230104   000000    035959  1672775999  ...    720  0.821427  2.883686     1.0
721  20230104   040000    075959  1672790399  ...    721  0.770401  2.618052     1.0
722  20230104   080000    115959  1672804799  ...    722  0.914817  3.093077     1.0
723  20230104   120000    155959  1672819199  ...    723  0.877228  2.794820     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '7355.8815420216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16862.49514008', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


