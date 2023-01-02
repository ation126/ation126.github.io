# 20230102 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [02/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10298
self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16612.5, self.close=16609.9, self.high=16618.4, self.low=16608.5, self.vol=653.57, self.amt=10858220.7233 
2023-01-02 08:10:01,484:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230102   074500    074959  ...         0.0        0.0       0
5854  20230102   075000    075459  ...         0.0        0.0       0
5855  20230102   075500    075959  ...         0.0        0.0       0
5856  20230102   080000    080459  ...         0.0        0.0       0
5857  20230102   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 08:10:01,485:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16612.5, self.close=16609.9, self.high=16618.4, self.low=16608.5, self.vol=653.57, self.amt=10858220.7233, ukdf['pct'].iloc[-1]=-0.000157 , ukdf['amount'].iloc[-1]=10858220.7233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-4850.1856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16609.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10299
self.closeSec=1672618499, self.tradeDate='20230102', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16609.8, self.close=16604.2, self.high=16609.9, self.low=16602.0, self.vol=406.119, self.amt=6743790.3694 
127.0.0.1 - - [02/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-02 08:15:00,609:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230102   075000    075459  ...         0.0        0.0       0
5855  20230102   075500    075959  ...         0.0        0.0       0
5856  20230102   080000    080459  ...         0.0        0.0       0
5857  20230102   080500    080959  ...         0.0        0.0       0
5858  20230102   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 08:15:00,609:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672618499, self.tradeDate='20230102', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16609.8, self.close=16604.2, self.high=16609.9, self.low=16602.0, self.vol=406.119, self.amt=6743790.3694, ukdf['pct'].iloc[-1]=-0.000343 , ukdf['amount'].iloc[-1]=6743790.3694, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-4507.1824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16604.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16612.5, self.close=16609.9, self.high=16618.4, self.low=16608.5 
2023-01-02 08:10:01,434:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16612.5, self.close=16609.9, self.high=16618.4, self.low=16608.5   
127.0.0.1 - - [02/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-02 08:10:01,497:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230102   074500    074959  1672616999  ...  16594.7 -0.000241   1533    3
1534  20230102   075000    075459  1672617299  ...  16596.7  0.000331   1534    4
1535  20230102   075500    075959  1672617599  ...  16602.2  0.000488   1535    5
1536  20230102   080000    080459  1672617899  ...  16610.3  0.000126   1536    0
1537  20230102   080500    080959  1672618199  ...  16608.5 -0.000157   1537    1

[5 rows x 11 columns]
2023-01-02 08:10:01,506:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [02/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.42537664748083837, self.count=10865 

self.closeSec=1672618499, self.tradeDate='20230102', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16609.8, self.close=16604.2, self.high=16609.9, self.low=16602.0 
2023-01-02 08:15:00,508:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672618499, self.tradeDate='20230102', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16609.8, self.close=16604.2, self.high=16609.9, self.low=16602.0   
2023-01-02 08:15:00,575:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230102   075000    075459  1672617299  ...  16596.7  0.000331   1534    4
1535  20230102   075500    075959  1672617599  ...  16602.2  0.000488   1535    5
1536  20230102   080000    080459  1672617899  ...  16610.3  0.000126   1536    0
1537  20230102   080500    080959  1672618199  ...  16608.5 -0.000157   1537    1
1538  20230102   081000    081459  1672618499  ...  16602.0 -0.000343   1538    2

[5 rows x 11 columns]
2023-01-02 08:15:00,575:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

5774  20230102    072959  16594.4  ...  48.750000  0.535808  0.265390

[5 rows x 33 columns]
0.5046210720887245
acc is : 0.5046210720887245
2023-01-02 08:00:17,240:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     1  0.499666  0.500334       1  ...  NaN   NaN -0.0016  0.988305
537     1  0.497986  0.502014       0  ...  NaN   NaN -0.0016  0.987752
538     1  0.496325  0.503675       1  ...  NaN   NaN -0.0016  0.988115
539     1  0.498750  0.501250       1  ...  NaN   NaN -0.0016  0.988430
540     0  0.500654  0.499346       1  ...  NaN   NaN -0.0016  0.989062

[5 rows x 10 columns]
2023-01-02 08:00:17,251:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.499367  0.500633       1  ...  NaN   NaN -0.0016  0.984752
46     1  0.498014  0.501986       0  ...  NaN   NaN -0.0016  0.985850
47     1  0.496566  0.503434       1  ...  NaN   NaN -0.0016  0.989311
48     1  0.498750  0.501250       1  ...  NaN   NaN -0.0016  0.988430
49     0  0.500654  0.499346       1  ...  NaN   NaN -0.0016  0.989062

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-3874.3008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16610.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
Traceback (most recent call last):
  File "/root/FIL/strategy/logic/FIL_lib/client.py", line 95, in __start_handle
    handle_call(handle_data)
  File "main.py", line 431, in handleKline
    curSign = int(df_panel['sign'].iloc[-1])
ValueError: cannot convert float NaN to integer


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230102   074000    074959  1672616999    16601  16596.8 -0.000253
2023-01-02 07:50:00,573:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5431 

self.closeSec=1672617599, self.tradeDate='20230102', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16596.8', self.close='16610.9'
2023-01-02 08:00:00,911:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672617599, self.tradeDate='20230102', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16596.8', self.close='16610.9'
2023-01-02 08:00:00,955:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230102   071000    071959  1672615199  16606.9  16607.6  0.000193
620  20230102   072000    072959  1672615799  16607.9  16599.7 -0.000476
621  20230102   073000    073959  1672616399  16599.7    16601  0.000078
622  20230102   074000    074959  1672616999    16601  16596.8 -0.000253
623  20230102   075000    075959  1672617599  16596.8  16610.9  0.000850
2023-01-02 08:00:00,956:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5432 

self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16610.4', self.close='16609.9'
2023-01-02 08:10:01,543:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16610.4', self.close='16609.9'
2023-01-02 08:10:01,569:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230102   072000    072959  1672615799  16607.9  16599.7 -0.000476
621  20230102   073000    073959  1672616399  16599.7    16601  0.000078
622  20230102   074000    074959  1672616999    16601  16596.8 -0.000253
623  20230102   075000    075959  1672617599  16596.8  16610.9  0.000850
624  20230102   080000    080959  1672618199  16610.4  16609.9 -0.000060
2023-01-02 08:10:01,569:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230102   074000    074959  1672616999    16601  16596.8
2023-01-02 07:50:00,604:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5432 

self.closeSec=1672617599, self.tradeDate='20230102', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16596.8', self.close='16610.9'
2023-01-02 08:00:00,945:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672617599, self.tradeDate='20230102', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16596.8', self.close='16610.9'
2023-01-02 08:00:00,974:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230102   071000    071959  1672615199  16606.9  16607.6
17468  20230102   072000    072959  1672615799  16607.9  16599.7
17469  20230102   073000    073959  1672616399  16599.7    16601
17470  20230102   074000    074959  1672616999    16601  16596.8
17471  20230102   075000    075959  1672617599  16596.8  16610.9
2023-01-02 08:00:00,974:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5433 

self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16610.4', self.close='16609.9'
2023-01-02 08:10:01,567:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16610.4', self.close='16609.9'
127.0.0.1 - - [02/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-02 08:10:01,579:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230102   072000    072959  1672615799  16607.9  16599.7
17469  20230102   073000    073959  1672616399  16599.7    16601
17470  20230102   074000    074959  1672616999    16601  16596.8
17471  20230102   075000    075959  1672617599  16596.8  16610.9
17472  20230102   080000    080959  1672618199  16610.4  16609.9
2023-01-02 08:10:01,579:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230102   074000    074959  1672616999    16601  16596.8
2023-01-02 07:50:00,574:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5432 

self.closeSec=1672617599, self.tradeDate='20230102', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16596.8', self.close='16610.9'
127.0.0.1 - - [02/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-02 08:00:00,918:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672617599, self.tradeDate='20230102', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16596.8', self.close='16610.9'
2023-01-02 08:00:00,971:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230102   071000    071959  1672615199  16606.9  16607.6
12140  20230102   072000    072959  1672615799  16607.9  16599.7
12141  20230102   073000    073959  1672616399  16599.7    16601
12142  20230102   074000    074959  1672616999    16601  16596.8
12143  20230102   075000    075959  1672617599  16596.8  16610.9
2023-01-02 08:00:00,973:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5433 

self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16610.4', self.close='16609.9'
2023-01-02 08:10:01,519:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16610.4', self.close='16609.9'
127.0.0.1 - - [02/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-02 08:10:01,548:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230102   072000    072959  1672615799  16607.9  16599.7
12141  20230102   073000    073959  1672616399  16599.7    16601
12142  20230102   074000    074959  1672616999    16601  16596.8
12143  20230102   075000    075959  1672617599  16596.8  16610.9
12144  20230102   080000    080959  1672618199  16610.4  16609.9
2023-01-02 08:10:01,548:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6296
self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16612.5, self.close=16609.9, self.high=16618.4, self.low=16608.5, self.vol=653.57, self.amt=10858220.7233 
127.0.0.1 - - [02/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-02 08:10:01,528:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230102   074500    074959  ...         0.0        0.0       0
5854  20230102   075000    075459  ...         0.0        0.0       0
5855  20230102   075500    075959  ...         0.0        0.0       0
5856  20230102   080000    080459  ...         0.0        0.0       0
5857  20230102   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 08:10:01,529:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672618199, self.tradeDate='20230102', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16612.5, self.close=16609.9, self.high=16618.4, self.low=16608.5, self.vol=653.57, self.amt=10858220.7233, ukdf['pct'].iloc[-1]=-0.000157 , ukdf['amount'].iloc[-1]=10858220.7233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6297
self.closeSec=1672618499, self.tradeDate='20230102', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16609.8, self.close=16604.2, self.high=16609.9, self.low=16602.0, self.vol=406.119, self.amt=6743790.3694 
2023-01-02 08:15:00,577:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230102   075000    075459  ...         0.0        0.0       0
5855  20230102   075500    075959  ...         0.0        0.0       0
5856  20230102   080000    080459  ...         0.0        0.0       0
5857  20230102   080500    080959  ...         0.0        0.0       0
5858  20230102   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 08:15:00,578:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672618499, self.tradeDate='20230102', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16609.8, self.close=16604.2, self.high=16609.9, self.low=16602.0, self.vol=406.119, self.amt=6743790.3694, ukdf['pct'].iloc[-1]=-0.000343 , ukdf['amount'].iloc[-1]=6743790.3694, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230101   200000    235959  1672588799  ...    719  0.047921 -0.681075    -1.0
720  20230102   000000    035959  1672603199  ...    720  0.033879 -0.703794    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-1723.04', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16596.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [02/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891007.4496510001, self.flagDict['side']='sell', self.tradeCount=9, self.count=226
self.closeSec=1672617599, self.tradeDate='20230102', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16596.1, self.close=16610.9, self.high=16618.8, self.low=16579.1, self.vol=16635.812, self.amt=276152328.8793 
2023-01-02 08:00:00,789:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672617599, self.tradeDate='20230102', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16596.1, self.close=16610.9, self.high=16618.8, self.low=16579.1, self.vol=16635.812, self.amt=276152328.8793 
2023-01-02 08:00:00,833:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230101   120000    155959  ...  17998.501  2.972818e+08 -0.000587
718  20230101   160000    195959  ...  15117.276  2.498421e+08  0.001828
719  20230101   200000    235959  ...  15542.884  2.571605e+08  0.000199
720  20230102   000000    035959  ...  25971.333  4.306549e+08  0.002598
721  20230102   040000    075959  ...  16635.812  2.761523e+08  0.000892

[5 rows x 11 columns]
2023-01-02 08:00:02,493:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230101   120000    155959  1672559999  ...    717  0.076628 -0.635073    -1.0
718  20230101   160000    195959  1672574399  ...    718  0.069651 -0.637465    -1.0
719  20230101   200000    235959  1672588799  ...    719  0.047921 -0.681075    -1.0
720  20230102   000000    035959  1672603199  ...    720  0.033879 -0.703794    -1.0
721  20230102   040000    075959  1672617599  ...    721  0.028206 -0.703374    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-2487.639', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16610.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


