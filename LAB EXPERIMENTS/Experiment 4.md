## PROGRAM
``` R PROGRAM
# Create vectors
v <- 1:12

# Create array with dimension names
arr <- array(v, dim = c(2, 3, 2),
             dimnames = list(
               Rows = c("R1", "R2"),
               Columns = c("C1", "C2", "C3"),
               Tables = c("T1", "T2")
             ))

# Display the array
print(arr)

# Print specific elements
print(arr[1, 2, 1])
print(arr[2, 3, 2])
```
# OUTPUT
<img width="660" height="531" alt="WhatsApp Image 2026-10-13 at 09 51 23" src="https://github.com/user-attachments/assets/6a25bd81-337d-46ae-9f03-f2c72d49380b" />
