# neetcode-150
neetcode-150

### Arrays & Hashing 07062022
- Contains duplicate
- Valid Anagram - Learnt about HashMap merging, where you add a remappingFunction to a hasmap.
  The Java HashMap merge() method inserts the specified key/value mapping to the hashmap if the specified key is already not present. If the specified key is already associated with a value, the method replaces the old value with the result of the specified function 
  
      hashmap.merge(key, value, remappingFunction)
Example

      hashmap.merge("key", 1, Integer::sum) - remapping function does a sum of existing value at key and the new vakue if the key is already found

