# 20230114 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13754
self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=19950.0, self.close=20008.4, self.high=20100.0, self.low=19926.0, self.vol=17780.903, self.amt=355918411.79495 
127.0.0.1 - - [14/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-14 08:10:01,483:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230114   074500    074959  ...         0.0        0.0       0
5854  20230114   075000    075459  ...         0.0        0.0       0
5855  20230114   075500    075959  ...         0.0        0.0       0
5856  20230114   080000    080459  ...         0.0        0.0       0
5857  20230114   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 08:10:01,483:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=19950.0, self.close=20008.4, self.high=20100.0, self.low=19926.0, self.vol=17780.903, self.amt=355918411.79495, ukdf['pct'].iloc[-1]=0.002927 , ukdf['amount'].iloc[-1]=355918411.79495, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-209660.50818584224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20013.42171274', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13755
self.closeSec=1673655299, self.tradeDate='20230114', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20013.2, self.close=20253.0, self.high=20344.6, self.low=20004.1, self.vol=28713.264, self.amt=580513269.55186 
127.0.0.1 - - [14/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-14 08:15:00,727:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230114   075000    075459  ...         0.0        0.0       0
5855  20230114   075500    075959  ...         0.0        0.0       0
5856  20230114   080000    080459  ...         0.0        0.0       0
5857  20230114   080500    080959  ...         0.0        0.0       0
5858  20230114   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 08:15:00,727:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673655299, self.tradeDate='20230114', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20013.2, self.close=20253.0, self.high=20344.6, self.low=20004.1, self.vol=28713.264, self.amt=580513269.55186, ukdf['pct'].iloc[-1]=0.012225 , ukdf['amount'].iloc[-1]=580513269.55186, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-224105.93859941728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20253.47473078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=303, self.factor=0.17624244642216394, self.count=14320 

self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=19950.0, self.close=20008.4, self.high=20100.0, self.low=19926.0 
2023-01-14 08:10:01,416:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=19950.0, self.close=20008.4, self.high=20100.0, self.low=19926.0   
2023-01-14 08:10:01,450:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230114   074500    074959  1673653799  ...  19832.5  0.000181   1533    3
1534  20230114   075000    075459  1673654099  ...  19851.2  0.002543   1534    4
1535  20230114   075500    075959  1673654399  ...  19900.7  0.000583   1535    5
1536  20230114   080000    080459  1673654699  ...  19882.6  0.001295   1536    0
1537  20230114   080500    080959  1673654999  ...  19926.0  0.002927   1537    1

[5 rows x 11 columns]
2023-01-14 08:10:01,456:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=303, self.factor=0.17624244642216394, self.count=14321 

self.closeSec=1673655299, self.tradeDate='20230114', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20013.2, self.close=20253.0, self.high=20344.6, self.low=20004.1 
2023-01-14 08:15:00,588:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673655299, self.tradeDate='20230114', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20013.2, self.close=20253.0, self.high=20344.6, self.low=20004.1   
127.0.0.1 - - [14/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-14 08:15:00,692:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230114   075000    075459  1673654099  ...  19851.2  0.002543   1534    4
1535  20230114   075500    075959  1673654399  ...  19900.7  0.000583   1535    5
1536  20230114   080000    080459  1673654699  ...  19882.6  0.001295   1536    0
1537  20230114   080500    080959  1673654999  ...  19926.0  0.002927   1537    1
1538  20230114   081000    081459  1673655299  ...  20004.1  0.012225   1538    2

[5 rows x 11 columns]
2023-01-14 08:15:00,692:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-14 08:00:33,903:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230114    052959  19464.0  ...  57.083333  0.664940  0.184052
5771  20230114    055959  19458.8  ...  57.500000  0.705235  0.177507
5772  20230114    062959  19808.9  ...  57.500000  0.717544  0.166701
5773  20230114    065959  19932.1  ...  57.500000  0.696154  0.164046
5774  20230114    072959  19842.1  ...  57.083333  0.689954  0.163006

[5 rows x 33 columns]
0.5545286506469501
acc is : 0.5545286506469501
2023-01-14 08:00:34,095:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.527028  0.472972       1  ...  1.068243   1.0    0.0  1.185270
537     0  0.633889  0.366111       1  ...  1.074952   1.0    0.0  1.192714
538     0  0.602647  0.397353       0  ...  1.070115   1.0    0.0  1.187346
539     0  0.553208  0.446792       0  ...  1.068686   1.0    0.0  1.185761
540     0  0.548103  0.451897       1  ...  1.074543   1.0    0.0  1.192259

[5 rows x 10 columns]
2023-01-14 08:00:34,127:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526787  0.473213       1  ...  1.068243   1.0    0.0  1.184002
46     0  0.634091  0.365909       1  ...  1.074952   1.0    0.0  1.191637
47     0  0.602703  0.397297       0  ...  1.070115   1.0    0.0  1.187858
48     0  0.553208  0.446792       0  ...  1.068686   1.0    0.0  1.185761
49     0  0.548103  0.451897       1  ...  1.074543   1.0    0.0  1.192259

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230114   074000    074959  1673653799  19835.4  19858.7  0.001175
2023-01-14 07:50:00,631:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7159 

self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='19858.6', self.close='19924.2'
127.0.0.1 - - [14/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-14 08:00:00,952:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='19858.6', self.close='19924.2'
2023-01-14 08:00:00,965:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230114   071000    071959  1673651999  19858.6  19795.8 -0.003167
620  20230114   072000    072959  1673652599  19795.9  19815.6  0.001000
621  20230114   073000    073959  1673653199  19815.7  19835.4  0.000999
622  20230114   074000    074959  1673653799  19835.4  19858.7  0.001175
623  20230114   075000    075959  1673654399  19858.6  19924.2  0.003298
2023-01-14 08:00:00,965:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7160 

self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='19924.3', self.close='20008.4'
2023-01-14 08:10:01,816:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='19924.3', self.close='20008.4'
127.0.0.1 - - [14/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-14 08:10:01,847:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230114   072000    072959  1673652599  19795.9  19815.6  0.001000
621  20230114   073000    073959  1673653199  19815.7  19835.4  0.000999
622  20230114   074000    074959  1673653799  19835.4  19858.7  0.001175
623  20230114   075000    075959  1673654399  19858.6  19924.2  0.003298
624  20230114   080000    080959  1673654999  19924.3  20008.4  0.004226
2023-01-14 08:10:01,851:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230114   074000    074959  1673653799  19835.4  19858.7
2023-01-14 07:50:00,647:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7160 

self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='19858.6', self.close='19924.2'
127.0.0.1 - - [14/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-14 08:00:00,929:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='19858.6', self.close='19924.2'
2023-01-14 08:00:00,989:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230114   071000    071959  1673651999  19858.6  19795.8
17468  20230114   072000    072959  1673652599  19795.9  19815.6
17469  20230114   073000    073959  1673653199  19815.7  19835.4
17470  20230114   074000    074959  1673653799  19835.4  19858.7
17471  20230114   075000    075959  1673654399  19858.6  19924.2
2023-01-14 08:00:00,989:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7161 

self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='19924.3', self.close='20008.4'
2023-01-14 08:10:01,807:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='19924.3', self.close='20008.4'
2023-01-14 08:10:01,858:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230114   072000    072959  1673652599  19795.9  19815.6
17469  20230114   073000    073959  1673653199  19815.7  19835.4
17470  20230114   074000    074959  1673653799  19835.4  19858.7
17471  20230114   075000    075959  1673654399  19858.6  19924.2
17472  20230114   080000    080959  1673654999  19924.3  20008.4
2023-01-14 08:10:01,859:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230114   074000    074959  1673653799  19835.4  19858.7
2023-01-14 07:50:00,640:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7160 

self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='19858.6', self.close='19924.2'
2023-01-14 08:00:00,930:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='19858.6', self.close='19924.2'
127.0.0.1 - - [14/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-14 08:00:00,975:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230114   071000    071959  1673651999  19858.6  19795.8
12140  20230114   072000    072959  1673652599  19795.9  19815.6
12141  20230114   073000    073959  1673653199  19815.7  19835.4
12142  20230114   074000    074959  1673653799  19835.4  19858.7
12143  20230114   075000    075959  1673654399  19858.6  19924.2
2023-01-14 08:00:00,975:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7161 

self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='19924.3', self.close='20008.4'
2023-01-14 08:10:01,827:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='19924.3', self.close='20008.4'
127.0.0.1 - - [14/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-14 08:10:01,855:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230114   072000    072959  1673652599  19795.9  19815.6
12141  20230114   073000    073959  1673653199  19815.7  19835.4
12142  20230114   074000    074959  1673653799  19835.4  19858.7
12143  20230114   075000    075959  1673654399  19858.6  19924.2
12144  20230114   080000    080959  1673654999  19924.3  20008.4
2023-01-14 08:10:01,855:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9752
self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=19950.0, self.close=20008.4, self.high=20100.0, self.low=19926.0, self.vol=17780.903, self.amt=355918411.79495 
127.0.0.1 - - [14/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-14 08:10:01,492:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230114   074500    074959  ...         0.0        0.0       0
5854  20230114   075000    075459  ...         0.0        0.0       0
5855  20230114   075500    075959  ...         0.0        0.0       0
5856  20230114   080000    080459  ...         0.0        0.0       0
5857  20230114   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 08:10:01,497:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673654999, self.tradeDate='20230114', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=19950.0, self.close=20008.4, self.high=20100.0, self.low=19926.0, self.vol=17780.903, self.amt=355918411.79495, ukdf['pct'].iloc[-1]=0.002927 , ukdf['amount'].iloc[-1]=355918411.79495, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9753
self.closeSec=1673655299, self.tradeDate='20230114', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20013.2, self.close=20253.0, self.high=20344.6, self.low=20004.1, self.vol=28713.264, self.amt=580513269.55186 
127.0.0.1 - - [14/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-14 08:15:00,728:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230114   075000    075459  ...         0.0        0.0       0
5855  20230114   075500    075959  ...         0.0        0.0       0
5856  20230114   080000    080459  ...         0.0        0.0       0
5857  20230114   080500    080959  ...         0.0        0.0       0
5858  20230114   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 08:15:00,728:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673655299, self.tradeDate='20230114', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20013.2, self.close=20253.0, self.high=20344.6, self.low=20004.1, self.vol=28713.264, self.amt=580513269.55186, ukdf['pct'].iloc[-1]=0.012225 , ukdf['amount'].iloc[-1]=580513269.55186, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230113   200000    235959  1673625599  ...    719  1.171959  1.306448     1.0
720  20230114   000000    035959  1673639999  ...    720  1.163214  1.258982     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '110678.7584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19352.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=298
self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=19354.1, self.close=19924.2, self.high=19997.8, self.low=19307.4, self.vol=253648.534, self.amt=4995445212.24883 
127.0.0.1 - - [14/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-14 08:00:00,828:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673654399, self.tradeDate='20230114', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=19354.1, self.close=19924.2, self.high=19997.8, self.low=19307.4, self.vol=253648.534, self.amt=4995445212.24883 
2023-01-14 08:00:00,849:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230113   120000    155959  ...   30968.560  5.827712e+08 -0.002856
718  20230113   160000    195959  ...  102428.168  1.939314e+09  0.004995
719  20230113   200000    235959  ...  200752.474  3.826630e+09  0.018021
720  20230114   000000    035959  ...  170547.519  3.282301e+09  0.005215
721  20230114   040000    075959  ...  253648.534  4.995445e+09  0.029520

[5 rows x 11 columns]
2023-01-14 08:00:03,082:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230113   120000    155959  1673596799  ...    717  1.171585  1.361232     1.0
718  20230113   160000    195959  1673611199  ...    718  1.132857  1.238241     1.0
719  20230113   200000    235959  1673625599  ...    719  1.171959  1.306448     1.0
720  20230114   000000    035959  1673639999  ...    720  1.163214  1.258982     1.0
721  20230114   040000    075959  1673654399  ...    721  1.235840  1.402725     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '139913.2096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19924.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


