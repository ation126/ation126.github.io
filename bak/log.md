# 20230102 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [02/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10394
self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16715.9, self.close=16729.2, self.high=16731.6, self.low=16714.3, self.vol=1440.863, self.amt=24096880.5176 
2023-01-02 16:10:01,481:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230102   154500    154959  ...         0.0        0.0       0
5950  20230102   155000    155459  ...         0.0        0.0       0
5951  20230102   155500    155959  ...         0.0        0.0       0
5952  20230102   160000    160459  ...         0.0        0.0       0
5953  20230102   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 16:10:01,481:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16715.9, self.close=16729.2, self.high=16731.6, self.low=16714.3, self.vol=1440.863, self.amt=24096880.5176, ukdf['pct'].iloc[-1]=0.000802 , ukdf['amount'].iloc[-1]=24096880.5176, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-12029.1824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16729.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10395
self.closeSec=1672647299, self.tradeDate='20230102', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16729.2, self.close=16740.1, self.high=16745.0, self.low=16729.1, self.vol=1657.478, self.amt=27742226.1851 
127.0.0.1 - - [02/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-02 16:15:00,588:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230102   155000    155459  ...         0.0        0.0       0
5951  20230102   155500    155959  ...         0.0        0.0       0
5952  20230102   160000    160459  ...         0.0        0.0       0
5953  20230102   160500    160959  ...         0.0        0.0       0
5954  20230102   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 16:15:00,588:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672647299, self.tradeDate='20230102', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16729.2, self.close=16740.1, self.high=16745.0, self.low=16729.1, self.vol=1657.478, self.amt=27742226.1851, ukdf['pct'].iloc[-1]=0.000652 , ukdf['amount'].iloc[-1]=27742226.1851, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-12685.1008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16740.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.3836405385343954, self.count=10960 

self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16715.9, self.close=16729.2, self.high=16731.6, self.low=16714.3 
2023-01-02 16:10:01,428:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16715.9, self.close=16729.2, self.high=16731.6, self.low=16714.3   
2023-01-02 16:10:01,459:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230102   154500    154959  1672645799  ...  16714.5 -0.000586   1629    3
1630  20230102   155000    155459  1672646099  ...  16712.3 -0.000042   1630    4
1631  20230102   155500    155959  1672646399  ...  16710.1 -0.000377   1631    5
1632  20230102   160000    160459  1672646699  ...  16701.0  0.000191   1632    0
1633  20230102   160500    160959  1672646999  ...  16714.3  0.000802   1633    1

[5 rows x 11 columns]
2023-01-02 16:10:01,459:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.3836405385343954, self.count=10961 

self.closeSec=1672647299, self.tradeDate='20230102', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16729.2, self.close=16740.1, self.high=16745.0, self.low=16729.1 
2023-01-02 16:15:00,525:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672647299, self.tradeDate='20230102', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16729.2, self.close=16740.1, self.high=16745.0, self.low=16729.1   
127.0.0.1 - - [02/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-02 16:15:00,571:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230102   155000    155459  1672646099  ...  16712.3 -0.000042   1630    4
1631  20230102   155500    155959  1672646399  ...  16710.1 -0.000377   1631    5
1632  20230102   160000    160459  1672646699  ...  16701.0  0.000191   1632    0
1633  20230102   160500    160959  1672646999  ...  16714.3  0.000802   1633    1
1634  20230102   161000    161459  1672647299  ...  16729.1  0.000652   1634    2

[5 rows x 11 columns]
2023-01-02 16:15:00,571:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

5790  20230102    152959  16632.5  ...  49.166667  0.613262  0.303164

[5 rows x 33 columns]
0.507380073800738
acc is : 0.507380073800738
2023-01-02 16:00:18,348:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     0  0.501924  0.498076       1  ...  NaN   NaN -0.0016  0.987596
538     0  0.507765  0.492235       0  ...  NaN   NaN -0.0016  0.987590
539     1  0.497045  0.502955       0  ...  NaN   NaN -0.0016  0.987145
540     1  0.496320  0.503680       1  ...  NaN   NaN -0.0016  0.992700
541     0  0.527842  0.472158       0  ...  NaN   NaN -0.0016  0.991899

[5 rows x 10 columns]
2023-01-02 16:00:18,359:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.503291  0.496709       1  ...  NaN   NaN -0.0016  0.992941
46     0  0.508905  0.491095       0  ...  NaN   NaN -0.0016  0.992059
47     1  0.498097  0.501903       0  ...  NaN   NaN -0.0016  0.988770
48     1  0.496553  0.503447       1  ...  NaN   NaN -0.0016  0.994216
49     0  0.527842  0.472158       0  ...  NaN   NaN -0.0016  0.991899

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '401.7525343824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16710.94677705', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
Traceback (most recent call last):
  File "/root/FIL/strategy/logic/FIL_lib/client.py", line 95, in __start_handle
    handle_call(handle_data)
  File "main.py", line 431, in handleKline
    curSign = int(df_panel['sign'].iloc[-1])
ValueError: cannot convert float NaN to integer


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230102   154000    154959  1672645799  16749.8  16719.6 -0.001809
2023-01-02 15:50:00,542:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5479 

self.closeSec=1672646399, self.tradeDate='20230102', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16719.7', self.close='16712.6'
127.0.0.1 - - [02/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-02 16:00:01,283:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672646399, self.tradeDate='20230102', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16719.7', self.close='16712.6'
2023-01-02 16:00:01,311:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230102   151000    151959  1672643999  16635.1  16718.6  0.005013
524  20230102   152000    152959  1672644599  16719.1  16728.3  0.000580
525  20230102   153000    153959  1672645199  16728.4  16749.9  0.001291
526  20230102   154000    154959  1672645799  16749.8  16719.6 -0.001809
527  20230102   155000    155959  1672646399  16719.7  16712.6 -0.000419
2023-01-02 16:00:01,311:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5480 

self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16712.6', self.close='16729.2'
2023-01-02 16:10:01,512:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16712.6', self.close='16729.2'
127.0.0.1 - - [02/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-02 16:10:01,530:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230102   152000    152959  1672644599  16719.1  16728.3  0.000580
525  20230102   153000    153959  1672645199  16728.4  16749.9  0.001291
526  20230102   154000    154959  1672645799  16749.8  16719.6 -0.001809
527  20230102   155000    155959  1672646399  16719.7  16712.6 -0.000419
528  20230102   160000    160959  1672646999  16712.6  16729.2  0.000993
2023-01-02 16:10:01,530:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230102   154000    154959  1672645799  16749.8  16719.6
2023-01-02 15:50:00,550:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5480 

self.closeSec=1672646399, self.tradeDate='20230102', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16719.7', self.close='16712.6'
127.0.0.1 - - [02/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-02 16:00:01,304:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672646399, self.tradeDate='20230102', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16719.7', self.close='16712.6'
2023-01-02 16:00:01,330:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230102   151000    151959  1672643999  16635.1  16718.6
17516  20230102   152000    152959  1672644599  16719.1  16728.3
17517  20230102   153000    153959  1672645199  16728.4  16749.9
17518  20230102   154000    154959  1672645799  16749.8  16719.6
17519  20230102   155000    155959  1672646399  16719.7  16712.6
2023-01-02 16:00:01,330:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5481 

self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16712.6', self.close='16729.2'
2023-01-02 16:10:01,537:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16712.6', self.close='16729.2'
2023-01-02 16:10:01,560:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230102   152000    152959  1672644599  16719.1  16728.3
17517  20230102   153000    153959  1672645199  16728.4  16749.9
17518  20230102   154000    154959  1672645799  16749.8  16719.6
17519  20230102   155000    155959  1672646399  16719.7  16712.6
17520  20230102   160000    160959  1672646999  16712.6  16729.2
2023-01-02 16:10:01,561:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230102   154000    154959  1672645799  16749.8  16719.6
2023-01-02 15:50:00,544:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [02/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5480 

self.closeSec=1672646399, self.tradeDate='20230102', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16719.7', self.close='16712.6'
2023-01-02 16:00:01,275:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672646399, self.tradeDate='20230102', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16719.7', self.close='16712.6'
2023-01-02 16:00:01,322:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230102   151000    151959  1672643999  16635.1  16718.6
12188  20230102   152000    152959  1672644599  16719.1  16728.3
12189  20230102   153000    153959  1672645199  16728.4  16749.9
12190  20230102   154000    154959  1672645799  16749.8  16719.6
12191  20230102   155000    155959  1672646399  16719.7  16712.6
2023-01-02 16:00:01,322:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [02/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5481 

self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16712.6', self.close='16729.2'
2023-01-02 16:10:01,525:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16712.6', self.close='16729.2'
2023-01-02 16:10:01,543:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230102   152000    152959  1672644599  16719.1  16728.3
12189  20230102   153000    153959  1672645199  16728.4  16749.9
12190  20230102   154000    154959  1672645799  16749.8  16719.6
12191  20230102   155000    155959  1672646399  16719.7  16712.6
12192  20230102   160000    160959  1672646999  16712.6  16729.2
2023-01-02 16:10:01,544:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [02/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6392
self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16715.9, self.close=16729.2, self.high=16731.6, self.low=16714.3, self.vol=1440.863, self.amt=24096880.5176 
2023-01-02 16:10:01,479:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230102   154500    154959  ...         0.0        0.0       0
5950  20230102   155000    155459  ...         0.0        0.0       0
5951  20230102   155500    155959  ...         0.0        0.0       0
5952  20230102   160000    160459  ...         0.0        0.0       0
5953  20230102   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 16:10:01,479:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672646999, self.tradeDate='20230102', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16715.9, self.close=16729.2, self.high=16731.6, self.low=16714.3, self.vol=1440.863, self.amt=24096880.5176, ukdf['pct'].iloc[-1]=0.000802 , ukdf['amount'].iloc[-1]=24096880.5176, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6393
self.closeSec=1672647299, self.tradeDate='20230102', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16729.2, self.close=16740.1, self.high=16745.0, self.low=16729.1, self.vol=1657.478, self.amt=27742226.1851 
2023-01-02 16:15:00,593:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230102   155000    155459  ...         0.0        0.0       0
5951  20230102   155500    155959  ...         0.0        0.0       0
5952  20230102   160000    160459  ...         0.0        0.0       0
5953  20230102   160500    160959  ...         0.0        0.0       0
5954  20230102   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-02 16:15:00,593:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672647299, self.tradeDate='20230102', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16729.2, self.close=16740.1, self.high=16745.0, self.low=16729.1, self.vol=1657.478, self.amt=27742226.1851, ukdf['pct'].iloc[-1]=0.000652 , ukdf['amount'].iloc[-1]=27742226.1851, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230102   040000    075959  1672617599  ...    721  0.028206 -0.703374    -1.0
722  20230102   080000    115959  1672631999  ...    722  0.036558 -0.662826    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-4942.971', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16656', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [02/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891007.4496510001, self.flagDict['side']='sell', self.tradeCount=9, self.count=228
self.closeSec=1672646399, self.tradeDate='20230102', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16654.7, self.close=16712.6, self.high=16767.8, self.low=16612.8, self.vol=53334.962, self.amt=890111091.78344 
2023-01-02 16:00:01,156:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672646399, self.tradeDate='20230102', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16654.7, self.close=16712.6, self.high=16767.8, self.low=16612.8, self.vol=53334.962, self.amt=890111091.78344 
2023-01-02 16:00:01,192:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230101   200000    235959  ...  15542.884  2.571605e+08  0.000199
720  20230102   000000    035959  ...  25971.333  4.306549e+08  0.002598
721  20230102   040000    075959  ...  16635.812  2.761523e+08  0.000892
722  20230102   080000    115959  ...  36634.472  6.085019e+08  0.002637
723  20230102   120000    155959  ...  53334.962  8.901111e+08  0.003476

[5 rows x 11 columns]
2023-01-02 16:00:02,547:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230101   200000    235959  1672588799  ...    719  0.047921 -0.681075    -1.0
720  20230102   000000    035959  1672603199  ...    720  0.033879 -0.703794    -1.0
721  20230102   040000    075959  1672617599  ...    721  0.028206 -0.703374    -1.0
722  20230102   080000    115959  1672631999  ...    722  0.036558 -0.662826    -1.0
723  20230102   120000    155959  1672646399  ...    723  0.081884 -0.510533     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-7985.2135', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16712.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


