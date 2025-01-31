x="{} is a high-level {} language"
print(x.format('python','programing'))

print(x.format('java','progaming'))

y="{a} is a high-level {b} language"

print(y.format(b='programing',a='java'))

y="{1} is a high-level {0} language"

print(y.format('programing','java'))


l='lamda'
m=4556


y="{} is a high-level {} language"
print(y)
print(y.format(l,m))



l=10
m=15
c=20

print("c=",c,"m=",m)
print(f"c={c} m={m}")
