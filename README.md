# Write-a-Python-program-to-count-the-number-of-elements-in-a-list-within-a-specified-range.

def range_count(l,min,max):
    count = 0
    for i in l:
        if min <= i <= max:
            count += 1
    return count

l = list(range(1,20))
print(range_count(l,12,18))
