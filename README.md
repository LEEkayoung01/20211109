# 20211109 컴프투 실습과제

#1 MSE
>>>def solution(predict_list, ground_truth_list):
>>>  n = len(predict_list)
>>>  sum = 0
>>>  for i in range(n):
>>>    temp = (ground_truth_list[i] - predict_list[i])**2
>>>    sum += temp
>>>  MSE = round(sum/n, 1)
>>>  return MSE

>>> solution([1, 5, 10], [11, 15, 12])


