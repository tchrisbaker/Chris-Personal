Using [[Linq]] to sort objects by distance
```C#
// uses System.Linq
  `hits = hits.OrderBy(`
  `x => Vector2.Distance(this.transform.position,x.transform.position)`
  `).ToList();`
  ```
  
  #Unity3d #CSharp 