# 20221207 18:15:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [07/Dec/2022 18:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2930
self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180500', self.closeTime='180959', self.symbol='BTCUSDT', self.open=16815.0, self.close=16814.6, self.high=16819.8, self.low=16811.1, self.vol=861.044, self.amt=14479176.5697 
2022-12-07 18:10:01,697:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5973  20221207   174500    174959  ...    0.150558   0.286456       0
5974  20221207   175000    175459  ...    0.150393   0.286371       0
5975  20221207   175500    175959  ...    0.150227   0.286286       0
5976  20221207   180000    180459  ...    0.150062   0.286200       0
5977  20221207   180500    180959  ...    0.149898   0.286117       0

[5 rows x 18 columns]
2022-12-07 18:10:01,697:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180500', self.closeTime='180959',self.symbol='BTCUSDT',self.open=16815.0, self.close=16814.6, self.high=16819.8, self.low=16811.1, self.vol=861.044, self.amt=14479176.5697, ukdf['pct'].iloc[-1]=-3e-05 , ukdf['amount'].iloc[-1]=14479176.5697, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5977, value=0.0, value_mean=0.14989780008059964, signal=0, value_std=0.2861172066971261 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17223.98709830512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16815.52685287', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2931
self.closeSec=1670408099, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181459', self.symbol='BTCUSDT', self.open=16814.6, self.close=16799.3, self.high=16814.7, self.low=16797.3, self.vol=1317.276, self.amt=22137617.3635 
127.0.0.1 - - [07/Dec/2022 18:15:00] "POST / HTTP/1.1" 200 -
2022-12-07 18:15:00,576:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5974  20221207   175000    175459  ...    0.150393   0.286371       0
5975  20221207   175500    175959  ...    0.150227   0.286286       0
5976  20221207   180000    180459  ...    0.150062   0.286200       0
5977  20221207   180500    180959  ...    0.149898   0.286117       0
5978  20221207   181000    181459  ...    0.149734   0.286034       0

[5 rows x 18 columns]
2022-12-07 18:15:00,577:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670408099, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181459',self.symbol='BTCUSDT',self.open=16814.6, self.close=16799.3, self.high=16814.7, self.low=16797.3, self.vol=1317.276, self.amt=22137617.3635, ukdf['pct'].iloc[-1]=-0.00091 , ukdf['amount'].iloc[-1]=22137617.3635, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5978, value=0.0, value_mean=0.1497336153169149, signal=0, value_std=0.2860335766819014 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16254.033630768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16799.408243', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6038728964274044, self.count=3496 

self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180500', self.closeTime='180959', self.symbol='BTCUSDT', self.open=16815.0, self.close=16814.6, self.high=16819.8, self.low=16811.1 
2022-12-07 18:10:01,644:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180500', self.closeTime='180959',self.symbol='BTCUSDT',self.open=16815.0, self.close=16814.6, self.high=16819.8, self.low=16811.1   
2022-12-07 18:10:01,681:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1653  20221207   174500    174959  1670406599  ...  16795.2  0.000631   1653    3
1654  20221207   175000    175459  1670406899  ...  16808.5  0.000303   1654    4
1655  20221207   175500    175959  1670407199  ...  16812.9  0.000648   1655    5
1656  20221207   180000    180459  1670407499  ...  16812.9 -0.000648   1656    0
1657  20221207   180500    180959  1670407799  ...  16811.1 -0.000030   1657    1

[5 rows x 11 columns]
2022-12-07 18:10:01,682:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Dec/2022 18:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6038728964274044, self.count=3497 

self.closeSec=1670408099, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181459', self.symbol='BTCUSDT', self.open=16814.6, self.close=16799.3, self.high=16814.7, self.low=16797.3 
2022-12-07 18:15:00,533:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670408099, self.tradeDate='20221207', self.openTime='181000', self.closeTime='181459',self.symbol='BTCUSDT',self.open=16814.6, self.close=16799.3, self.high=16814.7, self.low=16797.3   
2022-12-07 18:15:00,546:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1654  20221207   175000    175459  1670406899  ...  16808.5  0.000303   1654    4
1655  20221207   175500    175959  1670407199  ...  16812.9  0.000648   1655    5
1656  20221207   180000    180459  1670407499  ...  16812.9 -0.000648   1656    0
1657  20221207   180500    180959  1670407799  ...  16811.1 -0.000030   1657    1
1658  20221207   181000    181459  1670408099  ...  16797.3 -0.000910   1658    2

[5 rows x 11 columns]
2022-12-07 18:15:00,547:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-07 18:00:23,529:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5790  20221207    152959  16945.7  ...  50.833333  0.404902  0.543367
5791  20221207    155959  16807.3  ...  50.416667  0.386729  0.567871
5792  20221207    162959  16755.4  ...  50.833333  0.399597  0.579164
5793  20221207    165959  16780.9  ...  50.833333  0.402728  0.588875
5794  20221207    172959  16785.8  ...  51.250000  0.416873  0.594164

[5 rows x 33 columns]
0.5285451197053407
acc is : 0.5285451197053407
2022-12-07 18:00:23,619:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
538     1  0.434081  0.565919       0  ...  0.951740  -1.0    0.0  1.007589
539     1  0.450284  0.549716       1  ...  0.950371  -1.0    0.0  1.009038
540     1  0.468200  0.531800       1  ...  0.950037  -1.0    0.0  1.009393
541     1  0.466497  0.533503       1  ...  0.948515  -1.0    0.0  1.011011
542     1  0.478047  0.521953       1  ...  0.947759  -1.0    0.0  1.011816

[5 rows x 10 columns]
2022-12-07 18:00:23,630:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.434262  0.565738       0  ...  0.951740  -1.0    0.0  1.011170
46     1  0.450379  0.549621       1  ...  0.950371  -1.0    0.0  1.007118
47     1  0.468509  0.531491       1  ...  0.950037  -1.0    0.0  1.009727
48     1  0.466497  0.533503       1  ...  0.948515  -1.0    0.0  1.011011
49     1  0.478047  0.521953       1  ...  0.947759  -1.0    0.0  1.011816

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '5549.38735834', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16821.6155355', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

538  20221207   174000    174959  1670406599  16799.9    16810  0.000601
2022-12-07 17:50:00,520:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1747 

self.closeSec=1670407199, self.tradeDate='20221207', self.openTime='175000', self.closeTime='175959', self.symbol='BTCUSDT', self.open='16810', self.close='16826'
2022-12-07 18:00:01,176:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670407199, self.tradeDate='20221207', self.openTime='175000', self.closeTime='175959',self.symbol='BTCUSDT',self.open='16810', self.close='16826'
127.0.0.1 - - [07/Dec/2022 18:00:01] "POST / HTTP/1.1" 200 -
2022-12-07 18:00:01,189:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
535  20221207   171000    171959  1670404799    16800  16797.9 -0.000125
536  20221207   172000    172959  1670405399    16798  16812.6  0.000875
537  20221207   173000    173959  1670405999  16812.5  16799.9 -0.000755
538  20221207   174000    174959  1670406599  16799.9    16810  0.000601
539  20221207   175000    175959  1670407199    16810    16826  0.000952
2022-12-07 18:00:01,189:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Dec/2022 18:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1748 

self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180000', self.closeTime='180959', self.symbol='BTCUSDT', self.open='16825.9', self.close='16814.7'
2022-12-07 18:10:01,978:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180000', self.closeTime='180959',self.symbol='BTCUSDT',self.open='16825.9', self.close='16814.7'
2022-12-07 18:10:01,988:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
536  20221207   172000    172959  1670405399    16798  16812.6  0.000875
537  20221207   173000    173959  1670405999  16812.5  16799.9 -0.000755
538  20221207   174000    174959  1670406599  16799.9    16810  0.000601
539  20221207   175000    175959  1670407199    16810    16826  0.000952
540  20221207   180000    180959  1670407799  16825.9  16814.7 -0.000672
2022-12-07 18:10:01,989:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17384  20221207   172000    172959  1670405399    16798  16812.6
17385  20221207   173000    173959  1670405999  16812.5  16799.9
17386  20221207   174000    174959  1670406599  16799.9    16810
17387  20221207   175000    175959  1670407199    16810    16826 

2022-12-07 18:00:01,364:INFO:pyemd2:main.py:137:handleKline:185189: panel.iloc[-5:,:] :
            emd  pct   pct_pre tradeDate
17280 -0.097956  0.0 -0.009408  20221207
2022-12-07 18:00:01,382:INFO:pyemd2:main.py:147:handleKline:185189: df_panel.iloc[-5:,:] :
    tradeDate       emd  pct   pct_pre       thd
128  20221203 -0.479754  0.0  0.003447 -0.065858
129  20221204 -0.749898  0.0  0.002253 -0.340296
130  20221205 -1.145471  0.0  0.015281 -0.731653
131  20221206 -0.024328  0.0 -0.006995  0.385181
132  20221207 -0.097956  0.0 -0.009408  0.310503
2022-12-07 18:00:01,546:INFO:pyemd2:main.py:196:queryContractAssets:185189: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '940056.5307028', 'total': '940056.5307028', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
127.0.0.1 - - [07/Dec/2022 18:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1749 

self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180000', self.closeTime='180959', self.symbol='BTCUSDT', self.open='16825.9', self.close='16814.7'
2022-12-07 18:10:02,027:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180000', self.closeTime='180959',self.symbol='BTCUSDT',self.open='16825.9', self.close='16814.7'
2022-12-07 18:10:02,050:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17384  20221207   172000    172959  1670405399    16798  16812.6
17385  20221207   173000    173959  1670405999  16812.5  16799.9
17386  20221207   174000    174959  1670406599  16799.9    16810
17387  20221207   175000    175959  1670407199    16810    16826
17388  20221207   180000    180959  1670407799  16825.9  16814.7
2022-12-07 18:10:02,053:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12202  20221207   174000    174959  1670406599  16799.9    16810
2022-12-07 17:50:00,523:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Dec/2022 18:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1748 

self.closeSec=1670407199, self.tradeDate='20221207', self.openTime='175000', self.closeTime='175959', self.symbol='BTCUSDT', self.open='16810', self.close='16826'
2022-12-07 18:00:01,164:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670407199, self.tradeDate='20221207', self.openTime='175000', self.closeTime='175959',self.symbol='BTCUSDT',self.open='16810', self.close='16826'
2022-12-07 18:00:01,173:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12199  20221207   171000    171959  1670404799    16800  16797.9
12200  20221207   172000    172959  1670405399    16798  16812.6
12201  20221207   173000    173959  1670405999  16812.5  16799.9
12202  20221207   174000    174959  1670406599  16799.9    16810
12203  20221207   175000    175959  1670407199    16810    16826
2022-12-07 18:00:01,190:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Dec/2022 18:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1749 

self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180000', self.closeTime='180959', self.symbol='BTCUSDT', self.open='16825.9', self.close='16814.7'
2022-12-07 18:10:02,007:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670407799, self.tradeDate='20221207', self.openTime='180000', self.closeTime='180959',self.symbol='BTCUSDT',self.open='16825.9', self.close='16814.7'
2022-12-07 18:10:02,022:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12200  20221207   172000    172959  1670405399    16798  16812.6
12201  20221207   173000    173959  1670405999  16812.5  16799.9
12202  20221207   174000    174959  1670406599  16799.9    16810
12203  20221207   175000    175959  1670407199    16810    16826
12204  20221207   180000    180959  1670407799  16825.9  16814.7
2022-12-07 18:10:02,022:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0
722  20221207   080000    115959  1670385599  ...    722  1.084938  2.647182     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-16610.74134876276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17018.14662842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [07/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=72
self.closeSec=1670399999, self.tradeDate='20221207', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17017.4, self.close=16755.7, self.high=17036.6, self.low=16719.1, self.vol=97327.468, self.amt=1641000514.5662 
2022-12-07 16:00:00,889:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670399999, self.tradeDate='20221207', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17017.4, self.close=16755.7, self.high=17036.6, self.low=16719.1, self.vol=97327.468, self.amt=1641000514.5662 
2022-12-07 16:00:00,923:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221206   200000    235959  ...  69024.422  1.172189e+09  0.000018
720  20221207   000000    035959  ...  56413.953  9.566549e+08 -0.000636
721  20221207   040000    075959  ...  51125.606  8.698549e+08  0.006714
722  20221207   080000    115959  ...  42347.692  7.222808e+08 -0.003548
723  20221207   120000    155959  ...  97327.468  1.641001e+09 -0.015378

[5 rows x 11 columns]
2022-12-07 16:00:02,301:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221206   200000    235959  1670342399  ...    719  0.716348  1.398787     1.0
720  20221207   000000    035959  1670356799  ...    720  1.120770  3.120988     1.0
721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0
722  20221207   080000    115959  1670385599  ...    722  1.084938  2.647182     1.0
723  20221207   120000    155959  1670399999  ...    723  0.702535  1.042009     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-32007.63118873926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16755.49967267', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


