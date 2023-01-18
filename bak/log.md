# 20230118 13:34:28

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/Jan/2023 13:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14969
self.closeSec=1674019499, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132459', self.symbol='BTCUSDT', self.open=21295.1, self.close=21302.0, self.high=21309.9, self.low=21295.0, self.vol=395.621, self.amt=8428017.087 
2023-01-18 13:25:01,633:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5916  20230118   130000    130459  ...         0.0        0.0       0
5917  20230118   130500    130959  ...         0.0        0.0       0
5918  20230118   131000    131459  ...         0.0        0.0       0
5919  20230118   131500    131959  ...         0.0        0.0       0
5920  20230118   132000    132459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 13:25:01,635:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674019499, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132459',self.symbol='BTCUSDT',self.open=21295.1, self.close=21302.0, self.high=21309.9, self.low=21295.0, self.vol=395.621, self.amt=8428017.087, ukdf['pct'].iloc[-1]=0.000329 , ukdf['amount'].iloc[-1]=8428017.087, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5920, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-287196.87664989984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21301.91494034', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Jan/2023 13:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14970
self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132500', self.closeTime='132959', self.symbol='BTCUSDT', self.open=21301.9, self.close=21290.3, self.high=21317.9, self.low=21290.3, self.vol=547.633, self.amt=11667325.0336 
2023-01-18 13:30:00,971:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5917  20230118   130500    130959  ...         0.0        0.0       0
5918  20230118   131000    131459  ...         0.0        0.0       0
5919  20230118   131500    131959  ...         0.0        0.0       0
5920  20230118   132000    132459  ...         0.0        0.0       0
5921  20230118   132500    132959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 13:30:00,971:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132500', self.closeTime='132959',self.symbol='BTCUSDT',self.open=21301.9, self.close=21290.3, self.high=21317.9, self.low=21290.3, self.vol=547.633, self.amt=11667325.0336, ukdf['pct'].iloc[-1]=-0.000549 , ukdf['amount'].iloc[-1]=11667325.0336, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5921, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-286503.9536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21290.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1599  20230118   131500    131959  1674019199  ...  21291.2 -0.000099   1599    3
1600  20230118   132000    132459  1674019499  ...  21295.0  0.000329   1600    4

[5 rows x 11 columns]
2023-01-18 13:25:01,479:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 13:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=505, self.factor=0.5044369631207147, self.count=15536 

self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132500', self.closeTime='132959', self.symbol='BTCUSDT', self.open=21301.9, self.close=21290.3, self.high=21317.9, self.low=21290.3 
2023-01-18 13:30:00,729:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132500', self.closeTime='132959',self.symbol='BTCUSDT',self.open=21301.9, self.close=21290.3, self.high=21317.9, self.low=21290.3   
2023-01-18 13:30:00,860:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1597  20230118   130500    130959  1674018599  ...  21252.6  0.000588   1597    1
1598  20230118   131000    131459  1674018899  ...  21277.6  0.000916   1598    2
1599  20230118   131500    131959  1674019199  ...  21291.2 -0.000099   1599    3
1600  20230118   132000    132459  1674019499  ...  21295.0  0.000329   1600    4
1601  20230118   132500    132959  1674019799  ...  21290.3 -0.000549   1601    5

[5 rows x 11 columns]
2023-01-18 13:30:00,860:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-18 13:30:01,092:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
223  20230118   112500    112959  1674012599  ...  0.000399   1577    5  0.497099
224  20230118   115500    115959  1674014399  ... -0.001700   1583    5  0.500751
225  20230118   122500    122959  1674016199  ...  0.000653   1589    5  0.502265
226  20230118   125500    125959  1674017999  ...  0.000512   1595    5  0.504437
227  20230118   132500    132959  1674019799  ... -0.000549   1601    5  0.505996

[5 rows x 12 columns]


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-18 13:30:46,769:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5781  20230118    105959  21201.2  ...  51.250000  0.545191  0.560134
5782  20230118    112959  21292.5  ...  51.666667  0.552030  0.556531
5783  20230118    115959  21328.4  ...  51.250000  0.533966  0.561213
5784  20230118    122959  21254.1  ...  51.666667  0.541953  0.561382
5785  20230118    125959  21292.9  ...  51.666667  0.538748  0.562969

[5 rows x 33 columns]
0.5239852398523985
acc is : 0.5239852398523985
2023-01-18 13:30:47,094:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.535938  0.464062       1  ...  1.059370   1.0    0.0  1.258617
538     0  0.524001  0.475999       0  ...  1.055680   1.0    0.0  1.254233
539     1  0.496591  0.503409       1  ...  1.057607   1.0    0.0  1.256522
540     0  0.517105  0.482895       0  ...  1.056952   1.0    0.0  1.255743
541     0  0.509523  0.490477       1  ...  1.057478   1.0    0.0  1.256369

[5 rows x 10 columns]
2023-01-18 13:30:47,144:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.535876  0.464124       1  ...  1.059370   1.0    0.0  1.262880
46     0  0.524045  0.475955       0  ...  1.055680   1.0    0.0  1.256375
47     1  0.496596  0.503404       1  ...  1.057607   1.0    0.0  1.258230
48     0  0.517081  0.482919       0  ...  1.056952   1.0    0.0  1.257450
49     0  0.509523  0.490477       1  ...  1.057478   1.0    0.0  1.256369

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

510  20230118   130000    130959  1674018599  21279.7  21277.6 -0.000099
2023-01-18 13:10:02,047:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/Jan/2023 13:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7767 

self.closeSec=1674019199, self.tradeDate='20230118', self.openTime='131000', self.closeTime='131959', self.symbol='BTCUSDT', self.open='21277.7', self.close='21295'
2023-01-18 13:20:00,524:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674019199, self.tradeDate='20230118', self.openTime='131000', self.closeTime='131959',self.symbol='BTCUSDT',self.open='21277.7', self.close='21295'
2023-01-18 13:20:00,557:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
507  20230118   123000    123959  1674016799  21292.9  21273.4 -0.000916
508  20230118   124000    124959  1674017399  21273.3  21285.5  0.000569
509  20230118   125000    125959  1674017999  21285.5  21279.7 -0.000272
510  20230118   130000    130959  1674018599  21279.7  21277.6 -0.000099
511  20230118   131000    131959  1674019199  21277.7    21295  0.000818
2023-01-18 13:20:00,557:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/Jan/2023 13:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7768 

self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132959', self.symbol='BTCUSDT', self.open='21295.1', self.close='21290.3'
2023-01-18 13:30:00,989:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132959',self.symbol='BTCUSDT',self.open='21295.1', self.close='21290.3'
2023-01-18 13:30:01,051:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
508  20230118   124000    124959  1674017399  21273.3  21285.5  0.000569
509  20230118   125000    125959  1674017999  21285.5  21279.7 -0.000272
510  20230118   130000    130959  1674018599  21279.7  21277.6 -0.000099
511  20230118   131000    131959  1674019199  21277.7    21295  0.000818
512  20230118   132000    132959  1674019799  21295.1  21290.3 -0.000221
2023-01-18 13:30:01,051:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17502  20230118   130000    130959  1674018599  21279.7  21277.6
2023-01-18 13:10:02,040:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7768 

self.closeSec=1674019199, self.tradeDate='20230118', self.openTime='131000', self.closeTime='131959', self.symbol='BTCUSDT', self.open='21277.7', self.close='21295'
2023-01-18 13:20:00,550:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674019199, self.tradeDate='20230118', self.openTime='131000', self.closeTime='131959',self.symbol='BTCUSDT',self.open='21277.7', self.close='21295'
127.0.0.1 - - [18/Jan/2023 13:20:00] "POST / HTTP/1.1" 200 -
2023-01-18 13:20:00,573:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17499  20230118   123000    123959  1674016799  21292.9  21273.4
17500  20230118   124000    124959  1674017399  21273.3  21285.5
17501  20230118   125000    125959  1674017999  21285.5  21279.7
17502  20230118   130000    130959  1674018599  21279.7  21277.6
17503  20230118   131000    131959  1674019199  21277.7    21295
2023-01-18 13:20:00,573:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 13:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7769 

self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132959', self.symbol='BTCUSDT', self.open='21295.1', self.close='21290.3'
2023-01-18 13:30:00,973:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132959',self.symbol='BTCUSDT',self.open='21295.1', self.close='21290.3'
2023-01-18 13:30:01,099:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17500  20230118   124000    124959  1674017399  21273.3  21285.5
17501  20230118   125000    125959  1674017999  21285.5  21279.7
17502  20230118   130000    130959  1674018599  21279.7  21277.6
17503  20230118   131000    131959  1674019199  21277.7    21295
17504  20230118   132000    132959  1674019799  21295.1  21290.3
2023-01-18 13:30:01,099:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12174  20230118   130000    130959  1674018599  21279.7  21277.6
2023-01-18 13:10:02,046:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Jan/2023 13:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7768 

self.closeSec=1674019199, self.tradeDate='20230118', self.openTime='131000', self.closeTime='131959', self.symbol='BTCUSDT', self.open='21277.7', self.close='21295'
2023-01-18 13:20:00,533:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674019199, self.tradeDate='20230118', self.openTime='131000', self.closeTime='131959',self.symbol='BTCUSDT',self.open='21277.7', self.close='21295'
2023-01-18 13:20:00,562:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12171  20230118   123000    123959  1674016799  21292.9  21273.4
12172  20230118   124000    124959  1674017399  21273.3  21285.5
12173  20230118   125000    125959  1674017999  21285.5  21279.7
12174  20230118   130000    130959  1674018599  21279.7  21277.6
12175  20230118   131000    131959  1674019199  21277.7    21295
2023-01-18 13:20:00,562:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7769 

self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132959', self.symbol='BTCUSDT', self.open='21295.1', self.close='21290.3'
2023-01-18 13:30:01,000:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132959',self.symbol='BTCUSDT',self.open='21295.1', self.close='21290.3'
127.0.0.1 - - [18/Jan/2023 13:30:00] "POST / HTTP/1.1" 200 -
2023-01-18 13:30:01,060:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12172  20230118   124000    124959  1674017399  21273.3  21285.5
12173  20230118   125000    125959  1674017999  21285.5  21279.7
12174  20230118   130000    130959  1674018599  21279.7  21277.6
12175  20230118   131000    131959  1674019199  21277.7    21295
12176  20230118   132000    132959  1674019799  21295.1  21290.3
2023-01-18 13:30:01,060:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  127.0.0.1 - - [18/Jan/2023 13:25:01] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10967
self.closeSec=1674019499, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132459', self.symbol='BTCUSDT', self.open=21295.1, self.close=21302.0, self.high=21309.9, self.low=21295.0, self.vol=395.621, self.amt=8428017.087 
2023-01-18 13:25:01,545:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5916  20230118   130000    130459  ...         0.0        0.0       0
5917  20230118   130500    130959  ...         0.0        0.0       0
5918  20230118   131000    131459  ...         0.0        0.0       0
5919  20230118   131500    131959  ...         0.0        0.0       0
5920  20230118   132000    132459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 13:25:01,545:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674019499, self.tradeDate='20230118', self.openTime='132000', self.closeTime='132459',self.symbol='BTCUSDT',self.open=21295.1, self.close=21302.0, self.high=21309.9, self.low=21295.0, self.vol=395.621, self.amt=8428017.087, ukdf['pct'].iloc[-1]=0.000329 , ukdf['amount'].iloc[-1]=8428017.087, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5920, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10968
self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132500', self.closeTime='132959', self.symbol='BTCUSDT', self.open=21301.9, self.close=21290.3, self.high=21317.9, self.low=21290.3, self.vol=547.633, self.amt=11667325.0336 
127.0.0.1 - - [18/Jan/2023 13:30:00] "POST / HTTP/1.1" 200 -
2023-01-18 13:30:00,819:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5917  20230118   130500    130959  ...         0.0        0.0       0
5918  20230118   131000    131459  ...         0.0        0.0       0
5919  20230118   131500    131959  ...         0.0        0.0       0
5920  20230118   132000    132459  ...         0.0        0.0       0
5921  20230118   132500    132959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 13:30:00,819:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674019799, self.tradeDate='20230118', self.openTime='132500', self.closeTime='132959',self.symbol='BTCUSDT',self.open=21301.9, self.close=21290.3, self.high=21317.9, self.low=21290.3, self.vol=547.633, self.amt=11667325.0336, ukdf['pct'].iloc[-1]=-0.000549 , ukdf['amount'].iloc[-1]=11667325.0336, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5921, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

720  20230118   000000    035959  1673985599  ...    720  0.363703 -1.263897    -1.0
721  20230118   040000    075959  1673999999  ...    721  0.123877 -1.893662    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '1837.908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21130.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=323
self.closeSec=1674014399, self.tradeDate='20230118', self.openTime='080000', self.closeTime='115959', self.symbol='BTCUSDT', self.open=21130.8, self.close=21254.1, self.high=21376.3, self.low=21103.6, self.vol=58477.632, self.amt=1242591692.2198 
127.0.0.1 - - [18/Jan/2023 12:00:01] "POST / HTTP/1.1" 200 -
2023-01-18 12:00:01,983:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674014399, self.tradeDate='20230118', self.openTime='080000', self.closeTime='115959',self.symbol='BTCUSDT',self.open=21130.8, self.close=21254.1, self.high=21376.3, self.low=21103.6, self.vol=58477.632, self.amt=1242591692.2198 
2023-01-18 12:00:02,086:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
718  20230117   160000    195959  ...   49711.091  1.052226e+09  0.003970
719  20230117   200000    235959  ...  233118.482  4.958880e+09 -0.002022
720  20230118   000000    035959  ...   86362.443  1.834486e+09  0.007627
721  20230118   040000    075959  ...   56117.691  1.193678e+09 -0.009795
722  20230118   080000    115959  ...   58477.632  1.242592e+09  0.005959

[5 rows x 11 columns]
2023-01-18 12:00:02,964:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
718  20230117   160000    195959  1673956799  ...    718  0.635010 -0.505098     NaN
719  20230117   200000    235959  1673971199  ...    719  0.515810 -0.841899    -1.0
720  20230118   000000    035959  1673985599  ...    720  0.363703 -1.263897    -1.0
721  20230118   040000    075959  1673999999  ...    721  0.123877 -1.893662    -1.0
722  20230118   080000    115959  1674014399  ...    722  0.005990 -2.167398    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-4580.1517698768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21256.6136656', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


