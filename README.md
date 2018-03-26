# slasher
Return the remaining elements of an array after chopping off n elements from the head.<br />
The head means the beginning of the array, or the zeroth index.<br />
slasher([1, 2, 3], 2) should return [3].<br />
slasher([1, 2, 3], 0) should return [1, 2, 3].<br />
slasher([1, 2, 3], 9) should return [].<br />
slasher([1, 2, 3], 4) should return [].<br />
slasher(["burgers", "fries", "shake"], 1) should return ["fries", "shake"].<br />
slasher([1, 2, "chicken", 3, "potatoes", "cheese", 4], 5) should return ["cheese", 4].<br />
