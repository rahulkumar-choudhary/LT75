## List of Data Structures

| Data Structure  | Operations                                                                           |
| --------------- | ------------------------------------------------------------------------------------ |
| `HashSet`       | `add`, `contains`, `remove`, `size`, `clear`                                         |
| `LinkedList`    | `add`, `addFirst`, `addLast`, `removeFirst`, `removeLast`, `get`, `contains`, `size` |
| `String`        | `length`, `charAt`, `substring`, `equals`, `indexOf`, `split`                        |
| `ArrayList`     | `add`, `get`, `set`, `remove`, `contains`, `size`, `clear`                           |
| `HashMap`       | `put`, `get`, `containsKey`, `remove`, `keySet`, `values`                            |
| `PriorityQueue` | `offer`, `poll`, `peek`, `size`, `clear`                                             |
| `ArrayDeque`    | `addFirst`, `addLast`, `removeFirst`, `removeLast`, `peekFirst`, `peekLast`          |
| `TreeSet`       | `add`, `remove`, `first`, `last`, `contains`                                         |
| `LinkedHashMap` | `put`, `get`, `containsKey`, `remove`                                                |
| `Stack` | `pop`, `peek`, `push(a)`, `size`, `isEmpty` | 

---
#### 1. `HashSet` : stores unique elements.

```
Set<Integer> set1 = new HashSet<>();
```

1. `add(element)` : Adds an element.

   * Returns: true if added, false if already present.
2. `contains(element)` : Checks if an element is in the set.

   * Returns: true or false.
3. `remove(element)` : Removes an element.

   * Returns: true if removed, false if not found.

* `size()` : Returns the number of elements.
* `clear()` : Removes all elements.

---

#### 2. `LinkedList` : dynamic list & deque.

```
LinkedList<Integer> list = new LinkedList<>();
```

1. `add(element)` : Adds element to end.
2. `addFirst(element)` : Adds element at start.
3. `addLast(element)` : Adds element at end.
4. `removeFirst()` : Removes first element.
5. `removeLast()` : Removes last element.
6. `get(index)` : Gets element at index.
7. `contains(element)` : Checks for a value.

* `size()` : Returns count.
* `clear()` : Clears list.

---

#### 3. `String` : immutable text.

```
String s = "example";
```

1. `length()` : Number of characters.
2. `charAt(index)` : Character at position.
3. `substring(start, end)` : Returns substring.
4. `equals(other)` : Checks string equality.
5. `indexOf(ch)` : First index of char/substring.
6. `split(delimiter)` : Splits into array.

---

#### 4. `ArrayList` : dynamic array.

```
ArrayList<Integer> arr = new ArrayList<>();
```

1. `add(element)` : Adds element at end.
2. `add(index, element)` : Inserts at index.
3. `get(index)` : Gets element at index.
4. `set(index, element)` : Replaces element.
5. `remove(index)` : Removes element by index.
6. `contains(element)` : Checks presence.

* `size()` : Returns current size.
* `clear()` : Removes all elements.

---

#### 5. `HashMap` : key-value pairs.

```
HashMap<String, Integer> map = new HashMap<>();
```

1. `put(key, value)` : Inserts or updates a key.
2. `get(key)` : Retrieves value or null.
3. `containsKey(key)` : Checks if key exists.
4. `remove(key)` : Removes entry.

* `keySet()` : All stored keys.
* `values()` : All stored values.

---

#### 6. `PriorityQueue` : heap queue.

```
PriorityQueue<Integer> pq = new PriorityQueue<>();
```

1. `offer(element)` : Adds element.
2. `poll()` : Removes and returns head (smallest default).
3. `peek()` : Returns head without removing.

* `size()` : Number of elements.
* `clear()` : Clears all.

---

#### 7. `ArrayDeque` : double-ended queue.

```
ArrayDeque<Integer> dq = new ArrayDeque<>();
```

1. `addFirst(elem)` : Add at front.
2. `addLast(elem)` : Add at end.
3. `removeFirst()` : Remove first.
4. `removeLast()` : Remove last.
5. `peekFirst()` : View first.
6. `peekLast()` : View last.

---

#### 8. `TreeSet` : sorted unique set.

```
TreeSet<Integer> tree = new TreeSet<>();
```

1. `add(elem)` : Adds in sorted order.
2. `remove(elem)` : Removes element.
3. `first()` : Smallest element.
4. `last()` : Largest element.
5. `contains(elem)` : Checks presence.

---

#### 9. `LinkedHashMap` : ordered map.

```
LinkedHashMap<String, Integer> lhm = new LinkedHashMap<>();
```

1. `put(key, value)` : Adds key in insertion order.
2. `get(key)` : Retrieves value.
3. `containsKey(key)` : Checks key.
4. `remove(key)` : Deletes entry.

* Maintains insertion order of keys.

---

#### 10. `Stack`: FILO.

```
Stack<Integer> stack = new Stack<>();
// use while loop to perform comparisons.
```

1. `pop()` : removes the last element.
2. `peek()` : return the value of the last element but does not remove it. 
3. `push(a)` : appends the `a` value.
4. `suze()`
5. `isEmpty` 

---


> Note: This concise cheat-sheet for the most common methods need for typical Interview/LeetCode 75 problems. Expand it further as you practice more problems.

[1]: https://www.geeksforgeeks.org/java/java-collection-tutorial/?utm_source=chatgpt.com "Java Collections Tutorial"
[2]: https://www.w3schools.com/java/java_collections.asp?utm_source=chatgpt.com "Java Collections Framework"
