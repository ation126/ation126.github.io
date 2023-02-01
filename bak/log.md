# 20230201 11:13:34

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [01/Feb/2023 11:05:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18973
self.closeSec=1675220699, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110459', self.symbol='BTCUSDT', self.open=23102.3, self.close=23094.5, self.high=23105.1, self.low=23094.5, self.vol=297.195, self.amt=6865754.5427 
2023-02-01 11:05:00,734:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5888  20230201   104000    104459  ...         0.0        0.0       0
5889  20230201   104500    104959  ...         0.0        0.0       0
5890  20230201   105000    105459  ...         0.0        0.0       0
5891  20230201   105500    105959  ...         0.0        0.0       0
5892  20230201   110000    110459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 11:05:00,736:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675220699, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110459',self.symbol='BTCUSDT',self.open=23102.3, self.close=23094.5, self.high=23105.1, self.low=23094.5, self.vol=297.195, self.amt=6865754.5427, ukdf['pct'].iloc[-1]=-0.000333 , ukdf['amount'].iloc[-1]=6865754.5427, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5892, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-395110.89917885824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23095.22161624', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18974
self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110500', self.closeTime='110959', self.symbol='BTCUSDT', self.open=23094.5, self.close=23089.2, self.high=23095.6, self.low=23081.6, self.vol=228.782, self.amt=5282389.5519 
127.0.0.1 - - [01/Feb/2023 11:10:01] "POST / HTTP/1.1" 200 -
2023-02-01 11:10:01,495:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5889  20230201   104500    104959  ...         0.0        0.0       0
5890  20230201   105000    105459  ...         0.0        0.0       0
5891  20230201   105500    105959  ...         0.0        0.0       0
5892  20230201   110000    110459  ...         0.0        0.0       0
5893  20230201   110500    110959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 11:10:01,496:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110500', self.closeTime='110959',self.symbol='BTCUSDT',self.open=23094.5, self.close=23089.2, self.high=23095.6, self.low=23081.6, self.vol=228.782, self.amt=5282389.5519, ukdf['pct'].iloc[-1]=-0.000229 , ukdf['amount'].iloc[-1]=5282389.5519, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5893, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-394807.67129968912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23090.18259937', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1675220699, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110459', self.symbol='BTCUSDT', self.open=23102.3, self.close=23094.5, self.high=23105.1, self.low=23094.5 
2023-02-01 11:05:00,645:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675220699, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110459',self.symbol='BTCUSDT',self.open=23102.3, self.close=23094.5, self.high=23105.1, self.low=23094.5   
127.0.0.1 - - [01/Feb/2023 11:05:00] "POST / HTTP/1.1" 200 -
2023-02-01 11:05:00,671:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1568  20230201   104000    104459  1675219499  ...  23083.3 -0.000385   1568    2
1569  20230201   104500    104959  1675219799  ...  23079.0 -0.000043   1569    3
1570  20230201   105000    105459  1675220099  ...  23076.1  0.000650   1570    4
1571  20230201   105500    105959  1675220399  ...  23092.1  0.000212   1571    5
1572  20230201   110000    110459  1675220699  ...  23094.5 -0.000333   1572    0

[5 rows x 11 columns]
2023-02-01 11:05:00,671:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Feb/2023 11:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=24, self.factor=0.44036127895907606, self.count=19540 

self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110500', self.closeTime='110959', self.symbol='BTCUSDT', self.open=23094.5, self.close=23089.2, self.high=23095.6, self.low=23081.6 
2023-02-01 11:10:01,431:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110500', self.closeTime='110959',self.symbol='BTCUSDT',self.open=23094.5, self.close=23089.2, self.high=23095.6, self.low=23081.6   
2023-02-01 11:10:01,471:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1569  20230201   104500    104959  1675219799  ...  23079.0 -0.000043   1569    3
1570  20230201   105000    105459  1675220099  ...  23076.1  0.000650   1570    4
1571  20230201   105500    105959  1675220399  ...  23092.1  0.000212   1571    5
1572  20230201   110000    110459  1675220699  ...  23094.5 -0.000333   1572    0
1573  20230201   110500    110959  1675220999  ...  23081.6 -0.000229   1573    1

[5 rows x 11 columns]
2023-02-01 11:10:01,471:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-01 11:00:47,235:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5776  20230201    082959  23119.5  ...  50.000000  0.491045  0.363316
5777  20230201    085959  23034.9  ...  50.416667  0.499690  0.367555
5778  20230201    092959  23076.3  ...  50.416667  0.495625  0.373699
5779  20230201    095959  23056.6  ...  50.833333  0.508597  0.372481
5780  20230201    102959  23118.7  ...  50.416667  0.500420  0.376877

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-02-01 11:00:47,553:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.497056  0.502944       1  ...  1.063229   1.0    0.0  1.055245
537     0  0.525428  0.474572       0  ...  1.062330   1.0    0.0  1.054353
538     1  0.488076  0.511924       1  ...  1.065187   1.0    0.0  1.057188
539     0  0.513376  0.486624       0  ...  1.063409   1.0    0.0  1.055423
540     1  0.490463  0.509537       1  ...  1.064427   1.0    0.0  1.056434

[5 rows x 10 columns]
2023-02-01 11:00:47,601:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498690  0.501310       1  ...  0.984350   1.0    0.0  1.082526
46     0  0.526665  0.473335       0  ...  1.018094   1.0    0.0  1.078424
47     1  0.489878  0.510122       1  ...  0.986163   1.0    0.0  1.081329
48     0  0.514870  0.485130       0  ...  0.984516   1.0    0.0  1.073843
49     1  0.490463  0.509537       1  ...  1.064427   1.0    0.0  1.056434

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.955', 'enterprice': '23100.3', 'countrevence': '0', 'unrealprofit': '120.70443589765', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23104.19935183', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

640  20230201   104000    104959  1675219799    23090  23082.3 -0.000429
2023-02-01 10:50:00,815:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 11:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9769 

self.closeSec=1675220399, self.tradeDate='20230201', self.openTime='105000', self.closeTime='105959', self.symbol='BTCUSDT', self.open='23081.3', self.close='23102.2'
2023-02-01 11:00:02,208:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675220399, self.tradeDate='20230201', self.openTime='105000', self.closeTime='105959',self.symbol='BTCUSDT',self.open='23081.3', self.close='23102.2'
2023-02-01 11:00:02,237:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
637  20230201   101000    101959  1675217999  23094.2    23077 -0.000745
638  20230201   102000    102959  1675218599  23076.9  23080.1  0.000134
639  20230201   103000    103959  1675219199    23080  23092.2  0.000524
640  20230201   104000    104959  1675219799    23090  23082.3 -0.000429
641  20230201   105000    105959  1675220399  23081.3  23102.2  0.000862
2023-02-01 11:00:02,237:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 11:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9770 

self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110959', self.symbol='BTCUSDT', self.open='23102.3', self.close='23089.2'
2023-02-01 11:10:01,530:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110959',self.symbol='BTCUSDT',self.open='23102.3', self.close='23089.2'
2023-02-01 11:10:01,562:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
638  20230201   102000    102959  1675218599  23076.9  23080.1  0.000134
639  20230201   103000    103959  1675219199    23080  23092.2  0.000524
640  20230201   104000    104959  1675219799    23090  23082.3 -0.000429
641  20230201   105000    105959  1675220399  23081.3  23102.2  0.000862
642  20230201   110000    110959  1675220999  23102.3  23089.2 -0.000563
2023-02-01 11:10:01,563:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17488  20230201   104000    104959  1675219799    23090  23082.3
2023-02-01 10:50:00,846:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 11:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9770 

self.closeSec=1675220399, self.tradeDate='20230201', self.openTime='105000', self.closeTime='105959', self.symbol='BTCUSDT', self.open='23081.3', self.close='23102.2'
2023-02-01 11:00:02,237:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675220399, self.tradeDate='20230201', self.openTime='105000', self.closeTime='105959',self.symbol='BTCUSDT',self.open='23081.3', self.close='23102.2'
2023-02-01 11:00:02,274:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17485  20230201   101000    101959  1675217999  23094.2    23077
17486  20230201   102000    102959  1675218599  23076.9  23080.1
17487  20230201   103000    103959  1675219199    23080  23092.2
17488  20230201   104000    104959  1675219799    23090  23082.3
17489  20230201   105000    105959  1675220399  23081.3  23102.2
2023-02-01 11:00:02,274:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9771 

self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110959', self.symbol='BTCUSDT', self.open='23102.3', self.close='23089.2'
127.0.0.1 - - [01/Feb/2023 11:10:01] "POST / HTTP/1.1" 200 -
2023-02-01 11:10:01,537:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110959',self.symbol='BTCUSDT',self.open='23102.3', self.close='23089.2'
2023-02-01 11:10:01,568:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17486  20230201   102000    102959  1675218599  23076.9  23080.1
17487  20230201   103000    103959  1675219199    23080  23092.2
17488  20230201   104000    104959  1675219799    23090  23082.3
17489  20230201   105000    105959  1675220399  23081.3  23102.2
17490  20230201   110000    110959  1675220999  23102.3  23089.2
2023-02-01 11:10:01,569:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12160  20230201   104000    104959  1675219799    23090  23082.3
2023-02-01 10:50:00,843:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9770 

self.closeSec=1675220399, self.tradeDate='20230201', self.openTime='105000', self.closeTime='105959', self.symbol='BTCUSDT', self.open='23081.3', self.close='23102.2'
2023-02-01 11:00:02,201:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675220399, self.tradeDate='20230201', self.openTime='105000', self.closeTime='105959',self.symbol='BTCUSDT',self.open='23081.3', self.close='23102.2'
127.0.0.1 - - [01/Feb/2023 11:00:02] "POST / HTTP/1.1" 200 -
2023-02-01 11:00:02,216:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12157  20230201   101000    101959  1675217999  23094.2    23077
12158  20230201   102000    102959  1675218599  23076.9  23080.1
12159  20230201   103000    103959  1675219199    23080  23092.2
12160  20230201   104000    104959  1675219799    23090  23082.3
12161  20230201   105000    105959  1675220399  23081.3  23102.2
2023-02-01 11:00:02,216:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Feb/2023 11:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9771 

self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110959', self.symbol='BTCUSDT', self.open='23102.3', self.close='23089.2'
2023-02-01 11:10:01,534:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110959',self.symbol='BTCUSDT',self.open='23102.3', self.close='23089.2'
2023-02-01 11:10:01,551:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12158  20230201   102000    102959  1675218599  23076.9  23080.1
12159  20230201   103000    103959  1675219199    23080  23092.2
12160  20230201   104000    104959  1675219799    23090  23082.3
12161  20230201   105000    105959  1675220399  23081.3  23102.2
12162  20230201   110000    110959  1675220999  23102.3  23089.2
2023-02-01 11:10:01,551:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [01/Feb/2023 11:05:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14971
self.closeSec=1675220699, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110459', self.symbol='BTCUSDT', self.open=23102.3, self.close=23094.5, self.high=23105.1, self.low=23094.5, self.vol=297.195, self.amt=6865754.5427 
2023-02-01 11:05:00,688:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5888  20230201   104000    104459  ...         0.0        0.0       0
5889  20230201   104500    104959  ...         0.0        0.0       0
5890  20230201   105000    105459  ...         0.0        0.0       0
5891  20230201   105500    105959  ...         0.0        0.0       0
5892  20230201   110000    110459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 11:05:00,688:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675220699, self.tradeDate='20230201', self.openTime='110000', self.closeTime='110459',self.symbol='BTCUSDT',self.open=23102.3, self.close=23094.5, self.high=23105.1, self.low=23094.5, self.vol=297.195, self.amt=6865754.5427, ukdf['pct'].iloc[-1]=-0.000333 , ukdf['amount'].iloc[-1]=6865754.5427, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5892, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Feb/2023 11:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14972
self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110500', self.closeTime='110959', self.symbol='BTCUSDT', self.open=23094.5, self.close=23089.2, self.high=23095.6, self.low=23081.6, self.vol=228.782, self.amt=5282389.5519 
2023-02-01 11:10:01,519:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5889  20230201   104500    104959  ...         0.0        0.0       0
5890  20230201   105000    105459  ...         0.0        0.0       0
5891  20230201   105500    105959  ...         0.0        0.0       0
5892  20230201   110000    110459  ...         0.0        0.0       0
5893  20230201   110500    110959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 11:10:01,520:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675220999, self.tradeDate='20230201', self.openTime='110500', self.closeTime='110959',self.symbol='BTCUSDT',self.open=23094.5, self.close=23089.2, self.high=23095.6, self.low=23081.6, self.vol=228.782, self.amt=5282389.5519, ukdf['pct'].iloc[-1]=-0.000229 , ukdf['amount'].iloc[-1]=5282389.5519, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5893, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
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


