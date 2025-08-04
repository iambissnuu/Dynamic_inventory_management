# Dynamic Inventory Management System

This project is a partial implementation of a Dynamic Inventory Management System developed for the MSCS532 course. It demonstrates the use of key data structures in Python including hash tables, heaps, and AVL trees. The system allows adding products, retrieving items with the lowest stock, and sorting products by price.

## Project Files

- `product.py`: Defines the `Product` class which holds the ID, name, quantity, and price.
- `product_manager.py`: Manages all product records using a hash table (Python dictionary).
- `stock_heap.py`: Uses the `heapq` module to maintain a min-heap for low-stock tracking.
- `avl_tree.py`: Implements an AVL tree for sorting products based on price.
- `main.py`: Demonstrates functionality with a small number of manually added products.
- `simulate_large_dataset.py`: Generates and processes 1000 random products to test scalability.
- `test.py`: A placeholder for future unit tests.

## How to Run

To run the small demo with a few predefined products:

```bash
python main.py
