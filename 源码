import math 
def test_acc(test):
    a=0
    print(a)
    for i in range(len(test)):
        for test_col in target_cols:
           a = (test_pred[test_col][i]-train[test_col][i])**2 + a 
        #    print(test_pred[test_col][i])
        #    print(train[test_col][i])
    print(a)
    rmse = math.sqrt(a/(6*len(test)))
    print('RMSE: ',rmse)
    score = 1/(1+rmse)
    print('score: ',score)
