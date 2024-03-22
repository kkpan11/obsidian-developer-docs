---
aliases: "Workspace.on('quit')"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`Workspace`](Workspace) › [on('quit')](Workspace/on('quit').md)

## Workspace.on('quit') method

Triggered when the app is about to quit. Not guaranteed to actually run. Perform some best effort cleanup here.

**Signature:**

```typescript
on(name: 'quit', callback: (tasks: Tasks) => any, ctx?: any): EventRef;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  <code>name</code> | <code>'quit'</code> |  |
|  <code>callback</code> | <code>(tasks: </code>[`Tasks`](Tasks)<code>) =&gt; any</code> |  |
|  <code>ctx</code> | <code>any</code> | _(Optional)_ |

**Returns:**

[`EventRef`](EventRef)
