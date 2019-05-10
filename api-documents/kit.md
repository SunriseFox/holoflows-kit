<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@holoflows/kit](./kit.md)

## kit package

A toolkit for browser extension developing.

## Classes

|  Class | Description |
|  --- | --- |
|  [EventWatcher](./kit.eventwatcher.md) | A Watcher based on event handlers. |
|  [IntervalWatcher](./kit.intervalwatcher.md) | A watcher based on time interval. |
|  [LiveSelector](./kit.liveselector.md) | Create a live selector that can continuously select the element you want. |
|  [MessageCenter](./kit.messagecenter.md) | Send and receive messages in different contexts. |
|  [MutationObserverWatcher](./kit.mutationobserverwatcher.md) | A watcher based on MutationObserver |
|  [ValueRef](./kit.valueref.md) | A <code>ref</code> object with <code>addListener</code> |
|  [Watcher](./kit.watcher.md) | Use LiveSelector to watch dom change<!-- -->You need to implement <code>startWatch</code> |

## Functions

|  Function | Description |
|  --- | --- |
|  [AsyncCall(implementation, options)](./kit.asynccall.md) | Async call between different context. |
|  [AutomatedTabTask(taskImplements, options)](./kit.automatedtabtask.md) | Open a new page in the background, execute some task, then close it automatically. |
|  [DomProxy(options)](./kit.domproxy.md) | DomProxy provide an interface that be stable even dom is changed. |
|  [GetContext()](./kit.getcontext.md) | Get current running context. |
|  [OnlyRunInContext(context, name)](./kit.onlyrunincontext.md) | Make sure this file only run in wanted context |
|  [OnlyRunInContext(context, throws)](./kit.onlyrunincontext_1.md) |  |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [AsyncCallOptions](./kit.asynccalloptions.md) | Options for [AsyncCall()](./kit.asynccall.md) |
|  [AutomatedTabTaskDefineTimeOptions](./kit.automatedtabtaskdefinetimeoptions.md) | Define-time options for [AutomatedTabTask()](./kit.automatedtabtask.md) |
|  [AutomatedTabTaskRuntimeOptions](./kit.automatedtabtaskruntimeoptions.md) | Runtime options for [AutomatedTabTask()](./kit.automatedtabtask.md) |
|  [DomProxy](./kit.domproxy.md) | A DomProxy object |
|  [DomProxyOptions](./kit.domproxyoptions.md) | Options for DomProxy |
|  [Serialization](./kit.serialization.md) | Define how to do serialization and deserialization of remote procedure call |

## Variables

|  Variable | Description |
|  --- | --- |
|  [JSONSerialization](./kit.jsonserialization.md) | Serialization implementation by JSON.parse/stringify |
|  [NoSerialization](./kit.noserialization.md) | Serialization implementation that do nothing |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [Contexts](./kit.contexts.md) | All context that possible in when developing a WebExtension |
