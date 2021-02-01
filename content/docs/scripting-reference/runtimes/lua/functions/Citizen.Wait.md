---
title: Citizen.Wait
---

This will "pause" the execution of the current thread for miliseconds amount of time.

Syntax
------

```lua
Citizen.Wait(int milliseconds)
```

### Required arguments
- **milliseconds**: The amount of milliseconds to pause the current thread.

Examples
--------

```lua
Citizen.CreateThread(function()
  while true do
    Citizen.Wait(100) -- Waits 100 milliseconds
  end
end)
```
