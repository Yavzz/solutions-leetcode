int* twoSum(int* nums, int numsSize, int target, int* returnSize) {
   
    int* inds = (int*) malloc(2* sizeof(int));

    *returnSize = 2;
    for (int i = 0; i < (numsSize-1); i++) {
        for (int a = i+1; a <numsSize; a++) {
            if (nums[i] + nums[a] == target) {
                inds[0] = i;
                inds[1] = a;
                break;

            }
        }
    }
     return inds;
}
