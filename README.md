# wek-2

my_list = []
print(f"Initial empty list: {my_list}")

# Append the following elements to my_list: 10, 20, 30, 40.
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
print(f"After appending 10, 20, 30, 40: {my_list}")

# Insert the value 15 at the second position (index 1) in the list.
my_list.insert(1, 15)
print(f"After inserting 15 at second position: {my_list}")

# Extend my_list with another list: [50, 60, 70].
my_list.extend([50, 60, 70])
print(f"After extending with [50, 60, 70]: {my_list}")

# Remove the last element from my_list.
# The pop() method removes and returns the last item by default.
my_list.pop()
print(f"After removing the last element: {my_list}")

# Sort my_list in ascending order.
my_list.sort()
print(f"After sorting in ascending order: {my_list}")

# Find and print the index of the value 30 in my_list.
try:
    index_of_30 = my_list.index(30)
    print(f"The index of value 30 in my_list is: {index_of_30}")
except ValueError:
    print("Value 30 not found in the list.")

