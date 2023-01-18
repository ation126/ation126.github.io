# 20230118 12:24:27

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14955
self.closeSec=1674015299, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121459', self.symbol='BTCUSDT', self.open=21245.3, self.close=21273.1, self.high=21273.1, self.low=21245.2, self.vol=717.391, self.amt=15252091.2986 
127.0.0.1 - - [18/Jan/2023 12:15:00] "POST / HTTP/1.1" 200 -
2023-01-18 12:15:00,719:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5902  20230118   115000    115459  ...         0.0        0.0       0
5903  20230118   115500    115959  ...         0.0        0.0       0
5904  20230118   120000    120459  ...         0.0        0.0       0
5905  20230118   120500    120959  ...         0.0        0.0       0
5906  20230118   121000    121459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 12:15:00,720:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674015299, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121459',self.symbol='BTCUSDT',self.open=21245.3, self.close=21273.1, self.high=21273.1, self.low=21245.2, self.vol=717.391, self.amt=15252091.2986, ukdf['pct'].iloc[-1]=0.001309 , ukdf['amount'].iloc[-1]=15252091.2986, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5906, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-285527.41904921296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21274.17202621', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14956
self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121500', self.closeTime='121959', self.symbol='BTCUSDT', self.open=21273.1, self.close=21275.1, self.high=21275.1, self.low=21250.5, self.vol=576.447, self.amt=12257909.9248 
127.0.0.1 - - [18/Jan/2023 12:20:00] "POST / HTTP/1.1" 200 -
2023-01-18 12:20:00,572:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5903  20230118   115500    115959  ...         0.0        0.0       0
5904  20230118   120000    120459  ...         0.0        0.0       0
5905  20230118   120500    120959  ...         0.0        0.0       0
5906  20230118   121000    121459  ...         0.0        0.0       0
5907  20230118   121500    121959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 12:20:00,579:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121500', self.closeTime='121959',self.symbol='BTCUSDT',self.open=21273.1, self.close=21275.1, self.high=21275.1, self.low=21250.5, self.vol=576.447, self.amt=12257909.9248, ukdf['pct'].iloc[-1]=9.4e-05 , ukdf['amount'].iloc[-1]=12257909.9248, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5907, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-285555.3988997944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21274.63699315', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674015299, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121459', self.symbol='BTCUSDT', self.open=21245.3, self.close=21273.1, self.high=21273.1, self.low=21245.2 
2023-01-18 12:15:00,654:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674015299, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121459',self.symbol='BTCUSDT',self.open=21245.3, self.close=21273.1, self.high=21273.1, self.low=21245.2   
127.0.0.1 - - [18/Jan/2023 12:15:00] "POST / HTTP/1.1" 200 -
2023-01-18 12:15:00,694:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1582  20230118   115000    115459  1674014099  ...  21290.3 -0.000971   1582    4
1583  20230118   115500    115959  1674014399  ...  21254.1 -0.001700   1583    5
1584  20230118   120000    120459  1674014699  ...  21236.9 -0.000367   1584    0
1585  20230118   120500    120959  1674014999  ...  21226.6 -0.000047   1585    1
1586  20230118   121000    121459  1674015299  ...  21245.2  0.001309   1586    2

[5 rows x 11 columns]
2023-01-18 12:15:00,694:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=503, self.factor=0.5007510148303588, self.count=15522 

self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121500', self.closeTime='121959', self.symbol='BTCUSDT', self.open=21273.1, self.close=21275.1, self.high=21275.1, self.low=21250.5 
2023-01-18 12:20:00,444:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121500', self.closeTime='121959',self.symbol='BTCUSDT',self.open=21273.1, self.close=21275.1, self.high=21275.1, self.low=21250.5   
127.0.0.1 - - [18/Jan/2023 12:20:00] "POST / HTTP/1.1" 200 -
2023-01-18 12:20:00,517:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1583  20230118   115500    115959  1674014399  ...  21254.1 -0.001700   1583    5
1584  20230118   120000    120459  1674014699  ...  21236.9 -0.000367   1584    0
1585  20230118   120500    120959  1674014999  ...  21226.6 -0.000047   1585    1
1586  20230118   121000    121459  1674015299  ...  21245.2  0.001309   1586    2
1587  20230118   121500    121959  1674015599  ...  21250.5  0.000094   1587    3

[5 rows x 11 columns]
2023-01-18 12:20:00,517:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-18 12:00:17,568:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5778  20230118    092959  21201.1  ...  51.250000  0.522895  0.542459
5779  20230118    095959  21184.0  ...  51.250000  0.535881  0.549184
5780  20230118    102959  21243.9  ...  51.250000  0.525495  0.560084
5781  20230118    105959  21201.2  ...  51.250000  0.545191  0.560134
5782  20230118    112959  21292.5  ...  51.666667  0.552030  0.556531

[5 rows x 33 columns]
0.5249537892791127
acc is : 0.5249537892791127
2023-01-18 12:00:17,632:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.496475  0.503525       1  ...  1.055173   1.0    0.0  1.255772
537     0  0.519459  0.480541       0  ...  1.053053   1.0    0.0  1.253248
538     0  0.502474  0.497526       1  ...  1.057697   1.0    0.0  1.258775
539     0  0.536032  0.463968       1  ...  1.059370   1.0    0.0  1.260767
540     0  0.524045  0.475955       0  ...  1.055680   1.0    0.0  1.256375

[5 rows x 10 columns]
2023-01-18 12:00:17,644:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496349  0.503651       1  ...  1.055173   1.0    0.0  1.260661
46     0  0.519526  0.480474       0  ...  1.053053   1.0    0.0  1.252094
47     0  0.502428  0.497572       1  ...  1.057697   1.0    0.0  1.257304
48     0  0.535876  0.464124       1  ...  1.059370   1.0    0.0  1.262880
49     0  0.524045  0.475955       0  ...  1.055680   1.0    0.0  1.256375

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

503  20230118   115000    115959  1674014399    21309  21254.1 -0.002670
2023-01-18 12:00:01,641:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/Jan/2023 12:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7760 

self.closeSec=1674014999, self.tradeDate='20230118', self.openTime='120000', self.closeTime='120959', self.symbol='BTCUSDT', self.open='21254.1', self.close='21245.3'
2023-01-18 12:10:01,530:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674014999, self.tradeDate='20230118', self.openTime='120000', self.closeTime='120959',self.symbol='BTCUSDT',self.open='21254.1', self.close='21245.3'
2023-01-18 12:10:01,571:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
500  20230118   112000    112959  1674012599    21356  21328.4 -0.001316
501  20230118   113000    113959  1674013199  21328.4  21295.2 -0.001557
502  20230118   114000    114959  1674013799  21295.3    21311  0.000742
503  20230118   115000    115959  1674014399    21309  21254.1 -0.002670
504  20230118   120000    120959  1674014999  21254.1  21245.3 -0.000414
2023-01-18 12:10:01,571:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7761 

self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121959', self.symbol='BTCUSDT', self.open='21245.3', self.close='21275.1'
2023-01-18 12:20:00,531:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121959',self.symbol='BTCUSDT',self.open='21245.3', self.close='21275.1'
127.0.0.1 - - [18/Jan/2023 12:20:00] "POST / HTTP/1.1" 200 -
2023-01-18 12:20:00,545:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
501  20230118   113000    113959  1674013199  21328.4  21295.2 -0.001557
502  20230118   114000    114959  1674013799  21295.3    21311  0.000742
503  20230118   115000    115959  1674014399    21309  21254.1 -0.002670
504  20230118   120000    120959  1674014999  21254.1  21245.3 -0.000414
505  20230118   121000    121959  1674015599  21245.3  21275.1  0.001403
2023-01-18 12:20:00,545:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17495  20230118   115000    115959  1674014399    21309  21254.1
2023-01-18 12:00:01,653:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7761 

self.closeSec=1674014999, self.tradeDate='20230118', self.openTime='120000', self.closeTime='120959', self.symbol='BTCUSDT', self.open='21254.1', self.close='21245.3'
127.0.0.1 - - [18/Jan/2023 12:10:01] "POST / HTTP/1.1" 200 -
2023-01-18 12:10:01,541:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674014999, self.tradeDate='20230118', self.openTime='120000', self.closeTime='120959',self.symbol='BTCUSDT',self.open='21254.1', self.close='21245.3'
2023-01-18 12:10:01,553:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17492  20230118   112000    112959  1674012599    21356  21328.4
17493  20230118   113000    113959  1674013199  21328.4  21295.2
17494  20230118   114000    114959  1674013799  21295.3    21311
17495  20230118   115000    115959  1674014399    21309  21254.1
17496  20230118   120000    120959  1674014999  21254.1  21245.3
2023-01-18 12:10:01,553:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7762 

self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121959', self.symbol='BTCUSDT', self.open='21245.3', self.close='21275.1'
2023-01-18 12:20:00,536:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121959',self.symbol='BTCUSDT',self.open='21245.3', self.close='21275.1'
127.0.0.1 - - [18/Jan/2023 12:20:00] "POST / HTTP/1.1" 200 -
2023-01-18 12:20:00,553:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17493  20230118   113000    113959  1674013199  21328.4  21295.2
17494  20230118   114000    114959  1674013799  21295.3    21311
17495  20230118   115000    115959  1674014399    21309  21254.1
17496  20230118   120000    120959  1674014999  21254.1  21245.3
17497  20230118   121000    121959  1674015599  21245.3  21275.1
2023-01-18 12:20:00,568:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12167  20230118   115000    115959  1674014399    21309  21254.1
2023-01-18 12:00:01,665:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Jan/2023 12:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7761 

self.closeSec=1674014999, self.tradeDate='20230118', self.openTime='120000', self.closeTime='120959', self.symbol='BTCUSDT', self.open='21254.1', self.close='21245.3'
2023-01-18 12:10:01,532:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674014999, self.tradeDate='20230118', self.openTime='120000', self.closeTime='120959',self.symbol='BTCUSDT',self.open='21254.1', self.close='21245.3'
2023-01-18 12:10:01,579:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12164  20230118   112000    112959  1674012599    21356  21328.4
12165  20230118   113000    113959  1674013199  21328.4  21295.2
12166  20230118   114000    114959  1674013799  21295.3    21311
12167  20230118   115000    115959  1674014399    21309  21254.1
12168  20230118   120000    120959  1674014999  21254.1  21245.3
2023-01-18 12:10:01,579:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7762 

self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121959', self.symbol='BTCUSDT', self.open='21245.3', self.close='21275.1'
2023-01-18 12:20:00,558:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121959',self.symbol='BTCUSDT',self.open='21245.3', self.close='21275.1'
127.0.0.1 - - [18/Jan/2023 12:20:00] "POST / HTTP/1.1" 200 -
2023-01-18 12:20:00,584:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12165  20230118   113000    113959  1674013199  21328.4  21295.2
12166  20230118   114000    114959  1674013799  21295.3    21311
12167  20230118   115000    115959  1674014399    21309  21254.1
12168  20230118   120000    120959  1674014999  21254.1  21245.3
12169  20230118   121000    121959  1674015599  21245.3  21275.1
2023-01-18 12:20:00,584:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Jan/2023 12:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10953
self.closeSec=1674015299, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121459', self.symbol='BTCUSDT', self.open=21245.3, self.close=21273.1, self.high=21273.1, self.low=21245.2, self.vol=717.391, self.amt=15252091.2986 
2023-01-18 12:15:00,715:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5902  20230118   115000    115459  ...         0.0        0.0       0
5903  20230118   115500    115959  ...         0.0        0.0       0
5904  20230118   120000    120459  ...         0.0        0.0       0
5905  20230118   120500    120959  ...         0.0        0.0       0
5906  20230118   121000    121459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 12:15:00,715:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674015299, self.tradeDate='20230118', self.openTime='121000', self.closeTime='121459',self.symbol='BTCUSDT',self.open=21245.3, self.close=21273.1, self.high=21273.1, self.low=21245.2, self.vol=717.391, self.amt=15252091.2986, ukdf['pct'].iloc[-1]=0.001309 , ukdf['amount'].iloc[-1]=15252091.2986, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5906, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10954
self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121500', self.closeTime='121959', self.symbol='BTCUSDT', self.open=21273.1, self.close=21275.1, self.high=21275.1, self.low=21250.5, self.vol=576.447, self.amt=12257909.9248 
127.0.0.1 - - [18/Jan/2023 12:20:00] "POST / HTTP/1.1" 200 -
2023-01-18 12:20:00,565:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5903  20230118   115500    115959  ...         0.0        0.0       0
5904  20230118   120000    120459  ...         0.0        0.0       0
5905  20230118   120500    120959  ...         0.0        0.0       0
5906  20230118   121000    121459  ...         0.0        0.0       0
5907  20230118   121500    121959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 12:20:00,567:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674015599, self.tradeDate='20230118', self.openTime='121500', self.closeTime='121959',self.symbol='BTCUSDT',self.open=21273.1, self.close=21275.1, self.high=21275.1, self.low=21250.5, self.vol=576.447, self.amt=12257909.9248, ukdf['pct'].iloc[-1]=9.4e-05 , ukdf['amount'].iloc[-1]=12257909.9248, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5907, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
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


