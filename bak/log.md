# 20230128 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [28/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17786
self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23087.4, self.close=23040.5, self.high=23094.4, self.low=23040.5, self.vol=1125.983, self.amt=25970961.1409 
2023-01-28 08:10:01,476:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230128   074500    074959  ...         0.0        0.0       0
5854  20230128   075000    075459  ...         0.0        0.0       0
5855  20230128   075500    075959  ...         0.0        0.0       0
5856  20230128   080000    080459  ...         0.0        0.0       0
5857  20230128   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 08:10:01,476:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23087.4, self.close=23040.5, self.high=23094.4, self.low=23040.5, self.vol=1125.983, self.amt=25970961.1409, ukdf['pct'].iloc[-1]=-0.002027 , ukdf['amount'].iloc[-1]=25970961.1409, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-391980.4464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23043.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17787
self.closeSec=1674864899, self.tradeDate='20230128', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23040.5, self.close=23046.1, self.high=23056.1, self.low=23034.0, self.vol=679.069, self.amt=15647636.9128 
127.0.0.1 - - [28/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-28 08:15:00,745:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230128   075000    075459  ...         0.0        0.0       0
5855  20230128   075500    075959  ...         0.0        0.0       0
5856  20230128   080000    080459  ...         0.0        0.0       0
5857  20230128   080500    080959  ...         0.0        0.0       0
5858  20230128   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 08:15:00,745:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674864899, self.tradeDate='20230128', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23040.5, self.close=23046.1, self.high=23056.1, self.low=23034.0, self.vol=679.069, self.amt=15647636.9128, ukdf['pct'].iloc[-1]=0.000243 , ukdf['amount'].iloc[-1]=15647636.9128, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-392192.86658299152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23046.72998177', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23087.4, self.close=23040.5, self.high=23094.4, self.low=23040.5 
2023-01-28 08:10:01,428:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23087.4, self.close=23040.5, self.high=23094.4, self.low=23040.5   
127.0.0.1 - - [28/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-28 08:10:01,454:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230128   074500    074959  1674863399  ...  23038.0 -0.000386   1533    3
1534  20230128   075000    075459  1674863699  ...  23035.5 -0.000282   1534    4
1535  20230128   075500    075959  1674863999  ...  23042.7  0.001098   1535    5
1536  20230128   080000    080459  1674864299  ...  23050.0  0.000837   1536    0
1537  20230128   080500    080959  1674864599  ...  23040.5 -0.002027   1537    1

[5 rows x 11 columns]
2023-01-28 08:10:01,454:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=349, self.factor=0.40581792097429403, self.count=18353 

self.closeSec=1674864899, self.tradeDate='20230128', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23040.5, self.close=23046.1, self.high=23056.1, self.low=23034.0 
2023-01-28 08:15:00,712:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674864899, self.tradeDate='20230128', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23040.5, self.close=23046.1, self.high=23056.1, self.low=23034.0   
127.0.0.1 - - [28/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-28 08:15:00,744:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230128   075000    075459  1674863699  ...  23035.5 -0.000282   1534    4
1535  20230128   075500    075959  1674863999  ...  23042.7  0.001098   1535    5
1536  20230128   080000    080459  1674864299  ...  23050.0  0.000837   1536    0
1537  20230128   080500    080959  1674864599  ...  23040.5 -0.002027   1537    1
1538  20230128   081000    081459  1674864899  ...  23034.0  0.000243   1538    2

[5 rows x 11 columns]
2023-01-28 08:15:00,744:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-28 08:00:18,781:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230128    052959  23104.6  ...  53.333333  0.528340  0.283039
5771  20230128    055959  23145.0  ...  52.916667  0.516249  0.295285
5772  20230128    062959  23077.9  ...  52.916667  0.515121  0.313129
5773  20230128    065959  23071.6  ...  52.500000  0.502514  0.336636
5774  20230128    072959  23000.7  ...  52.500000  0.513247  0.353011

[5 rows x 33 columns]
0.5194085027726433
acc is : 0.5194085027726433
2023-01-28 08:00:18,890:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.525758  0.474242       0  ...  0.978078   1.0    0.0  1.096723
537     0  0.500375  0.499625       0  ...  0.977811   1.0    0.0  1.096423
538     0  0.503615  0.496385       0  ...  0.974806   1.0    0.0  1.093054
539     1  0.479607  0.520393       1  ...  0.977459   1.0    0.0  1.096029
540     0  0.525691  0.474309       1  ...  0.977659   1.0    0.0  1.096252

[5 rows x 10 columns]
2023-01-28 08:00:18,915:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526514  0.473486       0  ...  0.978078   1.0    0.0  1.098916
46     0  0.501905  0.498095       0  ...  0.990803   1.0    0.0  1.099333
47     0  0.504313  0.495687       0  ...  0.974806   1.0    0.0  1.095042
48     1  0.479607  0.520393       1  ...  0.977459   1.0    0.0  1.096029
49     0  0.525691  0.474309       1  ...  0.977659   1.0    0.0  1.096252

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.8', 'enterprice': '23035.8', 'countrevence': '0', 'unrealprofit': '700.613527768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23058.54719246', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230128   074000    074959  1674863399  23063.9  23049.2 -0.000637
2023-01-28 07:50:00,692:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9175 

self.closeSec=1674863999, self.tradeDate='20230128', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23049.2', self.close='23068'
2023-01-28 08:00:01,719:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674863999, self.tradeDate='20230128', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23049.2', self.close='23068'
127.0.0.1 - - [28/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-28 08:00:01,767:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230128   071000    071959  1674861599  23036.9  23052.1  0.000629
620  20230128   072000    072959  1674862199  23052.1  23063.3  0.000486
621  20230128   073000    073959  1674862799  23063.3  23063.9  0.000026
622  20230128   074000    074959  1674863399  23063.9  23049.2 -0.000637
623  20230128   075000    075959  1674863999  23049.2    23068  0.000816
2023-01-28 08:00:01,787:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9176 

self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23068.1', self.close='23040.5'
2023-01-28 08:10:01,520:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23068.1', self.close='23040.5'
2023-01-28 08:10:01,542:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230128   072000    072959  1674862199  23052.1  23063.3  0.000486
621  20230128   073000    073959  1674862799  23063.3  23063.9  0.000026
622  20230128   074000    074959  1674863399  23063.9  23049.2 -0.000637
623  20230128   075000    075959  1674863999  23049.2    23068  0.000816
624  20230128   080000    080959  1674864599  23068.1  23040.5 -0.001192
2023-01-28 08:10:01,542:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230128   074000    074959  1674863399  23063.9  23049.2
2023-01-28 07:50:00,699:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9176 

self.closeSec=1674863999, self.tradeDate='20230128', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23049.2', self.close='23068'
2023-01-28 08:00:01,737:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674863999, self.tradeDate='20230128', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23049.2', self.close='23068'
2023-01-28 08:00:01,785:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230128   071000    071959  1674861599  23036.9  23052.1
17468  20230128   072000    072959  1674862199  23052.1  23063.3
17469  20230128   073000    073959  1674862799  23063.3  23063.9
17470  20230128   074000    074959  1674863399  23063.9  23049.2
17471  20230128   075000    075959  1674863999  23049.2    23068
2023-01-28 08:00:01,789:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9177 

self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23068.1', self.close='23040.5'
2023-01-28 08:10:01,560:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23068.1', self.close='23040.5'
2023-01-28 08:10:01,567:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230128   072000    072959  1674862199  23052.1  23063.3
17469  20230128   073000    073959  1674862799  23063.3  23063.9
17470  20230128   074000    074959  1674863399  23063.9  23049.2
17471  20230128   075000    075959  1674863999  23049.2    23068
17472  20230128   080000    080959  1674864599  23068.1  23040.5
2023-01-28 08:10:01,567:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230128   074000    074959  1674863399  23063.9  23049.2
2023-01-28 07:50:00,697:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9176 

self.closeSec=1674863999, self.tradeDate='20230128', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23049.2', self.close='23068'
2023-01-28 08:00:01,726:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674863999, self.tradeDate='20230128', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23049.2', self.close='23068'
2023-01-28 08:00:01,792:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230128   071000    071959  1674861599  23036.9  23052.1
12140  20230128   072000    072959  1674862199  23052.1  23063.3
12141  20230128   073000    073959  1674862799  23063.3  23063.9
12142  20230128   074000    074959  1674863399  23063.9  23049.2
12143  20230128   075000    075959  1674863999  23049.2    23068
2023-01-28 08:00:01,792:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9177 

self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23068.1', self.close='23040.5'
2023-01-28 08:10:01,527:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23068.1', self.close='23040.5'
2023-01-28 08:10:01,533:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230128   072000    072959  1674862199  23052.1  23063.3
12141  20230128   073000    073959  1674862799  23063.3  23063.9
12142  20230128   074000    074959  1674863399  23063.9  23049.2
12143  20230128   075000    075959  1674863999  23049.2    23068
12144  20230128   080000    080959  1674864599  23068.1  23040.5
2023-01-28 08:10:01,533:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [28/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13784
self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23087.4, self.close=23040.5, self.high=23094.4, self.low=23040.5, self.vol=1125.983, self.amt=25970961.1409 
2023-01-28 08:10:01,466:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230128   074500    074959  ...         0.0        0.0       0
5854  20230128   075000    075459  ...         0.0        0.0       0
5855  20230128   075500    075959  ...         0.0        0.0       0
5856  20230128   080000    080459  ...         0.0        0.0       0
5857  20230128   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 08:10:01,466:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674864599, self.tradeDate='20230128', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23087.4, self.close=23040.5, self.high=23094.4, self.low=23040.5, self.vol=1125.983, self.amt=25970961.1409, ukdf['pct'].iloc[-1]=-0.002027 , ukdf['amount'].iloc[-1]=25970961.1409, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13785
self.closeSec=1674864899, self.tradeDate='20230128', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23040.5, self.close=23046.1, self.high=23056.1, self.low=23034.0, self.vol=679.069, self.amt=15647636.9128 
127.0.0.1 - - [28/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-28 08:15:00,751:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230128   075000    075459  ...         0.0        0.0       0
5855  20230128   075500    075959  ...         0.0        0.0       0
5856  20230128   080000    080459  ...         0.0        0.0       0
5857  20230128   080500    080959  ...         0.0        0.0       0
5858  20230128   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-28 08:15:00,751:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674864899, self.tradeDate='20230128', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23040.5, self.close=23046.1, self.high=23056.1, self.low=23034.0, self.vol=679.069, self.amt=15647636.9128, ukdf['pct'].iloc[-1]=0.000243 , ukdf['amount'].iloc[-1]=15647636.9128, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230127   200000    235959  1674835199  ...    719  0.129665 -1.199676    -1.0
720  20230128   000000    035959  1674849599  ...    720  0.183695 -1.064329    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-13447.9836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23249.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=382
self.closeSec=1674863999, self.tradeDate='20230128', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23246.8, self.close=23068.0, self.high=23500.0, self.low=22940.0, self.vol=121012.865, self.amt=2806965349.92621 
127.0.0.1 - - [28/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-28 08:00:01,599:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674863999, self.tradeDate='20230128', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23246.8, self.close=23068.0, self.high=23500.0, self.low=22940.0, self.vol=121012.865, self.amt=2806965349.92621 
2023-01-28 08:00:01,652:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230127   120000    155959  ...   58836.674  1.350516e+09  0.013439
718  20230127   160000    195959  ...   38844.896  8.918868e+08 -0.004491
719  20230127   200000    235959  ...  120970.159  2.779084e+09 -0.000962
720  20230128   000000    035959  ...   84096.917  1.945958e+09  0.013264
721  20230128   040000    075959  ...  121012.865  2.806965e+09 -0.007687

[5 rows x 11 columns]
2023-01-28 08:00:03,383:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230127   120000    155959  1674806399  ...    717  0.157918 -1.190554    -1.0
718  20230127   160000    195959  1674820799  ...    718  0.130983 -1.222563    -1.0
719  20230127   200000    235959  1674835199  ...    719  0.129665 -1.199676    -1.0
720  20230128   000000    035959  1674849599  ...    720  0.183695 -1.064329    -1.0
721  20230128   040000    075959  1674863999  ...    721  0.243670 -0.910256    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-5855.8414', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23068', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


