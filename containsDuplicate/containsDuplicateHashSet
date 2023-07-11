class Solution {
   public boolean containsDuplicate( int[] nums ) {
        HashSet< Integer > dup = new HashSet<>();
        for( int num : nums) {
            if( dup.contains( num )) {
                return true;
            }
            dup.add( num );
        }
        return false;
    }
}
