practice2
======
print "Funny calender"
god=0
while god<=0:
       god = int(input("Imput year: "))
year = god
if year % 4 == 0:
	if year % 100 == 0 and year % 400 != 0:
		year = 365
	else:
		year = 366
else:
	year = 365
print("The number of days in "+str(god)+ " year:"+ str(year))
if year==365:
        print "It is a not leap year"
else:
        print "It is  a leap year"
January=March=May=July=August=October=December=[x for x in range (1,32)]
April=June=September=November=[x for x in range(1,31)]
if year==365:
        February=[x for x in range (1,29)]
else:
        February=[x for x in range (1,30)]
print "I will print a month for you in particular order! "
num=int(input("Please, input the number of month  "))
if num==7 or num==8:
       print "It is a summer month, I will print it like a snake"
       def spiral(n):
           dx,dy = 1,0            # Starting increments
           x,y = 0,0              # Starting location
           myarray = [[None]* n for j in range(n)]
           for i in xrange(n**2):
               myarray[x][y] = i+1
               nx,ny = x+dx, y+dy
               if 0<=nx<n and 0<=ny<n and myarray[nx][ny] == None:
                   x,y = nx,ny
               else:
                   dx,dy = -dy,dx
                   x,y = x+dx, y+dy
           return myarray
 
       def printspiral(myarray):
           n = range(len(myarray))
           for y in n:
               for x in n:
                   print "%2i" % myarray[x][y],
               print
 
       printspiral(spiral(5))
       def spiral(n):
           dx,dy = 1,0            # Starting increments
           x,y = 0,0              # Starting location
           myarray = [[None]* n for j in range(n)]
           for i in xrange(n**2):
               myarray[x][y] = i+25
               nx,ny = x+dx, y+dy
               if 0<=nx<n and 0<=ny<n and myarray[nx][ny] == None:
                   x,y = nx,ny
               else:
                   dx,dy = -dy,dx
                   x,y = x+dx, y+dy
           return myarray
       print  
       def printspiral(myarray):
           n = range(len(myarray))
           for y in n:
               for x in n:
                   print "%2i" % myarray[x][y],
               print
       printspiral(spiral(2))
       print
       print 29,30,31

if num==6:
       
       def spiral(n):
           dx,dy = 1,0            # Starting increments
           x,y = 0,0              # Starting location
           myarray = [[None]* n for j in range(n)]
           for i in xrange(n**2):
               myarray[x][y] = i+1
               nx,ny = x+dx, y+dy
               if 0<=nx<n and 0<=ny<n and myarray[nx][ny] == None:
                   x,y = nx,ny
               else:
                   dx,dy = -dy,dx
                   x,y = x+dx, y+dy
           return myarray
 
       def printspiral(myarray):
           n = range(len(myarray))
           for y in n:
               for x in n:
                   print "%2i" % myarray[x][y],
               print
 
       printspiral(spiral(5))
       def spiral(n):
           dx,dy = 1,0            # Starting increments
           x,y = 0,0              # Starting location
           myarray = [[None]* n for j in range(n)]
           for i in xrange(n**2):
               myarray[x][y] = i+25
               nx,ny = x+dx, y+dy
               if 0<=nx<n and 0<=ny<n and myarray[nx][ny] == None:
                   x,y = nx,ny
               else:
                   dx,dy = -dy,dx
                   x,y = x+dx, y+dy
           return myarray
       print  
       def printspiral(myarray):
           n = range(len(myarray))
           for y in n:
               for x in n:
                   print "%2i" % myarray[x][y],
               print
       printspiral(spiral(2))
       print
       print 29,30

if num==3  or num==5:
       print "It is a spring month, I will print it upsidedown"
       print March[::-1]
if num==4:
       print "It is a spring month, I will print it upsidedown"
       h=April[::-1]
       print h
       
if num==12 or num==1 or num==2:

       board = []
       for i in range(0,9):
           board.append([" "] * 9)
       def print_board(board):
           for row in board:
               print " ".join(row)
      # print_board(board) 
if num==12 or num==1 or num==2:
       print "It is a winter month, I will print you a snowdrop"
       for i in range(0,9):
              w=4
              board[w][i]= "x"
       for i in range(0,9):
              M=4
              board[i][M]="x"
              
       for i in range(1,8):
              for j in range(1,8):
                     if i==j:
                            board[i][j]="x"
       for i in range(1,8):
              for j in range(1,8):
                     if i+j==8:
                            board[i][j]="x"
                            
       print print_board(board)
if num==9 or num==10 or num==11:
       print "It is a autumn month, I will print even numbers and then odd numbers"
if num==9 or num==11:
       print September[1::2]
       print September[0::2]
if num==10:
       print October[1::2]
       print October[0::2]
