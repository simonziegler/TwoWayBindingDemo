# Two Way Binding Error Demo

Demonstrates how two way bindng fails for a component that calls `ValueChanged` from within the associated `Value` parameter's setter, and which also uses a cascading parameter. 
The erroneous behaviour occurs either wiht .NET 3.1 or .NET 5 Preview 7.
