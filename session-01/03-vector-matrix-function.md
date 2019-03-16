### 1. Vector
#### A. Numeric vector
```{}
#########################
# open R application (linux/windows)
# type
1 + 1

# more about Arithmetic Operators
?Arithmetic

# store values in variables(buckets)
# variable 'a'
a = 1

# variable 'b'
b = 10

# sum
a + b

# product
a * b

# division
a / b

#########################
# multiple values
manyVariables = c(1,2,4)

manyVariables * a

manyVariables / b

#########################
# store outputs
output = manyVariables * a
```

#### B. Character vector
```{}
#########################
firstName = 'Rintu'
lastName = 'Kutum'

# join first and last name
paste(firstName, lastName, sep=' ')
```

#### C. Factor vector
```{}
#########################
abc = c('A', 'B', 'C')
abcFactor = factor(abc)

abcFactorManual = factor(
  abc,
  levels = c('C','A','B')
)
```
#### D. Access elements in Vector
```{}
myNumbersManual = c(1,2,3)
# or
myNumbersAuto = 1:3

## access second elemnt
myNumbersAuto[2]

## access by name
names(myNumbersManual) = c(
  'one',
  'two',
  'three'
)
## access second element
myNumbersManual['one']
```

## functions
```{}
# single input 'x'
square <- function(x){
  output = x * x
  return(output)
}

square(x=2)

# two inputs 'a' and 'b'
add <- function(a, b){
  output = a + b
  return(output)
}
add(a = 2, b = 92)

```



## Matrix

```{}
# get random numbers
rnorm(n=100,mean=10,sd=10)

# store into an variable
set.seed(1029)
myValues <- rnorm(n=100,mean=10,sd=10)
myMat <- matrix(
  data = myValues,
  nrow = 20,
  ncol = 5
)
# Access elements
# first row
myMat[1,]
# fisrt column
myMat[,1]

```
