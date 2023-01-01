# 20230101 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [01/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10106
self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16524.9, self.close=16513.7, self.high=16524.9, self.low=16511.7, self.vol=704.072, self.amt=11629289.2269 
2023-01-01 16:10:01,493:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230101   154500    154959  ...         0.0        0.0       0
5950  20230101   155000    155459  ...         0.0        0.0       0
5951  20230101   155500    155959  ...         0.0        0.0       0
5952  20230101   160000    160459  ...         0.0        0.0       0
5953  20230101   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 16:10:01,493:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16524.9, self.close=16513.7, self.high=16524.9, self.low=16511.7, self.vol=704.072, self.amt=11629289.2269, ukdf['pct'].iloc[-1]=-0.000678 , ukdf['amount'].iloc[-1]=11629289.2269, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '906.63298931168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16514.23364482', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10107
self.closeSec=1672560899, self.tradeDate='20230101', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16513.7, self.close=16510.3, self.high=16513.7, self.low=16510.3, self.vol=205.636, self.amt=3395513.1738 
2023-01-01 16:15:00,630:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230101   155000    155459  ...         0.0        0.0       0
5951  20230101   155500    155959  ...         0.0        0.0       0
5952  20230101   160000    160459  ...         0.0        0.0       0
5953  20230101   160500    160959  ...         0.0        0.0       0
5954  20230101   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 16:15:00,631:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672560899, self.tradeDate='20230101', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16513.7, self.close=16510.3, self.high=16513.7, self.low=16510.3, self.vol=205.636, self.amt=3395513.1738, ukdf['pct'].iloc[-1]=-0.000206 , ukdf['amount'].iloc[-1]=3395513.1738, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '1137.3264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16510.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=83, self.factor=0.5839072313355582, self.count=10672 

self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16524.9, self.close=16513.7, self.high=16524.9, self.low=16511.7 
2023-01-01 16:10:01,429:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16524.9, self.close=16513.7, self.high=16524.9, self.low=16511.7   
2023-01-01 16:10:01,481:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230101   154500    154959  1672559399  ...  16519.1  0.000024   1629    3
1630  20230101   155000    155459  1672559699  ...  16514.6 -0.000309   1630    4
1631  20230101   155500    155959  1672559999  ...  16515.4  0.000242   1631    5
1632  20230101   160000    160459  1672560299  ...  16519.5  0.000327   1632    0
1633  20230101   160500    160959  1672560599  ...  16511.7 -0.000678   1633    1

[5 rows x 11 columns]
2023-01-01 16:10:01,481:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=83, self.factor=0.5839072313355582, self.count=10673 

self.closeSec=1672560899, self.tradeDate='20230101', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16513.7, self.close=16510.3, self.high=16513.7, self.low=16510.3 
2023-01-01 16:15:00,546:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672560899, self.tradeDate='20230101', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16513.7, self.close=16510.3, self.high=16513.7, self.low=16510.3   
2023-01-01 16:15:00,593:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230101   155000    155459  1672559699  ...  16514.6 -0.000309   1630    4
1631  20230101   155500    155959  1672559999  ...  16515.4  0.000242   1631    5
1632  20230101   160000    160459  1672560299  ...  16519.5  0.000327   1632    0
1633  20230101   160500    160959  1672560599  ...  16511.7 -0.000678   1633    1
1634  20230101   161000    161459  1672560899  ...  16510.3 -0.000206   1634    2

[5 rows x 11 columns]
2023-01-01 16:15:00,593:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

5790  20230101    152959  16535.3  ...  45.416667  0.463039  0.609267

[5 rows x 33 columns]
0.5129151291512916
acc is : 0.5129151291512916
2023-01-01 16:00:17,717:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     1  0.493742  0.506258       1  ...  NaN   NaN -0.0016  0.981657
538     1  0.499458  0.500542       1  ...  NaN   NaN -0.0016  0.982524
539     0  0.501564  0.498436       0  ...  NaN   NaN -0.0016  0.982227
540     1  0.498626  0.501374       0  ...  NaN   NaN -0.0016  0.980980
541     1  0.492175  0.507825       1  ...  NaN   NaN -0.0016  0.981294

[5 rows x 10 columns]
2023-01-01 16:00:17,735:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.493746  0.506254       1  ...  NaN   NaN -0.0016  0.980044
46     1  0.499209  0.500791       1  ...  NaN   NaN -0.0016  0.978345
47     0  0.501545  0.498455       0  ...  NaN   NaN -0.0016  0.979162
48     1  0.498889  0.501111       0  ...  NaN   NaN -0.0016  0.978440
49     1  0.492175  0.507825       1  ...  NaN   NaN -0.0016  0.981294

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-7734.96080609088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16519.62074854', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
Traceback (most recent call last):
  File "/root/FIL/strategy/logic/FIL_lib/client.py", line 95, in __start_handle
    handle_call(handle_data)
  File "main.py", line 431, in handleKline
    curSign = int(df_panel['sign'].iloc[-1])
ValueError: cannot convert float NaN to integer


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230101   154000    154959  1672559399  16514.2  16520.6  0.000388
2023-01-01 15:50:00,589:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5335 

self.closeSec=1672559999, self.tradeDate='20230101', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16520.6', self.close='16519.5'
2023-01-01 16:00:00,853:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672559999, self.tradeDate='20230101', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16520.6', self.close='16519.5'
2023-01-01 16:00:00,898:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230101   151000    151959  1672557599    16528  16499.9 -0.001700
524  20230101   152000    152959  1672558199  16499.9  16514.3  0.000873
525  20230101   153000    153959  1672558799  16514.3  16514.2 -0.000006
526  20230101   154000    154959  1672559399  16514.2  16520.6  0.000388
527  20230101   155000    155959  1672559999  16520.6  16519.5 -0.000067
2023-01-01 16:00:00,898:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5336 

self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16519.5', self.close='16513.7'
2023-01-01 16:10:01,544:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16519.5', self.close='16513.7'
2023-01-01 16:10:01,583:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230101   152000    152959  1672558199  16499.9  16514.3  0.000873
525  20230101   153000    153959  1672558799  16514.3  16514.2 -0.000006
526  20230101   154000    154959  1672559399  16514.2  16520.6  0.000388
527  20230101   155000    155959  1672559999  16520.6  16519.5 -0.000067
528  20230101   160000    160959  1672560599  16519.5  16513.7 -0.000351
2023-01-01 16:10:01,584:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230101   154000    154959  1672559399  16514.2  16520.6
2023-01-01 15:50:00,595:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5336 

self.closeSec=1672559999, self.tradeDate='20230101', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16520.6', self.close='16519.5'
127.0.0.1 - - [01/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-01 16:00:00,885:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672559999, self.tradeDate='20230101', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16520.6', self.close='16519.5'
2023-01-01 16:00:00,955:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230101   151000    151959  1672557599    16528  16499.9
17516  20230101   152000    152959  1672558199  16499.9  16514.3
17517  20230101   153000    153959  1672558799  16514.3  16514.2
17518  20230101   154000    154959  1672559399  16514.2  16520.6
17519  20230101   155000    155959  1672559999  16520.6  16519.5
2023-01-01 16:00:00,955:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5337 

self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16519.5', self.close='16513.7'
127.0.0.1 - - [01/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 16:10:01,538:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16519.5', self.close='16513.7'
2023-01-01 16:10:01,598:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230101   152000    152959  1672558199  16499.9  16514.3
17517  20230101   153000    153959  1672558799  16514.3  16514.2
17518  20230101   154000    154959  1672559399  16514.2  16520.6
17519  20230101   155000    155959  1672559999  16520.6  16519.5
17520  20230101   160000    160959  1672560599  16519.5  16513.7
2023-01-01 16:10:01,598:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230101   154000    154959  1672559399  16514.2  16520.6
2023-01-01 15:50:00,549:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5336 

self.closeSec=1672559999, self.tradeDate='20230101', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16520.6', self.close='16519.5'
2023-01-01 16:00:00,861:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672559999, self.tradeDate='20230101', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16520.6', self.close='16519.5'
2023-01-01 16:00:00,947:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230101   151000    151959  1672557599    16528  16499.9
12188  20230101   152000    152959  1672558199  16499.9  16514.3
12189  20230101   153000    153959  1672558799  16514.3  16514.2
12190  20230101   154000    154959  1672559399  16514.2  16520.6
12191  20230101   155000    155959  1672559999  16520.6  16519.5
2023-01-01 16:00:00,947:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5337 

self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16519.5', self.close='16513.7'
2023-01-01 16:10:01,550:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16519.5', self.close='16513.7'
2023-01-01 16:10:01,597:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230101   152000    152959  1672558199  16499.9  16514.3
12189  20230101   153000    153959  1672558799  16514.3  16514.2
12190  20230101   154000    154959  1672559399  16514.2  16520.6
12191  20230101   155000    155959  1672559999  16520.6  16519.5
12192  20230101   160000    160959  1672560599  16519.5  16513.7
2023-01-01 16:10:01,597:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6104
self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16524.9, self.close=16513.7, self.high=16524.9, self.low=16511.7, self.vol=704.072, self.amt=11629289.2269 
127.0.0.1 - - [01/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-01 16:10:01,623:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230101   154500    154959  ...         0.0        0.0       0
5950  20230101   155000    155459  ...         0.0        0.0       0
5951  20230101   155500    155959  ...         0.0        0.0       0
5952  20230101   160000    160459  ...         0.0        0.0       0
5953  20230101   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 16:10:01,623:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672560599, self.tradeDate='20230101', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16524.9, self.close=16513.7, self.high=16524.9, self.low=16511.7, self.vol=704.072, self.amt=11629289.2269, ukdf['pct'].iloc[-1]=-0.000678 , ukdf['amount'].iloc[-1]=11629289.2269, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6105
self.closeSec=1672560899, self.tradeDate='20230101', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16513.7, self.close=16510.3, self.high=16513.7, self.low=16510.3, self.vol=205.636, self.amt=3395513.1738 
2023-01-01 16:15:00,620:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230101   155000    155459  ...         0.0        0.0       0
5951  20230101   155500    155959  ...         0.0        0.0       0
5952  20230101   160000    160459  ...         0.0        0.0       0
5953  20230101   160500    160959  ...         0.0        0.0       0
5954  20230101   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-01 16:15:00,621:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672560899, self.tradeDate='20230101', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16513.7, self.close=16510.3, self.high=16513.7, self.low=16510.3, self.vol=205.636, self.amt=3395513.1738, ukdf['pct'].iloc[-1]=-0.000206 , ukdf['amount'].iloc[-1]=3395513.1738, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230101   040000    075959  1672531199  ...    721  0.088487 -0.635651    -1.0
722  20230101   080000    115959  1672545599  ...    722  0.069158 -0.672480    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '1864.91025301185', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16529.56521027', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [01/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891007.4496510001, self.flagDict['side']='sell', self.tradeCount=9, self.count=222
self.closeSec=1672559999, self.tradeDate='20230101', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16529.2, self.close=16519.6, self.high=16545.7, self.low=16488.0, self.vol=17998.501, self.amt=297281833.1213 
2023-01-01 16:00:00,745:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672559999, self.tradeDate='20230101', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16529.2, self.close=16519.6, self.high=16545.7, self.low=16488.0, self.vol=17998.501, self.amt=297281833.1213 
2023-01-01 16:00:00,824:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221231   200000    235959  ...  37418.928  6.210058e+08  0.001231
720  20230101   000000    035959  ...  15398.520  2.553106e+08 -0.001308
721  20230101   040000    075959  ...  31497.566  5.205152e+08 -0.001612
722  20230101   080000    115959  ...  14204.791  2.348208e+08 -0.000502
723  20230101   120000    155959  ...  17998.501  2.972818e+08 -0.000587

[5 rows x 11 columns]
2023-01-01 16:00:02,576:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221231   200000    235959  1672502399  ...    719  0.206195 -0.342355     NaN
720  20230101   000000    035959  1672516799  ...    720  0.095088 -0.632482    -1.0
721  20230101   040000    075959  1672531199  ...    721  0.088487 -0.635651    -1.0
722  20230101   080000    115959  1672545599  ...    722  0.069158 -0.672480    -1.0
723  20230101   120000    155959  1672559999  ...    723  0.076628 -0.635073    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '2401.487', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16519.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


