set1 = {1, 2, 3, 4, 5}
set2 = {4, 5, 6, 7, 8}
union_set = set1.union(set2)
print("union:", union_set)
intersection_set = set1.intersection(set2)
print("intersection", intersection_set)
difference_set = set1.difference(set2)
print("difference (set1 - set2):", difference_set)
symmetric_difference_set = set1.symmetric_difference(set2)
print("symmetric difference:", symmetric_difference_set)
out put:union: {1, 2, 3, 4, 5, 6, 7, 8}
intersection {4, 5}
difference (set1 - set2): {1, 2, 3}
symmetric difference: {1, 2, 3, 6, 7, 8}
​
