from collections import Counter

def intersect(nums1, nums2):
    count1, count2 = Counter(nums1), Counter(nums2)
    intersection = []

    for num in count1:
        if num in count2:
            freq = min(count1[num], count2[num])
            intersection.extend([num] * freq)

    return intersection

# Test examples
print(intersect([1, 2, 2, 1], [2, 2]))  # Output: [2, 2]
print(intersect([4, 9, 5], [9, 4, 9, 8, 4]))  # Output: [9, 4]
