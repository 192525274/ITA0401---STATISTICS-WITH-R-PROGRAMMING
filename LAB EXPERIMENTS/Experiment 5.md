## PROGRAM
``` R PROGRAM
# Create factor variables using women dataset
height <- factor(women$height)
print(height)

# Create a random LETTER sample
letters_sample <- sample(LETTERS, 5)
letter_factor <- factor(letters_sample)
print(letter_factor)

# Manipulate factor variables
print(levels(letter_factor))
print(nlevels(letter_factor))

# Convert factor to character
print(as.character(letter_factor))
```
# OUTPUT
<img width="544" height="353" alt="WhatsApp Image 2026-10-13 at 09 53 37" src="https://github.com/user-attachments/assets/27516cd4-8fa1-49aa-ab4c-c4be3f4f5a07" />
