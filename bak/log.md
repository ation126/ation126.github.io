# 20230201 09:43:53

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [01/Feb/2023 09:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18955
self.closeSec=1675215299, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093459', self.symbol='BTCUSDT', self.open=23056.6, self.close=23076.1, self.high=23082.7, self.low=23052.4, self.vol=446.503, self.amt=10299472.7152 
2023-02-01 09:35:00,522:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5870  20230201   091000    091459  ...         0.0        0.0       0
5871  20230201   091500    091959  ...         0.0        0.0       0
5872  20230201   092000    092459  ...         0.0        0.0       0
5873  20230201   092500    092959  ...         0.0        0.0       0
5874  20230201   093000    093459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 09:35:00,522:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675215299, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093459',self.symbol='BTCUSDT',self.open=23056.6, self.close=23076.1, self.high=23082.7, self.low=23052.4, self.vol=446.503, self.amt=10299472.7152, ukdf['pct'].iloc[-1]=0.000841 , ukdf['amount'].iloc[-1]=10299472.7152, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5874, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-394012.36585887632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23076.96627657', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Feb/2023 09:40:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18956
self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093500', self.closeTime='093959', self.symbol='BTCUSDT', self.open=23076.2, self.close=23119.1, self.high=23130.0, self.low=23076.1, self.vol=1749.298, self.amt=40428321.0209 
2023-02-01 09:40:01,559:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5871  20230201   091500    091959  ...         0.0        0.0       0
5872  20230201   092000    092459  ...         0.0        0.0       0
5873  20230201   092500    092959  ...         0.0        0.0       0
5874  20230201   093000    093459  ...         0.0        0.0       0
5875  20230201   093500    093959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 09:40:01,559:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093500', self.closeTime='093959',self.symbol='BTCUSDT',self.open=23076.2, self.close=23119.1, self.high=23130.0, self.low=23076.1, self.vol=1749.298, self.amt=40428321.0209, ukdf['pct'].iloc[-1]=0.001863 , ukdf['amount'].iloc[-1]=40428321.0209, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5875, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-396629.38108918256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23120.45562831', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1675215299, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093459', self.symbol='BTCUSDT', self.open=23056.6, self.close=23076.1, self.high=23082.7, self.low=23052.4 
2023-02-01 09:35:00,434:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675215299, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093459',self.symbol='BTCUSDT',self.open=23056.6, self.close=23076.1, self.high=23082.7, self.low=23052.4   
127.0.0.1 - - [01/Feb/2023 09:35:00] "POST / HTTP/1.1" 200 -
2023-02-01 09:35:00,480:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1550  20230201   091000    091459  1675214099  ...  23089.9  0.000177   1550    2
1551  20230201   091500    091959  1675214399  ...  23075.0 -0.001428   1551    3
1552  20230201   092000    092459  1675214699  ...  23062.0 -0.000425   1552    4
1553  20230201   092500    092959  1675214999  ...  23051.0 -0.000369   1553    5
1554  20230201   093000    093459  1675215299  ...  23052.4  0.000841   1554    0

[5 rows x 11 columns]
2023-02-01 09:35:00,480:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Feb/2023 09:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=21, self.factor=0.4501605832790754, self.count=19522 

self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093500', self.closeTime='093959', self.symbol='BTCUSDT', self.open=23076.2, self.close=23119.1, self.high=23130.0, self.low=23076.1 
2023-02-01 09:40:01,432:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093500', self.closeTime='093959',self.symbol='BTCUSDT',self.open=23076.2, self.close=23119.1, self.high=23130.0, self.low=23076.1   
2023-02-01 09:40:01,574:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1551  20230201   091500    091959  1675214399  ...  23075.0 -0.001428   1551    3
1552  20230201   092000    092459  1675214699  ...  23062.0 -0.000425   1552    4
1553  20230201   092500    092959  1675214999  ...  23051.0 -0.000369   1553    5
1554  20230201   093000    093459  1675215299  ...  23052.4  0.000841   1554    0
1555  20230201   093500    093959  1675215599  ...  23076.1  0.001863   1555    1

[5 rows x 11 columns]
2023-02-01 09:40:01,575:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-01 09:30:46,082:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5773  20230201    065959  22891.5  ...  50.000000  0.521574  0.351501
5774  20230201    072959  23178.5  ...  50.000000  0.504807  0.353792
5775  20230201    075959  23100.5  ...  50.000000  0.508691  0.353823
5776  20230201    082959  23119.5  ...  50.000000  0.491045  0.363316
5777  20230201    085959  23034.9  ...  50.416667  0.499690  0.367555

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2023-02-01 09:30:46,418:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.562250  0.437750       0  ...  1.020032   1.0    0.0  1.080477
537     1  0.495605  0.504395       1  ...  1.020862   1.0    0.0  1.081356
538     0  0.520307  0.479693       0  ...  1.017136   1.0    0.0  1.077409
539     1  0.498256  0.501744       1  ...  1.018955   1.0    0.0  1.079336
540     0  0.526665  0.473335       0  ...  1.018094   1.0    0.0  1.078424

[5 rows x 10 columns]
2023-02-01 09:30:46,465:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.563313  0.436687       0  ...  0.985391   1.0    0.0  1.083462
46     1  0.496413  0.503587       1  ...  0.986193   1.0    0.0  1.084344
47     0  0.519995  0.480005       0  ...  1.017136   1.0    0.0  1.078978
48     1  0.498690  0.501310       1  ...  0.984350   1.0    0.0  1.082526
49     0  0.526665  0.473335       0  ...  1.018094   1.0    0.0  1.078424

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.955', 'enterprice': '23100.3', 'countrevence': '0', 'unrealprofit': '-1308.3473254693', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23058.03389354', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

631  20230201   091000    091959  1675214399    23104  23078.5 -0.001099
2023-02-01 09:20:00,767:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9760 

self.closeSec=1675214999, self.tradeDate='20230201', self.openTime='092000', self.closeTime='092959', self.symbol='BTCUSDT', self.open='23078.5', self.close='23056.7'
2023-02-01 09:30:01,724:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675214999, self.tradeDate='20230201', self.openTime='092000', self.closeTime='092959',self.symbol='BTCUSDT',self.open='23078.5', self.close='23056.7'
2023-02-01 09:30:01,776:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
628  20230201   084000    084959  1675212599  23064.7  23092.9  0.001344
629  20230201   085000    085959  1675213199  23092.9  23076.2 -0.000723
630  20230201   090000    090959  1675213799  23076.3  23103.9  0.001200
631  20230201   091000    091959  1675214399    23104  23078.5 -0.001099
632  20230201   092000    092959  1675214999  23078.5  23056.7 -0.000945
2023-02-01 09:30:01,776:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9761 

self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093959', self.symbol='BTCUSDT', self.open='23056.6', self.close='23119.1'
2023-02-01 09:40:01,535:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093959',self.symbol='BTCUSDT',self.open='23056.6', self.close='23119.1'
127.0.0.1 - - [01/Feb/2023 09:40:01] "POST / HTTP/1.1" 200 -
2023-02-01 09:40:01,564:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
629  20230201   085000    085959  1675213199  23092.9  23076.2 -0.000723
630  20230201   090000    090959  1675213799  23076.3  23103.9  0.001200
631  20230201   091000    091959  1675214399    23104  23078.5 -0.001099
632  20230201   092000    092959  1675214999  23078.5  23056.7 -0.000945
633  20230201   093000    093959  1675215599  23056.6  23119.1  0.002706
2023-02-01 09:40:01,565:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17479  20230201   091000    091959  1675214399    23104  23078.5
2023-02-01 09:20:00,772:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9761 

self.closeSec=1675214999, self.tradeDate='20230201', self.openTime='092000', self.closeTime='092959', self.symbol='BTCUSDT', self.open='23078.5', self.close='23056.7'
2023-02-01 09:30:01,744:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675214999, self.tradeDate='20230201', self.openTime='092000', self.closeTime='092959',self.symbol='BTCUSDT',self.open='23078.5', self.close='23056.7'
2023-02-01 09:30:01,801:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17476  20230201   084000    084959  1675212599  23064.7  23092.9
17477  20230201   085000    085959  1675213199  23092.9  23076.2
17478  20230201   090000    090959  1675213799  23076.3  23103.9
17479  20230201   091000    091959  1675214399    23104  23078.5
17480  20230201   092000    092959  1675214999  23078.5  23056.7
2023-02-01 09:30:01,801:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9762 

self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093959', self.symbol='BTCUSDT', self.open='23056.6', self.close='23119.1'
2023-02-01 09:40:01,528:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093959',self.symbol='BTCUSDT',self.open='23056.6', self.close='23119.1'
127.0.0.1 - - [01/Feb/2023 09:40:01] "POST / HTTP/1.1" 200 -
2023-02-01 09:40:01,572:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17477  20230201   085000    085959  1675213199  23092.9  23076.2
17478  20230201   090000    090959  1675213799  23076.3  23103.9
17479  20230201   091000    091959  1675214399    23104  23078.5
17480  20230201   092000    092959  1675214999  23078.5  23056.7
17481  20230201   093000    093959  1675215599  23056.6  23119.1
2023-02-01 09:40:01,572:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12151  20230201   091000    091959  1675214399    23104  23078.5
2023-02-01 09:20:00,770:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9761 

self.closeSec=1675214999, self.tradeDate='20230201', self.openTime='092000', self.closeTime='092959', self.symbol='BTCUSDT', self.open='23078.5', self.close='23056.7'
2023-02-01 09:30:01,740:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675214999, self.tradeDate='20230201', self.openTime='092000', self.closeTime='092959',self.symbol='BTCUSDT',self.open='23078.5', self.close='23056.7'
2023-02-01 09:30:01,790:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12148  20230201   084000    084959  1675212599  23064.7  23092.9
12149  20230201   085000    085959  1675213199  23092.9  23076.2
12150  20230201   090000    090959  1675213799  23076.3  23103.9
12151  20230201   091000    091959  1675214399    23104  23078.5
12152  20230201   092000    092959  1675214999  23078.5  23056.7
2023-02-01 09:30:01,790:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Feb/2023 09:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9762 

self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093959', self.symbol='BTCUSDT', self.open='23056.6', self.close='23119.1'
2023-02-01 09:40:01,521:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093959',self.symbol='BTCUSDT',self.open='23056.6', self.close='23119.1'
2023-02-01 09:40:01,590:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12149  20230201   085000    085959  1675213199  23092.9  23076.2
12150  20230201   090000    090959  1675213799  23076.3  23103.9
12151  20230201   091000    091959  1675214399    23104  23078.5
12152  20230201   092000    092959  1675214999  23078.5  23056.7
12153  20230201   093000    093959  1675215599  23056.6  23119.1
2023-02-01 09:40:01,590:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [01/Feb/2023 09:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14953
self.closeSec=1675215299, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093459', self.symbol='BTCUSDT', self.open=23056.6, self.close=23076.1, self.high=23082.7, self.low=23052.4, self.vol=446.503, self.amt=10299472.7152 
2023-02-01 09:35:00,550:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5870  20230201   091000    091459  ...         0.0        0.0       0
5871  20230201   091500    091959  ...         0.0        0.0       0
5872  20230201   092000    092459  ...         0.0        0.0       0
5873  20230201   092500    092959  ...         0.0        0.0       0
5874  20230201   093000    093459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 09:35:00,550:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675215299, self.tradeDate='20230201', self.openTime='093000', self.closeTime='093459',self.symbol='BTCUSDT',self.open=23056.6, self.close=23076.1, self.high=23082.7, self.low=23052.4, self.vol=446.503, self.amt=10299472.7152, ukdf['pct'].iloc[-1]=0.000841 , ukdf['amount'].iloc[-1]=10299472.7152, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5874, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Feb/2023 09:40:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14954
self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093500', self.closeTime='093959', self.symbol='BTCUSDT', self.open=23076.2, self.close=23119.1, self.high=23130.0, self.low=23076.1, self.vol=1749.298, self.amt=40428321.0209 
2023-02-01 09:40:01,631:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5871  20230201   091500    091959  ...         0.0        0.0       0
5872  20230201   092000    092459  ...         0.0        0.0       0
5873  20230201   092500    092959  ...         0.0        0.0       0
5874  20230201   093000    093459  ...         0.0        0.0       0
5875  20230201   093500    093959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 09:40:01,631:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675215599, self.tradeDate='20230201', self.openTime='093500', self.closeTime='093959',self.symbol='BTCUSDT',self.open=23076.2, self.close=23119.1, self.high=23130.0, self.low=23076.1, self.vol=1749.298, self.amt=40428321.0209, ukdf['pct'].iloc[-1]=0.001863 , ukdf['amount'].iloc[-1]=40428321.0209, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5875, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230131   200000    235959  1675180799  ...    719  0.665860  0.579371     NaN
720  20230201   000000    035959  1675195199  ...    720  0.649389  0.538291     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-21212.03567051124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23155.69912559', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [01/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=406
self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23154.6, self.close=23119.4, self.high=23330.0, self.low=22804.0, self.vol=105553.545, self.amt=2432204759.64328 
2023-02-01 08:00:01,885:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23154.6, self.close=23119.4, self.high=23330.0, self.low=22804.0, self.vol=105553.545, self.amt=2432204759.64328 
2023-02-01 08:00:01,929:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230131   120000    155959  ...   43431.989  9.923849e+08  0.006177
718  20230131   160000    195959  ...   46060.100  1.054003e+09 -0.004824
719  20230131   200000    235959  ...  113354.585  2.613078e+09  0.011244
720  20230201   000000    035959  ...   49408.861  1.142916e+09  0.001761
721  20230201   040000    075959  ...  105553.545  2.432205e+09 -0.001520

[5 rows x 11 columns]
2023-02-01 08:00:03,958:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230131   120000    155959  1675151999  ...    717  0.655813  0.534550     NaN
718  20230131   160000    195959  1675166399  ...    718  0.678704  0.609307     1.0
719  20230131   200000    235959  1675180799  ...    719  0.665860  0.579371     NaN
720  20230201   000000    035959  1675195199  ...    720  0.649389  0.538291     NaN
721  20230201   040000    075959  1675209599  ...    721  0.611552  0.441319     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-22505.78453444628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23122.49542823', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


