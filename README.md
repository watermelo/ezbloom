# ezbloom

### 基于内存的简易布隆过滤器 


```python
ez = EzBloom(cap=100, fail_rate=0.001)
ez.add('wtf')
ez.is_contain('wtf')
```

根据cap fail_rate自动计算bit_size hash_count 计算参考算法[Bloom_filter]

[Bloom_filter]: https://en.wikipedia.org/wiki/Bloom_filter#Probability_of_false_positives 