public int[] frontPiece(int[] nums) {
  int[] answerArray = new int[2];
  
  if (nums.length<2) {
  	return nums;
  }
  
  else{
	  for(int i = 0; i < 2; i++) {
 	 	answerArray[i] = nums[i];
 	 }
  }
  return answerArray;

}
