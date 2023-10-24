# mnojestva-1
def count_unique_numbers(nums):
    return len(set(nums))
def count_common_numbers(list1, list2):
    return len(set(list1) & set(list2))
def find_common_numbers(list1, list2):
    common_numbers = sorted(set(list1) & set(list2))
    return common_numbers
def check_repeated_numbers(sequence):
    nums = set()
    for num in sequence:
        if num in nums:
            print("YES")
        else:
            print("NO")
            nums.add(num)
def count_different_words(file_name):
    with open(file_name, 'r') as file:
        text = file.read()
    words = text.split()
    different_words = set(words)
    return len(different_words)
