# Swift Reduce Function Unexpected Behavior

This repository demonstrates a common error encountered when using the `reduce` function in Swift. The example shows how using the addition operator (+) directly with `reduce` can lead to unexpected results if the input array contains non-numeric values.

The `bug.swift` file contains the erroneous code, while `bugSolution.swift` offers a corrected version.

## How to Reproduce

1. Clone this repository.
2. Open `bug.swift` in Xcode or a Swift compatible editor.
3. Run the code. You'll observe that the output is not as expected.
4. Open `bugSolution.swift` to see the corrected version.