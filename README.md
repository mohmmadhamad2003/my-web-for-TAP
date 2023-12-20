function twoSum(nums, target) {
    const numIndexMap = {};

    for (let i = 0; i < nums.length; i++) {
        const complement = target - nums[i];

        if (numIndexMap.hasOwnProperty(complement)) {
            return [numIndexMap[complement], i];
        }

        numIndexMap[nums[i]] = i;
    }
}

const nums = [2, 7, 11, 15];
const target = 9;
const result = twoSum(nums, target);
console.log(result);


