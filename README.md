## RSA Factoring Challenge

## Task 0: RSA Factoring Challenge

### Overview:
The RSA Factoring Challenge involves finding prime numbers \( p \) and \( q \) for a given RSA number \( n \) such that \( n = p \times q \). The goal is to factorize \( n \) into its prime components.

### Implementation (Task 0):
- **Script Name:** `factors`
- **Usage:** `./factors <file>` (where `<file>` contains natural numbers to factor, one per line)
- **Output Format:** `n=p*q` (one factorization per line, \( p \) and \( q \) don't have to be prime numbers)

### Example:
```bash
./factors tests/test00
```
Output:
```plaintext
4=2*2
12=6*2
34=17*2
128=64*2
1024=512*2
4958=2479*2
1718944270642558716715=343788854128511743343*5
9=3*3
99=33*3
999=333*3
9999=3333*3
9797973=3265991*3
49=7*7
239809320265259=15485783*15485773
```

### Execution Time:
```plaintext
real    0m0.009s
user    0m0.008s
sys 0m0.001s
```

## Task 1: RSA Factoring Challenge (Prime Numbers)

### Overview:
Task 1 extends Task 0, but with the added constraint that \( p \) and \( q \) must be prime numbers. This makes the factorization more challenging.

### Implementation (Task 1):
- **Script Name:** `rsa`
- **Usage:** `./rsa <file>` (where `<file>` contains RSA numbers to factor, one per line)
- **Output Format:** `n=p*q` (one factorization per line, \( p \) and \( q \) must be prime numbers)

### Example:
```bash
./rsa tests/rsa-1
```
Output:
```plaintext
6=3*2
```

```bash
./rsa tests/rsa-2
```
Output:
```plaintext
77=11*7
```

### Execution Time:
```plaintext
real    0m0.009s
user    0m0.008s
sys 0m0.001s
```

These scripts aim to efficiently factorize RSA numbers, with Task 1 requiring prime numbers \( p \) and \( q \). The execution times are optimized to complete within 5 seconds, providing a balance between efficiency and accuracy.