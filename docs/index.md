---
generator: doxide
---


# Unicorn Docs

Documentation for the Unicorn Game Engine

## Types

| Name | Description |
| ---- | ----------- |
| [UniqueID64](UniqueID64.md) |  |
| [Array3D](Array3D.md) |  |
| [Application](Application.md) |  |
| [MemoryTrackingSettings](MemoryTrackingSettings.md) |  |
| [DirectResourcePool](DirectResourcePool.md) |  |
| [ResourcePool](ResourcePool.md) |  |
| [EditorWindow](EditorWindow.md) |  |

## Functions

| Name | Description |
| ---- | ----------- |
| [AddUniqueToVector](#AddUniqueToVector) | <summary> Adds element to the back of the vector </summary> <returns> TRUE if value was not already in the vector. |
| [EraseItemFromVector](#EraseItemFromVector) | <summary> Removes item from a vector </summary> <returns> TRUE if item was found and removed FALSE if item was not found in the vector </returns>  |
| [StartMemoryTracking](#StartMemoryTracking) | <summary> Keeps track of memory allocations and deallocations when compiled with _DEBUG (normally defined in Debug). |

## Function Details

### AddUniqueToVector<a name="AddUniqueToVector"></a>
!!! function "template&lt;typename T&gt; inline bool AddUniqueToVector(Vector&lt;T&gt;&amp; Vector, T&amp; Item)"

    <summary>
    Adds element to the back of the vector
    </summary>
    <returns>
    TRUE if value was not already in the vector.
    FALSE if value already exists
    </returns>
    

### EraseItemFromVector<a name="EraseItemFromVector"></a>
!!! function "template&lt;typename T&gt; inline bool EraseItemFromVector(Vector&lt;T&gt;&amp; Vector, T&amp; Item)"

    <summary>
    Removes item from a vector
    </summary>
    <returns>
    TRUE if item was found and removed
    FALSE if item was not found in the vector
    </returns>
    

### StartMemoryTracking<a name="StartMemoryTracking"></a>
!!! function "void StartMemoryTracking(const MemoryTrackingSettings&amp; trackingSettings)"

    <summary>
    Keeps track of memory allocations and deallocations when compiled with _DEBUG (normally defined in Debug).
    By default only leaks are tracked and stack traces are not stored.
    </summary>
    <param name="trackingSettings">
    </param>
    

