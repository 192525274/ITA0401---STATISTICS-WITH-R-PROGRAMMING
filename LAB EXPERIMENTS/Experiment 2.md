## PROGRAM
``` R PROGAM
# 5x4 Matrix filled by row
m1 <- matrix(1:20, nrow=5, ncol=4, byrow=TRUE,
             dimnames=list(paste0("R",1:5), paste0("C",1:4)))
print(m1)

# 3x3 Matrix filled by column
m2 <- matrix(1:9, nrow=3, ncol=3, byrow=FALSE,
             dimnames=list(paste0("R",1:3), paste0("C",1:3)))
print(m2)

# 2x2 Matrix filled by row
m3 <- matrix(1:4, nrow=2, ncol=2, byrow=TRUE,
             dimnames=list(paste0("R",1:2), paste0("C",1:2)))
print(m3)
```
# OUTPUT
<img width="705" height="438" alt="WhatsApp Image 2026-10-13 at 09 47 19" src="https://github.com/user-attachments/assets/933ee7fe-bfb9-4240-9bb1-3d8263a5e033" />























