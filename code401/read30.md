# Read 30

## WHY

1. hold unique values
1. dictionary
1. library

## WHAT

Hashtables are a data structure that stores information. Everyone Node or Bucket has a *key/value* pair. When using hashtables, you want the ability to store the key into the data structure and retrieve the value. We use a hash to do this. Hash maps take advantage of an array's O(1) read access. It uses a hash function to place each item at a precise index location based off it's key. It takes the key and returns an integer. The integer determines where the key/value pair is placed.

**Terms**

- **Hash**: When an algorithm takes an incoming string and converts it into a value that can be used for security or another purpose. For hashtable, it is used to determine the index of the array.
- **Buckets**: What is contained in each index of the array of a hashtable. Each index is a bucket. It could potentially contain multiple key/value pairs if a collision occurs.
- **Collisions**: This happens when more than one key gets hashed to the same location of the hashtable.

## HOW

**Create a hash**: Create a hashtable by creating an array and following the correct steps of logic
- Add or multiply all the ASCII values.
- Multiply it by a prime number.
- Use modulo to get the remainder of the result, when divided by the total size of the array.
- Insert into the array at that index.

**Buckets**: Each index can hold multiple different values. Each index of the array has buckets. Each buckets has a key/value pair. When there is no entry in a bucket, then they start at null. Each bucket starts as empty. When a key generates a hashCode that corresponds with an index, then it is overwritten.

**Collisions**: Sometimes the key hashes to the same index in an array. A perfect hash will never have collisions. To solve a collision, you need to change the initial state of the buckets. You can initialize LinkedLists.

## Readings

- Read [Hashtables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
- Watch [What is a HashTable](https://www.youtube.com/watch?v=MfhjkfocRR0)
- Read [Basics of Hash Tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
- Skim [Hash table](https://en.wikipedia.org/wiki/Hash_table)

[<== Back](https://simoneodegard.github.io/reading-notes/)