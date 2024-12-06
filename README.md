# Priority Queue on Key-Value Data Using Heap Data Structure

This project implements a priority queue using a heap data structure to handle key-value data stored in a text file. The program supports operations like building a max-heap based on the value field, retrieving the k-th largest value, sorting elements, and efficiently retrieving the top k elements under a limited memory budget.

## Operations Implemented

### 1. Build a Max Heap
- **Objective**: Build a max heap from the input data based on the values (numerical field). The heap structure allows efficient retrieval of the maximum value.

### 2. Get the Key for the k-th Largest Value
- **Objective**: Given a number `k`, return the key associated with the k-th largest value in the dataset.

### 3. Sort Elements by Value
- **Objective**: Sort the key-value pairs in descending order of their values.

### 4. Retrieve Top k Elements Under Memory Constraint
- **Objective**: Retrieve the top k elements based on their values, using a heap of size no more than `k`. This operation simulates a limited memory scenario.

## File Format
The data is stored in a text file `data-2col.txt` with two columns:
- **Column 1**: Key (string)
- **Column 2**: Value (numerical)

## Requirements
- Python 3.x

## Installation

Clone the repository:

```bash
git clone https://github.com/Krishna737Sharma/priority-queue-heap.git
cd priority-queue-heap
