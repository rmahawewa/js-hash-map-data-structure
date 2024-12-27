# js-hash-map-data-structure
https://www.theodinproject.com/lessons/javascript-hashmap-data-structure



# Lesson overview

# Hash codes and how to generate them
# Hash maps and how they work internally

# Hashing is very good for security






# Bucket concept

```
Buckets are storage that we need to store our elements.
Example: John Smith store in a bucket
Pass John in to the hash function and get the value
Find the bucket with the value 
Store John as the Key and Smith as the Value in the specified bucket
```

# Collisions

```
When two entries get same hash code there will be a collision.
To avoid collitions developers should know when to grow the bucket size
Hence 'Capasity' and 'Load factor' concepts comes to front
Capasity - means the total number of buckets we currently have
Load factor - is a number we assigned to the hash map at start. This factor convays the time to extend the number of buckets

```