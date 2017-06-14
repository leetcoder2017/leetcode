---
layout: post
title:  Hamming Distance
date:   2017-06-13 21:24:00 +0800
---

| Time Complexity | Space Complexity |
|:----------------|:-----------------|
| O(n)            | O(1)             |

```c++
int hammingDistance(int x, int y) {
	int cnt = 0;
	int v = x^y;
	while (v) {
		cnt += v & 1;
		v >>= 1;
	}
	return cnt;
}
```

Comment:
Shifting the XOR value is more efficient than shifting the bit mask.