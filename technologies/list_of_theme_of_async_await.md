Список тем по async/await в .NET
---------------------------------------------------
Introduction  
Course agenda  
BenchmarkDotNet basics   
Demo: sharplab.io  
Demo: ConcurrencyVisualizer  
Demo: Parallel Stacks/Tasks  
Homework
    
2 Async basics  
Threads & Pools  
Task API  
Demo: ThreadPool use with diffrent API  
Demo: Task.Run and closure  
Async-await foundations  
Demo: which thread is it?  
Demo: Async WebAPI Controllers  
Fire and forget  
Demo: asynchronous logging  
Task eliding  
ValueTask  
Demo: optimizing asynchronous chains of calls  
Demo: asynchronous File API  
Homework  

3 Async II  
Execution, contexts, scheduler  
Demo: your own SynchronizationContext  
Demo: Scheduler Azure Durable Functions  
Sync vs async  
Demo: utilizing legacy synchronous APIs  
Demo: let’s deadlock it!  
TaskCompletionSource  
Demo: wrapping callback-based APIs (Event Asynchronous Pattern)  
Awaitables  
Demo: await await await false;  
Locals  
Demo: StringBuilder i ThreadLocal  
Demo: scopes with AsyncLocal  
Demo: floating the state  
Homework  


4 Async III  
Tasks aggregations  
Demo: awaiting in task completion order  
Demo: Parallel.For with async vs Task.WhenAll  
Demo: testing with TaskCompletionSource oraz Task.WhenAny  
Taks canellation with CancellationToken  
Demo: timeout with WhenAny  
IAsyncDiposable  
IAsyncEnumerable  
Demo: gRPC with IAsyncEnumerable  
Demo: New SQL client  
Homework  


5 Low-level concurrency  
Hardware  
volatile  
Demo: Epoch programming in ConcurrentQueue  
Interlocked  
Demo: simple pool with Interlocked.Exchange  
Barriers and alignment  
Demo: range reservation with Aeron.NET and Interlocked.CompareExchange  
Homework  

6 Concurrent - tools  
Exclusive locking  
Demo: decompiling lock  
Demo: non-blocking usage of Monitor.TryEnter  
Demo: task throttling with Task z SemaphoreSlim  
ReaderWriterLock  
Demo: Bbuilding custom string pool with ReaderWriterLock  
Wait handles  
Demo: consuming event once with AutoResetEvent  
Asynchronous primitives  
Demo: deadlock debugging  
Homework  

7 Concurrent Data Structures  
Foundations  
BlockingCollection  
Demo: BlockingCollection z CancellationToken  
ConcurrentStack  
Demo: object cache with ConcurrentStack  
ConcurrentQueue  
Demo: memory pool in Kestrel ASP.NET with ConcurrentQueue  
ConcurrentDictionary  
Demo: efficient caching with ConcurrentDictionary.GetOrAdd  
ConcurrentBag  
Homework  


8 New Concurrent Data Structures  
Channels  
Demo: bounded channels for metrics’ snapshots  
Pipelines  
Demo: Pipelines in ServiceStack.Redis with locking and ConcurrentQueue  
Homework  


9 Miscellaneous topics  
Demo: IValueTaskSource with Interlocked.CompareExchange  
Demo: IValueTaskSource based on an array with token discriminator  
ValueTask and pooling in .NET 5  
False Sharing  
F# async vs C# async  
Demo: Hosted services with IHostBuilder, IHostedService and ConcurrentQueue  
Demo: Observing thread contention in JetBrains Timeline  
PLINQ vs Parallel.ForEach and CPU/IO bound  
Homework  
