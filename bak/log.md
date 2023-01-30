# 20230130 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [30/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18362
self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23752.4, self.close=23791.8, self.high=23799.8, self.low=23737.5, self.vol=1941.951, self.amt=46172456.6737 
2023-01-30 08:10:01,484:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230130   074500    074959  ...         0.0        0.0       0
5854  20230130   075000    075459  ...         0.0        0.0       0
5855  20230130   075500    075959  ...         0.0        0.0       0
5856  20230130   080000    080459  ...         0.0        0.0       0
5857  20230130   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 08:10:01,485:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23752.4, self.close=23791.8, self.high=23799.8, self.low=23737.5, self.vol=1941.951, self.amt=46172456.6737, ukdf['pct'].iloc[-1]=0.001659 , ukdf['amount'].iloc[-1]=46172456.6737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-436873.20428024016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23789.22429341', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18363
self.closeSec=1675037699, self.tradeDate='20230130', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23791.7, self.close=23777.9, self.high=23804.6, self.low=23771.3, self.vol=1062.177, self.amt=25269482.0462 
127.0.0.1 - - [30/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-30 08:15:00,907:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230130   075000    075459  ...         0.0        0.0       0
5855  20230130   075500    075959  ...         0.0        0.0       0
5856  20230130   080000    080459  ...         0.0        0.0       0
5857  20230130   080500    080959  ...         0.0        0.0       0
5858  20230130   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 08:15:00,907:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675037699, self.tradeDate='20230130', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23791.7, self.close=23777.9, self.high=23804.6, self.low=23771.3, self.vol=1062.177, self.amt=25269482.0462, ukdf['pct'].iloc[-1]=-0.000584 , ukdf['amount'].iloc[-1]=25269482.0462, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-435985.66484628192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23774.47523342', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23752.4, self.close=23791.8, self.high=23799.8, self.low=23737.5 
2023-01-30 08:10:01,423:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23752.4, self.close=23791.8, self.high=23799.8, self.low=23737.5   
127.0.0.1 - - [30/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-30 08:10:01,461:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230130   074500    074959  1675036199  ...  23744.0  0.000371   1533    3
1534  20230130   075000    075459  1675036499  ...  23751.1  0.001128   1534    4
1535  20230130   075500    075959  1675036799  ...  23740.2 -0.001783   1535    5
1536  20230130   080000    080459  1675037099  ...  23718.0  0.000510   1536    0
1537  20230130   080500    080959  1675037399  ...  23737.5  0.001659   1537    1

[5 rows x 11 columns]
2023-01-30 08:10:01,464:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=445, self.factor=0.30162616263228126, self.count=18929 

self.closeSec=1675037699, self.tradeDate='20230130', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23791.7, self.close=23777.9, self.high=23804.6, self.low=23771.3 
2023-01-30 08:15:00,836:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675037699, self.tradeDate='20230130', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23791.7, self.close=23777.9, self.high=23804.6, self.low=23771.3   
2023-01-30 08:15:00,891:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230130   075000    075459  1675036499  ...  23751.1  0.001128   1534    4
1535  20230130   075500    075959  1675036799  ...  23740.2 -0.001783   1535    5
1536  20230130   080000    080459  1675037099  ...  23718.0  0.000510   1536    0
1537  20230130   080500    080959  1675037399  ...  23737.5  0.001659   1537    1
1538  20230130   081000    081459  1675037699  ...  23771.3 -0.000584   1538    2

[5 rows x 11 columns]
2023-01-30 08:15:00,891:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-30 08:00:17,831:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230130    052959  23701.0  ...  53.750000  0.605288  0.245221
5771  20230130    055959  23752.7  ...  54.166667  0.612454  0.241099
5772  20230130    062959  23795.8  ...  54.166667  0.608323  0.238519
5773  20230130    065959  23780.0  ...  53.750000  0.606579  0.237287
5774  20230130    072959  23773.4  ...  53.750000  0.601910  0.238158

[5 rows x 33 columns]
0.5378927911275416
acc is : 0.5378927911275416
2023-01-30 08:00:17,937:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.529239  0.470761       1  ...  1.018224   1.0    0.0  1.137189
537     0  0.520712  0.479288       0  ...  1.017548   1.0    0.0  1.136434
538     0  0.505043  0.494957       0  ...  1.017266   1.0    0.0  1.136119
539     0  0.512262  0.487738       0  ...  1.016517   1.0    0.0  1.135283
540     0  0.516052  0.483948       0  ...  1.015849   1.0    0.0  1.134537

[5 rows x 10 columns]
2023-01-30 08:00:17,962:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.529668  0.470332       1  ...  1.025095   1.0    0.0  1.131216
46     0  0.522067  0.477933       0  ...  1.006877   1.0    0.0  1.150454
47     0  0.505968  0.494032       0  ...  1.017266   1.0    0.0  1.140134
48     0  0.512262  0.487738       0  ...  1.016517   1.0    0.0  1.135283
49     0  0.516052  0.483948       0  ...  1.015849   1.0    0.0  1.134537

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.8', 'enterprice': '23035.8', 'countrevence': '0', 'unrealprofit': '21806.376885832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23743.79924954', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230130   074000    074959  1675036199  23784.4  23755.9 -0.001186
2023-01-30 07:50:00,581:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9463 

self.closeSec=1675036799, self.tradeDate='20230130', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23755.9', self.close='23740.3'
127.0.0.1 - - [30/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-30 08:00:01,817:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675036799, self.tradeDate='20230130', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23755.9', self.close='23740.3'
2023-01-30 08:00:01,832:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230130   071000    071959  1675034399    23859  23850.5 -0.000360
620  20230130   072000    072959  1675034999  23850.4  23755.9 -0.003966
621  20230130   073000    073959  1675035599  23753.8  23784.1  0.001187
622  20230130   074000    074959  1675036199  23784.4  23755.9 -0.001186
623  20230130   075000    075959  1675036799  23755.9  23740.3 -0.000657
2023-01-30 08:00:01,832:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9464 

self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23740.2', self.close='23791.8'
2023-01-30 08:10:01,708:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23740.2', self.close='23791.8'
2023-01-30 08:10:01,726:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230130   072000    072959  1675034999  23850.4  23755.9 -0.003966
621  20230130   073000    073959  1675035599  23753.8  23784.1  0.001187
622  20230130   074000    074959  1675036199  23784.4  23755.9 -0.001186
623  20230130   075000    075959  1675036799  23755.9  23740.3 -0.000657
624  20230130   080000    080959  1675037399  23740.2  23791.8  0.002169
2023-01-30 08:10:01,726:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230130   074000    074959  1675036199  23784.4  23755.9
2023-01-30 07:50:00,582:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9464 

self.closeSec=1675036799, self.tradeDate='20230130', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23755.9', self.close='23740.3'
127.0.0.1 - - [30/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-30 08:00:01,827:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675036799, self.tradeDate='20230130', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23755.9', self.close='23740.3'
2023-01-30 08:00:01,841:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230130   071000    071959  1675034399    23859  23850.5
17468  20230130   072000    072959  1675034999  23850.4  23755.9
17469  20230130   073000    073959  1675035599  23753.8  23784.1
17470  20230130   074000    074959  1675036199  23784.4  23755.9
17471  20230130   075000    075959  1675036799  23755.9  23740.3
2023-01-30 08:00:01,841:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9465 

self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23740.2', self.close='23791.8'
2023-01-30 08:10:01,721:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23740.2', self.close='23791.8'
127.0.0.1 - - [30/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-30 08:10:01,731:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230130   072000    072959  1675034999  23850.4  23755.9
17469  20230130   073000    073959  1675035599  23753.8  23784.1
17470  20230130   074000    074959  1675036199  23784.4  23755.9
17471  20230130   075000    075959  1675036799  23755.9  23740.3
17472  20230130   080000    080959  1675037399  23740.2  23791.8
2023-01-30 08:10:01,731:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230130   074000    074959  1675036199  23784.4  23755.9
2023-01-30 07:50:00,614:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9464 

self.closeSec=1675036799, self.tradeDate='20230130', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23755.9', self.close='23740.3'
127.0.0.1 - - [30/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-30 08:00:01,809:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675036799, self.tradeDate='20230130', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23755.9', self.close='23740.3'
2023-01-30 08:00:01,848:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230130   071000    071959  1675034399    23859  23850.5
12140  20230130   072000    072959  1675034999  23850.4  23755.9
12141  20230130   073000    073959  1675035599  23753.8  23784.1
12142  20230130   074000    074959  1675036199  23784.4  23755.9
12143  20230130   075000    075959  1675036799  23755.9  23740.3
2023-01-30 08:00:01,848:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9465 

self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23740.2', self.close='23791.8'
127.0.0.1 - - [30/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-30 08:10:01,730:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23740.2', self.close='23791.8'
2023-01-30 08:10:01,745:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230130   072000    072959  1675034999  23850.4  23755.9
12141  20230130   073000    073959  1675035599  23753.8  23784.1
12142  20230130   074000    074959  1675036199  23784.4  23755.9
12143  20230130   075000    075959  1675036799  23755.9  23740.3
12144  20230130   080000    080959  1675037399  23740.2  23791.8
2023-01-30 08:10:01,745:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [30/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14360
self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23752.4, self.close=23791.8, self.high=23799.8, self.low=23737.5, self.vol=1941.951, self.amt=46172456.6737 
2023-01-30 08:10:01,484:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230130   074500    074959  ...         0.0        0.0       0
5854  20230130   075000    075459  ...         0.0        0.0       0
5855  20230130   075500    075959  ...         0.0        0.0       0
5856  20230130   080000    080459  ...         0.0        0.0       0
5857  20230130   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 08:10:01,485:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675037399, self.tradeDate='20230130', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23752.4, self.close=23791.8, self.high=23799.8, self.low=23737.5, self.vol=1941.951, self.amt=46172456.6737, ukdf['pct'].iloc[-1]=0.001659 , ukdf['amount'].iloc[-1]=46172456.6737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [30/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14361
self.closeSec=1675037699, self.tradeDate='20230130', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23791.7, self.close=23777.9, self.high=23804.6, self.low=23771.3, self.vol=1062.177, self.amt=25269482.0462 
2023-01-30 08:15:00,914:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230130   075000    075459  ...         0.0        0.0       0
5855  20230130   075500    075959  ...         0.0        0.0       0
5856  20230130   080000    080459  ...         0.0        0.0       0
5857  20230130   080500    080959  ...         0.0        0.0       0
5858  20230130   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 08:15:00,914:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675037699, self.tradeDate='20230130', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23791.7, self.close=23777.9, self.high=23804.6, self.low=23771.3, self.vol=1062.177, self.amt=25269482.0462, ukdf['pct'].iloc[-1]=-0.000584 , ukdf['amount'].iloc[-1]=25269482.0462, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230129   200000    235959  1675007999  ...    719  0.200960 -0.816995    -1.0
720  20230130   000000    035959  1675022399  ...    720  0.333661 -0.460132     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-40600.6593965046', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23900.4504767', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [30/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=394
self.closeSec=1675036799, self.tradeDate='20230130', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23896.5, self.close=23740.3, self.high=23910.1, self.low=23600.0, self.vol=71846.477, self.amt=1708220208.3976 
2023-01-30 08:00:01,655:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675036799, self.tradeDate='20230130', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23896.5, self.close=23740.3, self.high=23910.1, self.low=23600.0, self.vol=71846.477, self.amt=1708220208.3976 
2023-01-30 08:00:01,679:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230129   120000    155959  ...   26823.648  6.224532e+08  0.000448
718  20230129   160000    195959  ...  114678.629  2.680838e+09  0.009896
719  20230129   200000    235959  ...   88615.332  2.084092e+09  0.003956
720  20230130   000000    035959  ...  134522.960  3.190306e+09  0.015895
721  20230130   040000    075959  ...   71846.477  1.708220e+09 -0.006541

[5 rows x 11 columns]
2023-01-30 08:00:03,123:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230129   120000    155959  1674979199  ...    717  0.154466 -0.965586    -1.0
718  20230129   160000    195959  1674993599  ...    718  0.191412 -0.857409    -1.0
719  20230129   200000    235959  1675007999  ...    719  0.200960 -0.816995    -1.0
720  20230130   000000    035959  1675022399  ...    720  0.333661 -0.460132     NaN
721  20230130   040000    075959  1675036799  ...    721  0.355328 -0.386449     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-34044.04328228164', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23743.36062778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


