# PHP Type Juggling Bug
This repository demonstrates a common error in PHP: type juggling during array summation.  When an array contains a mix of numeric and string values, PHP's loose typing can lead to unexpected behavior.  The `calculateSum` function incorrectly handles the string '4', concatenating it instead of adding its numerical value.  The solution demonstrates how to strictly type-check array elements to avoid this issue.

## How to Reproduce
1. Clone this repository.
2. Run `php bug.php`. Observe the unexpected output.
3. Run `php bugSolution.php`. Observe the corrected output.