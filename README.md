# 迭代
# -*- coding: utf-8 -*-

def findMinAndMax(L):

	min=max=L[0]
	
	if L==[]:
	
		return(None,None)
		
	for x in L:
	
		if x<=min:
		
			min=x
			
		if x>=max:
		
			max=x
	return min,max
	
print(findMinAndMax([7，1,3,5,6]))
