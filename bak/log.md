# 20230114 11:07:43

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13788
self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105500', self.closeTime='105959', self.symbol='BTCUSDT', self.open=20972.6, self.close=20959.7, self.high=20975.0, self.low=20951.5, self.vol=1374.941, self.amt=28825120.7912 
127.0.0.1 - - [14/Jan/2023 11:00:02] "POST / HTTP/1.1" 200 -
2023-01-14 11:00:14,155:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5887  20230114   103500    103959  ...         0.0        0.0       0
5888  20230114   104000    104459  ...         0.0        0.0       0
5889  20230114   104500    104959  ...         0.0        0.0       0
5890  20230114   105000    105459  ...         0.0        0.0       0
5891  20230114   105500    105959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 11:00:14,266:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105500', self.closeTime='105959',self.symbol='BTCUSDT',self.open=20972.6, self.close=20959.7, self.high=20975.0, self.low=20951.5, self.vol=1374.941, self.amt=28825120.7912, ukdf['pct'].iloc[-1]=-0.000615 , ukdf['amount'].iloc[-1]=28825120.7912, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5891, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-266718.0848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20961.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13789
self.closeSec=1673665499, self.tradeDate='20230114', self.openTime='110000', self.closeTime='110459', self.symbol='BTCUSDT', self.open=20959.8, self.close=21010.7, self.high=21010.8, self.low=20955.8, self.vol=1794.966, self.amt=37662798.7687 
127.0.0.1 - - [14/Jan/2023 11:05:00] "POST / HTTP/1.1" 200 -
2023-01-14 11:05:02,516:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5888  20230114   104000    104459  ...         0.0        0.0       0
5889  20230114   104500    104959  ...         0.0        0.0       0
5890  20230114   105000    105459  ...         0.0        0.0       0
5891  20230114   105500    105959  ...         0.0        0.0       0
5892  20230114   110000    110459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 11:05:02,537:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673665499, self.tradeDate='20230114', self.openTime='110000', self.closeTime='110459',self.symbol='BTCUSDT',self.open=20959.8, self.close=21010.7, self.high=21010.8, self.low=20955.8, self.vol=1794.966, self.amt=37662798.7687, ukdf['pct'].iloc[-1]=0.002433 , ukdf['amount'].iloc[-1]=37662798.7687, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5892, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-269197.25417508224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21002.79864024', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1570  20230114   105000    105459  1673664899  ...  20917.6  0.000491   1570    4
1571  20230114   105500    105959  1673665199  ...  20951.5 -0.000615   1571    5

[5 rows x 11 columns]
2023-01-14 11:00:11,074:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-14 11:00:12,476:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
218  20230114   085500    085959  1673657999  ... -0.000793   1547    5  0.170317
219  20230114   092500    092959  1673659799  ... -0.009594   1553    5  0.169344
220  20230114   095500    095959  1673661599  ...  0.001363   1559    5  0.166264
221  20230114   102500    102959  1673663399  ...  0.002764   1565    5  0.162906
222  20230114   105500    105959  1673665199  ... -0.000615   1571    5  0.159701

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=309, self.factor=0.159700563987013, self.count=14355 

self.closeSec=1673665499, self.tradeDate='20230114', self.openTime='110000', self.closeTime='110459', self.symbol='BTCUSDT', self.open=20959.8, self.close=21010.7, self.high=21010.8, self.low=20955.8 
127.0.0.1 - - [14/Jan/2023 11:05:00] "POST / HTTP/1.1" 200 -
2023-01-14 11:05:02,357:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673665499, self.tradeDate='20230114', self.openTime='110000', self.closeTime='110459',self.symbol='BTCUSDT',self.open=20959.8, self.close=21010.7, self.high=21010.8, self.low=20955.8   
2023-01-14 11:05:02,829:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1568  20230114   104000    104459  1673664299  ...  20964.2 -0.000838   1568    2
1569  20230114   104500    104959  1673664599  ...  20906.1 -0.000920   1569    3
1570  20230114   105000    105459  1673664899  ...  20917.6  0.000491   1570    4
1571  20230114   105500    105959  1673665199  ...  20951.5 -0.000615   1571    5
1572  20230114   110000    110459  1673665499  ...  20955.8  0.002433   1572    0

[5 rows x 11 columns]
2023-01-14 11:05:02,829:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-14 11:01:12,288:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5776  20230114    082959  19924.3  ...     57.5  0.740562  0.149358
5777  20230114    085959  20374.2  ...     57.5  0.776106  0.154724
5778  20230114    092959  20901.8  ...     57.5  0.743550  0.163733
5779  20230114    095959  20734.2  ...     57.5  0.755722  0.167505
5780  20230114    102959  20934.3  ...     57.5  0.757661  0.170282

[5 rows x 33 columns]
0.5341959334565619
acc is : 0.5341959334565619
2023-01-14 11:01:12,952:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.669301  0.330699       1  ...  1.127520   1.0    0.0  1.250037
537     0  0.724724  0.275276       0  ...  1.118545   1.0    0.0  1.240088
538     0  0.599626  0.400374       1  ...  1.128992   1.0    0.0  1.251670
539     0  0.680665  0.319335       1  ...  1.130718   1.0    0.0  1.253583
540     0  0.648008  0.351992       0  ...  1.130389   1.0    0.0  1.253218

[5 rows x 10 columns]
2023-01-14 11:01:12,980:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.669431  0.330569       1  ...  1.127520   1.0    0.0  1.251287
46     0  0.724306  0.275694       0  ...  1.048374   1.0    0.0  1.240563
47     0  0.598938  0.401062       1  ...  1.128992   1.0    0.0  1.252681
48     0  0.679273  0.320727       1  ...  1.059783   1.0    0.0  1.253156
49     0  0.648008  0.351992       0  ...  1.130389   1.0    0.0  1.253218

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

639  20230114   103000    103959  1673663999  20970.9  20999.2  0.001593
2023-01-14 10:40:01,654:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7176 

self.closeSec=1673664599, self.tradeDate='20230114', self.openTime='104000', self.closeTime='104959', self.symbol='BTCUSDT', self.open='20999.2', self.close='20962.3'
2023-01-14 10:50:00,799:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673664599, self.tradeDate='20230114', self.openTime='104000', self.closeTime='104959',self.symbol='BTCUSDT',self.open='20999.2', self.close='20962.3'
127.0.0.1 - - [14/Jan/2023 10:50:00] "POST / HTTP/1.1" 200 -
2023-01-14 10:50:00,818:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
636  20230114   100000    100959  1673662199  20934.3  21008.8  0.003583
637  20230114   101000    101959  1673662799  21008.8  20913.4 -0.004541
638  20230114   102000    102959  1673663399    20917  20965.8  0.002506
639  20230114   103000    103959  1673663999  20970.9  20999.2  0.001593
640  20230114   104000    104959  1673664599  20999.2  20962.3 -0.001757
2023-01-14 10:50:00,818:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7177 

self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105000', self.closeTime='105959', self.symbol='BTCUSDT', self.open='20962.4', self.close='20959.8'
127.0.0.1 - - [14/Jan/2023 11:00:07] "POST / HTTP/1.1" 200 -
2023-01-14 11:00:13,394:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105000', self.closeTime='105959',self.symbol='BTCUSDT',self.open='20962.4', self.close='20959.8'
2023-01-14 11:00:14,975:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
637  20230114   101000    101959  1673662799  21008.8  20913.4 -0.004541
638  20230114   102000    102959  1673663399    20917  20965.8  0.002506
639  20230114   103000    103959  1673663999  20970.9  20999.2  0.001593
640  20230114   104000    104959  1673664599  20999.2  20962.3 -0.001757
641  20230114   105000    105959  1673665199  20962.4  20959.8 -0.000119
2023-01-14 11:00:14,984:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17487  20230114   103000    103959  1673663999  20970.9  20999.2
2023-01-14 10:40:01,680:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Jan/2023 10:50:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7177 

self.closeSec=1673664599, self.tradeDate='20230114', self.openTime='104000', self.closeTime='104959', self.symbol='BTCUSDT', self.open='20999.2', self.close='20962.3'
2023-01-14 10:50:00,802:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673664599, self.tradeDate='20230114', self.openTime='104000', self.closeTime='104959',self.symbol='BTCUSDT',self.open='20999.2', self.close='20962.3'
2023-01-14 10:50:00,827:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17484  20230114   100000    100959  1673662199  20934.3  21008.8
17485  20230114   101000    101959  1673662799  21008.8  20913.4
17486  20230114   102000    102959  1673663399    20917  20965.8
17487  20230114   103000    103959  1673663999  20970.9  20999.2
17488  20230114   104000    104959  1673664599  20999.2  20962.3
2023-01-14 10:50:00,827:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7178 

self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105000', self.closeTime='105959', self.symbol='BTCUSDT', self.open='20962.4', self.close='20959.8'
127.0.0.1 - - [14/Jan/2023 11:00:07] "POST / HTTP/1.1" 200 -
2023-01-14 11:00:20,830:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105000', self.closeTime='105959',self.symbol='BTCUSDT',self.open='20962.4', self.close='20959.8'
2023-01-14 11:00:21,880:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17485  20230114   101000    101959  1673662799  21008.8  20913.4
17486  20230114   102000    102959  1673663399    20917  20965.8
17487  20230114   103000    103959  1673663999  20970.9  20999.2
17488  20230114   104000    104959  1673664599  20999.2  20962.3
17489  20230114   105000    105959  1673665199  20962.4  20959.8
2023-01-14 11:00:21,881:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12159  20230114   103000    103959  1673663999  20970.9  20999.2
2023-01-14 10:40:01,659:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Jan/2023 10:50:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7177 

self.closeSec=1673664599, self.tradeDate='20230114', self.openTime='104000', self.closeTime='104959', self.symbol='BTCUSDT', self.open='20999.2', self.close='20962.3'
2023-01-14 10:50:00,765:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673664599, self.tradeDate='20230114', self.openTime='104000', self.closeTime='104959',self.symbol='BTCUSDT',self.open='20999.2', self.close='20962.3'
2023-01-14 10:50:00,790:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12156  20230114   100000    100959  1673662199  20934.3  21008.8
12157  20230114   101000    101959  1673662799  21008.8  20913.4
12158  20230114   102000    102959  1673663399    20917  20965.8
12159  20230114   103000    103959  1673663999  20970.9  20999.2
12160  20230114   104000    104959  1673664599  20999.2  20962.3
2023-01-14 10:50:00,790:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7178 

self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105000', self.closeTime='105959', self.symbol='BTCUSDT', self.open='20962.4', self.close='20959.8'
127.0.0.1 - - [14/Jan/2023 11:00:08] "POST / HTTP/1.1" 200 -
2023-01-14 11:00:18,342:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105000', self.closeTime='105959',self.symbol='BTCUSDT',self.open='20962.4', self.close='20959.8'
2023-01-14 11:00:19,751:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12157  20230114   101000    101959  1673662799  21008.8  20913.4
12158  20230114   102000    102959  1673663399    20917  20965.8
12159  20230114   103000    103959  1673663999  20970.9  20999.2
12160  20230114   104000    104959  1673664599  20999.2  20962.3
12161  20230114   105000    105959  1673665199  20962.4  20959.8
2023-01-14 11:00:19,786:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9786
self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105500', self.closeTime='105959', self.symbol='BTCUSDT', self.open=20972.6, self.close=20959.7, self.high=20975.0, self.low=20951.5, self.vol=1374.941, self.amt=28825120.7912 
127.0.0.1 - - [14/Jan/2023 11:00:01] "POST / HTTP/1.1" 200 -
2023-01-14 11:00:05,520:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5887  20230114   103500    103959  ...         0.0        0.0       0
5888  20230114   104000    104459  ...         0.0        0.0       0
5889  20230114   104500    104959  ...         0.0        0.0       0
5890  20230114   105000    105459  ...         0.0        0.0       0
5891  20230114   105500    105959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 11:00:05,591:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673665199, self.tradeDate='20230114', self.openTime='105500', self.closeTime='105959',self.symbol='BTCUSDT',self.open=20972.6, self.close=20959.7, self.high=20975.0, self.low=20951.5, self.vol=1374.941, self.amt=28825120.7912, ukdf['pct'].iloc[-1]=-0.000615 , ukdf['amount'].iloc[-1]=28825120.7912, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5891, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9787
self.closeSec=1673665499, self.tradeDate='20230114', self.openTime='110000', self.closeTime='110459', self.symbol='BTCUSDT', self.open=20959.8, self.close=21010.7, self.high=21010.8, self.low=20955.8, self.vol=1794.966, self.amt=37662798.7687 
127.0.0.1 - - [14/Jan/2023 11:05:00] "POST / HTTP/1.1" 200 -
2023-01-14 11:05:02,301:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5888  20230114   104000    104459  ...         0.0        0.0       0
5889  20230114   104500    104959  ...         0.0        0.0       0
5890  20230114   105000    105459  ...         0.0        0.0       0
5891  20230114   105500    105959  ...         0.0        0.0       0
5892  20230114   110000    110459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 11:05:02,304:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673665499, self.tradeDate='20230114', self.openTime='110000', self.closeTime='110459',self.symbol='BTCUSDT',self.open=20959.8, self.close=21010.7, self.high=21010.8, self.low=20955.8, self.vol=1794.966, self.amt=37662798.7687, ukdf['pct'].iloc[-1]=0.002433 , ukdf['amount'].iloc[-1]=37662798.7687, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5892, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230113   200000    235959  1673625599  ...    719  1.171959  1.306448     1.0
720  20230114   000000    035959  1673639999  ...    720  1.163214  1.258982     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '110678.7584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19352.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=298
self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=19354.1, self.close=19924.2, self.high=19997.8, self.low=19307.4, self.vol=253648.534, self.amt=4995445212.24883 
127.0.0.1 - - [14/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-14 08:00:00,828:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=19354.1, self.close=19924.2, self.high=19997.8, self.low=19307.4, self.vol=253648.534, self.amt=4995445212.24883 
2023-01-14 08:00:00,849:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230113   120000    155959  ...   30968.560  5.827712e+08 -0.002856
718  20230113   160000    195959  ...  102428.168  1.939314e+09  0.004995
719  20230113   200000    235959  ...  200752.474  3.826630e+09  0.018021
720  20230114   000000    035959  ...  170547.519  3.282301e+09  0.005215
721  20230114   040000    075959  ...  253648.534  4.995445e+09  0.029520

[5 rows x 11 columns]
2023-01-14 08:00:03,082:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230113   120000    155959  1673596799  ...    717  1.171585  1.361232     1.0
718  20230113   160000    195959  1673611199  ...    718  1.132857  1.238241     1.0
719  20230113   200000    235959  1673625599  ...    719  1.171959  1.306448     1.0
720  20230114   000000    035959  1673639999  ...    720  1.163214  1.258982     1.0
721  20230114   040000    075959  1673654399  ...    721  1.235840  1.402725     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '139913.2096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19924.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


