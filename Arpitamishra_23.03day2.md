class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {int n = nums.size();
    for(int i=0; i<n ; i++){
        for(int j=i+1; j < n; j++){
            if( nums[i] + nums [j] == target){
                return {i,j};
            }
        }
    }
      return {};  
    }
};
<img width="1054" height="888" alt="image" src="https://github.com/user-attachments/assets/2d799e70-278e-4e16-a3d1-6adfa71a81bd" />
