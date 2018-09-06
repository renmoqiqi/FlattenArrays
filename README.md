# FlattenArrays 数组降维

"""
Implement Flatten Arrays.
Given an array that may contain nested arrays,
produce a single resultant array.
"""
```
    NSArray *nestedArray = @[@[@"1", @"2"], @[@"1", @"2"]];

    NSArray *flattenedArray = [nestedArray valueForKeyPath: @"@unionOfArrays.self"];
    
 ```
 ```   
 Printing description of flattenedArray:
<__NSArrayM 0x600000454160>(
1,
2,
1,
2
)
 ```
 
 https://www.jianshu.com/p/2c2af5695904
 
