# ezcoinflip
function coinflip() {
    /**
     * This function simulates a coin flip and returns the result.
     * 
     * Returns:
     * string: The result of the coin flip, either "Heads" or "Tails".
     */
    
    try {
        // Generate a random number between 0 and 1
        const random = Math.random();
        
        // Determine the result based on the random number
        if (random < 0.5) {
            return "Heads";
        } else {
            return "Tails";
        }
    } catch (error) {
        // Log any errors that occur
        console.error("An error occurred:", error);
        return null;
    }
}
