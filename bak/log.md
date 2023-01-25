# 20230125 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16922
self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22656.7, self.close=22636.9, self.high=22660.0, self.low=22608.4, self.vol=1785.04, self.amt=40402272.56 
127.0.0.1 - - [25/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-25 08:10:01,488:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230125   074500    074959  ...         0.0        0.0       0
5854  20230125   075000    075459  ...         0.0        0.0       0
5855  20230125   075500    075959  ...         0.0        0.0       0
5856  20230125   080000    080459  ...         0.0        0.0       0
5857  20230125   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 08:10:01,489:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22656.7, self.close=22636.9, self.high=22660.0, self.low=22608.4, self.vol=1785.04, self.amt=40402272.56, ukdf['pct'].iloc[-1]=-0.00087 , ukdf['amount'].iloc[-1]=40402272.56, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-367494.832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22636.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16923
self.closeSec=1674605699, self.tradeDate='20230125', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22637.0, self.close=22632.4, self.high=22645.0, self.low=22602.7, self.vol=1200.329, self.amt=27160162.5124 
127.0.0.1 - - [25/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-25 08:15:00,738:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230125   075000    075459  ...         0.0        0.0       0
5855  20230125   075500    075959  ...         0.0        0.0       0
5856  20230125   080000    080459  ...         0.0        0.0       0
5857  20230125   080500    080959  ...         0.0        0.0       0
5858  20230125   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 08:15:00,739:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674605699, self.tradeDate='20230125', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22637.0, self.close=22632.4, self.high=22645.0, self.low=22602.7, self.vol=1200.329, self.amt=27160162.5124, ukdf['pct'].iloc[-1]=-0.000199 , ukdf['amount'].iloc[-1]=27160162.5124, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-367254.128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22632.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=205, self.factor=0.4556866604339824, self.count=17488 

self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22656.7, self.close=22636.9, self.high=22660.0, self.low=22608.4 
2023-01-25 08:10:01,427:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22656.7, self.close=22636.9, self.high=22660.0, self.low=22608.4   
2023-01-25 08:10:01,478:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230125   074500    074959  1674604199  ...  22536.8  0.001496   1533    3
1534  20230125   075000    075459  1674604499  ...  22572.5 -0.000486   1534    4
1535  20230125   075500    075959  1674604799  ...  22597.3  0.000548   1535    5
1536  20230125   080000    080459  1674605099  ...  22593.9  0.001290   1536    0
1537  20230125   080500    080959  1674605399  ...  22608.4 -0.000870   1537    1

[5 rows x 11 columns]
2023-01-25 08:10:01,478:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=205, self.factor=0.4556866604339824, self.count=17489 

self.closeSec=1674605699, self.tradeDate='20230125', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22637.0, self.close=22632.4, self.high=22645.0, self.low=22602.7 
2023-01-25 08:15:00,697:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674605699, self.tradeDate='20230125', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22637.0, self.close=22632.4, self.high=22645.0, self.low=22602.7   
127.0.0.1 - - [25/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-25 08:15:00,728:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230125   075000    075459  1674604499  ...  22572.5 -0.000486   1534    4
1535  20230125   075500    075959  1674604799  ...  22597.3  0.000548   1535    5
1536  20230125   080000    080459  1674605099  ...  22593.9  0.001290   1536    0
1537  20230125   080500    080959  1674605399  ...  22608.4 -0.000870   1537    1
1538  20230125   081000    081459  1674605699  ...  22602.7 -0.000199   1538    2

[5 rows x 11 columns]
2023-01-25 08:15:00,728:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-25 08:00:17,864:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230125    052959  23004.2  ...  54.583333  0.524687  0.397488
5771  20230125    055959  22990.1  ...  54.583333  0.503115  0.407386
5772  20230125    062959  22896.2  ...  54.166667  0.462187  0.440615
5773  20230125    065959  22690.0  ...  54.166667  0.473801  0.464721
5774  20230125    072959  22750.7  ...  54.166667  0.447476  0.485355

[5 rows x 33 columns]
0.5415896487985212
acc is : 0.5415896487985212
2023-01-25 08:00:17,970:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     0  0.511819  0.488181       0  ...  1.045255   1.0  0.0000  1.185232
537     1  0.487192  0.512808       0  ...  1.036207   1.0  0.0000  1.174972
538     1  0.444468  0.555532       1  ...  1.032143  -1.0 -0.0016  1.177700
539     0  0.502296  0.497704       0  ...  1.038526  -1.0  0.0000  1.170417
540     1  0.448668  0.551332       1  ...  1.037727  -1.0  0.0000  1.171318

[5 rows x 10 columns]
2023-01-25 08:00:17,997:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.512177  0.487823       0  ...  1.045255   1.0  0.0000  1.189259
46     1  0.487930  0.512070       0  ...  1.036207   1.0  0.0000  1.187432
47     1  0.444715  0.555285       1  ...  1.032143  -1.0 -0.0016  1.189480
48     0  0.502296  0.497704       0  ...  1.038526  -1.0  0.0000  1.170417
49     1  0.448668  0.551332       1  ...  1.037727  -1.0  0.0000  1.171318

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.198', 'enterprice': '22732.6', 'countrevence': '0', 'unrealprofit': '3747.76544670216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22616.20253908', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230125   074000    074959  1674604199  22540.6    22626  0.003575
2023-01-25 07:50:00,666:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8743 

self.closeSec=1674604799, self.tradeDate='20230125', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22623.5', self.close='22627.4'
2023-01-25 08:00:02,001:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674604799, self.tradeDate='20230125', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22623.5', self.close='22627.4'
2023-01-25 08:00:02,062:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230125   071000    071959  1674602399  22671.5  22534.9 -0.006021
620  20230125   072000    072959  1674602999  22534.9    22610  0.003333
621  20230125   073000    073959  1674603599  22611.6  22545.4 -0.002857
622  20230125   074000    074959  1674604199  22540.6    22626  0.003575
623  20230125   075000    075959  1674604799  22623.5  22627.4  0.000062
2023-01-25 08:00:02,062:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8744 

self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22627.5', self.close='22636.9'
2023-01-25 08:10:01,541:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22627.5', self.close='22636.9'
127.0.0.1 - - [25/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-25 08:10:01,549:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230125   072000    072959  1674602999  22534.9    22610  0.003333
621  20230125   073000    073959  1674603599  22611.6  22545.4 -0.002857
622  20230125   074000    074959  1674604199  22540.6    22626  0.003575
623  20230125   075000    075959  1674604799  22623.5  22627.4  0.000062
624  20230125   080000    080959  1674605399  22627.5  22636.9  0.000420
2023-01-25 08:10:01,550:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230125   074000    074959  1674604199  22540.6    22626
2023-01-25 07:50:00,677:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8744 

self.closeSec=1674604799, self.tradeDate='20230125', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22623.5', self.close='22627.4'
2023-01-25 08:00:02,019:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674604799, self.tradeDate='20230125', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22623.5', self.close='22627.4'
2023-01-25 08:00:02,045:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230125   071000    071959  1674602399  22671.5  22534.9
17468  20230125   072000    072959  1674602999  22534.9    22610
17469  20230125   073000    073959  1674603599  22611.6  22545.4
17470  20230125   074000    074959  1674604199  22540.6    22626
17471  20230125   075000    075959  1674604799  22623.5  22627.4
2023-01-25 08:00:02,045:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8745 

self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22627.5', self.close='22636.9'
2023-01-25 08:10:01,547:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22627.5', self.close='22636.9'
2023-01-25 08:10:01,574:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230125   072000    072959  1674602999  22534.9    22610
17469  20230125   073000    073959  1674603599  22611.6  22545.4
17470  20230125   074000    074959  1674604199  22540.6    22626
17471  20230125   075000    075959  1674604799  22623.5  22627.4
17472  20230125   080000    080959  1674605399  22627.5  22636.9
2023-01-25 08:10:01,574:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230125   074000    074959  1674604199  22540.6    22626
2023-01-25 07:50:00,673:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8744 

self.closeSec=1674604799, self.tradeDate='20230125', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22623.5', self.close='22627.4'
127.0.0.1 - - [25/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-25 08:00:02,017:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674604799, self.tradeDate='20230125', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22623.5', self.close='22627.4'
2023-01-25 08:00:02,043:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230125   071000    071959  1674602399  22671.5  22534.9
12140  20230125   072000    072959  1674602999  22534.9    22610
12141  20230125   073000    073959  1674603599  22611.6  22545.4
12142  20230125   074000    074959  1674604199  22540.6    22626
12143  20230125   075000    075959  1674604799  22623.5  22627.4
2023-01-25 08:00:02,043:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8745 

self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22627.5', self.close='22636.9'
2023-01-25 08:10:01,556:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22627.5', self.close='22636.9'
2023-01-25 08:10:01,562:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230125   072000    072959  1674602999  22534.9    22610
12141  20230125   073000    073959  1674603599  22611.6  22545.4
12142  20230125   074000    074959  1674604199  22540.6    22626
12143  20230125   075000    075959  1674604799  22623.5  22627.4
12144  20230125   080000    080959  1674605399  22627.5  22636.9
2023-01-25 08:10:01,562:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12920
self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22656.7, self.close=22636.9, self.high=22660.0, self.low=22608.4, self.vol=1785.04, self.amt=40402272.56 
127.0.0.1 - - [25/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-25 08:10:01,479:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230125   074500    074959  ...         0.0        0.0       0
5854  20230125   075000    075459  ...         0.0        0.0       0
5855  20230125   075500    075959  ...         0.0        0.0       0
5856  20230125   080000    080459  ...         0.0        0.0       0
5857  20230125   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 08:10:01,480:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674605399, self.tradeDate='20230125', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22656.7, self.close=22636.9, self.high=22660.0, self.low=22608.4, self.vol=1785.04, self.amt=40402272.56, ukdf['pct'].iloc[-1]=-0.00087 , ukdf['amount'].iloc[-1]=40402272.56, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [25/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12921
self.closeSec=1674605699, self.tradeDate='20230125', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22637.0, self.close=22632.4, self.high=22645.0, self.low=22602.7, self.vol=1200.329, self.amt=27160162.5124 
2023-01-25 08:15:00,755:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230125   075000    075459  ...         0.0        0.0       0
5855  20230125   075500    075959  ...         0.0        0.0       0
5856  20230125   080000    080459  ...         0.0        0.0       0
5857  20230125   080500    080959  ...         0.0        0.0       0
5858  20230125   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 08:15:00,755:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674605699, self.tradeDate='20230125', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22637.0, self.close=22632.4, self.high=22645.0, self.low=22602.7, self.vol=1200.329, self.amt=27160162.5124, ukdf['pct'].iloc[-1]=-0.000199 , ukdf['amount'].iloc[-1]=27160162.5124, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230124   200000    235959  1674575999  ...    719  0.566763 -0.712239    -1.0
720  20230125   000000    035959  1674590399  ...    720  0.332173 -1.263201    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-3764.7676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23017.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [25/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=364
self.closeSec=1674604799, self.tradeDate='20230125', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23015.1, self.close=22627.4, self.high=23073.6, self.low=22450.0, self.vol=141871.503, self.amt=3229600515.30948 
2023-01-25 08:00:01,866:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674604799, self.tradeDate='20230125', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23015.1, self.close=22627.4, self.high=23073.6, self.low=22450.0, self.vol=141871.503, self.amt=3229600515.30948 
2023-01-25 08:00:01,897:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230124   120000    155959  ...   37575.800  8.677053e+08 -0.001122
718  20230124   160000    195959  ...   80599.104  1.845843e+09 -0.006086
719  20230124   200000    235959  ...  126440.595  2.891896e+09  0.000524
720  20230125   000000    035959  ...   67270.843  1.543281e+09  0.003970
721  20230125   040000    075959  ...  141871.503  3.229601e+09 -0.016841

[5 rows x 11 columns]
2023-01-25 08:00:03,456:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230124   120000    155959  1674547199  ...    717  0.829119 -0.071439     NaN
718  20230124   160000    195959  1674561599  ...    718  0.749789 -0.268334     NaN
719  20230124   200000    235959  1674575999  ...    719  0.566763 -0.712239    -1.0
720  20230125   000000    035959  1674590399  ...    720  0.332173 -1.263201    -1.0
721  20230125   040000    075959  1674604799  ...    721  0.040427 -1.910773    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '12529.7476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22627.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


