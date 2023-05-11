# Write-a-Python-program-to-remove-duplicates-from-Dictionary

my_dict = {"a": 10, "b": 20, "c": 30, "d": 20, "e": 50, "f": 30}
unique_dict = {}
for key, value in my_dict.items():
 if value not in unique_dict.values():
 unique_dict[key] = value
print("Original dictionary:", my_dict)
print("Dictionary with duplicates removed:", unique_dict)
