# Python
import heapq

def find_kth_largest(nums: list, k: int) -> int:
    return heapq.nlargest(k, nums)[-1]
