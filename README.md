# Leetcode-BinarySearch-4-Lines-ONLY
import java.util.Arrays;
class Solution {
    public int search(int[] nums, int target) {
        Arrays.sort(nums);
        if(Arrays.binarySearch(nums, target)<-1){
            return -1;
        }
        else{
        return Arrays.binarySearch(nums,target);
        }
    }
}
