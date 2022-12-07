# 20221207 11:45:48
/root/FIL/strategy/amihud/log.txt
127.0.0.1 - - [07/Dec/2022 11:40:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2852
self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113500', self.closeTime='113959', self.symbol='BTCUSDT', self.open=17014.8, self.close=17022.6, self.high=17024.8, self.low=17014.8, self.vol=597.47, self.amt=10169708.2532 
2022-12-07 11:40:01,450:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5895  20221207   111500    111959  ...    0.166192   0.297375       0
5896  20221207   112000    112459  ...    0.165997   0.297253       0
5897  20221207   112500    112959  ...    0.165802   0.297132       0
5898  20221207   113000    113459  ...    0.165607   0.297010       0
5899  20221207   113500    113959  ...    0.165412   0.296888       0

[5 rows x 18 columns]
2022-12-07 11:40:01,450:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113500', self.closeTime='113959',self.symbol='BTCUSDT',self.open=17014.8, self.close=17022.6, self.high=17024.8, self.low=17014.8, self.vol=597.47, self.amt=10169708.2532, ukdf['pct'].iloc[-1]=0.000458 , ukdf['amount'].iloc[-1]=10169708.2532, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5899, value=0.0, value_mean=0.16541154935316324, signal=0, value_std=0.29688797573297815 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-29684.8208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17022.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2853
self.closeSec=1670384699, self.tradeDate='20221207', self.openTime='114000', self.closeTime='114459', self.symbol='BTCUSDT', self.open=17022.5, self.close=17023.4, self.high=17025.3, self.low=17021.0, self.vol=429.162, self.amt=7305824.7882 
127.0.0.1 - - [07/Dec/2022 11:45:00] "POST / HTTP/1.1" 200 -
2022-12-07 11:45:00,559:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5896  20221207   112000    112459  ...    0.165997   0.297253       0
5897  20221207   112500    112959  ...    0.165802   0.297132       0
5898  20221207   113000    113459  ...    0.165607   0.297010       0
5899  20221207   113500    113959  ...    0.165412   0.296888       0
5900  20221207   114000    114459  ...    0.165219   0.296770       0

[5 rows x 18 columns]
2022-12-07 11:45:00,560:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670384699, self.tradeDate='20221207', self.openTime='114000', self.closeTime='114459',self.symbol='BTCUSDT',self.open=17022.5, self.close=17023.4, self.high=17025.3, self.low=17021.0, self.vol=429.162, self.amt=7305824.7882, ukdf['pct'].iloc[-1]=4.7e-05 , ukdf['amount'].iloc[-1]=7305824.7882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5900, value=0.0, value_mean=0.16521892782203415, signal=0, value_std=0.2967702574185301 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-29732.9616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17023.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1

/root/FIL/strategy/factorcheck/log.txt

self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113500', self.closeTime='113959', self.symbol='BTCUSDT', self.open=17014.8, self.close=17022.6, self.high=17024.8, self.low=17014.8 
127.0.0.1 - - [07/Dec/2022 11:40:01] "POST / HTTP/1.1" 200 -
2022-12-07 11:40:01,416:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113500', self.closeTime='113959',self.symbol='BTCUSDT',self.open=17014.8, self.close=17022.6, self.high=17024.8, self.low=17014.8   
2022-12-07 11:40:01,428:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1575  20221207   111500    111959  1670383199  ...  17027.0 -0.000376   1575    3
1576  20221207   112000    112459  1670383499  ...  17015.4 -0.000159   1576    4
1577  20221207   112500    112959  1670383799  ...  17018.4 -0.000347   1577    5
1578  20221207   113000    113459  1670384099  ...  17011.3 -0.000217   1578    0
1579  20221207   113500    113959  1670384399  ...  17014.8  0.000458   1579    1

[5 rows x 11 columns]
2022-12-07 11:40:01,428:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Dec/2022 11:45:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5549167815345329, self.count=3419 

self.closeSec=1670384699, self.tradeDate='20221207', self.openTime='114000', self.closeTime='114459', self.symbol='BTCUSDT', self.open=17022.5, self.close=17023.4, self.high=17025.3, self.low=17021.0 
2022-12-07 11:45:00,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670384699, self.tradeDate='20221207', self.openTime='114000', self.closeTime='114459',self.symbol='BTCUSDT',self.open=17022.5, self.close=17023.4, self.high=17025.3, self.low=17021.0   
2022-12-07 11:45:00,528:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1576  20221207   112000    112459  1670383499  ...  17015.4 -0.000159   1576    4
1577  20221207   112500    112959  1670383799  ...  17018.4 -0.000347   1577    5
1578  20221207   113000    113459  1670384099  ...  17011.3 -0.000217   1578    0
1579  20221207   113500    113959  1670384399  ...  17014.8  0.000458   1579    1
1580  20221207   114000    114459  1670384699  ...  17021.0  0.000047   1580    2

[5 rows x 11 columns]
2022-12-07 11:45:00,528:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

/root/FIL/strategy/logic/log.txt
2022-12-07 11:30:19,784:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5777  20221207    085959  17060.3  ...  50.833333  0.516579  0.515859
5778  20221207    092959  17056.5  ...  50.833333  0.502610  0.511078
5779  20221207    095959  17027.9  ...  51.250000  0.506089  0.504502
5780  20221207    102959  17035.1  ...  51.666667  0.508730  0.496770
5781  20221207    105959  17040.7  ...  51.666667  0.511686  0.487787

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2022-12-07 11:30:19,850:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.493637  0.506363       0  ...  0.936617  -1.0    0.0  1.030807
537     1  0.485883  0.514117       1  ...  0.936216  -1.0    0.0  1.031249
538     1  0.484950  0.515050       1  ...  0.935914  -1.0    0.0  1.031582
539     1  0.483012  0.516988       1  ...  0.935579  -1.0    0.0  1.031951
540     1  0.485705  0.514295       0  ...  0.937220  -1.0    0.0  1.030141

[5 rows x 10 columns]
2022-12-07 11:30:19,862:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494081  0.505919       0  ...  0.957851  -1.0    0.0  1.032739
46     1  0.486012  0.513988       1  ...  0.936216  -1.0    0.0  1.031974
47     1  0.484674  0.515326       1  ...  0.935914  -1.0    0.0  1.031763
48     1  0.482579  0.517421       1  ...  0.935579  -1.0    0.0  1.029763
49     1  0.485705  0.514295       0  ...  0.937220  -1.0    0.0  1.030141

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '-2171.736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17020', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}

/root/FIL/strategy/modifiedmom/log.txt
2022-12-07 11:20:00,559:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Dec/2022 11:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1708 

self.closeSec=1670383799, self.tradeDate='20221207', self.openTime='112000', self.closeTime='112959', self.symbol='BTCUSDT', self.open='17027.1', self.close='17016.8'
2022-12-07 11:30:01,181:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670383799, self.tradeDate='20221207', self.openTime='112000', self.closeTime='112959',self.symbol='BTCUSDT',self.open='17027.1', self.close='17016.8'
127.0.0.1 - - [07/Dec/2022 11:30:01] "POST / HTTP/1.1" 200 -
2022-12-07 11:30:01,189:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
640  20221207   104000    104959  1670381399  17044.7  17052.1  0.000434
641  20221207   105000    105959  1670381999  17052.1  17046.7 -0.000317
642  20221207   110000    110959  1670382599  17046.7  17031.8 -0.000874
643  20221207   111000    111959  1670383199  17031.7  17027.1 -0.000276
644  20221207   112000    112959  1670383799  17027.1  17016.8 -0.000605
2022-12-07 11:30:01,190:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Dec/2022 11:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1709 

self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113000', self.closeTime='113959', self.symbol='BTCUSDT', self.open='17016.8', self.close='17022.6'
2022-12-07 11:40:01,540:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113000', self.closeTime='113959',self.symbol='BTCUSDT',self.open='17016.8', self.close='17022.6'
2022-12-07 11:40:01,555:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
641  20221207   105000    105959  1670381999  17052.1  17046.7 -0.000317
642  20221207   110000    110959  1670382599  17046.7  17031.8 -0.000874
643  20221207   111000    111959  1670383199  17031.7  17027.1 -0.000276
644  20221207   112000    112959  1670383799  17027.1  17016.8 -0.000605
645  20221207   113000    113959  1670384399  17016.8  17022.6  0.000341
2022-12-07 11:40:01,555:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

/root/FIL/strategy/pyemd/log.txt
17491  20221207   111000    111959  1670383199  17031.7  17027.1
2022-12-07 11:20:00,555:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Dec/2022 11:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1709 

self.closeSec=1670383799, self.tradeDate='20221207', self.openTime='112000', self.closeTime='112959', self.symbol='BTCUSDT', self.open='17027.1', self.close='17016.8'
2022-12-07 11:30:01,200:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670383799, self.tradeDate='20221207', self.openTime='112000', self.closeTime='112959',self.symbol='BTCUSDT',self.open='17027.1', self.close='17016.8'
2022-12-07 11:30:01,207:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17488  20221207   104000    104959  1670381399  17044.7  17052.1
17489  20221207   105000    105959  1670381999  17052.1  17046.7
17490  20221207   110000    110959  1670382599  17046.7  17031.8
17491  20221207   111000    111959  1670383199  17031.7  17027.1
17492  20221207   112000    112959  1670383799  17027.1  17016.8
2022-12-07 11:30:01,207:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Dec/2022 11:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1710 

self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113000', self.closeTime='113959', self.symbol='BTCUSDT', self.open='17016.8', self.close='17022.6'
2022-12-07 11:40:01,548:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113000', self.closeTime='113959',self.symbol='BTCUSDT',self.open='17016.8', self.close='17022.6'
2022-12-07 11:40:01,556:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17489  20221207   105000    105959  1670381999  17052.1  17046.7
17490  20221207   110000    110959  1670382599  17046.7  17031.8
17491  20221207   111000    111959  1670383199  17031.7  17027.1
17492  20221207   112000    112959  1670383799  17027.1  17016.8
17493  20221207   113000    113959  1670384399  17016.8  17022.6
2022-12-07 11:40:01,556:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

/root/FIL/strategy/similarity/log.txt
12163  20221207   111000    111959  1670383199  17031.7  17027.1
2022-12-07 11:20:00,562:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Dec/2022 11:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1709 

self.closeSec=1670383799, self.tradeDate='20221207', self.openTime='112000', self.closeTime='112959', self.symbol='BTCUSDT', self.open='17027.1', self.close='17016.8'
2022-12-07 11:30:01,214:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670383799, self.tradeDate='20221207', self.openTime='112000', self.closeTime='112959',self.symbol='BTCUSDT',self.open='17027.1', self.close='17016.8'
2022-12-07 11:30:01,227:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12160  20221207   104000    104959  1670381399  17044.7  17052.1
12161  20221207   105000    105959  1670381999  17052.1  17046.7
12162  20221207   110000    110959  1670382599  17046.7  17031.8
12163  20221207   111000    111959  1670383199  17031.7  17027.1
12164  20221207   112000    112959  1670383799  17027.1  17016.8
2022-12-07 11:30:01,227:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Dec/2022 11:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1710 

self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113000', self.closeTime='113959', self.symbol='BTCUSDT', self.open='17016.8', self.close='17022.6'
2022-12-07 11:40:01,540:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670384399, self.tradeDate='20221207', self.openTime='113000', self.closeTime='113959',self.symbol='BTCUSDT',self.open='17016.8', self.close='17022.6'
2022-12-07 11:40:01,546:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12161  20221207   105000    105959  1670381999  17052.1  17046.7
12162  20221207   110000    110959  1670382599  17046.7  17031.8
12163  20221207   111000    111959  1670383199  17031.7  17027.1
12164  20221207   112000    112959  1670383799  17027.1  17016.8
12165  20221207   113000    113959  1670384399  17016.8  17022.6
2022-12-07 11:40:01,547:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

/root/FIL/strategy/s_rsrs/log.txt
719  20221206   200000    235959  1670342399  ...    719  0.716348  1.398787     1.0
720  20221207   000000    035959  1670356799  ...    720  1.120770  3.120988     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-19779.0628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16964.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=70
self.closeSec=1670371199, self.tradeDate='20221207', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16964.1, self.close=17078.0, self.high=17100.0, self.low=16946.3, self.vol=51125.606, self.amt=869854896.3636 
127.0.0.1 - - [07/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-07 08:00:01,571:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670371199, self.tradeDate='20221207', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16964.1, self.close=17078.0, self.high=17100.0, self.low=16946.3, self.vol=51125.606, self.amt=869854896.3636 
2022-12-07 08:00:01,584:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221206   120000    155959  ...  33273.403  5.652557e+08 -0.000106
718  20221206   160000    195959  ...  57639.285  9.783913e+08 -0.001118
719  20221206   200000    235959  ...  69024.422  1.172189e+09  0.000018
720  20221207   000000    035959  ...  56413.953  9.566549e+08 -0.000636
721  20221207   040000    075959  ...  51125.606  8.698549e+08  0.006714

[5 rows x 11 columns]
2022-12-07 08:00:02,279:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221206   120000    155959  1670313599  ...    717  0.735540  1.557487     1.0
718  20221206   160000    195959  1670327999  ...    718  0.713850  1.417234     1.0
719  20221206   200000    235959  1670342399  ...    719  0.716348  1.398787     1.0
720  20221207   000000    035959  1670356799  ...    720  1.120770  3.120988     1.0
721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-13012.51157857668', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17079.52682306', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1

