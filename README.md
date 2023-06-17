# matrix 

# matrix k with variables 
x=8*cos(55)/23
y=45* sin(90)+ 32
x
y

u=2*98+sin(45)
z=(tan(23)*6)- 85
u
z

k<-matrix(c(x,y,z,u), ncol=2, nrow=2)
k
solve(k)



# simple matrix with numbers 
m<-matrix(c(12,3,45,3,4,56,78,90,1), ncol=3, nrow=3)
m
solve(m)

#rbind is the function to add new row in the matrix but need to initialize it with new matrix 
a<-rbind(k, c(34,66))
a


#display matrix no. in col and row 
k[2,]
m[1,2]
k[2,2] *m[1,2]

# View function shows you the data in tabular form 
View(m)

matrix(1:8, ncol=3, nrow=4)
diag(matrix)
matrix(1:8, nrow=2, byrow=TRUE)
diag(2)
1:5 %o% 1:5

outer(1:3 , 1:5, "-")
outer(1:3 , 1:5, "*")

A <- matrix(c(1:8,10), 3, 3)
A
solve(A)
x <- c(1,2,3)
x
A %*% x 
diag(x)
