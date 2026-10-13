## PROGRAM
``` R PROGRAM
# 1. Factors of a Number
n <- 12
cat("Factors of", n, "are:")
for (i in 1:n) {
  if (n %% i == 0) {
    cat(i, " ")
  }
}
cat("\n\n")

# 2. Generate 10 Random Integers
x <- sample(-50:50, 10, replace = TRUE)
cat("Random integers:\n")
print(x)

# 3. FizzBuzz from 1 to 100
cat("\nFizzBuzz:\n")
for (i in 1:100) {
  if (i %% 3 == 0 && i %% 5 == 0) {
    cat("FizzBuzz\n")
  } else if (i %% 3 == 0) {
    cat("Fizz\n")
  } else if (i %% 5 == 0) {
    cat("Buzz\n")
  } else {
    cat(i, "\n")
  }
}
```
# output
<img width="663" height="554" alt="WhatsApp Image 2026-10-13 at 09 55 45" src="https://github.com/user-attachments/assets/c980ab3b-389a-4fb5-81fd-0fa7af9dd040" />
<img width="631" height="559" alt="WhatsApp Image 2026-10-13 at 09 56 23" src="https://github.com/user-attachments/assets/ce8152ff-5ed9-4a90-808b-c32f5659c5ca" />
<img width="675" height="561" alt="WhatsApp Image 2026-10-13 at 09 57 01" src="https://github.com/user-attachments/assets/1bf43d6c-e8d3-41f1-b8ae-669834cf4316" />
<img width="646" height="504" alt="WhatsApp Image 2026-10-13 at 09 57 33" src="https://github.com/user-attachments/assets/a453c032-1d09-4f9c-ae4a-5caaa3dfb67b" />


