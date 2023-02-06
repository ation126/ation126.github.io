# 20230206 16:35:52

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [06/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20478
self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=22861.0, self.close=22837.8, self.high=22865.0, self.low=22836.4, self.vol=1159.846, self.amt=26500698.2678 
2023-02-06 16:30:00,658:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230206   160500    160959  ...         0.0        0.0       0
5954  20230206   161000    161459  ...         0.0        0.0       0
5955  20230206   161500    161959  ...         0.0        0.0       0
5956  20230206   162000    162459  ...         0.0        0.0       0
5957  20230206   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 16:30:00,659:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=22861.0, self.close=22837.8, self.high=22865.0, self.low=22836.4, self.vol=1159.846, self.amt=26500698.2678, ukdf['pct'].iloc[-1]=-0.00101 , ukdf['amount'].iloc[-1]=26500698.2678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-379667.0937378736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22838.5776811', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20479
self.closeSec=1675672499, self.tradeDate='20230206', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=22837.8, self.close=22865.2, self.high=22884.9, self.low=22830.0, self.vol=1511.692, self.amt=34556293.9693 
2023-02-06 16:35:00,801:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230206   161000    161459  ...         0.0        0.0       0
5955  20230206   161500    161959  ...         0.0        0.0       0
5956  20230206   162000    162459  ...         0.0        0.0       0
5957  20230206   162500    162959  ...         0.0        0.0       0
5958  20230206   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 16:35:00,801:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675672499, self.tradeDate='20230206', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=22837.8, self.close=22865.2, self.high=22884.9, self.low=22830.0, self.vol=1511.692, self.amt=34556293.9693, ukdf['pct'].iloc[-1]=0.0012 , ukdf['amount'].iloc[-1]=34556293.9693, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-381343.66756156256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22866.43885206', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1637  20230206   162500    162959  1675672199  ...  22836.4 -0.001010   1637    5

[5 rows x 11 columns]
2023-02-06 16:30:00,573:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-06 16:30:00,609:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230206   142500    142959  1675664999  ...  0.000426   1613    5  0.663529
230  20230206   145500    145959  1675666799  ... -0.000158   1619    5  0.666329
231  20230206   152500    152959  1675668599  ... -0.000329   1625    5  0.667487
232  20230206   155500    155959  1675670399  ... -0.000118   1631    5  0.666830
233  20230206   162500    162959  1675672199  ... -0.001010   1637    5  0.666235

[5 rows x 12 columns]
2023-02-06 16:30:00,638:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2061630, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230206, closeTime:162959, close:22837.8, total:928613.5591976999, factor:0.6662350336157611, factorCnt:0, side:buy 
127.0.0.1 - - [06/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6662350336157611, self.count=21045 

self.closeSec=1675672499, self.tradeDate='20230206', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=22837.8, self.close=22865.2, self.high=22884.9, self.low=22830.0 
2023-02-06 16:35:00,718:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675672499, self.tradeDate='20230206', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=22837.8, self.close=22865.2, self.high=22884.9, self.low=22830.0   
2023-02-06 16:35:00,775:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230206   161000    161459  1675671299  ...  22877.3  0.000498   1634    2
1635  20230206   161500    161959  1675671599  ...  22861.7 -0.001053   1635    3
1636  20230206   162000    162459  1675671899  ...  22852.3 -0.000376   1636    4
1637  20230206   162500    162959  1675672199  ...  22836.4 -0.001010   1637    5
1638  20230206   163000    163459  1675672499  ...  22830.0  0.001200   1638    0

[5 rows x 11 columns]
2023-02-06 16:35:00,775:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-06 16:30:32,416:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230206    135959  22700.6  ...  44.583333  0.390235  0.725514
5788  20230206    142959  22771.6  ...  45.000000  0.394390  0.728578
5789  20230206    145959  22784.4  ...  45.000000  0.392657  0.732026
5790  20230206    152959  22776.1  ...  45.000000  0.407340  0.731223
5791  20230206    155959  22820.4  ...  45.416667  0.424150  0.725641

[5 rows x 33 columns]
0.503690036900369
acc is : 0.503690036900369
2023-02-06 16:30:32,569:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.490037  0.509963       1  ...  1.054135  -1.0    0.0  0.983201
538     1  0.483076  0.516924       0  ...  1.054505  -1.0    0.0  0.982855
539     1  0.478070  0.521930       1  ...  1.052459  -1.0    0.0  0.984763
540     1  0.494657  0.505343       1  ...  1.050047  -1.0    0.0  0.987020
541     0  0.514428  0.485572       0  ...  1.051649  -1.0    0.0  0.985514

[5 rows x 10 columns]
2023-02-06 16:30:32,617:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488548  0.511452       1  ...  1.054135  -1.0    0.0  0.986538
46     1  0.482365  0.517635       0  ...  1.054505  -1.0    0.0  0.987710
47     1  0.478181  0.521819       1  ...  1.052459  -1.0    0.0  0.989863
48     1  0.494107  0.505893       1  ...  1.050047  -1.0    0.0  0.984509
49     0  0.514428  0.485572       0  ...  1.051649  -1.0    0.0  0.985514

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '26113.3243', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22843.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230206   160000    160959  1675670999  22873.1  22882.2  0.000415
2023-02-06 16:10:01,557:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10521 

self.closeSec=1675671599, self.tradeDate='20230206', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22882.2', self.close='22869.5'
2023-02-06 16:20:00,734:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675671599, self.tradeDate='20230206', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22882.2', self.close='22869.5'
127.0.0.1 - - [06/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-06 16:20:00,746:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230206   153000    153959  1675669199  22820.4  22838.4  0.000789
526  20230206   154000    154959  1675669799  22838.4    22864  0.001121
527  20230206   155000    155959  1675670399  22864.1  22872.7  0.000381
528  20230206   160000    160959  1675670999  22873.1  22882.2  0.000415
529  20230206   161000    161959  1675671599  22882.2  22869.5 -0.000555
2023-02-06 16:20:00,747:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10522 

self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='22869.6', self.close='22837.8'
127.0.0.1 - - [06/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-06 16:30:00,950:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='22869.6', self.close='22837.8'
2023-02-06 16:30:00,981:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230206   154000    154959  1675669799  22838.4    22864  0.001121
527  20230206   155000    155959  1675670399  22864.1  22872.7  0.000381
528  20230206   160000    160959  1675670999  22873.1  22882.2  0.000415
529  20230206   161000    161959  1675671599  22882.2  22869.5 -0.000555
530  20230206   162000    162959  1675672199  22869.6  22837.8 -0.001386
2023-02-06 16:30:00,981:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230206   160000    160959  1675670999  22873.1  22882.2
2023-02-06 16:10:01,563:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10522 

self.closeSec=1675671599, self.tradeDate='20230206', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22882.2', self.close='22869.5'
127.0.0.1 - - [06/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-06 16:20:00,754:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675671599, self.tradeDate='20230206', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22882.2', self.close='22869.5'
2023-02-06 16:20:00,779:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230206   153000    153959  1675669199  22820.4  22838.4
17518  20230206   154000    154959  1675669799  22838.4    22864
17519  20230206   155000    155959  1675670399  22864.1  22872.7
17520  20230206   160000    160959  1675670999  22873.1  22882.2
17521  20230206   161000    161959  1675671599  22882.2  22869.5
2023-02-06 16:20:00,783:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10523 

self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='22869.6', self.close='22837.8'
127.0.0.1 - - [06/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-06 16:30:00,938:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='22869.6', self.close='22837.8'
2023-02-06 16:30:00,979:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230206   154000    154959  1675669799  22838.4    22864
17519  20230206   155000    155959  1675670399  22864.1  22872.7
17520  20230206   160000    160959  1675670999  22873.1  22882.2
17521  20230206   161000    161959  1675671599  22882.2  22869.5
17522  20230206   162000    162959  1675672199  22869.6  22837.8
2023-02-06 16:30:00,981:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230206   160000    160959  1675670999  22873.1  22882.2
2023-02-06 16:10:01,553:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10522 

self.closeSec=1675671599, self.tradeDate='20230206', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22882.2', self.close='22869.5'
2023-02-06 16:20:00,777:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675671599, self.tradeDate='20230206', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22882.2', self.close='22869.5'
127.0.0.1 - - [06/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-06 16:20:00,799:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230206   153000    153959  1675669199  22820.4  22838.4
12190  20230206   154000    154959  1675669799  22838.4    22864
12191  20230206   155000    155959  1675670399  22864.1  22872.7
12192  20230206   160000    160959  1675670999  22873.1  22882.2
12193  20230206   161000    161959  1675671599  22882.2  22869.5
2023-02-06 16:20:00,800:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10523 

self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='22869.6', self.close='22837.8'
127.0.0.1 - - [06/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-06 16:30:00,926:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='22869.6', self.close='22837.8'
2023-02-06 16:30:00,967:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230206   154000    154959  1675669799  22838.4    22864
12191  20230206   155000    155959  1675670399  22864.1  22872.7
12192  20230206   160000    160959  1675670999  22873.1  22882.2
12193  20230206   161000    161959  1675671599  22882.2  22869.5
12194  20230206   162000    162959  1675672199  22869.6  22837.8
2023-02-06 16:30:00,967:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [06/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16476
self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=22861.0, self.close=22837.8, self.high=22865.0, self.low=22836.4, self.vol=1159.846, self.amt=26500698.2678 
2023-02-06 16:30:00,690:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230206   160500    160959  ...         0.0        0.0       0
5954  20230206   161000    161459  ...         0.0        0.0       0
5955  20230206   161500    161959  ...         0.0        0.0       0
5956  20230206   162000    162459  ...         0.0        0.0       0
5957  20230206   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 16:30:00,690:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675672199, self.tradeDate='20230206', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=22861.0, self.close=22837.8, self.high=22865.0, self.low=22836.4, self.vol=1159.846, self.amt=26500698.2678, ukdf['pct'].iloc[-1]=-0.00101 , ukdf['amount'].iloc[-1]=26500698.2678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16477
self.closeSec=1675672499, self.tradeDate='20230206', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=22837.8, self.close=22865.2, self.high=22884.9, self.low=22830.0, self.vol=1511.692, self.amt=34556293.9693 
127.0.0.1 - - [06/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-06 16:35:00,793:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230206   161000    161459  ...         0.0        0.0       0
5955  20230206   161500    161959  ...         0.0        0.0       0
5956  20230206   162000    162459  ...         0.0        0.0       0
5957  20230206   162500    162959  ...         0.0        0.0       0
5958  20230206   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 16:35:00,797:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675672499, self.tradeDate='20230206', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=22837.8, self.close=22865.2, self.high=22884.9, self.low=22830.0, self.vol=1511.692, self.amt=34556293.9693, ukdf['pct'].iloc[-1]=0.0012 , ukdf['amount'].iloc[-1]=34556293.9693, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230206   040000    075959  1675641599  ...    721  0.718608  0.611415     1.0
722  20230206   080000    115959  1675655999  ...    722  0.764930  0.790011     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-31486.8084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22892', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [06/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=438
self.closeSec=1675670399, self.tradeDate='20230206', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22892.0, self.close=22872.7, self.high=22924.0, self.low=22600.0, self.vol=59449.276, self.amt=1353709472.4157 
2023-02-06 16:00:01,170:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675670399, self.tradeDate='20230206', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22892.0, self.close=22872.7, self.high=22924.0, self.low=22600.0, self.vol=59449.276, self.amt=1353709472.4157 
2023-02-06 16:00:01,200:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230205   200000    235959  ...  103064.491  2.387031e+09 -0.011129
720  20230206   000000    035959  ...  131414.742  3.015818e+09 -0.008864
721  20230206   040000    075959  ...   47187.259  1.081561e+09  0.001734
722  20230206   080000    115959  ...   41294.353  9.483247e+08 -0.001627
723  20230206   120000    155959  ...   59449.276  1.353709e+09 -0.000839

[5 rows x 11 columns]
2023-02-06 16:00:02,524:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230205   200000    235959  1675612799  ...    719  0.412451 -0.451433     NaN
720  20230206   000000    035959  1675627199  ...    720  0.367856 -0.581595     NaN
721  20230206   040000    075959  1675641599  ...    721  0.718608  0.611415     1.0
722  20230206   080000    115959  1675655999  ...    722  0.764930  0.790011     1.0
723  20230206   120000    155959  1675670399  ...    723  0.662380  0.457873     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-32152.06827318084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22874.92629419', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


