# MidtermExamProblem7
Problem 7 Midterm

def satisfies(L):
newList = L[:]
for i in newList:
  if f(i)==false:
    L.remove(i)
 return len(L)
def f(s):
return 'a' in s
L = ['a', 'b', 'a']
print satisfiesF(L)
print L
run_satisfiesF(L, satisfiesF)
