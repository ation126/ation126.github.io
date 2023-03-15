# 20230315 11:16:17

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31070
self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110500', self.closeTime='110959', self.symbol='BTCUSDT', self.open=24839.3, self.close=24851.0, self.high=24869.7, self.low=24830.2, self.vol=466.266, self.amt=11587088.09 
127.0.0.1 - - [15/Mar/2023 11:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 11:10:02,028:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5889  20230315   104500    104959  ...         0.0        0.0       0
5890  20230315   105000    105459  ...         0.0        0.0       0
5891  20230315   105500    105959  ...         0.0        0.0       0
5892  20230315   110000    110459  ...         0.0        0.0       0
5893  20230315   110500    110959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 11:10:02,031:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110500', self.closeTime='110959',self.symbol='BTCUSDT',self.open=24839.3, self.close=24851.0, self.high=24869.7, self.low=24830.2, self.vol=466.266, self.amt=11587088.09, ukdf['pct'].iloc[-1]=0.000467 , ukdf['amount'].iloc[-1]=11587088.09, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5893, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-500760.6016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24850.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31071
self.closeSec=1678850099, self.tradeDate='20230315', self.openTime='111000', self.closeTime='111459', self.symbol='BTCUSDT', self.open=24850.9, self.close=24834.8, self.high=24856.2, self.low=24834.0, self.vol=704.017, self.amt=17490167.545 
127.0.0.1 - - [15/Mar/2023 11:15:01] "POST / HTTP/1.1" 200 -
2023-03-15 11:15:01,654:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5890  20230315   105000    105459  ...         0.0        0.0       0
5891  20230315   105500    105959  ...         0.0        0.0       0
5892  20230315   110000    110459  ...         0.0        0.0       0
5893  20230315   110500    110959  ...         0.0        0.0       0
5894  20230315   111000    111459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 11:15:01,659:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678850099, self.tradeDate='20230315', self.openTime='111000', self.closeTime='111459',self.symbol='BTCUSDT',self.open=24850.9, self.close=24834.8, self.high=24856.2, self.low=24834.0, self.vol=704.017, self.amt=17490167.545, ukdf['pct'].iloc[-1]=-0.000652 , ukdf['amount'].iloc[-1]=17490167.545, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5894, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-499785.7504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24834.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110500', self.closeTime='110959', self.symbol='BTCUSDT', self.open=24839.3, self.close=24851.0, self.high=24869.7, self.low=24830.2 
127.0.0.1 - - [15/Mar/2023 11:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 11:10:01,655:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110500', self.closeTime='110959',self.symbol='BTCUSDT',self.open=24839.3, self.close=24851.0, self.high=24869.7, self.low=24830.2   
2023-03-15 11:10:01,691:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1569  20230315   104500    104959  1678848599  ...  24838.1 -0.000093   1569    3
1570  20230315   105000    105459  1678848899  ...  24835.7  0.001686   1570    4
1571  20230315   105500    105959  1678849199  ...  24838.0 -0.001941   1571    5
1572  20230315   110000    110459  1678849499  ...  24836.3 -0.000081   1572    0
1573  20230315   110500    110959  1678849799  ...  24830.2  0.000467   1573    1

[5 rows x 11 columns]
2023-03-15 11:10:01,691:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=109, self.factor=0.33400215515180537, self.count=31637 

self.closeSec=1678850099, self.tradeDate='20230315', self.openTime='111000', self.closeTime='111459', self.symbol='BTCUSDT', self.open=24850.9, self.close=24834.8, self.high=24856.2, self.low=24834.0 
127.0.0.1 - - [15/Mar/2023 11:15:01] "POST / HTTP/1.1" 200 -
2023-03-15 11:15:01,589:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678850099, self.tradeDate='20230315', self.openTime='111000', self.closeTime='111459',self.symbol='BTCUSDT',self.open=24850.9, self.close=24834.8, self.high=24856.2, self.low=24834.0   
2023-03-15 11:15:01,615:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1570  20230315   105000    105459  1678848899  ...  24835.7  0.001686   1570    4
1571  20230315   105500    105959  1678849199  ...  24838.0 -0.001941   1571    5
1572  20230315   110000    110459  1678849499  ...  24836.3 -0.000081   1572    0
1573  20230315   110500    110959  1678849799  ...  24830.2  0.000467   1573    1
1574  20230315   111000    111459  1678850099  ...  24834.0 -0.000652   1574    2

[5 rows x 11 columns]
2023-03-15 11:15:01,616:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-15 11:00:34,421:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5776  20230315    082959  24682.5  ...  54.583333  0.538003  0.508721
5777  20230315    085959  24403.5  ...  55.000000  0.559643  0.520687
5778  20230315    092959  24742.6  ...  55.416667  0.571847  0.526543
5779  20230315    095959  24944.9  ...  55.000000  0.569832  0.532673
5780  20230315    102959  24919.7  ...  55.000000  0.564894  0.540010

[5 rows x 33 columns]
0.5600739371534196
acc is : 0.5600739371534196
2023-03-15 11:00:34,576:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     1  0.389526  0.610474       1  ...  1.121937  -1.0  0.0000  1.107453
537     0  0.617686  0.382314       1  ...  1.129316   1.0 -0.0016  1.116508
538     0  0.580011  0.419989       0  ...  1.128170   1.0  0.0000  1.115375
539     0  0.511132  0.488868       0  ...  1.125386   1.0  0.0000  1.112622
540     1  0.489373  0.510627       0  ...  1.124630   1.0  0.0000  1.111875

[5 rows x 10 columns]
2023-03-15 11:00:34,610:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.389043  0.610957       1  ...  1.121937  -1.0  0.0000  1.106072
46     0  0.617973  0.382027       1  ...  1.129316   1.0 -0.0016  1.118430
47     0  0.579963  0.420037       0  ...  1.109754   1.0  0.0000  1.117306
48     0  0.511354  0.488646       0  ...  1.125386   1.0  0.0000  1.112304
49     1  0.489373  0.510627       0  ...  1.124630   1.0  0.0000  1.111875

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.773', 'enterprice': '24920.1', 'countrevence': '0', 'unrealprofit': '-2387.90287365756', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24842.50266228', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

640  20230315   104000    104959  1678848599  24850.2  24847.8 -0.000101
2023-03-15 10:50:01,792:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Mar/2023 11:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15817 

self.closeSec=1678849199, self.tradeDate='20230315', self.openTime='105000', self.closeTime='105959', self.symbol='BTCUSDT', self.open='24847.7', self.close='24841.4'
2023-03-15 11:00:01,957:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678849199, self.tradeDate='20230315', self.openTime='105000', self.closeTime='105959',self.symbol='BTCUSDT',self.open='24847.7', self.close='24841.4'
2023-03-15 11:00:01,993:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
637  20230315   101000    101959  1678846799  24946.4  24899.5 -0.001880
638  20230315   102000    102959  1678847399  24899.4  24858.1 -0.001663
639  20230315   103000    103959  1678847999  24858.1  24850.3 -0.000314
640  20230315   104000    104959  1678848599  24850.2  24847.8 -0.000101
641  20230315   105000    105959  1678849199  24847.7  24841.4 -0.000258
2023-03-15 11:00:01,993:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15818 

self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110000', self.closeTime='110959', self.symbol='BTCUSDT', self.open='24841.5', self.close='24851'
127.0.0.1 - - [15/Mar/2023 11:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 11:10:02,461:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110000', self.closeTime='110959',self.symbol='BTCUSDT',self.open='24841.5', self.close='24851'
2023-03-15 11:10:02,743:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
638  20230315   102000    102959  1678847399  24899.4  24858.1 -0.001663
639  20230315   103000    103959  1678847999  24858.1  24850.3 -0.000314
640  20230315   104000    104959  1678848599  24850.2  24847.8 -0.000101
641  20230315   105000    105959  1678849199  24847.7  24841.4 -0.000258
642  20230315   110000    110959  1678849799  24841.5    24851  0.000386
2023-03-15 11:10:02,743:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17488  20230315   104000    104959  1678848599  24850.2  24847.8
2023-03-15 10:50:01,807:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Mar/2023 11:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15818 

self.closeSec=1678849199, self.tradeDate='20230315', self.openTime='105000', self.closeTime='105959', self.symbol='BTCUSDT', self.open='24847.7', self.close='24841.4'
2023-03-15 11:00:01,963:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678849199, self.tradeDate='20230315', self.openTime='105000', self.closeTime='105959',self.symbol='BTCUSDT',self.open='24847.7', self.close='24841.4'
2023-03-15 11:00:01,999:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17485  20230315   101000    101959  1678846799  24946.4  24899.5
17486  20230315   102000    102959  1678847399  24899.4  24858.1
17487  20230315   103000    103959  1678847999  24858.1  24850.3
17488  20230315   104000    104959  1678848599  24850.2  24847.8
17489  20230315   105000    105959  1678849199  24847.7  24841.4
2023-03-15 11:00:02,000:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15819 

self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110000', self.closeTime='110959', self.symbol='BTCUSDT', self.open='24841.5', self.close='24851'
127.0.0.1 - - [15/Mar/2023 11:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 11:10:03,147:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110000', self.closeTime='110959',self.symbol='BTCUSDT',self.open='24841.5', self.close='24851'
2023-03-15 11:10:03,195:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17486  20230315   102000    102959  1678847399  24899.4  24858.1
17487  20230315   103000    103959  1678847999  24858.1  24850.3
17488  20230315   104000    104959  1678848599  24850.2  24847.8
17489  20230315   105000    105959  1678849199  24847.7  24841.4
17490  20230315   110000    110959  1678849799  24841.5    24851
2023-03-15 11:10:03,195:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12160  20230315   104000    104959  1678848599  24850.2  24847.8
2023-03-15 10:50:01,825:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15818 

self.closeSec=1678849199, self.tradeDate='20230315', self.openTime='105000', self.closeTime='105959', self.symbol='BTCUSDT', self.open='24847.7', self.close='24841.4'
2023-03-15 11:00:01,976:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678849199, self.tradeDate='20230315', self.openTime='105000', self.closeTime='105959',self.symbol='BTCUSDT',self.open='24847.7', self.close='24841.4'
127.0.0.1 - - [15/Mar/2023 11:00:01] "POST / HTTP/1.1" 200 -
2023-03-15 11:00:02,004:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12157  20230315   101000    101959  1678846799  24946.4  24899.5
12158  20230315   102000    102959  1678847399  24899.4  24858.1
12159  20230315   103000    103959  1678847999  24858.1  24850.3
12160  20230315   104000    104959  1678848599  24850.2  24847.8
12161  20230315   105000    105959  1678849199  24847.7  24841.4
2023-03-15 11:00:02,004:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15819 

self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110000', self.closeTime='110959', self.symbol='BTCUSDT', self.open='24841.5', self.close='24851'
127.0.0.1 - - [15/Mar/2023 11:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 11:10:03,023:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110000', self.closeTime='110959',self.symbol='BTCUSDT',self.open='24841.5', self.close='24851'
2023-03-15 11:10:03,118:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12158  20230315   102000    102959  1678847399  24899.4  24858.1
12159  20230315   103000    103959  1678847999  24858.1  24850.3
12160  20230315   104000    104959  1678848599  24850.2  24847.8
12161  20230315   105000    105959  1678849199  24847.7  24841.4
12162  20230315   110000    110959  1678849799  24841.5    24851
2023-03-15 11:10:03,118:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Mar/2023 11:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27068
self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110500', self.closeTime='110959', self.symbol='BTCUSDT', self.open=24839.3, self.close=24851.0, self.high=24869.7, self.low=24830.2, self.vol=466.266, self.amt=11587088.09 
2023-03-15 11:10:01,578:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5889  20230315   104500    104959  ...         0.0        0.0       0
5890  20230315   105000    105459  ...         0.0        0.0       0
5891  20230315   105500    105959  ...         0.0        0.0       0
5892  20230315   110000    110459  ...         0.0        0.0       0
5893  20230315   110500    110959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 11:10:01,580:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678849799, self.tradeDate='20230315', self.openTime='110500', self.closeTime='110959',self.symbol='BTCUSDT',self.open=24839.3, self.close=24851.0, self.high=24869.7, self.low=24830.2, self.vol=466.266, self.amt=11587088.09, ukdf['pct'].iloc[-1]=0.000467 , ukdf['amount'].iloc[-1]=11587088.09, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5893, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Mar/2023 11:15:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27069
self.closeSec=1678850099, self.tradeDate='20230315', self.openTime='111000', self.closeTime='111459', self.symbol='BTCUSDT', self.open=24850.9, self.close=24834.8, self.high=24856.2, self.low=24834.0, self.vol=704.017, self.amt=17490167.545 
2023-03-15 11:15:01,642:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5890  20230315   105000    105459  ...         0.0        0.0       0
5891  20230315   105500    105959  ...         0.0        0.0       0
5892  20230315   110000    110459  ...         0.0        0.0       0
5893  20230315   110500    110959  ...         0.0        0.0       0
5894  20230315   111000    111459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 11:15:01,643:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678850099, self.tradeDate='20230315', self.openTime='111000', self.closeTime='111459',self.symbol='BTCUSDT',self.open=24850.9, self.close=24834.8, self.high=24856.2, self.low=24834.0, self.vol=704.017, self.amt=17490167.545, ukdf['pct'].iloc[-1]=-0.000652 , ukdf['amount'].iloc[-1]=17490167.545, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5894, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230314   200000    235959  1678809599  ...    719  1.158051  2.045910     1.0
720  20230315   000000    035959  1678823999  ...    720  1.232075  2.223976     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '280469.08074529575', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25094.07668151', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=658
self.closeSec=1678838399, self.tradeDate='20230315', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25066.4, self.close=24682.5, self.high=25184.0, self.low=23951.0, self.vol=240076.01, self.amt=5904619850.52422 
127.0.0.1 - - [15/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-15 08:00:02,060:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678838399, self.tradeDate='20230315', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25066.4, self.close=24682.5, self.high=25184.0, self.low=23951.0, self.vol=240076.01, self.amt=5904619850.52422 
2023-03-15 08:00:02,091:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230314   120000    155959  ...  154883.625  3.782950e+09 -0.005250
718  20230314   160000    195959  ...  156510.376  3.834140e+09  0.020427
719  20230314   200000    235959  ...  572682.237  1.469777e+10  0.047035
720  20230315   000000    035959  ...  344588.234  8.672309e+09 -0.032854
721  20230315   040000    075959  ...  240076.010  5.904620e+09 -0.015064

[5 rows x 11 columns]
2023-03-15 08:00:04,664:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230314   120000    155959  1678780799  ...    717  1.056560  1.757535     1.0
718  20230314   160000    195959  1678795199  ...    718  1.049601  1.716673     1.0
719  20230314   200000    235959  1678809599  ...    719  1.158051  2.045910     1.0
720  20230315   000000    035959  1678823999  ...    720  1.232075  2.223976     1.0
721  20230315   040000    075959  1678838399  ...    721  1.246479  2.193121     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '257481.6475', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24682.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


