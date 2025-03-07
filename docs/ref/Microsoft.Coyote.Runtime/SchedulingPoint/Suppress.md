# SchedulingPoint.Suppress method

Suppresses interleavings during testing until [`Resume`](Resume.md) is invoked.

```csharp
public static void Suppress()
```

## Remarks

This method does not suppress interleavings that happen when an operation is waiting some other operation to complete, when an operation completes and the scheduler switches to a new operation, or interleavings from uncontrolled concurrency.

## See Also

* class [SchedulingPoint](../SchedulingPoint.md)
* namespace [Microsoft.Coyote.Runtime](../SchedulingPoint.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
