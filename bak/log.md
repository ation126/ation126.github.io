# 20230209 00:35:55

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [09/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21150
self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=22712.2, self.close=22797.5, self.high=22815.0, self.low=22662.9, self.vol=10285.978, self.amt=233756168.8211 
2023-02-09 00:30:00,647:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230209   000500    000959  ...         0.0        0.0       0
5762  20230209   001000    001459  ...         0.0        0.0       0
5763  20230209   001500    001959  ...         0.0        0.0       0
5764  20230209   002000    002459  ...         0.0        0.0       0
5765  20230209   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 00:30:00,649:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=22712.2, self.close=22797.5, self.high=22815.0, self.low=22662.9, self.vol=10285.978, self.amt=233756168.8211, ukdf['pct'].iloc[-1]=0.003941 , ukdf['amount'].iloc[-1]=233756168.8211, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-377345.6432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22800', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21151
self.closeSec=1675874099, self.tradeDate='20230209', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=22799.9, self.close=22747.1, self.high=22799.9, self.low=22723.1, self.vol=4114.468, self.amt=93628421.2351 
127.0.0.1 - - [09/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-09 00:35:00,493:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230209   001000    001459  ...         0.0        0.0       0
5763  20230209   001500    001959  ...         0.0        0.0       0
5764  20230209   002000    002459  ...         0.0        0.0       0
5765  20230209   002500    002959  ...         0.0        0.0       0
5766  20230209   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 00:35:00,495:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675874099, self.tradeDate='20230209', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=22799.9, self.close=22747.1, self.high=22799.9, self.low=22723.1, self.vol=4114.468, self.amt=93628421.2351, ukdf['pct'].iloc[-1]=-0.002211 , ukdf['amount'].iloc[-1]=93628421.2351, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-374162.3328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22747.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230209   002000    002459  1675873499  ...  22700.1 -0.002719   1444    4
1445  20230209   002500    002959  1675873799  ...  22662.9  0.003941   1445    5

[5 rows x 11 columns]
2023-02-09 00:30:00,540:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-09 00:30:00,618:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230208   222500    222959  1675866599  ... -0.001594   1709    5  0.329915
198  20230208   225500    225959  1675868399  ...  0.001077   1715    5  0.341985
199  20230208   232500    232959  1675870199  ... -0.000209   1721    5  0.357253
200  20230208   235500    235959  1675871999  ... -0.000538   1727    5  0.372882
201  20230209   002500    002959  1675873799  ...  0.003941   1445    5  0.383490

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=47, self.factor=0.3834901574041486, self.count=21717 

self.closeSec=1675874099, self.tradeDate='20230209', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=22799.9, self.close=22747.1, self.high=22799.9, self.low=22723.1 
2023-02-09 00:35:00,404:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675874099, self.tradeDate='20230209', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=22799.9, self.close=22747.1, self.high=22799.9, self.low=22723.1   
127.0.0.1 - - [09/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-09 00:35:00,466:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230209   001000    001459  1675872899  ...  22789.8 -0.002612   1442    2
1443  20230209   001500    001959  1675873199  ...  22758.4 -0.001167   1443    3
1444  20230209   002000    002459  1675873499  ...  22700.1 -0.002719   1444    4
1445  20230209   002500    002959  1675873799  ...  22662.9  0.003941   1445    5
1446  20230209   003000    003459  1675874099  ...  22723.1 -0.002211   1446    0

[5 rows x 11 columns]
2023-02-09 00:35:00,466:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-09 00:30:32,564:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230208    215959  23057.5  ...  47.500000  0.501999  0.384141
5756  20230208    222959  23104.0  ...  47.500000  0.490188  0.396642
5757  20230208    225959  23056.6  ...  47.083333  0.486648  0.421325
5758  20230208    232959  23042.4  ...  46.666667  0.464531  0.456249
5759  20230208    235959  22949.9  ...  46.666667  0.444946  0.491121

[5 rows x 33 columns]
0.5083487940630798
acc is : 0.5083487940630798
2023-02-09 00:30:32,729:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     1  0.486553  0.513447       0  ...  0.985076  -1.0    0.0  1.003823
535     1  0.466646  0.533354       0  ...  0.985687  -1.0    0.0  1.003200
536     1  0.469942  0.530058       0  ...  0.989640  -1.0    0.0  0.999177
537     1  0.452566  0.547434       0  ...  0.993421  -1.0    0.0  0.995359
538     1  0.450628  0.549372       0  ...  0.996237  -1.0    0.0  0.992538

[5 rows x 10 columns]
2023-02-09 00:30:32,763:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487012  0.512988       0  ...  0.964023  -1.0    0.0  1.001077
46     1  0.467375  0.532625       0  ...  0.964621  -1.0    0.0  1.000456
47     1  0.471360  0.528640       0  ...  0.968489  -1.0    0.0  0.999695
48     1  0.453487  0.546513       0  ...  0.972190  -1.0    0.0  0.994692
49     1  0.450628  0.549372       0  ...  0.996237  -1.0    0.0  0.992538

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '4748.57915183476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22777.36636637', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230209   000000    000959  1675872599  22862.4  22854.5 -0.000341
2023-02-09 00:10:01,580:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10857 

self.closeSec=1675873199, self.tradeDate='20230209', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22854.4', self.close='22769.9'
2023-02-09 00:20:00,736:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675873199, self.tradeDate='20230209', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22854.4', self.close='22769.9'
2023-02-09 00:20:00,798:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230208   233000    233959  1675870799  22949.9  22907.1 -0.001865
574  20230208   234000    234959  1675871399  22907.2  22904.8 -0.000100
575  20230208   235000    235959  1675871999  22904.8  22862.3 -0.001856
576  20230209   000000    000959  1675872599  22862.4  22854.5 -0.000341
577  20230209   001000    001959  1675873199  22854.4  22769.9 -0.003702
2023-02-09 00:20:00,798:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10858 

self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22767.6', self.close='22797.5'
2023-02-09 00:30:00,738:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22767.6', self.close='22797.5'
2023-02-09 00:30:00,793:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230208   234000    234959  1675871399  22907.2  22904.8 -0.000100
575  20230208   235000    235959  1675871999  22904.8  22862.3 -0.001856
576  20230209   000000    000959  1675872599  22862.4  22854.5 -0.000341
577  20230209   001000    001959  1675873199  22854.4  22769.9 -0.003702
578  20230209   002000    002959  1675873799  22767.6  22797.5  0.001212
2023-02-09 00:30:00,795:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230209   000000    000959  1675872599  22862.4  22854.5
2023-02-09 00:10:01,596:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10858 

self.closeSec=1675873199, self.tradeDate='20230209', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22854.4', self.close='22769.9'
127.0.0.1 - - [09/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-09 00:20:00,771:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675873199, self.tradeDate='20230209', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22854.4', self.close='22769.9'
2023-02-09 00:20:00,812:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230208   233000    233959  1675870799  22949.9  22907.1
17422  20230208   234000    234959  1675871399  22907.2  22904.8
17423  20230208   235000    235959  1675871999  22904.8  22862.3
17424  20230209   000000    000959  1675872599  22862.4  22854.5
17425  20230209   001000    001959  1675873199  22854.4  22769.9
2023-02-09 00:20:00,812:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10859 

self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22767.6', self.close='22797.5'
127.0.0.1 - - [09/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 00:30:00,761:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22767.6', self.close='22797.5'
2023-02-09 00:30:00,806:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230208   234000    234959  1675871399  22907.2  22904.8
17423  20230208   235000    235959  1675871999  22904.8  22862.3
17424  20230209   000000    000959  1675872599  22862.4  22854.5
17425  20230209   001000    001959  1675873199  22854.4  22769.9
17426  20230209   002000    002959  1675873799  22767.6  22797.5
2023-02-09 00:30:00,806:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230209   000000    000959  1675872599  22862.4  22854.5
2023-02-09 00:10:01,605:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  127.0.0.1 - - [09/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10858 

self.closeSec=1675873199, self.tradeDate='20230209', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22854.4', self.close='22769.9'
2023-02-09 00:20:00,754:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675873199, self.tradeDate='20230209', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22854.4', self.close='22769.9'
2023-02-09 00:20:00,769:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230208   233000    233959  1675870799  22949.9  22907.1
12238  20230208   234000    234959  1675871399  22907.2  22904.8
12239  20230208   235000    235959  1675871999  22904.8  22862.3
12240  20230209   000000    000959  1675872599  22862.4  22854.5
12241  20230209   001000    001959  1675873199  22854.4  22769.9
2023-02-09 00:20:00,769:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10859 

self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22767.6', self.close='22797.5'
127.0.0.1 - - [09/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 00:30:00,741:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22767.6', self.close='22797.5'
2023-02-09 00:30:00,785:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230208   234000    234959  1675871399  22907.2  22904.8
12239  20230208   235000    235959  1675871999  22904.8  22862.3
12240  20230209   000000    000959  1675872599  22862.4  22854.5
12241  20230209   001000    001959  1675873199  22854.4  22769.9
12242  20230209   002000    002959  1675873799  22767.6  22797.5
2023-02-09 00:30:00,785:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17148
self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=22712.2, self.close=22797.5, self.high=22815.0, self.low=22662.9, self.vol=10285.978, self.amt=233756168.8211 
127.0.0.1 - - [09/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-09 00:30:00,642:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230209   000500    000959  ...         0.0        0.0       0
5762  20230209   001000    001459  ...         0.0        0.0       0
5763  20230209   001500    001959  ...         0.0        0.0       0
5764  20230209   002000    002459  ...         0.0        0.0       0
5765  20230209   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 00:30:00,645:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675873799, self.tradeDate='20230209', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=22712.2, self.close=22797.5, self.high=22815.0, self.low=22662.9, self.vol=10285.978, self.amt=233756168.8211, ukdf['pct'].iloc[-1]=0.003941 , ukdf['amount'].iloc[-1]=233756168.8211, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17149
self.closeSec=1675874099, self.tradeDate='20230209', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=22799.9, self.close=22747.1, self.high=22799.9, self.low=22723.1, self.vol=4114.468, self.amt=93628421.2351 
2023-02-09 00:35:00,494:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230209   001000    001459  ...         0.0        0.0       0
5763  20230209   001500    001959  ...         0.0        0.0       0
5764  20230209   002000    002459  ...         0.0        0.0       0
5765  20230209   002500    002959  ...         0.0        0.0       0
5766  20230209   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-09 00:35:00,494:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675874099, self.tradeDate='20230209', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=22799.9, self.close=22747.1, self.high=22799.9, self.low=22723.1, self.vol=4114.468, self.amt=93628421.2351, ukdf['pct'].iloc[-1]=-0.002211 , ukdf['amount'].iloc[-1]=93628421.2351, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230208   120000    155959  1675843199  ...    723  0.382526 -0.392084     NaN
724  20230208   160000    195959  1675857599  ...    724  0.378819 -0.393258     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-21328.8936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23152.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=452
self.closeSec=1675871999, self.tradeDate='20230208', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23152.8, self.close=22862.3, self.high=23194.3, self.low=22849.9, self.vol=103068.788, self.amt=2372762317.6481 
127.0.0.1 - - [09/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-02-09 00:00:01,333:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675871999, self.tradeDate='20230208', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23152.8, self.close=22862.3, self.high=23194.3, self.low=22849.9, self.vol=103068.788, self.amt=2372762317.6481 
2023-02-09 00:00:01,349:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230208   040000    075959  ...   68836.763  1.596656e+09  0.006497
722  20230208   080000    115959  ...   49143.645  1.145290e+09  0.000624
723  20230208   120000    155959  ...   24681.986  5.730485e+08 -0.001019
724  20230208   160000    195959  ...   32606.039  7.556279e+08 -0.003190
725  20230208   200000    235959  ...  103068.788  2.372762e+09 -0.012547

[5 rows x 11 columns]
2023-02-09 00:00:03,508:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230208   040000    075959  1675814399  ...    721  0.400748 -0.347794     NaN
722  20230208   080000    115959  1675828799  ...    722  0.398882 -0.337792     NaN
723  20230208   120000    155959  1675843199  ...    723  0.382526 -0.392084     NaN
724  20230208   160000    195959  1675857599  ...    724  0.378819 -0.393258     NaN
725  20230208   200000    235959  1675871999  ...    725  0.380896 -0.375045     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-32741.4492', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22859.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


