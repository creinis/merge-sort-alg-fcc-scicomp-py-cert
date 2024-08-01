# Merge Sort Algorithm

###### Technologies:
<p align="center">
<img src="https://img.icons8.com/color/75/000000/python.png" width="75" height="75" alt="Python" style="margin: 10px 15px 0 15px;" />
</p>

### Try it!

To run the Merge Sort Algorithm application, follow the instructions in the Setup section below.

## Project Structure

- `merge_sort.py`: Contains the implementation of the Merge Sort Algorithm function.

## Setup

### Prerequisites

- Python 3 installed

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/creinis/merge-sort-alg-fcc-scicomp-py-cert.git
   cd merge-sort-alg-fcc-scicomp-py-cert
   ```

2. Run the Merge Sort Algorithm script:
   ```bash
   python3 merge_sort.py
   ```

## Merge Sort Algorithm

### Functionality

The Merge Sort Algorithm is a divide-and-conquer sorting algorithm. It works by recursively splitting the array into smaller subarrays, sorting each subarray, and then merging the sorted subarrays to produce the final sorted array.

### Practical Use Case

The Merge Sort Algorithm is useful for sorting large datasets efficiently. It is stable and has a predictable time complexity of O(n log n), making it suitable for applications where performance is critical, such as database sorting, data analysis, and real-time systems.

### Benefits

- **Efficiency:** Sorts large datasets efficiently with a time complexity of O(n log n).
- **Stability:** Maintains the relative order of equal elements.
- **Divide-and-Conquer:** Utilizes a recursive approach to break down the problem and solve it step-by-step.
- **Python Standard Library:** Utilizes Python’s built-in data structures for implementation.

## How to Use

1. Run the `merge_sort.py` script:
   ```bash
   python3 merge_sort.py
   ```

2. The `merge_sort` function can be used to sort any list of numbers.

### Example Usage

```python
from merge_sort import merge_sort

# Define the array to be sorted
numbers = [4, 10, 6, 14, 2, 1, 8, 5]
print('Unsorted array:')
print(numbers)

# Sort the array using merge sort
merge_sort(numbers)
print('Sorted array:')
print(numbers)
```

### Example Output

```plaintext
Unsorted array:
[4, 10, 6, 14, 2, 1, 8, 5]
Sorted array:
[1, 2, 4, 5, 6, 8, 10, 14]
```

## Function Parameters

- `array`: The list of numbers to be sorted.

### Constraints

- The input list should contain comparable elements (e.g., all integers or all floats).

### Additional Information

- **Merge Process:** Combines two sorted subarrays into one sorted array by comparing elements and merging them in sorted order.

---
#### This is a FreeCodeCamp Challenge for Scientific Computing with Python Projects Certification.
<p align="center">
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg" width="250" height="75" alt="freeCodeCamp" style="margin: 0 15px; opacity: 0.6" />
</p>
