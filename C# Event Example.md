

```ad-note
Example for how to create a C# event
```



```C#
//Inspectable.cs
public static event Action <bool> InspectablesInRangeChanged;


// InspectionPanel.cs
void OnEnable()  
{ 
 
 Inspectable.InspectablesInRangeChanged += UpdateHintTextState;  
}  
  
void OnDisable() => Inspectable.InspectablesInRangeChanged -= UpdateHintTextState;
``` 
 
 #CSharp #Unity3d #JasonCourse
 
