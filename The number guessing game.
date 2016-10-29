print '                 .......WELCOME TO THE GUESSING GAME.......'
print '                 --------------TRY YOUR LUCK---------------'
ch='Y'
hs=0
print
print 'Instruction:-'
print 'There is a no. and you have to guess the no. between the selected range'
while ch=='y' or ch=='Y':
    c=0
    print
    print 'Choose Difficulty Level                             High Score:',hs
    print '1.Easy(1-100)\n2.Moderate(1-300)\n3.High(1-500)\n4.Extreme(1-800)\n5.Professional(1-1000)'
    d=input('Enter your choice(1,2,3,4,5):')
    import random
    if d==1:
        r=random.randint(1,100)
        u=100
    elif d==2:
        r=random.randint(1,300)
        u=300
    elif d==3:
        r=random.randint(1,500)
        u=500
    elif d==4:
        r=random.randint(1,800)
        u=800
    elif d==5:
        r=random.randint(1,1000)
        u=1000
    else:
        print
        print 'Wrong Input!!'
        break
    print
    print 'Enter any no. between(1 -',u,')'
    g=input('')
    print
    while g!=r:
        c+=1
        if g>r:
            print 'You guessed it wrong, it is greater than the no.'
        elif g<r:
            print 'You guessed it wrong, it is smaller than the no.'
        g=input('Try again:')    
    else:
        print 
        print 'You guessed it right.....You won the game!!!!'
    print
    if c==0:
        score=1000
    elif c==1:
        score=800
    elif c==2:
        score=700
    elif c==3:
        score=600
    elif c==4:
        score=500
    elif c==5:
        score=400
    elif c==6:
        score=300
    elif c>=7 and c<=10:
        score=250
    else:
        score=50
    s=score
    if s>hs:
        hs=s
    print 'Your Score is:',score
    print
    ch=raw_input('Do you want to play the game again(Y/N):')
    print
    print '                        ----------********-----------'
else:
    print 
    print 'Thanks for playing.....Have a Good time....'
    print
    print '                        ----------********-----------'
