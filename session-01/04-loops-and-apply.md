## for loop
```{R}
# vector
vec = c(1,2,10,10)

Len = length(vec)
for(i in 1:Len){
	print(vec[i])
}

# matrix
nums = rnorm(n=100,mean=19,sd=0.14)
mat = matrix(data = nums, ncol = 10,nrow=10)

nRows = nrow(mat)
nCols = ncol(mat)

for(i in 1:nRows){
	for(j in 1:nCols){
		print(mat[i,j])
	}
}
```

