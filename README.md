# mergewithoutextraspace
void merge(vector<int>& nums1, int m, vector<int>& nums2, int n) {
        int p=nums1.size();
        for(int i=m;i<p;i++){
            nums1[i]=nums2[i-m];
        }
        sort(nums1.begin(),nums1.end());
        return ;
    }
