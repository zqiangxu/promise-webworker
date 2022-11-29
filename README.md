# promise-webworker
WebWorker 支持 promise 通信

```
const worker = new PromiseWorker();

worker.postMessage({
    message: 'hello'
});
```