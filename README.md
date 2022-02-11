# dinesh-gallasno=int(input('enter student no:'))
sname=input('enter student name:')
sgroup=input('enter student group:')
s1=int(input('maths marks:'))
s2=int(input('statistics marks:'))
s3=int(input('computer science marks:'))
s4=int(input('telugu marks:'))
s5=int(input('english marks'))
s6=int(input('online business marks'))
if s1>=35 and s2>=35 and s3>=35 and s4>=35 and s5>=35 and s6>=35:
    print(sname,'is passed')
else:
    print(sname,'is failed')
