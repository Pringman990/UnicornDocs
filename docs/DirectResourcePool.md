---
generator: doxide
---


# DirectResourcePool

**template&lt;typename T&gt; class DirectResourcePool**

Resource pool with direct pointer access to the resource.


## Functions

| Name | Description |
| ---- | ----------- |
| [Clear](#Clear) | Deletes all resources in this pool. |

## Function Details

### Clear<a name="Clear"></a>
!!! function "template&lt;typename Fn, typename... Args&gt; void Clear(Fn OnRemove, Args&amp;&amp;... args)"

    Deletes all resources in this pool.
    
    
    :material-code-tags: `OnRemove`
    :    Remove function for specialized deletion of resource.
        
    :material-code-tags: `Args`
    :    If the OnRemove function needs to take in arguments.
    

