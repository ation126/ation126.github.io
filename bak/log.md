# 20230118 09:47:17

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/Jan/2023 09:40:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14924
self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093500', self.closeTime='093959', self.symbol='BTCUSDT', self.open=21193.4, self.close=21216.8, self.high=21220.0, self.low=21193.3, self.vol=587.95, self.amt=12469891.0201 
2023-01-18 09:40:01,579:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5871  20230118   091500    091959  ...         0.0        0.0       0
5872  20230118   092000    092459  ...         0.0        0.0       0
5873  20230118   092500    092959  ...         0.0        0.0       0
5874  20230118   093000    093459  ...         0.0        0.0       0
5875  20230118   093500    093959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 09:40:01,580:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093500', self.closeTime='093959',self.symbol='BTCUSDT',self.open=21193.4, self.close=21216.8, self.high=21220.0, self.low=21193.3, self.vol=587.95, self.amt=12469891.0201, ukdf['pct'].iloc[-1]=0.001137 , ukdf['amount'].iloc[-1]=12469891.0201, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5875, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-282075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21216.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Jan/2023 09:45:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14925
self.closeSec=1674006299, self.tradeDate='20230118', self.openTime='094000', self.closeTime='094459', self.symbol='BTCUSDT', self.open=21216.9, self.close=21221.8, self.high=21229.3, self.low=21206.3, self.vol=445.983, self.amt=9463174.3669 
2023-01-18 09:45:00,804:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5872  20230118   092000    092459  ...         0.0        0.0       0
5873  20230118   092500    092959  ...         0.0        0.0       0
5874  20230118   093000    093459  ...         0.0        0.0       0
5875  20230118   093500    093959  ...         0.0        0.0       0
5876  20230118   094000    094459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 09:45:00,810:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674006299, self.tradeDate='20230118', self.openTime='094000', self.closeTime='094459',self.symbol='BTCUSDT',self.open=21216.9, self.close=21221.8, self.high=21229.3, self.low=21206.3, self.vol=445.983, self.amt=9463174.3669, ukdf['pct'].iloc[-1]=0.000236 , ukdf['amount'].iloc[-1]=9463174.3669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5876, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-282400.06464473776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21222.20189851', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=498, self.factor=0.48632840144236883, self.count=15490 

self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093500', self.closeTime='093959', self.symbol='BTCUSDT', self.open=21193.4, self.close=21216.8, self.high=21220.0, self.low=21193.3 
2023-01-18 09:40:01,441:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093500', self.closeTime='093959',self.symbol='BTCUSDT',self.open=21193.4, self.close=21216.8, self.high=21220.0, self.low=21193.3   
2023-01-18 09:40:01,480:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1551  20230118   091500    091959  1674004799  ...  21207.5 -0.001850   1551    3
1552  20230118   092000    092459  1674005099  ...  21195.3 -0.000415   1552    4
1553  20230118   092500    092959  1674005399  ...  21175.0 -0.000703   1553    5
1554  20230118   093000    093459  1674005699  ...  21180.4  0.000415   1554    0
1555  20230118   093500    093959  1674005999  ...  21193.3  0.001137   1555    1

[5 rows x 11 columns]
2023-01-18 09:40:01,480:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 09:45:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=498, self.factor=0.48632840144236883, self.count=15491 

self.closeSec=1674006299, self.tradeDate='20230118', self.openTime='094000', self.closeTime='094459', self.symbol='BTCUSDT', self.open=21216.9, self.close=21221.8, self.high=21229.3, self.low=21206.3 
2023-01-18 09:45:00,636:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674006299, self.tradeDate='20230118', self.openTime='094000', self.closeTime='094459',self.symbol='BTCUSDT',self.open=21216.9, self.close=21221.8, self.high=21229.3, self.low=21206.3   
2023-01-18 09:45:00,743:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1552  20230118   092000    092459  1674005099  ...  21195.3 -0.000415   1552    4
1553  20230118   092500    092959  1674005399  ...  21175.0 -0.000703   1553    5
1554  20230118   093000    093459  1674005699  ...  21180.4  0.000415   1554    0
1555  20230118   093500    093959  1674005999  ...  21193.3  0.001137   1555    1
1556  20230118   094000    094459  1674006299  ...  21206.3  0.000236   1556    2

[5 rows x 11 columns]
2023-01-18 09:45:00,743:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-18 09:30:47,273:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5773  20230118    065959  21303.5  ...  51.250000  0.535412  0.456552
5774  20230118    072959  21229.9  ...  51.250000  0.531840  0.472101
5775  20230118    075959  21215.2  ...  51.250000  0.511082  0.496044
5776  20230118    082959  21130.8  ...  51.250000  0.517785  0.515099
5777  20230118    085959  21158.6  ...  51.666667  0.527014  0.528293

[5 rows x 33 columns]
0.5231053604436229
acc is : 0.5231053604436229
2023-01-18 09:30:47,506:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.477572  0.522428       0  ...  1.053753   1.0    0.0  1.259704
537     1  0.484829  0.515171       0  ...  1.049427   1.0    0.0  1.254532
538     1  0.466234  0.533766       1  ...  1.050937   1.0    0.0  1.256337
539     1  0.493994  0.506006       1  ...  1.053043   1.0    0.0  1.258855
540     0  0.502548  0.497452       0  ...  1.052193   1.0    0.0  1.257839

[5 rows x 10 columns]
2023-01-18 09:30:47,548:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.477613  0.522387       0  ...  1.053753   1.0    0.0  1.261419
46     1  0.484916  0.515084       0  ...  1.049427   1.0    0.0  1.256240
47     1  0.466215  0.533785       1  ...  1.050937   1.0    0.0  1.258324
48     1  0.494037  0.505963       1  ...  1.053043   1.0    0.0  1.258840
49     0  0.502548  0.497452       0  ...  1.052193   1.0    0.0  1.257839

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

631  20230118   091000    091959  1674004799  21250.3  21207.6 -0.002005
2023-01-18 09:20:00,626:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 09:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7744 

self.closeSec=1674005399, self.tradeDate='20230118', self.openTime='092000', self.closeTime='092959', self.symbol='BTCUSDT', self.open='21207.5', self.close='21183.9'
2023-01-18 09:30:01,532:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674005399, self.tradeDate='20230118', self.openTime='092000', self.closeTime='092959',self.symbol='BTCUSDT',self.open='21207.5', self.close='21183.9'
2023-01-18 09:30:01,573:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
628  20230118   084000    084959  1674002999  21220.3  21216.9 -0.000160
629  20230118   085000    085959  1674003599  21217.3    21201 -0.000749
630  20230118   090000    090959  1674004199  21201.1  21250.2  0.002321
631  20230118   091000    091959  1674004799  21250.3  21207.6 -0.002005
632  20230118   092000    092959  1674005399  21207.5  21183.9 -0.001118
2023-01-18 09:30:01,584:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7745 

self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093000', self.closeTime='093959', self.symbol='BTCUSDT', self.open='21184', self.close='21216.8'
127.0.0.1 - - [18/Jan/2023 09:40:01] "POST / HTTP/1.1" 200 -
2023-01-18 09:40:01,562:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093000', self.closeTime='093959',self.symbol='BTCUSDT',self.open='21184', self.close='21216.8'
2023-01-18 09:40:01,595:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
629  20230118   085000    085959  1674003599  21217.3    21201 -0.000749
630  20230118   090000    090959  1674004199  21201.1  21250.2  0.002321
631  20230118   091000    091959  1674004799  21250.3  21207.6 -0.002005
632  20230118   092000    092959  1674005399  21207.5  21183.9 -0.001118
633  20230118   093000    093959  1674005999    21184  21216.8  0.001553
2023-01-18 09:40:01,595:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17479  20230118   091000    091959  1674004799  21250.3  21207.6
2023-01-18 09:20:00,645:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 09:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7745 

self.closeSec=1674005399, self.tradeDate='20230118', self.openTime='092000', self.closeTime='092959', self.symbol='BTCUSDT', self.open='21207.5', self.close='21183.9'
2023-01-18 09:30:01,557:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674005399, self.tradeDate='20230118', self.openTime='092000', self.closeTime='092959',self.symbol='BTCUSDT',self.open='21207.5', self.close='21183.9'
2023-01-18 09:30:01,569:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17476  20230118   084000    084959  1674002999  21220.3  21216.9
17477  20230118   085000    085959  1674003599  21217.3    21201
17478  20230118   090000    090959  1674004199  21201.1  21250.2
17479  20230118   091000    091959  1674004799  21250.3  21207.6
17480  20230118   092000    092959  1674005399  21207.5  21183.9
2023-01-18 09:30:01,569:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7746 

self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093000', self.closeTime='093959', self.symbol='BTCUSDT', self.open='21184', self.close='21216.8'
2023-01-18 09:40:01,544:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093000', self.closeTime='093959',self.symbol='BTCUSDT',self.open='21184', self.close='21216.8'
127.0.0.1 - - [18/Jan/2023 09:40:01] "POST / HTTP/1.1" 200 -
2023-01-18 09:40:01,591:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17477  20230118   085000    085959  1674003599  21217.3    21201
17478  20230118   090000    090959  1674004199  21201.1  21250.2
17479  20230118   091000    091959  1674004799  21250.3  21207.6
17480  20230118   092000    092959  1674005399  21207.5  21183.9
17481  20230118   093000    093959  1674005999    21184  21216.8
2023-01-18 09:40:01,591:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12151  20230118   091000    091959  1674004799  21250.3  21207.6
2023-01-18 09:20:00,623:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Jan/2023 09:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7745 

self.closeSec=1674005399, self.tradeDate='20230118', self.openTime='092000', self.closeTime='092959', self.symbol='BTCUSDT', self.open='21207.5', self.close='21183.9'
2023-01-18 09:30:01,529:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674005399, self.tradeDate='20230118', self.openTime='092000', self.closeTime='092959',self.symbol='BTCUSDT',self.open='21207.5', self.close='21183.9'
2023-01-18 09:30:01,564:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12148  20230118   084000    084959  1674002999  21220.3  21216.9
12149  20230118   085000    085959  1674003599  21217.3    21201
12150  20230118   090000    090959  1674004199  21201.1  21250.2
12151  20230118   091000    091959  1674004799  21250.3  21207.6
12152  20230118   092000    092959  1674005399  21207.5  21183.9
2023-01-18 09:30:01,565:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7746 

self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093000', self.closeTime='093959', self.symbol='BTCUSDT', self.open='21184', self.close='21216.8'
2023-01-18 09:40:01,552:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093000', self.closeTime='093959',self.symbol='BTCUSDT',self.open='21184', self.close='21216.8'
127.0.0.1 - - [18/Jan/2023 09:40:01] "POST / HTTP/1.1" 200 -
2023-01-18 09:40:01,584:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12149  20230118   085000    085959  1674003599  21217.3    21201
12150  20230118   090000    090959  1674004199  21201.1  21250.2
12151  20230118   091000    091959  1674004799  21250.3  21207.6
12152  20230118   092000    092959  1674005399  21207.5  21183.9
12153  20230118   093000    093959  1674005999    21184  21216.8
2023-01-18 09:40:01,586:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10922
self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093500', self.closeTime='093959', self.symbol='BTCUSDT', self.open=21193.4, self.close=21216.8, self.high=21220.0, self.low=21193.3, self.vol=587.95, self.amt=12469891.0201 
127.0.0.1 - - [18/Jan/2023 09:40:01] "POST / HTTP/1.1" 200 -
2023-01-18 09:40:01,502:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5871  20230118   091500    091959  ...         0.0        0.0       0
5872  20230118   092000    092459  ...         0.0        0.0       0
5873  20230118   092500    092959  ...         0.0        0.0       0
5874  20230118   093000    093459  ...         0.0        0.0       0
5875  20230118   093500    093959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 09:40:01,502:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674005999, self.tradeDate='20230118', self.openTime='093500', self.closeTime='093959',self.symbol='BTCUSDT',self.open=21193.4, self.close=21216.8, self.high=21220.0, self.low=21193.3, self.vol=587.95, self.amt=12469891.0201, ukdf['pct'].iloc[-1]=0.001137 , ukdf['amount'].iloc[-1]=12469891.0201, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5875, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10923
self.closeSec=1674006299, self.tradeDate='20230118', self.openTime='094000', self.closeTime='094459', self.symbol='BTCUSDT', self.open=21216.9, self.close=21221.8, self.high=21229.3, self.low=21206.3, self.vol=445.983, self.amt=9463174.3669 
127.0.0.1 - - [18/Jan/2023 09:45:00] "POST / HTTP/1.1" 200 -
2023-01-18 09:45:00,813:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5872  20230118   092000    092459  ...         0.0        0.0       0
5873  20230118   092500    092959  ...         0.0        0.0       0
5874  20230118   093000    093459  ...         0.0        0.0       0
5875  20230118   093500    093959  ...         0.0        0.0       0
5876  20230118   094000    094459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 09:45:00,817:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674006299, self.tradeDate='20230118', self.openTime='094000', self.closeTime='094459',self.symbol='BTCUSDT',self.open=21216.9, self.close=21221.8, self.high=21229.3, self.low=21206.3, self.vol=445.983, self.amt=9463174.3669, ukdf['pct'].iloc[-1]=0.000236 , ukdf['amount'].iloc[-1]=9463174.3669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5876, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230117   200000    235959  1673971199  ...    719  0.515810 -0.841899    -1.0
720  20230118   000000    035959  1673985599  ...    720  0.363703 -1.263897    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-8699.4312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21337.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=322
self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=21337.3, self.close=21128.2, self.high=21410.8, self.low=21123.1, self.vol=56117.691, self.amt=1193677679.6111 
127.0.0.1 - - [18/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-18 08:00:01,236:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=21337.3, self.close=21128.2, self.high=21410.8, self.low=21123.1, self.vol=56117.691, self.amt=1193677679.6111 
2023-01-18 08:00:01,269:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230117   120000    155959  ...   40393.627  8.539123e+08  0.000241
718  20230117   160000    195959  ...   49711.091  1.052226e+09  0.003970
719  20230117   200000    235959  ...  233118.482  4.958880e+09 -0.002022
720  20230118   000000    035959  ...   86362.443  1.834486e+09  0.007627
721  20230118   040000    075959  ...   56117.691  1.193678e+09 -0.009795

[5 rows x 11 columns]
2023-01-18 08:00:03,344:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230117   120000    155959  1673942399  ...    717  0.774235 -0.117167     NaN
718  20230117   160000    195959  1673956799  ...    718  0.635010 -0.505098     NaN
719  20230117   200000    235959  1673971199  ...    719  0.515810 -0.841899    -1.0
720  20230118   000000    035959  1673985599  ...    720  0.363703 -1.263897    -1.0
721  20230118   040000    075959  1673999999  ...    721  0.123877 -1.893662    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '1837.908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21130.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


