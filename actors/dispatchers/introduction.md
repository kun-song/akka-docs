# Dispatchers

`MessageDispatcher` 是 Akka Actor 运行的发动机，所有 `MessageDispatcher` 实现同样也是 `ExecutionContext`，因此可用于执行任务，例如 `Future`s。
