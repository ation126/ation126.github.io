# 20230206 08:36:00

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20382
self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23016.9, self.close=23049.2, self.high=23062.2, self.low=23009.9, self.vol=2393.097, self.amt=55132723.1247 
127.0.0.1 - - [06/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-06 08:30:01,259:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230206   080500    080959  ...         0.0        0.0       0
5858  20230206   081000    081459  ...         0.0        0.0       0
5859  20230206   081500    081959  ...         0.0        0.0       0
5860  20230206   082000    082459  ...         0.0        0.0       0
5861  20230206   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 08:30:01,260:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23016.9, self.close=23049.2, self.high=23062.2, self.low=23009.9, self.vol=2393.097, self.amt=55132723.1247, ukdf['pct'].iloc[-1]=0.001399 , ukdf['amount'].iloc[-1]=55132723.1247, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-392436.9816523304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23050.78666665', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20383
self.closeSec=1675643699, self.tradeDate='20230206', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23049.2, self.close=23031.7, self.high=23051.9, self.low=23024.0, self.vol=1263.846, self.amt=29112989.3464 
127.0.0.1 - - [06/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-06 08:35:00,809:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230206   081000    081459  ...         0.0        0.0       0
5859  20230206   081500    081959  ...         0.0        0.0       0
5860  20230206   082000    082459  ...         0.0        0.0       0
5861  20230206   082500    082959  ...         0.0        0.0       0
5862  20230206   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 08:35:00,809:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675643699, self.tradeDate='20230206', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23049.2, self.close=23031.7, self.high=23051.9, self.low=23024.0, self.vol=1263.846, self.amt=29112989.3464, ukdf['pct'].iloc[-1]=-0.000759 , ukdf['amount'].iloc[-1]=29112989.3464, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-391305.07181684944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23031.97667869', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1541  20230206   082500    082959  1675643399  ...  23009.9  0.001399   1541    5

[5 rows x 11 columns]
2023-02-06 08:30:01,218:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-06 08:30:01,274:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230206   062500    062959  1675636199  ... -0.000618   1517    5  0.636749
214  20230206   065500    065959  1675637999  ... -0.000548   1523    5  0.636859
215  20230206   072500    072959  1675639799  ... -0.001024   1529    5  0.638792
216  20230206   075500    075959  1675641599  ... -0.000558   1535    5  0.640681
217  20230206   082500    082959  1675643399  ...  0.001399   1541    5  0.637968

[5 rows x 12 columns]
2023-02-06 08:30:01,321:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2060830, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230206, closeTime:082959, close:23049.2, total:928613.5591976999, factor:0.6379680886921212, factorCnt:0, side:buy 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6379680886921212, self.count=20949 

self.closeSec=1675643699, self.tradeDate='20230206', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23049.2, self.close=23031.7, self.high=23051.9, self.low=23024.0 
2023-02-06 08:35:00,775:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675643699, self.tradeDate='20230206', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23049.2, self.close=23031.7, self.high=23051.9, self.low=23024.0   
127.0.0.1 - - [06/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-06 08:35:00,802:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230206   081000    081459  1675642499  ...  22963.1  0.000883   1538    2
1539  20230206   081500    081959  1675642799  ...  22976.0  0.000457   1539    3
1540  20230206   082000    082459  1675643099  ...  22998.8  0.000339   1540    4
1541  20230206   082500    082959  1675643399  ...  23009.9  0.001399   1541    5
1542  20230206   083000    083459  1675643699  ...  23024.0 -0.000759   1542    0

[5 rows x 11 columns]
2023-02-06 08:35:00,802:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-06 08:30:34,137:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230206    055959  22882.2  ...  45.000000  0.383661  0.706860
5772  20230206    062959  22896.8  ...  45.416667  0.408885  0.704829
5773  20230206    065959  22965.9  ...  45.416667  0.412965  0.701831
5774  20230206    072959  22977.4  ...  45.416667  0.401172  0.703637
5775  20230206    075959  22929.3  ...  45.000000  0.401123  0.705342

[5 rows x 33 columns]
0.512014787430684
acc is : 0.512014787430684
2023-02-06 08:30:34,299:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.494788  0.505212       1  ...  0.992349  -1.0    0.0  1.017631
537     0  0.508628  0.491372       1  ...  0.991852  -1.0    0.0  1.018141
538     1  0.496949  0.503051       0  ...  0.993924  -1.0    0.0  1.016014
539     1  0.486704  0.513296       0  ...  0.993933  -1.0    0.0  1.016005
540     1  0.495008  0.504992       1  ...  0.988731  -1.0    0.0  1.021322

[5 rows x 10 columns]
2023-02-06 08:30:34,335:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493985  0.506015       1  ...  0.992349  -1.0    0.0  1.014296
46     0  0.508598  0.491402       1  ...  0.991852  -1.0    0.0  1.015459
47     1  0.497823  0.502177       0  ...  0.993924  -1.0    0.0  1.018220
48     1  0.487870  0.512130       0  ...  0.993933  -1.0    0.0  1.018211
49     1  0.495008  0.504992       1  ...  0.988731  -1.0    0.0  1.021322

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '19691.14101052873', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23051.39057461', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230206   080000    080959  1675642199  22929.3  22978.4  0.002146
2023-02-06 08:10:01,574:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10473 

self.closeSec=1675642799, self.tradeDate='20230206', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22978.4', self.close='23009.2'
2023-02-06 08:20:01,057:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675642799, self.tradeDate='20230206', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22978.4', self.close='23009.2'
2023-02-06 08:20:01,063:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230206   073000    073959  1675640399  22929.3  22933.4  0.000174
622  20230206   074000    074959  1675640999  22933.4  22949.4  0.000698
623  20230206   075000    075959  1675641599  22949.4  22929.2 -0.000880
624  20230206   080000    080959  1675642199  22929.3  22978.4  0.002146
625  20230206   081000    081959  1675642799  22978.4  23009.2  0.001340
2023-02-06 08:20:01,070:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10474 

self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23008.2', self.close='23049.2'
2023-02-06 08:30:01,564:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23008.2', self.close='23049.2'
2023-02-06 08:30:01,596:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230206   074000    074959  1675640999  22933.4  22949.4  0.000698
623  20230206   075000    075959  1675641599  22949.4  22929.2 -0.000880
624  20230206   080000    080959  1675642199  22929.3  22978.4  0.002146
625  20230206   081000    081959  1675642799  22978.4  23009.2  0.001340
626  20230206   082000    082959  1675643399  23008.2  23049.2  0.001738
2023-02-06 08:30:01,596:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230206   080000    080959  1675642199  22929.3  22978.4
2023-02-06 08:10:01,544:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10474 

self.closeSec=1675642799, self.tradeDate='20230206', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22978.4', self.close='23009.2'
2023-02-06 08:20:01,095:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675642799, self.tradeDate='20230206', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22978.4', self.close='23009.2'
127.0.0.1 - - [06/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-06 08:20:01,114:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230206   073000    073959  1675640399  22929.3  22933.4
17470  20230206   074000    074959  1675640999  22933.4  22949.4
17471  20230206   075000    075959  1675641599  22949.4  22929.2
17472  20230206   080000    080959  1675642199  22929.3  22978.4
17473  20230206   081000    081959  1675642799  22978.4  23009.2
2023-02-06 08:20:01,114:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10475 

self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23008.2', self.close='23049.2'
2023-02-06 08:30:01,583:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23008.2', self.close='23049.2'
127.0.0.1 - - [06/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-06 08:30:01,623:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230206   074000    074959  1675640999  22933.4  22949.4
17471  20230206   075000    075959  1675641599  22949.4  22929.2
17472  20230206   080000    080959  1675642199  22929.3  22978.4
17473  20230206   081000    081959  1675642799  22978.4  23009.2
17474  20230206   082000    082959  1675643399  23008.2  23049.2
2023-02-06 08:30:01,623:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230206   080000    080959  1675642199  22929.3  22978.4
2023-02-06 08:10:01,539:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10474 

self.closeSec=1675642799, self.tradeDate='20230206', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22978.4', self.close='23009.2'
2023-02-06 08:20:01,088:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675642799, self.tradeDate='20230206', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22978.4', self.close='23009.2'
127.0.0.1 - - [06/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-06 08:20:01,107:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230206   073000    073959  1675640399  22929.3  22933.4
12142  20230206   074000    074959  1675640999  22933.4  22949.4
12143  20230206   075000    075959  1675641599  22949.4  22929.2
12144  20230206   080000    080959  1675642199  22929.3  22978.4
12145  20230206   081000    081959  1675642799  22978.4  23009.2
2023-02-06 08:20:01,107:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10475 

self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='23008.2', self.close='23049.2'
2023-02-06 08:30:01,573:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='23008.2', self.close='23049.2'
127.0.0.1 - - [06/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-06 08:30:01,618:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230206   074000    074959  1675640999  22933.4  22949.4
12143  20230206   075000    075959  1675641599  22949.4  22929.2
12144  20230206   080000    080959  1675642199  22929.3  22978.4
12145  20230206   081000    081959  1675642799  22978.4  23009.2
12146  20230206   082000    082959  1675643399  23008.2  23049.2
2023-02-06 08:30:01,618:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16380
self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=23016.9, self.close=23049.2, self.high=23062.2, self.low=23009.9, self.vol=2393.097, self.amt=55132723.1247 
127.0.0.1 - - [06/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-06 08:30:01,263:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230206   080500    080959  ...         0.0        0.0       0
5858  20230206   081000    081459  ...         0.0        0.0       0
5859  20230206   081500    081959  ...         0.0        0.0       0
5860  20230206   082000    082459  ...         0.0        0.0       0
5861  20230206   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 08:30:01,264:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675643399, self.tradeDate='20230206', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=23016.9, self.close=23049.2, self.high=23062.2, self.low=23009.9, self.vol=2393.097, self.amt=55132723.1247, ukdf['pct'].iloc[-1]=0.001399 , ukdf['amount'].iloc[-1]=55132723.1247, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16381
self.closeSec=1675643699, self.tradeDate='20230206', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=23049.2, self.close=23031.7, self.high=23051.9, self.low=23024.0, self.vol=1263.846, self.amt=29112989.3464 
127.0.0.1 - - [06/Feb/2023 08:35:00] "POST / HTTP/1.1" 200 -
2023-02-06 08:35:00,846:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230206   081000    081459  ...         0.0        0.0       0
5859  20230206   081500    081959  ...         0.0        0.0       0
5860  20230206   082000    082459  ...         0.0        0.0       0
5861  20230206   082500    082959  ...         0.0        0.0       0
5862  20230206   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 08:35:00,848:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675643699, self.tradeDate='20230206', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=23049.2, self.close=23031.7, self.high=23051.9, self.low=23024.0, self.vol=1263.846, self.amt=29112989.3464, ukdf['pct'].iloc[-1]=-0.000759 , ukdf['amount'].iloc[-1]=29112989.3464, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230205   200000    235959  1675612799  ...    719  0.412451 -0.451433     NaN
720  20230206   000000    035959  1675627199  ...    720  0.367856 -0.581595     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-31601.12248798968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22889.06616138', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=436
self.closeSec=1675641599, self.tradeDate='20230206', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22889.6, self.close=22929.2, self.high=23025.0, self.low=22787.8, self.vol=47187.259, self.amt=1081561457.3435 
127.0.0.1 - - [06/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-02-06 08:00:02,179:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675641599, self.tradeDate='20230206', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22889.6, self.close=22929.2, self.high=23025.0, self.low=22787.8, self.vol=47187.259, self.amt=1081561457.3435 
2023-02-06 08:00:02,233:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230205   120000    155959  ...   20096.361  4.697797e+08  0.001439
718  20230205   160000    195959  ...   20554.304  4.805312e+08 -0.000980
719  20230205   200000    235959  ...  103064.491  2.387031e+09 -0.011129
720  20230206   000000    035959  ...  131414.742  3.015818e+09 -0.008864
721  20230206   040000    075959  ...   47187.259  1.081561e+09  0.001734

[5 rows x 11 columns]
2023-02-06 08:00:04,416:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230205   120000    155959  1675583999  ...    717  0.579785  0.060318     NaN
718  20230205   160000    195959  1675598399  ...    718  0.502495 -0.173977     NaN
719  20230205   200000    235959  1675612799  ...    719  0.412451 -0.451433     NaN
720  20230206   000000    035959  1675627199  ...    720  0.367856 -0.581595     NaN
721  20230206   040000    075959  1675641599  ...    721  0.718608  0.611415     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-30037.3476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22929.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


