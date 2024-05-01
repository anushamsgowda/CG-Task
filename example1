import java.util.HashMap;
import java.util.Map;

public class TwoSum {
    public int[] twoSum(int[] nums, int target) {
        Map<Integer, Integer> numIndexMap = new HashMap<>();  // A map to store numbers and their indices
        for (int i = 0; i < nums.length; i++) {
            int remaining = target - nums[i];  // Calculate the remaining value
            if (numIndexMap.containsKey(remaining)) {
                // If the remaining value is in the map, return the indices
                return new int[]{numIndexMap.get(remaining), i};
            }
            numIndexMap.put(nums[i], i);  // Add the number and its index to the map
        }
        return null;  // Return null if no pair of numbers add up to the target
    }
}
