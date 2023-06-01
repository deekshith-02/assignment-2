# assignment-2
Write a Python program to get a list, sorted in increasing order by the last element in each tuple from a given list of non-empty tuples

def sort_tuples_by_last_element(tuples_list):
    sorted_list = sorted(tuples_list, key=lambda x: x[-1])
    return sorted_list

# Test the function with the sample list
sample_list = [(2, 5), (1, 2), (4, 4), (2, 3), (2, 1)]
result = sort_tuples_by_last_element(sample_list)
print(result)
