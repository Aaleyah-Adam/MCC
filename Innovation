data = [
    [31, 18, 15, 29],
    [17, 28, 9, 29],
    [10, 30, 17, 17],
    [3, 11, 23, 39],
    [18, 29, 14, 9],
    [21, 22, 25, 13],
    [14, 34, 2, 3],
    [13, 9, 18, 21],
    [22, 12, 22, 15],
    [8, 25, 27, 18],
    [14, 4, 54, 17],
    [3, 6, 22, 37],
    [28, 9, 16, 16],
    [20, 12, 28, 14],
    [9, 12, 13, 33],
    [8, 27, 26, 15],
    [14, 15, 26, 18],
    [5, 8, 32, 26],
    [13, 15, 34, 22],
    [10, 3, 47, 27],
    [6, 6, 21, 35],
    [9, 6, 27, 35],
    [8, 21, 34, 26],
    [21, 11, 33, 18],
    [6, 16, 10, 30],
    [17, 20, 14, 36],
    [6, 4, 20, 34],
    [8, 15, 22, 21],
    [27, 9, 30, 18],
    [21, 20, 20, 9]
]

# Calculate the sum of all 4 integers across the data
total_sum = sum(sum(row) for row in data)

# Calculate the sum of the first two elements of each row
sum_of_first_two = sum(row[0] + row[1] for row in data)

print("Sum of all 4 integers: ", total_sum)
print("Sum of the first two elements of each row: ", sum_of_first_two)

highest = 0

for subarray in data:
    sum_of_four = sum(subarray)
    print(f"Sum of {subarray}: {sum_of_four}")
    if sum_of_four > highest:
        highest = sum_of_four

for subarray in data:
    sum_of_first_two = subarray[0] + subarray[1]
    print(f"Sum of the first two numbers in {subarray}: {sum_of_first_two}")


print(highest)
