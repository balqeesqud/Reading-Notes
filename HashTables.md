
# Hash Tables

## Structure: Why, What, How

### **Why are Hash Tables Important?**

Hash tables are an essential data structure in computer science and have a wide range of applications due to their 
efficiency in data retrieval and storage. Here's why they are important:
  - Fast Data Retrieval: Allow for near-constant time data retrieval. This means you can access data quickly 
    regardless of the size of the dataset. This is crucial in various applications like databases, and caches.
  - Distributed Databases: Are used in distributed systems to quickly locate data across multiple servers. 
    The hashing function is used to determine which server should store or retrieve the data.
  - Dictionaries and Symbol Tables: Are fundamental in implementing dictionaries and symbol tables in programming languages. They provide a way to associate keys with values efficiently.
  - Caching: Caches in computer systems often use hash tables to store frequently accessed data, reducing the time
    it takes to fetch information from slower storage.
  - Security: Cryptographic hash functions, a specific type of hash function, are used in various security applications
    like digital signatures, password hashing, and data integrity verification.

### **What are Hash Tables?**

Is a data structure that uses a hash function to map keys to values. It stores data in an array-like structure, 
where each data element has a unique key. 
 - Hash Function: The heart of a hash table is the hash function. It takes an input (or key) and returns an index in
   the array where the corresponding value is stored. The hash function should provide a uniform distribution to 
   minimize collisions.
 - Collisions: Collisions occur when two different keys map to the same index in the array. Hash tables must have a 
   strategy to handle collisions, like chaining (each index stores a linked list of values).
 - Efficient Operations: Hash tables provide fast operations for data retrieval, insertion, and deletion. 
   On average, these operations take O(1) time, making them incredibly efficient.

### **How Do Hash Tables Work?**

An example of how a hash table works:

Imagine we have a hash table that stores the population of different cities. The **city names** are the **keys**, and
the **populations** are the **values**. Here's how it works:

1. Hash Function: When I want to look up the population of a city, I pass the city name through a hash function.
   The hash function, lets say, converts the characters of the city name into a numerical value and returns an index.
2. Index: The index is used to access a specific location in the hash table array. If the hash function is good,
   different city names should ideally result in different indices.
3. Data Retrieval: You can quickly retrieve the population of a city by accessing the array at the determined index.
   This is a fast and efficient process.
4. Handling Collisions: In case two cities end up with the same index due to the hash function, the hash table has 
   mechanisms (like chaining or open addressing) to store multiple values at the same index.

In summary, hash tables are important because they offer fast data retrieval, and they achieve this through a hash 
function that maps keys to unique indices in an array-like structure. When collisions occur, they have strategies to 
handle them efficiently, making them a fundamental data structure in computer science.