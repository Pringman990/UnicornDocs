---
generator: doxide
---


# Global

Global functions and variables.

## Functions

| Name | Description |
| ---- | ----------- |
| [AddUniqueToVector](#AddUniqueToVector) | Adds element to the back of the vector. |
| [EraseItemFromVector](#EraseItemFromVector) | Removes item from a vector. |
| [RandomFloat](#RandomFloat) | Gives a random float between min and max. |
| [RandomInt](#RandomInt) | Gives a random int32 between min and max. |
| [StringToWString](#StringToWString) | Converts a std::string to std::wstring.  |
| [WStringToString](#WStringToString) | Converts a std::wstring to std::string.  |

## Function Details

### AddUniqueToVector<a name="AddUniqueToVector"></a>
!!! function "template&lt;typename T&gt; inline bool AddUniqueToVector(Vector&lt;T&gt;&amp; Vector, T&amp; Item)"

    Adds element to the back of the vector.
    
    
    :material-keyboard-return: **Return**
    :    If value was not already in the vector.
    

### EraseItemFromVector<a name="EraseItemFromVector"></a>
!!! function "template&lt;typename T&gt; inline bool EraseItemFromVector(Vector&lt;T&gt;&amp; Vector, T&amp; Item)"

    Removes item from a vector.
    
    
    :material-keyboard-return: **Return**
    :    If item was found and removed.
    

### RandomFloat<a name="RandomFloat"></a>
!!! function "inline float RandomFloat(float Min, float Max)"

    Gives a random float between min and max.
    

### RandomInt<a name="RandomInt"></a>
!!! function "inline int32 RandomInt(int32 Min, int32 Max)"

    Gives a random int32 between min and max.
    

### StringToWString<a name="StringToWString"></a>
!!! function "inline std::wstring StringToWString(const String&amp; String)"

    Converts a std::string to std::wstring.
    

### WStringToString<a name="WStringToString"></a>
!!! function "inline String WStringToString(const std::wstring&amp; WideString)"

    Converts a std::wstring to std::string.
    

