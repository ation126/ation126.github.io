# 20230101 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10010
self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16529.2, self.close=16521.5, self.high=16533.6, self.low=16519.0, self.vol=315.38, self.amt=5212211.4652 
127.0.0.1 - - [01/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 08:10:01,477:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230101   074500    074959  ...         0.0        0.0       0
5854  20230101   075000    075459  ...         0.0        0.0       0
5855  20230101   075500    075959  ...         0.0        0.0       0
5856  20230101   080000    080459  ...         0.0        0.0       0
5857  20230101   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 08:10:01,478:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16529.2, self.close=16521.5, self.high=16533.6, self.low=16519.0, self.vol=315.38, self.amt=5212211.4652, ukdf['pct'].iloc[-1]=-0.000472 , ukdf['amount'].iloc[-1]=5212211.4652, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '469.3728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16521.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10011
self.closeSec=1672532099, self.tradeDate='20230101', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16521.4, self.close=16517.8, self.high=16524.4, self.low=16517.4, self.vol=349.748, self.amt=5777919.1522 
127.0.0.1 - - [01/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-01 08:15:00,584:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230101   075000    075459  ...         0.0        0.0       0
5855  20230101   075500    075959  ...         0.0        0.0       0
5856  20230101   080000    080459  ...         0.0        0.0       0
5857  20230101   080500    080959  ...         0.0        0.0       0
5858  20230101   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 08:15:00,584:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672532099, self.tradeDate='20230101', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16521.4, self.close=16517.8, self.high=16524.4, self.low=16517.4, self.vol=349.748, self.amt=5777919.1522, ukdf['pct'].iloc[-1]=-0.000224 , ukdf['amount'].iloc[-1]=5777919.1522, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '716.0944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16517.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16529.2, self.close=16521.5, self.high=16533.6, self.low=16519.0 
2023-01-01 08:10:01,400:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16529.2, self.close=16521.5, self.high=16533.6, self.low=16519.0   
127.0.0.1 - - [01/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 08:10:01,412:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230101   074500    074959  1672530599  ...  16532.0 -0.000598   1533    3
1534  20230101   075000    075459  1672530899  ...  16530.5  0.000145   1534    4
1535  20230101   075500    075959  1672531199  ...  16530.2  0.000157   1535    5
1536  20230101   080000    080459  1672531499  ...  16523.0 -0.000502   1536    0
1537  20230101   080500    080959  1672531799  ...  16519.0 -0.000472   1537    1

[5 rows x 11 columns]
2023-01-01 08:10:01,412:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=67, self.factor=0.4694059798539491, self.count=10577 

self.closeSec=1672532099, self.tradeDate='20230101', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16521.4, self.close=16517.8, self.high=16524.4, self.low=16517.4 
2023-01-01 08:15:00,533:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672532099, self.tradeDate='20230101', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16521.4, self.close=16517.8, self.high=16524.4, self.low=16517.4   
2023-01-01 08:15:00,575:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230101   075000    075459  1672530899  ...  16530.5  0.000145   1534    4
1535  20230101   075500    075959  1672531199  ...  16530.2  0.000157   1535    5
1536  20230101   080000    080459  1672531499  ...  16523.0 -0.000502   1536    0
1537  20230101   080500    080959  1672531799  ...  16519.0 -0.000472   1537    1
1538  20230101   081000    081459  1672532099  ...  16517.4 -0.000224   1538    2

[5 rows x 11 columns]
2023-01-01 08:15:00,575:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

5774  20230101    072959  16515.1  ...  43.750000  0.462313  0.586398

[5 rows x 33 columns]
0.5046210720887245
acc is : 0.5046210720887245
2023-01-01 08:00:18,465:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     1  0.495687  0.504313       0  ...  NaN   NaN -0.0016  0.984381
537     1  0.491974  0.508026       0  ...  NaN   NaN -0.0016  0.984179
538     1  0.494119  0.505881       0  ...  NaN   NaN -0.0016  0.982656
539     1  0.486206  0.513794       1  ...  NaN   NaN -0.0016  0.983001
540     1  0.493709  0.506291       1  ...  NaN   NaN -0.0016  0.983994

[5 rows x 10 columns]
2023-01-01 08:00:18,484:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.495912  0.504088       0  ...  NaN   NaN -0.0016  0.978275
46     1  0.492467  0.507533       0  ...  NaN   NaN -0.0016  0.984947
47     1  0.493861  0.506139       0  ...  NaN   NaN -0.0016  0.981563
48     1  0.486635  0.513365       1  ...  NaN   NaN -0.0016  0.983001
49     1  0.493709  0.506291       1  ...  NaN   NaN -0.0016  0.983994

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-7097.90444472672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16534.60044101', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
Traceback (most recent call last):
  File "/root/FIL/strategy/logic/FIL_lib/client.py", line 95, in __start_handle
    handle_call(handle_data)
  File "main.py", line 431, in handleKline
    curSign = int(df_panel['sign'].iloc[-1])
ValueError: cannot convert float NaN to integer


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230101   074000    074959  1672530599    16542  16532.6 -0.000562
2023-01-01 07:50:00,632:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5287 

self.closeSec=1672531199, self.tradeDate='20230101', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16532.7', self.close='16537.6'
2023-01-01 08:00:00,847:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672531199, self.tradeDate='20230101', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16532.7', self.close='16537.6'
127.0.0.1 - - [01/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-01 08:00:00,876:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230101   071000    071959  1672528799  16490.1  16520.6  0.001850
620  20230101   072000    072959  1672529399  16520.6  16520.9  0.000018
621  20230101   073000    073959  1672529999  16520.9  16541.9  0.001271
622  20230101   074000    074959  1672530599    16542  16532.6 -0.000562
623  20230101   075000    075959  1672531199  16532.7  16537.6  0.000302
2023-01-01 08:00:00,876:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5288 

self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16537.5', self.close='16521.5'
2023-01-01 08:10:01,520:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16537.5', self.close='16521.5'
127.0.0.1 - - [01/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 08:10:01,546:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230101   072000    072959  1672529399  16520.6  16520.9  0.000018
621  20230101   073000    073959  1672529999  16520.9  16541.9  0.001271
622  20230101   074000    074959  1672530599    16542  16532.6 -0.000562
623  20230101   075000    075959  1672531199  16532.7  16537.6  0.000302
624  20230101   080000    080959  1672531799  16537.5  16521.5 -0.000974
2023-01-01 08:10:01,546:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230101   074000    074959  1672530599    16542  16532.6
2023-01-01 07:50:00,579:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5288 

self.closeSec=1672531199, self.tradeDate='20230101', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16532.7', self.close='16537.6'
127.0.0.1 - - [01/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-01 08:00:00,840:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672531199, self.tradeDate='20230101', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16532.7', self.close='16537.6'
2023-01-01 08:00:00,888:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230101   071000    071959  1672528799  16490.1  16520.6
17468  20230101   072000    072959  1672529399  16520.6  16520.9
17469  20230101   073000    073959  1672529999  16520.9  16541.9
17470  20230101   074000    074959  1672530599    16542  16532.6
17471  20230101   075000    075959  1672531199  16532.7  16537.6
2023-01-01 08:00:00,888:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5289 

self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16537.5', self.close='16521.5'
127.0.0.1 - - [01/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 08:10:01,535:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16537.5', self.close='16521.5'
2023-01-01 08:10:01,559:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230101   072000    072959  1672529399  16520.6  16520.9
17469  20230101   073000    073959  1672529999  16520.9  16541.9
17470  20230101   074000    074959  1672530599    16542  16532.6
17471  20230101   075000    075959  1672531199  16532.7  16537.6
17472  20230101   080000    080959  1672531799  16537.5  16521.5
2023-01-01 08:10:01,559:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230101   074000    074959  1672530599    16542  16532.6
2023-01-01 07:50:00,641:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5288 

self.closeSec=1672531199, self.tradeDate='20230101', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16532.7', self.close='16537.6'
2023-01-01 08:00:00,866:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672531199, self.tradeDate='20230101', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16532.7', self.close='16537.6'
2023-01-01 08:00:00,904:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230101   071000    071959  1672528799  16490.1  16520.6
12140  20230101   072000    072959  1672529399  16520.6  16520.9
12141  20230101   073000    073959  1672529999  16520.9  16541.9
12142  20230101   074000    074959  1672530599    16542  16532.6
12143  20230101   075000    075959  1672531199  16532.7  16537.6
2023-01-01 08:00:00,905:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5289 

self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16537.5', self.close='16521.5'
2023-01-01 08:10:01,544:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16537.5', self.close='16521.5'
127.0.0.1 - - [01/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 08:10:01,576:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230101   072000    072959  1672529399  16520.6  16520.9
12141  20230101   073000    073959  1672529999  16520.9  16541.9
12142  20230101   074000    074959  1672530599    16542  16532.6
12143  20230101   075000    075959  1672531199  16532.7  16537.6
12144  20230101   080000    080959  1672531799  16537.5  16521.5
2023-01-01 08:10:01,576:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [01/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6008
self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16529.2, self.close=16521.5, self.high=16533.6, self.low=16519.0, self.vol=315.38, self.amt=5212211.4652 
2023-01-01 08:10:01,503:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230101   074500    074959  ...         0.0        0.0       0
5854  20230101   075000    075459  ...         0.0        0.0       0
5855  20230101   075500    075959  ...         0.0        0.0       0
5856  20230101   080000    080459  ...         0.0        0.0       0
5857  20230101   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 08:10:01,506:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672531799, self.tradeDate='20230101', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16529.2, self.close=16521.5, self.high=16533.6, self.low=16519.0, self.vol=315.38, self.amt=5212211.4652, ukdf['pct'].iloc[-1]=-0.000472 , ukdf['amount'].iloc[-1]=5212211.4652, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6009
self.closeSec=1672532099, self.tradeDate='20230101', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16521.4, self.close=16517.8, self.high=16524.4, self.low=16517.4, self.vol=349.748, self.amt=5777919.1522 
127.0.0.1 - - [01/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-01 08:15:00,599:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230101   075000    075459  ...         0.0        0.0       0
5855  20230101   075500    075959  ...         0.0        0.0       0
5856  20230101   080000    080459  ...         0.0        0.0       0
5857  20230101   080500    080959  ...         0.0        0.0       0
5858  20230101   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 08:15:00,600:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672532099, self.tradeDate='20230101', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16521.4, self.close=16517.8, self.high=16524.4, self.low=16517.4, self.vol=349.748, self.amt=5777919.1522, ukdf['pct'].iloc[-1]=-0.000224 , ukdf['amount'].iloc[-1]=5777919.1522, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-01-01 04:00:09,622:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41450F1672516804294I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672516804392098, 'quantity': '53.898', 'price': '16564.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672516803739, 'updatetime': 1672516804392, 'tradetype': 'usdt', 'selfid': 41450, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672516804392, 'clientorderid': '41450F1672516804294I0L65', 'price': '16564.2', 'quantity': '53.898', 'commission': '892.7772516', 'commissionasset': 'USDT', 'tradetime': 1672516804392, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672516804392}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-01 04:00:09,623:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41450F1672516804294I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672516804392098, 'quantity': '53.898', 'price': '16564.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672516803739, 'updatetime': 1672516804392, 'tradetype': 'usdt', 'selfid': 41450, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672516804392, 'clientorderid': '41450F1672516804294I0L65', 'price': '16564.2', 'quantity': '53.898', 'commission': '892.7772516', 'commissionasset': 'USDT', 'tradetime': 1672516804392, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672516804392}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Jan/2023 04:00:09] "POST / HTTP/1.1" 200 -
2023-01-01 04:00:09,749:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41451F1672516809605I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672516809705740, 'quantity': '53.845', 'price': '16564.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672516809426, 'updatetime': 1672516809705, 'tradetype': 'usdt', 'selfid': 41451, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672516809705, 'clientorderid': '41451F1672516809605I0L65', 'price': '16564.2', 'quantity': '53.845', 'commission': '891.899349', 'commissionasset': 'USDT', 'tradetime': 1672516809705, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672516809705}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Jan/2023 04:00:09] "POST / HTTP/1.1" 200 -
2023-01-01 04:00:09,906:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41451F1672516809605I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672516809705740, 'quantity': '53.845', 'price': '16564.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672516809426, 'updatetime': 1672516809705, 'tradetype': 'usdt', 'selfid': 41451, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672516809705, 'clientorderid': '41451F1672516809605I0L65', 'price': '16564.2', 'quantity': '53.845', 'commission': '891.899349', 'commissionasset': 'USDT', 'tradetime': 1672516809705, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672516809705}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891007.4496510001, self.flagDict['side']='sell', self.tradeCount=9, self.count=220
self.closeSec=1672531199, self.tradeDate='20230101', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16564.3, self.close=16537.6, self.high=16569.7, self.low=16461.8, self.vol=31497.566, self.amt=520515184.0376 
2023-01-01 08:00:00,770:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672531199, self.tradeDate='20230101', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16564.3, self.close=16537.6, self.high=16569.7, self.low=16461.8, self.vol=31497.566, self.amt=520515184.0376 
2023-01-01 08:00:00,815:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221231   120000    155959  ...  15302.151  2.532091e+08  0.000925
718  20221231   160000    195959  ...  18890.316  3.128260e+08  0.000072
719  20221231   200000    235959  ...  37418.928  6.210058e+08  0.001231
720  20230101   000000    035959  ...  15398.520  2.553106e+08 -0.001308
721  20230101   040000    075959  ...  31497.566  5.205152e+08 -0.001612

[5 rows x 11 columns]
2023-01-01 08:00:02,164:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221231   120000    155959  1672473599  ...    717  0.374744  0.093364     NaN
718  20221231   160000    195959  1672487999  ...    718  0.314214 -0.059448     NaN
719  20221231   200000    235959  1672502399  ...    719  0.206195 -0.342355     NaN
720  20230101   000000    035959  1672516799  ...    720  0.095088 -0.632482    -1.0
721  20230101   040000    075959  1672531199  ...    721  0.088487 -0.635651    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '1432.277', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16537.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


