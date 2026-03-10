# Application-level-Array-program-1
import array

# Array to store sales of 5 days
sales = array.array('i', [200, 350, 300, 400, 250])

# Display sales
print("Daily Sales:", sales)

# Total sales
total = sum(sales)
print("Total Sales:", total)

# Average sales
average = total / len(sales)
print("Average Sales:", average)



Daily Sales: array('i', [200, 350, 300, 400, 250])
Total Sales: 1500
Average Sales: 300.0
