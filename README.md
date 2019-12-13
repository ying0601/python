##QUESTION 1
(A)
def reverse_word(f):
    f = f[::-1]
    return f

(B) 不好意思，這題仍有誤，但未能於時間內解決
def reverse_word(f):
    f = f[::-1]
    list_f = list(f)
    list_rev = list_f.reverse()
    ans = " ".join(list_rev)
    return ans

##QUESTION 2
num = int(input("enter a number:"))
a = []
b = []
for i in range(1,num+1):
    if i%3!=0:
      if i%5!=0:
        a.append(i)
for j in range(1,num+1):
    if j%15==0:
        b.append(j)
print(len(a)+len(b))

##QUESTION 3
假設我拿的袋子上面寫"原子筆"，而裡面裝的是"鉛筆"，那麼其他兩個袋子應分別標示"鉛筆"及"混和"，
則可以確定，標示"鉛筆"的袋子裝的為"混和"；標示"混和"內裝的是"原子筆"

##QUESTION 4
$750除3代表一人須付$250，一開始拿$300/人，表示會退回$50/人，但最後只收回$30/人，
代表中間差額為$20*3=$60(也就是服務生按扛的金額數)。
如果用題目敘述的方式計算，在實際收回與應收回的差額上會出問題，故無法以題目的方式計算，
應用以上的方式。
