//# code
lass Solution {
public:
    int removeElement(vector<int>& nums, int val) {
         int k=0;
       for ( int i=0; i<nums.size(); i++){
        //vector<int > dd;
   
        if ( nums[i]!=val){
            //dd[i]=nums[i];
          nums[k]=nums[i];
          k++;
        }

       }
       return k;
    }
};
