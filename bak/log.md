# 20230127 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [27/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17498
self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23024.5, self.close=23063.0, self.high=23065.9, self.low=23019.0, self.vol=1151.502, self.amt=26534849.0635 
2023-01-27 08:10:01,493:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230127   074500    074959  ...         0.0        0.0       0
5854  20230127   075000    075459  ...         0.0        0.0       0
5855  20230127   075500    075959  ...         0.0        0.0       0
5856  20230127   080000    080459  ...         0.0        0.0       0
5857  20230127   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 08:10:01,494:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23024.5, self.close=23063.0, self.high=23065.9, self.low=23019.0, self.vol=1151.502, self.amt=26534849.0635, ukdf['pct'].iloc[-1]=0.001672 , ukdf['amount'].iloc[-1]=26534849.0635, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-393177.16524589696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23063.08697896', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17499
self.closeSec=1674778499, self.tradeDate='20230127', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23062.9, self.close=23035.7, self.high=23068.7, self.low=23030.0, self.vol=701.468, self.amt=16170544.563 
2023-01-27 08:15:00,726:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230127   075000    075459  ...         0.0        0.0       0
5855  20230127   075500    075959  ...         0.0        0.0       0
5856  20230127   080000    080459  ...         0.0        0.0       0
5857  20230127   080500    080959  ...         0.0        0.0       0
5858  20230127   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 08:15:00,727:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674778499, self.tradeDate='20230127', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23062.9, self.close=23035.7, self.high=23068.7, self.low=23030.0, self.vol=701.468, self.amt=16170544.563, ukdf['pct'].iloc[-1]=-0.001184 , ukdf['amount'].iloc[-1]=16170544.563, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-391536.2283474496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23035.8180196', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23024.5, self.close=23063.0, self.high=23065.9, self.low=23019.0 
2023-01-27 08:10:01,440:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23024.5, self.close=23063.0, self.high=23065.9, self.low=23019.0   
127.0.0.1 - - [27/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-27 08:10:01,474:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230127   074500    074959  1674776999  ...  22988.0 -0.000852   1533    3
1534  20230127   075000    075459  1674777299  ...  22985.1  0.000796   1534    4
1535  20230127   075500    075959  1674777599  ...  22997.5 -0.000291   1535    5
1536  20230127   080000    080459  1674777899  ...  22997.5  0.000983   1536    0
1537  20230127   080500    080959  1674778199  ...  23019.0  0.001672   1537    1

[5 rows x 11 columns]
2023-01-27 08:10:01,475:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=301, self.factor=0.5354692303806202, self.count=18065 

self.closeSec=1674778499, self.tradeDate='20230127', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23062.9, self.close=23035.7, self.high=23068.7, self.low=23030.0 
2023-01-27 08:15:00,655:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674778499, self.tradeDate='20230127', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23062.9, self.close=23035.7, self.high=23068.7, self.low=23030.0   
2023-01-27 08:15:00,670:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230127   075000    075459  1674777299  ...  22985.1  0.000796   1534    4
1535  20230127   075500    075959  1674777599  ...  22997.5 -0.000291   1535    5
1536  20230127   080000    080459  1674777899  ...  22997.5  0.000983   1536    0
1537  20230127   080500    080959  1674778199  ...  23019.0  0.001672   1537    1
1538  20230127   081000    081459  1674778499  ...  23030.0 -0.001184   1538    2

[5 rows x 11 columns]
2023-01-27 08:15:00,670:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-27 08:00:19,058:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230127    052959  23105.9  ...  52.916667  0.515841  0.576867
5771  20230127    055959  23037.0  ...  52.916667  0.521490  0.568158
5772  20230127    062959  23073.5  ...  52.916667  0.516914  0.562853
5773  20230127    065959  23047.3  ...  52.916667  0.508300  0.566173
5774  20230127    072959  22997.9  ...  52.500000  0.507444  0.570093

[5 rows x 33 columns]
0.5138632162661737
acc is : 0.5138632162661737
2023-01-27 08:00:19,154:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.506391  0.493609       1  ...  0.976730   1.0    0.0  1.098597
537     0  0.527676  0.472324       0  ...  0.975625   1.0    0.0  1.097354
538     0  0.512917  0.487083       0  ...  0.973534   1.0    0.0  1.095002
539     0  0.501331  0.498669       0  ...  0.973327   1.0    0.0  1.094769
540     0  0.506922  0.493078       1  ...  0.973699   1.0    0.0  1.095188

[5 rows x 10 columns]
2023-01-27 08:00:19,177:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505828  0.494172       1  ...  0.976730   1.0    0.0  1.102676
46     0  0.527591  0.472409       0  ...  0.975625   1.0    0.0  1.101592
47     0  0.513571  0.486429       0  ...  0.973534   1.0    0.0  1.101189
48     0  0.501331  0.498669       0  ...  0.973327   1.0    0.0  1.094769
49     0  0.506922  0.493078       1  ...  0.973699   1.0    0.0  1.095188

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.682', 'enterprice': '23079.5', 'countrevence': '0', 'unrealprofit': '-2189.2262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23010.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230127   074000    074959  1674776999  22989.2  22990.3  0.000043
2023-01-27 07:50:00,576:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9031 

self.closeSec=1674777599, self.tradeDate='20230127', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22990.2', self.close='23001.9'
2023-01-27 08:00:01,892:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674777599, self.tradeDate='20230127', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22990.2', self.close='23001.9'
2023-01-27 08:00:01,964:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230127   071000    071959  1674775199    23000  22989.5 -0.000461
620  20230127   072000    072959  1674775799  22989.4  22993.1  0.000157
621  20230127   073000    073959  1674776399  22993.1  22989.3 -0.000165
622  20230127   074000    074959  1674776999  22989.2  22990.3  0.000043
623  20230127   075000    075959  1674777599  22990.2  23001.9  0.000505
2023-01-27 08:00:01,964:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9032 

self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23001.9', self.close='23063'
2023-01-27 08:10:01,519:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23001.9', self.close='23063'
2023-01-27 08:10:01,569:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230127   072000    072959  1674775799  22989.4  22993.1  0.000157
621  20230127   073000    073959  1674776399  22993.1  22989.3 -0.000165
622  20230127   074000    074959  1674776999  22989.2  22990.3  0.000043
623  20230127   075000    075959  1674777599  22990.2  23001.9  0.000505
624  20230127   080000    080959  1674778199  23001.9    23063  0.002656
2023-01-27 08:10:01,569:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230127   074000    074959  1674776999  22989.2  22990.3
2023-01-27 07:50:00,600:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9032 

self.closeSec=1674777599, self.tradeDate='20230127', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22990.2', self.close='23001.9'
127.0.0.1 - - [27/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-27 08:00:01,873:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674777599, self.tradeDate='20230127', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22990.2', self.close='23001.9'
2023-01-27 08:00:01,887:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230127   071000    071959  1674775199    23000  22989.5
17468  20230127   072000    072959  1674775799  22989.4  22993.1
17469  20230127   073000    073959  1674776399  22993.1  22989.3
17470  20230127   074000    074959  1674776999  22989.2  22990.3
17471  20230127   075000    075959  1674777599  22990.2  23001.9
2023-01-27 08:00:01,888:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9033 

self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23001.9', self.close='23063'
2023-01-27 08:10:01,564:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23001.9', self.close='23063'
2023-01-27 08:10:01,578:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230127   072000    072959  1674775799  22989.4  22993.1
17469  20230127   073000    073959  1674776399  22993.1  22989.3
17470  20230127   074000    074959  1674776999  22989.2  22990.3
17471  20230127   075000    075959  1674777599  22990.2  23001.9
17472  20230127   080000    080959  1674778199  23001.9    23063
2023-01-27 08:10:01,579:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230127   074000    074959  1674776999  22989.2  22990.3
2023-01-27 07:50:00,592:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9032 

self.closeSec=1674777599, self.tradeDate='20230127', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='22990.2', self.close='23001.9'
2023-01-27 08:00:01,920:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674777599, self.tradeDate='20230127', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='22990.2', self.close='23001.9'
2023-01-27 08:00:01,975:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230127   071000    071959  1674775199    23000  22989.5
12140  20230127   072000    072959  1674775799  22989.4  22993.1
12141  20230127   073000    073959  1674776399  22993.1  22989.3
12142  20230127   074000    074959  1674776999  22989.2  22990.3
12143  20230127   075000    075959  1674777599  22990.2  23001.9
2023-01-27 08:00:01,975:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9033 

self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23001.9', self.close='23063'
127.0.0.1 - - [27/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-27 08:10:01,546:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23001.9', self.close='23063'
2023-01-27 08:10:01,576:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230127   072000    072959  1674775799  22989.4  22993.1
12141  20230127   073000    073959  1674776399  22993.1  22989.3
12142  20230127   074000    074959  1674776999  22989.2  22990.3
12143  20230127   075000    075959  1674777599  22990.2  23001.9
12144  20230127   080000    080959  1674778199  23001.9    23063
2023-01-27 08:10:01,577:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13496
self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23024.5, self.close=23063.0, self.high=23065.9, self.low=23019.0, self.vol=1151.502, self.amt=26534849.0635 
127.0.0.1 - - [27/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-27 08:10:01,491:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230127   074500    074959  ...         0.0        0.0       0
5854  20230127   075000    075459  ...         0.0        0.0       0
5855  20230127   075500    075959  ...         0.0        0.0       0
5856  20230127   080000    080459  ...         0.0        0.0       0
5857  20230127   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 08:10:01,492:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674778199, self.tradeDate='20230127', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23024.5, self.close=23063.0, self.high=23065.9, self.low=23019.0, self.vol=1151.502, self.amt=26534849.0635, ukdf['pct'].iloc[-1]=0.001672 , ukdf['amount'].iloc[-1]=26534849.0635, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13497
self.closeSec=1674778499, self.tradeDate='20230127', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23062.9, self.close=23035.7, self.high=23068.7, self.low=23030.0, self.vol=701.468, self.amt=16170544.563 
127.0.0.1 - - [27/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-27 08:15:00,728:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230127   075000    075459  ...         0.0        0.0       0
5855  20230127   075500    075959  ...         0.0        0.0       0
5856  20230127   080000    080459  ...         0.0        0.0       0
5857  20230127   080500    080959  ...         0.0        0.0       0
5858  20230127   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 08:15:00,728:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674778499, self.tradeDate='20230127', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23062.9, self.close=23035.7, self.high=23068.7, self.low=23030.0, self.vol=701.468, self.amt=16170544.563, ukdf['pct'].iloc[-1]=-0.001184 , ukdf['amount'].iloc[-1]=16170544.563, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230126   200000    235959  1674748799  ...    719  0.205563 -1.183238    -1.0
720  20230127   000000    035959  1674763199  ...    720  0.201797 -1.164617    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-5567.2139726828', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23061.0847806', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=376
self.closeSec=1674777599, self.tradeDate='20230127', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23063.4, self.close=23001.9, self.high=23161.0, self.low=22955.0, self.vol=42267.061, self.amt=974371447.3721 
2023-01-27 08:00:01,741:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674777599, self.tradeDate='20230127', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23063.4, self.close=23001.9, self.high=23161.0, self.low=22955.0, self.vol=42267.061, self.amt=974371447.3721 
2023-01-27 08:00:01,766:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230126   120000    155959  ...   50565.793  1.165545e+09 -0.007268
718  20230126   160000    195959  ...   54116.524  1.242078e+09  0.001050
719  20230126   200000    235959  ...  155447.749  3.585153e+09 -0.001605
720  20230127   000000    035959  ...   64169.464  1.475425e+09  0.005007
721  20230127   040000    075959  ...   42267.061  9.743714e+08 -0.002667

[5 rows x 11 columns]
2023-01-27 08:00:03,009:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230126   120000    155959  1674719999  ...    717  0.185886 -1.284585    -1.0
718  20230126   160000    195959  1674734399  ...    718  0.176547 -1.274700    -1.0
719  20230126   200000    235959  1674748799  ...    719  0.205563 -1.183238    -1.0
720  20230127   000000    035959  1674763199  ...    720  0.201797 -1.164617    -1.0
721  20230127   040000    075959  1674777599  ...    721  0.194076 -1.155881    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-3164.64368628316', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23003.52164182', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


