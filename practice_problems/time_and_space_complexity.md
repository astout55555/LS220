# Q1

```javascript
function test(n) {
  for (let i = 0; i < n; i++) {
    console.log("Hello!");
  }
}
```

Time complexity: O(N)

Space complexity: O(1) [size of the number doesn't change memory requirements]

# Q2

```javascript
function test(n) {
  for (let i = 0; i < n; i++) {
    for (let j = i; j < n; j++) {
      console.log("Hello!");
    }
  }
}
```

Time complexity: O(N^2)

Space complexity: O(1)

# Q3

```javascript
function test(n) {
  let result = [];
  for (let i = 0; i < n; i++) {
    result.push(i);
  }
  return result;
}
```

Time complexity: O(N)

Space complexity: O(N)

# Q4

```javascript
function test(n) {
  let sum = 0;
  for (let i = 1; i <= n; i++) {
    for (let j = 1; j <= i; j++) {
      sum += 1;
    }
  }
  return sum;
}
```

Time complexity: O(N^2)

Space complexity: O(1)

# Q5

```javascript
function test(n) {
  let result = [];
  for (let i = 0; i < n; i++) {
    result.push(i);
    for (let j = 0; j < n; j++) {
      result[i] += j;
    }
  }
  return result;
}
```

Time complexity: O(N^2)

Space complexity: O(N)

# Q6

```javascript
function test(n) {
  for (let i = 0; i < n; i++) {
    for (let j = 0; j < n; j++) {
      for (let k = 0; k < n; k++) {
        console.log("Hello!");
      }
    }
  }
}
```

Time complexity: O(N^3)

Space complexity: O(1)

# Q7

```javascript
function test(n) {
  let result = [];
  for (let i = 0; i < n; i++) {
    result.push(new Array(n).fill(0));
  }
  return result;
}
```

Time complexity: O(N^2)

Space complexity: O(N^2)

# Q8

```javascript
function test(n) {
  for (let i = n; i >= 1; i /= 2) {
    console.log("Hello!");
  }
}
```

Time complexity: O(logN)

Space complexity: O(1)

# Q9

```javascript
function test(n) {
  let matrix = [];
  for (let i = 0; i < n; i++) {
    matrix[i] = [];
    for (let j = 0; j < n; j++) {
      matrix[i][j] = i + j;
    }
  }
  return matrix;
}
```

Time complexity: O(N^2)

Space complexity: O(N^2)

# Q10

```javascript
function test(n) {
  for (let i = 0; i < n; i++) {
    for (let j = 1; j < n; j *= 2) {
      console.log("Hello!");
    }
  }
}
```

Time complexity: O(NlogN)

Space complexity: O(1)

# Q11

```javascript
function test(n) {
  for (let i = 0; i < n; i++) {
    for (let j = 0; j < 100; j++) {
      console.log("Hello!");
    }
  }
}
```

Time complexity: O(N)

Space complexity: O(1)

# Q12

```javascript
function test(n, m) {
  for (let i = 0; i < n; i++) {
    console.log("Hello!");
  }
  for (let j = 0; j < m; j++) {
    console.log("World!");
  }
}
```

Time complexity: O(N) + O(M)

Space complexity: O(1)

# Q13

```javascript
function test(n) {
  for (let i = 0; i < 2 * n; i++) {
    console.log("Hello!");
  }
}
```

Time complexity: O(N)

Space complexity: O(1)

# Q14

```javascript
function test(n) {
  let count = 0;
  for (let i = n; i > 0; i /= 2) {
    for (let j = 0; j < n; j++) {
      count++;
    }
  }
  return count;
}
```

Time complexity: O(NlogN)

Space complexity: O(1)
