class Solution {
public:
    int removeDuplicates(vector<int>& nums) {
        int k = 1;
        for (int i = 1; i < nums.size(); i++){
            if(nums[i] != nums[i-1]){
                nums[k] = nums[i];
                k++;
            }
        }
        return k;
    }
};
<img width="1057" height="871" alt="Screenshot 2026-03-23 202841" src="https://github.com/user-attachments/assets/83e6a71b-c383-46bb-9749-c327cef336f0" />
