---
generator: doxide
---


# MemoryTrackingSettings

**struct MemoryTrackingSettings**



## Variables

| Name | Description |
| ---- | ----------- |
| [myShouldStoreStackTraces](#myShouldStoreStackTraces) | <summary> Enables storage of stack traces for all allocations. |
| [myShouldTrackAllAllocations](#myShouldTrackAllAllocations) | <summary> Enables tracking of all allocations, not just leaks. |

## Variable Details

### myShouldStoreStackTraces<a name="myShouldStoreStackTraces"></a>

!!! variable "bool myShouldStoreStackTraces"

    <summary>
    Enables storage of stack traces for all allocations. This comes at a significant performance cost, but makes it easier to track down memory leaks
    </summary>
    

### myShouldTrackAllAllocations<a name="myShouldTrackAllAllocations"></a>

!!! variable "bool myShouldTrackAllAllocations"

    <summary>
    Enables tracking of all allocations, not just leaks. Prints a summary of top allocation stack traces if myShouldStoreStackTraces is enabled.
    </summary>
    

