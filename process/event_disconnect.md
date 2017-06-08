<!-- YAML
added: v0.7.7
-->

如果Node.js进程是由IPC channel的方式创建的(详见 [Child Process][]
and [Cluster][] 文档)，当IPC channel关闭时，会触发`'disconnect'`事件。
