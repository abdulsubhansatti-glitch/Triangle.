# Number of rows for the triangle
rows = 8

# Outer loop for each row
for i in range(1, rows + 1):
    # Inner loop for each star in the row
    for j in range(i):
        print("*", end=" ")
    # Move to the next line after finishing a row
    print()
