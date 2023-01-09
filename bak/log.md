# 20230109 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [09/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12314
self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17123.6, self.close=17132.5, self.high=17139.9, self.low=17112.4, self.vol=2848.9, self.amt=48791722.8127 
2023-01-09 08:10:01,435:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230109   074500    074959  ...         0.0        0.0       0
5854  20230109   075000    075459  ...         0.0        0.0       0
5855  20230109   075500    075959  ...         0.0        0.0       0
5856  20230109   080000    080459  ...         0.0        0.0       0
5857  20230109   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 08:10:01,435:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17123.6, self.close=17132.5, self.high=17139.9, self.low=17112.4, self.vol=2848.9, self.amt=48791722.8127, ukdf['pct'].iloc[-1]=0.000526 , ukdf['amount'].iloc[-1]=48791722.8127, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-36352.45524427664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17133.40222089', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12315
self.closeSec=1673223299, self.tradeDate='20230109', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17132.4, self.close=17158.2, self.high=17179.9, self.low=17125.5, self.vol=4347.645, self.amt=74593092.0937 
2023-01-09 08:15:00,588:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230109   075000    075459  ...         0.0        0.0       0
5855  20230109   075500    075959  ...         0.0        0.0       0
5856  20230109   080000    080459  ...         0.0        0.0       0
5857  20230109   080500    080959  ...         0.0        0.0       0
5858  20230109   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 08:15:00,588:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673223299, self.tradeDate='20230109', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17132.4, self.close=17158.2, self.high=17179.9, self.low=17125.5, self.vol=4347.645, self.amt=74593092.0937, ukdf['pct'].iloc[-1]=0.0015 , ukdf['amount'].iloc[-1]=74593092.0937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-37967.20541779408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17160.23601133', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=63, self.factor=0.47026996438518937, self.count=12880 

self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17123.6, self.close=17132.5, self.high=17139.9, self.low=17112.4 
2023-01-09 08:10:01,428:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17123.6, self.close=17132.5, self.high=17139.9, self.low=17112.4   
2023-01-09 08:10:01,459:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230109   074500    074959  1673221799  ...  17038.8  0.000423   1533    3
1534  20230109   075000    075459  1673222099  ...  17045.0  0.001179   1534    4
1535  20230109   075500    075959  1673222399  ...  17060.0  0.003422   1535    5
1536  20230109   080000    080459  1673222699  ...  17109.0 -0.000012   1536    0
1537  20230109   080500    080959  1673222999  ...  17112.4  0.000526   1537    1

[5 rows x 11 columns]
2023-01-09 08:10:01,460:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=63, self.factor=0.47026996438518937, self.count=12881 

self.closeSec=1673223299, self.tradeDate='20230109', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17132.4, self.close=17158.2, self.high=17179.9, self.low=17125.5 
2023-01-09 08:15:00,526:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673223299, self.tradeDate='20230109', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17132.4, self.close=17158.2, self.high=17179.9, self.low=17125.5   
127.0.0.1 - - [09/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-09 08:15:00,565:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230109   075000    075459  1673222099  ...  17045.0  0.001179   1534    4
1535  20230109   075500    075959  1673222399  ...  17060.0  0.003422   1535    5
1536  20230109   080000    080459  1673222699  ...  17109.0 -0.000012   1536    0
1537  20230109   080500    080959  1673222999  ...  17112.4  0.000526   1537    1
1538  20230109   081000    081459  1673223299  ...  17125.5  0.001500   1538    2

[5 rows x 11 columns]
2023-01-09 08:15:00,565:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-09 08:00:18,002:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230109    052959  16959.5  ...  52.083333  0.552657  0.586267
5771  20230109    055959  16963.4  ...  52.083333  0.536195  0.589181
5772  20230109    062959  16949.2  ...  52.500000  0.548563  0.583805
5773  20230109    065959  16961.9  ...  52.083333  0.542680  0.582013
5774  20230109    072959  16956.8  ...  52.083333  0.613791  0.563339

[5 rows x 33 columns]
0.5545286506469501
acc is : 0.5545286506469501
2023-01-09 08:00:18,084:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     0  0.506373  0.493627       0  ...  NaN   NaN -0.0016  1.019807
537     0  0.500412  0.499588       1  ...  NaN   NaN -0.0016  1.020578
538     0  0.507811  0.492189       0  ...  NaN   NaN -0.0016  1.020271
539     0  0.500477  0.499523       1  ...  NaN   NaN -0.0016  1.025433
540     0  0.529687  0.470313       1  ...  NaN   NaN -0.0016  1.030307

[5 rows x 10 columns]
2023-01-09 08:00:18,098:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.506595  0.493405       0  ...  NaN   NaN -0.0016  1.022804
46     0  0.500493  0.499507       1  ...  NaN   NaN -0.0016  1.020614
47     0  0.508031  0.491969       0  ...  NaN   NaN -0.0016  1.021365
48     0  0.500477  0.499523       1  ...  NaN   NaN -0.0016  1.025433
49     0  0.529687  0.470313       1  ...  NaN   NaN -0.0016  1.030307

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '17905.62868584384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17122.53152478', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230109   074000    074959  1673221799  17038.9  17045.2  0.000364
2023-01-09 07:50:00,781:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6439 

self.closeSec=1673222399, self.tradeDate='20230109', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17045.2', self.close='17123.7'
2023-01-09 08:00:01,136:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673222399, self.tradeDate='20230109', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17045.2', self.close='17123.7'
2023-01-09 08:00:01,166:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230109   071000    071959  1673219999  17037.3  17056.3  0.000833
620  20230109   072000    072959  1673220599  17056.2  17042.7 -0.000797
621  20230109   073000    073959  1673221199  17042.7    17039 -0.000217
622  20230109   074000    074959  1673221799  17038.9  17045.2  0.000364
623  20230109   075000    075959  1673222399  17045.2  17123.7  0.004605
2023-01-09 08:00:01,166:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6440 

self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17124.6', self.close='17132.5'
2023-01-09 08:10:01,531:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17124.6', self.close='17132.5'
127.0.0.1 - - [09/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-09 08:10:01,537:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230109   072000    072959  1673220599  17056.2  17042.7 -0.000797
621  20230109   073000    073959  1673221199  17042.7    17039 -0.000217
622  20230109   074000    074959  1673221799  17038.9  17045.2  0.000364
623  20230109   075000    075959  1673222399  17045.2  17123.7  0.004605
624  20230109   080000    080959  1673222999  17124.6  17132.5  0.000514
2023-01-09 08:10:01,543:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230109   074000    074959  1673221799  17038.9  17045.2
2023-01-09 07:50:00,799:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  127.0.0.1 - - [09/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6440 

self.closeSec=1673222399, self.tradeDate='20230109', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17045.2', self.close='17123.7'
2023-01-09 08:00:01,152:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673222399, self.tradeDate='20230109', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17045.2', self.close='17123.7'
2023-01-09 08:00:01,171:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230109   071000    071959  1673219999  17037.3  17056.3
17468  20230109   072000    072959  1673220599  17056.2  17042.7
17469  20230109   073000    073959  1673221199  17042.7    17039
17470  20230109   074000    074959  1673221799  17038.9  17045.2
17471  20230109   075000    075959  1673222399  17045.2  17123.7
2023-01-09 08:00:01,171:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6441 

self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17124.6', self.close='17132.5'
2023-01-09 08:10:01,505:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17124.6', self.close='17132.5'
2023-01-09 08:10:01,521:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230109   072000    072959  1673220599  17056.2  17042.7
17469  20230109   073000    073959  1673221199  17042.7    17039
17470  20230109   074000    074959  1673221799  17038.9  17045.2
17471  20230109   075000    075959  1673222399  17045.2  17123.7
17472  20230109   080000    080959  1673222999  17124.6  17132.5
2023-01-09 08:10:01,521:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230109   074000    074959  1673221799  17038.9  17045.2
2023-01-09 07:50:00,774:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6440 

self.closeSec=1673222399, self.tradeDate='20230109', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17045.2', self.close='17123.7'
127.0.0.1 - - [09/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-09 08:00:01,136:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673222399, self.tradeDate='20230109', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17045.2', self.close='17123.7'
2023-01-09 08:00:01,168:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230109   071000    071959  1673219999  17037.3  17056.3
12140  20230109   072000    072959  1673220599  17056.2  17042.7
12141  20230109   073000    073959  1673221199  17042.7    17039
12142  20230109   074000    074959  1673221799  17038.9  17045.2
12143  20230109   075000    075959  1673222399  17045.2  17123.7
2023-01-09 08:00:01,169:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6441 

self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17124.6', self.close='17132.5'
2023-01-09 08:10:01,513:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17124.6', self.close='17132.5'
127.0.0.1 - - [09/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-09 08:10:01,524:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230109   072000    072959  1673220599  17056.2  17042.7
12141  20230109   073000    073959  1673221199  17042.7    17039
12142  20230109   074000    074959  1673221799  17038.9  17045.2
12143  20230109   075000    075959  1673222399  17045.2  17123.7
12144  20230109   080000    080959  1673222999  17124.6  17132.5
2023-01-09 08:10:01,524:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8312
self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17123.6, self.close=17132.5, self.high=17139.9, self.low=17112.4, self.vol=2848.9, self.amt=48791722.8127 
127.0.0.1 - - [09/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-09 08:10:01,471:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230109   074500    074959  ...         0.0        0.0       0
5854  20230109   075000    075459  ...         0.0        0.0       0
5855  20230109   075500    075959  ...         0.0        0.0       0
5856  20230109   080000    080459  ...         0.0        0.0       0
5857  20230109   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 08:10:01,472:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673222999, self.tradeDate='20230109', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17123.6, self.close=17132.5, self.high=17139.9, self.low=17112.4, self.vol=2848.9, self.amt=48791722.8127, ukdf['pct'].iloc[-1]=0.000526 , ukdf['amount'].iloc[-1]=48791722.8127, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8313
self.closeSec=1673223299, self.tradeDate='20230109', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17132.4, self.close=17158.2, self.high=17179.9, self.low=17125.5, self.vol=4347.645, self.amt=74593092.0937 
2023-01-09 08:15:00,572:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230109   075000    075459  ...         0.0        0.0       0
5855  20230109   075500    075959  ...         0.0        0.0       0
5856  20230109   080000    080459  ...         0.0        0.0       0
5857  20230109   080500    080959  ...         0.0        0.0       0
5858  20230109   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-09 08:15:00,573:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673223299, self.tradeDate='20230109', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17132.4, self.close=17158.2, self.high=17179.9, self.low=17125.5, self.vol=4347.645, self.amt=74593092.0937, ukdf['pct'].iloc[-1]=0.0015 , ukdf['amount'].iloc[-1]=74593092.0937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230108   200000    235959  1673193599  ...    719  0.221401 -0.395178     NaN
720  20230109   000000    035959  1673207999  ...    720  0.236135 -0.354664     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.715', 'enterprice': '16938.9', 'countrevence': '0', 'unrealprofit': '985.7705', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16920.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=892041.1793865, self.flagDict['side']='sell', self.tradeCount=11, self.count=268
self.closeSec=1673222399, self.tradeDate='20230109', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16920.3, self.close=17123.7, self.high=17181.1, self.low=16916.5, self.vol=60866.075, self.amt=1036431655.1927 
127.0.0.1 - - [09/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-09 08:00:01,035:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673222399, self.tradeDate='20230109', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16920.3, self.close=17123.7, self.high=17181.1, self.low=16916.5, self.vol=60866.075, self.amt=1036431655.1927 
2023-01-09 08:00:01,072:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230108   120000    155959  ...   7997.895  1.354707e+08  0.000384
718  20230108   160000    195959  ...  15529.917  2.630195e+08 -0.001593
719  20230108   200000    235959  ...  27048.995  4.585836e+08  0.004244
720  20230109   000000    035959  ...  31183.879  5.282959e+08 -0.004114
721  20230109   040000    075959  ...  60866.075  1.036432e+09  0.012015

[5 rows x 11 columns]
2023-01-09 08:00:02,535:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230108   120000    155959  1673164799  ...    717  0.186551 -0.494174     NaN
718  20230108   160000    195959  1673179199  ...    718  0.192833 -0.482656     NaN
719  20230108   200000    235959  1673193599  ...    719  0.221401 -0.395178     NaN
720  20230109   000000    035959  1673207999  ...    720  0.236135 -0.354664     NaN
721  20230109   040000    075959  1673222399  ...    721  0.338125 -0.011355     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.715', 'enterprice': '16938.9', 'countrevence': '0', 'unrealprofit': '-9783.904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17124.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


