# 20230103 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [03/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10586
self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16659.9, self.close=16675.1, self.high=16677.5, self.low=16659.1, self.vol=1052.168, self.amt=17538165.5228 
2023-01-03 08:10:01,494:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230103   074500    074959  ...         0.0        0.0       0
5854  20230103   075000    075459  ...         0.0        0.0       0
5855  20230103   075500    075959  ...         0.0        0.0       0
5856  20230103   080000    080459  ...         0.0        0.0       0
5857  20230103   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 08:10:01,495:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16659.9, self.close=16675.1, self.high=16677.5, self.low=16659.1, self.vol=1052.168, self.amt=17538165.5228, ukdf['pct'].iloc[-1]=0.000912 , ukdf['amount'].iloc[-1]=17538165.5228, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-8767.6432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16675', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10587
self.closeSec=1672704899, self.tradeDate='20230103', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16675.0, self.close=16682.5, self.high=16682.5, self.low=16670.7, self.vol=733.383, self.amt=12230050.474 
127.0.0.1 - - [03/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-03 08:15:00,628:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230103   075000    075459  ...         0.0        0.0       0
5855  20230103   075500    075959  ...         0.0        0.0       0
5856  20230103   080000    080459  ...         0.0        0.0       0
5857  20230103   080500    080959  ...         0.0        0.0       0
5858  20230103   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 08:15:00,628:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672704899, self.tradeDate='20230103', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16675.0, self.close=16682.5, self.high=16682.5, self.low=16670.7, self.vol=733.383, self.amt=12230050.474, ukdf['pct'].iloc[-1]=0.000444 , ukdf['amount'].iloc[-1]=12230050.474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-9212.9456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16682.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.2896600445238997, self.count=11152 

self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16659.9, self.close=16675.1, self.high=16677.5, self.low=16659.1 
2023-01-03 08:10:01,439:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16659.9, self.close=16675.1, self.high=16677.5, self.low=16659.1   
2023-01-03 08:10:01,486:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230103   074500    074959  1672703399  ...  16680.0 -0.000892   1533    3
1534  20230103   075000    075459  1672703699  ...  16666.1 -0.000444   1534    4
1535  20230103   075500    075959  1672703999  ...  16650.0 -0.000402   1535    5
1536  20230103   080000    080459  1672704299  ...  16639.5 -0.000366   1536    0
1537  20230103   080500    080959  1672704599  ...  16659.1  0.000912   1537    1

[5 rows x 11 columns]
2023-01-03 08:10:01,486:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.2896600445238997, self.count=11153 

self.closeSec=1672704899, self.tradeDate='20230103', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16675.0, self.close=16682.5, self.high=16682.5, self.low=16670.7 
2023-01-03 08:15:00,563:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672704899, self.tradeDate='20230103', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16675.0, self.close=16682.5, self.high=16682.5, self.low=16670.7   
127.0.0.1 - - [03/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-03 08:15:00,604:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230103   075000    075459  1672703699  ...  16666.1 -0.000444   1534    4
1535  20230103   075500    075959  1672703999  ...  16650.0 -0.000402   1535    5
1536  20230103   080000    080459  1672704299  ...  16639.5 -0.000366   1536    0
1537  20230103   080500    080959  1672704599  ...  16659.1  0.000912   1537    1
1538  20230103   081000    081459  1672704899  ...  16670.7  0.000444   1538    2

[5 rows x 11 columns]
2023-01-03 08:15:00,605:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-03 08:00:19,242:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230103    052959  16722.7  ...  49.166667  0.572424  0.239315
5771  20230103    055959  16720.8  ...  49.583333  0.594064  0.235846
5772  20230103    062959  16751.9  ...  49.583333  0.562405  0.243449
5773  20230103    065959  16718.0  ...  49.166667  0.542141  0.258261
5774  20230103    072959  16694.6  ...  49.166667  0.549464  0.269132

[5 rows x 33 columns]
0.5157116451016636
acc is : 0.5157116451016636
2023-01-03 08:00:19,340:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     1  0.497188  0.502812       1  ...  NaN   NaN -0.0016  1.008094
537     0  0.508534  0.491466       0  ...  NaN   NaN -0.0016  1.006054
538     1  0.488051  0.511949       0  ...  NaN   NaN -0.0016  1.004652
539     1  0.487987  0.512013       1  ...  NaN   NaN -0.0016  1.005272
540     1  0.495973  0.504027       0  ...  NaN   NaN -0.0016  1.002925

[5 rows x 10 columns]
2023-01-03 08:00:19,352:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
22     1  0.497414  0.502586       1  ...  NaN   NaN -0.0016  1.007239
23     0  0.508521  0.491479       0  ...  NaN   NaN -0.0016  1.004506
24     1  0.487818  0.512182       0  ...  NaN   NaN -0.0016  1.002330
25     1  0.487890  0.512110       1  ...  NaN   NaN -0.0016  1.005272
26     1  0.495973  0.504027       0  ...  NaN   NaN -0.0016  1.002925

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-1610.82486170496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16663.62319268', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230103   074000    074959  1672703399  16690.5  16680.2 -0.000617
2023-01-03 07:50:00,815:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5575 

self.closeSec=1672703999, self.tradeDate='20230103', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16680.2', self.close='16666'
2023-01-03 08:00:00,892:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672703999, self.tradeDate='20230103', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16680.2', self.close='16666'
127.0.0.1 - - [03/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-03 08:00:00,943:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230103   071000    071959  1672701599  16706.5  16706.5  0.000096
620  20230103   072000    072959  1672702199  16706.6    16705 -0.000090
621  20230103   073000    073959  1672702799    16705  16690.5 -0.000868
622  20230103   074000    074959  1672703399  16690.5  16680.2 -0.000617
623  20230103   075000    075959  1672703999  16680.2    16666 -0.000851
2023-01-03 08:00:00,944:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5576 

self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16665.9', self.close='16675.1'
2023-01-03 08:10:01,521:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16665.9', self.close='16675.1'
127.0.0.1 - - [03/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-03 08:10:01,552:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230103   072000    072959  1672702199  16706.6    16705 -0.000090
621  20230103   073000    073959  1672702799    16705  16690.5 -0.000868
622  20230103   074000    074959  1672703399  16690.5  16680.2 -0.000617
623  20230103   075000    075959  1672703999  16680.2    16666 -0.000851
624  20230103   080000    080959  1672704599  16665.9  16675.1  0.000546
2023-01-03 08:10:01,552:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230103   074000    074959  1672703399  16690.5  16680.2
2023-01-03 07:50:00,824:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5576 

self.closeSec=1672703999, self.tradeDate='20230103', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16680.2', self.close='16666'
2023-01-03 08:00:00,876:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672703999, self.tradeDate='20230103', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16680.2', self.close='16666'
2023-01-03 08:00:00,948:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230103   071000    071959  1672701599  16706.5  16706.5
17468  20230103   072000    072959  1672702199  16706.6    16705
17469  20230103   073000    073959  1672702799    16705  16690.5
17470  20230103   074000    074959  1672703399  16690.5  16680.2
17471  20230103   075000    075959  1672703999  16680.2    16666
2023-01-03 08:00:00,948:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5577 

self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16665.9', self.close='16675.1'
127.0.0.1 - - [03/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-03 08:10:01,537:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16665.9', self.close='16675.1'
2023-01-03 08:10:01,566:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230103   072000    072959  1672702199  16706.6    16705
17469  20230103   073000    073959  1672702799    16705  16690.5
17470  20230103   074000    074959  1672703399  16690.5  16680.2
17471  20230103   075000    075959  1672703999  16680.2    16666
17472  20230103   080000    080959  1672704599  16665.9  16675.1
2023-01-03 08:10:01,567:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230103   074000    074959  1672703399  16690.5  16680.2
2023-01-03 07:50:00,823:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5576 

self.closeSec=1672703999, self.tradeDate='20230103', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16680.2', self.close='16666'
2023-01-03 08:00:00,873:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672703999, self.tradeDate='20230103', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16680.2', self.close='16666'
127.0.0.1 - - [03/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-03 08:00:00,963:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230103   071000    071959  1672701599  16706.5  16706.5
12140  20230103   072000    072959  1672702199  16706.6    16705
12141  20230103   073000    073959  1672702799    16705  16690.5
12142  20230103   074000    074959  1672703399  16690.5  16680.2
12143  20230103   075000    075959  1672703999  16680.2    16666
2023-01-03 08:00:00,963:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5577 

self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16665.9', self.close='16675.1'
2023-01-03 08:10:01,547:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16665.9', self.close='16675.1'
2023-01-03 08:10:01,564:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230103   072000    072959  1672702199  16706.6    16705
12141  20230103   073000    073959  1672702799    16705  16690.5
12142  20230103   074000    074959  1672703399  16690.5  16680.2
12143  20230103   075000    075959  1672703999  16680.2    16666
12144  20230103   080000    080959  1672704599  16665.9  16675.1
2023-01-03 08:10:01,564:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6584
self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16659.9, self.close=16675.1, self.high=16677.5, self.low=16659.1, self.vol=1052.168, self.amt=17538165.5228 
127.0.0.1 - - [03/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-03 08:10:01,454:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230103   074500    074959  ...         0.0        0.0       0
5854  20230103   075000    075459  ...         0.0        0.0       0
5855  20230103   075500    075959  ...         0.0        0.0       0
5856  20230103   080000    080459  ...         0.0        0.0       0
5857  20230103   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 08:10:01,455:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672704599, self.tradeDate='20230103', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16659.9, self.close=16675.1, self.high=16677.5, self.low=16659.1, self.vol=1052.168, self.amt=17538165.5228, ukdf['pct'].iloc[-1]=0.000912 , ukdf['amount'].iloc[-1]=17538165.5228, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6585
self.closeSec=1672704899, self.tradeDate='20230103', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16675.0, self.close=16682.5, self.high=16682.5, self.low=16670.7, self.vol=733.383, self.amt=12230050.474 
2023-01-03 08:15:00,595:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230103   075000    075459  ...         0.0        0.0       0
5855  20230103   075500    075959  ...         0.0        0.0       0
5856  20230103   080000    080459  ...         0.0        0.0       0
5857  20230103   080500    080959  ...         0.0        0.0       0
5858  20230103   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 08:15:00,596:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672704899, self.tradeDate='20230103', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16675.0, self.close=16682.5, self.high=16682.5, self.low=16670.7, self.vol=733.383, self.amt=12230050.474, ukdf['pct'].iloc[-1]=0.000444 , ukdf['amount'].iloc[-1]=12230050.474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230102   200000    235959  1672675199  ...    719  0.216347 -0.038365     NaN
720  20230103   000000    035959  1672689599  ...    720  0.235114  0.060823     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-8959.808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16730.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891007.4496510001, self.flagDict['side']='sell', self.tradeCount=9, self.count=232
self.closeSec=1672703999, self.tradeDate='20230103', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16730.5, self.close=16666.0, self.high=16799.0, self.low=16650.0, self.vol=35222.075, self.amt=588827379.8831 
127.0.0.1 - - [03/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-03 08:00:00,738:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672703999, self.tradeDate='20230103', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16730.5, self.close=16666.0, self.high=16799.0, self.low=16650.0, self.vol=35222.075, self.amt=588827379.8831 
2023-01-03 08:00:00,772:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230102   120000    155959  ...  53334.962  8.901111e+08  0.003476
718  20230102   160000    195959  ...  37547.955  6.280194e+08  0.000951
719  20230102   200000    235959  ...  35861.233  5.990651e+08  0.000036
720  20230103   000000    035959  ...  16546.853  2.766021e+08  0.000078
721  20230103   040000    075959  ...  35222.075  5.888274e+08 -0.003849

[5 rows x 11 columns]
2023-01-03 08:00:02,404:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230102   120000    155959  1672646399  ...    717  0.081884 -0.510533     NaN
718  20230102   160000    195959  1672660799  ...    718  0.163524 -0.237419     NaN
719  20230102   200000    235959  1672675199  ...    719  0.216347 -0.038365     NaN
720  20230103   000000    035959  1672689599  ...    720  0.235114  0.060823     NaN
721  20230103   040000    075959  1672703999  ...    721  0.297501  0.321886     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-5476.0365', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16665.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


