# 20230131 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [31/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18650
self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22810.1, self.close=22820.1, self.high=22842.3, self.low=22806.0, self.vol=1326.583, self.amt=30277163.0492 
2023-01-31 08:10:01,709:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230131   074500    074959  ...         0.0        0.0       0
5854  20230131   075000    075459  ...         0.0        0.0       0
5855  20230131   075500    075959  ...         0.0        0.0       0
5856  20230131   080000    080459  ...         0.0        0.0       0
5857  20230131   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 08:10:01,710:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22810.1, self.close=22820.1, self.high=22842.3, self.low=22806.0, self.vol=1326.583, self.amt=30277163.0492, ukdf['pct'].iloc[-1]=0.000438 , ukdf['amount'].iloc[-1]=30277163.0492, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-378518.17136731168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22819.48498018', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18651
self.closeSec=1675124099, self.tradeDate='20230131', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22818.2, self.close=22777.4, self.high=22852.0, self.low=22766.5, self.vol=2977.125, self.amt=67876668.1654 
127.0.0.1 - - [31/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-31 08:15:00,744:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230131   075000    075459  ...         0.0        0.0       0
5855  20230131   075500    075959  ...         0.0        0.0       0
5856  20230131   080000    080459  ...         0.0        0.0       0
5857  20230131   080500    080959  ...         0.0        0.0       0
5858  20230131   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 08:15:00,744:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675124099, self.tradeDate='20230131', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22818.2, self.close=22777.4, self.high=22852.0, self.low=22766.5, self.vol=2977.125, self.amt=67876668.1654, ukdf['pct'].iloc[-1]=-0.001871 , ukdf['amount'].iloc[-1]=67876668.1654, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-375979.648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22777.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6300966364482816, self.count=19216 

self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22810.1, self.close=22820.1, self.high=22842.3, self.low=22806.0 
2023-01-31 08:10:01,658:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22810.1, self.close=22820.1, self.high=22842.3, self.low=22806.0   
2023-01-31 08:10:01,707:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230131   074500    074959  1675122599  ...  22761.0 -0.000092   1533    3
1534  20230131   075000    075459  1675122899  ...  22781.5  0.001773   1534    4
1535  20230131   075500    075959  1675123199  ...  22813.4 -0.000333   1535    5
1536  20230131   080000    080459  1675123499  ...  22800.2 -0.000429   1536    0
1537  20230131   080500    080959  1675123799  ...  22806.0  0.000438   1537    1

[5 rows x 11 columns]
2023-01-31 08:10:01,708:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [31/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6300966364482816, self.count=19217 

self.closeSec=1675124099, self.tradeDate='20230131', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22818.2, self.close=22777.4, self.high=22852.0, self.low=22766.5 
2023-01-31 08:15:00,686:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675124099, self.tradeDate='20230131', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22818.2, self.close=22777.4, self.high=22852.0, self.low=22766.5   
2023-01-31 08:15:00,724:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230131   075000    075459  1675122899  ...  22781.5  0.001773   1534    4
1535  20230131   075500    075959  1675123199  ...  22813.4 -0.000333   1535    5
1536  20230131   080000    080459  1675123499  ...  22800.2 -0.000429   1536    0
1537  20230131   080500    080959  1675123799  ...  22806.0  0.000438   1537    1
1538  20230131   081000    081459  1675124099  ...  22766.5 -0.001871   1538    2

[5 rows x 11 columns]
2023-01-31 08:15:00,724:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-31 08:00:18,143:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230131    052959  22694.0  ...  51.250000  0.402764  0.738266
5771  20230131    055959  22760.8  ...  50.833333  0.400182  0.745110
5772  20230131    062959  22743.7  ...  50.833333  0.393259  0.754034
5773  20230131    065959  22697.2  ...  51.250000  0.400528  0.757704
5774  20230131    072959  22729.0  ...  51.250000  0.412033  0.758484

[5 rows x 33 columns]
0.5249537892791127
acc is : 0.5249537892791127
2023-01-31 08:00:18,240:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.485834  0.514166       0  ...  1.030200  -1.0    0.0  1.088211
537     1  0.498253  0.501747       0  ...  1.032297  -1.0    0.0  1.085995
538     1  0.489995  0.510005       1  ...  1.030851  -1.0    0.0  1.087517
539     0  0.515884  0.484116       1  ...  1.028543  -1.0    0.0  1.089952
540     0  0.524257  0.475743       1  ...  1.026741  -1.0    0.0  1.091861

[5 rows x 10 columns]
2023-01-31 08:00:18,264:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486674  0.513326       0  ...  1.030200  -1.0    0.0  1.089738
46     1  0.498324  0.501676       0  ...  1.032297  -1.0    0.0  1.086354
47     1  0.490633  0.509367       1  ...  1.030851  -1.0    0.0  1.088897
48     0  0.515884  0.484116       1  ...  1.028543  -1.0    0.0  1.089952
49     0  0.524257  0.475743       1  ...  1.026741  -1.0    0.0  1.091861

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.741', 'enterprice': '23173.4', 'countrevence': '0', 'unrealprofit': '10885.76927948511', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22819.28760029', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230131   074000    074959  1675122599    22791  22787.1 -0.000167
2023-01-31 07:50:00,788:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9607 

self.closeSec=1675123199, self.tradeDate='20230131', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22787.1', self.close='22819.9'
127.0.0.1 - - [31/Jan/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-01-31 08:00:02,374:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675123199, self.tradeDate='20230131', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22787.1', self.close='22819.9'
2023-01-31 08:00:02,388:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230131   071000    071959  1675120799  22727.9  22775.4  0.002090
620  20230131   072000    072959  1675121399  22775.3    22780  0.000202
621  20230131   073000    073959  1675121999  22787.5  22790.9  0.000478
622  20230131   074000    074959  1675122599    22791  22787.1 -0.000167
623  20230131   075000    075959  1675123199  22787.1  22819.9  0.001439
2023-01-31 08:00:02,388:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9608 

self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22819.9', self.close='22818.1'
2023-01-31 08:10:01,749:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22819.9', self.close='22818.1'
2023-01-31 08:10:01,779:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230131   072000    072959  1675121399  22775.3    22780  0.000202
621  20230131   073000    073959  1675121999  22787.5  22790.9  0.000478
622  20230131   074000    074959  1675122599    22791  22787.1 -0.000167
623  20230131   075000    075959  1675123199  22787.1  22819.9  0.001439
624  20230131   080000    080959  1675123799  22819.9  22818.1 -0.000079
2023-01-31 08:10:01,779:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230131   074000    074959  1675122599    22791  22787.1
2023-01-31 07:50:00,822:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Jan/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9608 

self.closeSec=1675123199, self.tradeDate='20230131', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22787.1', self.close='22819.9'
2023-01-31 08:00:02,382:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675123199, self.tradeDate='20230131', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22787.1', self.close='22819.9'
2023-01-31 08:00:02,433:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230131   071000    071959  1675120799  22727.9  22775.4
17468  20230131   072000    072959  1675121399  22775.3    22780
17469  20230131   073000    073959  1675121999  22787.5  22790.9
17470  20230131   074000    074959  1675122599    22791  22787.1
17471  20230131   075000    075959  1675123199  22787.1  22819.9
2023-01-31 08:00:02,433:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9609 

self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22819.9', self.close='22818.1'
2023-01-31 08:10:01,771:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22819.9', self.close='22818.1'
2023-01-31 08:10:01,777:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230131   072000    072959  1675121399  22775.3    22780
17469  20230131   073000    073959  1675121999  22787.5  22790.9
17470  20230131   074000    074959  1675122599    22791  22787.1
17471  20230131   075000    075959  1675123199  22787.1  22819.9
17472  20230131   080000    080959  1675123799  22819.9  22818.1
2023-01-31 08:10:01,777:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230131   074000    074959  1675122599    22791  22787.1
2023-01-31 07:50:00,810:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9608 

self.closeSec=1675123199, self.tradeDate='20230131', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22787.1', self.close='22819.9'
127.0.0.1 - - [31/Jan/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-01-31 08:00:02,367:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675123199, self.tradeDate='20230131', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22787.1', self.close='22819.9'
2023-01-31 08:00:02,423:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230131   071000    071959  1675120799  22727.9  22775.4
12140  20230131   072000    072959  1675121399  22775.3    22780
12141  20230131   073000    073959  1675121999  22787.5  22790.9
12142  20230131   074000    074959  1675122599    22791  22787.1
12143  20230131   075000    075959  1675123199  22787.1  22819.9
2023-01-31 08:00:02,423:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [31/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9609 

self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22819.9', self.close='22818.1'
2023-01-31 08:10:01,766:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22819.9', self.close='22818.1'
2023-01-31 08:10:01,782:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230131   072000    072959  1675121399  22775.3    22780
12141  20230131   073000    073959  1675121999  22787.5  22790.9
12142  20230131   074000    074959  1675122599    22791  22787.1
12143  20230131   075000    075959  1675123199  22787.1  22819.9
12144  20230131   080000    080959  1675123799  22819.9  22818.1
2023-01-31 08:10:01,783:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14648
self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=22810.1, self.close=22820.1, self.high=22842.3, self.low=22806.0, self.vol=1326.583, self.amt=30277163.0492 
127.0.0.1 - - [31/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-31 08:10:01,735:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230131   074500    074959  ...         0.0        0.0       0
5854  20230131   075000    075459  ...         0.0        0.0       0
5855  20230131   075500    075959  ...         0.0        0.0       0
5856  20230131   080000    080459  ...         0.0        0.0       0
5857  20230131   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 08:10:01,735:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675123799, self.tradeDate='20230131', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=22810.1, self.close=22820.1, self.high=22842.3, self.low=22806.0, self.vol=1326.583, self.amt=30277163.0492, ukdf['pct'].iloc[-1]=0.000438 , ukdf['amount'].iloc[-1]=30277163.0492, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14649
self.closeSec=1675124099, self.tradeDate='20230131', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=22818.2, self.close=22777.4, self.high=22852.0, self.low=22766.5, self.vol=2977.125, self.amt=67876668.1654 
127.0.0.1 - - [31/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-31 08:15:00,753:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230131   075000    075459  ...         0.0        0.0       0
5855  20230131   075500    075959  ...         0.0        0.0       0
5856  20230131   080000    080459  ...         0.0        0.0       0
5857  20230131   080500    080959  ...         0.0        0.0       0
5858  20230131   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 08:15:00,753:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675124099, self.tradeDate='20230131', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=22818.2, self.close=22777.4, self.high=22852.0, self.low=22766.5, self.vol=2977.125, self.amt=67876668.1654, ukdf['pct'].iloc[-1]=-0.001871 , ukdf['amount'].iloc[-1]=67876668.1654, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230130   200000    235959  1675094399  ...    719  0.618886  0.372043     NaN
720  20230131   000000    035959  1675108799  ...    720  0.513624  0.094729     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-35826.736303611', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22780.61698225', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [31/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=400
self.closeSec=1675123199, self.tradeDate='20230131', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22783.6, self.close=22819.9, self.high=22837.0, self.low=22484.2, self.vol=82595.41, self.amt=1875681496.8579 
2023-01-31 08:00:02,001:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675123199, self.tradeDate='20230131', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22783.6, self.close=22819.9, self.high=22837.0, self.low=22484.2, self.vol=82595.41, self.amt=1875681496.8579 
2023-01-31 08:00:02,047:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230130   120000    155959  ...   35817.696  8.486056e+08 -0.002224
718  20230130   160000    195959  ...  178463.464  4.155246e+09 -0.024226
719  20230130   200000    235959  ...  114367.727  2.644439e+09  0.004481
720  20230131   000000    035959  ...  110669.265  2.538005e+09 -0.017037
721  20230131   040000    075959  ...   82595.410  1.875681e+09  0.001589

[5 rows x 11 columns]
2023-01-31 08:00:03,512:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230130   120000    155959  1675065599  ...    717  0.699296  0.560167     NaN
718  20230130   160000    195959  1675079999  ...    718  0.645062  0.429012     NaN
719  20230130   200000    235959  1675094399  ...    719  0.618886  0.372043     NaN
720  20230131   000000    035959  1675108799  ...    720  0.513624  0.094729     NaN
721  20230131   040000    075959  1675123199  ...    721  0.537706  0.174729     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-34183.4205230508', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22822.7922153', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


