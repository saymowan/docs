# Assert.GreaterOrEqual

**Assert.GreaterOrEqual** tests whether one object is greater than or equal to another.
Contrary to the normal order of Asserts, these methods are designed to be
read in the "natural" English-language or mathematical order. Thus
**Assert.GreaterOrEqual(x, y)** asserts that x is greater than or equal to y (x >= y).

```csharp
Assert.GreaterOrEqual(int arg1, int arg2);
Assert.GreaterOrEqual(int arg1, int arg2,
                      string message, params object[] params);

Assert.GreaterOrEqual(uint arg1, uint arg2);
Assert.GreaterOrEqual(uint arg1, uint arg2,
                      string message, params object[] params);

Assert.GreaterOrEqual(long arg1, long arg2);
Assert.GreaterOrEqual(long arg1, long arg2,
                      string message, params object[] params);

Assert.GreaterOrEqual(ulong arg1, ulong arg2);
Assert.GreaterOrEqual(ulong arg1, ulong arg2,
                      string message, params object[] params);

Assert.GreaterOrEqual(decimal arg1, decimal arg2);
Assert.GreaterOrEqual(decimal arg1, decimal arg2,
                      string message, params object[] params);

Assert.GreaterOrEqual(double arg1, double arg2);
Assert.GreaterOrEqual(double arg1, double arg2,
                      string message, params object[] params);

Assert.GreaterOrEqual(float arg1, float arg2);
Assert.GreaterOrEqual(float arg1, float arg2,
                      string message, params object[] params);

Assert.GreaterOrEqual(IComparable arg1, IComparable arg2);
Assert.GreaterOrEqual(IComparable arg1, IComparable arg2,
                      string message, params object[] params);
```

## See Also

* [Assert.Greater](Assert.Greater.md)
* [Assert.Less](Assert.Less.md)
* [Assert.LessOrEqual](Assert.LessOrEqual.md)
* [Comparison Constraints](xref:constraints#comparison-constraints)
