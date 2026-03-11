# Student marks list
marks = [78, 45, 90, 66, 82]

n = len(marks)

# Bubble Sort
for i in range(n):
    for j in range(0, n-i-1):
        if marks[j] > marks[j+1]:
            marks[j], marks[j+1] = marks[j+1], marks[j]

print("Sorted Student Marks:", marks)
